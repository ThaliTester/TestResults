#### Test 60124347d4f5b03_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
D/TimaKeyStoreProvider(10978): TimaSignature is unavailable
D/ActivityThread(10978): Added TimaKeyStore provider
V/dalvik-internals(10868): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals(10868): hooked signal using trap ()
V/dalvik-internals(10868): hooked sysv_signal using trap ()
V/dalvik-internals(10868): hooked bsd_signal using trap ()
V/dalvik-internals(10868): hooked sigaction using jump ()
V/dalvik-internals(10868): hooked _ZN3art6mirror5Class19FindInterfaceMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals(10868): hooked _ZN3art6mirror5Class25FindDeclaredVirtualMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals(10868): hooked _ZN3art6mirror5Class17FindVirtualMethodEPKNS0_8DexCacheEj using jump ()
D/DexLibLoader(10868): patched ART 5.0.x miranda bug
V/DexLibLoader(10868): opening dex store /data/data/com.facebook.katana/dex
V/DexLibLoader(10868): Secondary program dex metadata: [.root_relative]
V/DexLibLoader(10868): Secondary program dex metadata: [.locators]
V/DexLibLoader(10868): Secondary program dex metadata: [classes2.dex 102b05d6536f178eac593d7d65578de2ddd6825a secondary.dex01.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes3.dex 857a97620767f7e63fa9c0527067cd6c7a002041 secondary.dex02.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes4.dex 9935231bfc9137654b613e0c3ad23e5d3c069eb5 secondary.dex03.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes5.dex 08fa37bfdbdd915e303997b9b9eee7d09b51c215 secondary.dex04.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes6.dex 82b91dbe59da3b655a867a417fbb83d9fc617838 secondary.dex05.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes7.dex a8a078ec908ddaee0545b2315081ac33b68f213a secondary.dex06.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes8.dex 294c9ad6031509e29eb40eb619940d45eeb3c245 secondary.dex07.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes9.dex 43850a0126da4bbcbaf22e20c7357a75cf3a71aa secondary.dex08.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes10.dex 3c65d9974656bb0f434d5d9e03c6534a2f64b58a secondary.dex09.Canary]
V/DexLibLoader(10868): Secondary program dex metadata: [classes11.dex 5501f6915e13d4353ae2cf4cb583284b418d46c4 secondary.dex10.Canary]
E/Zygote  (10999): MountEmulatedStorage()
E/Zygote  (10999): v2
I/SELinux (10999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
--------- beginning of system
I/libpersona(10999): KNOX_SDCARD checking this for 10102
I/libpersona(10999): KNOX_SDCARD not a persona
I/SELinux (10999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3513): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/com.sec.android.app.automotive.carmode.framework.manager.update.UpdateManagerReceiver: pid=10999 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
D/Compatibility(10942): onHandleIntent()
D/Compatibility(10942): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10681, android.intent.extra.user_handle=0}]
I/ActivityManager( 3513): Killing 10247:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
D/Compatibility(10942): found: 2
D/TimaKeyStoreProvider(10999): TimaSignature is unavailable
D/ActivityThread(10999): Added TimaKeyStore provider
D/Compatibility(10942): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10942): skipping ResolveInfo{5e5fadd com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10942): considering ResolveInfo{39495652 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10942): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/ResourcesManager(10978): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
D/Compatibility(10942): enabling receiver ResolveInfo{11f2ed23 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ResourcesManager(10978): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility(10942): enabling receiver ResolveInfo{34c1d220 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ResourcesManager(10962): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
D/Compatibility(10942): enabling receiver ResolveInfo{294c67d9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/ResourcesManager(10962): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10962): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/Compatibility(10942): enabling receiver ResolveInfo{802859e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/UpdateIcingCorporaServi( 4041): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility(10942): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ResourcesManager(10999): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
I/ActivityManager( 3513): Killing 10263:com.sec.knox.bridge/1000 (adj 13): bgCount ##31
V/DexLibLoader(10868): read status:9 check:faceb007faceb00e
I/OMACP   (10978): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
V/DexLibLoader(10868): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader(10868): verified deps file
I/DexLibLoader(10868): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
V/MultiDexClassLoader(10868): installing MultiDexClassLoader before application classloader
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(10999): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
D/MultiDexClassLoader(10868): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10868): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader(10868): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10868): Setup multi dex took 0 ms.
V/DexLibLoader(10868): optimization needed: no
E/Zygote  (11023): MountEmulatedStorage()
E/Zygote  (11023): v2
D/MemoryReductionHack(10868): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
I/SELinux (11023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/libpersona(11023): KNOX_SDCARD checking this for 1000
I/libpersona(11023): KNOX_SDCARD not a persona
,D/Mms/Omacp(10782): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/SELinux (11023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/PerformanceUtils(10782): link cahcing start
I/ActivityManager( 3513): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=11023 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/Mms/ArtClassLoader(10782): init before art
D/Mms/ArtClassLoader(10782): init [DONE] art
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
D/TimaKeyStoreProvider(11023): TimaSignature is unavailable
D/ActivityThread(11023): Added TimaKeyStore provider
D/ResourcesManager( 4041): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   (10978): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/ResourcesManager(11023): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/Mms/PerformanceUtils(10782): link cahcing done
E/[CarMode](10999): [DLApplication]-onCreate: Applicatino Started!
I/GMPM    (10868): App measurement is starting up
D/SampleAppCoreManager(10999): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(10999): mContext is not null
W/ContextImpl(11023): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2994 
I/VlingoAndroidCore(10999): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
E/GMPM    (10868): getGoogleAppId failed with status: 10
I/ActivityManager( 3513): Killing 10278:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##31
E/GMPM    (10868): Uploading is not possible. App measurement disabled
I/UpdateIcingCorporaServi( 4041): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
I/SL_DEBUG(10962): isLoggable:: isProductShip = 1
I/SL_DEBUG(10962): isLoggable:: SL_DEBUG_EXIST = false
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/Zygote  (11059): MountEmulatedStorage()
I/libpersona(11059): KNOX_SDCARD checking this for 10034
E/Zygote  (11059): v2
I/libpersona(11059): KNOX_SDCARD not a persona
I/SELinux (11059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11059): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3513): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=11059 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider(11059): TimaSignature is unavailable
D/ActivityThread(11059): Added TimaKeyStore provider
D/ResourcesManager( 8882): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/StaticBindingVerifier(10868): Verify
D/ResourcesManager(11059): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10962): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10962): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
V/Transcoder(10962): Transcoder(0xb3c32560)::constructor
V/Transcoder(10962): addObitRecipient
V/TMI-JNI (10962): Mobile Transcoder JNI version 1.6.0/20131120/4.4
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
I/System.out(11059): Inside WakeupProvider
E/Zygote  (11083): MountEmulatedStorage()
I/libpersona(11083): KNOX_SDCARD checking this for 10045
E/Zygote  (11083): v2
I/libpersona(11083): KNOX_SDCARD not a persona
I/SELinux (11083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3513): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=11083 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11083): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/DatabaseUtils(11059): Writing exception to parcel
E/DatabaseUtils(11059): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(11059): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(11059): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(11059): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(11059): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(11059): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(11059): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(11059): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(11059): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(11059): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(11059): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(10999): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(10999): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10999): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(10999): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10999): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10999): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10999): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10999): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10999): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10999): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(10999): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(10999): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(10999): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(10999): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(10999): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(10999): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10999): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(10999): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10999): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10999): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10999): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10999): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10999): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10999): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10999): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10999): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils(11059): Writing exception to parcel
E/DatabaseUtils(11059): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(11059): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(11059): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(11059): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(11059): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(11059): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(11059): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(11059): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(11059): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(11059): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(11059): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(10999): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(10999): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10999): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(10999): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10999): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10999): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10999): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10999): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10999): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10999): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(10999): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(10999): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(10999): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(10999): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10999): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(10999): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10999): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10999): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10999): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10999): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10999): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10999): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10999): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10999): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode](10999): [DLApplication]-Init Called!:false
W/[CarMode](10999): [CommonUtil]-=========================================
W/[CarMode](10999): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](10999): [CommonUtil]-=========================================
E/[CarMode](10999): [DLApplication]-Init Started!:true
I/[CarModeFW](10999): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](10999): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](10999): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](10999): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](10999): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](10999): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](10999): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](10999): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](10999): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](10999): ### android.os.Looper::loop(145)
I/[CarModeFW](10999): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](10999): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](10999): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](10999): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication(11059): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
D/TimaKeyStoreProvider(11083): TimaSignature is unavailable
D/ActivityThread(11083): Added TimaKeyStore provider
I/ActivityManager( 3513): Killing 10293:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
D/ResourcesManager(11083): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
I/VlingoAndroidCore(11059): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
I/MessageDataHandler(10999): initialize
D/[CarModeFW](10999): CDH-initiazlieCaches : before sync
D/[CarModeFW](10999): CDH-initiazlieCaches : after sync
D/[CarModeFW](10999): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW](10999): CDH-ContactDataHandler initiazlieCaches time : 16
D/[CarModeFW](10999): CDH-initiazlieCaches : end sync
D/AndroidRuntime(11055): 
D/AndroidRuntime(11055): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/[CarModeFW](10999): DrivingManager-initialize...
D/AndroidRuntime(11055): CheckJNI is OFF
D/AndroidRuntime(11055): readGMSProperty: start
D/AndroidRuntime(11055): readGMSProperty: already setted!!
I/SensorService( 3513): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3513): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3513): Skipped sensor MAX86902 because it requires permission 
W/GAV2    (10750): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/SensorService( 3513): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3513): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
D/AndroidRuntime(11055): readGMSProperty: end
D/AndroidRuntime(11055): addProductProperty: start
I/ActivityManager( 3513): Killing 10399:com.sec.providers.settingsearch/u0a181 (adj 13): bgCount ##31
W/LightSharedPreferencesImpl(10868): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(10868): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10868): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(10868): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(10868): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl(10868): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl(10868): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(10868): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl(10868): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl(10868): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(10868): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(10868): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl(10868): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(10868): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10868): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(10868): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(10868): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(10868): 	... 10 more
D/VlingoApplication(11059): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication(11059): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/DialogFlow(11059): initQueue()
I/SA      (11083): [SSP] onCreated
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/AffinityControl(11055): AffinityControl: registerfunction enter
I/MediaPlayer(10999): Need to enable context aware info
V/MediaPlayer-JNI(10999): native_setup
V/MediaPlayer(10999): constructor
V/MediaPlayer(10999): setListener
D/AndroidRuntime(11055): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3513): inState():  stateMachine is null !!
I/PersonaManagerService( 3513): PersonaId don't exist
I/ActivityManager( 3513): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3513): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3513): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3513): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/CustomFrequencyManagerService( 3513): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3513  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3513): mDVFSHelper.acquire()
I/art     ( 3513): Explicit concurrent mark sweep GC freed 220182(14MB) AllocSpace objects, 3(3MB) LOS objects, 24% free, 48MB/64MB, paused 1.813ms total 107.172ms
D/WifiService( 3513): New client listening to asynchronous messages
I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=404, uhalitest
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.XUIInstallConfirmActivity(394/onUserLeaveHint)] 
I/DBG_DM  ( 6310): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 19
I/DBG_DM  ( 6310): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 6310): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.XUIInstallConfirmActivity(399/onUserLeaveHint)] Home Key!!
D/AndroidRuntime(11055): Shutting down VM
D/[CarModeFW](10999): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/[CarModeFW](10999): DriveLinkServiceInterfaceImp-drivelink framework initialize end
D/[CarMode](10999): [DLServiceManager]-getOnDLLocationSuggestionListener..........
W/fb4a(:<default>):UserScope(10868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457399604297
I/DBG_DM  ( 6310): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/[CarMode](10999): [DLServiceManager]-updateLocationList
D/[CarMode](10999): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457399604297
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457399604297
D/[CarModeFW](10999): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457399604298
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457399604298
I/SA      (11083): [TPM] There is no property file
F/DLApplication(10999): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457399604300
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457399604302
I/[CarMode](10999): [LogNotNull]-Package name is: com.here.app.maps
D/TP/SmsProvider( 3983): query,matched:2, calling pid = 10999
D/[CarModeFW](10999): ContactDataHandler-getFavoriteContactList : cur len = 0
W/fb4a(:<default>):UserScope(10868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 10
D/TP/SmsProvider( 3983): match 2:Elapsed time : 3.702 ms
D/MessageDataHandler(10999):  getInboxList smsCursor : 22
I/SA      (11083): [SCU] isHaveSA() - false
D/TP/SmsProvider( 3983): query,matched:2, calling pid = 10999
D/TP/SmsProvider( 3983): match 2:Elapsed time : 1.466 ms
E/[CarMode](10999): [DLApplication]-Init End!:true
D/[CarModeFW](10999): CalllogDataHandler-getCalllogList : cur len = 0
D/[CarModeFW](10999): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 26
D/TP/MmsProvider( 3983): Query uri=content://mms/inbox, match=2, calling pid = 10999
D/[CarModeFW](10999): ContactDataHandler-getFavoriteContactList : cur len = 0
I/SA      (11083): [TPM] getModelProperty : null
I/SA      (11083): [TPM] getCSCProperty : null
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 28
W/fb4a(:<default>):UserScope(10868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/DBG_DM  ( 6310): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/SA      (11083): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
I/SA      (11083): [DM] init START
D/SecContentProvider2( 3513): uri = 14 selection = getSealedState
D/SecContentProvider2( 3513): mCursor = null
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 41
D/ApplicationPolicy( 3513): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
I/SA      (11083): [DM] This device is not a Vodafone
D/[CarMode](10999): [TAG]-phone sound mode is: 0
V/[CarMode](10999): [DLApplication]-savePreviousGpsState
V/ApplicationPolicy( 3513): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/PointerIcon( 3513): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3513): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3513): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3513): setHoveringSpenCustomIcon IconType is same.1
D/[CarModeFW](10999): LocationDataHandler-No schedules found.
D/MessageDataHandler(10999):  getInboxList mmsCursor : 22
I/SA      (11083): checkReactivationActive for LOLLIPOP
V/[CarMode](10999): [DLApplication]-savePreviousGpsState: Previous state = 0
I/SA      (11083): checkReactivationActive for reactiveActive
I/SA      (11083): setSupportRL : true
D/[CarModeFW](10999): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
I/SA      (11083): [SCU] isHaveSA() - false
I/SA      (11083): support phone number id : false
I/SA      (11083): [DM] init END
I/SA      (11083): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
D/TP/MmsProvider( 3983): Query uri=content://mms, match=0, calling pid = 10999
I/SA      (11083): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10681 extra.user_handle.:0 ]
D/[CarMode](10999): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode](10999): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/Zygote  (11147): MountEmulatedStorage()
E/Zygote  (11147): v2
I/libpersona(11147): KNOX_SDCARD checking this for 10003
I/libpersona(11147): KNOX_SDCARD not a persona
I/SELinux (11147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3513): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=11147 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SELinux (11147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11147): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
D/LightsService( 3513): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3513) 
D/LightsService( 3513): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3513): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3513): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/WindowManager( 3513): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 6310): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
I/libpersona(11162): KNOX_SDCARD checking this for 10046
E/Zygote  (11162): MountEmulatedStorage()
I/libpersona(11162): KNOX_SDCARD not a persona
E/Zygote  (11162): v2
I/SELinux (11162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
V/xAnalytics(10868): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics(10868): JNI_OnLoad XAnalyticsNative entered
V/xAnalytics(10868): JNI_OnLoad XAnalyticsNative complete
V/xAnalytics(10868): tigon: 0x0 - xanalytics: 0xffffffff9440e340
I/SELinux (11162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/xAnalytics(10868): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
V/xAnalytics(10868): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     (10868): Attempt to remove local handle scope entry from IRT, ignoring
E/SELinux (11162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/ActivityManager( 3513): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=11162 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
D/TimaKeyStoreProvider(11147): TimaSignature is unavailable
D/ActivityThread(11147): Added TimaKeyStore provider
D/MessageDataHandler(10999):  getInboxList mms,sms cursor join : 44
D/PersonaManager( 3696): isKioskContainerExistOnDevice
D/PersonaManager( 3696): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3696): Icon Only
I/DBG_DM  ( 6310): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/MessageDataHandler(10999): getUnreadMessageCount :0
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 96
I/[CarMode](10999): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode](10999): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
D/TP/MmsSmsProvider( 3983): query,matched:0, calling pid = 10999
V/TP/MmsSmsProvider( 3983): getSimpleConversations entered.
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 3983): match 0:Elapsed time : 0.759 ms
D/TimaKeyStoreProvider(11162): TimaSignature is unavailable
D/ActivityThread(11162): Added TimaKeyStore provider
I/UpdateManagerReceiver(10999): Intent : android.intent.action.PACKAGE_ADDEDTue Mar 08 02:13:24 GMT+01:00 2016
D/ResourcesManager(11147): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/DialogFlow(10999): initQueue()
E/Zygote  (11184): MountEmulatedStorage()
I/libpersona(11184): KNOX_SDCARD checking this for 10681
E/Zygote  (11184): v2
I/libpersona(11184): KNOX_SDCARD not a persona
I/SELinux (11184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/UserAnalysis.PlaceProvider(11147): PlaceProvider onCreate()
I/SELinux (11184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11184): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3513): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11184 uid=10681 gids={50681, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/StatusBar( 3696): Icon Only
D/PanelView( 3696): There is/are notification(s) 
D/PanelView( 3696): There is/are notification(s) 
D/PersonaManager( 3696): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3696): Icon Only
I/StatusBar( 3696): Icon Only
D/PanelView( 3696): There is/are notification(s) 
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(11184): TimaSignature is unavailable
D/ActivityThread(11184): Added TimaKeyStore provider
D/ResourcesManager(11162): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ResourcesManager(11162): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11162): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(11162): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/UserAnalysis.SecureDbManager(11147): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper(11147): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(11147): Create SecureDbHelper
E/Zygote  (11200): MountEmulatedStorage()
E/Zygote  (11200): v2
I/libpersona(11200): KNOX_SDCARD checking this for 1000
I/libpersona(11200): KNOX_SDCARD not a persona
I/SELinux (11200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3513): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=11200 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Icing   ( 4813): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
I/ActivityManager( 3513): Killing 9629:com.android.calendar/u0a164 (adj 13): bgCount ##31
I/ActivityManager( 3513): Killing 9612:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##32
I/ActivityManager( 3513): Killing 10550:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 3513): Killing 10514:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##34
V/ActivityManager( 3513): Display changed displayId=0
D/TimaKeyStoreProvider(11200): TimaSignature is unavailable
D/ActivityThread(11200): Added TimaKeyStore provider
E/Minikin (11162): addFont failed to create font /system/fonts/SamsungSans-light.ttf
I/System.out(11059): INFO:Resource not found:/Common.properties Using default values
D/KnoxNotification( 3696): ----- inflateViews : modified publicViewLocal -----
D/StatusBarManagerService( 3513): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/KnoxNotification( 3696): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 3696): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3696): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3cff37fa
D/PersonaManager( 3696): isKioskContainerExistOnDevice
D/PersonaManager( 3696): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3696): Icon Only
D/IntelligenceServiceApplication(11147): onCreate()
D/TP/MmsSmsProvider( 3983): query,matched:13, calling pid = 10999
I/RelayReceiver_PinBoard(11162): onReceive... android.intent.action.PACKAGE_ADDED
D/TP/MmsSmsProvider( 3983): match 13:Elapsed time : 8.088 ms
D/ResourcesManager(11184): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ResourcesManager(11200): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,W/ContextImpl(11200): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/hwcutils( 2849): MppFactory::MppFactory()
D/        ( 2849): virtual LibMpp* MppFactory::CreateMpp(int, int, int, int) dev(4) mode(0) drm(0), 
,D/libexynosgscaler( 2849): LibMpp::LibMpp()
,D/ResourcesManager( 4813): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/Icing   ( 4813): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,I/RelayService_PinBoard(11162): RelayService Started!! : android.intent.action.PACKAGE_ADDED
,I/StatusBar( 3696): Icon Only
,D/PanelView( 3696): There is/are notification(s) 
D/PanelView( 3696): There is/are notification(s) 
,D/PersonaManager( 3696): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3696): Icon Only
I/StatusBar( 3696): Icon Only
D/PanelView( 3696): There is/are notification(s) 
,D/PanelView( 3696): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/[CarModeFW](10999): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](10999): MyPlaceProvider-=============
D/[CarModeFW](10999): MyPlaceProvider-=============
D/[CarModeFW](10999): MyPlaceProvider-=============
D/[CarModeFW](10999): MyPlaceProvider-=============
D/[CarModeFW](10999): MyPlaceProvider-=============
D/[CarModeFW](10999): MyPlaceProvider-=============
D/[CarModeFW](10999): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](10999): MyPlaceProvider-==============
D/[CarModeFW](10999): MyPlaceProvider-==============
D/[CarModeFW](10999): MyPlaceProvider-==============
D/[CarModeFW](10999): MyPlaceProvider-==============
D/[CarModeFW](10999): MyPlaceProvider-==============
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11200): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  (11221): MountEmulatedStorage()
E/Zygote  (11221): v2
I/libpersona(11221): KNOX_SDCARD checking this for 10110
I/libpersona(11221): KNOX_SDCARD not a persona
,E/FilterInstaller(11200): installFilters
I/SELinux (11221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/FilterInstaller(11200): There is no requred permission
,I/SELinux (11221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3513): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=11221 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11221): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/MessageDataHandler(10999):  getInboxList address cursor : 116
,D/TP/MmsSmsProvider( 3983): query,matched:0, calling pid = 10999
V/TP/MmsSmsProvider( 3983): getSimpleConversations entered.
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 3983): match 0:Elapsed time : 1.325 ms
D/[CarModeFW](10999): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457399604608 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW](10999): DestinationAvailableTableHandler-insert FAIL!
,E/DestinationList(10999): loadLocationDestinationList is null
,D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 313
,D/TimaKeyStoreProvider(11221): TimaSignature is unavailable
,D/ActivityThread(11221): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 371us total 18.271ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 252us total 8.109ms
,I/WebViewFactory(11184): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11184): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/PanelView( 3696): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 348us total 8.082ms
,E/Zygote  (11237): MountEmulatedStorage()
E/Zygote  (11237): v2
,I/libpersona(11237): KNOX_SDCARD checking this for 10121
I/libpersona(11237): KNOX_SDCARD not a persona
,I/SELinux (11237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3513): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=11237 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/MessageDataHandler(10999):  getInboxList thread cursor : 56
,I/ActivityManager( 3513): Killing 9309:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,I/LibraryLoader(11184): Loading: webviewchromium
,E/lowmemorykiller( 2828): Error writing /proc/9309/oom_score_adj; errno=22
,I/ActivityManager( 3513): Killing 10414:com.google.android.gm/u0a122 (adj 15): bgCount ##31
,I/LibraryLoader(11184): Time to load native libraries: 3 ms (timestamps 553-556)
I/LibraryLoader(11184): Expected native library version number "",actual native library version number ""
,D/MessageDataHandler(10999):  thread, addr result: 7
I/[CarModeFW](10999): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 369
I/[CarModeFW](10999): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](10999): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 369
,D/TimaKeyStoreProvider(11237): TimaSignature is unavailable
,D/ActivityThread(11237): Added TimaKeyStore provider
,D/ResourcesManager(11221): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
D/AppStateLogger(10868): Successfully dumped app state to log file
V/WebViewChromiumFactoryProvider(11184): Binding Chromium to main looper Looper (main, tid 1) {2912a895}
I/LibraryLoader(11184): Expected native library version number "",actual native library version number ""
I/chromium(11184): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/ResourcesManager(11237): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/BrowserStartupController(11184): Initializing chromium process, renderers=0
,W/art     (11184): Attempt to remove local handle scope entry from IRT, ignoring
,D/PackageIntentReceiver(11237): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(11237): Not GearManger package! 
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,W/chromium(11184): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11184): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11184): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,E/Zygote  (11264): MountEmulatedStorage()
E/Zygote  (11264): v2
I/libpersona(11264): KNOX_SDCARD checking this for 1000
I/libpersona(11264): KNOX_SDCARD not a persona
,I/SELinux (11264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3513): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=11264 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3513): Killing 10466:com.google.android.music:main/u0a135 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(11264): TimaSignature is unavailable
,D/ActivityThread(11264): Added TimaKeyStore provider
,D/ResourcesManager(11264): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/chromium(11184): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
W/chromium(11184): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,V/fb-UnpackingSoSource(11221): locked dso store /data/data/com.facebook.appmanager/lib-main
,I/fb-UnpackingSoSource(11221): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(11221): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(11221): locked dso store /data/data/com.facebook.appmanager/lib-assets
,I/fb-UnpackingSoSource(11221): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(11221): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(11221): locked dso store /data/data/com.facebook.appmanager/lib-xzs
I/fb-UnpackingSoSource(11221): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource(11221): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
,D/ACRA    (11221): ACRA is enabled for com.facebook.appmanager, intializing...
,E/Zygote  (11301): MountEmulatedStorage()
E/Zygote  (11301): v2
I/libpersona(11301): KNOX_SDCARD checking this for 1000
I/libpersona(11301): KNOX_SDCARD not a persona
,I/SELinux (11301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11301): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3513): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=11301 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/art     (11184): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 3513): Killing 10317:com.google.process.gapps/u0a14 (adj 15): bgCount ##31
,W/AwContents(11184): onDetachedFromWindow called when already detached. Ignoring
,V/DexLibLoader(11221): DLL.loadAll betaBuild:true flags:0x00000001
,V/dalvik-internals(11221): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals(11221): hooked signal using trap ()
V/dalvik-internals(11221): hooked sysv_signal using trap ()
V/dalvik-internals(11221): hooked bsd_signal using trap ()
,V/dalvik-internals(11221): hooked sigaction using jump ()
V/DexLibLoader(11221): opening dex store /data/data/com.facebook.appmanager/dex
,D/TimaKeyStoreProvider(11301): TimaSignature is unavailable
V/DexLibLoader(11221): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
,V/DexLibLoader(11221): read status:9 check:faceb007faceb00e
D/ActivityThread(11301): Added TimaKeyStore provider
V/DexLibLoader(11221): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader(11221): verified deps file
I/DexLibLoader(11221): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader(11221): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader(11221): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader(11221): Setup multi dex took 1 ms.
V/DexLibLoader(11221): optimization needed: no
,D/SystemWebViewEngine(11184): CordovaWebView is running on device made by: samsung
,W/art     (11184): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11184): Attempt to remove local handle scope entry from IRT, ignoring
,D/ResourcesManager(11301): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/GMPM    (11221): App measurement is starting up
,E/GMPM    (11221): getGoogleAppId failed with status: 10
,E/GMPM    (11221): Uploading is not possible. App measurement disabled
,W/cn      (11221): Verify
,D/Activity(11184): performCreate Call secproduct feature valuefalse
D/Activity(11184): performCreate Call debug elastic valuetrue
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener(11301): Received: android.intent.action.PACKAGE_ADDED
,I/Icing   ( 4813): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,E/Zygote  (11330): MountEmulatedStorage()
E/Zygote  (11330): v2
I/libpersona(11330): KNOX_SDCARD checking this for 10147
I/libpersona(11330): KNOX_SDCARD not a persona
,I/SELinux (11330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3513): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=11330 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11330): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3513): Killing 10602:com.google.android.gms:car/u0a14 (adj 15): bgCount ##31
,W/appmanager(:<default>):LightSharedPreferencesImpl(11221): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl(11221): 	... 10 more
,W/appmanager(:<default>):b(11221): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/OpenGLRenderer(11184): Render dirty regions requested: true
,D/TimaKeyStoreProvider(11330): TimaSignature is unavailable
,D/ActivityThread(11330): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/appmanager(:<default>):b(11221): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ResourcesManager(11330): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ActivityManager( 3513): post active user change for 0
D/KnoxTimeoutHandler( 3513): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3513): handleActiveUserChange for user 0
,W/ResourcesManager(11330): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ContextImpl(11301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/libexynosgscaler( 2849): virtual CGscaler::~CGscaler()
D/libexynosgscaler( 2849): virtual LibMpp::~LibMpp()
D/        ( 2849): virtual MppFactory::~MppFactory()
,W/appmanager(:<default>):QuickExperimentControllerImpl(11221): Exposure of experiment com.facebook.http.g.c@3d745a6e occurred when no user was logged in
,I/art     (11221): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
I/art     (11221): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,I/OpenGLRenderer(11184): Initialized EGL, version 1.4
,I/OpenGLRenderer(11184): HWUI protection enabled for context ,  &this =0xaf745060 ,&mEglDisplay = 1 , &mEglConfig = -1278779120 
,D/OpenGLRenderer(11184): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11184): Enabling debug mode 0
D/mali_winsys(11184): new_window_surface returns 0x3000,  [1440x2560]-format:1
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
I/Icing   ( 4813): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,E/Zygote  (11371): MountEmulatedStorage()
I/libpersona(11371): KNOX_SDCARD checking this for 10013
E/Zygote  (11371): v2
I/libpersona(11371): KNOX_SDCARD not a persona
D/PointerIcon( 3513): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3513): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3513): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3513): setHoveringSpenCustomIcon IconType is same.1
I/SELinux (11371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11371): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3513): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=11371 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,D/AcmsService(11301): Enter Oncreate
,D/AcmsServiceMonitor(11301): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(11301): creating AcmsCore
D/AcmsCore(11301): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(11301): AcmsCore
,D/AcmsCore(11301): init
D/AcmsCore(11301): Looper handler is not null
D/AcmsCore(11301): Post to AcmsCoreHandler
D/AcmsServiceMonitor(11301): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11301): Incrementing - Counter value: 1
D/AcmsCore(11301): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsCertificateMngr(11301): AcmsCertificateMngr
D/AcmsRevocationMngr(11301): AcmsRevocationMngr
D/AcmsService(11301): onStartCommand
D/AcmsService(11301): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(11301): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(11301): Incrementing - Counter value: 2
D/AcmsService(11301): Incremented Counter Value : onStartCommand
I/System.out(11221): Thread-1566(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11221): Thread-1566(ApacheHTTPLog):isSBSettingEnabled false
D/ActivityThread(11301): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
I/System.out(11221): Thread-1566(ApacheHTTPLog):isShipBuild true
I/System.out(11221): Thread-1566(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider(11371): TimaSignature is unavailable
,D/ActivityThread(11371): Added TimaKeyStore provider
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
,D/InputMethodManagerService( 3513): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AcmsService(11301): Inside handle Intent
D/AcmsService(11301): App added - package name: com.test.thalitest
D/AcmsCore(11301): Post to AcmsCoreHandler
D/AcmsServiceMonitor(11301): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11301): Incrementing - Counter value: 3
D/AcmsCore(11301): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(11301): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(11301): Decrementing - Counter value: 2
D/ResourcesManager(11371): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3513): Displayed com.test.thalitest/.MainActivity: +696ms
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/Timeline(11184): Timeline: Activity_idle id: android.os.BinderProxy@11f2ed23 time:71004
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11403): MountEmulatedStorage()
E/Zygote  (11403): v2
I/libpersona(11403): KNOX_SDCARD checking this for 10014
I/libpersona(11403): KNOX_SDCARD not a persona
,I/SELinux (11403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3513): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=11403 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux (11403): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11403): TimaSignature is unavailable
,D/ActivityThread(11403): Added TimaKeyStore provider
,D/ResourcesManager(11403): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GservicesProvider(11403): Gservices pushing to system: true; secure/global: true
,D/JsMessageQueue(11184): Set native->JS mode to OnlineEventsBridgeMode
,I/GoogleHttpClient(11403): GMS http client unavailable, use old client
,D/ResourcesManager(11403): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/chromium(11184): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11184): 
,I/GoogleHttpClient(11403): GMS http client unavailable, use old client
,I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (4/9)
,I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/9)
,D/CustomFrequencyManagerService( 3513): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3513  tag : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3513): mDVFSHelper.release()
I/Timeline( 3513): Timeline: Activity_windows_visible id: ActivityRecord{d6813ee u0 com.test.thalitest/.MainActivity t28} time:71138
,D/CustomFrequencyManagerService( 3513): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3513  pkgName : ACTIVITY_RESUME_BOOSTER@6
,D/jxcore_app_log(11184): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358474112
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11184): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11184):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11184):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11184):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11184):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11184): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f4a3f98 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184): setBluetoothMacAddress: E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11184): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11184): setIdentityString: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11184): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11184): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Bluetooth MAC address: E0:DB:10:14:E2:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a6ebe57 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel(11184): addListener: New listener added - the number of listeners is now 1
,D/WifiService( 3513): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11184): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11184): setScanMode: 1 -> 2
,I/chromium(11184): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger( 2849): id=13 Removed uhalitest (6/8)
,I/SurfaceFlinger( 2849): id=13 Removed uhalitest (-2/8)
,I/ActivityManager( 3513): Killing 10717:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
,V/GLSActivity( 4642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,W/ActivityThread(11221): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/Zygote  (11439): MountEmulatedStorage()
E/Zygote  (11439): v2
I/libpersona(11439): KNOX_SDCARD checking this for 10160
I/libpersona(11439): KNOX_SDCARD not a persona
,I/SELinux (11439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11439): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3513): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=11439 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11439): TimaSignature is unavailable
,D/ActivityThread(11439): Added TimaKeyStore provider
,D/ResourcesManager(11439): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(11439): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11439): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/Mms/MmsApp(10782):  start initViewCache mms
,D/Mms/ComposeMessageFragment(10782): [start]    fillCache consume time = 1912.090917
D/Mms/ComposeMessageFragment(10782): fillCache, easy = false
,V/Common  (11439): getScreenSize 1440 2560
,E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
,I/art     ( 3513): Explicit concurrent mark sweep GC freed 20132(1185KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 53MB/69MB, paused 2.032ms total 86.613ms
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (11460): MountEmulatedStorage()
E/Zygote  (11460): v2
I/libpersona(11460): KNOX_SDCARD checking this for 10160
I/libpersona(11460): KNOX_SDCARD not a persona
,I/SELinux (11460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3513): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=11460 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
I/JAM     (11439): Load The ApaService JNI
E/SELinux (11460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/JAM     (11439): version: ProfessionalAudio_v1.0.b5
I/JAM     (11439): Try v1.0.b3 ...
,I/System.out(11221): P[5]_NetworkDispatch1 calls detatch()
,D/Spen    (11439): SpenSdk version level = 55
D/Spen    (11439): SpenSdk jar version = 3.0.243
,I/ActivityManager( 3513): Killing 10220:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/AbsListView(10782): Get MotionRecognitionManager
,D/MotionRecognitionService( 3513):  ssp status : true
,D/TimaKeyStoreProvider(11460): TimaSignature is unavailable
,D/ActivityThread(11460): Added TimaKeyStore provider
,D/Spen    (11439): SpenSdk apk version = 3.0.235
D/Spen    (11439): Server UPDATE Check
,D/Mms/ComposeMessageFragment(10782): [end]    fillCache consume time = 85.214792
,W/linker  (11439): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SPenError(11439): JNI_OnLoad
,D/JNI_Bitmap(11439): Init .. Done
,D/SPenSpiDecoder(11439): JNI_OnLoad .. Done
D/SPenError(11439): JNI_OnLoad Success
,D/PluginManager(11439): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager(11439): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(11439): JNI_OnLoad
,D/Init_SPenSdk_Jni(11439): AndroidSDK: 21
D/Init_SPenSdk_Jni(11439): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni(11439): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni(11439): JNI_OnLoad .. Done
,D/Model_ObjectImage_Jni(11439): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(11439): JNI_OnLoad .. Done
,D/ResourcesManager(11460): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/Model_ObjectContainer_Jni(11439): JNI_OnLoad .. Done
D/Model_PageDoc_Jni(11439): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(11439): check build type eng[0]
D/Model_NoteDoc_Jni(11439): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(11439): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(11439): JNI_OnLoad .. Done
D/Model   (11439): OnLoad class Done
W/ResourcesManager(11460): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11460): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11460): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/BroadcastQueue( 3513): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{24f038e9 u0 ReceiverList{11dcfd70 11221 com.facebook.appmanager/10110/u0 remote:2b3d73b3}}
W/BroadcastQueue( 3513): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{24f038e9 u0 ReceiverList{11dcfd70 11221 com.facebook.appmanager/10110/u0 remote:2b3d73b3}}
D/CustomFrequencyManagerService( 3513): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3513  tag : ACTIVITY_RESUME_BOOSTER@6
D/spe_log (11439): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(11439): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(11439): Canvas JNI_OnLoad enter!!
D/SPen_Library(11439): Canvas JNI_OnLoad Success
D/SPen_Library(11439): TextView JNI_OnLoad enter!!
D/SPen_Library(11439): TextView JNI_OnLoad Success
D/SPen_Library(11439): Text JNI_OnLoad enter!!
D/SPen_Library(11439): Text JNI_OnLoad Success
D/SPen_Library(11439): FontManager JNI_OnLoad enter!!
D/SPen_Library(11439): FontManager JNI_OnLoad Success
D/SPen_Library(11439): CapturePage JNI_OnLoad enter!!
D/SPen_Library(11439): CapturePage JNI_OnLoad Success
D/SPen_Library(11439): Multi JNI_OnLoad enter!!
D/SPen_Library(11439): Multi JNI_OnLoad Success
D/SPen_Library(11439): Draw Engine JNI_OnLoad Success
D/SPen_Library(11439): Brush JNI_OnLoad enter!!
D/SPen_Library(11439): Brush JNI_OnLoad Success
D/SPen_Library(11439): ChineseBrush JNI_OnLoad enter!!
D/SPen_Library(11439): ChineseBrush JNI_OnLoad Success
D/SPen_Library(11439): InkPen JNI_OnLoad enter!!
D/SPen_Library(11439): InkPen JNI_OnLoad Success
D/SPen_Library(11439): Marker JNI_OnLoad enter!!
D/SPen_Library(11439): Marker JNI_OnLoad Success
D/SPen_Library(11439): Pencil JNI_OnLoad enter!!
D/SPen_Library(11439): Pencil JNI_OnLoad Success
D/SPen_Library(11439): NativePen JNI_OnLoad enter!!
D/SPen_Library(11439): NativePen JNI_OnLoad Success
D/SPen_Library(11439): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(11439): MontblancFountainPen JNI_OnLoad Success
D/SPen_Library(11439): MontblancCalligraphyPen JNI_OnLoad enter!!
D/SPen_Library(11439): MontblancCalligraphyPen JNI_OnLoad Success
D/SPen_Library(11439): MagicPen JNI_OnLoad enter!!
D/SPen_Library(11439): MagicPen JNI_OnLoad Success
D/SPen_Library(11439): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(11439): ObliquePen JNI_OnLoad Success
D/SPen_Library(11439): FountainPen JNI_OnLoad enter!!
D/SPen_Library(11439): FountainPen JNI_OnLoad Success
D/Spen    (11439): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(11439): SPenSdk_init2
D/Init_SPenSdk(11439): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(11439): Total S Pen SDK Directory Size = 0
D/Spen    (11439): initialize complete
W/linker  (11439): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/BroadcastQueue( 3513): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1d6d3846 u0 ReceiverList{19cd1c21 11221 com.facebook.appmanager/10110/u0 remote:350f0a88}}
D/ResourcesManager(11439): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/SNoteProvider(11460): onCreate enableSnoteSync = true
D/SNoteProvider(11460): ===query=== 
V/Common  (11460): getScreenSize 1440 2560
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/Zygote  (11494): MountEmulatedStorage()
I/libpersona(11494): KNOX_SDCARD checking this for 10183
E/Zygote  (11494): v2
I/libpersona(11494): KNOX_SDCARD not a persona
I/SELinux (11494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3513): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=11494 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/SELinux (11494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11494): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3513): Killing 10765:com.facebook.system/u0a10 (adj 15): bgCount ##31
I/ActivityManager( 3513): Killing 10735:com.google.android.partnersetup/u0a17 (adj 15): bgCount ##31
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/TimaKeyStoreProvider(11494): TimaSignature is unavailable
D/ActivityThread(11494): Added TimaKeyStore provider
D/SNoteProvider(11460): ===query=== 
D/ResourcesManager(11494): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/Mms/BubbleViewCache(10782): fillCache bubble = 8
E/SQLiteLog(11494): (284) automatic index on shooting_modes(title_id)
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3513): checkUser: useridlist=null, currentuser=0
E/Zygote  (11512): MountEmulatedStorage()
E/Zygote  (11512): v2
I/libpersona(11512): KNOX_SDCARD checking this for 10190
I/libpersona(11512): KNOX_SDCARD not a persona
I/SELinux (11512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11512): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3513): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=11512 uid=10190 gids={50190, 9997} abi=armeabi-v7a
I/ActivityManager( 3513): Killing 10802:com.sec.android.service.health/u0a19 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(11512): TimaSignature is unavailable
D/ActivityThread(11512): Added TimaKeyStore provider
D/ResourcesManager(11512): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(11512): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11512): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
I/TapandpayWidget:Utils(11512): Clear T&P info.
D/TapandpayWidget:TanpandpayAppWidgetProvider(11512): Widget is not attached.
I/splitIntent( 3513): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 3513): Killing 10824:com.sec.pcw.device/1000 (adj 15): bgCount ##31
D/BootupListener( 3983): ACTION_DRIVELINK
D/SettingsProvider( 3513): name = drivelink_navigation
D/SettingsProvider( 3513): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3513): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3513): selectionArgs: false
D/SettingsProvider( 3513): selectionArgs: 1001
D/SecContentProvider( 3513): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3513): ret = -1
D/BootupListener( 3983): NAVI : com.here.app.maps
D/SettingsProvider( 3513): name = internet_call_settings_visibility
D/SettingsProvider( 3513): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3513): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3513): selectionArgs: false
D/SettingsProvider( 3513): selectionArgs: 1001
D/SecContentProvider( 3513): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3513): ret = -1
D/BootupListener( 3983): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
D/Widget  (11439): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
D/Widget  (11439): onReceive android.appwidget.action.APPWIDGET_UPDATE
D/Widget  (11439): widgetUpdate 5
D/RCPManagerService( 3513): exchangeData() failure , invalid userId
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11221): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11221): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
W/appmanager(:<default>):QuickExperimentControllerImpl(11221): Exposure of experiment com.facebook.imagepipeline.m.d@31e4b2cb occurred when no user was logged in
W/appmanager(:<default>):aa(11221): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
W/appmanager(:<default>):aa(11221): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
V/analytics4a(11221): JNI_OnLoad called
V/analytics4a(11221): JNI_OnLoad complete
D/AcmsKeyStoreHelper(11301):  getKeyStoreForApplication Enter
I/AcmsKeyStoreHelper(11301): Key Store exist
I/AcmsKeyStoreHelper(11301): Hence loading the keystore file
I/art     (11221): Explicit concurrent mark sweep GC freed 66395(3MB) AllocSpace objects, 6(119KB) LOS objects, 22% free, 28MB/36MB, paused 810us total 28.951ms
W/appmanager(:<default>):m(11221): No feature status reporters found; is this dead code?
D/AcmsKeyStoreHelper(11301):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(11301): getKeyStoreForApplication success 
D/AcmsCore(11301): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(11301): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11301): Decrementing - Counter value: 1
D/AcmsCore(11301): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore(11301): This is NOT a valid MirrorLink app
D/AcmsCore(11301): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(11301): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(11301): Decrementing - Counter value: 0
D/AcmsServiceMonitor(11301): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor(11301): getSvcCounter - Counter value: 0
D/AcmsService(11301): Enter onDestroy
I/AcmsService(11301): cleanUp(): inside service clean up
D/AcmsCore(11301): AcmsCore: inside DeInit
D/AcmsCore(11301): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(11301): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(11301): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(11301): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(11301): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(11301): getSvcCounter - Counter value: 0
D/AcmsService(11301): killing acms process
I/Process (11301): Sending signal. PID: 11301 SIG: 9
I/ActivityManager( 3513): Process ACMS.Process (pid 11301)(adj 0) has died(77,1176)
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/jxcore-log(11184): Initializing JXcore engine
W/jxcore-log(11184): JXcore engine is ready
W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/auditd  ( 4629): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3513): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3513): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11184): Starting JXcore engine
,W/jxcore-log(11184): Platform android
W/jxcore-log(11184): 
W/jxcore-log(11184): Process ARCH arm
W/jxcore-log(11184): 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11184): JXcore Cordova bridge is ready!
I/jxcore-log(11184): 
,W/jxcore-log(11184): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions(11184): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3513): waitForAlarm result :8
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
,E/Watchdog( 3513): !@Sync 2
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libencoder( 3513): width= 768, height = 768, colot_type= 6, bit_depth= 8
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PersonaManager( 3696): isKioskContainerExistOnDevice
,D/PersonaManager( 3696): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3696): Icon Only
I/StatusBar( 3696): Icon Only
D/PanelView( 3696): There is/are notification(s) 
D/PanelView( 3696): There is/are notification(s) 
,D/TaskPersister( 3513): removeObsoleteFile: deleting file=27_task_thumbnail.png
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4309, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:-640, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-496
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 3696): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3513): SIOP:: AP = 350, PST = 322, CUR = -640
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):UserScope(10868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/GAV2    (10750): Thread[GAThread,5,main]: No campaign data found.
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     (10868): Thread[1,tid=10868,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/art     (10868): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching, sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImp,l(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data, while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/BroadcastQueue( 3513): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{14c7ca3d u0 ReceiverList{32056f94 10868 com.facebook.katana/10114/u0 remote:2ffd87e7}}
,W/BroadcastQueue( 3513): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{14c7ca3d u0 ReceiverList{32056f94 10868 com.facebook.katana/10114/u0 remote:2ffd87e7}}
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/GcOptimizer(10868): Configure for next cold start: disable
,W/BroadcastQueue( 3513): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{31998cdf u0 ReceiverList{2183ef7e 10868 com.facebook.katana/10114/u0 remote:86bcd39}}
,W/fb4a(:<default>):UserScope(10868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QuickExperimentControllerImpl(10868): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsMainExperiment@1dc36783 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(10868): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsPassiveListenerExperiment@80f2d00 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl(10868): Exposure of experiment com.facebook.inject.init.GeneratedFbInjectorWeakrefExperiment@2242e363 occurred when no user was logged in
,W/fb4a(:<default>):UserScope(10868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):QeInternalImpl(10868): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/BadgeProvider(10904): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider(10904): sendNotify, [notify] : null
D/BadgeProvider(10904): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider(10904): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10904): update, [UpdateCount] : 1
,D/Launcher.Model( 4003): reloadBadges entered.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10868): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10868): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,W/fb4a(:<default>):UserScope(10868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10868): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/System.out(11221): P[5]_NetworkDispatch2 calls detatch()
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11221): P[5]_NetworkDispatch3 calls detatch()
,V/io.jxcore.node.JXcoreExtension(11184): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log(11184): BLE multiple advertisement supported
I/jxcore-log(11184): 
,I/jxcore-log(11184): My device name is: samsung-SM-N910C
I/jxcore-log(11184): 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    (11330): Thread[GAThread,5,main]: No campaign data found.
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3513): Killing 10199:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
I/jxcore-log(11184): 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11184): 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11184): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log(11184): 
,I/jxcore-log(11184): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log(11184): 
,I/io.jxcore.node.ConnectivityInfo(11184): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo(11184):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo(11184):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo(11184):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo(11184):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo(11184):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo(11184):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo(11184):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo(11184):     - force notify: true
D/io.jxcore.node.JXcoreExtension(11184): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log(11184): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log(11184): 
,I/jxcore-log(11184): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log(11184): 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3513): [MSG] MCS_UNBIND
,I/ActivityManager( 3513): Killing 9765:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3513): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/AlarmManager( 3513): waitForAlarm result :4
,E/ActivityThread( 4813): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3513): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 51109, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 3513): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 141788, reason: UserStart
,W/ResourceType( 5208): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5208): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3513): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3513): mCursor = null
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11221): P[5]_NetworkDispatch4 calls detatch()
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11221): P[5]_NetworkDispatch5 calls detatch()
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11221): P[5]_NetworkDispatch6 calls detatch()
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(11184): 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11221): P[5]_NetworkDispatch7 calls detatch()
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log(11184): 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log(11184): 
,I/System.out(11221): P[5]_NetworkDispatch8 calls detatch()
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11184): 
,I/jxcore-log(11184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
I/jxcore-log(11184): 
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
,I/jxcore-log(11184): Unit Test app is loaded
I/jxcore-log(11184): 
,I/jxcore-log(11184): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log(11184): 
,I/chromium(11184): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11221): P[5]_NetworkDispatch9 calls detatch()
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3513): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3696 (0x0)
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4393, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:-492, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:189
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3513): SIOP:: AP = 350, PST = 325, CUR = -492
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3513): waitForAlarm result :4
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  (10345): [1405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10345): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3513): Waited long enough for: ServiceRecord{3a2e187b u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3513): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3513): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3513): [s] DisplayPowerCallbacks : onStateChanged()
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 3513): lcd : 3 +
,D/lights  ( 3513): lcd : 3 -
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
,D/lights  ( 3513): lcd : 1 +
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3513): lcd : 1 -
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness(),
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/StatusBar.NetworkController( 3696): applyOpen
,D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3513): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3513): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3696): applyOpen
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3696): applyOpen
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3513): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3513): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 3513): !@[ps] Screen__Off - 1 : timeout (0x4) (2)
D/InputManager-JNI( 3513): setDeviceInteractive: 0
I/PowerManagerService( 3513): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 3513): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3513): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI( 3513): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI( 3513): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 3513): handleSandman : startDream()
,E/PowerManagerService( 3513): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 3513): Sleeping (uid 1000)...
D/InputManager-JNI( 3513): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService( 3513): [s] UserActivityState : 4 -> 0
,D/PowerManagerService( 3513): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService( 3513): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI( 3513): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,I/SurfaceFlinger( 2849): id=15 createSurf (1440x2560),2 flag=404, DolorFade
,D/InputManager-JNI( 3513): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3513): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService( 3513): 	.unregisterCallback : 1, client=
,D/SContextService( 3513): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3c7a2d11, Service = Auto Rotation, used = 1
W/CAE     ( 3513): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3513): stop(ContextProvider.java:149)
,V/CAE     ( 3513): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3513): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3513): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3513): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs( 2867): sendContextData: -78, 7, 0, 0
,D/PowerManagerService( 3513): Excessive delay in ColorFade : createSurface: 21ms
,D/CAE     ( 3513): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3513): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
D/mali_winsys( 3513): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PowerManagerService( 3513): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 36ms
,D/CAE     ( 3513): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3513): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3513): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3513): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3513): removeSContextService() : service = Auto Rotation
D/SContextService( 3513): ===== SContext Service List =====
D/SContextManager( 3513):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@6fb05ae, service=Auto Rotation
,D/KeyguardViewMediator( 3696): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3696): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3696): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 3696): notifyScreenOffLocked
,D/KeyguardViewMediator( 3696): timeout : 5000
,D/PowerManagerService( 3513): Excessive delay in ColorFade : initGLShaders: 39ms
,V/ActivityThread(11184): updateVisibility : ActivityRecord{e49dbd9 token=android.os.BinderProxy@11f2ed23 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PowerManagerService( 3513): Excessive delay in ColorFade : draw: 17ms
,D/KeyguardViewMediator( 3696): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 3696): handleNotifyScreenOff
,D/PowerManagerService( 3513): Excessive delay in ColorFade : draw: 12ms
,D/PowerManagerService( 3513): Excessive delay in ColorFade : draw: 13ms
D/PowerManagerService( 3513): Excessive delay in ColorFade prepare: 145ms
,D/DisplayPowerController( 3513): ColorFade: onAnimationStart
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3513): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3513): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3513): lcd : 0 +
D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3513): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3513): lcd : 0 -
,D/LightsService( 3513): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3513) 
D/LightsService( 3513): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 3513): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3513): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager( 3513): unregisterListener ::   
D/lights  ( 3513): led_pattern : 5 +
,D/BatteryService( 3513): turn on LED for fully charged
,I/CAE     ( 3513): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3513): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3513): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3513): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs( 2867): sendContextData: -76, 13, -46, 0
,I/CAE     ( 3513): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 1, 13, 47,
D/SensorHubManager( 3513): SendSensorHubData: send data = -63, 14, 1, 13, 47
,D/Sensorhubs( 2867): sendContextData: -63, 14, 1, 13, 47
,D/lights  ( 3513): led_pattern : 5 -
,D/LightsService( 3513): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/MotionRecognitionService( 3513):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService( 3513):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3513): evaluateTrafficStatsPolling
,D/WifiStateMachine( 3513): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3513): handleScreenStateChanged Exit: false
,D/NotificationService( 3513): ACTION_SCREEN_OFF
D/LightsService( 3513): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3513) 
D/LightsService( 3513): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 3513): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3513): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
E/WifiStateMachine( 3513): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
D/LightsService( 3513): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SensorManager( 3513): unregisterListener ::   
E/WifiStateMachine( 3513): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3513): do suspend true
,I/AudioHardwareTinyALSA( 2854): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 3513): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:-105, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:138
D/BatteryService( 3513): stay LED for fully charged
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/AutomaticBrightnessController( 3513): mCallbacks.updateBrightness()
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/IpRemoteDisplayController( 3513): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3513): Bridge Server is not available
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/VolumePanel( 3696): registerReceiver: onReceive start 
D/VolumePanel( 3696): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3696): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3696): registerReceiver: onReceive end 
,D/VolumePanel( 3696): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3696): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3696): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3696): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3696): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3513): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3513): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3513): sExerciseIterface is not available
,D/PersonaManagerService( 3513): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 3513): MSG_ACTION_SCREEN_OFF called
,D/DisplayPowerController( 3513): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3513): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/NfcService( 3971): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3696):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3696): onReceive : Intent.ACTION_SCREEN_OFF
,D/accuweather( 5336): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 5336): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5336): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3513): SIOP:: AP = 310, PST = 323, CUR = -105
,D/DisplayPowerState( 3513): !@ ColorFade entry
D/DisplayPowerController( 3513): ColorFade: onAnimationEnd
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5336): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5336): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5336): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5336): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/PowerManagerService( 3513): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/AutomaticBrightnessController( 3513): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/AutomaticBrightnessController( 3513): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController( 3513): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/Sensors ( 3513): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController( 3513): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AutomaticBrightnessController( 3513): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3513): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3513): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorManager( 3513): unregisterListener ::   
,D/DisplayPowerController( 3513): getFinalBrightness : 0 -> 0
I/Sensors ( 3513): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/DisplayPowerController( 3513): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SurfaceFlinger( 2849): Set power mode=0, type=0 flinger=0xb6962000
I/DisplayManagerService( 3513): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 3513): Display changed displayId=0
,D/DisplayPowerController( 3513): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3513): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3513): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3513): [PWL] sb release: PowerManagerService.Display
I/hwcomposer( 2849): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,D/SensorManager( 3513): unregisterListener ::   
,D/accuweather( 5336): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5336): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5336): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5336): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5336): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5336): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5336): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3513): Excessive delay in setPowerMode(): 206ms
,D/PowerManagerService( 3513): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL( 3513): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3513): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/PowerManagerService( 3513): [PWL] Off : 0s ago
,D/PowerManagerService( 3513): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 209ms
,W/IdleConnectionHandler(11221): Removing a connection that never existed!
,W/IdleConnectionHandler(11221): Removing a connection that never existed!
,V/AlarmManager( 3513): waitForAlarm result :4,
,D/KeyguardViewMediator( 3696): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 3696): doKeyguard: not showing because lockscreen is off
,V/AlarmManager( 3513): waitForAlarm result :4
,I/PowerManagerService( 3513): [PWL] Off : 5s ago
I/PowerManagerService( 3513): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3513): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3513): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10014, pid=4642, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=25)
,V/GLSActivity( 4642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 4642): Vacuum at: now=1457399633428 tag=VacuumService
,I/PhenotypeConfigurator( 4642): Scheduling Phenotype for one-off execution 5111 seconds from now (1457399633773)
,I/PhenotypeFlagCommitter( 4642): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4642): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 3513): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 4642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4642): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4642): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4642): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4642, getuid(): 10014
,I/qtaguid ( 4642): Tagging socket 85 with tag 1000120100000000{268440065,0} uid -1, pid: 4642, getuid(): 10014
,V/xAnalytics(10868): xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,D/LocationManagerService( 3513): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4642): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4642): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4642, getuid(): 10014
,D/LocationManagerService( 3513): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4642): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4642): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4642, getuid(): 10014
,E/Watchdog( 3513): !@Sync 3
,V/AlarmManager( 3513): waitForAlarm result :4
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:117
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 300, PST = 321, CUR = 35
,D/FactoryTest(10162): Not factory mode
,D/FactoryTest(10162): Not factory mode. isFactoryMode() returend false
,D/MTPRx   (10162): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   (10162): still no open session command from host, so toast
,W/ContextImpl(10162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,W/ContextImpl(10162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
,I/Timeline(10162): Timeline: Activity_launch_request id:com.android.settings time:105007
,E/PersonaManagerService( 3513): inState():  stateMachine is null !!
I/PersonaManagerService( 3513): PersonaId don't exist
,I/ActivityManager( 3513): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 3513): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager( 3513): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager( 3513): mDVFSHelper.acquire()
,V/ActivityManager( 3513): Display changed displayId=0
,E/MTPRx   (10162): started activity for popup
,D/PointerIcon( 3513): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3513): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3513): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3513): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(10162): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(10162): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10162): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(10162): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10162): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10162): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10162): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10162): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity(10162): PREF_DONT_ASK_AGAIN : true
,D/PointerIcon( 3513): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3513): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3513): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3513): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService( 3513): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 3513): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@279baa77 attribute=android.view.inputmethod.EditorInfo@1a4206e4, token = android.os.BinderProxy@3e69705b
,D/SettingsReceiverActivity(10162): dev.kiessupport is : TRUE
,D/Activity(10162): performCreate Call secproduct feature valuefalse
D/Activity(10162): performCreate Call debug elastic valuetrue
,D/ActivityManager( 3513): post active user change for 0
D/KnoxTimeoutHandler( 3513): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3513): handleActiveUserChange for user 0
,V/ActivityThread(11184): updateVisibility : ActivityRecord{e49dbd9 token=android.os.BinderProxy@11f2ed23 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline(11184): Timeline: Activity_idle id: android.os.BinderProxy@11f2ed23 time:105342
,V/AlarmManager( 3513): waitForAlarm result :8
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3513): mDVFSHelper.release()
,I/PowerManagerService( 3513): [PWL] Off : 15s ago
,V/AlarmManager( 3513): waitForAlarm result :4
,V/AlarmManager( 3513): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 3513): <AppSync3 Whitelist>
,V/AlarmManager( 3513): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3696): handleTimeUpdate
,D/KeyguardEffectViewController( 3696): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3696): *** don't update sliding image ***
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3513): SIOP:: AP = 290, PST = 318, CUR = 81
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:81, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:108
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3513): waitForAlarm result :4
,D/SSRM:n  ( 3513): SIOP:: AP = 280, PST = 312, CUR = 81
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:90, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:97
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 30s ago
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3513): !@Sync 4
,D/SSRM:n  ( 3513): SIOP:: AP = 280, PST = 306, CUR = 90
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:85, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:84
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3513): SIOP:: AP = 270, PST = 302, CUR = 85
,I/PowerManagerService( 3513): [PWL] Off : 50s ago
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:78, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:80
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 270, PST = 300, CUR = 78
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:72, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:80
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 5
,D/SSRM:n  ( 3513): SIOP:: AP = 270, PST = 293, CUR = 72
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3513): waitForAlarm result :8
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3513): [PWL] Off : 75s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 270, PST = 291, CUR = 65
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4642): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3513): SIOP:: AP = 270, PST = 289, CUR = 59
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3513): !@Sync 6
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 282, CUR = 55
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3513): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3696): handleTimeUpdate
,D/KeyguardEffectViewController( 3696): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3696): *** don't update sliding image ***
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3513): waitForAlarm result :4
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3513): [PWL] Off : 105s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 274, CUR = 52
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3513): stay LED for fully charged
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 271, CUR = 49
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 7
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 268, CUR = 47
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3513): waitForAlarm result :8
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 266, CUR = 44
,I/PowerManagerService( 3513): [PWL] Off : 140s ago
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 265, CUR = 42
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3513): !@Sync 8
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 263, CUR = 40
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 263, CUR = 40
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3513): [PWL] Off : 180s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 262, CUR = 39,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 9
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 262, CUR = 39
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3513): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 261, CUR = 37
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 261, CUR = 36
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3513): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3513): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3513): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3513): initializing...
,I/TLC_TIMA_PKM_initialize( 3513): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 3513): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3513): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3513): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3513): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 3513): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3513): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3513): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 3513): device_id = 0x0
,I/TZ: mc_tlc_communication( 3513): tlc_open() was called
I/TZ: mc_tlc_communication( 3513): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3513): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3513): Opening the session
,I/TZ: mc_tlc_communication( 3513): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3513): Trustlet response is completed
,E/Watchdog( 3513): !@Sync 10
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 260, CUR = 35
,I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3513): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3513): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
W/ProcessCpuTracker( 3513): Skipping unknown process pid 11885
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3513): [PWL] Off : 225s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 260, CUR = 35
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 260, CUR = 33
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3513): !@Sync 11
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 260, CUR = 33
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 3513): SIOP:: AP = 260, PST = 260, CUR = 32
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 259, CUR = 32
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3513): [PWL] Off : 275s ago
,E/Watchdog( 3513): !@Sync 12
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 259, CUR = 32
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 258, CUR = 30
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 258, CUR = 30
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 13
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 257, CUR = 28
,V/AlarmManager( 3513): waitForAlarm result :8
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 256, CUR = 29
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 330s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 256, CUR = 28
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3513): !@Sync 14
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 256, CUR = 27
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 255, CUR = 27
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 255, CUR = 27
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3513): !@Sync 15
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 254, CUR = 27,
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 254, CUR = 25
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 390s ago,
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 253, CUR = 25
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 16
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 253, CUR = 26
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 253, CUR = 27
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 252, CUR = 24
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 17
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 252, CUR = 24
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 252, CUR = 23
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 251, CUR = 24
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 455s ago
,E/Watchdog( 3513): !@Sync 18
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 251, CUR = 22
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 251, CUR = 21
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 23
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 19
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 24
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 22
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 21
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,D/BatteryService( 3513): stay LED for fully charged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3513): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3513): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3513): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3513): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3513): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 3513): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 20
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 525s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 19
,W/ContextImpl( 3513): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3513): Killing 10782:com.android.mms/u0a52 (adj 15): bgCount ##31
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3513): stay LED for fully charged
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CountryDetector( 3513): No listener is left
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 20
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3513): !@Sync 21
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 20,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 21
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 20
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 22
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 21
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26,
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 19
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 600s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 18,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 23
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 20
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 24
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 16
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 25
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 19
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 680s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 19,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 26
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 18
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 27
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 28
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3513): [PWL] Off : 765s ago
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 29,
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/TimaService( 3513): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3513): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3513): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 30
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3513): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3513): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3513): Skipping unknown process pid 12297
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3513): !@Sync 31
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 15
,I/PowerManagerService( 3513): [PWL] Off : 855s ago
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 32
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14,
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 33
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 34
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 950s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3513): !@Sync 35
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12,
,E/Watchdog( 3513): !@Sync 36
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3513): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,E/Watchdog( 3513): !@Sync 37
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,I/art     ( 3513): Background sticky concurrent mark sweep GC freed 113394(10MB) AllocSpace objects, 323(5MB) LOS objects, 12% free, 53MB/61MB, paused 3.466ms total 130.237ms
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3513): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,E/Watchdog( 3513): !@Sync 38
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 12
,E/Watchdog( 3513): !@Sync 39
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/BatteryService( 3513): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 9
,D/TimaService( 3513): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3513): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3513): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3513): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3513): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3513): Updating Usage Statistics in DB @ 1457400745618
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	,at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
,W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3513): ::getAppControlDB: Exception to create DB
W/System.err( 3513): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3513): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3513): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3513): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3513): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3513): Done Updating Usage Statistics in DB @ 1457400745706
,E/Watchdog( 3513): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3513): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3513): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3513): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 10,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 11,
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 9
,E/Watchdog( 3513): !@Sync 41
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 10
,I/PowerManagerService( 3513): [PWL] Off : 1155s ago
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3513): stay LED for fully charged
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 10
,E/Watchdog( 3513): !@Sync 42
,D/BatteryService( 3513): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3513): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3513): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3513): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3513): Plugged
,I/MotionRecognitionService( 3513): setPowerConnected  = true
,D/BatteryService( 3513): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5631): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3513): SIOP:: AP = 250, PST = 250, CUR = 10
,TIME-OUT KILL (timeout was 1200000ms)
```
