#### Test 757892686fd65a6_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
07-01 08:58:44.871  5996  5996 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
--------- beginning of system
07-01 08:58:44.871  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.871  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.871  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.871  1019  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.891  6261  6261 E Zygote  : MountEmulatedStorage()
07-01 08:58:44.891  6261  6261 E Zygote  : v2
07-01 08:58:44.891  6261  6261 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-01 08:58:44.891  6261  6261 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-01 08:58:44.891  6261  6261 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 08:58:44.891  6261  6261 I libpersona: KNOX_SDCARD checking this for 10100
07-01 08:58:44.891  6261  6261 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:44.891  1019  1326 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6261 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-01 08:58:44.911  6261  6261 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:44.911  6261  6261 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:44.921  1953  2131 I art     : Explicit concurrent mark sweep GC freed 61199(3MB) AllocSpace objects, 7(256KB) LOS objects, 40% free, 14MB/23MB, paused 1.685ms total 82.822ms
07-01 08:58:44.961  6261  6261 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
07-01 08:58:44.961  6261  6261 D PackageIntentReceiver: Not GearManger package! 
07-01 08:58:44.961  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
07-01 08:58:44.961  1019  1032 D ActivityManager: com.samsung.helphub, Starting
07-01 08:58:44.961  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.961  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.961  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.961  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:44.961  3819  4309 I Icing   : Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
07-01 08:58:44.971  6283  6283 E Zygote  : MountEmulatedStorage()
07-01 08:58:44.971  6283  6283 E Zygote  : v2
07-01 08:58:44.971  6283  6283 I libpersona: KNOX_SDCARD checking this for 1000
07-01 08:58:44.971  6283  6283 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:44.971  6283  6283 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-01 08:58:44.981  6283  6283 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-01 08:58:44.981  6283  6283 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 08:58:44.981  1019  1032 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6283 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
07-01 08:58:44.991  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
07-01 08:58:45.001  1019  1549 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 08:58:45.001  1019  1549 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
07-01 08:58:45.011  1019  1549 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.011  1019  1549 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.011  1019  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.011  1019  1031 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
07-01 08:58:45.011  1019  1031 D ActivityManager: com.google.android.gms, Starting
07-01 08:58:45.011  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
07-01 08:58:45.021  6283  6283 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:45.021  6283  6283 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:45.051  1019  1326 I ActivityManager: Killing 5186:com.google.android.gm/u0a101 (adj 15): empty #31
07-01 08:58:45.051  1953  1953 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-01 08:58:45.081  1019  1502 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
07-01 08:58:45.081  1019  1502 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
07-01 08:58:45.081  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:45.081  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:45.081  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:45.081  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:45.081  5996  6290 W AccountFeatureHelper: Write apps_features disabled false
07-01 08:58:45.091  3819  4309 I Icing   : Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
07-01 08:58:45.091  6301  6301 E Zygote  : MountEmulatedStorage()
07-01 08:58:45.091  6301  6301 E Zygote  : v2
07-01 08:58:45.091  6301  6301 I libpersona: KNOX_SDCARD checking this for 1000
07-01 08:58:45.091  6301  6301 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:45.091  6301  6301 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-01 08:58:45.101  6301  6301 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-01 08:58:45.101  1019  1502 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6301 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
07-01 08:58:45.101  1019  1502 I ActivityManager: Killing 5704:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
07-01 08:58:45.101  6301  6301 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 08:58:45.131  6301  6301 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:45.131  6301  6301 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:45.161  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 08:58:45.161  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.161  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.161  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.181  1019  1335 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
07-01 08:58:45.181  6301  6316 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
07-01 08:58:45.181  6301  6316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
07-01 08:58:45.181  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.181  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.181  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.191  1019  1142 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
07-01 08:58:45.191  1019  1142 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
07-01 08:58:45.191  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.191  1019  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:45.191  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
07-01 08:58:45.191  6301  6301 D AcmsService: Enter Oncreate
07-01 08:58:45.201  6301  6301 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-01 08:58:45.201  6301  6301 D AcmsService: creating AcmsCore
07-01 08:58:45.201  6301  6301 D AcmsCore: AcmsCore.getAcmsCore() - Enter
07-01 08:58:45.201  6301  6301 D AcmsCore: AcmsCore
07-01 08:58:45.201  6301  6301 D AcmsCore: init
07-01 08:58:45.201  6301  6301 D AcmsCore: Looper handler is not null
07-01 08:58:45.201  6301  6301 D AcmsCore: Post to AcmsCoreHandler
07-01 08:58:45.201  6301  6301 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-01 08:58:45.201  6301  6301 D AcmsServiceMonitor: Incrementing - Counter value: 1
07-01 08:58:45.201  6301  6301 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
07-01 08:58:45.201  6301  6301 D AcmsService: onStartCommand
07-01 08:58:45.201  6301  6301 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
07-01 08:58:45.201  6301  6301 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
07-01 08:58:45.201  6301  6301 D AcmsServiceMonitor: Incrementing - Counter value: 2
07-01 08:58:45.201  6301  6301 D AcmsService: Incremented Counter Value : onStartCommand
07-01 08:58:45.201  1019  1032 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
07-01 08:58:45.201  1019  1032 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
07-01 08:58:45.201  6301  6317 D AcmsCertificateMngr: AcmsCertificateMngr
07-01 08:58:45.201  6301  6301 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
07-01 08:58:45.211  6301  6317 D AcmsRevocationMngr: AcmsRevocationMngr
07-01 08:58:45.221  5996  5996 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-01 08:58:45.221  1019  1326 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 08:58:45.221  1019  1326 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.221  1019  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.221  1019  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.241  1019  1502 I ActivityManager: Killing 4462:com.google.android.music:main/u0a111 (adj 15): empty #31
07-01 08:58:45.241  6301  6301 D AcmsService: Inside handle Intent
07-01 08:58:45.241  6301  6301 D AcmsService: App added - package name: com.test.thalitest
07-01 08:58:45.241  6301  6301 D AcmsCore: Post to AcmsCoreHandler
07-01 08:58:45.241  6301  6301 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-01 08:58:45.241  6301  6301 D AcmsServiceMonitor: Incrementing - Counter value: 3
07-01 08:58:45.241  6301  6301 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
07-01 08:58:45.241  6301  6301 D AcmsService: Decremented Counter Value : handleStartIntent
07-01 08:58:45.241  6301  6301 D AcmsServiceMonitor: Decrementing - Counter value: 2
07-01 08:58:45.261  1019  1142 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-01 08:58:45.261  1019  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
07-01 08:58:45.261  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.261  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.261  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.281  1019  1549 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 08:58:45.281  1019  1549 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.281  1019  1549 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.281  1019  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.281  1953  6320 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-01 08:58:45.281  1953  6299 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-01 08:58:45.291  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 08:58:45.291  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.291  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.291  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.301  1953  2131 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 08:58:45.311  1019  1549 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 08:58:45.311  1019  1549 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.311  1019  1549 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.311  1019  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.311  1953  6320 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-01 08:58:45.311   276  1013 D EnterpriseController: uids 10012
07-01 08:58:45.311   276  1013 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
07-01 08:58:45.311   276  1013 D Netd    : getNetworkForDns: using netid 502 for uid 10012
07-01 08:58:45.311  1953  6299 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-01 08:58:45.311  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 08:58:45.311  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.311  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.311  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.311  1953  2131 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-01 08:58:45.311  1953  2131 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1953, getuid(): 10012
07-01 08:58:45.341  1019  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 08:58:45.341  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.341  1019  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.341  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.341  1953  6320 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-01 08:58:45.341  1953  6299 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-01 08:58:45.341  1953  6299 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
07-01 08:58:45.361  1953  2131 I qtaguid : Tagging socket 77 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1953, getuid(): 10012
07-01 08:58:45.361  1953  6299 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-01 08:58:45.371  5927  5927 I Mms/MmsApp:  start initViewCache mms
07-01 08:58:45.381  5927  5927 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1950.428957
07-01 08:58:45.381  5927  5927 D Mms/ComposeMessageFragment: fillCache, easy = false
07-01 08:58:45.421  1019  1502 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-01 08:58:45.471  1953  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 08:58:45.471   276  1013 D EnterpriseController: uids 10012
07-01 08:58:45.471   276  1013 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
07-01 08:58:45.471   276  1013 D Netd    : getNetworkForDns: using netid 502 for uid 10012
07-01 08:58:45.471  1953  6299 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-01 08:58:45.471  1953  6299 I qtaguid : Tagging socket 82 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1953, getuid(): 10012
07-01 08:58:45.481  5927  5927 D AbsListView: Get MotionRecognitionManager
07-01 08:58:45.481  1019  1504 D MotionRecognitionService:  ssp status : false
07-01 08:58:45.491  5927  5927 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 113.342292
07-01 08:58:45.511  1953  6299 I qtaguid : Tagging socket 85 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1953, getuid(): 10012
07-01 08:58:45.571  5927  5927 D Mms/BubbleViewCache: fillCache bubble = 1
07-01 08:58:45.601  1953  2131 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-01 08:58:45.601  1953  2131 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
07-01 08:58:45.611  1953  2131 V BaseAppContext: GmsRequestQueue started.
07-01 08:58:45.611  1953  6326 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 08:58:45.611   276  1013 D EnterpriseController: uids 10012
07-01 08:58:45.611   276  1013 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
07-01 08:58:45.611   276  1013 D Netd    : getNetworkForDns: using netid 502 for uid 10012
07-01 08:58:45.621  1953  6326 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-01 08:58:45.621  1953  6326 I qtaguid : Tagging socket 86 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1953, getuid(): 10012
07-01 08:58:45.661  1953  6326 I qtaguid : Tagging socket 89 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1953, getuid(): 10012
07-01 08:58:45.731   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 08:58:45.781  3819  4309 I Icing   : Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
07-01 08:58:45.841  1019  1539 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-01 08:58:45.851  1953  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 08:58:45.851  1953  6299 I qtaguid : Tagging socket 82 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1953, getuid(): 10012
07-01 08:58:45.871  3819  4309 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
07-01 08:58:45.891  1019  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-01 08:58:45.891  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:45.891  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:45.891  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 08:58:45.891  1953  6326 I qtaguid : Untagging socket 86
07-01 08:58:45.891  1953  2131 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
07-01 08:58:45.991  1019  1549 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-01 08:58:46.011  6333  6333 D AndroidRuntime: 
07-01 08:58:46.011  6333  6333 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 08:58:46.011  6333  6333 D AndroidRuntime: CheckJNI is OFF
07-01 08:58:46.011  6333  6333 D AndroidRuntime: readGMSProperty: start
07-01 08:58:46.011  6333  6333 D AndroidRuntime: readGMSProperty: already setted!!
07-01 08:58:46.011  6333  6333 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 08:58:46.011  6333  6333 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 08:58:46.011  6333  6333 D AndroidRuntime: readGMSProperty: end
07-01 08:58:46.011  6333  6333 D AndroidRuntime: addProductProperty: start
07-01 08:58:46.031  1953  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 08:58:46.031  1953  6299 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1953, getuid(): 10012
07-01 08:58:46.141  6333  6333 E AffinityControl: AffinityControl: registerfunction enter
07-01 08:58:46.161  1953  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 08:58:46.161  1953  6299 I qtaguid : Tagging socket 82 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1953, getuid(): 10012
07-01 08:58:46.161  6333  6333 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 08:58:46.171  1019  1032 E PersonaManagerService: inState():  stateMachine is null !!
07-01 08:58:46.171  1019  1032 I PersonaManagerService: PersonaId don't exist
07-01 08:58:46.171  1019  1032 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-01 08:58:46.171  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 08:58:46.181  1019  1032 W ActivityManager: mDVFSHelper.acquire()
07-01 08:58:46.191  1019  1032 D FocusedStackFrame: Set to : 0
07-01 08:58:46.191  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-01 08:58:46.191  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-01 08:58:46.201  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.201  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.201  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.201  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:46.211  6344  6344 E Zygote  : MountEmulatedStorage()
07-01 08:58:46.211  6344  6344 E Zygote  : v2
07-01 08:58:46.211  6344  6344 I libpersona: KNOX_SDCARD checking this for 10155
07-01 08:58:46.211  6344  6344 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:46.211  6344  6344 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-01 08:58:46.211  1019  1032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6344 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 08:58:46.211  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 08:58:46.211  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 08:58:46.211  1019  1032 D InputDispatcher: Focused application set to: xxxx
07-01 08:58:46.211  1019  1032 D InputDispatcher: Focus left window: 1488
07-01 08:58:46.211  6333  6333 D AndroidRuntime: Shutting down VM
07-01 08:58:46.211  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-01 08:58:46.211  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-01 08:58:46.211   256   256 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-01 08:58:46.211  6344  6344 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-01 08:58:46.221  6344  6344 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-01 08:58:46.231  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 08:58:46.231  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:46.231  6344  6344 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:46.231  6344  6344 D ActivityThread: Added TimaKeyStore provider
07-01 08:58:46.231  1019  1549 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-01 08:58:46.241  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:46.251  1019  1549 D PersonaManager: isKioskContainerExistOnDevice
07-01 08:58:46.271  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-01 08:58:46.311   256  1041 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-01 08:58:46.311   256   451 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-01 08:58:46.321  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{3d14e6d0 token=android.os.BinderProxy@32e39775 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-01 08:58:46.321  1488  1488 D Launcher: onTrimMemory. Level: 20
07-01 08:58:46.331  1019  1539 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-01 08:58:46.341  1953  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 08:58:46.341  1953  6299 I qtaguid : Tagging socket 82 with tag 1106583100000000{285628465,0} for uid -1, pid: 1953, getuid(): 10012
07-01 08:58:46.371  1019  1539 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-01 08:58:46.371  1019  1539 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-01 08:58:46.371  1019  1539 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-01 08:58:46.371  1019  1539 D BatteryService: stay LED for fully charged
07-01 08:58:46.381  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-01 08:58:46.371  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-01 08:58:46.381  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 08:58:46.381  1019  1019 I MotionRecognitionService: Plugged
07-01 08:58:46.381  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
07-01 08:58:46.381  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-01 08:58:46.381  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-01 08:58:46.391  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:58:46.391  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:58:46.391  6344  6344 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-01 08:58:46.391  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 08:58:46.391  2654  2734 D HeadsetStateMachine: Disconnected process message: 10
07-01 08:58:46.411  6344  6344 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6380-6382)
07-01 08:58:46.411  6344  6344 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:46.411  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 08:58:46.421  6333  6333 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-01 08:58:46.431  6344  6344 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1db41b1a}
07-01 08:58:46.431  6344  6344 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:46.431  6344  6344 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 08:58:46.461  6344  6344 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 08:58:46.471  6344  6344 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:46.471  6344  6344 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 08:58:46.491  6344  6344 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-01 08:58:46.491  6344  6344 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-01 08:58:46.491  6344  6344 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-01 08:58:46.501  6344  6344 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-01 08:58:46.501  6344  6344 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-01 08:58:46.501  6344  6344 I Adreno-EGL: Build Date: 04/06/15 Mon
07-01 08:58:46.501  6344  6344 I Adreno-EGL: Local Branch: 
07-01 08:58:46.501  6344  6344 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-01 08:58:46.501  6344  6344 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-01 08:58:46.501  6344  6344 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-01 08:58:46.651  6344  6372 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-01 08:58:46.691  6344  6344 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:46.711  6344  6344 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 08:58:46.721  6344  6344 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-01 08:58:46.721  6344  6344 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-01 08:58:46.721  6301  6317 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
07-01 08:58:46.721  6344  6344 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-01 08:58:46.731   322   322 I ServiceManager: Waiting for service AtCmdFwd...
07-01 08:58:46.731  6344  6344 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:46.731  6344  6344 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:46.741  6301  6317 I AcmsKeyStoreHelper: Key Store exist
07-01 08:58:46.741  6301  6317 I AcmsKeyStoreHelper: Hence loading the keystore file
07-01 08:58:46.751  1019  1045 W ActivityManager: Activity pause timeout for ActivityRecord{3670e417 u0 com.test.thalitest/.MainActivity t24}
07-01 08:58:46.781  6344  6385 D OpenGLRenderer: Render dirty regions requested: true
07-01 08:58:46.781  1019  1502 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 08:58:46.781  1019  1502 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 08:58:46.781  1019  1502 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-01 08:58:46.781  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 08:58:46.781  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
07-01 08:58:46.791  6344  6344 V ActivityThread: updateVisibility : ActivityRecord{315a5aed token=android.os.BinderProxy@b09d17 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-01 08:58:46.801  6344  6344 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-01 08:58:46.801  6344  6344 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-01 08:58:46.801   256   256 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
07-01 08:58:46.811  1019  2746 D SSRM:n  : SIOP:: AP = 350
07-01 08:58:46.811  1019  1549 D InputDispatcher: Focus entered window: 6344
07-01 08:58:46.811  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 08:58:46.821  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:46.821  6344  6344 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-01 08:58:46.821  6344  6385 I OpenGLRenderer: Initialized EGL, version 1.4
07-01 08:58:46.821  6344  6385 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-01 08:58:46.831  6344  6385 D OpenGLRenderer: Enabling debug mode 0
07-01 08:58:46.851  6301  6317 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
07-01 08:58:46.851  6301  6317 I AcmsCertificateMngr: getKeyStoreForApplication success 
07-01 08:58:46.851  6301  6317 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
07-01 08:58:46.851  6301  6317 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-01 08:58:46.851  6301  6317 D AcmsServiceMonitor: Decrementing - Counter value: 1
07-01 08:58:46.851  6301  6317 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
07-01 08:58:46.851  6301  6317 D AcmsCore: This is NOT a valid MirrorLink app
07-01 08:58:46.851  6301  6317 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
07-01 08:58:46.851  6301  6317 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-01 08:58:46.851  6301  6317 D AcmsServiceMonitor: Decrementing - Counter value: 0
07-01 08:58:46.851  6301  6317 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
07-01 08:58:46.851  6301  6301 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-01 08:58:46.851  6301  6301 D AcmsService: Enter onDestroy
07-01 08:58:46.851  6301  6301 I AcmsService: cleanUp(): inside service clean up
07-01 08:58:46.851  6301  6301 D AcmsCore: AcmsCore: inside DeInit
07-01 08:58:46.851  6301  6301 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
07-01 08:58:46.851  6301  6301 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
07-01 08:58:46.851  6301  6301 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
07-01 08:58:46.851  6301  6301 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
07-01 08:58:46.851  6301  6301 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
07-01 08:58:46.851  6301  6301 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-01 08:58:46.851  6301  6301 D AcmsService: killing acms process
07-01 08:58:46.851  6301  6301 I Process : Sending signal. PID: 6301 SIG: 9
07-01 08:58:46.871  1019  1335 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-01 08:58:46.881  1019  6388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-01 08:58:46.881  6344  6344 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b09d17 time:126855
07-01 08:58:46.881  1178  1178 I StatusBar: Icon Only
07-01 08:58:46.881  1178  1178 D PanelView: There is/are notification(s) 
07-01 08:58:46.891  6344  6344 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-01 08:58:46.891  1807  1807 I SamsungIME: getCurrentCandidateView
07-01 08:58:46.891  1019  1050 I ActivityManager: Displayed Component not be shown by security: +640ms (total +12s235ms)
07-01 08:58:46.901  1019  1050 W ActivityManager: mDVFSHelper.release()
07-01 08:58:46.901  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3670e417 u0 com.test.thalitest/.MainActivity t24} time:126870
07-01 08:58:46.901   256   451 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-01 08:58:46.901   256  1041 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
07-01 08:58:46.961  1019  1308 I ActivityManager: Process ACMS.Process (pid 6301)(adj 0) has died(38,1147)
07-01 08:58:46.961  1807  1807 D SamsungIME: Dismiss ExpandCandiate
07-01 08:58:46.971  6344  6344 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6344
07-01 08:58:47.091  6344  6344 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-01 08:58:47.111  1807  1807 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 08:58:47.141  1807  1807 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 08:58:47.151  1807  1807 I SamsungIME: KeybaordView init() : load resources
,07-01 08:58:47.181  1807  1807 I SamsungIME: getCurrentKeyboard
,07-01 08:58:47.181  1807  1807 I SamsungIME: getTextKeyboard
,07-01 08:58:47.191  1807  1807 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-01 08:58:47.211  6344  6390 D jxcore_app_log: JniHelper::setJavaVM(0xb7cf5328), pthread_self() = -1205515696
,07-01 08:58:47.221  6344  6390 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:47.221  6344  6390 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:47.221  6344  6390 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:47.221  6344  6390 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:47.221  6344  6390 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 08:58:47.221  6344  6390 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3594d95d added. We now have 1 listener(s)
,07-01 08:58:47.221  6344  6390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,07-01 08:58:47.231  6344  6390 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,07-01 08:58:47.231  6344  6390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 08:58:47.231  6344  6390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 08:58:47.231  6344  6390 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4b22a0 added. We now have 1 listener(s)
,07-01 08:58:47.231  6344  6390 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 08:58:47.241  6344  6390 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-01 08:58:47.241  6344  6390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 08:58:47.241  6344  6390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:58:47.241  6344  6390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-01 08:58:47.241  6344  6390 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 08:58:47.251  6344  6390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 08:58:47.251  6344  6390 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 08:58:47.261  6344  6390 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 08:58:47.261  6344  6390 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:47.261  6344  6390 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 08:58:47.271  6344  6390 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 08:58:47.271  6344  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 08:58:47.271  6344  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 08:58:47.311  6344  6344 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:58:47.711  1953  6327 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 08:58:47.711  1953  6327 I qtaguid : Tagging socket 86 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1953, getuid(): 10012
,07-01 08:58:47.721  1807  6393 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-01 08:58:47.731   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 08:58:47.751   286   286 E SMD     : DCD OFF
,07-01 08:58:47.851  6344  6398 W jxcore-log: Initializing JXcore engine
07-01 08:58:47.851  6344  6398 W jxcore-log: JXcore engine is ready
,07-01 08:58:47.891  1019  1549 I ActivityManager: Killing 5383:com.dropbox.android/u0a92 (adj 15): empty #31
,07-01 08:58:47.921  1933  1933 E audit   : type=1400 msg=audit(1467356327.921:205): avc:  denied  { ioctl } for  pid=6398 comm="Thread-1098" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-01 08:58:47.921  1933  1933 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
,07-01 08:58:47.921  1933  1933 E audit   : type=1300 msg=audit(1467356327.921:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9eac08f8 items=0 ppid=312 ppcomm=main pid=6398 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1098" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-01 08:58:47.921  1933  1933 E audit   : type=1320 msg=audit(1467356327.921:205): 
,07-01 08:58:47.931  1953  6327 I qtaguid : Untagging socket 86
,07-01 08:58:47.931  6344  6398 W jxcore-log: Starting JXcore engine
,07-01 08:58:47.931  1953  2131 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-01 08:58:47.971  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,07-01 08:58:48.001  3819  4309 V UdcCtxListenerSrv: handle intent
,07-01 08:58:48.051  6344  6398 W jxcore-log: Platform android
07-01 08:58:48.051  6344  6398 W jxcore-log: 
07-01 08:58:48.051  6344  6398 W jxcore-log: Process ARCH arm
07-01 08:58:48.051  6344  6398 W jxcore-log: 
,07-01 08:58:48.251  6344  6398 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:58:48.251  6344  6398 I jxcore-log: 
,07-01 08:58:48.251  6344  6398 W jxcore-log: JXcore engine is started
,07-01 08:58:48.261  6344  6390 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 08:58:48.261  6344  6344 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 08:58:48.271  6344  6398 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-01 08:58:48.271  6344  6398 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 08:58:48.281  6344  6344 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-01 08:58:48.281  6344  6344 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 08:58:48.281  1019  1142 D FocusedStackFrame: Set to : 0
07-01 08:58:48.281  1019  1142 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 08:58:48.281  1019  1142 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 08:58:48.281  1019  1142 D InputDispatcher: Focused application set to: xxxx
07-01 08:58:48.281  1019  1142 D InputDispatcher: Focus left window: 6344
07-01 08:58:48.291  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 08:58:48.291  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 08:58:48.291  1019  1142 I ActivityManager: Killing 5358:com.google.android.talk/u0a104 (adj 15): empty #31
07-01 08:58:48.291  6344  6344 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 08:58:48.301  6344  6344 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-01 08:58:48.301  6344  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-01 08:58:48.301  6344  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 08:58:48.301  6344  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 08:58:48.301  6344  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 08:58:48.301  6344  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3594d95d removed from the list
07-01 08:58:48.301  6344  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 08:58:48.301  6344  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4b22a0 removed from the list
07-01 08:58:48.301  6344  6344 D io.jxcore.node.ConnectivityMonitor: stop
07-01 08:58:48.301  6344  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-01 08:58:48.301  6344  6344 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 08:58:48.311   256   451 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-01 08:58:48.311   256  1041 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-01 08:58:48.321  1019  1549 W ActivityManager: mDVFSHelper.acquire()
,07-01 08:58:48.321  1019  1549 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-01 08:58:48.341  1488  1488 D Launcher: onRestart, Launcher: 929615590
07-01 08:58:48.341  1488  1488 D Launcher: onStart, Launcher: 929615590
07-01 08:58:48.341  1488  1488 D Launcher.HomeView: onStart
07-01 08:58:48.341  1488  1488 D Launcher: onResume, Launcher: 929615590
,07-01 08:58:48.351  1019  1548 D SettingsProvider: name = kids_home_mode
07-01 08:58:48.351  1019  1548 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 08:58:48.351  1019  1548 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 08:58:48.351  1019  1548 D SettingsProvider: selectionArgs: false
07-01 08:58:48.351  1019  1548 D SettingsProvider: selectionArgs: 10007
07-01 08:58:48.351  1019  1548 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 08:58:48.351  1019  1548 D SettingsProvider: ret = -1
,07-01 08:58:48.351  1488  1488 D Launcher.HomeView: onResume
,07-01 08:58:48.361  1488  1488 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-01 08:58:48.361  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.361  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.361  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-01 08:58:48.361  1488  1488 D MenuAppsGridFragment: onResume
,07-01 08:58:48.361  1019  1308 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,07-01 08:58:48.361  1019  1308 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-01 08:58:48.371  1488  1488 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-01 08:58:48.371  1488  1488 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-01 08:58:48.371  1019  1308 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.371  1488  1488 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-01 08:58:48.371  1019  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.371  1019  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-01 08:58:48.371  5037  5037 D GalleryCacheReady: Receive : home resume
,07-01 08:58:48.371  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.371  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 08:58:48.381  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-01 08:58:48.381  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.381  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 08:58:48.381  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-01 08:58:48.381  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-01 08:58:48.381  1019  1045 D ActivityManager: com.sec.android.widgetapp.digitalclock, Starting
,07-01 08:58:48.381  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.381  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.381  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.381  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.401  6403  6403 E Zygote  : MountEmulatedStorage()
,07-01 08:58:48.401  6403  6403 I libpersona: KNOX_SDCARD checking this for 10088
07-01 08:58:48.401  6403  6403 E Zygote  : v2
07-01 08:58:48.401  6403  6403 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:48.401  1019  1045 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6403 uid=10088 gids={50088, 9997} abi=armeabi-v7a
07-01 08:58:48.401  6403  6403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-01 08:58:48.401  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.401  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.401  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-01 08:58:48.411  6403  6403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-01 08:58:48.411  1019  1308 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.411  1019  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.411  1019  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
07-01 08:58:48.411  6403  6403 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-01 08:58:48.411  1019  1335 D ActivityManager: handle home activity for 0
07-01 08:58:48.411  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
07-01 08:58:48.411  1019  1335 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-01 08:58:48.411  1019  1335 D KnoxTimeoutHandler: post home show event for user 0
07-01 08:58:48.411  1019  1335 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 08:58:48.411  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-01 08:58:48.411  1019  1335 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 08:58:48.411  1019  1335 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-01 08:58:48.411  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-01 08:58:48.411  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 08:58:48.411  1488  1488 D Launcher.HomeView: onPause
,07-01 08:58:48.421  1488  1488 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-01 08:58:48.421  5927  5927 D Mms/UIEventReceiver: ui event
07-01 08:58:48.421  5783  5783 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-01 08:58:48.421  1019  1326 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.421  1019  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.421  1019  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-01 08:58:48.431  1019  1326 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.431  1019  1326 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1488, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-01 08:58:48.431  1019  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.431  1019  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-01 08:58:48.431  6403  6403 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:48.441  6403  6403 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:48.441  1019  1549 D PersonaManager: isKioskContainerExistOnDevice
,07-01 08:58:48.451   256   256 I SurfaceFlinger: id=14 createSurf (720x1280),1 flag=4, Mauncher
07-01 08:58:48.451  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.451  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.451  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-01 08:58:48.451  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:48.451  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-01 08:58:48.451  2521  2521 D Recents_RecreateReceiver: onReceive by home
,07-01 08:58:48.461  1019  1502 D InputDispatcher: Focus entered window: 1488
,07-01 08:58:48.461  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 08:58:48.461  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-01 08:58:48.461  1488  1488 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-01 08:58:48.471  6403  6403 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 08:58:48.471  1488  1488 D Launcher.HomeView: onStop
07-01 08:58:48.471  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{3d14e6d0 token=android.os.BinderProxy@32e39775 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-01 08:58:48.471  1019  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-01 08:58:48.481  6344  6344 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-01 08:58:48.481  1019  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 08:58:48.481  1807  1807 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-01 08:58:48.491  1178  1178 I StatusBar: Icon Only
,07-01 08:58:48.491  1178  1178 D PanelView: There is/are notification(s) 
,07-01 08:58:48.501  1019  1335 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.501  1019  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.501  1019  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-01 08:58:48.501  1019  1335 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-01 08:58:48.501  1019  1335 D ActivityManager: com.sec.android.app.camera, Starting
,07-01 08:58:48.501  1019  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.501  1019  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.501  1019  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.501  1019  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:48.511  1488  1488 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@32e39775 time:128481
,07-01 08:58:48.521  6422  6422 E Zygote  : MountEmulatedStorage()
07-01 08:58:48.521  6422  6422 I libpersona: KNOX_SDCARD checking this for 10139
07-01 08:58:48.521  6422  6422 E Zygote  : v2
07-01 08:58:48.521  6422  6422 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:48.521  6422  6422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,07-01 08:58:48.521  1019  1335 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6422 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,07-01 08:58:48.521  1019  1335 I ActivityManager: Killing 5750:com.google.android.gms:car/u0a12 (adj 15): empty #31,
,07-01 08:58:48.521  6422  6422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-01 08:58:48.531  6422  6422 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:48.531  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11ff31d3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t22} time:128504
07-01 08:58:48.531  1019  1050 W ActivityManager: mDVFSHelper.release()
,07-01 08:58:48.551  6422  6422 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:48.551  6422  6422 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:48.551  6399  6399 D AndroidRuntime: 
07-01 08:58:48.551  6399  6399 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-01 08:58:48.561  6399  6399 D AndroidRuntime: CheckJNI is OFF
,07-01 08:58:48.561  6399  6399 D AndroidRuntime: readGMSProperty: start
07-01 08:58:48.561  6399  6399 D AndroidRuntime: readGMSProperty: already setted!!
07-01 08:58:48.561  6399  6399 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 08:58:48.561  6399  6399 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 08:58:48.561  6399  6399 D AndroidRuntime: readGMSProperty: end
07-01 08:58:48.561  6399  6399 D AndroidRuntime: addProductProperty: start
,07-01 08:58:48.581  6422  6422 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-01 08:58:48.581  6422  6422 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-01 08:58:48.581  6422  6422 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-01 08:58:48.581  6422  6422 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-01 08:58:48.581  6422  6422 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 08:58:48.601  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-01 08:58:48.621  1019  1335 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,07-01 08:58:48.621  1019  1335 I ActivityManager: Killing 5487:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,07-01 08:58:48.621  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:48.621  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:48.621  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-01 08:58:48.631  5783  5783 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-01 08:58:48.691  6399  6399 E AffinityControl: AffinityControl: registerfunction enter
,07-01 08:58:48.721  6399  6399 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-01 08:58:48.731  1019  1031 D PackageManager: START PACKAGE DELETE: observer{58177512}
07-01 08:58:48.731  1019  1031 D PackageManager: pkg{<packageName>}
07-01 08:58:48.731  1019  1031 D PackageManager: user{0}
07-01 08:58:48.731  1019  1031 D PackageManager: caller{2000}
07-01 08:58:48.731  1019  1031 D PackageManager: flags{2}
,07-01 08:58:48.731  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,07-01 08:58:48.731  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-01 08:58:48.731  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,07-01 08:58:48.731  1019  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-01 08:58:48.731  1019  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-01 08:58:48.731  1019  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-01 08:58:48.731  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-01 08:58:48.731   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
07-01 08:58:48.731  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
07-01 08:58:48.731  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
07-01 08:58:48.731  1019  1060 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
07-01 08:58:48.731  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-01 08:58:48.731  1019  1045 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
07-01 08:58:48.731  1019  1045 I ActivityManager: Killing 6344:com.test.thalitest/u0a155 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-01 08:58:48.841  1019  1060 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,07-01 08:58:48.851  1019  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-01 08:58:48.881  5684  5684 I art     : Explicit concurrent mark sweep GC freed 1979(113KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 929us total 24.372ms
,07-01 08:58:48.881  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-01 08:58:48.901  6183  6183 I art     : Explicit concurrent mark sweep GC freed 26893(1646KB) AllocSpace objects, 1(22KB) LOS objects, 24% free, 8MB/11MB, paused 1.766ms total 51.975ms
,07-01 08:58:48.911  1807  1807 E SamsungIME: mOCRHelper is null
,07-01 08:58:48.911  5808  5808 I art     : Explicit concurrent mark sweep GC freed 13150(723KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 879us total 58.328ms
07-01 08:58:48.911  1953  2117 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 08:58:48.931  1452  1452 D PersonaManager: isKioskContainerExistOnDevice
,07-01 08:58:48.941  3674  3674 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jul 01 08:58:48 GMT+02:00 2016
,07-01 08:58:48.941  1019  1127 V NetworkStats: removeUidsLocked() for UIDs [10155]
07-01 08:58:48.941  1019  1127 V NetworkStats: performPollLocked(flags=0x3)
,07-01 08:58:48.941  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 08:58:48.941  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,07-01 08:58:48.951  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-01 08:58:48.951  1019  1504 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-01 08:58:48.951  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-01 08:58:48.951  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:48.951  1452  1452 D RegisteredServicesCache: empty dynamic service
,07-01 08:58:48.951  1019  1127 V NetworkStats: performPollLocked() took 15ms
07-01 08:58:48.951  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 08:58:48.951  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 08:58:48.951  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-01 08:58:48.981  1452  1452 D RegisteredComponentCache: Collect Tech packages for Knox
,07-01 08:58:48.981  1452  1452 D PersonaManager: isKioskContainerExistOnDevice
,07-01 08:58:48.991  3674  3674 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,07-01 08:58:48.991  1019  1308 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
07-01 08:58:48.991  1019  1308 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-01 08:58:48.991  1019  1308 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-01 08:58:48.991  1019  1308 D ActivityManager: com.sec.esdk.elm, Starting
,07-01 08:58:48.991  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.991  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.991  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:48.991  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.011  6447  6447 E Zygote  : MountEmulatedStorage(),
07-01 08:58:49.011  6447  6447 E Zygote  : v2
07-01 08:58:49.011  6447  6447 I libpersona: KNOX_SDCARD checking this for 10094
,07-01 08:58:49.011  6447  6447 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.011  6447  6447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-01 08:58:49.011  6447  6447 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-01 08:58:49.011  1019  1308 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6447 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,07-01 08:58:49.011  6447  6447 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.021  1019  1335 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,07-01 08:58:49.021  1019  1335 D SecContentProvider2: mCursor = null
,07-01 08:58:49.031  3674  3674 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,07-01 08:58:49.031  3674  3674 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-01 08:58:49.041  3674  3674 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-01 08:58:49.051  6447  6447 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.051  6447  6447 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.061  3674  6446 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-01 08:58:49.091  3674  6446 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,07-01 08:58:49.101  3674  6446 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,07-01 08:58:49.111  3674  6446 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-01 08:58:49.141  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 08:58:49.141  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 08:58:49.141  1019  1019 D RCPManagerService: PackageReceiver onReceive()
07-01 08:58:49.151  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-01 08:58:49.151  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.151  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-01 08:58:49.151  1019  1019 D OTPFW   : OtpDbHelper::getInstance New instance created
07-01 08:58:49.151  1019  1019 D OTPFW   : DBIntegrity::getInstance - New instance created
07-01 08:58:49.151  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
07-01 08:58:49.151  1019  1045 D ActivityManager: com.sec.android.app.themechooser, Starting
07-01 08:58:49.151  5037  5037 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
07-01 08:58:49.161  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
07-01 08:58:49.161  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
07-01 08:58:49.161  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
07-01 08:58:49.161  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-01 08:58:49.161  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicy: uID is 10155
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-01 08:58:49.161  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.161  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.161  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.161  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 08:58:49.161  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-01 08:58:49.171  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-01 08:58:49.181  6463  6463 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.181  6463  6463 E Zygote  : v2
07-01 08:58:49.181  6463  6463 I libpersona: KNOX_SDCARD checking this for 10149
07-01 08:58:49.181  6463  6463 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.181  6463  6463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-01 08:58:49.181  6463  6463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-01 08:58:49.181  6463  6463 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.191  1019  1045 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6463 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 08:58:49.191  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
,07-01 08:58:49.191  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-01 08:58:49.191  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=24_task.xml
07-01 08:58:49.191  1019  1019 V EnterpriseBillingPolicy: uID is 10155
07-01 08:58:49.191  1019  1019 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
07-01 08:58:49.191  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 08:58:49.191  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-01 08:58:49.201  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-01 08:58:49.201  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 08:58:49.201  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 08:58:49.201  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-01 08:58:49.201  1019  2746 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-01 08:58:49.201  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-01 08:58:49.211  6463  6463 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 08:58:49.211  6463  6463 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.221  3674  6446 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-01 08:58:49.231  1019  1060 I art     : Explicit concurrent mark sweep GC freed 59303(4MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/43MB, paused 3.534ms total 305.880ms
,07-01 08:58:49.231  1019  1142 I art     : WaitForGcToComplete blocked for 199.934ms for cause Explicit
,07-01 08:58:49.241  3674  6446 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-01 08:58:49.251  3674  6446 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,07-01 08:58:49.251  3674  3674 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,07-01 08:58:49.251  1019  1060 D PackageManager: delete codoeFile: 
,07-01 08:58:49.261  1019  1060 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,07-01 08:58:49.261  1019  1060 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,07-01 08:58:49.271  1019  1060 D PackageManager: result of delete: 1{58177512}
,07-01 08:58:49.271  6399  6399 D AndroidRuntime: Shutting down VM
,07-01 08:58:49.271  1019  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-01 08:58:49.271  1019  1060 D PackageManager: userId{-1}
07-01 08:58:49.271  1019  1060 D PackageManager: andCode{true}
,07-01 08:58:49.281  1019  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-01 08:58:49.381  1019  1142 I art     : Explicit concurrent mark sweep GC freed 12288(720KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 2.553ms total 151.462ms
,07-01 08:58:49.391  1019  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-01 08:58:49.391  1019  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-01 08:58:49.391  5927  5927 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-01 08:58:49.391  1019  1044 W TextServicesManagerService: no available spell checker services found
,07-01 08:58:49.401  1019  1502 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,07-01 08:58:49.401  1019  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,07-01 08:58:49.411  1019  1502 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:49.411  1019  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:49.411  1019  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,07-01 08:58:49.411  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.421  1019  1031 I TactileAssist: enable value -1
,07-01 08:58:49.421  1019  1031 I TactileAssist: internal enable value -1
,07-01 08:58:49.421  1019  1031 I TactileAssist: intensity value -1
,07-01 08:58:49.421  1019  1031 I TactileAssist: saveAppList value true
,07-01 08:58:49.421  5808  6462 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,07-01 08:58:49.431  1019  1031 I TactileAssist: List of disabled apps :
,07-01 08:58:49.441  5927  6478 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.441  5927  6478 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-01 08:58:49.441  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.451  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.451  6447  6447 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-01 08:58:49.461  6447  6447 D elm:15183: ELMEngine.ELMEngine( context ).
,07-01 08:58:49.461  6463  6463 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-01 08:58:49.461  6463  6463 D ThemeInfoUtil: isCurrentFestival = false
,07-01 08:58:49.461  6447  6447 D elm:15183: MDMBridge.setEnterpriseBridge()
,07-01 08:58:49.461  6163  6163 D Compatibility: onReceive() it will make start service
,07-01 08:58:49.461  5808  5808 I art     : Explicit concurrent mark sweep GC freed 1042(50KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.142ms total 58.637ms
,07-01 08:58:49.481  1019  1548 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-01 08:58:49.481  1019  1548 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-01 08:58:49.481  1019  1548 W ActivityManager: userId = 0, bbcId = -10000
,07-01 08:58:49.481  1019  1548 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:49.481  1019  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-01 08:58:49.481  6447  6447 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-01 08:58:49.481  6399  6399 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-01 08:58:49.491  1488  1488 D Launcher.Model: reloadBadges entered.
07-01 08:58:49.491  6089  6100 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-01 08:58:49.491  6089  6100 D BadgeProvider: sendNotify, [notify] : null
07-01 08:58:49.491  6089  6100 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-01 08:58:49.491  6089  6100 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-01 08:58:49.491  6089  6100 D BadgeProvider: update, [UpdateCount] : 1
,07-01 08:58:49.491  6447  6447 D elm:15183: ElmAgentService : onCreate(),
07-01 08:58:49.491  6447  6480 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-01 08:58:49.491  6447  6480 D elm:15183: MainReceiver.listeningToPackageRemoved()
07-01 08:58:49.491  6447  6480 D elm:15183: MDMBridge.getInstance()
07-01 08:58:49.491  6447  6480 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
07-01 08:58:49.491  3330  3330 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-01 08:58:49.491  3330  3330 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-01 08:58:49.491  3330  3330 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-01 08:58:49.491  3330  3330 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-01 08:58:49.491  3330  3330 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-01 08:58:49.491  3330  3330 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-01 08:58:49.491  3330  3330 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-01 08:58:49.491  3330  3330 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:49.491  3330  3330 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 08:58:49.491  3330  3330 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 08:58:49.491  3330  3330 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:49.491  3330  3330 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:49.491  1019  1504 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-01 08:58:49.491  3330  3330 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 08:58:49.491  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
07-01 08:58:49.491  3330  3330 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-01 08:58:49.491  6447  6480 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
07-01 08:58:49.491  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:49.491  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:49.491  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
07-01 08:58:49.501  1019  1502 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-01 08:58:49.501  1019  1502 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-01 08:58:49.501  1019  1502 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:49.501  1019  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:49.501  1019  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
07-01 08:58:49.511  5139  5139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
07-01 08:58:49.511  1019  1539 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-01 08:58:49.511  1019  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
07-01 08:58:49.511  1019  1539 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:49.511  1019  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 08:58:49.511  1019  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
07-01 08:58:49.511  6447  6447 D elm:15183: ElmAgentService : onDestroy().
07-01 08:58:49.521  6163  6482 D Compatibility: onHandleIntent()
07-01 08:58:49.521  6163  6482 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
07-01 08:58:49.521  6163  6482 D Compatibility: found: 2
07-01 08:58:49.521  6163  6482 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-01 08:58:49.521  6163  6482 D Compatibility: skipping ResolveInfo{26f46941 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-01 08:58:49.521  6163  6482 D Compatibility: considering ResolveInfo{3768cee6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-01 08:58:49.521  6163  6482 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
07-01 08:58:49.521  6163  6482 D Compatibility: enabling receiver ResolveInfo{328e5c27 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
07-01 08:58:49.531  6011  6011 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
07-01 08:58:49.531  6011  6011 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
07-01 08:58:49.531  6011  6011 I TapandpayWidget:Utils: Clear T&P info.
07-01 08:58:49.531  5944  5944 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-01 08:58:49.531  6011  6011 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
07-01 08:58:49.531  5944  5944 I PCWCLIENTTRACE_PushUtil: sales region : global
07-01 08:58:49.531  5944  5944 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-01 08:58:49.531  5944  5944 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.531  6163  6482 D Compatibility: enabling receiver ResolveInfo{13db4ed4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
07-01 08:58:49.541  1019  1142 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-01 08:58:49.541  1019  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-01 08:58:49.541  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
07-01 08:58:49.541  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 08:58:49.541  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
07-01 08:58:49.541  6163  6482 D Compatibility: enabling receiver ResolveInfo{125d587d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-01 08:58:49.551  1019  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
07-01 08:58:49.551  6163  6482 D Compatibility: enabling receiver ResolveInfo{3062f372 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
07-01 08:58:49.551  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.551  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.561  6163  6482 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
07-01 08:58:49.561  5546  5546 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
07-01 08:58:49.561  1019  1326 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-01 08:58:49.561  1019  1326 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
07-01 08:58:49.561  6183  6486 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-01 08:58:49.561  1019  1539 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
07-01 08:58:49.561  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.561  1019  1539 D ActivityManager: com.sec.enterprise.knox.cloudmdm.smdms, Starting
07-01 08:58:49.561  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.561  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.561  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.561  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.571  1019  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-01 08:58:49.571  1019  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 08:58:49.571  1019  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 08:58:49.571  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.581  6487  6487 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.581  6487  6487 I libpersona: KNOX_SDCARD checking this for 10160
07-01 08:58:49.581  6487  6487 E Zygote  : v2
07-01 08:58:49.581  6487  6487 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.581  6487  6487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-01 08:58:49.581  1019  1539 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6487 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
07-01 08:58:49.581  6487  6487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-01 08:58:49.581  6487  6487 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 08:58:49.611  1019  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-01 08:58:49.611  1019  1539 D ActivityManager: com.samsung.android.intelligenceservice, Starting
,07-01 08:58:49.611  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.611  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.611  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.611  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.611  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.621  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.621  6502  6502 E Zygote  : MountEmulatedStorage(),
,07-01 08:58:49.631  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.631  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-01 08:58:49.631  6502  6502 E Zygote  : v2
,07-01 08:58:49.631  1019  1539 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6502 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
07-01 08:58:49.631  6487  6487 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:49.631  6502  6502 I libpersona: KNOX_SDCARD checking this for 10003
07-01 08:58:49.631  6502  6502 I libpersona: KNOX_SDCARD not a persona
07-01 08:58:49.631  6487  6487 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.631  6183  6486 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-01 08:58:49.631  6183  6486 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-01 08:58:49.641  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 08:58:49.641  6502  6502 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-01 08:58:49.641  6018  6018 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
07-01 08:58:49.641  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.641  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.,
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 08:58:49.641  6018  6018 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-01 08:58:49.641  6018  6018 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:49.641  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.641  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 08:58:49.651  6502  6502 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-01 08:58:49.651  6502  6502 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 08:58:49.651  1019  1539 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-01 08:58:49.651  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 08:58:49.651  1019  1539 D ActivityManager: com.sec.spp.push, Starting
07-01 08:58:49.651   312   312 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 677us total 24.156ms
07-01 08:58:49.651  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.651  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.651  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 08:58:49.651  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 08:58:49.671  6487  6487 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-01 08:58:49.671   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 17.240ms
,07-01 08:58:49.671  6502  6502 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 08:58:49.671  6502  6502 D ActivityThread: Added TimaKeyStore provider
,07-01 08:58:49.691   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.154ms
,07-01 08:58:49.691  6487  6487 D [0]UMC:UMCContentProvider: @onCreate
,07-01 08:58:49.701  6518  6518 E Zygote  : MountEmulatedStorage()
07-01 08:58:49.701  6518  6518 E Zygote  : v2
07-01 08:58:49.701  6518  6518 I libpersona: KNOX_SDCARD checking this for 10035
07-01 08:58:49.701  6518  6518 I libpersona: KNOX_SDCARD not a persona
,07-01 08:58:49.701  6518  6518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,07-01 08:58:49.711  6518  6518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
07-01 08:58:49.711  6518  6518 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL

```
