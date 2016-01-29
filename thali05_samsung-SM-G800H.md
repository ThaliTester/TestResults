#### Test 57531243c766d4e_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SA      ( 4047): [SLFUCHKMGR] constructor called
I/SA      ( 4047): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4047): [OR] == isSIMCardReady false ==
I/SA      ( 4047): [SCU] == networkStateCheck == true
I/SA      ( 4047): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4047): isChinaCountryCode : false
I/SA      ( 4047): [OR] == networkStateCheck true ==
--------- beginning of /dev/log/system
D/PowerManagerService(  739): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1064 (0x0)
I/SA      ( 4047): [OR] GetMyCountryZoneTask
I/SA      ( 4047): [OR] onReceive END
I/SA      ( 4047): [SRS] prepareGetMyCountryZone
I/SA      ( 4047): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4047): [SSP] query invoked
I/ActivityManager(  739): Killing 2970:com.wssnps/1000 (adj 15): empty #43
I/SA      ( 4047): [TPMU] GetMccFromDB : null
I/SA      ( 4047): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4047): [TPM] isNoProxy(default) : true
I/SA      ( 4047): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
I/SELinux ( 4073): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4073):  
,I/SELinux ( 4073): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4073):  
I/SELinux ( 4073):  
I/SELinux ( 4073): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4073): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4073): >>>>> Normal User
E/dalvikvm( 4073): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
E/SELinux ( 4073): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4073): in addTimaSignatureService
D/TimaKeyStoreProvider( 4073): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4073): Added TimaKesytore provider
I/System.out( 4047): Thread-389(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 4047): Thread-389(ApacheHTTPLog):isShipBuild true
I/System.out( 4047): Thread-389(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/sCloudBackupApp( 4073): sCloudBackupApp Version Info : 3.7.3.KK_APP
I/SCloudBackupReceiver( 4073): Other Intent
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
I/ActivityManager(  739): Killing 2982:com.samsung.android.app.accesscontrol/u0a64 (adj 15): empty #43
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/accuweather( 1444): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1444): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/accuweather( 1444): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/accuweather( 1444): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/SELinux ( 4089): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4089):  
I/SELinux ( 4089): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4089):  
I/SELinux ( 4089):  
I/SELinux ( 4089): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4089): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 4089): >>>>> Normal User
E/dalvikvm( 4089): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
E/SELinux ( 4089): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/TimaKeyStoreProvider( 4089): in addTimaSignatureService
D/TimaKeyStoreProvider( 4089): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4089): Added TimaKesytore provider
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4089, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  739): Killing 3012:com.sec.android.nearby.mediaserver/u0a70 (adj 15): empty #43
I/SELinux ( 4102): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4102):  
D/AndroidRuntime( 4085): 
D/AndroidRuntime( 4085): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4085): CheckJNI is OFF
D/AndroidRuntime( 4085): setted country_code = Poland
D/AndroidRuntime( 4085): setted countryiso_code = PL
D/AndroidRuntime( 4085): setted sales_code = XEO
D/AndroidRuntime( 4085): readGMSProperty: start
D/AndroidRuntime( 4085): readGMSProperty: already setted!!
D/AndroidRuntime( 4085): readGMSProperty: end
D/AndroidRuntime( 4085): addProductProperty: start
I/SELinux ( 4102): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4102):  
I/SELinux ( 4102):  
I/SELinux ( 4102): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4102): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4102): >>>>> Normal User
E/dalvikvm( 4102): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
D/dalvikvm( 4085): Trying to load lib libjavacore.so 0x0
E/SELinux ( 4102): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 4085): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4085): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4085): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4085): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/TimaKeyStoreProvider( 4102): in addTimaSignatureService
D/TimaKeyStoreProvider( 4102): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4102): Added TimaKesytore provider
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837977 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/HeadlinesChannelApplication( 4102): [onCreate]
D/Headlines( 4102): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4102, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/HeadlinesChannelUtil( 4102): getCountryCode(): countryCode = PL
D/Headlines( 4102): Breath.onCreate
D/HeadlinesCardManager( 4102): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 4102): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 4102): CardProvider Library : 13
E/memtrack( 4085): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4085): failed to load memtrack module: -2
I/SELinux ( 4122): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4122):  
I/ActivityManager(  739): Killing 3028:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  739): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=739 (0x0)
D/PowerManagerService(  739): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=739, ws=WorkSource{1000}) (elapsedTime=3481)
D/PowerManagerService(  739): [s] UserActivityState : 0 -> 1
D/dalvikvm( 4085): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 4126): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4126):  
I/SELinux ( 4122): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4122):  
I/SELinux ( 4122):  
I/SELinux ( 4122): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4122): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4122): >>>>> Normal User
E/dalvikvm( 4122): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
E/SELinux ( 4122): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/SELinux ( 4126): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4126):  
I/SELinux ( 4126):  
I/SELinux ( 4126): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4126): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4126): >>>>> Normal User
E/dalvikvm( 4126): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 4126): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4122): in addTimaSignatureService
D/TimaKeyStoreProvider( 4122): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4122): Added TimaKesytore provider
D/AndroidRuntime( 4085): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 4126): in addTimaSignatureService
D/TimaKeyStoreProvider( 4126): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4126): Added TimaKesytore provider
I/SA      ( 4047): [RC New] [v2liruge] api execute + 795
I/SA      ( 4047): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 4047): AsyncTask #1 calls detatch()
I/SA      ( 4047): [TPMU] getNetworkMcc : 
I/SA      ( 4047): [SCU] saveMccToPreferece Start
I/SA      ( 4047): [SCU] RegionMCC : 260
I/SA      ( 4047): [SSP] query invoked
I/SA      ( 4047): [TPMU] GetMccFromDB : null
I/SA      ( 4047): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4047): [SCU] saveMccToPreferece End
I/SA      ( 4047): [RC New] executeRequest [v2liruge] end. 836
I/SA      ( 4047): [RC New] Execute end
I/SA      ( 4047): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4047): [OR] GetMyCountryZoneTask Success
D/MagazineService Version( 4126): Magazine-Channel: 13
D/MagazineService Version( 4126): Magazine-Provider: 13
D/MagazineService Version( 4126): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 4126): [onCreate]
D/AndroidRuntime( 4085): Shutting down VM
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4126, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 4085): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
D/MagazineService::CardProviderContentProvider( 4126): insertProvider: provider already exists.: com.samsung.android.app.headlines
D/MagazineService::CardProviderContentProvider( 4126): insertProvider: provider is updated.: com.samsung.android.app.headlines
D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 4102): registerCardProvider: provider already exists.
I/Headlines( 4102): HeadlinesDataCenter ctor
I/Headlines( 4102): HeadlinesDataCenter. mLocale = en_US
D/HeadlinesChannelUtil( 4102): getCountryCode(): countryCode = PL
D/HeadlinesCardManager( 4102): HeadlinesCardManager : constructor welcome :YES
D/Headlines( 4102): Breath timer started. interval : 30000
D/Headlines( 4102): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4102): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4102): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4102): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4102): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4102): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 4102): requestUpdateNewsWelcomeCard !!! no welcome card
I/ActivityManager(  739): Killing 3041:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #43
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 4122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 4122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4122): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 4122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/dalvikvm(  739): GC_CONCURRENT freed 7701K, 21% free 42031K/53156K, paused 5ms+21ms, total 220ms
,D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 186ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 180ms
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 187ms
,W/ContextImpl( 4122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=15 Removed Uoast (12/12)
,I/SurfaceFlinger(  246): id=15 Removed Uoast (-2/12)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,V/WebViewChromium( 4122): Binding Chromium to the main looper Looper (main, tid 1) {429b41f8}
,I/chromium( 4122): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4122): Initializing chromium process, renderers=0
,E/SMD     (  240): DCD ON
,W/chromium( 4122): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4122): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4122): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4122): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4122): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4122): Remote Branch: 
I/Adreno-EGL( 4122): Local Patches: 
I/Adreno-EGL( 4122): Reconstruct Branch: 
,I/NSApplication( 4122): Starting up...
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4122, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,V/AlarmManager(  739): waitForAlarm result :8
,I/SELinux ( 4171): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4171):  
I/ActivityManager(  739): Killing 3058:com.blurb.checkout/u0a75 (adj 15): empty #43
,W/linker  ( 3557): libcordon.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/dalvikvm( 3557): No JNI_OnLoad found in /system/lib/libcordon.so 0x42cdbb80, skipping init
,I/SELinux ( 4171): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4171):  
I/SELinux ( 4171):  
,I/SELinux ( 4171): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4171): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4171): >>>>> Normal User
,E/dalvikvm( 4171): >>>>> com.google.android.apps.plus [ userId:0 | appId:10130 ]
,E/SELinux ( 4171): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4171): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4171): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4171): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4171, uid=10130 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3305): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3305): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3305): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42ce4478
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,I/SELinux ( 4199): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4199):  
,D/dalvikvm( 4171): GC_CONCURRENT freed 3680K, 26% free 13995K/18904K, paused 2ms+2ms, total 31ms
,I/ActivityManager(  739): Killing 3075:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 4199): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4199):  
I/SELinux ( 4199):  
,I/SELinux ( 4199): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4199): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4199): >>>>> Normal User
,E/dalvikvm( 4199): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4199): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4199): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4199): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4199): Added TimaKesytore provider
D/dalvikvm( 4171): GC_FOR_ALLOC freed 19K, 15% free 16082K/18904K, paused 12ms, total 12ms
,D/dalvikvm( 4171): GC_FOR_ALLOC freed 6K, 13% free 20239K/23072K, paused 17ms, total 18ms
,I/dalvikvm( 3557): Total arena pages for JIT: 11
,I/dalvikvm( 3557): Total arena pages for JIT: 12
I/dalvikvm( 3557): Total arena pages for JIT: 13
,I/dalvikvm( 3557): Total arena pages for JIT: 14
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/WaitQueueForNetworkActivate( 4199): notifyNetworkActivated
,W/ContextImpl( 4199): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  739): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SSRMv2:SIOP(  739): SIOP:: AP = 330, Delta = 10
D/YouTube ( 3596): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/YouTube ( 3596): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3596): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
D/SensorService(  739):   -0.0 -0.1 9.6
,D/hcjo    ( 4199): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4199): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4199): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4199): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4199): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4199): exit::IDLE
,D/InitializeManagerStateMachine( 4199): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4199): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4199): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4199): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4199): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4199): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4199): entry::SUCCESS
,D/hcjo    ( 4199): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4199): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4199): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4199): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4199): exit::SUCCESS
,D/InitializeManagerStateMachine( 4199): entry::IDLE
I/ActivityManager(  739): Killing 3092:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,D/dalvikvm( 1292): null clazz in OP_INSTANCE_OF, single-stepping
,I/iu.SyncManager( 1756): SYNC; picasa accounts
,D/NetworkLogImpl( 1756): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1756): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1756): num queued entries: 0
,I/iu.UploadsManager( 1756): num updated entries: 0
,I/iu.SyncManager( 1756): NEXT; no task
,I/SELinux ( 4223): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4223):  
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 50% free 9506K/18904K, paused 2ms+3ms, total 27ms
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3878): mConnectivityHandler : connected
,I/SELinux ( 4223): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4223):  
I/SELinux ( 4223):  
,I/SELinux ( 4223): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4223): >>>>> Normal User
,E/dalvikvm( 4223): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 4223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 2ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 4223): in addTimaSignatureService
,W/PCWCLIENTTRACE_AccountUtil( 3878): [hasSamungAccount] - No Samsung Account
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 2ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 4223): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4223): Added TimaKesytore provider
,W/linker  ( 3878): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 3878): ================================================
I/CSTORAGE( 3878):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 3878): ================================================
D/dalvikvm( 3878): No JNI_OnLoad found in /system/lib/libterrier.so 0x42cdb550, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3878): [GetString-S]
,I/terrier ( 3878): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 3878): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 3878): App is not loaded in QSEE
,D/QSEECOMAPI: ( 3878): Loaded image: APP id = 4
,D/QSEECOMAPI: ( 3878): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 3878): QSEECom_shutdown_app, app_id = 4
E/terrier ( 3878): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3878): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 3878): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3878): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3878): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 3878): [ensureRegistration] - No Samsung account
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{4371fdc0 u0 com.sec.knox.seandroid/.service.SEAndroidLauncher}
,D/BootCompletedReceiver(  739): onReceive
I/ActivityManager(  739): Killing 3110:com.samsung.android.app.colorblind/1000 (adj 15): empty #43
,I/KLMS-2.3.201 : ( 3973): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/KLMS-2.3.201 : ( 3973): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1454090192073
,I/KLMS-2.3.201 : ( 3973): StateImplV2() : dateTimeChanged() : Fri Jan 29 18:56:32 CET 2016
,I/SELinux ( 4239): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4239):  
,I/SELinux ( 4239): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4239):  
I/SELinux ( 4239):  
,I/SELinux ( 4239): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4239): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4239): >>>>> Normal User
,E/dalvikvm( 4239): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
,E/SELinux ( 4239): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4239): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4239): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4239): Added TimaKesytore provider
,D/ConnectivityService(  739): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4239, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
,W/ContextImpl( 4239): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 4257): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4257):  
,E/Device Type Shared Preferences( 4239): Device Type Shared Preferences - getDeviceTypeChecked -true
,E/Device Type Shared Preferences( 4239): Device Type Shared Preferences - not connecting to service
,E/com.sec.android.app.shealth.SHealthApplication( 4239): ContentProvider is not null
,I/SELinux ( 4257): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4257):  
I/SELinux ( 4257):  
,I/SELinux ( 4257): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4257): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4257): >>>>> Normal User
,E/dalvikvm( 4257): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 4257): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4257): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4257): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4257): Added TimaKesytore provider
,V/MediaPlayer( 4239): decode(61, 33979084, 48105)
,V/MediaPlayerService(  249): decode(35, 33979084, 48105)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
,V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57cc8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b57cc8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57cc8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57cc8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  249): notify(0xb7b57cc8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
,V/MediaPlayerService(  249): wait for playback complete
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57cc8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57cc8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57cc8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(63, 33914984, 10421)
,V/MediaPlayerService(  249): decode(35, 33914984, 10421)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4257, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): addBatteryData
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55f38, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(64, 37457308, 34198)
V/MediaPlayerService(  249): decode(35, 37457308, 34198)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener,
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm( 4257): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42cd6b90, skipping init
I/SecureStorage( 4257): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4257): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/SecureStorage(  382): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4257
I/SecureStorage(  382): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4257): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 4257): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  382): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4257
I/SecureStorage(  382): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b6d718, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(65, 33862452, 7405)
V/MediaPlayerService(  249): decode(35, 33862452, 7405)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(66, 37547940, 5555)
V/MediaPlayerService(  249): decode(35, 37547940, 5555)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b618c0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(67, 30367732, 5085)
V/MediaPlayerService(  249): decode(35, 30367732, 5085)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b54450, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(68, 30372876, 21552)
V/MediaPlayerService(  249): decode(35, 30372876, 21552)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  249): postAudioEOS delayUs (0)
,V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
,V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b59fa0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(69, 37543652, 4230)
,V/MediaPlayerService(  249): decode(35, 37543652, 4230)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
,V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{43630408 u0 com.samsung.android.sconnect/.periph.PeriphService}
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b61918, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents ,(keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(70, 30337076, 9400)
V/MediaPlayerService(  249): decode(35, 30337076, 9400)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 5, 0, 0)
V/AudioCache(  249): ignored
,V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
,I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/SO_AGENT( 3993): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
I/SO_AGENT( 3993): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5eb70, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
,V/MediaPlayer( 4239): decode(71, 33925464, 44276)
V/MediaPlayerService(  249): decode(35, 33925464, 44276)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/SA      ( 4047): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
,V/MediaPlayerService(  249): wait for playback complete
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b641d0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
,V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(72, 33885672, 29256)
V/MediaPlayerService(  249): decode(35, 33885672, 29256)
I/SELinux ( 4321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4321):  
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
,V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  249): notify(0xb7b5dbf0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
,V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
,V/AwesomePlayer(  249): prepareAsync
,V/MediaPlayerService(  249): wait for prepare
,I/ActivityManager(  739): Killing 3124:com.dropbox.android/u0a91 (adj 15): empty #43
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b5dbf0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5dbf0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5dbf0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5dbf0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
,I/SELinux ( 4321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4321):  
I/SELinux ( 4321):  
I/SELinux ( 4321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
,E/SELinux ( 4321): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4321): >>>>> Normal User
,E/dalvikvm( 4321): >>>>> com.android.mms [ userId:0 | appId:10048 ]
,V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5dbf0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5dbf0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
,V/StagefrightPlayer(  249): reset
,E/SELinux ( 4321): [DEBUG] seapp_context_lookup: seinfoCategory = release
,V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b5dbf0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
,V/MediaPlayer( 4239): decode(73, 37491572, 52024)
,V/MediaPlayerService(  249): decode(35, 37491572, 52024)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  249): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
,I/AudioPlayer(  249): First fillBuffer call!!
,D/TimaKeyStoreProvider( 4321): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4321): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4321): Added TimaKesytore provider
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
,V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b57e48, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4239): decode(74, 33969800, 9226)
,V/MediaPlayerService(  249): decode(35, 33969800, 9226)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b53f60, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
,V/AwesomePlayer(  249): prepareAsync
,V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,W/dalvikvm( 4321): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b53f60, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  249): notify(0xb7b53f60, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b53f60, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b53f60, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
,V/MediaPlayerService(  249): wait for playback complete
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  249): postAudioEOS delayUs (0)
,V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b53f60, 2, 0, 0)
,V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b53f60, 7, 0, 0)
V/AudioCache(  249): ignored
,V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache(  249): wait - success
V/AwesomePlayer(  249): addBatteryData
,V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b53f60, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
,V/MediaPlayer( 4239): decode(75, 30402580, 4509)
,V/MediaPlayerService(  249): decode(35, 30402580, 4509)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
,V/MediaPlayerService(  249): wait for playback complete
,V/AwesomePlayer(  249): postAudioEOS delayUs (0)
,V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
,V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
,V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb7b55bc0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
,D/Mms/MmsApp( 4321): [start]    onCreate()
,D/Mms/TelephonyPermission( 4321): start operation mode monitor
,D/Mms/TelephonyPermission( 4321): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4321): isDefault true
,D/Mms/MmsApp( 4321): onCreate() com.android.mms
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/Mms/MmsConfig( 4321): before partial update
,D/Mms/MmsConfig( 4321): Load Resize quality : 80
,D/Mms/MmsConfig( 4321):  enable multiwindow = false
,E/Mms/MessageUtils( 4321): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 4321): updateCountryIso : update country iso info 
D/CountryDetector(  739): The first listener is added
,D/TP/MmsSmsProvider( 1237): match 13:Elapsed time : 0.881 ms
,D/AmoledAdjustTimer(  739): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TP/MmsSmsProvider( 1237): match 12:Elapsed time : 1.029 ms
,D/Mms/Conversation( 4321): init()
,D/TP/MmsSmsProvider( 1237): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1237): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/TP/MmsSmsProvider( 1237): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1237): need read changed broadcast:false
,I/Mms/ReservationManager( 4321): ReservationManager()
,I/Mms/ReservationManager( 4321): resetAfterConnected()
,D/TP/MmsSmsProvider( 1237): match 7:Elapsed time : 3.169 ms
,I/Mms/ReservationManager( 4321): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 4321): [end]    onCreate()
,D/Mms/MessagingNotification( 4321): [start]    nonBlockingUpdateMessageIndicator()
,D/dalvikvm( 3557): GC_CONCURRENT freed 6811K, 43% free 10788K/18904K, paused 3ms+8ms, total 57ms
,D/Mms/MessagingNotification( 4321): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 4321): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 4321): isDefault true
,D/TP/MmsSmsProvider( 1237): match 200:Elapsed time : 1.015 ms
,D/Mms/DownloadManager( 4321): Service state changed: Bundle[mParcelledData.dataSize=740]
D/Mms/DownloadManager( 4321): roaming ------> false
,D/Mms/DownloadManager( 4321): mAutoDownloadSecondary ------> true
,D/TP/MmsSmsProvider( 1237): match 8:Elapsed time : 4.917 ms
,I/SELinux ( 4360): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4360):  
,I/ActivityManager(  739): Killing 3145:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 4360): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4360):  
I/SELinux ( 4360):  
,I/SELinux ( 4360): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4360): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4360): >>>>> Normal User
,E/dalvikvm( 4360): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 4360): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BadgeProvider( 1340): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 4360): in addTimaSignatureService
,D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1340): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 4321): setBadgeCount(), count=0
,D/Launcher.Model( 1249): reloadBadges entered.
,D/TimaKeyStoreProvider( 4360): Cannot add TimaSignature Service, License check Failed
,D/MessagingNotification( 4321): remove alarm
,D/ActivityThread( 4360): Added TimaKesytore provider
,D/Mms/MessagingNotification( 4321): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 4321): [end]    nonBlockingUpdateMessageIndicator()
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4360, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  739): Killing 3160:com.sec.android.fwupgrade/1000 (adj 15): empty #43
,I/ Time Manager ( 4360): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 4375): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4375):  
,I/SELinux ( 4375): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4375):  
I/SELinux ( 4375):  
I/SELinux ( 4375): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4375): >>>>> Normal User
E/dalvikvm( 4375): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
E/SELinux ( 4375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4375): in addTimaSignatureService
D/dalvikvm(  739): GC_CONCURRENT freed 7899K, 21% free 42294K/53156K, paused 7ms+23ms, total 245ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 58ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 104ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 128ms
D/TimaKeyStoreProvider( 4375): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4375): Added TimaKesytore provider
E/SMD     (  240): DCD ON
I/SecureStorage(  382): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  382): [INFO]: SPID(0x00000003)PID: 4257, TID: 4257
I/SELinux ( 4388): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4388):  
I/ActivityManager(  739): Killing 3174:com.sec.factory.camera/1000 (adj 15): empty #43
I/SELinux ( 4388): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4388):  
I/SELinux ( 4388):  
I/SELinux ( 4388): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4388): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4388): >>>>> Normal User
E/dalvikvm( 4388): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 4388): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4388): in addTimaSignatureService
D/TimaKeyStoreProvider( 4388): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4388): Added TimaKesytore provider
I/SecureStorage( 4257): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4257): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4257): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4257): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4257): Open platform.db in secure mode
D/elm:14132( 4388): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/elm:14132( 4388): ELMEngine.ELMEngine( context ).
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4388, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 4388): MDMBridge.setEnterpriseBridge()
D/elm:14132( 4388): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
I/knox    ( 3244): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/elm:14132( 4388): ElmAgentService : onCreate()
W/ContextImpl( 3244): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3244): MainReceiver.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 4388): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
I/knox    ( 3244): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 3244): KNOXAgentService : onCreate()
D/knox    ( 3244): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3244): KNOXAgentService. startJobThread() start
D/knox    ( 3244): KNOXAgentService. JobThread()
D/knox    ( 3244): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3244): KNOXAgentService. startJobThread() wait
D/elm:14132( 4388): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 4388): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 4388): ModuleBase.resetCalllogAPIAlarm()
I/SELinux ( 4403): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4403):  
D/knox    ( 3244): KNOXAgentService : onDestroy().
D/knox    ( 3244): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 4388): ModuleBase.ModifySetAlarm()
D/elm:14132( 4388): MDMBridge.getInstance()
D/elm:14132( 4388): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 4388): ElmAgentService : onDestroy().
I/ActivityManager(  739): Killing 3186:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #43
I/SELinux ( 4403): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4403):  
I/SELinux ( 4403):  
I/SELinux ( 4403): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4403): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 4403): >>>>> Normal User
E/dalvikvm( 4403): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
E/SELinux ( 4403): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 4403): in addTimaSignatureService
D/TimaKeyStoreProvider( 4403): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4403): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4257): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4257): ...getDatabaseLocked(b,b,pwd)
I/ActivityManager(  739): Killing 3202:com.google.android.talk/u0a105 (adj 15): empty #43
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4403, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4416): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4416):  
I/ActivityManager(  739): Killing 3228:com.samsung.helphub/1000 (adj 15): empty #43
,D/dalvikvm( 3557): GC_CONCURRENT freed 2443K, 46% free 10295K/18904K, paused 2ms+6ms, total 34ms
,I/SELinux ( 4416): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4416):  
I/SELinux ( 4416):  
,I/SELinux ( 4416): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4416): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4416): >>>>> Normal User
,E/dalvikvm( 4416): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 4416): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4416): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4416): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4416): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4416, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 4416): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42cdbd50, skipping init
D/TimeService( 4416): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454090194309
D/        ( 4416): TimeServiceNative: User Time to be set is 1454090194309
D/QC-time-services( 4416): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4416): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 4416): Lib:time_genoff_operation: pargs->ts_val = 1454090194309
,D/QC-time-services( 4416): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  301): Daemon: Connection accepted:time_genoff
D/QC-time-services(  301): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  301): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454090194309
D/QC-time-services(  301): Daemon:genoff_opr: Base = 2, val = 1454090194309, operation = 0
D/QC-time-services(  301): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/5/70 9:53:18
D/QC-time-services(  301): Daemon:Value read from RTC seconds = 5478798000
D/QC-time-services(  301): Daemon:new time 1454090194309 
D/QC-time-services(  301): Daemon: delta 1448611396309 genoff 1448611396309 
D/QC-time-services(  301): Daemon:genoff_persistent_update: Writing genoff = 1448611396309 to memory
D/QC-time-services(  301): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  301): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  301): Updating the TOD offset
D/QC-time-services(  301): Daemon:genoff_persistent_update: Writing genoff = 1448611396309 to memory
D/QC-time-services(  301): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  301): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  301): Daemon:Update to modem bit set
D/QC-time-services(  301): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  301): Daemon: Base = 2, Value being sent to MODEM = 1138125394309
,E/QC-time-services( 4416): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  301): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  301): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  739): Killing 3262:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #43
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1465): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1465): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 1756): Checkin interval check for package: unspecified last checkin: 1453985581353 min interval config: 0 actual interval: 104613047
,D/dalvikvm( 1292): GC_EXPLICIT freed 1204K, 44% free 10742K/18904K, paused 3ms+5ms, total 31ms
,I/SELinux ( 4430): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4430):  
,I/SELinux ( 4430): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4430):  
I/SELinux ( 4430):  
,I/SELinux ( 4430): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4430): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4430): >>>>> Normal User
,E/dalvikvm( 4430): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
,E/SELinux ( 4430): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,W/ContextImpl( 3557): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1659 android.content.ContextWrapper.sendStickyBroadcast:439 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:841 <bottom of call stack> 
I/Process ( 3557): Sending signal. PID: 3557 SIG: 9
D/TimaKeyStoreProvider( 4430): in addTimaSignatureService
D/TimaKeyStoreProvider( 4430): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4430): Added TimaKesytore provider
,I/ActivityManager(  739): Process com.sec.android.app.sysscope (pid 3557) (adj 0) has died.
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardViewMediator( 1064): handleKeyguardDoneDrawing
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4430, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
,D/SensorService(  739):   -0.0 -0.1 9.6
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{43865b28 u0 tv.peel.smartremote/tv.peel.samsung.widget.service.WidgetTimerService}
,E/SPPClientService( 4031): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,I/SELinux ( 4455): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4455):  
,I/ActivityManager(  739): Killing 3276:com.LocalFota/u0a110 (adj 15): empty #43
,I/SELinux ( 4455): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4455):  
I/SELinux ( 4455):  
,I/SELinux ( 4455): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4455): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4455): >>>>> Normal User
,E/dalvikvm( 4455): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10038 ]
,E/SELinux ( 4455): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4455): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4455): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4455): Added TimaKesytore provider
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SPPClientService( 4455): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4455): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 4455): PushLog.txt file is not deleted.
D/SPPClientService( 4455): PushLog.txt file is not deleted.
,D/SPPClientService( 4455): ============PushLog. stop!
,I/SELinux ( 4471): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4471):  
,I/ActivityManager(  739): Killing 3291:com.sec.android.app.mt/1000 (adj 15): empty #43
,D/dalvikvm(  247): GC_EXPLICIT freed 42K, 50% free 9506K/18904K, paused 2ms+3ms, total 42ms
,I/SELinux ( 4471): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4471):  
I/SELinux ( 4471):  
,I/SELinux ( 4471): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4471): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4471): >>>>> Normal User
,E/dalvikvm( 4471): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10038 ]
,E/SELinux ( 4471): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 2ms+2ms, total 21ms
,D/TimaKeyStoreProvider( 4471): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4471): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4471): Added TimaKesytore provider
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 2ms+3ms, total 20ms
,I/Mms/MmsApp( 4321):  start initViewCache mms
,E/SPPClientService( 4471): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4471): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 4471): PushLog.txt file is not deleted.
D/SPPClientService( 4471): PushLog.txt file is not deleted.
,D/SPPClientService( 4471): ============PushLog. stop!
,E/LNoti   ( 4471): [PhoneStatusChangeReceiver] This device doesn't register yet.
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{438620b0 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,D/Mms/ComposeMessageFragment( 4321): fillCache, easy = false
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/GAV2    ( 4122): Thread[GAThread,5,main]: No campaign data found.
,D/AbsListView( 4321): Get MotionRecognitionManager
,D/MotionRecognitionService(  739):  ssp status : false
,I/dalvikvm( 4321): Could not find method android.sec.multiwindow.MultiWindow.createInstance, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4321): VFY: unable to resolve static method 1402: Landroid/sec/multiwindow/MultiWindow;.createInstance (Landroid/app/Activity;)Landroid/sec/multiwindow/MultiWindow;
,D/dalvikvm( 4321): VFY: replacing opcode 0x71 at 0x03bb
I/dalvikvm( 4321): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4321): VFY: unable to resolve virtual method 1403: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 4321): VFY: replacing opcode 0x74 at 0x0759
I/dalvikvm( 4321): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4321): VFY: unable to resolve virtual method 1403: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
,D/dalvikvm( 4321): VFY: replacing opcode 0x74 at 0x07e8
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,V/WebViewChromium( 4321): Binding Chromium to the main looper Looper (main, tid 1) {429b0588}
,I/chromium( 4321): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4321): Initializing chromium process, renderers=0
,W/chromium( 4321): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4321): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4321): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4321): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4321): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4321): Remote Branch: 
I/Adreno-EGL( 4321): Local Patches: 
I/Adreno-EGL( 4321): Reconstruct Branch: 
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/checkbox( 4321): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4321): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4321): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4321): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/Mms/BubbleViewCache( 4321): fillCache bubble = 8
,D/Mms/Synchronizer( 4321): [start]    dbSync()
,D/TP/MmsSmsProvider( 1237): match 0:Elapsed time : 1.044 ms
,D/ApplicationPolicy(  739): isApplicationInstallationEnabled
,D/TP/MmsSmsProvider( 1237): update uri: content://mms-sms/db_synchronization
,V/TP/MmsSmsProvider( 1237): syncDBData start
D/PackageManager(  739): Time to collect certificates: 14.211 seconds
,W/PackageManager(  739): verifying app can be installed or not
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking PKG WL - false
V/TP/MmsSmsProvider( 1237): syncDBData sms end
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  739): isApplicationInstallationEnabled :  enabled true
V/TP/MmsSmsProvider( 1237): syncDBData mms end
,V/TP/MmsSmsProvider( 1237): syncDBData end
,D/Mms/Synchronizer( 4321): [end]    dbSync()
D/PackageManager(  739): Existing package: 
D/PackageManager(  739): doRename: 
D/PackageManager(  739): doRename apk path: 
D/PackageManager(  739): installNewPackageLI: 
I/MyContainer(  739): package (com.test.thalitest) installed with  seinfo=default
I/PackageManager(  739): Package com.test.thalitest codePath changed from /data/app/com.test.thalitest-12.apk to /data/app/com.test.thalitest-13.apk; Retaining data and using new
,W/MyContainer(  739):  assignseinfovalue, <package name > = com.test.thalitest<seinfo> = default<category> = 1023<allow category> = 0,501-1023
D/Mms/MessagingNotification( 4321): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/MmsSmsProvider( 1237): match 6:Elapsed time : 1.464 ms
,D/Mms/MessagesLockscreen( 4321): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1064): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1064): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1064): updateContainer()
D/ContextualEventContainer( 1064): update()
D/ContextualEventContainer( 1064): handleUpdate()
D/ContextualEventManager( 1064): getTopEventView()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,D/ContextualEventManager( 1064): removeContextualEvent(): requestClass=com.android.mms
,D/Mms/MessagesLockscreen( 4321): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,I/ActivityManager(  739): Killing 3338:com.sec.android.app.camera/u0a147 (adj 15): empty #43
D/ContextualEventManager( 1064): top view = flightmode
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1064): getTopEventClass()
D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
E/CscFactoryReceiver( 1237): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/ContextualEventManager( 1064): getTopEventClass()
D/ContextualEventManager( 1064): getTopContextualEvent()
D/CscFactoryReceiver( 1237): Media DB Scanner finished.
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
D/ContextualEventManager( 1064): getTopContextualEvent()
,D/CscFactoryReceiver( 1237): start service to Set Ringtone
,D/CscFactoryReceiver( 1237): start service to Set Notification
,D/CscFactoryReceiver( 1237): start service to Set Alarmtone
,D/CscUpdateService( 1237): onStart
,E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
,D/UsbManager( 1064):  :::: isUsb30Available :: return = false from pid = 1064
D/CscUpdateService( 1237): only ringtone update
,D/CscUpdateService( 1237): onStart
,E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1237): only notification update
D/CscUpdateService( 1237): onStart
E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1237): only alarmtone update
,E/CscParser( 1237): update(): xml file exist
,E/CscParser( 1237): update(): xml file exist
,I/SELinux ( 4508): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4508):  
,E/CscParser( 1237): update(): xml file exist
,D/dalvikvm( 1064): GC_EXPLICIT freed 13595K, 33% free 31318K/46128K, paused 3ms+7ms, total 45ms
D/ContextualEventManager( 1064): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1064): updateContainer()
,D/ContextualEventContainer( 1064): update()
,D/SecContextualClockFlightMode( 1064): handleUpdateClock()
,D/KeyguardProperties( 1064): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/ContextualEventContainer( 1064): handleUpdate()
D/ContextualEventManager( 1064): getTopEventView()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,D/ContextualEventManager( 1064): top view = flightmode
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,W/CSCSettings( 1237): Setting Ringtones (type) : 1
I/SELinux ( 4508): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4508):  
I/SELinux ( 4508):  
,I/SELinux ( 4508): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4508): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4508): >>>>> Normal User
E/dalvikvm( 4508): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
D/CscParser( 1237): RingTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,D/UsbManager( 1064):  :::: isUsb30Available :: return = false from pid = 1064
E/SELinux ( 4508): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/KeyguardViewMediator( 1064): handleKeyguardDoneDrawing
W/CSCSettings( 1237): Setting Ringtones (type) : 2
D/CscParser( 1237): MessageTone: null
W/CSCSettings( 1237): 1. Tag_Str: null
,D/SecContextualClockFlightMode( 1064): handleUpdateClock()
,D/KeyguardProperties( 1064): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardViewMediator( 1064): handleKeyguardDoneDrawing
,D/TimaKeyStoreProvider( 4508): in addTimaSignatureService
,D/KeyguardViewMediator( 1064): handleKeyguardDoneDrawing
,D/TimaKeyStoreProvider( 4508): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4508): Added TimaKesytore provider
,W/CSCSettings( 1237): Setting Ringtones (type) : 4
,D/CscParser( 1237): AlarmTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,D/FactoryTestApp( 3807): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
,I/IndexBroadcastProcessorService( 4508): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,D/FactoryTestApp( 3807): [XMLDataStorage$parseXML] is Live Demo : false
D/FactoryTestApp( 3807): [XMLDataStorage$parseXML] modelXML=sm-g800h.dat
D/FactoryTestApp( 3807): [XMLDataStorage$parseXML] deviceXML=kmini3g.dat
,D/FactoryTestApp( 3807): [XMLDataStorage$parseXML] nameXML=kmini3gxx.dat
,I/IndexBroadcastProcessorService( 4508): lucene systemReadyToIndex
,I/IndexService( 4508): lucene onCreate ...service
W/ActivityThread( 3807): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/FactoryTestApp( 3807): [XMLDataStorage$parseAsset] Convert dat file: sm-g800h.dat
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4508): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4508): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,I/dalvikvm( 4508): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
,W/dalvikvm( 4508): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 4508): VFY: replacing opcode 0x71 at 0x01ed
,I/IndexService( 4508): lucene beginIndexing
,D/FactoryTestApp( 3807): [XMLDataStorage$parseAsset] Decode base file: factory.dat
,E/File    ( 4508): fail readDirectory() errno=13
,I/IndexService( 4508): lucene onDestroy start
I/IndexService( 4508): lucene onDestroy end
,I/IndexService( 4508): lucene cleanupEverything start
I/IndexService( 4508): ERROR: null
,E/ParserThreadsListManager( 4508): Lucene Interrupt in run
I/IndexService( 4508): lucene cleanupEverything end
,I/Process ( 4508): Sending signal. PID: 4508 SIG: 9
,I/ActivityManager(  739): Process com.samsung.indexservice (pid 4508) (adj 9) has died.
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=MIC_COUNT
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FONT_SIZE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_RECENT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_USER
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_POWER
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
,D/dalvikvm( 3807): GC_CONCURRENT freed 7333K, 46% free 10354K/18904K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 3807): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_ATMEL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_ATMEL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_ATMEL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_ATMEL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_ATMEL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_ATMEL
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END,
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN,
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX,
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
,E/SMD     (  240): DCD ON
,D/dalvikvm( 3807): GC_CONCURRENT freed 2049K, 46% free 10352K/18904K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 3807): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
,E/installd(  255): creating libsymlink '/data/data/com.test.thalitest/lib'
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=BATTERY_TEMP_ADC
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 3807): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
,D/FactoryTestApp( 3807): [XMLDataStorage$parseAsset] SemiFunctionMenu
,D/FactoryTestApp( 3807): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 3807): [Support$Properties.get] property=ro.factory.factory_binary
,D/FactoryTestApp( 3807): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
,D/FactoryTestApp( 3807): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 3807): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
I/FactoryTestApp( 3807): [ModuleCommon$ModuleCommon] Create ModuleCommon
I/FactoryTestApp( 3807): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 3807): [ModuleCommon$getMediaScanningCount] get : 0
,D/FactoryTest( 3807): User mode
,I/FactoryTestApp( 3807): [ModuleCommon$getMediaScanningCount] get : 1
W/ContextImpl( 3807): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:269 android.app.ActivityThread.handleReceiver:2698 
,D/GalleryCacheReady( 2344): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/SELinux ( 4535): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4535):  
,D/GalleryCacheReady( 2344): handleMeidaScanFinish()
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 2344): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 2344): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
I/SELinux ( 4535): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4535):  
I/SELinux ( 4535):  
,I/SELinux ( 4535): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,W/ContextImpl( 2344): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,W/Vold    (  227): Returning OperationFailed - no handler for errno 30
E/SELinux ( 4535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4535): >>>>> Normal User
E/dalvikvm( 4535): >>>>> com.sec.android.app.music:service [ userId:0 | appId:10150 ]
E/SELinux ( 4535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/FaceInterface( 2344): requestFaceScan() is called.
,I/FaceInterface( 2344): startFaceScan() : waiting 5 sec
,D/TimaKeyStoreProvider( 4535): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4535): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4535): Added TimaKesytore provider
,D/dalvikvm( 4530): DexOpt: load 34ms, verify+opt 87ms, 650340 bytes
,D/PackageManager(  739): Time to dexopt: 0.301 seconds
,D/PackageManager(  739): !@killApplicatoin: 10179, update pkg
,W/PackageManager(  739): Code path for pkg : com.test.thalitest changing from /data/app/com.test.thalitest-12.apk to /data/app/com.test.thalitest-13.apk
,W/PackageManager(  739): Resource path for pkg : com.test.thalitest changing from /data/app/com.test.thalitest-12.apk to /data/app/com.test.thalitest-13.apk
,D/PackageManager(  739): Time to scan apk: 1.347 seconds
,D/PackageManager(  739): updateSettingsLI: 
,W/LocalSuggestAlbumData( 2344): query fail: 
,W/LocalSuggestAlbumData( 2344): query fail: 
,I/dalvikvm(  739): Total arena pages for JIT: 11
,I/dalvikvm(  739): Total arena pages for JIT: 12
I/dalvikvm(  739): Total arena pages for JIT: 13
,I/dalvikvm(  739): Total arena pages for JIT: 14
,I/dalvikvm(  739): Total arena pages for JIT: 15
,D/PackageManager(  739): New package installed in 
,D/CustomFrequencyManagerService(  739): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1401600  uid : 1000  pid : 739  pkgName : SSRM_PKG_OPT@21
,D/dalvikvm(  739): GC_FOR_ALLOC freed 4229K, 21% free 41998K/53156K, paused 182ms, total 182ms
,D/PackageManager(  739): doPostInstall for uid{10179}
D/PackageManager(  739): + starting rerstore round-trip 1
,D/PackageManager(  739): checkUidPermission - Execution time: 303 ms
D/PackageManager(  739): No resotre for backup - queue post-install for 1
,D/com.samsung.musicplus.bitmapcache.BitmapCache( 4535): Allocated bitmap cache: 13421772
,D/dalvikvm(  739): GC_FOR_ALLOC freed 18770K, 56% free 23402K/53156K, paused 150ms, total 150ms
,D/PackageManager(  739): queryIntentReceivers - Execution time: 151 ms
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{43bf5250 u0 com.qualcomm.atfwd/.AtFwdService}
I/PowerManagerService-JNI(  739): >>>>>>>>in native...
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "sms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PackageManager(  739): [MSG] MCS_UNBIND
I/PackageManager(  739): calling disconnectService()
,D/PackageManager(  739): Trying to unbind to DefaultContainerService
,D/PackageManager(  739): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager(  739): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10011, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@44f21f48, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/ActivityManager(  739): Killing 3352:com.sec.android.inputmethod/1000 (adj 15): empty #43
,I/InputReader(  739): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "sms"
D/PackageManager(  739): [MSG] POST_INSTALL: observer{1130650656}
D/PackageManager(  739):           Handling post-install for 1
D/PackageManager(  739): Sending to user 0: act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.UID=10179, android.intent.extra.user_handle=0}]
,W/InputMethodInfo(  739): Duplicated subtype definition found: , voice
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "sms"
,I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/QuickConnect[1.1][2] ( 3305): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_ADDED, package : com.test.thalitest
,I/InputReader(  739): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  739): Killing 3426:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "smsto"
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/CscFactoryReceiver( 1237): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 1237): Media DB Scanner finished.
,D/CscFactoryReceiver( 1237): start service to Set Ringtone
,D/CscFactoryReceiver( 1237): start service to Set Notification
,D/CscFactoryReceiver( 1237): start service to Set Alarmtone
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "sms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "smsto"
I/SELinux ( 4566): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4566):  
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  739): PackageReceiver onReceive()
,D/RCPManagerService(  739): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService(  739):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: null
,D/RCPManagerService(  739):  PackageReceiver onReceive() bundle null
,I/SELinux ( 4566): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4566):  
I/SELinux ( 4566):  
,I/SELinux ( 4566): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4566): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4566): >>>>> Normal User
,E/dalvikvm( 4566): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
,E/SELinux ( 4566): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 4566): in addTimaSignatureService
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "sms"
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4566): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4566): Added TimaKesytore provider
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  739): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/SensorService(  739):   -0.1 -0.1 9.5
,V/BackupManagerService(  739): addPackageParticipantsLocked: #1
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
,I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PersonaPolicyManagerService(  739): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CscUpdateService( 1237): onStart
,E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1237): only ringtone update
D/CscUpdateService( 1237): onStart
E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1237): only notification update
,E/CscParser( 1237): update(): xml file exist
,D/CscUpdateService( 1237): onStart
,E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
E/CscParser( 1237): update(): xml file exist
,D/CscUpdateService( 1237): only alarmtone update
,D/dalvikvm( 1237): GC_CONCURRENT freed 1706K, 44% free 10657K/18904K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 1237): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 1237): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 1237): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/CSCSettings( 1237): Setting Ringtones (type) : 1
D/CscParser( 1237): RingTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,E/CscParser( 1237): update(): xml file exist
,W/CSCSettings( 1237): Setting Ringtones (type) : 2
D/CscParser( 1237): MessageTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,W/CSCSettings( 1237): Setting Ringtones (type) : 4
D/CscParser( 1237): AlarmTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/FactoryTestApp( 3807): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
I/FactoryTestApp( 3807): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 3807): [FactoryTestBroadcastReceiver$onReceive] ACTION_MEDIA_SCANNER_FINISHED => XML data parsing was failed.
D/FactoryTestApp( 3807): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 3807): [Support$Properties.get] property=ro.factory.factory_binary
I/FactoryTestApp( 3807): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 3807): [ModuleCommon$getMediaScanningCount] get : 1
D/FactoryTest( 3807): User mode
I/FactoryTestApp( 3807): [ModuleCommon$getMediaScanningCount] get : 2
,I/FactoryTestApp( 3807): [ModuleCommon$getMediaScanningCount] get : 2
,D/FactoryTestApp( 3807): [Support$Values.getBoolean] id=FACTORY_TEST_APO, value=true
D/FactoryTestApp( 3807): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3807): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 3807): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
I/FactoryTestApp( 3807): [FactoryTestBroadcastReceiver$USER MODE] BOOT_COMPLETE
,I/FactoryTestApp( 3807): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted] start DummyFtClient service for APO
,I/IndexBroadcastProcessorService( 4566): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,I/IndexBroadcastProcessorService( 4566): lucene systemReadyToIndex
,W/ContextImpl( 3807): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:577 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:278 
D/FactoryTestApp( 3807): [Support$Values.getBoolean] id=SUPPORT_BOOST_MEDIASCAN, value=false
D/FactoryTest( 3807): User mode
I/FactoryTestApp( 3807): [ModuleCommon$15 Test Ready flag] set
,I/IndexService( 4566): lucene onCreate ...service
,D/dalvikvm(  739): GC_EXPLICIT freed 1904K, 55% free 24153K/53156K, paused 14ms+35ms, total 459ms
,I/FactoryTestApp( 3807): [ModuleCommon$isFirstBoot] before : false
,D/FactoryTestApp( 3807): [DummyFtClient$onCreate] Create DummyFtClient service
I/FactoryTestApp( 3807): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 3807): [DummyFtClient$onReceive] ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
D/FactoryTestApp( 3807): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 3807): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  739): return install result to caller: 1130650656
D/PackageManager(  739): returnCode: 1
,I/PackageManager(  739): Observer no longer exists.
D/FactoryTestApp( 3807): [Support$Values.getBoolean] id=SUPPORT_AUTO_WAKELOCK, value=false
D/FactoryTestApp( 3807): [DummyFtClient$onStartCommand] ...
D/FactoryTestApp( 3807): [DummyFtClient$sendBootCompletedAndFinish] ...
D/FactoryTestApp( 3807): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3807): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
D/FactoryTestApp( 3807): [IPCWriterToSecPhoneService$ResponseWriter] Create IPCWriterToSecPhoneService
,I/FactoryTestApp( 3807): [IPCWriterToSecPhoneService$connectToSecPhoneService]  
W/ContextImpl( 3807): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:141 
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,D/GalleryCacheReady( 2344): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4566): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/GalleryCacheReady( 2344): handleMeidaScanFinish()
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4566): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/SELinux ( 4585): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4585):  
,D/FaceInterface( 2344): requestFaceScan() is called.
,D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 2564): SLink location service is enable. content://media/external/images/media not register
D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 2564): SLink location service is enable. content://media/external/video/media not register
,D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
,I/LocationTagReadyService( 2564): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
,W/LocalSuggestAlbumData( 2344): query fail: 
,I/SettingSearch/SearchIntentReceiver( 1315): action : android.settings.CHANGED_ICC_LOCK_ENABLE
,W/LocalSuggestAlbumData( 2344): query fail: 
,I/FaceInterface( 2344): startFaceScan() : waiting 5 sec
,D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
I/SELinux ( 4585): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4585):  
I/SELinux ( 4585):  
,I/SELinux ( 4585): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4585): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4585): >>>>> Normal User
,E/dalvikvm( 4585): >>>>> com.sec.phone [ userId:0 | appId:1001 ]
,E/SELinux ( 4585): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/GalaxyFinderApplication( 2564): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2344): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 4585): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4585): Cannot add TimaSignature Service, License check Failed
,I/SELinux ( 4606): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4606):  
,D/ActivityThread( 4585): Added TimaKesytore provider
,I/dalvikvm( 4566): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 4566): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 4566): VFY: replacing opcode 0x71 at 0x01ed
,I/SELinux ( 4611): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4611):  
I/SELinux ( 4606): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4606):  
I/SELinux ( 4606):  
,I/SELinux ( 4606): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4606): >>>>> Normal User
,E/dalvikvm( 4606): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 4606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4606): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4606): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4606): Added TimaKesytore provider
,I/SELinux ( 4624): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4624):  
I/SELinux ( 4611): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4611):  
I/SELinux ( 4611):  
,I/SELinux ( 4611): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4611): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4611): >>>>> Normal User
,E/dalvikvm( 4611): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 4611): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SettingSearchManagerReceiver( 1237): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,I/SettingSearchManagerReceiver( 1237): addSearchInfoDB
,I/SELinux ( 4624): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4624):  
I/SELinux ( 4624):  
,I/SELinux ( 4624): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4624): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4624): >>>>> Normal User
,E/dalvikvm( 4624): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/TimaKeyStoreProvider( 4611): in addTimaSignatureService
,E/SELinux ( 4624): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 4642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4642):  
D/TimaKeyStoreProvider( 4611): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4611): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 4624): in addTimaSignatureService
D/TimaKeyStoreProvider( 4624): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4624): Added TimaKesytore provider
,I/SELinux ( 4642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4642):  
I/SELinux ( 4642):  
,I/SELinux ( 4642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4642): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4642): >>>>> Normal User
,E/dalvikvm( 4642): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 4642): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/IndexService( 4566): lucene beginIndexing
,D/TimaKeyStoreProvider( 4642): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4642): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4642): Added TimaKesytore provider
,V/KVNProvider( 4624): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 4624): getFindoCursor query string : 
,V/KVNProvider( 4624): getTagSearchCursor() tagSearchCursor count : 0
,I/FactoryTestApp( 3807): [IPCWriterToSecPhoneService$onServiceConnected] connected done
,D/FactoryTestApp( 3807): [IPCWriterToSecPhoneService$write] Send Response Message to SecPhone
,D/FactoryTestApp( 3807): [IPCWriterToSecPhoneService$write] Response ��
,D/AT_Distributor(  295): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/AT_Distributor(  295): SetAtdStatus(), 1_1_0
,D/AT_Distributor(  295): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 3807): [IPCWriterToSecPhoneService$handleMessage] Send BOOT COMPLETED done
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4642, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,W/ApplicationsProvider( 1397): Could not fetch usage stats
W/ApplicationsProvider( 1397): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1397): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1397): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1397): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1397): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1397): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1397): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/File    ( 4566): fail readDirectory() errno=13
,I/IndexService( 4566): lucene onDestroy start
,I/IndexService( 4566): lucene onDestroy end
,I/IndexService( 4566): lucene cleanupEverything start
,I/IndexService( 4566): ERROR: null
,E/ParserThreadsListManager( 4566): Lucene Interrupt in run
,I/IndexService( 4566): lucene cleanupEverything end
,I/Process ( 4566): Sending signal. PID: 4566 SIG: 9
,W/ApplicationsProvider( 1397): Could not fetch usage stats
W/ApplicationsProvider( 1397): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1397): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1397): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1397): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1397): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1397): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1397): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SettingSearchManagerReceiver( 1237): endInsert
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 4663): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4663):  
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{444caff0 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 4663): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4663):  
I/SELinux ( 4663):  
,I/SELinux ( 4663): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4663): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4663): >>>>> Normal User
,E/dalvikvm( 4663): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 4663): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/MediaStoreImporter( 3894): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/TimaKeyStoreProvider( 4663): in addTimaSignatureService
I/ActivityManager(  739): Killing 3454:com.sec.modem.settings/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 4663): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4663): Added TimaKesytore provider
I/ActivityManager(  739): Process com.samsung.indexservice (pid 4566) (adj 11) has died.
,D/AssistantMenuSettingSearch( 4663): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,D/AssistantMenuSettingSearch( 4663): Make Setting DB
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 4663): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:123 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:35 
I/ActivityManager(  739): Killing 3524:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/GCoreNlp( 1210): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/InputMethodInfo(  739): Duplicated subtype definition found: , voice
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4611, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,I/PowerManagerService-JNI(  739): CheckForString returning : -1
D/CustomFrequencyManagerService(  739): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1401600  uid : 1000  pid : 739  tag : SSRM_PKG_OPT@21
,I/SELinux ( 4682): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4682):  
,I/SELinux ( 4682): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4682):  
I/SELinux ( 4682):  
,I/SELinux ( 4682): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4682): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4682): >>>>> Normal User
,E/dalvikvm( 4682): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 4682): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4682): in addTimaSignatureService
D/EnterpriseDeviceManagerService(  739): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  739): Admin package name: com.google.android.gms
,D/TimaKeyStoreProvider( 4682): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4682): Added TimaKesytore provider
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  739): Killing 3596:com.google.android.youtube/u0a175 (adj 15): empty #43
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  739): onPackageAdded : com.test.thalitest
,E/SMD     (  240): DCD ON
,D/LocationProviderProxy(  739): applying state to connected service
,D/LocationProviderProxy(  739): applying state to connected service
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4682, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
,I/Babel   ( 4682): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4682): MmsConfig.loadMmsSettings
,I/Babel   ( 4682): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/Babel   ( 4682): MmsConfig.loadFromDatabase
,E/Babel   ( 4682): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4682): MmsConfig.loadFromResources
,E/Babel   ( 4682): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4682): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,W/Settings( 4682): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/dalvikvm( 4682): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4682): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4682): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4682): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4682): VFY: unable to resolve instance field 36
,D/dalvikvm( 4682): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4682): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4682): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4682): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4682): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4682): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4682): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42e07c08
,D/dalvikvm( 4682): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42e07c08
,D/dalvikvm( 4682): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42e07c08, skipping init
,D/dalvikvm( 4682): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42e07c08
,D/dalvikvm( 4682): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42e07c08
,V/JNIHelp ( 4682): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/knox    ( 3244): InnerIntentReceiver.onReceive() : com.sec.knox.seandroid.alarm.LOG_UPLOAD_ALARM_INTENT
,D/knox    ( 3244): KNOXAgentService. startJobThread() start
,D/knox    ( 3244): KNOXAgentService. JobThread()
,W/ContextImpl( 3244): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.InnerIntentReceiver.onReceive:171 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3244): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3244): KNOXAgentService. startJobThread() wait
D/knox    ( 3244): KNOXAgentService : onCreate()
D/knox    ( 3244): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3244): startFileChecker
I/knox    ( 3244): start checking file is exist to uploading
D/knox    ( 3244): KNOXAgentService : onDestroy().
D/knox    ( 3244): notiShow :0 / context pref : 2
D/knox    ( 3244): ModuleBase.cancelAllAlarmManageModule()
I/knox    ( 3244): denial log zip completed
,W/GCoreFlp( 1210): No location to return for getLastLocation()
,W/FusedLocationProvider( 1210): location=null
,D/GCM     ( 1292): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PowerManagerService(  739): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  739): Nap time...
,D/PowerManagerService(  739): [s] WAKEFULNESS_NAPPING
I/PowerManagerService(  739): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService(  739): Going to sleep due to screen timeout...
D/PowerManagerService(  739): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController(  739): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController(  739): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors (  739): LightSensor enable = 0
,D/Sensors (  739): LightSensor enableSensor = 0
,D/SensorManager(  739): unregisterListener ::   
,D/DisplayPowerController(  739): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/Sensors (  739): HAL:resetDataRates mEnabled=4
,D/SensorManager(  739): unregisterListener ::   
,I/ActivityManager(  739): Killing 3793:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,I/SurfaceFlinger(  246): id=16 createSurf (720x1280),-1 flag=20004, FlectronBea
,D/DisplayPowerController(  739): !@ElectronBeam entry
,D/dalvikvm( 4682): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42e07c08
,D/dalvikvm( 4682): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42e07c08
D/dalvikvm( 4682): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42e07c08
,D/dalvikvm( 4682): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42e07c08
,D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 4723): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4723):  
,I/SELinux ( 4723): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4723):  
I/SELinux ( 4723):  
,I/SELinux ( 4723): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4723): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4723): >>>>> Normal User
E/dalvikvm( 4723): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 4723): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  247): GC_EXPLICIT freed 46K, 50% free 9506K/18904K, paused 3ms+3ms, total 45ms
,D/lights  (  739): lcd : 0 +
,D/TimaKeyStoreProvider( 4723): in addTimaSignatureService
,D/lights  (  739): lcd : 0 -
,D/MISC PowerHAL(  739): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL(  739): sysfs_write +: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL(  739): sysfs_write -: /sys/class/input/input1/enabled: 0
,D/MISC PowerHAL(  739): miscpower_set_interactive: /sys/class/input/input6/enabled
,D/MISC PowerHAL(  739): sysfs_write +: /sys/class/input/input6/enabled: 0
,V/WindowOrientationListener(  739): WindowOrientationListener disabled
D/PowerManagerService(  739): blankAllDisplays() is called.
D/PowerManagerService(  739): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService(  739): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  739): [PWL] sb release: PowerManagerService.Display
D/SensorService(  739): AutoRotationSensor::activate (ident=0x79441320, enabled=0)
D/MISC PowerHAL(  739): sysfs_write -: /sys/class/input/input6/enabled: 0
I/Sensors (  739): HAL: batch Dry Run is complete
D/MISC PowerHAL(  739): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  739): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  739): Got set_interactive hint
,D/KeyguardViewMediator( 1064): onScreenTurnedOff(3)
D/SurfaceFlinger(  246): Screen released, type=0 flinger=0xb8603980
,D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
,D/KeyguardViewMediator( 1064): notifyScreenOffLocked
,E/KeyguardViewMediator( 1064): resetStateLocked
D/KeyguardViewMediator( 1064): handleNotifyScreenOff
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 2ms+3ms, total 24ms
D/KeyguardViewManager( 1064): onScreenTurnedOff()
,D/PowerManagerService(  739): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/KeyguardHostView( 1064): screen off, instance 42c76c70 at 68590
D/LockPatternUtils( 1064): isPcwEnable = null
V/KeyguardHostView( 1064): showPrimarySecurityScreen(turningOff=true)
I/MDPP    ( 1064): Property: Empty
D/KeyguardHostView( 1064): showSecurityScreen(None)
D/SecCameraShortcut( 1064): onScreenTurnedOff
D/TimaKeyStoreProvider( 4723): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4723): Added TimaKesytore provider
I/Sensors (  739): HAL:resetDataRates mEnabled=4
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 2ms+2ms, total 20ms
,D/SensorManager( 1064): unregisterListener ::   
,I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1064): KeyguardEffectViewParticleSpace : screenTurnedOff
,D/VisualEffectParticleEffect( 1064): clearEffect
,D/PersonaManager( 1064): isKioskContainerExistOnDevice
D/KeyguardViewMediator( 1064): Kiosk container not exists on device or sim lock exists.
D/KeyguardViewMediator( 1064): handleReset
D/KeyguardViewManager( 1064): reset()
,D/KeyguardHostView( 1064): onSaveInstanceState, tstate=1
,D/KeyguardGuestSelectorView( 1064): onDetachedFromWindow()
,D/SensorManager(  739): unregisterListener ::   
V/KeyguardUpdateMonitor( 1064): *** unregister callback for com.android.keyguard.CarrierText$1@42f4f178
V/KeyguardUpdateMonitor( 1064): *** unregister callback for com.android.keyguard.MSimCarrierText$1@42f4f550
V/KeyguardUpdateMonitor( 1064): *** unregister callback for com.android.keyguard.CarrierText$1@42f3bdd8
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for com.android.keyguard.EmergencyButton$1@42f4bf80
,D/InputDispatcher(  739): setInputDispatchMode: enabled=0, frozen=0
,I/ProviderInstaller( 4682): Installed default security provider GmsCore_OpenSSL
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  739): Excessive delay in blankDisplay() while turning screen off: 245ms
,I/libsuspend(  739): !@[s] autosuspend_autosleep_enable
,I/libsuspend(  739): !@[s] autosuspend_autosleep_enable done
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/PowerManagerService(  739): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 247ms
D/PowerManagerService(  739): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService(  739): [PWL] Off : 0s ago
I/PowerManagerService(  739): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  739): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  739): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=739, ws=WorkSource{1000}) (elapsedTime=25553)
I/PowerManagerService(  739): [PWL]       PARTIAL_WAKE_LOCK              'GmsDownloadService' (uid=10011, pid=1756, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=672)
I/PowerManagerService(  739): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=739, ws=null) (elapsedTime=210)
I/PowerManagerService(  739): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/WindowManager(  739): Screenshot max retries 4 of Token{433db398 ActivityRecord{435bf3a8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{434d0a20 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42d22020
W/WindowManager(  739): Screenshot failure taking screenshot for (720x1280) to layer 21005
,D/Launcher.HomeView( 1249): onStop
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for com.android.keyguard.KeyguardHostView$2@42c780c0
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1444): [237392/5] Surface widget pause on instance = 1
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
,E/KeyguardHostView( 1064): KeyguardHostView()
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
,D/ContextualEventManager( 1064): setOnClickHandler()
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
,V/KeyguardHostView( 1064): mIsMultipleLockOn is false
,D/accuweather( 1444): [KK AccuPhone]>>> WR:149 [0:0] onPause
,D/accuweather( 1444): [KK AccuPhone]>>> SM:526 [0:0] onPause
I/SensorManagerA(  739): getReportingMode :: sensor.mType = 5
D/KeyguardHostView( 1064): mIsVoiceUnlockOn=false
D/LightsService(  739): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 739) 
,D/LightsService(  739): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
V/KeyguardHostView( 1064): Initial transport state: 1, pbstate=0
D/Sensors (  739): LightSensor setDelay = 200000000
D/Sensors (  739): LightSensor setSensorDelay = 200000000
D/Sensors (  739): Light sensor flush: not enabled 0
D/Sensors (  739): LightSensor enable = 1
D/Sensors (  739): LightSensor enableSensor = 1
,D/SensorManager(  739): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
,D/LockPatternUtils( 1064): isPcwEnable = null
D/BatteryService(  739): turn on LED for fully charged
D/VibratorService(  739): JNI vibratorOff()
I/ActivityManager(  739): Killing 2998:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,D/ContextualEventContainer( 1064): ContextualEventContainer()
,V/KeyguardUpdateMonitor( 1064): *** register callback for com.android.keyguard.KeyguardMessageArea$2@429a7840
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for null
D/ContextualEventContainer( 1064): onFinishInflate()
,D/ContextualEventContainer( 1064): update()
W/InputMethodManagerService(  739): Ignoring setImeWindowStatus of uid 1000 token: null
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/STATUSBAR-NotificationService(  739): ACTION_SCREEN_OFF
,D/LightsService(  739): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 739) 
,D/LightsService(  739): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/KeyguardHostView( 1064): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
D/LockPatternUtils( 1064): isPcwEnable = null
V/KeyguardHostView( 1064): showPrimarySecurityScreen(turningOff=false)
I/MDPP    ( 1064): Property: Empty
D/KeyguardHostView( 1064): showSecurityScreen(None)
V/KeyguardHostView( 1064): inflating id = 2130903095
D/SecuritySelectorView( 1064): explore by touch mode off
D/audio_hw_primary(  249): adev_set_parameters: enter: screen_state=off
V/voice   (  249): voice_set_parameters: enter: screen_state=off
V/voice   (  249): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  249): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  249): platform_set_parameters: exit with code(-2)
V/audio_hw_primary(  249): adev_set_parameters: exit
I/SecExternalDisplayIntents_Java(  739): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/IpRemoteDisplayController(  739): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  739): Bridge Server is not available
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1064): shortcutSetting:1
D/SecCameraShortcut( 1064): isKidsMode:false
D/SecCameraShortcut( 1064): isEmergencyMode:false
E/MTPRx   ( 4723): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 4723): check value of boot_completed is1
E/MTPRx   ( 4723): check booting is completed_sys.boot_completed
D/PersonaManagerService(  739): ACTION_SCREEN_OFF onReceive
E/MTPRx   ( 4723): Sd-Card path/storage/extSdCard
D/PersonaManagerServiceHandler(  739): MSG_ACTION_SCREEN_OFF called
E/MTPRx   ( 4723): Status for mount/Unmount :removed
E/MTPRx   ( 4723): SDcard is not available
W/MTPRx   ( 4723): value of connected istrue
W/MTPRx   ( 4723): value of configured istrue
W/MTPRx   ( 4723): value of mtpEnabled istrue
W/MTPRx   ( 4723): value of ptpEnabled isfalse
E/MTPRx   ( 4723): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 4723): mFirstTime: false
,D/        ( 4723): MTP: reading debug level property
E/MTPRx   ( 4723):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 4723): Getting CryptionKey from JAVA
,E/MTPRx   ( 4723): currentUserId is 0
,E/MTPRx   ( 4723): Start observing USB_STATE_MATCH 
E/MTPRx   ( 4723): usbMode is 0200
,E/MTPRx   ( 4723): is_secretmode is NOT 1
,W/MTPRx   ( 4723): Phone is lockedtrue
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/MTPRx   ( 4723):  inside checkKnoxStatus
,D/MTPRx   ( 4723):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 4723): sending MTP_ICON_ENABLED to stack
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/EmergencyButton( 1064): enabled = false, :0
,D/LockPatternUtils( 1064): isPcwEnable = null
,I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
,D/SecCameraShortcut( 1064): setCallback(): null
,D/KeyguardVoiceEngineThread( 1064): condition = 0
E/MTPRx   ( 4723): else part ... so first time!!!
,D/SecuritySelectorView( 1064): mIsAirViewEnabled =false
D/SecCameraShortcut( 1064): setCallback(): not null
,D/SecuritySelectorView( 1064): hideBouncer mBouncerHelpText != null
E/MTPPlaObsrvr( 4723): inside setContext()
,E/MTPPlaObsrvr( 4723):  inside createplafiles
D/SecCameraShortcut( 1064): setCallback(): not null
D/SecCameraShortcut( 1064): setCallback(): not null
,D/SecuritySelectorView( 1064): hideBouncer mBouncerHelpText != null
,D/KeyguardHostView( 1064): mKeyguardHelpOverlay : null
D/KeyguardHostView( 1064): AUTO_WIPE = false , IT Policy = false
D/ContextualEventManager( 1064): setOnClickHandler()
,E/LSO     ( 1064): LSO Service is not yet ready!!!
,V/KeyguardUpdateMonitor( 1064): *** register callback for com.android.keyguard.KeyguardHostView$2@42f38b98
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for null
,V/KeyguardHostView( 1064): music state changed: 0
,D/KeyguardProperties( 1064): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1064): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1064): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1064): screenHeight : 1280
,D/VisualEffectCircleUnlockEffect( 1064): ratio : 0.6666667
,D/VisualEffectCircleUnlockEffect( 1064): Constructor
D/VisualEffectCircleUnlockEffect( 1064): arrowImageId = 2130837796
D/VisualEffectCircleUnlockEffect( 1064): circleUnlockMaxWidth = 576
D/VisualEffectCircleUnlockEffect( 1064): circleUnlockMinWidth = 172
D/VisualEffectCircleUnlockEffect( 1064): outerStrokeWidth = 2
D/VisualEffectCircleUnlockEffect( 1064): innerStrokeWidth = 4
,D/VisualEffectCircleUnlockEffect( 1064): lockSequenceTotal = 30
V/KeyguardUpdateMonitor( 1064): *** register callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@4310b8e8
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for null
V/KeyguardUpdateMonitor( 1064): *** register callback for com.android.keyguard.MSimCarrierText$1@43162c48
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for null
D/MSimCarrierText( 1064):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 0
D/CarrierText( 1064): getCarrierTextForSimState: status = Normal
D/CarrierText( 1064): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1064): updateCarrierText: text = 
D/CarrierText( 1064): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1064): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1064): updateCarrierText: text = 
D/MSimCarrierText( 1064):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 1
,D/CarrierText( 1064): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1064): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1064): updateCarrierText: text = 
D/CarrierText( 1064): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1064): getCarrierTextForSimState: status = SimNotReady
D/MSimCarrierText( 1064): updateCarrierText: text = null
V/KeyguardUpdateMonitor( 1064): *** register callback for com.android.keyguard.EmergencyButton$1@43195998
,V/KeyguardUpdateMonitor( 1064): *** unregister callback for null
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/EmergencyButton( 1064): enabled = false, :0
D/SecCameraShortcut( 1064): setCallback(): not null
,D/SecuritySelectorView( 1064): hideBouncer mBouncerHelpText != null
,D/KeyguardViewManager( 1064): mWindowLayoutParams not null
,D/KeyguardHostView( 1064): onRestoreInstanceState, transport=1
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1064): KeyguardEffectViewParticleSpace : reset
,I/Choreographer( 1064): Skipped 30 frames!  The application may be doing too much work on its main thread.
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/ContextualEventContainer( 1064): handleUpdate()
D/ContextualEventManager( 1064): getTopEventView()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,D/ContextualEventManager( 1064): top view = flightmode
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/UsbManager( 1064):  :::: isUsb30Available :: return = false from pid = 1064
,D/STATUSBAR-PhoneStatusBar( 1064): makeExpandedInvisible
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardViewMediator( 1064): handleKeyguardDoneDrawing
D/PhoneStatusBarView( 1064): marqueeStatusBar:121, mClearCover:0
D/Sensors (  739): LightSensor enable = 0
,D/Sensors (  739): LightSensor enableSensor = 0
D/SensorManager(  739): unregisterListener ::   
,D/lights  (  739): led_pattern : 5 +
D/LightsService(  739): [SvcLED]  onSensorChanged::light value = 0
,D/SecContextualClockFlightMode( 1064): handleUpdateClock()
,D/KeyguardProperties( 1064): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/lights  (  739): led_pattern : 5 -
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/LightsService(  739): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SecKeyguardFlightModeView( 1064): received broadcast android.intent.action.SCREEN_OFF
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:440 [0:0] stopRefreshIcon : 1
,D/accuweather( 1444): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/QuickConnect[1.1][2] ( 3305): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 3305): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 3305): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 3305): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42ce4478
V/QuickConnect[1.1][2] ( 3305): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42ce4478
D/QuickConnect[1.1][2] ( 3305): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 3305): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 3305): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 3305): stopLeScan()
,D/QuickConnect[1.1][2] ( 3305): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService(  739): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRMv2:SIOP(  739): SIOP:: AP = 340, Delta = 10
,D/dalvikvm(  739): GC_EXPLICIT freed 2799K, 56% free 23618K/53156K, paused 9ms+14ms, total 198ms
E/MTPPlaObsrvr( 4723): playlist count is0
,E/MTPPlaObsrvr( 4723):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4723):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4723): Inside registerContentObserver
,E/MtpAdbObserver( 4723): inside setContext()
E/MtpAdbObserver( 4723): Inside registerContentObserver
,W/Settings( 4723): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 4723): onCreate.
,E/MtpService( 4723): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4723): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4723): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4723): onStartCommand.
,E/MtpService( 4723): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 4723): calling native method
,E/MTPJNIInterface( 4723): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 4723): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4723): noti = 10
,E/MtpService( 4723): onStartCommand.
,E/MtpService( 4723): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 4723): calling native method
E/MTPRx   ( 4723): Checking the driver time out
E/MTPJNIInterface( 4723): noti = 2
D/        ( 4723): deleting sockets before message queue initialization
,D/        ( 4723): event handler thread is created, so set the flag
E/MTPRx   ( 4723): called native method
E/MTPJNIInterface( 4723): setting Media scanner status0
E/MTPJNIInterface( 4723): After setting Media scanner status0
W/MTPRx   ( 4723): notification from stack 1
,E/MTPJNIInterface( 4723): Getting media scanner status0
,E/MTPJNIInterface( 4723): DeviceName is Galaxy S5-2
D/MediaScannerReceiver( 1204): action: android.intent.action.MTP_FILE_SCAN
,D/NtpTrustedTime(  739): currentTimeMillis() cache hit
V/NetworkStats(  739): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  739): currentTimeMillis() cache hit
D/NtpTrustedTime(  739): currentTimeMillis() cache hit
,D/NtpTrustedTime(  739): currentTimeMillis() cache hit
,V/NetworkStats(  739): performPollLocked() took 28ms
D/Headlines( 4102): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4102): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4102): Breath 10871 latestRequest time : 1454090190385 current time : 1454090201256
,D/Mms/MessagesLockscreen( 4321): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1064): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1064): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1064): updateContainer()
D/ContextualEventContainer( 1064): update()
D/ContextualEventContainer( 1064): handleUpdate()
D/ContextualEventManager( 1064): getTopEventView()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,W/ContextImpl( 3894): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ContextualEventManager( 1064): top view = flightmode
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,I/DBG_DIAGMONDM( 3945): [1.140541.0531][Line:24][onReceive] com.sec.intent.action.SYSSCOPESTATUS
D/UsbManager( 1064):  :::: isUsb30Available :: return = false from pid = 1064
,W/ContextImpl( 3894): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/SELinux ( 4752): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4752):  
,D/SecContextualClockFlightMode( 1064): handleUpdateClock()
,D/KeyguardProperties( 1064): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/MediaScannerService( 1204): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,I/SELinux ( 4752): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4752):  
I/SELinux ( 4752):  
,I/SELinux ( 4752): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4752): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4752): >>>>> Normal User
,E/dalvikvm( 4752): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 4752): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4752): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4752): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4752): Added TimaKesytore provider
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,I/iu.UploadsManager( 1756): End new media; added: 0, uploading: 0, time: 57 ms
,D/MediaProvider( 1204): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1204): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1204): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,V/MediaScanner( 1204): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1204): Skipping:
,D/MediaScanner( 1204): 7klwibgf7fvntblfd7(75ebcf7
,I/DBG_DM  ( 4752): [][Line:95][onCreate] 
,D/MediaScanner( 1204): Skipping:
D/MediaScanner( 1204): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
E/DBG_DM  ( 4752): BootingfileStream is null
,E/DBG_DM  ( 4752): xdmCreateBootingFilestream
,V/MediaScanner( 1204): processDirectory :  /storage/extSdCard
W/MediaScanner( 1204): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1204): 7klwibgf7fxlKdCbid7
,E/File    ( 1204): fail readDirectory() errno=2
,V/MediaScanner( 1204): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42d82f90
,V/MediaScanner( 1204): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42d82f90
V/MediaScanner( 1204):  prescan time: 24ms (DB items: 20)
V/MediaScanner( 1204):     scan time: 33ms (Caching mode: true), (makeEntry time: 23ms ~69%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1204): postscan time: 11ms (bulkDeleter : 0), (delete DeadThumbnail time : 7ms)
V/MediaScanner( 1204):    total time: 68ms
V/MediaScanner( 1204): checked files: 3  directories : 17  (I: 0, U: 0)
,I/DBG_DM  ( 4752): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,E/MTPJNIInterface( 4723): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DBG_DM  ( 4752): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 4752): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 4752): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
D/MediaScannerService( 1204): !@done scanning volume external
,I/MusicLeanback( 3894): Conditions not met for autocaching.
,I/MusicLeanback( 3894): Stop autocaching.
,I/DBG_DM  ( 4752): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 4752): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 4752): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 4752): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 4752): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 4752): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 4752): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 4752): [3.19.140541][Line:139][onReceive] com.sec.intent.action.SYSSCOPESTATUS
I/ActivityManager(  739): Killing 3878:com.sec.pcw.device/1000 (adj 15): empty #43
,D/PreloadUpdateManagerStateMachine( 4199): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 4199): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4199): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4199): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,I/IcingCorporaProvider( 2173): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/SELinux ( 4778): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4778):  
,D/hcjo    ( 4199): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4199): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4199): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4199): entry::IDLE
,I/SELinux ( 4778): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4778):  
I/SELinux ( 4778):  
,I/SELinux ( 4778): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4778): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4778): >>>>> Normal User
,E/dalvikvm( 4778): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 4778): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4778): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4778): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4778): Added TimaKesytore provider
,I/Icing   ( 1756): Storage manager: low false usage 1.69MB avail 11.18GB capacity 11.95GB
,D/FileShare-Server( 4778): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/dalvikvm( 1756): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
,W/dalvikvm( 1756): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0029
,I/SELinux ( 4793): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4793):  
I/ActivityManager(  739): Killing 3929:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,I/SELinux ( 4793): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4793):  
I/SELinux ( 4793):  
,I/SELinux ( 4793): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4793): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4793): >>>>> Normal User
,E/dalvikvm( 4793): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 4793): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4793): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4793): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4793): Added TimaKesytore provider
,I/FactoryTestApp( 3807): [IPCWriterToSecPhoneService$disConnectSecPhoneService]  
I/ActivityManager(  739): Killing 3855:com.vlingo.midas/u0a33 (adj 15): empty #43
,D/BezelQuickConnect( 3318): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 3318): BezelBroadcastReceiver - packageName : com.google.android.gms
,I/dalvikvm( 3671): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 3671): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3671): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager(  739): Killing 4012:com.policydm/1000 (adj 15): empty #43
,D/PackageBroadcastService( 1756): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/FaceInterface( 2344): startFaceScan() : going on
,D/FaceInterface( 2344): startFaceScan() is called.
,I/SELinux ( 4808): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4808):  
,D/ContentApp( 1204): startScan() is called.
,I/PackageBroadcastService( 1756): Null package name or gms related package.  Ignoreing.
,D/FaceValue( 1204): mSleepTime: 800
,D/FaceValue( 1204): mMaxThreadNum: 2
,W/FaceValue( 1204): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1204): startScan() is end.
,D/ContentApp( 1204): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1204): isNeedToRestore : start
I/SELinux ( 4808): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4808):  
I/SELinux ( 4808):  
,I/SELinux ( 4808): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4808): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4808): >>>>> Normal User
,E/dalvikvm( 4808): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
,D/dalvikvm( 1204): GC_EXPLICIT freed 502K, 47% free 10050K/18904K, paused 9ms+6ms, total 52ms
,E/SELinux ( 4808): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4808): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4808): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4808): Added TimaKesytore provider
,E/MTPJNIInterface( 4723): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4723): SDcard is not available
,E/MTPJNIInterface( 4723): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4723): SDcard is not available
E/SQLiteLog( 4723): (21) API call with NULL database connection pointer
E/SQLiteLog( 4723): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 4723): (21) API call with NULL database connection pointer
E/SQLiteLog( 4723): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 4723): (21) API call with NULL database connection pointer
E/SQLiteLog( 4723): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 4723): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4723): (21) misuse at line 96833 of [00bb9c9ce4]
,D/        ( 4723): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4723): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 4723): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
W/MTPRx   ( 4723): notification from stack 2
,D/        ( 4723): *****Starting mtp_io()
W/MTPRx   ( 4723): notification from stack 3
,D/        ( 4723): [mtp_start_io] source_thread Creation 
D/        ( 4723): [mtp_start_io] sink_thread Creation 
,D/        ( 4723): [mtp_start_io:360] sink thread created so set th_sink
,E/SamsungIME( 4808): InputManagerImpl.getInstance() == null
,I/SELinux ( 4832): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4832):  
I/ActivityManager(  739): Killing 4073:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #43
,I/dalvikvm( 1756): Total arena pages for JIT: 11
,I/dalvikvm( 1756): Total arena pages for JIT: 12
I/dalvikvm( 1756): Total arena pages for JIT: 13
,I/dalvikvm( 1756): Total arena pages for JIT: 14
,I/SELinux ( 4832): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4832):  
I/SELinux ( 4832):  
,I/SELinux ( 4832): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4832): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4832): >>>>> Normal User
,E/dalvikvm( 4832): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 4832): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4832): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4832): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4832): Added TimaKesytore provider
,I/Icing   ( 1756): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4832, uid=10014 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4847): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4847):  
,I/ActivityManager(  739): Killing 4089:com.android.chrome/u0a81 (adj 15): empty #43
,I/SELinux ( 4847): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4847):  
I/SELinux ( 4847):  
,I/SELinux ( 4847): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4847): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4847): >>>>> Normal User
,E/dalvikvm( 4847): >>>>> com.samsung.groupcast [ userId:0 | appId:10015 ]
,E/SELinux ( 4847): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm( 1756): GC_CONCURRENT freed 1748K, 38% free 11838K/18904K, paused 5ms+5ms, total 41ms
,D/TimaKeyStoreProvider( 4847): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4847): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4847): Added TimaKesytore provider
,D/GroupCast_FileTools( 4847): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 4847): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.mv.player
W/System.err( 4847): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
,W/System.err( 4847): 	at com.samsung.groupcast.application.App.preLoadShareVideoCheck(App.java:325)
W/System.err( 4847): 	at com.samsung.groupcast.application.App.onCreate(App.java:145)
W/System.err( 4847): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
,W/System.err( 4847): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4847): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 4847): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4847): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4847): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 4847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 4847): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 4847): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 4847): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
,W/System.err( 4847): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 4847): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 4847): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 4847): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
,W/System.err( 4847): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4847): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 4847): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4847): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4847): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 4847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 4847): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 4859): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4859):  
I/ActivityManager(  739): Killing 4122:com.google.android.apps.magazines/u0a112 (adj 15): empty #43
,I/SELinux ( 4859): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4859):  
I/SELinux ( 4859):  
,I/SELinux ( 4859): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4859): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 4859): >>>>> Normal User
,E/dalvikvm( 4859): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,E/SELinux ( 4859): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4859): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4859): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4859): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4859, uid=10024 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4873): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4873):  
,I/SELinux ( 4873): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4873):  
I/SELinux ( 4873):  
D/dalvikvm(  739): GC_EXPLICIT freed 899K, 56% free 23541K/53156K, paused 7ms+13ms, total 139ms
,I/SELinux ( 4873): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4873): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4873): >>>>> Normal User
,E/dalvikvm( 4873): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 4873): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  739): Killing 4126:com.samsung.android.magazine.service/u0a106 (adj 15): empty #43
,I/dalvikvm( 4873): Enabling JNI app bug workarounds for target SDK version 8...
,E/SMD     (  240): DCD ON
,D/TimaKeyStoreProvider( 4873): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4873): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4873): Added TimaKesytore provider
,I/Icing   ( 1756): Internal init done: storage state 0
,I/Icing   ( 1756): Post-init done
,I/Icing   ( 1756): updateResources: need to parse f{com.google.android.gms}
,I/PCWCLIENTTRACE_PushUtil( 4873): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4873): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4873): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 4873): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 4873): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4873): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/SELinux ( 4885): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4885):  
I/ActivityManager(  739): Killing 3430:com.android.email/u0a155 (adj 15): empty #43
,I/SELinux ( 4885): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4885):  
I/SELinux ( 4885):  
,I/SELinux ( 4885): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4885): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4885): >>>>> Normal User
,E/dalvikvm( 4885): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10034 ]
,E/SELinux ( 4885): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4885): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4885): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4885): Added TimaKesytore provider
,D/AmoledAdjustTimer(  739): prevTemp = 284, currTemp = 287, prevStep = 4, currStep = 4
,W/System.err( 4885): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 4885): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 4885): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 4885): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 4885): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
,W/System.err( 4885): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 4885): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 4885): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
,W/System.err( 4885): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 4885): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 4885): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 4885): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,W/System.err( 4885): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 4885): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 4885): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 4885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4885): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 4885): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 4885): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 4885): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 4885): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 4885): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 4885): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 4885): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4885): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 4885): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 4885): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 4885): 	... 21 more
,D/GalaxyFinderApplication( 4885): [Slink platform] Version = 29011
,D/GalaxyFinderApplication( 4885): [Slink platform] use state of slink location service is [false] to [true]
,I/SELinux ( 4901): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4901):  
I/ActivityManager(  739): Killing 3584:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,D/dalvikvm( 2173): GC_CONCURRENT freed 6151K, 39% free 11532K/18904K, paused 4ms+22ms, total 59ms
,I/IcingCorporaProvider( 2173): UpdateCorporaTask done [took 1640 ms] updated apps [took 1640 ms] 
I/SELinux ( 4901): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4901):  
I/SELinux ( 4901):  
,I/SELinux ( 4901): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4901): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4901): >>>>> Normal User
,E/dalvikvm( 4901): >>>>> com.policydm [ userId:0 | appId:1000 ]
,E/SELinux ( 4901): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4901): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4901): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4901): Added TimaKesytore provider
,I/SELinux ( 4918): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4918):  
I/ActivityManager(  739): Killing 3961:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,D/dalvikvm(  247): GC_EXPLICIT freed 47K, 50% free 9506K/18904K, paused 3ms+3ms, total 26ms
,D/FactoryTestApp( 3807): [DummyFtClient$onDestroy] Destroy DummyFtClient service
,D/FactoryTestApp( 3807): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3807): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 3807): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
,D/FactoryTestApp( 3807): [DummyFtClient$onDestroy] kill process
I/Process ( 3807): Sending signal. PID: 3807 SIG: 9
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 2ms+3ms, total 18ms
I/SELinux ( 4918): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4918):  
I/SELinux ( 4918):  
,I/SELinux ( 4918): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4918): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4918): >>>>> Normal User
,E/dalvikvm( 4918): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
,E/SELinux ( 4918): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 1ms+3ms, total 18ms
I/FaceInterface( 2344): startFaceScan() : going on
,D/FaceInterface( 2344): startFaceScan() is called.
,D/ContentApp( 1204): startScan() is called.
D/ContentApp( 1204): startScan() is end.
D/ContentApp( 1204): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1204): isNeedToRestore : start
,I/ActivityManager(  739): Process com.sec.factory (pid 3807) (adj 0) has died.
D/TimaKeyStoreProvider( 4918): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4918): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4918): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4918, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4918): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4918): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  739): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,I/SA      ( 4047): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4047): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4047): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
,D/Mms/PackageInstallReceiver( 4321): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2173): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ContextImpl( 4663): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4944): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4944):  
,I/ActivityManager(  739): Killing 3973:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/SELinux ( 4944): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4944):  
I/SELinux ( 4944):  
,I/SELinux ( 4944): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4944): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4944): >>>>> Normal User
,E/dalvikvm( 4944): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4944): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4944): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4944): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4944): Added TimaKesytore provider
,I/IcingCorporaProvider( 2173): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
,D/CapabilityManagerService New( 4944): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,I/Icing   ( 1756): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4944, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4957): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4957):  
I/ActivityManager(  739): Killing 4257:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 4957): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4957):  
I/SELinux ( 4957):  
,I/SELinux ( 4957): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4957): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4957): >>>>> Normal User
,E/dalvikvm( 4957): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 4957): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4957): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4957): Cannot add TimaSignature Service, License check Failed
,D/Icing   ( 1756): Loaded CLD2 Version V2.0 - 20141016
,D/ActivityThread( 4957): Added TimaKesytore provider
,I/Icing   ( 1756): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/CheckinService( 1756): Done disabling old GoogleServicesFramework version
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=4957, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,W/ProcessCpuTracker(  739): Skipping unknown process pid 4739
,W/ProcessCpuTracker(  739): Skipping unknown process pid 4740
,W/ProcessCpuTracker(  739): Skipping unknown process pid 4742
,W/ProcessCpuTracker(  739): Skipping unknown process pid 4770
,W/ProcessCpuTracker(  739): Skipping unknown process pid 4969
,I/SELinux ( 4982): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4982):  
,I/ActivityManager(  739): Killing 3993:com.sec.android.soagent/u0a37 (adj 15): empty #43
,I/SELinux ( 4982): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4982):  
I/SELinux ( 4982):  
,I/SELinux ( 4982): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4982): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4982): >>>>> Normal User
,E/dalvikvm( 4982): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4982): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4982): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4982): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4982): Added TimaKesytore provider
,W/GAV2    ( 4957): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/PackageIntentReceiver( 4982): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4982): Not GearManger package! 
,I/SELinux ( 5008): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5008):  
,I/SELinux ( 5008): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5008):  
I/SELinux ( 5008):  
,I/SELinux ( 5008): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5008): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5008): >>>>> Normal User
,E/dalvikvm( 5008): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 5008): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5008): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5008): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5008): Added TimaKesytore provider
,D/MagazineService Version( 5008): Magazine-Channel: 13
,D/MagazineService Version( 5008): Magazine-Provider: 13
,D/MagazineService Version( 5008): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 5008): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5008): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=5008, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5008): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 5021): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5021):  
,D/MagazineService::MagazineService( 5008): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  739): Killing 4360:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,I/GAV4    ( 4682): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 5021): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5021):  
I/SELinux ( 5021):  
,I/SELinux ( 5021): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5021): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5021): >>>>> Normal User
,E/dalvikvm( 5021): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5021): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/GAV2    ( 4957): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/TimaKeyStoreProvider( 5021): in addTimaSignatureService
I/ActivityManager(  739): Killing 4375:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5021): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5021): Added TimaKesytore provider
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{445d7780 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/SELinux ( 5037): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5037):  
I/ActivityManager(  739): Killing 4388:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5037): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5037):  
I/SELinux ( 5037):  
,I/SELinux ( 5037): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5037): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5037): >>>>> Normal User
,E/dalvikvm( 5037): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5037): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5037): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5037): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5037): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=5037, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5037): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5049): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5049):  
I/ActivityManager(  739): Killing 3572:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 5049): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5049):  
I/SELinux ( 5049):  
,I/SELinux ( 5049): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5049): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5049): >>>>> Normal User
,E/dalvikvm( 5049): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5049): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5049): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5049): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5049): Added TimaKesytore provider
,I/ActivityManager(  739): Killing 4416:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Finsky  ( 3671): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1756): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Loading module APK com.google.android.play.games
,I/dalvikvm( 1756): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1756): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1756): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1756): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1756): VFY: replacing opcode 0x22 at 0x001a
,I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1756): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 1756): GC_CONCURRENT freed 1989K, 38% free 11820K/18904K, paused 3ms+4ms, total 35ms
,W/SQLiteConnectionPool( 1756): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1756): Submit a task: k
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,D/k       ( 1756): Processing package: com.test.thalitest
,D/GassUtils( 1756): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1756): Found info for package com.test.thalitest in db.
,I/SettingSearch/SearchIntentReceiver( 1315): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1315): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1315): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1315): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1315): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/PowerManagerService(  739): [PWL] Off : 5s ago
,I/PowerManagerService(  739): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  739): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  739): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=1756, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=75)
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,E/SMD     (  240): DCD ON
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,I/SettingSearch/SettingsSearchManager( 1315): Infomation -> numtitleinfo : 0 numSearchinfo : 312
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1756): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1756): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
,W/dalvikvm( 1756): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1756): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
,W/dalvikvm( 1756): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1756): cleanUpNonGplusAccounts done.
,E/CscFactoryReceiver( 1237): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1237): Media DB Scanner finished.
,D/CscFactoryReceiver( 1237): start service to Set Ringtone
,D/CscFactoryReceiver( 1237): start service to Set Notification
,D/CscFactoryReceiver( 1237): start service to Set Alarmtone
,I/SettingSearch/SettingsSearchManager( 1315):  Infomation -> getItem size : 312
D/CscUpdateService( 1237): onStart
E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1237): only ringtone update
D/CscUpdateService( 1237): onStart
E/CscParser( 1237): update(): xml file exist
E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1237): only notification update
D/CscUpdateService( 1237): onStart
E/CscUpdateService( 1237): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1237): only alarmtone update
,E/CscParser( 1237): update(): xml file exist
,W/CSCSettings( 1237): Setting Ringtones (type) : 1
,I/SELinux ( 5090): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5090):  
D/CscParser( 1237): RingTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,W/CSCSettings( 1237): Setting Ringtones (type) : 2
,D/CscParser( 1237): MessageTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,E/CscParser( 1237): update(): xml file exist
,W/CSCSettings( 1237): Setting Ringtones (type) : 4
D/CscParser( 1237): AlarmTone: null
,W/CSCSettings( 1237): 1. Tag_Str: null
,I/SELinux ( 5090): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5090):  
I/SELinux ( 5090):  
,I/SELinux ( 5090): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5090): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5090): >>>>> Normal User
,E/dalvikvm( 5090): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
,E/SELinux ( 5090): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5090): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5090): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5090): Added TimaKesytore provider
,I/IndexBroadcastProcessorService( 5090): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,I/SELinux ( 5103): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5103):  
,I/IndexBroadcastProcessorService( 5090): lucene systemReadyToIndex
,I/IndexService( 5090): lucene onCreate ...service
,I/SELinux ( 5103): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5103):  
I/SELinux ( 5103):  
,I/SELinux ( 5103): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5103): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5103): >>>>> Normal User
,E/dalvikvm( 5103): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 5103): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5103): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5103): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5103): Added TimaKesytore provider
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5090): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5090): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/FactoryTestApp( 5103): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
I/dalvikvm( 5090): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 5090): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 5090): VFY: replacing opcode 0x71 at 0x01ed
,W/ActivityThread( 5103): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 5103): [XMLDataStorage$parseXML] is Live Demo : false
D/FactoryTestApp( 5103): [XMLDataStorage$parseXML] modelXML=sm-g800h.dat
D/FactoryTestApp( 5103): [XMLDataStorage$parseXML] deviceXML=kmini3g.dat
D/FactoryTestApp( 5103): [XMLDataStorage$parseXML] nameXML=kmini3gxx.dat
,I/FactoryTestApp( 5103): [XMLDataStorage$parseAsset] Convert dat file: sm-g800h.dat
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/FactoryTestApp( 5103): [XMLDataStorage$parseAsset] Decode base file: factory.dat
,D/dalvikvm(  739): GC_EXPLICIT freed 1770K, 56% free 23645K/53156K, paused 10ms+15ms, total 160ms
,I/IndexService( 5090): lucene beginIndexing
,E/File    ( 5090): fail readDirectory() errno=13
,I/IndexService( 5090): lucene onDestroy start
,I/IndexService( 5090): lucene onDestroy end
,I/IndexService( 5090): lucene cleanupEverything start
,I/IndexService( 5090): lucene cleanupEverything end
,I/Process ( 5090): Sending signal. PID: 5090 SIG: 9
,I/ActivityManager(  739): Process com.samsung.indexservice (pid 5090) (adj 9) has died.
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,I/Icing   ( 1756): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=MIC_COUNT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FONT_SIZE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
,D/dalvikvm( 1756): GC_CONCURRENT freed 1146K, 34% free 12642K/18904K, paused 10ms+9ms, total 65ms
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
,I/Icing   ( 1756): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_RECENT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
,D/dalvikvm( 4642): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
,D/dalvikvm( 4642): GC_EXPLICIT freed 3866K, 47% free 10126K/18904K, paused 2ms+5ms, total 37ms
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_USER
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_POWER
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
,D/dalvikvm( 1315): GC_EXPLICIT freed 459K, 46% free 10295K/18904K, paused 3ms+4ms, total 37ms
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
,D/dalvikvm( 5103): GC_CONCURRENT freed 7280K, 46% free 10354K/18904K, paused 1ms+1ms, total 29ms
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_ATMEL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_ATMEL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_ATMEL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_ATMEL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_ATMEL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_ATMEL
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
,D/dalvikvm( 5103): GC_CONCURRENT freed 1990K, 46% free 10352K/18904K, paused 1ms+2ms, total 30ms
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=BATTERY_TEMP_ADC
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 5103): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
,D/FactoryTestApp( 5103): [XMLDataStorage$parseAsset] SemiFunctionMenu
,D/dalvikvm( 4642): GC_EXPLICIT freed 1000K, 48% free 10016K/18904K, paused 2ms+5ms, total 24ms
,D/FactoryTestApp( 5103): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 5103): [Support$Properties.get] property=ro.factory.factory_binary
D/FactoryTestApp( 5103): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 5103): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
,D/FactoryTestApp( 5103): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
I/FactoryTestApp( 5103): [ModuleCommon$ModuleCommon] Create ModuleCommon
I/FactoryTestApp( 5103): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 5103): [ModuleCommon$getMediaScanningCount] get : 2
D/FactoryTest( 5103): User mode
,I/FactoryTestApp( 5103): [ModuleCommon$getMediaScanningCount] get : 3
I/FactoryTestApp( 5103): [ModuleCommon$getMediaScanningCount] get : 3
I/FactoryTestApp( 5103): [ModuleCommon$getMediaScanningCount] get : 3
I/FactoryTestApp( 5103): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
,D/FactoryTestApp( 5103): [FactoryTestBroadcastReceiver$killProcessSelf] kill process
,I/Process ( 5103): Sending signal. PID: 5103 SIG: 9
,I/ActivityManager(  739): Process com.sec.factory (pid 5103) (adj 0) has died.
,D/GalleryCacheReady( 2344): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 2344): handleMeidaScanFinish()
,D/FaceInterface( 2344): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 2344): query fail: 
,I/FaceInterface( 2344): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 2344): query fail: 
,I/MediaStoreImporter( 3894): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/dalvikvm( 1315): GC_EXPLICIT freed 355K, 46% free 10287K/18904K, paused 3ms+4ms, total 25ms
,E/SMD     (  240): DCD ON
,D/dalvikvm( 4642): GC_EXPLICIT freed 899K, 48% free 10012K/18904K, paused 1ms+5ms, total 23ms
,D/dalvikvm( 1315): GC_EXPLICIT freed 361K, 46% free 10285K/18904K, paused 2ms+4ms, total 25ms
,I/HarmonyEASService(  739): Updating for all 1
,I/GAV2    ( 4957): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm(  739): GC_EXPLICIT freed 590K, 56% free 23550K/53156K, paused 6ms+14ms, total 125ms
,V/AlarmManager(  739): waitForAlarm result :8
,D/dalvikvm( 4642): GC_EXPLICIT freed 904K, 47% free 10020K/18904K, paused 1ms+5ms, total 23ms
,D/dalvikvm( 1315): GC_EXPLICIT freed 355K, 46% free 10294K/18904K, paused 2ms+4ms, total 26ms
,D/dalvikvm( 4642): GC_EXPLICIT freed 902K, 48% free 10016K/18904K, paused 2ms+5ms, total 27ms
,D/dalvikvm( 1315): GC_EXPLICIT freed 357K, 46% free 10297K/18904K, paused 2ms+4ms, total 25ms
,E/Watchdog(  739): !@Sync 2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 330, Delta = -10
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  739): stay LED for fully charged
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/iu.UploadsManager( 1756): End new media; added: 0, uploading: 0, time: 109 ms
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 4642): GC_EXPLICIT freed 881K, 48% free 10010K/18904K, paused 1ms+5ms, total 23ms
,E/SMD     (  240): DCD ON
,D/dalvikvm( 1315): GC_EXPLICIT freed 345K, 46% free 10305K/18904K, paused 2ms+5ms, total 25ms
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{44ff61e0 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/dalvikvm(  739): GC_EXPLICIT freed 416K, 56% free 23545K/53156K, paused 6ms+12ms, total 137ms
,D/dalvikvm( 4642): GC_EXPLICIT freed 875K, 48% free 10012K/18904K, paused 2ms+7ms, total 31ms
,I/FaceInterface( 2344): startFaceScan() : going on
,D/FaceInterface( 2344): startFaceScan() is called.
,D/ContentApp( 1204): startScan() is called.
,D/ContentApp( 1204): startScan() is end.
,D/ContentApp( 1204): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1204): isNeedToRestore : start
,D/dalvikvm( 1315): GC_EXPLICIT freed 351K, 46% free 10311K/18904K, paused 3ms+6ms, total 33ms
D/AmoledAdjustTimer(  739): prevTemp = 287, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager(  739): waitForAlarm result :4
,D/Finsky  ( 3671): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 3671): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3671): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3671): VFY: replacing opcode 0x62 at 0x0038
V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1292): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 1292): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1292): VFY: replacing opcode 0x6e at 0x0046
,I/System.out( 3671): Thread-349(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3671): Thread-349(ApacheHTTPLog):isShipBuild true
,I/System.out( 3671): Thread-349(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 3671): Thread-349 calls detatch()
,D/dalvikvm( 4642): GC_EXPLICIT freed 872K, 48% free 10010K/18904K, paused 3ms+8ms, total 39ms
,D/Finsky  ( 3671): [1] DfeNotificationManagerImpl.handleNotification: Handling notification type=[6], id=[EAMaEjQ2YWU3OGZiZWQzZGRkNzI6MyCx9rzzqCooBg]
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 3671): Total arena pages for JIT: 11
,I/dalvikvm( 3671): Total arena pages for JIT: 12
I/dalvikvm( 3671): Total arena pages for JIT: 13
,I/dalvikvm( 3671): Total arena pages for JIT: 14
,I/qtaguid ( 3671): Failed write_ctrl(u 73) res=-1 errno=22
I/qtaguid ( 3671): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3671): untagSocket(73) failed with errno -22
,I/System.out( 3671): Thread-348 calls detatch()
,D/Finsky  ( 3671): [1] DfeNotificationManagerImpl$3.onResponse: Notification [EAMaEjQ2YWU3OGZiZWQzZGRkNzI6MyCx9rzzqCooBg] successfully ack'd.
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3671): Failed write_ctrl(u 73) res=-1 errno=22
I/qtaguid ( 3671): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3671): untagSocket(73) failed with errno -22
,I/System.out( 3671): Thread-348 calls detatch()
,D/Finsky  ( 3671): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/dalvikvm( 1315): GC_EXPLICIT freed 337K, 46% free 10318K/18904K, paused 3ms+6ms, total 32ms
,I/System.out( 3671): Thread-349 calls detatch()
,E/SMD     (  240): DCD ON
,D/dalvikvm( 3671): GC_CONCURRENT freed 5871K, 38% free 11815K/18904K, paused 3ms+6ms, total 48ms
,D/dalvikvm( 3671): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/IcingInternalCorpora( 1756): getNumBytesRead when not calculated.
,D/dalvikvm(  739): GC_EXPLICIT freed 426K, 56% free 23571K/53156K, paused 8ms+15ms, total 165ms
,D/dalvikvm( 3671): GC_CONCURRENT freed 828K, 32% free 12916K/18904K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 3671): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 3671): GC_FOR_ALLOC freed 1887K, 32% free 12885K/18904K, paused 26ms, total 28ms
,D/dalvikvm( 3671): GC_CONCURRENT freed 1591K, 23% free 14681K/18904K, paused 2ms+6ms, total 52ms
,D/dalvikvm( 3671): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 4642): GC_EXPLICIT freed 870K, 48% free 10011K/18904K, paused 3ms+7ms, total 32ms
,I/PowerManagerService(  739): [PWL] Off : 15s ago
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{43906c48 u0 com.samsung.android.MtpApplication/.MtpService}
,D/dalvikvm( 1315): GC_EXPLICIT freed 346K, 46% free 10325K/18904K, paused 3ms+6ms, total 32ms
,D/Finsky  ( 3671): [1] ContentSyncService$3.onMutationsApplied$12348bc5: App library has changed, requesting content sync.
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 4642): GC_EXPLICIT freed 878K, 48% free 10008K/18904K, paused 3ms+6ms, total 31ms
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3671): Failed write_ctrl(u 78) res=-1 errno=22
,I/qtaguid ( 3671): Untagging socket 78 failed errno=-22
W/NetworkManagementSocketTagger( 3671): untagSocket(78) failed with errno -22
,I/System.out( 3671): Thread-348 calls detatch()
,D/dalvikvm( 4642): GC_CONCURRENT freed 1492K, 45% free 10478K/18904K, paused 2ms+11ms, total 41ms
,E/SMD     (  240): DCD ON
,D/dalvikvm( 1292): GC_EXPLICIT freed 954K, 43% free 10797K/18904K, paused 4ms+6ms, total 44ms
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SettingSearch/SearchIntentReceiver( 1315): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1315): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 1315): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1315): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1315): LOCALE_CHANGED call search setting db finish!!
,I/qtaguid ( 3671): Failed write_ctrl(u 78) res=-1 errno=22
I/qtaguid ( 3671): Untagging socket 78 failed errno=-22
W/NetworkManagementSocketTagger( 3671): untagSocket(78) failed with errno -22
,I/System.out( 3671): Thread-349 calls detatch()
,D/Finsky  ( 3671): [1] LibraryUtils.isAvailable: com.sec.android.fwupgrade available because owned, overriding [restriction=7].
,D/Finsky  ( 3671): [1] LibraryUtils.isAvailable: com.noknok.android.framework.service available because owned, overriding [restriction=7].
,D/Finsky  ( 3671): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 1210): callingUid 10011, callindPid: 1210
,D/Finsky  ( 3671): [371] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1210): client connected with version: 8296000
,D/Finsky  ( 3671): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3671): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1292): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3671): Thread-359(HTTPLog):isShipBuild true
,I/System.out( 3671): Thread-359(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  739): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  739): <AppSync3 Whitelist>
,V/AlarmManager(  739): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 310, Delta = -20
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/AmoledAdjustTimer(  739): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 30s ago
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4102): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  739): stay LED for fully charged
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
D/Headlines( 4102): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4102): Breath 40891 latestRequest time : 1454090190385 current time : 1454090231276
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = -10
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SMD     (  240): DCD ON
,D/Finsky  ( 3671): [361] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3671): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/AmoledAdjustTimer(  739): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 3
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 289, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 50s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4102): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4102): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/Headlines( 4102): Breath 70006 latestRequest time : 1454090190385 current time : 1454090260398
,I/VacuumService( 1210): Vacuum at: now=1454090260873 tag=VacuumService
,D/dalvikvm(  739): GC_EXPLICIT freed 1857K, 56% free 23714K/53156K, paused 8ms+16ms, total 186ms
,D/FactoryTest( 4723): Not factory mode
,D/FactoryTest( 4723): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4723): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4723): still no open session command from host, so toast
W/ContextImpl( 4723): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4723): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  739): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  739): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  739): mDVFSHelper.acquire()
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/LockPatternUtils( 1064): isPcwEnable = null
,E/MTPRx   ( 4723): started activity for popup
,I/SQLiteSecureOpenHelper( 2099): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2099): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4723): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/SettingsReceiverActivity( 4723): dev.kiessupport is : TRUE
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,I/WindowManager(  739): Screenshot max retries 4 of Token{433db398 ActivityRecord{435bf3a8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{434d0a20 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,D/LockPatternUtils( 1064): isPcwEnable = null
W/WindowManager(  739): Screenshot failure taking screenshot for (720x1280) to layer 21005
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,I/PhenotypeConfigurator( 1210): Scheduling Phenotype for one-off execution 3948 seconds from now (1454090261847)
,D/GetConfigurationSnapshotOperation( 1210): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1210): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1210): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1210): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1210): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  739): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1210): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1210): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1210): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1210): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1210): GC_CONCURRENT freed 1588K, 38% free 11860K/18904K, paused 3ms+5ms, total 43ms
,D/LocationManagerService(  739): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  739): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 287, currTemp = 284, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  739): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  739): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  739): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  739): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  739): !@Sync 4
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 75s ago
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  739): waitForAlarm result :8
,D/Headlines( 4102): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4102): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4102): Breath 90041 latestRequest time : 1454090190385 current time : 1454090280426
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  739): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  739): !@Sync 5
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 105s ago
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,D/Headlines( 4102): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4102): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4102): Breath 120038 latestRequest time : 1454090190385 current time : 1454090310423
,D/Headlines( 4102): stop 
,D/Headlines( 4102): Breath.onDestroy : 
,I/ActivityManager(  739): Killing 4430:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,E/SMD     (  240): DCD ON
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  739): !@Sync 6
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/ClearcutLoggerApiImpl( 1292): disconnect managed GoogleApiClient
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  739): [PWL] Off : 140s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 7
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 180s ago
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 8
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 9
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 225s ago
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  739): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  739): TimaServiceHandler.handleMessage what =1
,D/TimaService(  739): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  739): initializing...
,I/TLC_TIMA_PKM_initialize(  739): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  739): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  739): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  739): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  739): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  739): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  739): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  739): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  739): App is not loaded in QSEE
,D/QSEECOMAPI: (  739): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  739): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  739): Trustlet response is completed
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  739): !@Sync 10
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  739): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  739): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  739): waitForAlarm result :4
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5313):  
D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 5313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5313):  
I/SELinux ( 5313):  
,I/SELinux ( 5313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5313): >>>>> Normal User
,E/dalvikvm( 5313): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5313): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5313): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=5313, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  739): Killing 4455:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/PowerManagerService(  739): [PWL] Off : 275s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 11
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 12
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 13
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 14
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 390s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  739): stay LED for fully charged
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 15
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 16
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  739): GC_CONCURRENT freed 3383K, 56% free 23780K/53156K, paused 29ms+37ms, total 414ms
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  739): [PWL] Off : 455s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 17
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  739): stay LED for fully charged
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 18
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 19
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 525s ago
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  739): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  739): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  739): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 20
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 21
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 600s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 22
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  739): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  739): <AppSync3 Whitelist>
,V/AlarmManager(  739): (AppSync) ### 0 added ###
,V/AlarmManager(  739): waitForAlarm result :8
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 23
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  739): !@Sync 24
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  739): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  739): !@Sync 25
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  739): !@Sync 26
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): stay LED for fully charged
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  739): !@Sync 27
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,I/PowerManagerService(  739): [PWL] Off : 765s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,E/Watchdog(  739): !@Sync 28
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 29
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/TimaService(  739): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  739): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  739): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 30
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 855s ago
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 31
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :4
,I/SensorManagerA(  739): getReportingMode :: sensor.mType = 5
,D/LightsService(  739): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  739): LightSensor setDelay = 200000000
D/Sensors (  739): LightSensor setSensorDelay = 200000000
D/Sensors (  739): Light sensor flush: not enabled 0
D/Sensors (  739): LightSensor enable = 1
D/Sensors (  739): LightSensor enableSensor = 1
,D/SensorManager(  739): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/Sensors (  739): LightSensor enable = 0
,D/Sensors (  739): LightSensor enableSensor = 0
,D/SensorManager(  739): unregisterListener ::   
D/LightsService(  739): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  739): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  240): DCD ON
,D/ConnectivityService(  739): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/dalvikvm(  739): GC_CONCURRENT freed 3482K, 56% free 23776K/53156K, paused 24ms+35ms, total 409ms
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 32
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 33
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 950s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 34
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 35
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 268, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 36
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 1050s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 37
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 38
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 39
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/TimaService(  739): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  739): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  739): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  739): stay LED for fully charged
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  739): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  739): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 40
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  739): [PWL] Off : 1155s ago
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  739): waitForAlarm result :8
,V/AlarmManager(  739): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/Watchdog(  739): !@Sync 41
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  739): stay LED for fully charged
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  739): mCoverManager.getCoverState() : true
,D/BatteryService(  739): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1943): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  240): DCD ON
D/BatteryService(  739): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
D/BatteryService(  739): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  739): stay LED for fully charged
D/UiModeManager(  739): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/SSRMv2:SIOP(  739): SIOP:: AP = 300, Delta = 0
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AmoledAdjustTimer(  739): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
V/HeadsetService( 1943): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1943): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  240): DCD ON
E/Watchdog(  739): !@Sync 42
D/AndroidRuntime( 5523): 
D/AndroidRuntime( 5523): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5523): CheckJNI is OFF
D/AndroidRuntime( 5523): setted country_code = Poland
D/AndroidRuntime( 5523): setted countryiso_code = PL
D/AndroidRuntime( 5523): setted sales_code = XEO
D/AndroidRuntime( 5523): readGMSProperty: start
D/AndroidRuntime( 5523): readGMSProperty: already setted!!
D/AndroidRuntime( 5523): readGMSProperty: end
D/AndroidRuntime( 5523): addProductProperty: start
D/dalvikvm( 5523): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5523): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5523): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5523): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5523): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5523): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5523): failed to load memtrack module: -2
D/dalvikvm( 5523): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5523): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  739): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  739): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  739): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  739): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  739): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  739): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  739): START PACKAGE DELETE: observer{1129075000}
D/PackageManager(  739): pkg{<packageName>}
D/PackageManager(  739): user{0}
D/PackageManager(  739): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  739): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  739): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  739): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  739): getApplicationUninstallationEnabled
D/ApplicationPolicy(  739): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  739): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  739): !@killApplicatoin: 10179, uninstall pkg
E/SMD     (  240): DCD ON
D/PackageManager(  739): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  739): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/RCPManagerService(  739): PackageReceiver onReceive()
I/InputReader(  739): Reconfiguring input devices.  changes=0x00000010
I/HarmonyEASService(  739): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux ( 5543): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5543):  
D/AdaptiveEventManager( 1064): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3305): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/FPMS_FingerprintManagerService( 1083): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 2173): GC_EXPLICIT freed 985K, 42% free 11018K/18904K, paused 4ms+4ms, total 95ms
D/dalvikvm(  247): GC_EXPLICIT freed 43K, 50% free 9506K/18904K, paused 2ms+3ms, total 36ms
W/GeofencerStateMachine( 1210): Ignoring removeGeofence because network location is disabled.
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 1ms+3ms, total 18ms
I/SELinux ( 5543): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5543):  
I/SELinux ( 5543):  
I/SELinux ( 5543): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5543): >>>>> Normal User
E/dalvikvm( 5543): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5543): in addTimaSignatureService
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18904K, paused 3ms+2ms, total 21ms
D/TimaKeyStoreProvider( 5543): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5543): Added TimaKesytore provider
D/dalvikvm( 1397): GC_EXPLICIT freed 4296K, 47% free 10021K/18904K, paused 3ms+5ms, total 102ms
D/dalvikvm( 1756): GC_EXPLICIT freed 855K, 36% free 12236K/18904K, paused 3ms+8ms, total 189ms
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "sms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "mms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  739): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  739): removePackageParticipantsLocked: uid=10179 #1
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=5543, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm(  739): GC_EXPLICIT freed 3446K, 55% free 23922K/53156K, paused 42ms+12ms, total 295ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 57ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 61ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 60ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 60ms
D/dalvikvm(  739): WAIT_FOR_CONCURRENT_GC blocked 56ms
D/elm:14132( 5543): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5543): ELMEngine.ELMEngine( context ).
D/elm:14132( 5543): MDMBridge.setEnterpriseBridge()
D/PackageManager(  739): delete sourFile : 
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "sms"
D/elm:14132( 5543): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5543): ElmAgentService : onCreate()
D/elm:14132( 5543): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5543): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5543): MDMBridge.getInstance()
D/elm:14132( 5543): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/InputMethodInfo(  739): Duplicated subtype definition found: , voice
D/PackageManager(  739): delete native library directory: 
D/PackageManager(  739): return delete result to caller: 1129075000
D/AndroidRuntime( 5523): Shutting down VM
D/PackageManager(  739): returnCode: 1
D/dalvikvm( 5523): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
D/elm:14132( 5543): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5565): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5565):  
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
D/elm:14132( 5543): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/PackageManager(  739):   Scheme: "mms"
D/elm:14132( 5543): ElmAgentService : onDestroy().
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager(  739): Killing 4471:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "mmsto"
D/EnterpriseDeviceManagerService(  739): Package has changed for user 0
D/EnterpriseDeviceManagerService(  739): Admin package name: com.google.android.gms
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5565): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5565):  
I/SELinux ( 5565):  
I/SELinux ( 5565): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5565): >>>>> Normal User
E/dalvikvm( 5565): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 5565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "sms"
D/TimaKeyStoreProvider( 5565): in addTimaSignatureService
D/TimaKeyStoreProvider( 5565): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5565): Added TimaKesytore provider
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "mms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=5565, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 5565): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42cd5d10, skipping init
I/SecureStorage( 5565): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 5565): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  382): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5565
I/SecureStorage(  382): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 5565): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 5565): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  382): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5565
I/SecureStorage(  382): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  739): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  739): clearDefaults: com.test.thalitest
W/AtomicFile(  739): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  739): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/InputReader(  739): Processing first event
W/ApplicationsProvider( 1397): Could not fetch usage stats
W/ApplicationsProvider( 1397): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1397): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1397): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1397): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1397): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1397): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1397): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1397): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
