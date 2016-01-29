#### Test 5761781115ba656_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
W/System.err( 3996): com.sec.android.fota.osp.http.RestClientException
W/System.err( 3996): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 3996): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 3996): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 3996): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3996): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3996): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3996): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3996): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3996): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 3996): Caused by: java.lang.NullPointerException
W/System.err( 3996): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 3996): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 3996): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 3996): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
W/System.err( 3996): 	... 8 more
I/SELinux ( 4013): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4013):  
--------- beginning of /dev/log/system
I/ActivityManager(  749): Killing 2886:com.wssyncmldm/1000 (adj 15): empty #43
I/SELinux ( 4013): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4013):  
I/SELinux ( 4013):  
I/SELinux ( 4013): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4013): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4013): >>>>> Normal User
E/dalvikvm( 4013): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 4013): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4013): in addTimaSignatureService
D/TimaKeyStoreProvider( 4013): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4013): Added TimaKesytore provider
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4013, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
D/KLMS-2.3.201 : ( 4013): KLMSValidator() : checkQATesting()
I/KLMS-2.3.201 : ( 4013): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454056099394
I/KLMS-2.3.201 : ( 4013): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
I/ActivityManager(  749): Killing 1708:com.google.android.partnersetup/u0a14 (adj 15): empty #43
I/SELinux ( 4028): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4028):  
D/dalvikvm(  240): GC_EXPLICIT freed 46K, 50% free 9506K/18972K, paused 2ms+2ms, total 26ms
I/SELinux ( 4028): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4028):  
I/SELinux ( 4028):  
I/SELinux ( 4028): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+3ms, total 20ms
E/SELinux ( 4028): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4028): >>>>> Normal User
E/dalvikvm( 4028): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
E/SELinux ( 4028): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4028): in addTimaSignatureService
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+3ms, total 21ms
D/TimaKeyStoreProvider( 4028): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4028): Added TimaKesytore provider
D/SO_AGENT( 4028): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 4028): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4028, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4045): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4045):  
I/ActivityManager(  749): Killing 2936:com.samsung.android.intelligenceservice/u0a5 (adj 15): empty #43
I/SELinux ( 4045): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4045):  
I/SELinux ( 4045):  
I/SELinux ( 4045): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4045): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4045): >>>>> Normal User
E/dalvikvm( 4045): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4045): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4045): in addTimaSignatureService
D/TimaKeyStoreProvider( 4045): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4045): Added TimaKesytore provider
I/SELinux ( 4065): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4065):  
I/ActivityManager(  749): Killing 2964:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #43
I/SELinux ( 4065): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4065):  
I/SELinux ( 4065):  
I/SELinux ( 4065): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4065): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4065): >>>>> Normal User
E/dalvikvm( 4065): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 4065): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 4065): in addTimaSignatureService
D/TimaKeyStoreProvider( 4065): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4065): Added TimaKesytore provider
,V/AlarmManager(  749): waitForAlarm result :8
E/SPPClientService( 4065): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4065): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 4065): PushLog.txt file is not deleted.
D/SPPClientService( 4065): PushLog.txt file is not deleted.
D/SPPClientService( 4065): ============PushLog. stop!
I/SELinux ( 4081): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4081):  
I/ActivityManager(  749): Killing 2983:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 4081): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4081):  
I/SELinux ( 4081):  
I/SELinux ( 4081): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4081): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4081): >>>>> Normal User
E/dalvikvm( 4081): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4081): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4081): in addTimaSignatureService
D/TimaKeyStoreProvider( 4081): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4081): Added TimaKesytore provider
V/AlarmManager(  749): waitForAlarm result :8
I/SA      ( 4081): [SSP] onCreated
I/SA      ( 4081): [TPM] There is no property file
I/SA      ( 4081): [SCU] isHaveSA() - false
I/SA      ( 4081): [TPM] getModelProperty : null
I/SA      ( 4081): [TPM] getCSCProperty : null
I/SA      ( 4081): [DM] init START
I/SA      ( 4081): [DM] This device is not a Vodafone
I/SA      ( 4081): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4081): support phone number id : false
I/SA      ( 4081): [DM] init END
I/SA      ( 4081): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4081): [BDLM] already registered in spp
I/SA      ( 4081): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4081): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4081): [SLFUCHKMGR] constructor called
I/SA      ( 4081): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4081): [OR] == isSIMCardReady false ==
I/SA      ( 4081): [SCU] == networkStateCheck == true
I/SA      ( 4081): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4081): isChinaCountryCode : false
I/SA      ( 4081): [OR] == networkStateCheck true ==
I/SA      ( 4081): [OR] GetMyCountryZoneTask
I/SA      ( 4081): [OR] onReceive END
I/SA      ( 4081): [SRS] prepareGetMyCountryZone
I/SA      ( 4081): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/ActivityManager(  749): Killing 3000:com.wssnps/1000 (adj 15): empty #43
D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
I/SA      ( 4081): [SSP] query invoked
D/PowerManagerService(  749): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1068 (0x0)
I/SELinux ( 4107): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4107):  
I/SA      ( 4081): [TPMU] GetMccFromDB : null
I/SA      ( 4081): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4081): [TPM] isNoProxy(default) : true
I/SA      ( 4081): [RC New] Execute method=[GET] start
D/AndroidRuntime( 4079): 
D/AndroidRuntime( 4079): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4079): CheckJNI is OFF
D/AndroidRuntime( 4079): setted country_code = Poland
D/AndroidRuntime( 4079): setted countryiso_code = PL
D/AndroidRuntime( 4079): setted sales_code = XEO
D/AndroidRuntime( 4079): readGMSProperty: start
D/AndroidRuntime( 4079): readGMSProperty: already setted!!
D/AndroidRuntime( 4079): readGMSProperty: end
D/AndroidRuntime( 4079): addProductProperty: start
I/SELinux ( 4107): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4107):  
I/SELinux ( 4107):  
I/SELinux ( 4107): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4107): >>>>> Normal User
E/dalvikvm( 4107): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
D/dalvikvm( 4079): Trying to load lib libjavacore.so 0x0
E/SELinux ( 4107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 4079): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4079): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4079): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4079): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/TimaKeyStoreProvider( 4107): in addTimaSignatureService
I/System.out( 4081): Thread-389(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/TimaKeyStoreProvider( 4107): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4107): Added TimaKesytore provider
I/System.out( 4081): Thread-389(ApacheHTTPLog):isShipBuild true
I/System.out( 4081): Thread-389(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/memtrack( 4079): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4079): failed to load memtrack module: -2
D/dalvikvm( 4079): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm(  749): GC_CONCURRENT freed 7546K, 20% free 41995K/52052K, paused 7ms+23ms, total 252ms
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 96ms
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 117ms
D/AndroidRuntime( 4079): Calling main entry com.android.commands.am.Am
I/sCloudBackupApp( 4107): sCloudBackupApp Version Info : 3.7.3.KK_APP
I/SCloudBackupReceiver( 4107): Other Intent
I/ActivityManager(  749): Killing 3018:com.samsung.android.app.accesscontrol/u0a64 (adj 15): empty #43
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/accuweather( 1449): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1449): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/accuweather( 1449): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/accuweather( 1449): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
I/SELinux ( 4130): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4130):  
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/AndroidRuntime( 4079): Shutting down VM
D/dalvikvm( 4079): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 1ms+0ms, total 4ms
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
I/SELinux ( 4130): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4130):  
I/SELinux ( 4130):  
I/SELinux ( 4130): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4130): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 4130): >>>>> Normal User
E/dalvikvm( 4130): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
E/SELinux ( 4130): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/TimaKeyStoreProvider( 4130): in addTimaSignatureService
D/TimaKeyStoreProvider( 4130): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4130): Added TimaKesytore provider
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4130, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  749): Killing 3050:com.sec.android.nearby.mediaserver/u0a70 (adj 15): empty #43
I/SELinux ( 4144): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4144):  
E/SMD     (  233): DCD ON
,I/SELinux ( 4144): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4144):  
I/SELinux ( 4144):  
,I/SELinux ( 4144): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4144): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4144): >>>>> Normal User
,E/dalvikvm( 4144): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 4144): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  749): Killing 3066:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
D/PowerManagerService(  749): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=749 (0x0)
D/PowerManagerService(  749): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=749, ws=WorkSource{1000}) (elapsedTime=3463)
D/PowerManagerService(  749): [s] UserActivityState : 0 -> 1
,D/TimaKeyStoreProvider( 4144): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4144): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4144): Added TimaKesytore provider
,D/HeadlinesChannelApplication( 4144): [onCreate]
,D/Headlines( 4144): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4144, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,D/HeadlinesChannelUtil( 4144): getCountryCode(): countryCode = PL
,D/Headlines( 4144): Breath.onCreate
D/HeadlinesCardManager( 4144): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 4144): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 4144): CardProvider Library : 13
,I/SELinux ( 4156): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4156):  
,I/SELinux ( 4160): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4160):  
,I/SELinux ( 4156): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4156):  
I/SELinux ( 4156):  
,I/SELinux ( 4156): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4156): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4156): >>>>> Normal User
,E/dalvikvm( 4156): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 4156): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4156): in addTimaSignatureService
I/SELinux ( 4160): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4160):  
I/SELinux ( 4160):  
,I/SELinux ( 4160): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/TimaKeyStoreProvider( 4156): Cannot add TimaSignature Service, License check Failed
,E/SELinux ( 4160): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4160): >>>>> Normal User
,E/dalvikvm( 4160): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,D/ActivityThread( 4156): Added TimaKesytore provider
,E/SELinux ( 4160): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4160): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4160): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4160): Added TimaKesytore provider
,D/MagazineService Version( 4160): Magazine-Channel: 13
,D/MagazineService Version( 4160): Magazine-Provider: 13
,D/MagazineService Version( 4160): Magazine-Administrator: 11
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4160, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/HeadlinesChannelApplication( 4160): [onCreate]
,D/MagazineService::CardProviderContentProvider( 4160): insertProvider: provider already exists.: com.samsung.android.app.headlines
,I/SA      ( 4081): [RC New] [v2liruge] api execute + 1012
,I/SA      ( 4081): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4081): AsyncTask #1 calls detatch()
,I/SA      ( 4081): [TPMU] getNetworkMcc : 
I/SA      ( 4081): [SCU] saveMccToPreferece Start
,I/SA      ( 4081): [SCU] RegionMCC : 260
,I/SA      ( 4081): [SSP] query invoked
,I/SA      ( 4081): [TPMU] GetMccFromDB : null
I/SA      ( 4081): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4081): [SCU] saveMccToPreferece End
,I/SA      ( 4081): [RC New] executeRequest [v2liruge] end. 1028
,I/SA      ( 4081): [RC New] Execute end
I/SA      ( 4081): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4081): [OR] GetMyCountryZoneTask Success
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/MagazineService::CardProviderContentProvider( 4160): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 4144): registerCardProvider: provider already exists.
,I/Headlines( 4144): HeadlinesDataCenter ctor
I/Headlines( 4144): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 4144): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 4144): HeadlinesCardManager : constructor welcome :YES
,D/Headlines( 4144): Breath timer started. interval : 30000
D/Headlines( 4144): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4144): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4144): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4144): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4144): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 4144): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4144): requestUpdateNewsWelcomeCard !!! no welcome card
,I/ActivityManager(  749): Killing 3079:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #43
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4156): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4156): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  239): id=15 Removed Uoast (12/12)
I/SurfaceFlinger(  239): id=15 Removed Uoast (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/GAV2    ( 4156): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4156): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4156): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 4156): Binding Chromium to the main looper Looper (main, tid 1) {4231b228}
,I/chromium( 4156): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4156): Initializing chromium process, renderers=0
,V/AlarmManager(  749): waitForAlarm result :8
,W/chromium( 4156): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4156): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4156): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4156): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4156): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4156): Remote Branch: 
I/Adreno-EGL( 4156): Local Patches: 
I/Adreno-EGL( 4156): Reconstruct Branch: 
,W/linker  ( 3579): libcordon.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/dalvikvm( 3579): No JNI_OnLoad found in /system/lib/libcordon.so 0x426429f0, skipping init
D/SSRMv2:SIOP(  749): SIOP:: AP = 330, Delta = 10
,I/NSApplication( 4156): Starting up...
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4156, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4204):  
I/ActivityManager(  749): Killing 3091:com.blurb.checkout/u0a75 (adj 15): empty #43
,I/SELinux ( 4204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4204):  
I/SELinux ( 4204):  
,I/SELinux ( 4204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4204): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4204): >>>>> Normal User
,E/dalvikvm( 4204): >>>>> com.google.android.apps.plus [ userId:0 | appId:10130 ]
,E/SELinux ( 4204): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4204): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4204): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4204): Added TimaKesytore provider
,D/SensorService(  749):   -0.0 -0.1 9.6
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4204, uid=10130 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3344): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3344): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3344): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4264b538
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,I/SELinux ( 4232): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4232):  
,I/SELinux ( 4232): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4232):  
I/SELinux ( 4232):  
,I/SELinux ( 4232): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4232): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4232): >>>>> Normal User
,E/dalvikvm( 4232): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4232): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 4204): GC_CONCURRENT freed 3685K, 27% free 14001K/18972K, paused 2ms+1ms, total 32ms
,D/dalvikvm( 4204): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4204): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/TimaKeyStoreProvider( 4232): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4232): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4232): Added TimaKesytore provider
,I/ActivityManager(  749): Killing 3107:com.sec.knox.bridge/1000 (adj 15): empty #43
I/dalvikvm( 3579): Total arena pages for JIT: 11
I/dalvikvm( 3579): Total arena pages for JIT: 12
I/dalvikvm( 3579): Total arena pages for JIT: 13
I/dalvikvm( 3579): Total arena pages for JIT: 14
,D/dalvikvm( 4204): GC_FOR_ALLOC freed 16K, 16% free 16079K/18972K, paused 17ms, total 17ms
,D/dalvikvm( 4204): GC_FOR_ALLOC freed 6K, 13% free 20240K/23140K, paused 13ms, total 13ms
,D/WaitQueueForNetworkActivate( 4232): notifyNetworkActivated
,W/ContextImpl( 4232): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
I/ActivityManager(  749): Waited long enough for: ServiceRecord{4322c628 u0 com.sec.knox.seandroid/.service.SEAndroidLauncher}
W/ActivityManager(  749): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 4232): AutoUpdateManager:IDLE:execute
I/dalvikvm( 4232): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4232): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4232): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4232): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4232): exit::IDLE
,D/InitializeManagerStateMachine( 4232): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4232): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4232): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4232): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4232): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4232): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4232): entry::SUCCESS
D/hcjo    ( 4232): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4232): AutoUpdateTriggerManager:IDLE:setInterval:345600000
D/hcjo    ( 4232): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4232): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4232): exit::SUCCESS
,D/InitializeManagerStateMachine( 4232): entry::IDLE
,I/ActivityManager(  749): Killing 3120:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,D/dalvikvm( 1289): GC_EXPLICIT freed 1196K, 44% free 10739K/18972K, paused 4ms+5ms, total 34ms
,I/iu.SyncManager( 1642): SYNC; picasa accounts
,D/NetworkLogImpl( 1642): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1642): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1642): num queued entries: 0
,I/iu.UploadsManager( 1642): num updated entries: 0
,I/iu.SyncManager( 1642): NEXT; no task
,I/SELinux ( 4256): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4256):  
,D/YouTube ( 3624): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3624): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3624): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
,D/dalvikvm(  240): GC_EXPLICIT freed 43K, 50% free 9506K/18972K, paused 2ms+3ms, total 28ms
,I/SELinux ( 4256): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4256):  
I/SELinux ( 4256):  
,I/SELinux ( 4256): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4256): >>>>> Normal User
E/dalvikvm( 4256): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+3ms, total 20ms
,E/SELinux ( 4256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3903): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 3903): [hasSamungAccount] - No Samsung Account
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 3ms+2ms, total 21ms
,D/TimaKeyStoreProvider( 4256): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4256): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4256): Added TimaKesytore provider
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/linker  ( 3903): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/CSTORAGE( 3903): ================================================
I/CSTORAGE( 3903):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 3903): ================================================
D/dalvikvm( 3903): No JNI_OnLoad found in /system/lib/libterrier.so 0x42642670, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3903): [GetString-S]
,I/terrier ( 3903): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 3903): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 3903): App is not loaded in QSEE
,D/QSEECOMAPI: ( 3903): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 3903): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 3903): QSEECom_shutdown_app, app_id = 3
E/terrier ( 3903): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3903): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 3903): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3903): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3903): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 3903): [ensureRegistration] - No Samsung account
,D/BootCompletedReceiver(  749): onReceive
I/ActivityManager(  749): Killing 3138:com.samsung.android.app.colorblind/1000 (adj 15): empty #43
,I/KLMS-2.3.201 : ( 4013): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 4013): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1454056102887
,I/KLMS-2.3.201 : ( 4013): StateImplV2() : dateTimeChanged() : Fri Jan 29 09:28:22 CET 2016
,I/SELinux ( 4273): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4273):  
,I/SELinux ( 4273): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4273):  
I/SELinux ( 4273):  
,I/SELinux ( 4273): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4273): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4273): >>>>> Normal User
,E/dalvikvm( 4273): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
,E/SELinux ( 4273): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4273): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4273): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4273): Added TimaKesytore provider
,D/dalvikvm(  749): GC_FOR_ALLOC freed 7308K, 19% free 42166K/52052K, paused 207ms, total 207ms
D/AmoledAdjustTimer(  749): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
D/ConnectivityService(  749): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4273, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
,W/ContextImpl( 4273): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 4298): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4298):  
,E/Device Type Shared Preferences( 4273): Device Type Shared Preferences - getDeviceTypeChecked -true
,E/Device Type Shared Preferences( 4273): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 4273): ContentProvider is not null
,I/SELinux ( 4298): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4298):  
I/SELinux ( 4298):  
,I/SELinux ( 4298): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4298): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4298): >>>>> Normal User
,E/dalvikvm( 4298): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 4298): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4298): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4298): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4298): Added TimaKesytore provider
I/ActivityManager(  749): Waited long enough for: ServiceRecord{431e0870 u0 com.samsung.android.sconnect/.periph.PeriphService}
,V/MediaPlayer( 4273): decode(61, 33979084, 48105)
,V/MediaPlayerService(  242): decode(35, 33979084, 48105)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
,V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebcca8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
,V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8ebcca8, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  242): notify(0xb8ebcca8, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebcca8, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebcca8, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
,V/MediaPlayerService(  242): wait for playback complete
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  242): postAudioEOS delayUs (0)
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4298, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebcca8, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebcca8, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebcca8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(63, 33914984, 10421)
V/MediaPlayerService(  242): decode(35, 33914984, 10421)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242),: setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea6220, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(64, 37457308, 34198)
V/MediaPlayerService(  242): decode(35, 37457308, 34198)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/dalvikvm( 4298): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4263da40, skipping init
I/SecureStorage( 4298): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4298): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
I/SecureStorage(  290): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4298
I/SecureStorage(  290): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4298): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 4298): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  290): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4298
I/SecureStorage(  290): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea7988, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(65, 33862452, 7405)
V/MediaPlayerService(  242): decode(35, 33862452, 7405)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
I/AudioPlayer(  242): First fillBuffer call!!
I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaa8a8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(66, 37547940, 5555)
V/MediaPlayerService(  242): decode(35, 37547940, 5555)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
I/AudioPlayer(  242): First fillBuffer call!!
I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eab528, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(67, 30367732, 5085)
V/MediaPlayerService(  242): decode(35, 30367732, 5085)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (,8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
,V/MediaPlayerService(  242): wait for playback complete
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(68, 30372876, 21552)
,V/MediaPlayerService(  242): decode(35, 30372876, 21552)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
,V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
,V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
,V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
,I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 1, 0, 0)
V/AudioCache(  242): prepared
,V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
,I/AudioPlayer(  242): First fillBuffer call!!
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(69, 37543652, 4230)
V/MediaPlayerService(  242): decode(35, 37543652, 4230)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  242): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
,V/MediaPlayerService(  242): wait for playback complete
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebd368, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
,V/MediaPlayer( 4273): decode(70, 30337076, 9400)
V/MediaPlayerService(  242): decode(35, 30337076, 9400)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear,
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1,
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port,
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 5, 0, 0)
,V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
,V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0),
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache(  242): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
,V/MediaPlayerService(  242): wait for playback complete
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea2ca0, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(71, 33925464, 44276)
,V/MediaPlayerService(  242): decode(35, 33925464, 44276)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
,V/MediaPlayerService(  242): wait for playback complete
,D/SO_AGENT( 4028): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 4028): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4081): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca80, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
,V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
,V/MediaPlayer( 4273): decode(72, 33885672, 29256)
V/MediaPlayerService(  242): decode(35, 33885672, 29256)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca28, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca28, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca28, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca28, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca28, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
,V/MediaPlayerService(  242): wait for playback complete
,E/SMD     (  233): DCD ON
,I/SELinux ( 4368): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4368):  
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  242): postAudioEOS delayUs (0)
,V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca28, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
,V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eaca28, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  242): notify(0xb8eaca28, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,I/ActivityManager(  749): Killing 3157:com.dropbox.android/u0a91 (adj 15): empty #43
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(73, 37491572, 52024)
V/MediaPlayerService(  242): decode(35, 37491572, 52024)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242):, wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  242): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
I/AudioPlayer(  242): First fillBuffer call!!
I/SELinux ( 4368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4368):  
I/SELinux ( 4368):  
I/SELinux ( 4368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4368): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4368): >>>>> Normal User
E/dalvikvm( 4368): >>>>> com.android.mms [ userId:0 | appId:10048 ]
E/SELinux ( 4368): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4368): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4368): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4368): Added TimaKesytore provider
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 7, 0, 0)
V/AudioCache(  242): ignored
,V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ea5390, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
,V/MediaPlayer( 4273): decode(74, 33969800, 9226)
,V/MediaPlayerService(  242): decode(35, 33969800, 9226)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
,W/dalvikvm( 4368): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 200, 973, 0)
V/AudioCache(  242): ignored
,V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
,I/AudioPlayer(  242): First fillBuffer call!!
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  242): postAudioEOS delayUs (0)
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 7, 0, 0)
V/AudioCache(  242): ignored
,V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8eb6ba8, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/MediaPlayer( 4273): decode(75, 30402580, 4509)
V/MediaPlayerService(  242): decode(35, 30402580, 4509)
V/MediaPlayerService(  242): player type = 3
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): constructor
V/AwesomePlayer(  242): setDefault
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): StagefrightPlayer
V/AwesomePlayer(  242): setListener
V/StagefrightPlayer(  242): initCheck
V/AwesomePlayer(  242): setAudioSink
V/StagefrightPlayer(  242): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  242): mBitrate = -1 bits/sec
V/AwesomePlayer(  242): current audio track index (0) is added to vector
V/AwesomePlayer(  242): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  242): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  242): prepare
V/AwesomePlayer(  242): prepareAsync
V/MediaPlayerService(  242): wait for prepare
V/AwesomePlayer(  242): onPrepareAsyncEvent
I/SecMediaClock(  242): SecMediaClock constructor
I/SecMediaClock(  242): reset
V/AwesomePlayer(  242): initAudioDecoder
V/AwesomePlayer(  242): checkOffloadExceptions is true
,I/OMXCodec(  242): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  242): mDispatchers.add
I/OMXCodec(  242): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  242): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  242): finishAsyncPrepare_l
V/AwesomePlayer(  242): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 200, 973, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 5, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 1, 0, 0)
V/AudioCache(  242): prepared
V/AudioCache(  242): wait - success
V/MediaPlayerService(  242): start
V/StagefrightPlayer(  242): start
V/AwesomePlayer(  242): play
V/AwesomePlayer(  242): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  242): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  242): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  242): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  242): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  242):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  242): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  242): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 6, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): addBatteryData
V/MediaPlayerService(  242): wait for playback complete
V/AwesomePlayer(  242): postAudioEOS delayUs (0)
D/dalvikvm( 3579): GC_CONCURRENT freed 6871K, 43% free 10816K/18972K, paused 3ms+23ms, total 144ms
V/AwesomePlayer(  242): onCheckAudioStatus
V/AwesomePlayer(  242): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  242): onStreamDone
V/AwesomePlayer(  242): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  242): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 2, 0, 0)
V/AudioCache(  242): playback complete - thread will wake up later
V/AwesomePlayer(  242): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 7, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  242): addBatteryData
V/AudioCache(  242): wait - success
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  242): notify(0xb8ebccf0, 8, 0, 0)
V/AudioCache(  242): ignored
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  242): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  242): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  242): instance freeNode
I/AudioPlayer(  242): reset out
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  242): SecMediaClock destructor
V/AwesomePlayer(  242): mSecMediaClock clear
V/StagefrightPlayer(  242): ~StagefrightPlayer
V/StagefrightPlayer(  242): reset
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
V/AwesomePlayer(  242): destructor
V/AwesomePlayer(  242): reset_l()
V/AwesomePlayer(  242): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  242): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  242): mAudioTrackVector clear
V/AwesomePlayer(  242): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  242): mSecMediaClock clear
D/Mms/MmsApp( 4368): [start]    onCreate()
,D/Mms/TelephonyPermission( 4368): start operation mode monitor
,D/Mms/TelephonyPermission( 4368): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4368): isDefault true
,D/Mms/MmsApp( 4368): onCreate() com.android.mms
,D/Mms/MmsConfig( 4368): before partial update
,D/Mms/MmsConfig( 4368): Load Resize quality : 80
,D/Mms/MmsConfig( 4368):  enable multiwindow = false
,E/Mms/MessageUtils( 4368): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 4368): updateCountryIso : update country iso info 
D/CountryDetector(  749): The first listener is added
,D/TP/MmsSmsProvider( 1240): match 13:Elapsed time : 1.138 ms
,D/Mms/Conversation( 4368): init()
,D/TP/MmsSmsProvider( 1240): match 12:Elapsed time : 1.681 ms
,D/TP/MmsSmsProvider( 1240): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1240): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/TP/MmsSmsProvider( 1240): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1240): need read changed broadcast:false
,I/Mms/ReservationManager( 4368): ReservationManager()
,I/Mms/ReservationManager( 4368): resetAfterConnected()
,D/TP/MmsSmsProvider( 1240): match 7:Elapsed time : 3.670 ms
,I/Mms/ReservationManager( 4368): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 4368): [end]    onCreate()
,D/Mms/MessagingNotification( 4368): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/DownloadManager( 4368): Service state changed: Bundle[mParcelledData.dataSize=740]
,D/Mms/MessagingNotification( 4368): sDisableVibrateForCamera = false
D/Mms/DownloadManager( 4368): roaming ------> false
,D/Mms/DownloadManager( 4368): mAutoDownloadSecondary ------> true
D/Mms/MessagingNotification( 4368): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 4368): isDefault true
,I/SELinux ( 4402): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4402):  
,D/TP/MmsSmsProvider( 1240): match 8:Elapsed time : 23.480 ms
I/ActivityManager(  749): Killing 3178:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,D/TP/MmsSmsProvider( 1240): match 200:Elapsed time : 1.249 ms
,I/SELinux ( 4402): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4402):  
I/SELinux ( 4402):  
,I/SELinux ( 4402): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4402): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4402): >>>>> Normal User
,E/dalvikvm( 4402): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 4402): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BadgeProvider( 1337): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 4402): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4402): Cannot add TimaSignature Service, License check Failed
,D/Launcher.Model( 1251): reloadBadges entered.
D/ActivityThread( 4402): Added TimaKesytore provider
D/BadgeProvider( 1337): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 1337): sendNotify, [notify] : null
D/BadgeProvider( 1337): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1337): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 4368): setBadgeCount(), count=0
,D/MessagingNotification( 4368): remove alarm
,D/Mms/MessagingNotification( 4368): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 4368): [end]    nonBlockingUpdateMessageIndicator()
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4402, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  749): Killing 3191:com.sec.android.fwupgrade/1000 (adj 15): empty #43
,I/SELinux ( 4417): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4417):  
,I/ Time Manager ( 4402): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 4417): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4417):  
I/SELinux ( 4417):  
,I/SELinux ( 4417): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4417): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4417): >>>>> Normal User
,E/dalvikvm( 4417): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 4417): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4417): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4417): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4417): Added TimaKesytore provider
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
,D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
,D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 4429): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4429):  
I/ActivityManager(  749): Killing 3207:com.sec.factory.camera/1000 (adj 15): empty #43
,I/SELinux ( 4429): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4429):  
I/SELinux ( 4429):  
,I/SELinux ( 4429): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4429): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4429): >>>>> Normal User
,E/dalvikvm( 4429): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 4429): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4429): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4429): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4429): Added TimaKesytore provider
,D/dalvikvm( 3579): GC_CONCURRENT freed 2441K, 46% free 10382K/18972K, paused 3ms+15ms, total 42ms
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4429, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 4429): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/elm:14132( 4429): ELMEngine.ELMEngine( context ).
D/elm:14132( 4429): MDMBridge.setEnterpriseBridge()
D/elm:14132( 4429): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
I/knox    ( 3281): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 4429): ElmAgentService : onCreate()
,D/elm:14132( 4429): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/knox    ( 3281): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 3281): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 4429): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 4429): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 4429): ModuleBase.resetCalllogAPIAlarm()
W/ContextImpl( 3281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 3281): KNOXAgentService : onCreate()
,D/knox    ( 3281): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3281): KNOXAgentService. startJobThread() start
D/knox    ( 3281): KNOXAgentService. JobThread()
D/knox    ( 3281): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3281): KNOXAgentService. startJobThread() wait
,I/SELinux ( 4444): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4444):  
D/knox    ( 3281): KNOXAgentService : onDestroy().
D/knox    ( 3281): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 4429): ModuleBase.ModifySetAlarm()
D/elm:14132( 4429): MDMBridge.getInstance()
D/elm:14132( 4429): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 4429): ElmAgentService : onDestroy().
I/ActivityManager(  749): Killing 3219:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #43
,I/SELinux ( 4444): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4444):  
I/SELinux ( 4444):  
,I/SELinux ( 4444): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4444): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 4444): >>>>> Normal User
,E/dalvikvm( 4444): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 4444): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 4444): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4444): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4444): Added TimaKesytore provider
,I/SecureStorage(  290): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  290): [INFO]: SPID(0x00000003)PID: 4298, TID: 4298
,D/SensorService(  749):   -0.0 -0.1 9.6
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4444, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4458): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4458):  
I/ActivityManager(  749): Killing 3235:com.google.android.talk/u0a105 (adj 15): empty #43
,I/SecureStorage( 4298): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4298): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4298): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4298): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4298): Open platform.db in secure mode
I/SELinux ( 4458): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4458):  
I/SELinux ( 4458):  
,I/SELinux ( 4458): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4458): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4458): >>>>> Normal User
,E/dalvikvm( 4458): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 4458): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4458): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4458): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4458): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4458, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 4458): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42642bc0, skipping init
D/TimeService( 4458): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454056105252
D/        ( 4458): TimeServiceNative: User Time to be set is 1454056105252
D/QC-time-services( 4458): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4458): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4458): Lib:time_genoff_operation: pargs->ts_val = 1454056105252
D/QC-time-services(  282): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4458): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  282): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  282): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454056105252
D/QC-time-services(  282): Daemon:genoff_opr: Base = 2, val = 1454056105252, operation = 0
D/QC-time-services(  282): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/5/70 0:25:9
D/QC-time-services(  282): Daemon:Value read from RTC seconds = 5444709000
D/QC-time-services(  282): Daemon:new time 1454056105252 
D/QC-time-services(  282): Daemon: delta 1448611396252 genoff 1448611396252 
D/QC-time-services(  282): Daemon:genoff_persistent_update: Writing genoff = 1448611396252 to memory
D/QC-time-services(  282): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  282): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  282): Updating the TOD offset
D/QC-time-services(  282): Daemon:genoff_persistent_update: Writing genoff = 1448611396252 to memory
D/QC-time-services(  282): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  282): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  282): Daemon:Update to modem bit set
D/QC-time-services(  282): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  282): Daemon: Base = 2, Value being sent to MODEM = 1138091305252
,E/QC-time-services( 4458): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  282): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  282): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  749): Killing 3264:com.samsung.helphub/1000 (adj 15): empty #43
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/SQLiteSecureOpenHelper( 4298): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4298): ...getDatabaseLocked(b,b,pwd)
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1466): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1466): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
I/Process ( 3579): Sending signal. PID: 3579 SIG: 9
,D/comsamsunglog( 1466): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1466): [MSC_Daemon]>>> ====================================================================================================================
,W/ContextImpl( 3579): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1659 android.content.ContextWrapper.sendStickyBroadcast:439 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:841 <bottom of call stack> 
D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1466): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/ActivityManager(  749): Process com.sec.android.app.sysscope (pid 3579) (adj 0) has died.
,D/comdaemonstockapp( 1466): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1466): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/ActivityManager(  749): Killing 3296:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #43
,I/CheckinService( 1642): Checkin interval check for package: unspecified last checkin: 1453985581353 min interval config: 0 actual interval: 70524002
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 1466): [MSC_Daemon]>>> ====================================================================================================================
,D/dalvikvm( 1466): GC_CONCURRENT freed 7436K, 47% free 10188K/18972K, paused 3ms+3ms, total 35ms
D/comsamsunglog( 1466): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1466): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1466): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4474): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4474):  
I/ActivityManager(  749): Waited long enough for: ServiceRecord{431b4a88 u0 tv.peel.smartremote/tv.peel.samsung.widget.service.WidgetTimerService}
,I/SELinux ( 4474): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4474):  
I/SELinux ( 4474):  
,I/SELinux ( 4474): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4474): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4474): >>>>> Normal User
,E/dalvikvm( 4474): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
,E/SELinux ( 4474): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:26, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/TimaKeyStoreProvider( 4474): in addTimaSignatureService
D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/TimaKeyStoreProvider( 4474): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4474): Added TimaKesytore provider
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4474, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
,E/SPPClientService( 4065): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,I/SELinux ( 4499): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4499):  
I/ActivityManager(  749): Killing 3309:com.LocalFota/u0a110 (adj 15): empty #43
,I/ActivityManager(  749): Waited long enough for: ServiceRecord{43175cc0 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/SELinux ( 4499): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4499):  
I/SELinux ( 4499):  
,I/SELinux ( 4499): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4499): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4499): >>>>> Normal User
,E/dalvikvm( 4499): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10038 ]
,E/SELinux ( 4499): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4499): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4499): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4499): Added TimaKesytore provider
,E/SPPClientService( 4499): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4499): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 4499): PushLog.txt file is not deleted.
D/SPPClientService( 4499): PushLog.txt file is not deleted.
,D/SPPClientService( 4499): ============PushLog. stop!
,I/ActivityManager(  749): Killing 3327:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/SELinux ( 4515): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4515):  
,D/dalvikvm(  240): GC_EXPLICIT freed 42K, 50% free 9506K/18972K, paused 2ms+3ms, total 27ms
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+2ms, total 18ms
,I/SELinux ( 4515): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4515):  
I/SELinux ( 4515):  
,I/SELinux ( 4515): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4515): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4515): >>>>> Normal User
,E/dalvikvm( 4515): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10038 ]
,E/SELinux ( 4515): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 1ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 4515): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4515): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4515): Added TimaKesytore provider
,I/Mms/MmsApp( 4368):  start initViewCache mms
,D/PackageManager(  749): Time to collect certificates: 14.232 seconds
,D/ApplicationPolicy(  749): isApplicationInstallationEnabled
,W/PackageManager(  749): verifying app can be installed or not
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy(  749): isApplicationInstallationEnabled :  enabled true
D/PackageManager(  749): Existing package: 
D/PackageManager(  749): doRename: 
D/PackageManager(  749): doRename apk path: 
D/PackageManager(  749): installNewPackageLI: 
I/MyContainer(  749): package (com.test.thalitest) installed with  seinfo=default
I/PackageManager(  749): Package com.test.thalitest codePath changed from /data/app/com.test.thalitest-9.apk to /data/app/com.test.thalitest-10.apk; Retaining data and using new
W/MyContainer(  749):  assignseinfovalue, <package name > = com.test.thalitest<seinfo> = default<category> = 1023<allow category> = 0,501-1023
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm(  749): GC_EXPLICIT freed 5299K, 20% free 42128K/52052K, paused 6ms+22ms, total 237ms
,I/GAV2    ( 4156): Thread[GAThread,5,main]: No campaign data found.
,E/SPPClientService( 4515): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4515): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 4515): PushLog.txt file is not deleted.
,D/SPPClientService( 4515): PushLog.txt file is not deleted.
,D/SPPClientService( 4515): ============PushLog. stop!
,E/LNoti   ( 4515): [PhoneStatusChangeReceiver] This device doesn't register yet.
I/ActivityManager(  749): Killing 3379:com.sec.android.app.camera/u0a147 (adj 15): empty #43
,D/Mms/ComposeMessageFragment( 4368): fillCache, easy = false
D/daemonapp( 1466): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1466): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 1466): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1466): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1466): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1466): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 1466): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 1466): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 1466): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1466): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/AbsListView( 4368): Get MotionRecognitionManager
,D/MotionRecognitionService(  749):  ssp status : false
,I/dalvikvm( 4368): Could not find method android.sec.multiwindow.MultiWindow.createInstance, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4368): VFY: unable to resolve static method 1402: Landroid/sec/multiwindow/MultiWindow;.createInstance (Landroid/app/Activity;)Landroid/sec/multiwindow/MultiWindow;
,D/dalvikvm( 4368): VFY: replacing opcode 0x71 at 0x03bb
I/dalvikvm( 4368): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4368): VFY: unable to resolve virtual method 1403: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 4368): VFY: replacing opcode 0x74 at 0x0759
I/dalvikvm( 4368): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4368): VFY: unable to resolve virtual method 1403: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 4368): VFY: replacing opcode 0x74 at 0x07e8
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,V/WebViewChromium( 4368): Binding Chromium to the main looper Looper (main, tid 1) {42317400}
,I/chromium( 4368): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4368): Initializing chromium process, renderers=0
,W/chromium( 4368): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4368): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4368): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4368): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4368): Remote Branch: 
I/Adreno-EGL( 4368): Local Patches: 
I/Adreno-EGL( 4368): Reconstruct Branch: 
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4368): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4368): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4368): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4368): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/Mms/BubbleViewCache( 4368): fillCache bubble = 8
,D/Mms/Synchronizer( 4368): [start]    dbSync()
,D/TP/MmsSmsProvider( 1240): match 0:Elapsed time : 0.978 ms
,D/TP/MmsSmsProvider( 1240): update uri: content://mms-sms/db_synchronization
,V/TP/MmsSmsProvider( 1240): syncDBData start
,V/TP/MmsSmsProvider( 1240): syncDBData sms end
,V/TP/MmsSmsProvider( 1240): syncDBData mms end
,V/TP/MmsSmsProvider( 1240): syncDBData end
,D/Mms/Synchronizer( 4368): [end]    dbSync()
,D/Mms/MessagingNotification( 4368): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/MmsSmsProvider( 1240): match 6:Elapsed time : 0.939 ms
,E/SMD     (  233): DCD ON
D/ContextualEventManager( 1068): removeContextualEvent(): requestClass=com.android.mms
,D/Mms/MessagesLockscreen( 4368): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/ContextualEventManager( 1068): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1068): updateContainer()
D/ContextualEventContainer( 1068): update()
D/ContextualEventContainer( 1068): handleUpdate()
D/ContextualEventManager( 1068): getTopEventView()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,D/ContextualEventManager( 1068): removeContextualEvent(): requestClass=com.android.mms
,D/Mms/MessagesLockscreen( 4368): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/ContextualEventManager( 1068): top view = flightmode
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
D/ContextualEventManager( 1068): getTopContextualEvent()
E/CscFactoryReceiver( 1240): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 1240): Media DB Scanner finished.
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,D/CscFactoryReceiver( 1240): start service to Set Ringtone
,D/CscFactoryReceiver( 1240): start service to Set Notification
,D/CscFactoryReceiver( 1240): start service to Set Alarmtone
D/CscUpdateService( 1240): onStart
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1240): only ringtone update
D/CscUpdateService( 1240): onStart
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1240): only notification update
D/CscUpdateService( 1240): onStart
,D/UsbManager( 1068):  :::: isUsb30Available :: return = false from pid = 1068
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1240): only alarmtone update
,E/CscParser( 1240): update(): xml file exist
,E/CscParser( 1240): update(): xml file exist
,E/CscParser( 1240): update(): xml file exist
,I/SELinux ( 4556): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4556):  
,D/dalvikvm( 1068): GC_EXPLICIT freed 13596K, 33% free 31318K/46200K, paused 2ms+7ms, total 41ms
,I/SELinux ( 4556): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4556):  
I/SELinux ( 4556):  
,I/SELinux ( 4556): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4556): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4556): >>>>> Normal User
,E/dalvikvm( 4556): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
D/ContextualEventManager( 1068): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1068): updateContainer()
,D/ContextualEventContainer( 1068): update()
,E/SELinux ( 4556): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/CSCSettings( 1240): Setting Ringtones (type) : 4
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
D/CscParser( 1240): AlarmTone: null
,W/CSCSettings( 1240): 1. Tag_Str: null
D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/CSCSettings( 1240): Setting Ringtones (type) : 1
D/ContextualEventContainer( 1068): handleUpdate()
D/ContextualEventManager( 1068): getTopEventView()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/CscParser( 1240): RingTone: null
W/CSCSettings( 1240): 1. Tag_Str: null
,W/CSCSettings( 1240): Setting Ringtones (type) : 2
D/CscParser( 1240): MessageTone: null
,W/CSCSettings( 1240): 1. Tag_Str: null
D/ContextualEventManager( 1068): top view = flightmode
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/UsbManager( 1068):  :::: isUsb30Available :: return = false from pid = 1068
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,D/TimaKeyStoreProvider( 4556): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4556): Cannot add TimaSignature Service, License check Failed
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
,D/ActivityThread( 4556): Added TimaKesytore provider
,D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,I/IndexBroadcastProcessorService( 4556): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,D/FactoryTestApp( 3837): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
,I/IndexBroadcastProcessorService( 4556): lucene systemReadyToIndex
,W/ActivityThread( 3837): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 3837): [XMLDataStorage$parseXML] is Live Demo : false
D/FactoryTestApp( 3837): [XMLDataStorage$parseXML] modelXML=sm-g800h.dat
D/FactoryTestApp( 3837): [XMLDataStorage$parseXML] deviceXML=kmini3g.dat
D/FactoryTestApp( 3837): [XMLDataStorage$parseXML] nameXML=kmini3gxx.dat
I/IndexService( 4556): lucene onCreate ...service
,I/FactoryTestApp( 3837): [XMLDataStorage$parseAsset] Convert dat file: sm-g800h.dat
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4556): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4556): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,I/dalvikvm( 4556): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 4556): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 4556): VFY: replacing opcode 0x71 at 0x01ed
,I/IndexService( 4556): lucene beginIndexing
,E/File    ( 4556): fail readDirectory() errno=13
,D/FactoryTestApp( 3837): [XMLDataStorage$parseAsset] Decode base file: factory.dat
,I/IndexService( 4556): lucene onDestroy start
I/IndexService( 4556): lucene onDestroy end
,I/IndexService( 4556): lucene cleanupEverything start
I/IndexService( 4556): lucene cleanupEverything end
,I/Process ( 4556): Sending signal. PID: 4556 SIG: 9
,I/ActivityManager(  749): Process com.samsung.indexservice (pid 4556) (adj 9) has died.
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
,E/installd(  245): creating libsymlink '/data/data/com.test.thalitest/lib'
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=MIC_COUNT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FONT_SIZE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_RECENT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_USER
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_POWER
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
,D/dalvikvm( 3837): GC_CONCURRENT freed 7331K, 46% free 10355K/18972K, paused 3ms+1ms, total 35ms
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
D/dalvikvm( 4581): DexOpt: load 32ms, verify+opt 85ms, 650340 bytes
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
D/PackageManager(  749): Time to dexopt: 0.27 seconds
D/PackageManager(  749): !@killApplicatoin: 10179, update pkg
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
W/PackageManager(  749): Code path for pkg : com.test.thalitest changing from /data/app/com.test.thalitest-9.apk to /data/app/com.test.thalitest-10.apk
W/PackageManager(  749): Resource path for pkg : com.test.thalitest changing from /data/app/com.test.thalitest-9.apk to /data/app/com.test.thalitest-10.apk
D/PackageManager(  749): Time to scan apk: 1.39 seconds
,D/PackageManager(  749): updateSettingsLI: 
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_ATMEL
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_ATMEL
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_ATMEL
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_ATMEL
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_ATMEL
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_ATMEL
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
,D/dalvikvm( 3837): GC_CONCURRENT freed 2030K, 46% free 10354K/18972K, paused 1ms+2ms, total 26ms
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
,D/dalvikvm(  749): GC_FOR_ALLOC freed 961K, 20% free 41744K/52052K, paused 178ms, total 178ms
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=BATTERY_TEMP_ADC
I/dalvikvm(  749): Total arena pages for JIT: 11
,I/dalvikvm(  749): Total arena pages for JIT: 12
I/dalvikvm(  749): Total arena pages for JIT: 13
,I/dalvikvm(  749): Total arena pages for JIT: 14
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
,I/dalvikvm(  749): Total arena pages for JIT: 15,
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 3837): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
,D/FactoryTestApp( 3837): [XMLDataStorage$parseAsset] SemiFunctionMenu
,D/FactoryTestApp( 3837): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 3837): [Support$Properties.get] property=ro.factory.factory_binary
,D/FactoryTestApp( 3837): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 3837): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 3837): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 3837): [ModuleCommon$ModuleCommon] Create ModuleCommon
I/FactoryTestApp( 3837): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 3837): [ModuleCommon$getMediaScanningCount] get : 0
,D/FactoryTest( 3837): User mode
,I/FactoryTestApp( 3837): [ModuleCommon$getMediaScanningCount] get : 1
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:269 android.app.ActivityThread.handleReceiver:2698 
,D/PackageManager(  749): checkUidPermission - Execution time: 283 ms
D/PackageManager(  749): New package installed in 
D/CustomFrequencyManagerService(  749): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1401600  uid : 1000  pid : 749  pkgName : SSRM_PKG_OPT@21
,D/dalvikvm(  749): GC_FOR_ALLOC freed 18585K, 55% free 23426K/52052K, paused 165ms, total 165ms
,D/PackageManager(  749): getApplicationInfo - Execution time: 280 ms
,I/PowerManagerService-JNI(  749): >>>>>>>>in native...
D/PackageManager(  749): doPostInstall for uid{10179}
D/PackageManager(  749): + starting rerstore round-trip 1
D/PackageManager(  749): No resotre for backup - queue post-install for 1
,D/GalleryCacheReady( 2409): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 2409): handleMeidaScanFinish()
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 2409): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "sms"
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 2409): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 2409): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SensorService(  749):   -0.0 -0.1 9.6
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mms"
,I/SELinux ( 4593): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4593):  
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mmsto"
,D/FaceInterface( 2409): requestFaceScan() is called.
,I/FaceInterface( 2409): startFaceScan() : waiting 5 sec
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PackageManager(  749): [MSG] MCS_UNBIND
,I/PackageManager(  749): calling disconnectService()
,D/PackageManager(  749): Trying to unbind to DefaultContainerService
,I/ActivityManager(  749): Killing 3393:com.sec.android.inputmethod/1000 (adj 15): empty #43
I/SELinux ( 4593): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4593):  
I/SELinux ( 4593):  
I/SELinux ( 4593): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4593): >>>>> Normal User
E/dalvikvm( 4593): >>>>> com.sec.android.app.music:service [ userId:0 | appId:10150 ]
,E/SELinux ( 4593): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager(  749): [MSG] SEND_PENDING_BROADCAST
D/PackageManager(  749): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10011, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@429b5f68, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,W/LocalSuggestAlbumData( 2409): query fail: 
,D/TimaKeyStoreProvider( 4593): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4593): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4593): Added TimaKesytore provider
,I/InputReader(  749): Reconfiguring input devices.  changes=0x00000010
,D/PackageManager(  749): [MSG] POST_INSTALL: observer{1118250720}
D/PackageManager(  749):           Handling post-install for 1
,W/LocalSuggestAlbumData( 2409): query fail: 
D/PackageManager(  749): Sending to user 0: act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.UID=10179, android.intent.extra.user_handle=0}]
,W/InputMethodInfo(  749): Duplicated subtype definition found: , voice
,I/InputReader(  749): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/QuickConnect[1.1][2] ( 3344): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_ADDED, package : com.test.thalitest
I/ActivityManager(  749): Waited long enough for: ServiceRecord{438e6890 u0 com.qualcomm.atfwd/.AtFwdService}
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "smsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "smsto"
,D/com.samsung.musicplus.bitmapcache.BitmapCache( 4593): Allocated bitmap cache: 13421772
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
D/RCPManagerService(  749): PackageReceiver onReceive()
D/RCPManagerService(  749): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService(  749):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: null
,D/RCPManagerService(  749):  PackageReceiver onReceive() bundle null
,I/ActivityManager(  749): Killing 3459:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BackupManagerService(  749): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaPolicyManagerService(  749): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "smsto"
V/BackupManagerService(  749): addPackageParticipantsLocked: #1
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm(  749): GC_EXPLICIT freed 2227K, 54% free 24166K/52052K, paused 8ms+17ms, total 410ms
D/PackageManager(  749): return install result to caller: 1118250720
D/PackageManager(  749): returnCode: 1
I/PackageManager(  749): Observer no longer exists.
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/CscFactoryReceiver( 1240): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 1240): Media DB Scanner finished.
,D/CscFactoryReceiver( 1240): start service to Set Ringtone
,D/CscFactoryReceiver( 1240): start service to Set Notification
,D/CscFactoryReceiver( 1240): start service to Set Alarmtone
,D/CscUpdateService( 1240): onStart
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1240): only ringtone update
D/CscUpdateService( 1240): onStart
E/CscParser( 1240): update(): xml file exist
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1240): only notification update
,D/CscUpdateService( 1240): onStart
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1240): only alarmtone update
,E/CscParser( 1240): update(): xml file exist
,I/SELinux ( 4612): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4612):  
,D/dalvikvm( 1240): GC_CONCURRENT freed 1668K, 44% free 10704K/18972K, paused 37ms+3ms, total 58ms
I/SELinux ( 4612): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4612):  
I/SELinux ( 4612):  
,I/SELinux ( 4612): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1240): WAIT_FOR_CONCURRENT_GC blocked 23ms
E/dalvikvm( 4612): >>>>> Normal User
E/dalvikvm( 4612): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
,D/dalvikvm( 1240): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 1240): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SELinux ( 4612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/CscParser( 1240): update(): xml file exist
,D/TimaKeyStoreProvider( 4612): in addTimaSignatureService
,W/CSCSettings( 1240): Setting Ringtones (type) : 1
,D/CscParser( 1240): RingTone: null
W/CSCSettings( 1240): 1. Tag_Str: null
,W/CSCSettings( 1240): Setting Ringtones (type) : 2
D/CscParser( 1240): MessageTone: null
,W/CSCSettings( 1240): 1. Tag_Str: null
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/CSCSettings( 1240): Setting Ringtones (type) : 4
D/CscParser( 1240): AlarmTone: null
,W/CSCSettings( 1240): 1. Tag_Str: null
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4612): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4612): Added TimaKesytore provider
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FactoryTestApp( 3837): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
,I/FactoryTestApp( 3837): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
,D/FactoryTestApp( 3837): [FactoryTestBroadcastReceiver$onReceive] ACTION_MEDIA_SCANNER_FINISHED => XML data parsing was failed.
D/FactoryTestApp( 3837): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 3837): [Support$Properties.get] property=ro.factory.factory_binary
I/FactoryTestApp( 3837): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 3837): [ModuleCommon$getMediaScanningCount] get : 1
,I/IndexBroadcastProcessorService( 4612): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
D/FactoryTest( 3837): User mode
I/FactoryTestApp( 3837): [ModuleCommon$getMediaScanningCount] get : 2
,I/FactoryTestApp( 3837): [ModuleCommon$getMediaScanningCount] get : 2
,D/FactoryTestApp( 3837): [Support$Values.getBoolean] id=FACTORY_TEST_APO, value=true
I/IndexBroadcastProcessorService( 4612): lucene systemReadyToIndex
D/FactoryTestApp( 3837): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3837): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 3837): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
I/FactoryTestApp( 3837): [FactoryTestBroadcastReceiver$USER MODE] BOOT_COMPLETE
,I/FactoryTestApp( 3837): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted] start DummyFtClient service for APO
,I/IndexService( 4612): lucene onCreate ...service
,W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:577 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:278 
D/FactoryTestApp( 3837): [Support$Values.getBoolean] id=SUPPORT_BOOST_MEDIASCAN, value=false
D/FactoryTest( 3837): User mode
I/FactoryTestApp( 3837): [ModuleCommon$15 Test Ready flag] set
,I/FactoryTestApp( 3837): [ModuleCommon$isFirstBoot] before : false
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4612): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,D/GalleryCacheReady( 2409): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4612): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/FactoryTestApp( 3837): [DummyFtClient$onCreate] Create DummyFtClient service
I/FactoryTestApp( 3837): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 3837): [DummyFtClient$onReceive] ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
D/GalleryCacheReady( 2409): handleMeidaScanFinish()
,D/FactoryTestApp( 3837): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 3837): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,W/Vold    (  220): Returning OperationFailed - no handler for errno 30
D/FactoryTestApp( 3837): [Support$Values.getBoolean] id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 3837): [DummyFtClient$onStartCommand] ...
,D/FactoryTestApp( 3837): [DummyFtClient$sendBootCompletedAndFinish] ...
D/FactoryTestApp( 3837): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 3837): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
,D/FactoryTestApp( 3837): [IPCWriterToSecPhoneService$ResponseWriter] Create IPCWriterToSecPhoneService
,I/FactoryTestApp( 3837): [IPCWriterToSecPhoneService$connectToSecPhoneService]  
,D/FaceInterface( 2409): requestFaceScan() is called.
,D/GalaxyFinderApplication( 2567): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 2567): SLink location service is enable. content://media/external/images/media not register
D/GalaxyFinderApplication( 2567): [Slink platform] The state of Slink geocode service is true
,W/LocalSuggestAlbumData( 2409): query fail: 
D/LocationTagReadyService( 2567): SLink location service is enable. content://media/external/video/media not register
D/GalaxyFinderApplication( 2567): [Slink platform] The state of Slink geocode service is true
W/LocalSuggestAlbumData( 2409): query fail: 
,I/FaceInterface( 2409): startFaceScan() : waiting 5 sec
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:141 
,I/dalvikvm( 4612): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 4612): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 4612): VFY: replacing opcode 0x71 at 0x01ed
,I/SELinux ( 4633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4633):  
,I/LocationTagReadyService( 2567): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2567): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2567): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2567): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 4633): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4633):  
I/SELinux ( 4633):  
,I/SELinux ( 4633): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4633): >>>>> Normal User
E/dalvikvm( 4633): >>>>> com.sec.phone [ userId:0 | appId:1001 ]
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 4633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/GallerySearchProvider( 2409): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 4645): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4645):  
,D/TimaKeyStoreProvider( 4633): in addTimaSignatureService
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4633): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4633): Added TimaKesytore provider
,I/SettingSearch/SearchIntentReceiver( 1321): action : android.settings.CHANGED_ICC_LOCK_ENABLE
,I/SELinux ( 4645): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4645):  
I/SELinux ( 4645):  
,I/SELinux ( 4645): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4645): >>>>> Normal User
,E/dalvikvm( 4645): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 4645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4645): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4645): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4645): Added TimaKesytore provider
I/IndexService( 4612): lucene beginIndexing
I/SELinux ( 4664): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4664):  
,I/SELinux ( 4664): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4664):  
I/SELinux ( 4664):  
,I/SELinux ( 4664): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4664): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4664): >>>>> Normal User
,E/dalvikvm( 4664): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 4664): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ApplicationsProvider( 1410): Could not fetch usage stats
W/ApplicationsProvider( 1410): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1410): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1410): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1410): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1410): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/File    ( 4612): fail readDirectory() errno=13
,D/TimaKeyStoreProvider( 4664): in addTimaSignatureService
,I/FactoryTestApp( 3837): [IPCWriterToSecPhoneService$onServiceConnected] connected done
,I/IndexService( 4612): lucene onDestroy start
,D/TimaKeyStoreProvider( 4664): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4664): Added TimaKesytore provider
,D/FactoryTestApp( 3837): [IPCWriterToSecPhoneService$write] Send Response Message to SecPhone
,D/FactoryTestApp( 3837): [IPCWriterToSecPhoneService$write] Response ��
,I/SELinux ( 4683): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4683):  
,I/IndexService( 4612): lucene onDestroy end
,I/IndexService( 4612): lucene cleanupEverything start
,I/IndexService( 4612): ERROR: null
,E/ParserThreadsListManager( 4612): Lucene Interrupt in run
,I/IndexService( 4612): lucene cleanupEverything end
,I/Process ( 4612): Sending signal. PID: 4612 SIG: 9
,D/AT_Distributor(  277): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 3837): [IPCWriterToSecPhoneService$handleMessage] Send BOOT COMPLETED done
D/AT_Distributor(  277): SetAtdStatus(), 1_1_0
,D/AT_Distributor(  277): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,I/SettingSearchManagerReceiver( 1240): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,I/SettingSearchManagerReceiver( 1240): addSearchInfoDB
,I/SELinux ( 4687): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4687):  
,W/ApplicationsProvider( 1410): Could not fetch usage stats
W/ApplicationsProvider( 1410): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1410): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1410): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1410): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1410): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 4683): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4683):  
I/SELinux ( 4683):  
,I/SELinux ( 4683): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4683): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 4683): >>>>> Normal User
,E/dalvikvm( 4683): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 4683): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4683): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4683): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4683): Added TimaKesytore provider
,I/SELinux ( 4687): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4687):  
I/SELinux ( 4687):  
,I/SELinux ( 4687): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4687): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4687): >>>>> Normal User
,E/dalvikvm( 4687): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 4687): [DEBUG] seapp_context_lookup: seinfoCategory = release
,V/KVNProvider( 4664): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 4664): getFindoCursor query string : 
,D/TimaKeyStoreProvider( 4687): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4687): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4687): Added TimaKesytore provider
,V/KVNProvider( 4664): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager(  749): Process com.samsung.indexservice (pid 4612) (adj 11) has died.
,E/SMD     (  233): DCD ON
,I/ActivityManager(  749): Waited long enough for: ServiceRecord{442ea950 u0 com.google.android.gms/.gcm.GcmService}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4687, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/MediaStoreImporter( 3924): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PowerManagerService-JNI(  749): CheckForString returning : -1
D/CustomFrequencyManagerService(  749): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1401600  uid : 1000  pid : 749  tag : SSRM_PKG_OPT@21
,I/SettingSearchManagerReceiver( 1240): endInsert
,I/ActivityManager(  749): Killing 3493:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SELinux ( 4708): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4708):  
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/GCoreNlp( 1218): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SELinux ( 4708): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4708):  
I/SELinux ( 4708):  
,I/SELinux ( 4708): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4708): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4708): >>>>> Normal User
,E/dalvikvm( 4708): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 4708): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4708): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4708): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4708): Added TimaKesytore provider
,W/InputMethodInfo(  749): Duplicated subtype definition found: , voice
,D/AssistantMenuSettingSearch( 4708): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,D/AssistantMenuSettingSearch( 4708): Make Setting DB
,D/EnterpriseDeviceManagerService(  749): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  749): Admin package name: com.google.android.gms
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  749): onPackageAdded : com.test.thalitest
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4683, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,W/ContextImpl( 4708): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:123 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:35 
,I/ActivityManager(  749): Killing 3550:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 4725): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4725):  
,I/SELinux ( 4725): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4725):  
I/SELinux ( 4725):  
,I/SELinux ( 4725): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4725): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4725): >>>>> Normal User
,E/dalvikvm( 4725): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 4725): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4725): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4725): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4725): Added TimaKesytore provider
I/ActivityManager(  749): Killing 3624:com.google.android.youtube/u0a175 (adj 15): empty #43
,D/LocationProviderProxy(  749): applying state to connected service
,D/LocationProviderProxy(  749): applying state to connected service
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4725, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
,I/Babel   ( 4725): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4725): MmsConfig.loadMmsSettings
,I/Babel   ( 4725): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/Babel   ( 4725): MmsConfig.loadFromDatabase
,E/Babel   ( 4725): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4725): MmsConfig.loadFromResources
,E/Babel   ( 4725): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4725): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,W/Settings( 4725): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/dalvikvm( 4725): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4725): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4725): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4725): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4725): VFY: unable to resolve instance field 36
,D/dalvikvm( 4725): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4725): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4725): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4725): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4725): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4725): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4725): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42769c88
,D/dalvikvm( 4725): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42769c88
,D/dalvikvm( 4725): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42769c88, skipping init
,D/dalvikvm( 4725): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42769c88
,D/dalvikvm( 4725): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42769c88
,V/JNIHelp ( 4725): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PowerManagerService(  749): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  749): Nap time...
,D/PowerManagerService(  749): [s] WAKEFULNESS_NAPPING
I/PowerManagerService(  749): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService(  749): Going to sleep due to screen timeout...
D/PowerManagerService(  749): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController(  749): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/knox    ( 3281): InnerIntentReceiver.onReceive() : com.sec.knox.seandroid.alarm.LOG_UPLOAD_ALARM_INTENT
D/Sensors (  749): LightSensor enable = 0
,D/Sensors (  749): LightSensor enableSensor = 0
,D/SensorManager(  749): unregisterListener ::   
,I/Sensors (  749): HAL:resetDataRates mEnabled=4
I/DisplayPowerController(  749): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/DisplayPowerController(  749): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,W/ContextImpl( 3281): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.InnerIntentReceiver.onReceive:171 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3281): KNOXAgentService. startJobThread() start
D/knox    ( 3281): KNOXAgentService. JobThread()
D/knox    ( 3281): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3281): KNOXAgentService. startJobThread() wait
D/knox    ( 3281): KNOXAgentService : onCreate()
D/knox    ( 3281): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3281): startFileChecker
I/knox    ( 3281): start checking file is exist to uploading
D/SensorManager(  749): unregisterListener ::   
D/knox    ( 3281): KNOXAgentService : onDestroy().
D/knox    ( 3281): ModuleBase.cancelAllAlarmManageModule()
D/knox    ( 3281): notiShow :0 / context pref : 2
I/knox    ( 3281): denial log zip completed
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837934
,D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/SurfaceFlinger(  239): id=16 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/GCM     ( 1289): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/DisplayPowerController(  749): !@ElectronBeam entry
,W/GCoreFlp( 1218): No location to return for getLastLocation()
,W/FusedLocationProvider( 1218): location=null
,D/dalvikvm( 4725): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42769c88
,D/dalvikvm( 4725): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42769c88
,D/dalvikvm( 4725): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42769c88
,D/dalvikvm( 4725): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42769c88
,D/lights  (  749): lcd : 0 +
,D/lights  (  749): lcd : 0 -
,D/MISC PowerHAL(  749): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL(  749): sysfs_write +: /sys/class/input/input1/enabled: 0
,D/MISC PowerHAL(  749): sysfs_write -: /sys/class/input/input1/enabled: 0
,D/MISC PowerHAL(  749): miscpower_set_interactive: /sys/class/input/input6/enabled
D/MISC PowerHAL(  749): sysfs_write +: /sys/class/input/input6/enabled: 0
,D/MISC PowerHAL(  749): sysfs_write -: /sys/class/input/input6/enabled: 0
D/MISC PowerHAL(  749): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  749): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  749): Got set_interactive hint
,V/WindowOrientationListener(  749): WindowOrientationListener disabled
D/SensorService(  749): AutoRotationSensor::activate (ident=0x780b9840, enabled=0)
,I/Sensors (  749): HAL: batch Dry Run is complete
D/SurfaceFlinger(  239): Screen released, type=0 flinger=0xb877d980
,D/qdhwcomposer(  239): hwc_blank: Blanking display: 0
D/PowerManagerService(  749): blankAllDisplays() is called.
D/PowerManagerService(  749): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService(  749): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  749): [PWL] sb release: PowerManagerService.Display
,D/PowerManagerService(  749): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
I/Sensors (  749): HAL:resetDataRates mEnabled=4
D/KeyguardViewMediator( 1068): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1068): notifyScreenOffLocked
E/KeyguardViewMediator( 1068): resetStateLocked
D/KeyguardViewMediator( 1068): handleNotifyScreenOff
D/KeyguardViewManager( 1068): onScreenTurnedOff()
D/KeyguardHostView( 1068): screen off, instance 425ddde0 at 69576
D/LockPatternUtils( 1068): isPcwEnable = null
,D/SensorManager(  749): unregisterListener ::   
,D/InputDispatcher(  749): setInputDispatchMode: enabled=0, frozen=0
V/KeyguardHostView( 1068): showPrimarySecurityScreen(turningOff=true)
I/MDPP    ( 1068): Property: Empty
,D/KeyguardHostView( 1068): showSecurityScreen(None)
,D/SecCameraShortcut( 1068): onScreenTurnedOff
,D/SensorManager( 1068): unregisterListener ::   
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1068): KeyguardEffectViewParticleSpace : screenTurnedOff
,D/VisualEffectParticleEffect( 1068): clearEffect
,D/PersonaManager( 1068): isKioskContainerExistOnDevice
D/KeyguardViewMediator( 1068): Kiosk container not exists on device or sim lock exists.
D/KeyguardViewMediator( 1068): handleReset
D/KeyguardViewManager( 1068): reset()
,D/KeyguardHostView( 1068): onSaveInstanceState, tstate=1
,D/KeyguardGuestSelectorView( 1068): onDetachedFromWindow()
,I/ActivityManager(  749): Killing 3823:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.CarrierText$1@428b60e0
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.MSimCarrierText$1@428b64b8
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.CarrierText$1@428a2d40
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.EmergencyButton$1@428b2ee8
,I/ProviderInstaller( 4725): Installed default security provider GmsCore_OpenSSL
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/qdhwcomposer(  239): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  749): Excessive delay in blankDisplay() while turning screen off: 275ms
I/libsuspend(  749): !@[s] autosuspend_autosleep_enable
,I/libsuspend(  749): !@[s] autosuspend_autosleep_enable done
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/PowerManagerService(  749): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 276ms
D/PowerManagerService(  749): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService(  749): [PWL] Off : 0s ago
I/PowerManagerService(  749): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  749): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  749): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=749, ws=WorkSource{1000}) (elapsedTime=26293)
I/PowerManagerService(  749): [PWL]       PARTIAL_WAKE_LOCK              'GmsDownloadService' (uid=10011, pid=1642, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=492)
I/PowerManagerService(  749): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=749, ws=null) (elapsedTime=258)
I/PowerManagerService(  749): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=1289, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=232)
I/PowerManagerService(  749): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/WindowManager(  749): Screenshot max retries 4 of Token{424bfbf8 ActivityRecord{42595908 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42e837f8 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,W/WindowManager(  749): Screenshot failure taking screenshot for (720x1280) to layer 21005
V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42688f88
,D/LightsService(  749): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 749) 
,I/SensorManagerA(  749): getReportingMode :: sensor.mType = 5
D/Sensors (  749): LightSensor setDelay = 200000000
,D/Sensors (  749): LightSensor setSensorDelay = 200000000
D/Sensors (  749): Light sensor flush: not enabled 0
D/Sensors (  749): LightSensor enable = 1
D/Sensors (  749): LightSensor enableSensor = 1
,D/LightsService(  749): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager(  749): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Launcher.HomeView( 1251): onStop
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget pause on instance = 1
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
,D/accuweather( 1449): [KK AccuPhone]>>> WR:149 [0:0] onPause
,D/accuweather( 1449): [KK AccuPhone]>>> SM:526 [0:0] onPause
D/BatteryService(  749): turn on LED for fully charged
D/VibratorService(  749): JNI vibratorOff()
I/ActivityManager(  749): Killing 3036:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
D/SSRMv2:SIOP(  749): SIOP:: AP = 340, Delta = 10
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for com.android.keyguard.KeyguardHostView$2@425df230
W/InputMethodManagerService(  749): Ignoring setImeWindowStatus of uid 1000 token: null
,E/KeyguardHostView( 1068): KeyguardHostView()
,D/ContextualEventManager( 1068): setOnClickHandler()
,V/KeyguardHostView( 1068): mIsMultipleLockOn is false
D/KeyguardHostView( 1068): mIsVoiceUnlockOn=false
,V/KeyguardHostView( 1068): Initial transport state: 1, pbstate=0
,I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
,D/LockPatternUtils( 1068): isPcwEnable = null
D/STATUSBAR-NotificationService(  749): ACTION_SCREEN_OFF
D/LightsService(  749): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 749) 
D/LightsService(  749): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/audio_hw_primary(  242): adev_set_parameters: enter: screen_state=off
V/voice   (  242): voice_set_parameters: enter: screen_state=off
V/voice   (  242): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  242): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  242): platform_set_parameters: exit with code(-2)
,V/audio_hw_primary(  242): adev_set_parameters: exit
I/SecExternalDisplayIntents_Java(  749): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/ContextualEventContainer( 1068): ContextualEventContainer()
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.KeyguardMessageArea$2@42862ed0
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
D/ContextualEventContainer( 1068): onFinishInflate()
,D/ContextualEventContainer( 1068): update()
,D/IpRemoteDisplayController(  749): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  749): Bridge Server is not available
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/PersonaManagerService(  749): ACTION_SCREEN_OFF onReceive
,D/LockPatternUtils( 1068): isPcwEnable = null
D/LockPatternUtils( 1068): isPcwEnable = null
,D/PersonaManagerServiceHandler(  749): MSG_ACTION_SCREEN_OFF called
,D/KeyguardHostView( 1068): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
,D/LockPatternUtils( 1068): isPcwEnable = null
,V/KeyguardHostView( 1068): showPrimarySecurityScreen(turningOff=false)
,I/MDPP    ( 1068): Property: Empty
D/KeyguardHostView( 1068): showSecurityScreen(None)
,V/KeyguardHostView( 1068): inflating id = 2130903095
,D/SecuritySelectorView( 1068): explore by touch mode off
,I/SELinux ( 4768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4768):  
,D/dalvikvm(  240): GC_EXPLICIT freed 45K, 50% free 9506K/18972K, paused 3ms+3ms, total 32ms
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+3ms, total 19ms
I/SELinux ( 4768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4768):  
I/SELinux ( 4768):  
,I/SELinux ( 4768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4768): >>>>> Normal User
,E/dalvikvm( 4768): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/LightsService(  749): [SvcLED]  onSensorChanged::light value = 67
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+2ms, total 20ms
,D/Sensors (  749): LightSensor enable = 0
,D/Sensors (  749): LightSensor enableSensor = 0
,D/TimaKeyStoreProvider( 4768): in addTimaSignatureService
,D/SensorManager(  749): unregisterListener ::   
,D/lights  (  749): led_pattern : 5 +
,D/lights  (  749): led_pattern : 5 -
,D/LightsService(  749): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/TimaKeyStoreProvider( 4768): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4768): Added TimaKesytore provider
,D/dalvikvm(  749): GC_EXPLICIT freed 2974K, 55% free 23692K/52052K, paused 8ms+17ms, total 186ms
,I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
,I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
,D/SecCameraShortcut( 1068): shortcutSetting:1
,D/SecCameraShortcut( 1068): isKidsMode:false
,D/SecCameraShortcut( 1068): isEmergencyMode:false
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/EmergencyButton( 1068): enabled = false, :0
,D/LockPatternUtils( 1068): isPcwEnable = null
,I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
,D/SecCameraShortcut( 1068): setCallback(): null
,D/KeyguardVoiceEngineThread( 1068): condition = 0
,D/SecuritySelectorView( 1068): mIsAirViewEnabled =false
D/SecCameraShortcut( 1068): setCallback(): not null
,D/SecuritySelectorView( 1068): hideBouncer mBouncerHelpText != null
,D/SecCameraShortcut( 1068): setCallback(): not null
D/SecCameraShortcut( 1068): setCallback(): not null
,D/SecuritySelectorView( 1068): hideBouncer mBouncerHelpText != null
,D/KeyguardHostView( 1068): mKeyguardHelpOverlay : null
D/KeyguardHostView( 1068): AUTO_WIPE = false , IT Policy = false
D/ContextualEventManager( 1068): setOnClickHandler()
,E/LSO     ( 1068): LSO Service is not yet ready!!!
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.KeyguardHostView$2@423311c0
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
,V/KeyguardHostView( 1068): music state changed: 0
,D/KeyguardProperties( 1068): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1068): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1068): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1068): screenHeight : 1280
D/VisualEffectCircleUnlockEffect( 1068): ratio : 0.6666667
,D/VisualEffectCircleUnlockEffect( 1068): Constructor
D/VisualEffectCircleUnlockEffect( 1068): arrowImageId = 2130837796
D/VisualEffectCircleUnlockEffect( 1068): circleUnlockMaxWidth = 576
D/VisualEffectCircleUnlockEffect( 1068): circleUnlockMinWidth = 172
D/VisualEffectCircleUnlockEffect( 1068): outerStrokeWidth = 2
D/VisualEffectCircleUnlockEffect( 1068): innerStrokeWidth = 4
,D/VisualEffectCircleUnlockEffect( 1068): lockSequenceTotal = 30
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@4289e9f8
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.MSimCarrierText$1@42579608
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
D/MSimCarrierText( 1068):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 0
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1068): updateCarrierText: text = 
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1068): updateCarrierText: text = 
,D/MSimCarrierText( 1068):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 1
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1068): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1068): updateCarrierText: text = 
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1068): getCarrierTextForSimState: status = SimNotReady
D/MSimCarrierText( 1068): updateCarrierText: text = null
V/KeyguardUpdateMonitor( 1068): *** register callback for com.android.keyguard.EmergencyButton$1@425ffb08
,V/KeyguardUpdateMonitor( 1068): *** unregister callback for null
,E/MTPRx   ( 4768): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 4768): check value of boot_completed is1
,E/MTPRx   ( 4768): check booting is completed_sys.boot_completed
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/EmergencyButton( 1068): enabled = false, :0
,E/MTPRx   ( 4768): Sd-Card path/storage/extSdCard
D/SecCameraShortcut( 1068): setCallback(): not null
D/SecuritySelectorView( 1068): hideBouncer mBouncerHelpText != null
E/MTPRx   ( 4768): Status for mount/Unmount :removed
,E/MTPRx   ( 4768): SDcard is not available
W/MTPRx   ( 4768): value of connected istrue
D/KeyguardViewManager( 1068): mWindowLayoutParams not null
W/MTPRx   ( 4768): value of configured istrue
W/MTPRx   ( 4768): value of mtpEnabled istrue
,W/MTPRx   ( 4768): value of ptpEnabled isfalse
D/KeyguardHostView( 1068): onRestoreInstanceState, transport=1
,E/MTPRx   ( 4768): Received USB_STATE with sdCardLaunch = 0
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1068): KeyguardEffectViewParticleSpace : reset
E/MTPRx   ( 4768): mFirstTime: false
,I/Choreographer( 1068): Skipped 38 frames!  The application may be doing too much work on its main thread.
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/ContextualEventContainer( 1068): handleUpdate()
D/ContextualEventManager( 1068): getTopEventView()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,D/ContextualEventManager( 1068): top view = flightmode
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
D/ContextualEventManager( 1068): getTopContextualEvent()
,D/        ( 4768): MTP: reading debug level property
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
D/ContextualEventManager( 1068): getTopContextualEvent()
E/MTPRx   ( 4768):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 4768): Getting CryptionKey from JAVA
,E/MTPRx   ( 4768): currentUserId is 0
,E/MTPRx   ( 4768): Start observing USB_STATE_MATCH 
,D/UsbManager( 1068):  :::: isUsb30Available :: return = false from pid = 1068
E/MTPRx   ( 4768): usbMode is 0200
E/MTPRx   ( 4768): is_secretmode is NOT 1
W/MTPRx   ( 4768): Phone is lockedtrue
,D/LockPatternUtils( 1068): isPcwEnable = null
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardViewMediator( 1068): handleKeyguardDoneDrawing
,D/MTPRx   ( 4768):  inside checkKnoxStatus
,D/MTPRx   ( 4768):  inside checkKnoxStatus_isKnoxModeActive : false
D/STATUSBAR-PhoneStatusBar( 1068): makeExpandedInvisible
D/PhoneStatusBarView( 1068): marqueeStatusBar:121, mClearCover:0
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
,E/MTPRx   ( 4768): sending MTP_ICON_ENABLED to stack
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/MTPRx   ( 4768): else part ... so first time!!!
E/MTPPlaObsrvr( 4768): inside setContext()
,E/MTPPlaObsrvr( 4768):  inside createplafiles
,E/MTPPlaObsrvr( 4768): playlist count is0
,E/MTPPlaObsrvr( 4768):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4768):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4768): Inside registerContentObserver
,E/MtpAdbObserver( 4768): inside setContext()
E/MtpAdbObserver( 4768): Inside registerContentObserver
,W/Settings( 4768): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 4768): onCreate.
,E/MtpService( 4768): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4768): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4768): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/MTPRx   ( 4768): calling native method
,E/MTPJNIInterface( 4768): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 4768): < MTP > Registering BroadCast receiver :::::::
,D/SecKeyguardFlightModeView( 1068): received broadcast android.intent.action.SCREEN_OFF
E/MTPJNIInterface( 4768): noti = 10
E/MtpService( 4768): onStartCommand.
,E/MtpService( 4768): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MtpService( 4768): onStartCommand.
W/MTPRx   ( 4768): calling native method
E/MTPRx   ( 4768): Checking the driver time out
E/MTPJNIInterface( 4768): noti = 2
D/        ( 4768): deleting sockets before message queue initialization
,D/        ( 4768): event handler thread is created, so set the flag
E/MTPRx   ( 4768): called native method
E/MTPJNIInterface( 4768): setting Media scanner status0
E/MTPJNIInterface( 4768): After setting Media scanner status0
W/MTPRx   ( 4768): notification from stack 1
,E/MTPJNIInterface( 4768): Getting media scanner status0
E/MtpService( 4768): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4768): DeviceName is Galaxy S5-2
,D/MediaScannerReceiver( 1206): action: android.intent.action.MTP_FILE_SCAN
D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1449): [KK AccuPhone]>>> SWW:440 [0:0] stopRefreshIcon : 1
D/accuweather( 1449): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
V/NetworkStats(  749): performPollLocked(flags=0x3)
,D/QuickConnect[1.1][2] ( 3344): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 3344): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 3344): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 3344): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4264b538
V/QuickConnect[1.1][2] ( 3344): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4264b538
D/QuickConnect[1.1][2] ( 3344): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 3344): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 3344): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 3344): stopLeScan()
,D/QuickConnect[1.1][2] ( 3344): BleHelper.stopScan - call stopLeScan() complete
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
V/NetworkStats(  749): performPollLocked() took 30ms
,D/PowerManagerService(  749): [PWL] sb release: PowerManagerService.Broadcasts
D/NtpTrustedTime(  749): currentTimeMillis() cache hit
D/NtpTrustedTime(  749): currentTimeMillis() cache hit
,D/Headlines( 4144): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4144): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4144): Breath 10751 latestRequest time : 1454056101397 current time : 1454056112148
,D/Mms/MessagesLockscreen( 4368): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1068): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1068): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1068): updateContainer()
D/ContextualEventContainer( 1068): update()
D/ContextualEventContainer( 1068): handleUpdate()
D/ContextualEventManager( 1068): getTopEventView()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,W/ContextImpl( 3924): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ContextualEventManager( 1068): top view = flightmode
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
D/ContextualEventManager( 1068): getTopContextualEvent()
,I/DBG_DIAGMONDM( 3977): [1.140541.0531][Line:24][onReceive] com.sec.intent.action.SYSSCOPESTATUS
D/UsbManager( 1068):  :::: isUsb30Available :: return = false from pid = 1068
,W/ContextImpl( 3924): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/SSRMv2:SIOP(  749): SIOP:: AP = 340, Delta = 0
,I/SELinux ( 4790): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4790):  
D/MediaScannerService( 1206): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
,D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SELinux ( 4790): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4790):  
I/SELinux ( 4790):  
,I/SELinux ( 4790): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4790): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4790): >>>>> Normal User
,E/dalvikvm( 4790): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 4790): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4790): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4790): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4790): Added TimaKesytore provider
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,I/iu.UploadsManager( 1642): End new media; added: 0, uploading: 0, time: 100 ms
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter finished
I/MusicLeanback( 3924): Conditions not met for autocaching.
,I/MusicLeanback( 3924): Stop autocaching.
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1206): savePlaylistTableInBulkDeleter finished
,D/PreloadUpdateManagerStateMachine( 4232): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 4232): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4232): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4232): AutoUpdateTriggerManager:IDLE:setInterval:86400000
D/hcjo    ( 4232): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4232): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4232): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4232): entry::IDLE
,D/MediaScanner( 1206): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/DBG_DM  ( 4790): [][Line:95][onCreate] 
E/DBG_DM  ( 4790): BootingfileStream is null
,E/DBG_DM  ( 4790): xdmCreateBootingFilestream
,V/MediaScanner( 1206): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1206): Skipping:
,D/MediaScanner( 1206): 7klwibgf7fvntblfd7(75ebcf7
,I/DBG_DM  ( 4790): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 4790): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 4790): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 4790): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,D/MediaScanner( 1206): Skipping:
,D/MediaScanner( 1206): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1206): processDirectory :  /storage/extSdCard
W/MediaScanner( 1206): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1206): 7klwibgf7fxlKdCbid7
,E/File    ( 1206): fail readDirectory() errno=2
,V/MediaScanner( 1206): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426f6848
,V/MediaScanner( 1206): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426f6848
V/MediaScanner( 1206):  prescan time: 27ms (DB items: 20)
V/MediaScanner( 1206):     scan time: 26ms (Caching mode: true), (makeEntry time: 14ms ~53%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1206): postscan time: 6ms (bulkDeleter : 0), (delete DeadThumbnail time : 4ms)
V/MediaScanner( 1206):    total time: 59ms
,V/MediaScanner( 1206): checked files: 3  directories : 17  (I: 0, U: 0)
,E/MTPJNIInterface( 4768): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 1206): !@done scanning volume external
,I/DBG_DM  ( 4790): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 4790): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 4790): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 4790): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 4790): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 4790): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 4790): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 4790): [3.19.140541][Line:139][onReceive] com.sec.intent.action.SYSSCOPESTATUS
I/ActivityManager(  749): Killing 3903:com.sec.pcw.device/1000 (adj 15): empty #43
,I/IcingCorporaProvider( 2174): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/SELinux ( 4817): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4817):  
,I/SELinux ( 4817): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4817):  
I/SELinux ( 4817):  
,I/SELinux ( 4817): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4817): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4817): >>>>> Normal User
,E/dalvikvm( 4817): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 4817): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/FactoryTestApp( 3837): [IPCWriterToSecPhoneService$disConnectSecPhoneService]  
,D/TimaKeyStoreProvider( 4817): in addTimaSignatureService
I/ActivityManager(  749): Killing 3952:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,D/TimaKeyStoreProvider( 4817): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4817): Added TimaKesytore provider
,I/Icing   ( 1642): Storage manager: low false usage 1.68MB avail 11.18GB capacity 11.95GB
,D/FileShare-Server( 4817): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/SELinux ( 4832): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4832):  
I/ActivityManager(  749): Killing 3877:com.vlingo.midas/u0a33 (adj 15): empty #43
,I/dalvikvm( 1642): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
,W/dalvikvm( 1642): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1642): VFY: replacing opcode 0x6e at 0x0029
,I/SELinux ( 4832): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4832):  
I/SELinux ( 4832):  
,I/SELinux ( 4832): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4832): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4832): >>>>> Normal User
,E/dalvikvm( 4832): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 4832): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1206): GC_EXPLICIT freed 496K, 48% free 10042K/18972K, paused 2ms+5ms, total 32ms
,D/TimaKeyStoreProvider( 4832): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4832): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4832): Added TimaKesytore provider
,E/MTPJNIInterface( 4768): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4768): SDcard is not available
,E/SMD     (  233): DCD ON
,E/MTPJNIInterface( 4768): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4768): SDcard is not available
E/SQLiteLog( 4768): (21) API call with NULL database connection pointer
E/SQLiteLog( 4768): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 4768): (21) API call with NULL database connection pointer
E/SQLiteLog( 4768): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 4768): (21) API call with NULL database connection pointer
E/SQLiteLog( 4768): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 4768): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4768): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 4768): notification from stack 2
D/        ( 4768): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4768): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 4768): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
D/        ( 4768): *****Starting mtp_io()
,W/MTPRx   ( 4768): notification from stack 3
D/        ( 4768): [mtp_start_io] source_thread Creation 
,D/        ( 4768): [mtp_start_io] sink_thread Creation 
,D/        ( 4768): [mtp_start_io:360] sink thread created so set th_sink
,D/BezelQuickConnect( 3356): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 3356): BezelBroadcastReceiver - packageName : com.google.android.gms
,I/dalvikvm( 3700): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 3700): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3700): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager(  749): Killing 4045:com.policydm/1000 (adj 15): empty #43
,D/PackageBroadcastService( 1642): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/SELinux ( 4852): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4852):  
,I/PackageBroadcastService( 1642): Null package name or gms related package.  Ignoreing.
,I/SELinux ( 4852): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4852):  
I/SELinux ( 4852):  
,I/SELinux ( 4852): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4852): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4852): >>>>> Normal User
,E/dalvikvm( 4852): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
,E/SELinux ( 4852): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4852): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4852): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4852): Added TimaKesytore provider
,I/dalvikvm( 1642): Total arena pages for JIT: 11
,I/dalvikvm( 1642): Total arena pages for JIT: 12
I/dalvikvm( 1642): Total arena pages for JIT: 13
,I/dalvikvm( 1642): Total arena pages for JIT: 14
,I/Icing   ( 1642): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm(  749): GC_EXPLICIT freed 877K, 55% free 23531K/52052K, paused 7ms+13ms, total 129ms
,D/AmoledAdjustTimer(  749): prevTemp = 285, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 1642): GC_CONCURRENT freed 1804K, 38% free 11809K/18972K, paused 4ms+4ms, total 41ms
,E/SamsungIME( 4852): InputManagerImpl.getInstance() == null
,I/SELinux ( 4870): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4870):  
I/ActivityManager(  749): Killing 4107:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #43
,I/SELinux ( 4870): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4870):  
I/SELinux ( 4870):  
,I/SELinux ( 4870): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4870): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4870): >>>>> Normal User
,E/dalvikvm( 4870): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 4870): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4870): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4870): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4870): Added TimaKesytore provider
,I/FaceInterface( 2409): startFaceScan() : going on
,D/FaceInterface( 2409): startFaceScan() is called.
,D/ContentApp( 1206): startScan() is called.
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4870, uid=10014 requires android.permission.INTERACT_ACROSS_USERS
,D/FaceValue( 1206): mSleepTime: 800
,D/FaceValue( 1206): mMaxThreadNum: 2
,W/FaceValue( 1206): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1206): startScan() is end.
D/ContentApp( 1206): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1206): isNeedToRestore : start
,I/SELinux ( 4886): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4886):  
,I/ActivityManager(  749): Killing 4130:com.android.chrome/u0a81 (adj 15): empty #43
,I/Icing   ( 1642): Internal init done: storage state 0
I/SELinux ( 4886): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4886):  
I/SELinux ( 4886):  
,I/SELinux ( 4886): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4886): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4886): >>>>> Normal User
,E/dalvikvm( 4886): >>>>> com.samsung.groupcast [ userId:0 | appId:10015 ]
,E/SELinux ( 4886): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,I/Icing   ( 1642): Post-init done
,D/TimaKeyStoreProvider( 4886): in addTimaSignatureService
D/TimaKeyStoreProvider( 4886): Cannot add TimaSignature Service, License check Failed
,I/Icing   ( 1642): updateResources: need to parse f{com.google.android.gms}
,D/ActivityThread( 4886): Added TimaKesytore provider
,D/GroupCast_FileTools( 4886): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 4886): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.mv.player
W/System.err( 4886): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 4886): 	at com.samsung.groupcast.application.App.preLoadShareVideoCheck(App.java:325)
W/System.err( 4886): 	at com.samsung.groupcast.application.App.onCreate(App.java:145)
W/System.err( 4886): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4886): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
,W/System.err( 4886): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4886): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4886): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4886): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 4886): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4886): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4886): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 4886): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 4886): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 4886): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 4886): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 4886): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 4886): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
,W/System.err( 4886): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4886): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 4886): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4886): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4886): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4886): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4886): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4886): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4886): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 4886): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 4886): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 4898): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4898):  
I/ActivityManager(  749): Killing 4156:com.google.android.apps.magazines/u0a112 (adj 15): empty #43
,I/SELinux ( 4898): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4898):  
I/SELinux ( 4898):  
,I/SELinux ( 4898): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4898): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4898): >>>>> Normal User
,E/dalvikvm( 4898): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,E/SELinux ( 4898): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4898): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4898): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4898): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4898, uid=10024 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4913): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4913):  
,I/ActivityManager(  749): Killing 4160:com.samsung.android.magazine.service/u0a106 (adj 15): empty #43
,I/SELinux ( 4913): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4913):  
I/SELinux ( 4913):  
,I/SELinux ( 4913): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4913): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4913): >>>>> Normal User
,E/dalvikvm( 4913): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 4913): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/dalvikvm( 4913): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 4913): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4913): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4913): Added TimaKesytore provider
,I/PCWCLIENTTRACE_PushUtil( 4913): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4913): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4913): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 4913): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 4913): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4913): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/SELinux ( 4925): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4925):  
I/ActivityManager(  749): Killing 3471:com.android.email/u0a155 (adj 15): empty #43
,I/SELinux ( 4925): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4925):  
I/SELinux ( 4925):  
,I/SELinux ( 4925): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4925): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4925): >>>>> Normal User
,E/dalvikvm( 4925): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10034 ]
,E/SELinux ( 4925): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4925): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4925): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4925): Added TimaKesytore provider
,I/IcingCorporaProvider( 2174): UpdateCorporaTask done [took 1446 ms] updated apps [took 1446 ms] 
,W/System.err( 4925): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 4925): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 4925): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 4925): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 4925): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 4925): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
,W/System.err( 4925): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 4925): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 4925): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 4925): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
,W/System.err( 4925): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 4925): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4925): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 4925): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4925): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,W/System.err( 4925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4925): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4925): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4925): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 4925): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4925): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 4925): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 4925): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 4925): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4925): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 4925): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 4925): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 4925): 	... 21 more
,D/GalaxyFinderApplication( 4925): [Slink platform] Version = 29011
,D/GalaxyFinderApplication( 4925): [Slink platform] use state of slink location service is [false] to [true]
,I/SELinux ( 4942): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4942):  
I/ActivityManager(  749): Killing 3607:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/FaceInterface( 2409): startFaceScan() : going on
,D/FaceInterface( 2409): startFaceScan() is called.
,D/ContentApp( 1206): startScan() is called.
,D/ContentApp( 1206): startScan() is end.
D/ContentApp( 1206): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1206): isNeedToRestore : start
,I/SELinux ( 4942): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4942):  
I/SELinux ( 4942):  
,I/SELinux ( 4942): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4942): >>>>> Normal User
,E/dalvikvm( 4942): >>>>> com.policydm [ userId:0 | appId:1000 ]
,E/SELinux ( 4942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/FactoryTestApp( 3837): [DummyFtClient$onDestroy] Destroy DummyFtClient service
D/FactoryTestApp( 3837): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3837): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 3837): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
D/FactoryTestApp( 3837): [DummyFtClient$onDestroy] kill process
,I/Process ( 3837): Sending signal. PID: 3837 SIG: 9
,D/TimaKeyStoreProvider( 4942): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4942): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4942): Added TimaKesytore provider
I/ActivityManager(  749): Process com.sec.factory (pid 3837) (adj 0) has died.
,I/SELinux ( 4964): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4964):  
,I/ActivityManager(  749): Killing 3996:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,D/dalvikvm(  240): GC_EXPLICIT freed 47K, 50% free 9506K/18972K, paused 2ms+3ms, total 26ms
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+3ms, total 19ms
,I/SELinux ( 4964): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4964):  
I/SELinux ( 4964):  
,I/SELinux ( 4964): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4964): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4964): >>>>> Normal User
,E/dalvikvm( 4964): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
,E/SELinux ( 4964): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 4964): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4964): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4964): Added TimaKesytore provider
,I/Icing   ( 1642): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4964, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
,D/Icing   ( 1642): Loaded CLD2 Version V2.0 - 20141016
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4964): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,I/Icing   ( 1642): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
W/ActivityManager(  749): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4964): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,I/SA      ( 4081): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4081): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4081): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
,D/Mms/PackageInstallReceiver( 4368): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2174): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ContextImpl( 4708): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/CheckinService( 1642): Done disabling old GoogleServicesFramework version
,I/SELinux ( 4990): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4990):  
,I/SELinux ( 4990): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4990):  
I/SELinux ( 4990):  
,I/SELinux ( 4990): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4990): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4990): >>>>> Normal User
,E/dalvikvm( 4990): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4990): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm( 2174): GC_CONCURRENT freed 1743K, 39% free 11591K/18972K, paused 2ms+3ms, total 46ms
,D/dalvikvm( 2174): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/ActivityManager(  749): Killing 4013:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,D/TimaKeyStoreProvider( 4990): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4990): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4990): Added TimaKesytore provider
,I/IcingCorporaProvider( 2174): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4990, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 4990): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,I/SELinux ( 5003): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5003):  
I/ActivityManager(  749): Killing 4298:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 5003): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5003):  
I/SELinux ( 5003):  
,I/SELinux ( 5003): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5003): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5003): >>>>> Normal User
,E/dalvikvm( 5003): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 5003): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5003): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5003): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5003): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5003, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5023): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5023):  
,I/ActivityManager(  749): Killing 4028:com.sec.android.soagent/u0a37 (adj 15): empty #43
,W/GAV2    ( 5003): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 5023): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5023):  
I/SELinux ( 5023):  
,I/SELinux ( 5023): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5023): >>>>> Normal User
,E/dalvikvm( 5023): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 5023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5023): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5023): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5023): Added TimaKesytore provider
,D/PackageIntentReceiver( 5023): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5023): Not GearManger package! 
,I/SELinux ( 5045): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5045):  
,I/SELinux ( 5045): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5045):  
I/SELinux ( 5045):  
,I/SELinux ( 5045): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5045): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5045): >>>>> Normal User
,E/dalvikvm( 5045): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 5045): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5045): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5045): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5045): Added TimaKesytore provider
,D/MagazineService Version( 5045): Magazine-Channel: 13
,D/MagazineService Version( 5045): Magazine-Provider: 13
,D/MagazineService Version( 5045): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 5045): [onCreate]
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5045, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/MagazineService::MagazineBroadcastReceiver( 5045): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
E/SMD     (  233): DCD ON
,I/MagazineService::MagazineService( 5045): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 5059): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5059):  
,D/MagazineService::MagazineService( 5045): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/GAV4    ( 4725): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager(  749): Killing 4402:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,I/SELinux ( 5059): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5059):  
I/SELinux ( 5059):  
,I/SELinux ( 5059): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5059): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5059): >>>>> Normal User
,E/dalvikvm( 5059): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5059): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5059): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5059): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5059): Added TimaKesytore provider
,W/GAV2    ( 5003): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  749): Killing 4417:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/ActivityManager(  749): Waited long enough for: ServiceRecord{44b2a658 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/SELinux ( 5078): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5078):  
I/ActivityManager(  749): Killing 4429:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5078): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5078):  
I/SELinux ( 5078):  
,I/SELinux ( 5078): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5078): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5078): >>>>> Normal User
,E/dalvikvm( 5078): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5078): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5078): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5078): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5078): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5078, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5078): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5090): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5090):  
I/ActivityManager(  749): Killing 3592:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 5090): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5090):  
I/SELinux ( 5090):  
,I/SELinux ( 5090): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5090): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5090): >>>>> Normal User
,E/dalvikvm( 5090): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5090): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5090): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5090): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5090): Added TimaKesytore provider
,I/ActivityManager(  749): Killing 4458:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/PackageBroadcastService( 1642): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1642): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1642): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1642): VFY: replacing opcode 0x6e at 0x0053
,D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1642): Loading module APK com.google.android.play.games
,D/Finsky  ( 3700): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/dalvikvm( 1642): GC_CONCURRENT freed 1956K, 38% free 11807K/18972K, paused 5ms+20ms, total 68ms
,W/SQLiteConnectionPool( 1642): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/dalvikvm( 1642): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1642): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1642): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1642): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1642): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1642): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1642): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1642): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,I/PowerManagerService(  749): [PWL] Off : 5s ago
,D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1642): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1642): Submit a task: k
W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1642): Processing package: com.test.thalitest
,D/GassUtils( 1642): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1642): Found info for package com.test.thalitest in db.
,I/SettingSearch/SearchIntentReceiver( 1321): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1321): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1321): InitTitleDBThread start --> mDoingInitTitleDB : true
I/SettingSearch/SearchIntentReceiver( 1321): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1321): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/BaseAppContext( 1642): Using Auth Proxy for data requests.
,W/BaseAppContext( 1642): Using Auth Proxy for data requests.
,I/SettingSearch/SettingsSearchManager( 1321): Infomation -> numtitleinfo : 0 numSearchinfo : 312
,W/BaseAppContext( 1642): Using Auth Proxy for data requests.
W/dalvikvm( 1642): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1642): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1642): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1642): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1642): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1642): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1642): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1642): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1642): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1642): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1642): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1642): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1642): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1642): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1642): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1642): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1642): VFY: replacing opcode 0x6e at 0x0006
,I/SettingSearch/SettingsSearchManager( 1321):  Infomation -> getItem size : 312
,D/dalvikvm(  749): GC_EXPLICIT freed 1753K, 55% free 23706K/52052K, paused 7ms+14ms, total 142ms
,W/BaseAppContext( 1642): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1642): cleanUpNonGplusAccounts done.
,E/CscFactoryReceiver( 1240): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 1240): Media DB Scanner finished.
D/CscFactoryReceiver( 1240): start service to Set Ringtone
W/BaseAppContext( 1642): Using Auth Proxy for data requests.
,W/BaseAppContext( 1642): Using Auth Proxy for data requests.
,D/CscFactoryReceiver( 1240): start service to Set Notification
,D/CscFactoryReceiver( 1240): start service to Set Alarmtone
,D/CscUpdateService( 1240): onStart
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1240): only ringtone update
,D/CscUpdateService( 1240): onStart
,E/CscParser( 1240): update(): xml file exist
,E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1240): only notification update
,D/CscUpdateService( 1240): onStart
E/CscUpdateService( 1240): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1240): only alarmtone update
,E/CscParser( 1240): update(): xml file exist
,I/SELinux ( 5126): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5126):  
,W/CSCSettings( 1240): Setting Ringtones (type) : 1
D/CscParser( 1240): RingTone: null
,W/CSCSettings( 1240): 1. Tag_Str: null
,W/CSCSettings( 1240): Setting Ringtones (type) : 2
,D/CscParser( 1240): MessageTone: null
,W/CSCSettings( 1240): 1. Tag_Str: null
,E/CscParser( 1240): update(): xml file exist
,W/BaseAppContext( 1642): Using Auth Proxy for data requests.
,W/CSCSettings( 1240): Setting Ringtones (type) : 4
,D/CscParser( 1240): AlarmTone: null
,W/CSCSettings( 1240): 1. Tag_Str: null
I/SELinux ( 5126): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5126):  
I/SELinux ( 5126):  
,I/SELinux ( 5126): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5126): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5126): >>>>> Normal User
,E/dalvikvm( 5126): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
,E/SELinux ( 5126): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5126): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5126): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5126): Added TimaKesytore provider
,I/IndexBroadcastProcessorService( 5126): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,I/SELinux ( 5140): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5140):  
,I/IndexBroadcastProcessorService( 5126): lucene systemReadyToIndex
,I/IndexService( 5126): lucene onCreate ...service
,I/SELinux ( 5140): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5140):  
I/SELinux ( 5140):  
,I/SELinux ( 5140): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5140): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5140): >>>>> Normal User
,E/dalvikvm( 5140): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 5140): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5140): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5140): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5140): Added TimaKesytore provider
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5126): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 5126): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/dalvikvm( 5126): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 5126): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 5126): VFY: replacing opcode 0x71 at 0x01ed
,I/IndexService( 5126): lucene beginIndexing
,D/FactoryTestApp( 5140): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
,W/ActivityThread( 5140): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 5140): [XMLDataStorage$parseXML] is Live Demo : false
D/FactoryTestApp( 5140): [XMLDataStorage$parseXML] modelXML=sm-g800h.dat
,D/FactoryTestApp( 5140): [XMLDataStorage$parseXML] deviceXML=kmini3g.dat
E/File    ( 5126): fail readDirectory() errno=13
,D/FactoryTestApp( 5140): [XMLDataStorage$parseXML] nameXML=kmini3gxx.dat
,I/IndexService( 5126): lucene onDestroy start
,I/IndexService( 5126): lucene onDestroy end
,I/IndexService( 5126): lucene cleanupEverything start
,I/IndexService( 5126): ERROR: null
E/ParserThreadsListManager( 5126): Lucene Interrupt in run
I/IndexService( 5126): lucene cleanupEverything end
,I/Process ( 5126): Sending signal. PID: 5126 SIG: 9
,I/FactoryTestApp( 5140): [XMLDataStorage$parseAsset] Convert dat file: sm-g800h.dat
,I/ActivityManager(  749): Process com.samsung.indexservice (pid 5126) (adj 9) has died.
,D/FactoryTestApp( 5140): [XMLDataStorage$parseAsset] Decode base file: factory.dat
,W/dalvikvm( 1642): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1642): Module APK com.google.android.play.games already loaded
,I/Icing   ( 1642): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=MIC_COUNT
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
D/dalvikvm( 1642): GC_CONCURRENT freed 1205K, 34% free 12641K/18972K, paused 3ms+5ms, total 43ms
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
,I/Icing   ( 1642): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FONT_SIZE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_RECENT
,D/dalvikvm( 4687): GC_EXPLICIT freed 3866K, 47% free 10125K/18972K, paused 2ms+5ms, total 35ms
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
,D/dalvikvm( 1321): GC_EXPLICIT freed 460K, 46% free 10290K/18972K, paused 2ms+4ms, total 36ms
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_USER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_POWER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
,D/dalvikvm( 5140): GC_CONCURRENT freed 7289K, 46% free 10357K/18972K, paused 3ms+3ms, total 36ms
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_ATMEL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_ATMEL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_ATMEL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_ATMEL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_ATMEL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_ATMEL
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
,D/dalvikvm( 5140): GC_CONCURRENT freed 1950K, 46% free 10353K/18972K, paused 2ms+9ms, total 36ms
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=BATTERY_TEMP_ADC
,D/dalvikvm( 4687): GC_EXPLICIT freed 998K, 48% free 10017K/18972K, paused 2ms+5ms, total 26ms
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 5140): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
,E/SMD     (  233): DCD ON
,D/FactoryTestApp( 5140): [XMLDataStorage$parseAsset] SemiFunctionMenu
,D/FactoryTestApp( 5140): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 5140): [Support$Properties.get] property=ro.factory.factory_binary
,D/FactoryTestApp( 5140): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 5140): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 5140): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 5140): [ModuleCommon$ModuleCommon] Create ModuleCommon
I/FactoryTestApp( 5140): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 5140): [ModuleCommon$getMediaScanningCount] get : 2
,D/FactoryTest( 5140): User mode
I/FactoryTestApp( 5140): [ModuleCommon$getMediaScanningCount] get : 3
I/FactoryTestApp( 5140): [ModuleCommon$getMediaScanningCount] get : 3
I/FactoryTestApp( 5140): [ModuleCommon$getMediaScanningCount] get : 3
,I/FactoryTestApp( 5140): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
D/FactoryTestApp( 5140): [FactoryTestBroadcastReceiver$killProcessSelf] kill process
,I/Process ( 5140): Sending signal. PID: 5140 SIG: 9
,I/ActivityManager(  749): Process com.sec.factory (pid 5140) (adj 0) has died.
,D/GalleryCacheReady( 2409): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 2409): handleMeidaScanFinish()
,D/FaceInterface( 2409): requestFaceScan() is called.
,I/FaceInterface( 2409): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 2409): query fail: 
,W/LocalSuggestAlbumData( 2409): query fail: 
,D/dalvikvm( 1321): GC_EXPLICIT freed 368K, 46% free 10281K/18972K, paused 3ms+4ms, total 39ms
,I/MediaStoreImporter( 3924): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/dalvikvm(  749): GC_EXPLICIT freed 730K, 55% free 23541K/52052K, paused 7ms+12ms, total 124ms
,V/AlarmManager(  749): waitForAlarm result :8
,D/dalvikvm( 4687): GC_EXPLICIT freed 897K, 48% free 10014K/18972K, paused 2ms+5ms, total 25ms
,I/HarmonyEASService(  749): Updating for all 1
,D/dalvikvm( 1321): GC_EXPLICIT freed 358K, 46% free 10283K/18972K, paused 3ms+4ms, total 27ms
,I/GAV2    ( 5003): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 4687): GC_EXPLICIT freed 904K, 48% free 10022K/18972K, paused 2ms+5ms, total 25ms
,D/dalvikvm( 4687): null clazz in OP_INSTANCE_OF, single-stepping
,D/dalvikvm( 1321): GC_EXPLICIT freed 358K, 46% free 10292K/18972K, paused 3ms+4ms, total 25ms
,E/Watchdog(  749): !@Sync 2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 4687): GC_EXPLICIT freed 902K, 48% free 10018K/18972K, paused 2ms+5ms, total 24ms
,D/dalvikvm( 1321): GC_EXPLICIT freed 359K, 46% free 10294K/18972K, paused 3ms+4ms, total 27ms
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
D/BatteryService(  749): stay LED for fully charged
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  749): mCoverManager.getCoverState() : true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/SSRMv2:SIOP(  749): SIOP:: AP = 330, Delta = -10
,I/iu.UploadsManager( 1642): End new media; added: 0, uploading: 0, time: 132 ms
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  749): GC_EXPLICIT freed 460K, 55% free 23554K/52052K, paused 7ms+12ms, total 156ms
,D/dalvikvm( 4687): GC_EXPLICIT freed 881K, 48% free 10013K/18972K, paused 2ms+7ms, total 28ms
,D/dalvikvm( 1321): GC_EXPLICIT freed 348K, 46% free 10300K/18972K, paused 4ms+6ms, total 33ms
,D/AmoledAdjustTimer(  749): prevTemp = 289, currTemp = 291, prevStep = 4, currStep = 4
,I/ActivityManager(  749): Waited long enough for: ServiceRecord{43036780 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/dalvikvm( 4687): GC_EXPLICIT freed 875K, 48% free 10015K/18972K, paused 3ms+8ms, total 39ms
,I/FaceInterface( 2409): startFaceScan() : going on
,D/FaceInterface( 2409): startFaceScan() is called.
,D/ContentApp( 1206): startScan() is called.
,D/ContentApp( 1206): startScan() is end.
D/ContentApp( 1206): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1206): isNeedToRestore : start
,D/dalvikvm( 1321): GC_EXPLICIT freed 346K, 46% free 10309K/18972K, paused 4ms+7ms, total 40ms
,V/AlarmManager(  749): waitForAlarm result :4
,D/Finsky  ( 3700): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 3700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3700): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3700): VFY: replacing opcode 0x62 at 0x0038
V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1289): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 1289): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1289): VFY: replacing opcode 0x6e at 0x0046
,I/System.out( 3700): Thread-348(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3700): Thread-348(ApacheHTTPLog):isShipBuild true
,I/System.out( 3700): Thread-348(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  233): DCD ON
,D/dalvikvm( 4687): GC_EXPLICIT freed 872K, 48% free 10012K/18972K, paused 3ms+8ms, total 39ms
,D/dalvikvm( 1321): GC_EXPLICIT freed 336K, 46% free 10317K/18972K, paused 4ms+7ms, total 45ms
,D/dalvikvm(  749): GC_EXPLICIT freed 398K, 55% free 23546K/52052K, paused 9ms+19ms, total 231ms
,W/IcingInternalCorpora( 1642): getNumBytesRead when not calculated.
,I/PowerManagerService(  749): [PWL] Off : 15s ago
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 4687): GC_EXPLICIT freed 870K, 48% free 10013K/18972K, paused 3ms+9ms, total 38ms
,I/System.out( 3700): Thread-348 calls detatch()
,I/ActivityManager(  749): Waited long enough for: ServiceRecord{44a89cd0 u0 com.samsung.android.MtpApplication/.MtpService}
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1321): GC_EXPLICIT freed 347K, 46% free 10324K/18972K, paused 4ms+7ms, total 40ms
,I/qtaguid ( 3700): Failed write_ctrl(u 73) res=-1 errno=22
I/qtaguid ( 3700): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3700): untagSocket(73) failed with errno -22
,I/System.out( 3700): Thread-349 calls detatch()
,D/Finsky  ( 3700): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 3700): Total arena pages for JIT: 11
,I/dalvikvm( 3700): Total arena pages for JIT: 12
,I/dalvikvm( 3700): Total arena pages for JIT: 13
,I/dalvikvm( 3700): Total arena pages for JIT: 14
,E/SMD     (  233): DCD ON
,I/qtaguid ( 3700): Failed write_ctrl(u 73) res=-1 errno=22
,I/qtaguid ( 3700): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3700): untagSocket(73) failed with errno -22
,I/System.out( 3700): Thread-348 calls detatch()
,D/dalvikvm( 3700): GC_CONCURRENT freed 5805K, 38% free 11881K/18972K, paused 4ms+5ms, total 55ms
,D/dalvikvm( 3700): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4687): GC_EXPLICIT freed 876K, 48% free 10012K/18972K, paused 3ms+8ms, total 39ms
,D/dalvikvm( 3700): GC_FOR_ALLOC freed 1027K, 34% free 12628K/18972K, paused 35ms, total 36ms
,D/dalvikvm( 3700): GC_FOR_ALLOC freed 1634K, 33% free 12850K/18972K, paused 34ms, total 36ms
,D/dalvikvm( 1321): GC_EXPLICIT freed 363K, 46% free 10337K/18972K, paused 4ms+7ms, total 40ms
,D/dalvikvm( 3700): GC_CONCURRENT freed 1575K, 23% free 14629K/18972K, paused 4ms+5ms, total 56ms
,D/dalvikvm( 3700): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 4687): GC_CONCURRENT freed 1486K, 45% free 10550K/18972K, paused 2ms+33ms, total 67ms
,I/SettingSearch/SearchIntentReceiver( 1321): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1321): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 1321): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1321): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1321): LOCALE_CHANGED call search setting db finish!!
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  233): DCD ON
,I/qtaguid ( 3700): Failed write_ctrl(u 73) res=-1 errno=22
,I/qtaguid ( 3700): Untagging socket 73 failed errno=-22
,W/NetworkManagementSocketTagger( 3700): untagSocket(73) failed with errno -22
,I/System.out( 3700): Thread-349 calls detatch()
,D/Finsky  ( 3700): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.maps to true
,D/Finsky  ( 3700): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for flipboard.app to false
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3700): [1] LibraryUtils.isAvailable: com.sec.android.fwupgrade available because owned, overriding [restriction=7].
,D/Finsky  ( 3700): [1] LibraryUtils.isAvailable: com.noknok.android.framework.service available because owned, overriding [restriction=7].
,D/Finsky  ( 3700): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 1218): callingUid 10011, callindPid: 1218
,D/DeviceConnectionService( 1218): client connected with version: 8296000
,D/Finsky  ( 3700): [372] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3700): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3700): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/dalvikvm( 1289): GC_EXPLICIT freed 904K, 44% free 10796K/18972K, paused 3ms+5ms, total 45ms
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1289): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP(  749): SIOP:: AP = 310, Delta = -20
,I/System.out( 3700): Thread-359(HTTPLog):isShipBuild true
,I/System.out( 3700): Thread-359(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/AmoledAdjustTimer(  749): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  749): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  749): <AppSync3 Whitelist>
,V/AlarmManager(  749): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  749): [PWL] Off : 30s ago
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4144): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4144): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4144): Breath 40807 latestRequest time : 1454056101397 current time : 1454056142204
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = -10
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SMD     (  233): DCD ON
,D/Finsky  ( 3700): [361] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3700): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 3
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 290, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 50s ago
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4144): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4144): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4144): Breath 70013 latestRequest time : 1454056101397 current time : 1454056171410
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/FactoryTest( 4768): Not factory mode
,D/FactoryTest( 4768): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4768): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4768): still no open session command from host, so toast
W/ContextImpl( 4768): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4768): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  749): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  749): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  749): mDVFSHelper.acquire()
,D/LockPatternUtils( 1068): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2091): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2091): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1068): isPcwEnable = null
,E/MTPRx   ( 4768): started activity for popup
,I/VacuumService( 1218): Vacuum at: now=1454056172209 tag=VacuumService
,E/SettingsReceiverActivity( 4768): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/SettingsReceiverActivity( 4768): dev.kiessupport is : TRUE
,D/dalvikvm(  749): GC_EXPLICIT freed 1937K, 55% free 23710K/52052K, paused 8ms+14ms, total 206ms
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/WindowManager(  749): Screenshot max retries 4 of Token{424bfbf8 ActivityRecord{42595908 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42e837f8 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,W/WindowManager(  749): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1068): isPcwEnable = null
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 288, currTemp = 285, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  749): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  749): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  749): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  pkgName : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  233): DCD ON
,D/CustomFrequencyManagerService(  749): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  tag : ACTIVITY_RESUME_BOOSTER@9
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 75s ago
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,D/Headlines( 4144): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4144): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4144): Breath 90043 latestRequest time : 1454056101397 current time : 1454056191440
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 5
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 105s ago
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,D/Headlines( 4144): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4144): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4144): Breath 120039 latestRequest time : 1454056101397 current time : 1454056221436
,D/Headlines( 4144): stop 
,D/Headlines( 4144): Breath.onDestroy : 
,I/ActivityManager(  749): Killing 4474:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 6
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 140s ago
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 7
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  749): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 180s ago
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 8
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,E/SMD     (  233): DCD ON
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 9
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 225s ago
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  749): initializing...
,I/TLC_TIMA_PKM_initialize(  749): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  749): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  749): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  749): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  749): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  749): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  749): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  749): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  749): App is not loaded in QSEE
,D/QSEECOMAPI: (  749): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  749): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  749): Trustlet response is completed
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  749): !@Sync 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,E/SMD     (  233): DCD ON
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5373): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5373):  
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,I/SELinux ( 5373): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5373):  
I/SELinux ( 5373):  
,I/SELinux ( 5373): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5373): >>>>> Normal User
,E/dalvikvm( 5373): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5373): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5373): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5373): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5373, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  749): Killing 4499:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43,
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 275s ago
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 11
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 12
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 330s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 13
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 14
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 390s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 15
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 16
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 455s ago
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 17
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm(  749): GC_CONCURRENT freed 3411K, 55% free 23773K/52052K, paused 22ms+42ms, total 474ms
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 18
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 19
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  749): [PWL] Off : 525s ago
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  749): !@Sync 20
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 21
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 600s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 22
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  749): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  749): <AppSync3 Whitelist>
,V/AlarmManager(  749): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 23
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,E/SMD     (  233): DCD ON
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 24
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 680s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 25
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 26
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 27
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  749): [PWL] Off : 765s ago
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 28
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 29
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  233): DCD ON
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 30
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/PowerManagerService(  749): [PWL] Off : 855s ago
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 31
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :4
,I/SensorManagerA(  749): getReportingMode :: sensor.mType = 5
,D/Sensors (  749): LightSensor setDelay = 200000000
,D/Sensors (  749): LightSensor setSensorDelay = 200000000
,D/LightsService(  749): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  749): Light sensor flush: not enabled 0
D/Sensors (  749): LightSensor enable = 1
D/Sensors (  749): LightSensor enableSensor = 1
D/SensorManager(  749): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Sensors (  749): LightSensor enable = 0
,D/Sensors (  749): LightSensor enableSensor = 0
,D/SensorManager(  749): unregisterListener ::   
D/LightsService(  749): [SvcLED]  onSensorChanged::light value = 57
D/LightsService(  749): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/ConnectivityService(  749): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/PhenotypeConfigurator( 1218): Scheduling Phenotype for one-off execution 4339 seconds from now (1454056996873)
,D/GetConfigurationSnapshotOperation( 1218): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1218): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1218): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1218): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1218): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1218): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  749): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1218): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1218): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1218): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1218): Thread-106(HTTPLog):isShipBuild true
,I/System.out( 1218): Thread-106(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1218): GC_CONCURRENT freed 1514K, 37% free 11957K/18972K, paused 6ms+9ms, total 63ms
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/dalvikvm(  749): GC_CONCURRENT freed 3480K, 55% free 23798K/52052K, paused 23ms+44ms, total 482ms
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 32
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 33
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 950s ago
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,E/SMD     (  233): DCD ON
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 34
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 35
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 36
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 1050s ago
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 37
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 38
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 39
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 40
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 1155s ago
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  749): !@Sync 41
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1927): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1927): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5607): 
D/AndroidRuntime( 5607): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5607): CheckJNI is OFF
D/AndroidRuntime( 5607): setted country_code = Poland
D/AndroidRuntime( 5607): setted countryiso_code = PL
D/AndroidRuntime( 5607): setted sales_code = XEO
D/AndroidRuntime( 5607): readGMSProperty: start
D/AndroidRuntime( 5607): readGMSProperty: already setted!!
D/AndroidRuntime( 5607): readGMSProperty: end
D/AndroidRuntime( 5607): addProductProperty: start
D/dalvikvm( 5607): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5607): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5607): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5607): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5607): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5607): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5607): failed to load memtrack module: -2
D/dalvikvm( 5607): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5607): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  749): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  749): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  749): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  749): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  749): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  749): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  749): START PACKAGE DELETE: observer{1120162040}
D/PackageManager(  749): pkg{<packageName>}
D/PackageManager(  749): user{0}
D/PackageManager(  749): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  749): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  749): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  749): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  749): getApplicationUninstallationEnabled
D/ApplicationPolicy(  749): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  749): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  749): !@killApplicatoin: 10179, uninstall pkg
D/PackageManager(  749): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1642): GC_EXPLICIT freed 840K, 36% free 12233K/18972K, paused 3ms+5ms, total 47ms
D/dalvikvm( 2174): GC_EXPLICIT freed 534K, 41% free 11244K/18972K, paused 3ms+4ms, total 39ms
I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3344): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/dalvikvm( 1410): GC_EXPLICIT freed 4305K, 48% free 10027K/18972K, paused 2ms+7ms, total 57ms
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
D/RCPManagerService(  749): PackageReceiver onReceive()
I/HarmonyEASService(  749): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/InputReader(  749): Reconfiguring input devices.  changes=0x00000010
D/PackageManager(  749): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5632): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5632):  
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  240): GC_EXPLICIT freed 43K, 50% free 9506K/18972K, paused 3ms+3ms, total 31ms
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5632): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5632):  
I/SELinux ( 5632):  
I/SELinux ( 5632): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5632): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5632): >>>>> Normal User
E/dalvikvm( 5632): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5632): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 5ms+7ms, total 27ms
D/TimaKeyStoreProvider( 5632): in addTimaSignatureService
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5632): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5632): Added TimaKesytore provider
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 50% free 9506K/18972K, paused 2ms+3ms, total 20ms
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  749): GC_CONCURRENT freed 3484K, 55% free 23912K/52052K, paused 9ms+10ms, total 121ms
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 74ms
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 59ms
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 114ms
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  749): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  749): removePackageParticipantsLocked: uid=10179 #1
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5632, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm(  749): GC_EXPLICIT freed 859K, 55% free 23670K/52052K, paused 6ms+18ms, total 174ms
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 239ms
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 248ms
D/elm:14132( 5632): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5632): ELMEngine.ELMEngine( context ).
D/elm:14132( 5632): MDMBridge.setEnterpriseBridge()
D/PackageManager(  749): delete sourFile : 
D/elm:14132( 5632): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5632): ElmAgentService : onCreate()
D/elm:14132( 5632): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/AndroidRuntime( 5607): Shutting down VM
D/elm:14132( 5632): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5632): MDMBridge.getInstance()
D/elm:14132( 5632): MDMBridge.getAllLicenseInfoFromSDK()
D/PackageManager(  749): delete native library directory: 
D/PackageManager(  749): return delete result to caller: 1120162040
D/PackageManager(  749): returnCode: 1
D/elm:14132( 5632): MDMBridge.getAllLicenseInfoFromSDK()
D/dalvikvm( 5607): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
I/SELinux ( 5647): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5647):  
D/elm:14132( 5632): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5632): ElmAgentService : onDestroy().
I/ActivityManager(  749): Killing 4515:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
I/SELinux ( 5647): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5647):  
I/SELinux ( 5647):  
I/SELinux ( 5647): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5647): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5647): >>>>> Normal User
E/dalvikvm( 5647): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
E/SELinux ( 5647): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/InputMethodInfo(  749): Duplicated subtype definition found: , voice
D/TimaKeyStoreProvider( 5647): in addTimaSignatureService
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5647): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5647): Added TimaKesytore provider
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  749): Package has changed for user 0
D/EnterpriseDeviceManagerService(  749): Admin package name: com.google.android.gms
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5647, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 5647): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4263cc78, skipping init
I/SecureStorage( 5647): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 5647): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  290): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5647
I/SecureStorage(  290): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 5647): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 5647): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  290): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5647
I/SecureStorage(  290): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  749): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  749): clearDefaults: com.test.thalitest
D/InputReader(  749): Processing first event
E/SMD     (  233): DCD ON
W/ApplicationsProvider( 1410): Could not fetch usage stats
W/ApplicationsProvider( 1410): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1410): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1410): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1410): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1410): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
