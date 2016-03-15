#### Test 625481247d7767b_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-15 15:00:54.038  2068  2068 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
03-15 15:00:54.048  2068  3789 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
03-15 15:00:54.078  2068  3789 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
--------- beginning of system
03-15 15:00:54.128  1018  3636 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.128  1018  3636 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.128  1018  3636 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.128  1018  3636 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:54.148  3495  3717 E File    : fail readDirectory() errno=2
03-15 15:00:54.158  3495  3762 I Gmail   : notifyAccountChanged
03-15 15:00:54.158  3495  3762 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-15 15:00:54.158  3793  3793 E Zygote  : MountEmulatedStorage()
03-15 15:00:54.158  3793  3793 I libpersona: KNOX_SDCARD checking this for 10028
03-15 15:00:54.158  3793  3793 E Zygote  : v2
03-15 15:00:54.158  3793  3793 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:54.158  3793  3793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:54.168  3495  3621 I Gmail   : getAccountsCursor
03-15 15:00:54.168  3793  3793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:54.168  3793  3793 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 15:00:54.168  1018  3636 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3793 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-15 15:00:54.168  3495  3762 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-15 15:00:54.178  1018  3636 I ActivityManager: Killing 2985:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
03-15 15:00:54.178  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:54.178  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:54.178  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:54.188  3495  3762 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-15 15:00:54.188  3495  3762 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-15 15:00:54.208  3793  3793 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:54.218  3793  3793 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:54.218  2068  2068 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
03-15 15:00:54.218  2068  2068 D BootCompletedReceiver: Got an BootCompleted event.
03-15 15:00:54.228  1685  1712 I art     : Explicit concurrent mark sweep GC freed 4192(180KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 845us total 38.813ms
03-15 15:00:54.248  1685  1704 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-15 15:00:54.258  2068  3789 W BaseAppContext: Using Auth Proxy for data requests.
03-15 15:00:54.258  2068  2068 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
03-15 15:00:54.258  2068  3788 I SystemUpdateService: cancelUpdate (empty URL)
03-15 15:00:54.258  2068  3788 I SystemUpdateService: active receiver: disabled
03-15 15:00:54.268  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:54.268  1018  1586 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:54.268  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:54.268  1018  1522 I ActivityManager: Killing 3038:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
03-15 15:00:54.408  1018  1042 W libprocessgroup: failed to open /acct/uid_10043/pid_2985/cgroup.procs: No such file or directory
03-15 15:00:54.458  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3038/cgroup.procs: No such file or directory
03-15 15:00:54.468  2068  2087 I art     : WaitForGcToComplete blocked for 105.335ms for cause HomogeneousSpaceCompact
03-15 15:00:54.548  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:54.548  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:54.548  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:54.548  1018  1078 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:54.548  1018  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:54.548  1018  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:54.568  1018  3636 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:54.568  1018  3636 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:54.568  1018  3636 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:54.578  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:54.578  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:54.578  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:54.598  2068  2068 D SystemUpdateService: onDestroy
03-15 15:00:54.648  2068  3789 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
03-15 15:00:54.658  3743  3827 I Babel   : MmsConfig: mnc/mcc: 0/0
03-15 15:00:54.658  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
03-15 15:00:54.658  3743  3827 I Babel   : MmsConfig.loadMmsSettings
03-15 15:00:54.658  3743  3827 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-15 15:00:54.668  3743  3827 I Babel   : MmsConfig.loadFromDatabase
03-15 15:00:54.678  3793  3793 I System.out: Inside onCreate() of WakeupTriggerProvide
03-15 15:00:54.678  3793  3793 I System.out: Inside WakeupProvider
03-15 15:00:54.708  1018  3627 I ActivityManager: Killing 3023:com.sec.dsm.system/1000 (adj 15): empty #31
03-15 15:00:54.718  2623  2623 D FactoryTestApp: [DummyFtClient$onDestroy](2623) Destroy DummyFtClient service
03-15 15:00:54.718  2623  2623 D FactoryTestApp: [Support$Values.getString](2623) id=MODEL_COMMUNICATION_MODE, value=gsm
03-15 15:00:54.718  2623  2623 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2623) mConnectionMode = gsm
03-15 15:00:54.718  2623  2623 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2623) RUNNING_FTCLIENT : false
03-15 15:00:54.718  2623  2623 D FactoryTestApp: [DummyFtClient$onDestroy](2623) kill process
03-15 15:00:54.718  2623  2623 I Process : Sending signal. PID: 2623 SIG: 9
03-15 15:00:54.768  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
03-15 15:00:54.768  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
03-15 15:00:54.778  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.778  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.778  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.778  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.778  3743  3825 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 15:00:54.778  1685  3814 I art     : Explicit concurrent mark sweep GC freed 3492(140KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 969us total 35.051ms
03-15 15:00:54.788  3838  3838 E Zygote  : MountEmulatedStorage()
03-15 15:00:54.788  3838  3838 E Zygote  : v2
03-15 15:00:54.788  3838  3838 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:54.788  3838  3838 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:54.788  3838  3838 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:54.798  3838  3838 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:54.798  3838  3838 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:54.798  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3838 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:54.798  1018  2738 I ActivityManager: Process com.sec.factory (pid 2623)(adj 0) has died(68,652)
03-15 15:00:54.798  3743  3825 W AudioCapabilities: Unsupported mime audio/evrc
03-15 15:00:54.808  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3023/cgroup.procs: No such file or directory
03-15 15:00:54.818  3743  3825 W AudioCapabilities: Unsupported mime audio/qcelp
03-15 15:00:54.828  3838  3838 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:54.828  3838  3838 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:54.838  3743  3827 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-15 15:00:54.838  3743  3827 I Babel   : MmsConfig.loadFromResources
03-15 15:00:54.838  3743  3827 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-15 15:00:54.838  3743  3827 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-15 15:00:54.848  3743  3825 W AudioCapabilities: Unsupported mime audio/mpeg-L1
03-15 15:00:54.848  3743  3825 W AudioCapabilities: Unsupported mime audio/mpeg-L2
03-15 15:00:54.848  3743  3743 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-15 15:00:54.858  2068  3789 I AuthZen : Fetching signing key...
03-15 15:00:54.868  3793  3793 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
03-15 15:00:54.878  3227  3286 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-15 15:00:54.888  3743  3825 W AudioCapabilities: Unsupported mime audio/x-ms-wma
03-15 15:00:54.888  3743  3825 W AudioCapabilities: Unsupported mime audio/x-ima
03-15 15:00:54.888  3743  3825 W AudioCapabilities: Unsupported mime audio/qcelp
03-15 15:00:54.898  3743  3825 W AudioCapabilities: Unsupported mime audio/evrc
03-15 15:00:54.928  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
03-15 15:00:54.928  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:54.938  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:54.938  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-15 15:00:54.948  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.948  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.948  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.948  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:54.958  3743  3825 W VideoCapabilities: Unsupported mime video/wvc1
03-15 15:00:54.968  3743  3825 W VideoCapabilities: Unsupported mime video/x-ms-wmv
03-15 15:00:54.968  3857  3857 E Zygote  : MountEmulatedStorage()
03-15 15:00:54.968  3857  3857 E Zygote  : v2
03-15 15:00:54.968  3857  3857 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:54.968  3857  3857 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:54.968  3857  3857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:54.968  3857  3857 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:54.978  3857  3857 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:54.978  1018  2738 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3857 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:54.978  1718  1718 I GCoreUlr: DispatchingService.onCreate()
03-15 15:00:54.998  1718  3863 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
03-15 15:00:54.998  3793  3793 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
03-15 15:00:55.008  2068  3789 I AuthZen : Signing key fetched successfully!
03-15 15:00:55.008  3857  3857 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.008  3857  3857 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.018  3743  3825 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
03-15 15:00:55.018  2068  3789 W BaseAppContext: Using Auth Proxy for data requests.
03-15 15:00:55.028  3743  3825 W VideoCapabilities: Unsupported mime video/wvc1
03-15 15:00:55.028  3743  3825 W VideoCapabilities: Unsupported mime video/x-ms-wmv
03-15 15:00:55.038  3743  3825 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
03-15 15:00:55.038   280   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-15 15:00:55.038   280   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-15 15:00:55.038  3857  3857 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-15 15:00:55.048  3743  3825 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
03-15 15:00:55.048  3743  3825 W VideoCapabilities: Unsupported mime video/mp43
03-15 15:00:55.048  3743  3825 W VideoCapabilities: Unsupported mime video/sorenson
03-15 15:00:55.058  3812  3812 D AndroidRuntime: 
03-15 15:00:55.058  3812  3812 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 15:00:55.058  3812  3812 D AndroidRuntime: CheckJNI is OFF
03-15 15:00:55.058  3812  3812 D AndroidRuntime: readGMSProperty: start
03-15 15:00:55.058  3812  3812 D AndroidRuntime: readGMSProperty: already setted!!
03-15 15:00:55.058  3812  3812 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-15 15:00:55.058  3812  3812 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-15 15:00:55.058  3812  3812 D AndroidRuntime: readGMSProperty: end
03-15 15:00:55.058  3812  3812 D AndroidRuntime: addProductProperty: start
03-15 15:00:55.068  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
03-15 15:00:55.068  3227  3286 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-15 15:00:55.068  1018  1585 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.068  1018  1585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:55.068  1018  1585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
03-15 15:00:55.078  3227  3286 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
03-15 15:00:55.078  3227  3286 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-15 15:00:55.078  3227  3286 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-15 15:00:55.078  3227  3286 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-15 15:00:55.078  1018  2738 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.078  3227  3286 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-15 15:00:55.078  1018  2738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:55.078  1018  2738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
03-15 15:00:55.078  3227  3286 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
03-15 15:00:55.098  3857  3857 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
03-15 15:00:55.098  3743  3825 W VideoCapabilities: Unsupported mime video/mp4v-esdp
03-15 15:00:55.098  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.098  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.098  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.098  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.098  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
03-15 15:00:55.108  3882  3882 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.108  3882  3882 E Zygote  : v2
03-15 15:00:55.108  3882  3882 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:55.108  3882  3882 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.108  3882  3882 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.118  1018  1586 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:55.118  3882  3882 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.118  3882  3882 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:55.128  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.128  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:55.128  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
03-15 15:00:55.138  3743  3743 V Babel   : babel boot account: SMS
03-15 15:00:55.138  2068  3789 D a       : Opening database auth.proximity.permit_store...
03-15 15:00:55.148  3743  3743 V Babel   : babel boot account: thalitester@gmail.com
03-15 15:00:55.148  2068  3789 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-15 15:00:55.148  2068  3789 D AuthZenTransactionCache: Clearing transaction cache
03-15 15:00:55.168  3882  3882 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.168  3882  3882 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.168  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.168  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.168  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.168  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.188  3910  3910 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.188  3910  3910 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:55.188  3910  3910 E Zygote  : v2
03-15 15:00:55.188  3910  3910 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.188  3910  3910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.188  3743  3825 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-15 15:00:55.188  1018  1585 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3910 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:55.188  3910  3910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.198  3910  3910 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:55.208  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.208  1018  1586 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:55.208  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
03-15 15:00:55.208  1018  1097 V AlarmManager: waitForAlarm result :4
03-15 15:00:55.208   309   309 I art     : Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 20.568ms
03-15 15:00:55.218  3857  3857 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-15 15:00:55.218  3857  3857 I F_PHONE : default registerAction()
03-15 15:00:55.218  3857  3857 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
03-15 15:00:55.218  3910  3910 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.218  3910  3910 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.228   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 18.510ms
03-15 15:00:55.238  1018  1585 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.238  1018  1585 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:55.238  1018  1585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:55.248   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 16.816ms
03-15 15:00:55.248  3882  3882 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-15 15:00:55.258  1018  1097 V AlarmManager: waitForAlarm result :4
03-15 15:00:55.268  1018  1583 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.268  1018  1583 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:55.268  1018  1583 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:55.278  1018  1585 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.288  1018  1585 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:55.288  1018  1585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:55.288  3882  3882 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-15 15:00:55.288  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
03-15 15:00:55.298  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.298  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:55.298  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
03-15 15:00:55.298  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.298  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.298  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.298  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.308  1493  1493 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-15 15:00:55.318  1493  1493 D BluetoothBDTestService: onCreate()
03-15 15:00:55.318  1493  1493 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-15 15:00:55.318  1493  1493 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
03-15 15:00:55.318  1493  1493 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-15 15:00:55.318  2068  3802 I Icing   : Storage manager: low false usage 2.10MB avail 9.95GB capacity 11.63GB
03-15 15:00:55.328  3929  3929 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.328  3929  3929 E Zygote  : v2
03-15 15:00:55.328  3929  3929 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:55.328  3929  3929 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.328  3929  3929 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.328  1718  3861 I GCM     : GCM config loaded
03-15 15:00:55.328  1018  3628 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:55.328  3929  3929 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.328  1018  3628 I ActivityManager: Killing 3077:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
03-15 15:00:55.338  3929  3929 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:55.348  3793  3793 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
03-15 15:00:55.348  3793  3793 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
03-15 15:00:55.358  3929  3929 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.368  3929  3929 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.378  3929  3929 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:55.388  3793  3793 D DialogFlow: initQueue()
03-15 15:00:55.398  3495  3566 I Gmail   : getAccountsCursor
03-15 15:00:55.408  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.408  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.408  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.408  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.428  3947  3947 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.428  3947  3947 E Zygote  : v2
03-15 15:00:55.428  3947  3947 I libpersona: KNOX_SDCARD checking this for 10029
03-15 15:00:55.428  3947  3947 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.428  3947  3947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.428  3947  3947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.428  1018  1514 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3947 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-15 15:00:55.428  3947  3947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:55.438  1018  1514 I ActivityManager: Killing 1641:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
03-15 15:00:55.458  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3077/cgroup.procs: No such file or directory
03-15 15:00:55.458  3947  3947 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.458  3947  3947 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.498  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-15 15:00:55.498  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:55.498  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:55.498  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-15 15:00:55.498  3838  3856 I AMMetaDataParserService: Resource data:2131165186
03-15 15:00:55.498  3838  3856 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 15:00:55.498  3838  3856 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:55.498  3838  3856 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 15:00:55.498  3838  3856 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:00:55.498  1018  1210 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 15:00:55.498  3929  3929 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
03-15 15:00:55.508  3929  3929 I KnoxUsageLogPro: premStatus:2
03-15 15:00:55.508  3929  3929 I KnoxUsageLogPro: isEulaShown : false
03-15 15:00:55.508  3929  3929 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
03-15 15:00:55.508  1018  1514 I ActivityManager: Killing 3054:com.google.android.configupdater/u0a82 (adj 15): empty #31
03-15 15:00:55.508  3929  3962 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458050455520
03-15 15:00:55.568  1018  1042 W libprocessgroup: failed to open /acct/uid_10068/pid_1641/cgroup.procs: No such file or directory
03-15 15:00:55.568  1018  1042 W libprocessgroup: failed to open /acct/uid_10082/pid_3054/cgroup.procs: No such file or directory
03-15 15:00:55.578  3838  3856 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-15 15:00:55.578  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:55.598  1018  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.598  1018  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.598  1018  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.598  1018  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.598  3838  3856 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
03-15 15:00:55.608  3966  3966 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.608  3966  3966 E Zygote  : v2
03-15 15:00:55.608  3966  3966 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:55.608  3966  3966 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.608  1018  1583 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:55.608  1018  1583 I ActivityManager: Killing 3112:com.dropbox.android/u0a88 (adj 15): empty #31
03-15 15:00:55.608  3966  3966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.618  3966  3966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.618  3966  3966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:55.618  3838  3856 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
03-15 15:00:55.628  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.628  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.628  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.628  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.648  3929  3962 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 42106
03-15 15:00:55.648  3966  3966 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.648  3966  3966 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.648  3838  3856 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
03-15 15:00:55.648  3983  3983 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.648  3983  3983 I libpersona: KNOX_SDCARD checking this for 10030
03-15 15:00:55.648  3983  3983 E Zygote  : v2
03-15 15:00:55.648  3983  3983 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.658  1018  3627 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3983 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-15 15:00:55.658  1018  3627 I ActivityManager: Killing 3127:com.sec.android.diagmonagent/1000 (adj 15): empty #31
03-15 15:00:55.658  3983  3983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.658  1718  1718 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 15:00:55.658  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
03-15 15:00:55.668  3983  3983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.668  3983  3983 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-15 15:00:55.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-15 15:00:55.678  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.678  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:55.678  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-15 15:00:55.678  3838  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:00:55.698  3983  3983 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.698  3983  3983 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.728  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-15 15:00:55.728  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:55.728  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:55.728  3838  3856 I AMMetaDataParserService: Resource data:2131034113
03-15 15:00:55.748  1018  1042 W libprocessgroup: failed to open /acct/uid_10088/pid_3112/cgroup.procs: No such file or directory
03-15 15:00:55.748  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3127/cgroup.procs: No such file or directory
03-15 15:00:55.748  1718  3982 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
03-15 15:00:55.758  3838  3856 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 15:00:55.758  3838  3856 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:55.758  3838  3856 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-15 15:00:55.758  3966  3966 E KnoxSetupWizardClient: isShipMode : 1
03-15 15:00:55.758  3966  3966 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
03-15 15:00:55.798  3838  3856 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 15:00:55.798  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:55.818  3966  3966 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
03-15 15:00:55.818  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:55.818  3812  3812 E AffinityControl: AffinityControl: registerfunction enter
03-15 15:00:55.828  3966  4001 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-15 15:00:55.828  3966  4001 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-15 15:00:55.828  3966  4001 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-15 15:00:55.828  3966  4001 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-15 15:00:55.828  3966  4001 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-15 15:00:55.828  3966  4001 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-15 15:00:55.828  3966  4001 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
03-15 15:00:55.828  3838  3856 I GFX construct_block_size_descriptor_2d second part: took 3.087603ms for 0*0 texture 0
03-15 15:00:55.838  3838  3856 I GFX generate_partition_tables: took 6.269844ms for 0*0 texture 0
03-15 15:00:55.838  3966  3966 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
03-15 15:00:55.838  3838  3856 I GFX raster: took 10.652031ms for 96*96 texture 0
03-15 15:00:55.838  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7810ae8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a72e10 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:55.838  3966  3966 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-15 15:00:55.838  3966  3966 D ShortcutReceiver:  shortcut migration not required 
03-15 15:00:55.838  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.838  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.838  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.838  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.848  3838  3856 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-15 15:00:55.858  4006  4006 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.858  4006  4006 E Zygote  : v2
03-15 15:00:55.858  4006  4006 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:55.858  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:55.858  4006  4006 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.858  4006  4006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.858  3838  3856 I GFX raster: took 1.180625ms for 96*96 texture 0
03-15 15:00:55.858  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7810ae8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a73940 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:55.858  4006  4006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.858  1018  1586 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4006 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:55.858  4006  4006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:55.858  1018  1586 I ActivityManager: Killing 3160:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
03-15 15:00:55.888  4006  4006 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.888  4006  4006 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:55.928  4006  4006 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
03-15 15:00:55.938  4006  4006 I StatusChecker: onReceive : net.mt.init : DONE
03-15 15:00:55.938  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.938  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.938  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.938  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:55.948  3838  3856 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
03-15 15:00:55.948  4023  4023 I libpersona: KNOX_SDCARD checking this for 10113
03-15 15:00:55.948  4023  4023 E Zygote  : MountEmulatedStorage()
03-15 15:00:55.948  4023  4023 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:55.948  4023  4023 E Zygote  : v2
03-15 15:00:55.958  4023  4023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:55.958  4023  4023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:55.958  3812  3812 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-15 15:00:55.958  1018  1522 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4023 uid=10113 gids={50113, 9997} abi=armeabi-v7a
03-15 15:00:55.958  1018  1522 I ActivityManager: Killing 3202:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
03-15 15:00:55.958  4023  4023 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:55.968  1018  1078 I ActivityManager: Killing 3227:com.policydm/1000 (adj 15): empty #31
03-15 15:00:55.978  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:55.978  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:55.978  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:00:55.978  1018  1583 E PersonaManagerService: inState():  stateMachine is null !!
03-15 15:00:55.978  1018  1583 I PersonaManagerService: PersonaId don't exist
03-15 15:00:55.978  1018  1583 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-15 15:00:55.978  1018  1583 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 15:00:55.988  1018  1042 W libprocessgroup: failed to open /acct/uid_10146/pid_3160/cgroup.procs: No such file or directory
03-15 15:00:55.998  4023  4023 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:55.998  4023  4023 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:56.008  1018  1583 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 15:00:56.018  1018  1583 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 15:00:56.018  1018  1583 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 15:00:56.018  1018  1583 W ActivityManager: mDVFSHelper.acquire()
03-15 15:00:56.018  1018  1583 D InputDispatcher: Focused application set to: xxxx
03-15 15:00:56.018  1018  1583 D FocusedStackFrame: Set to : 0
03-15 15:00:56.018  1018  1583 D InputDispatcher: Focus left window: 1524
03-15 15:00:56.018  1524  1524 D Launcher.HomeView: onPause
03-15 15:00:56.028  3812  3812 D AndroidRuntime: Shutting down VM
03-15 15:00:56.028  1524  1524 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-15 15:00:56.038  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.038  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.038  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.038  1018  1586 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.058  4041  4041 E Zygote  : MountEmulatedStorage()
03-15 15:00:56.058  4041  4041 E Zygote  : v2
03-15 15:00:56.058  4041  4041 I libpersona: KNOX_SDCARD checking this for 10167
03-15 15:00:56.058  4041  4041 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:56.058  4041  4041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:56.058  4041  4041 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:56.058  1018  1586 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4041 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 15:00:56.058  4041  4041 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 15:00:56.068  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3227/cgroup.procs: No such file or directory
03-15 15:00:56.068  1018  1042 W libprocessgroup: failed to open /acct/uid_10088/pid_3202/cgroup.procs: No such file or directory
03-15 15:00:56.078  4023  4023 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
03-15 15:00:56.088  4041  4041 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:56.088  4041  4041 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:56.088  1018  2738 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:00:56.088  1018  2738 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 15:00:56.088  1018  2738 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:00:56.088  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 15:00:56.088  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-15 15:00:56.088  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:00:56.088  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-15 15:00:56.098  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 15:00:56.098  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-15 15:00:56.098   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
03-15 15:00:56.108  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:00:56.108  4023  4023 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
03-15 15:00:56.148  1018  1078 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:56.148  1524  1524 V ActivityThread: updateVisibility : ActivityRecord{2f21fa3f token=android.os.BinderProxy@109be989 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-15 15:00:56.148  1524  1524 D Launcher.HomeView: onStop
03-15 15:00:56.148  1018  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:56.148  1018  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
03-15 15:00:56.148  1524  1524 V ActivityThread: updateVisibility : ActivityRecord{2f21fa3f token=android.os.BinderProxy@109be989 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-15 15:00:56.148  1524  1524 D Launcher: onTrimMemory. Level: 20
03-15 15:00:56.158  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-15 15:00:56.158  1018  1018 D SensorService: [SO] activate (ident=0xb7eaf3d0, enabled=0)
03-15 15:00:56.158  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-15 15:00:56.168  4023  4023 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
03-15 15:00:56.178  1018  1018 D SensorManager: unregisterListener ::   
03-15 15:00:56.178  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-15 15:00:56.178  1718  1718 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
03-15 15:00:56.178  1018  1018 D SensorService: [SO] changed settle time [1]
03-15 15:00:56.178  1018  1018 D SensorService: [SO] setDelay [66000000]
03-15 15:00:56.178  1018  1018 D SensorService: [SO] activate (ident=0xb7eaf3d0, enabled=1)
03-15 15:00:56.178  1018  1018 D SensorService: [SO] AR_init
03-15 15:00:56.178  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-15 15:00:56.178  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.178  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.178  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.178  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.188  1018  1048 D PersonaManager: isKioskContainerExistOnDevice
03-15 15:00:56.188  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-15 15:00:56.198  4061  4061 E Zygote  : MountEmulatedStorage()
03-15 15:00:56.198  4061  4061 E Zygote  : v2
03-15 15:00:56.198  4061  4061 I libpersona: KNOX_SDCARD checking this for 10121
03-15 15:00:56.198  4061  4061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:56.198  4061  4061 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:56.208  4061  4061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:56.208  1718  1727 I art     : Explicit concurrent mark sweep GC freed 26299(1948KB) AllocSpace objects, 36(576KB) LOS objects, 39% free, 9MB/16MB, paused 1.422ms total 218.633ms
03-15 15:00:56.208  1018  1210 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4061 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-15 15:00:56.208  4061  4061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:56.228  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:56.228  3838  3856 I GFX construct_block_size_descriptor_2d second part: took 2.298125ms for 0*0 texture 0
03-15 15:00:56.228  3983  3983 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 15:00:56.228  3983  3983 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:56.228  3983  3983 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-15 15:00:56.238  3812  3812 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-15 15:00:56.258  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 15:00:56.258  3983  3983 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 15:00:56.258  3983  3983 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:00:56.258  3983  3983 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:00:56.268  3838  3856 I GFX generate_partition_tables: took 7.723231ms for 0*0 texture 0
,03-15 15:00:56.268  3838  3856 I GFX raster: took 10.966928ms for 96*96 texture 0
03-15 15:00:56.268  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a72e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a73940 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.278  4061  4061 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:56.278  4061  4061 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:56.278  3983  3983 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-15 15:00:56.278  3983  3983 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 15:00:56.278  1718  3982 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-15 15:00:56.288  3838  3856 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-15 15:00:56.318  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:56.318  3838  3856 I GFX raster: took 0.602083ms for 96*96 texture 0
03-15 15:00:56.318  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a73940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a58258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.328  1018  1040 D SensorService: [SO] -0.479 0.211 9.902
,03-15 15:00:56.328  1018  1040 D SensorService: [SO] [100 -> 255]
,03-15 15:00:56.348  3838  3856 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-15 15:00:56.368  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:56.368  3838  3856 I GFX raster: took 0.818698ms for 96*96 texture 0
03-15 15:00:56.368  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a688e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a68988 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.378  3838  3856 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-15 15:00:56.388  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:56.388  3838  3856 I GFX raster: took 0.667343ms for 96*96 texture 0
,03-15 15:00:56.388  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a6be10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a6bf68 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.398  1018  1587 I art     : Explicit concurrent mark sweep GC freed 41096(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/33MB, paused 2.747ms total 204.050ms
,03-15 15:00:56.398  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-15 15:00:56.398  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:56.398  1018  1587 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:56.398  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-15 15:00:56.408  1718  2132 W GCoreFlp: No location to return for getLastLocation()
,03-15 15:00:56.408  1718  2143 W FusedLocationProvider: location=null
,03-15 15:00:56.408  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:56.408  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:56.408  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:00:56.418  3244  3386 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 15:00:56.428  1718  1718 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:00:56.438  4041  4041 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-15 15:00:56.438  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:56.438  3838  3856 I GFX raster: took 0.690677ms for 96*96 texture 0
,03-15 15:00:56.438  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a3f8e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76bd498 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.448  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-15 15:00:56.458  4061  4061 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:00:56.458  4061  4061 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-15 15:00:56.458  4061  4061 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 15:00:56.468  1718  2132 W GCoreFlp: No location to return for getLastLocation()
,03-15 15:00:56.468  1718  2143 W FusedLocationProvider: location=null
,03-15 15:00:56.478  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:56.478  3838  3856 I GFX raster: took 0.562083ms for 96*96 texture 0
03-15 15:00:56.478  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76bd498 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb773f0e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.488  3838  3856 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
03-15 15:00:56.488  4041  4041 I LibraryLoader: Loading: webviewchromium
,03-15 15:00:56.488  4041  4041 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3084-3089)
03-15 15:00:56.488  4041  4041 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:00:56.498  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-15 15:00:56.498  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:56.498  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:56.498  3838  3856 I AMMetaDataParserService: Resource data:2131034113
,03-15 15:00:56.498  3436  3446 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-15 15:00:56.498  1718  3982 I GCoreUlr: Unbound from all location providers
03-15 15:00:56.498  1718  3982 I GCoreUlr: Place inference reporting - stopped
,03-15 15:00:56.508  3838  3856 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 15:00:56.508  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:00:56.508  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:56.508  3838  3856 I GFX raster: took 1.101511ms for 96*96 texture 0
03-15 15:00:56.508  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7810ae8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a6bfd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.518  3838  3856 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-15 15:00:56.528  4041  4041 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34dd576}
,03-15 15:00:56.528  4041  4041 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:00:56.538  4041  4041 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 15:00:56.538  1718  1718 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-15 15:00:56.548  1718  1718 I GCoreUlr: DispatchingService.onDestroy()
03-15 15:00:56.548  1718  1718 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-15 15:00:56.558  1718  1718 I GCoreUlr: Unbound from all location providers
,03-15 15:00:56.558  1718  1718 I GCoreUlr: Place inference reporting - stopped
03-15 15:00:56.568   290   290 E SMD     : DCD OFF
03-15 15:00:56.568  4041  4041 I BrowserStartupController: Initializing chromium process, renderers=0
03-15 15:00:56.578  4041  4041 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:00:56.608  4041  4041 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-15 15:00:56.608  4041  4041 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
03-15 15:00:56.608  4041  4041 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-15 15:00:56.618  4061  4061 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-15 15:00:56.618  1018  1078 D SettingsProvider: name = scon_is_running
,03-15 15:00:56.618  1018  1078 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 15:00:56.618  1018  1078 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 15:00:56.618  1018  1078 D SettingsProvider: selectionArgs: false
03-15 15:00:56.618  1018  1078 D SettingsProvider: selectionArgs: 10121
03-15 15:00:56.618  1018  1078 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 15:00:56.618  1018  1078 D SettingsProvider: ret = -1
03-15 15:00:56.618  4041  4041 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 15:00:56.618  4041  4041 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 15:00:56.618  4041  4041 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 15:00:56.618  4041  4041 I Adreno-EGL: Local Branch: 
03-15 15:00:56.618  4041  4041 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 15:00:56.618  4041  4041 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 15:00:56.618  4041  4041 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 15:00:56.628  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:56.628  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:56.628  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:00:56.638  1018  1078 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-15 15:00:56.638   259   453 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-15 15:00:56.638   259  1565 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-15 15:00:56.648  4061  4061 D QuickConnect: Utils.setQCRunningSetting - set : 0
,03-15 15:00:56.648  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 15:00:56.648  4061  4061 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-15 15:00:56.648  3793  3891 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-15 15:00:56.658  4061  4061 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-15 15:00:56.658  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:56.658  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.658  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:56.658  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:56.668  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-15 15:00:56.678  4096  4096 E Zygote  : MountEmulatedStorage()
03-15 15:00:56.678  4096  4096 E Zygote  : v2
03-15 15:00:56.678  4096  4096 I libpersona: KNOX_SDCARD checking this for 10127
03-15 15:00:56.678  4096  4096 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:56.678  4096  4096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:56.678  4096  4096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:56.688  4096  4096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:56.688  1018  1078 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4096 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-15 15:00:56.688  1018  1210 W ActivityManager: userId = 0, bbcId = -10000,
03-15 15:00:56.688  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:56.688  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:00:56.698  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:56.698  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:56.698  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:56.698  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:56.708  4110  4110 E Zygote  : MountEmulatedStorage()
03-15 15:00:56.708  4110  4110 E Zygote  : v2
03-15 15:00:56.708  4110  4110 I libpersona: KNOX_SDCARD checking this for 10026
03-15 15:00:56.708  4110  4110 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:56.708  4110  4110 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:56.718  4096  4096 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:56.718  1018  3627 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4110 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:00:56.718  4096  4096 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:56.718  4110  4110 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:56.718  4110  4110 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 15:00:56.738  1018  1030 I ActivityManager: Killing 3323:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,03-15 15:00:56.748  4096  4096 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 15:00:56.748  4096  4096 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
03-15 15:00:56.748  4096  4096 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-15 15:00:56.758  4096  4096 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 15:00:56.758  4110  4110 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:56.758  4110  4110 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:56.808  1018  1042 W libprocessgroup: failed to open /acct/uid_10090/pid_3323/cgroup.procs: No such file or directory
,03-15 15:00:56.808  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:56.808  3838  3856 I GFX raster: took 0.839688ms for 96*96 texture 0
03-15 15:00:56.808  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7810ae8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a6c9a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:56.838  3838  3856 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-15 15:00:56.848  4041  4041 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-15 15:00:56.848  4096  4096 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-15 15:00:56.868  4041  4091 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-15 15:00:56.878  4096  4096 D ManifestProvider: onCreate()
,03-15 15:00:56.918  4096  4096 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-15 15:00:56.938  3983  3983 I Process : Sending signal. PID: 3983 SIG: 9
,03-15 15:00:57.018  4041  4041 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:00:57.018  4041  4041 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-15 15:00:57.028  1018  3628 I ActivityManager: Process com.sec.android.app.sns3 (pid 3983)(adj 0) has died(27,683)
,03-15 15:00:57.028  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.028  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.028  3947  3964 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 15:00:57.028  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.028  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.038  4041  4041 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 15:00:57.038  4041  4041 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-15 15:00:57.038  4041  4041 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung,
,03-15 15:00:57.048  4149  4149 E Zygote  : MountEmulatedStorage()
,03-15 15:00:57.048  4149  4149 E Zygote  : v2
03-15 15:00:57.048  4149  4149 I libpersona: KNOX_SDCARD checking this for 10031
03-15 15:00:57.048  4149  4149 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:57.048  4149  4149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:57.048  4149  4149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 15:00:57.048  4149  4149 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:00:57.048  1018  1043 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4149 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,03-15 15:00:57.058  4041  4041 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 15:00:57.058  4041  4041 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:00:57.088  4149  4149 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:57.088  4149  4149 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:57.088   309   309 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 42.608ms
,03-15 15:00:57.098  4096  4096 W System.err: java.lang.NoSuchMethodException: isEnabled []
,03-15 15:00:57.108  4096  4096 W System.err: 	at java.lang.Class.getMethod(Class.java:665)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
03-15 15:00:57.108  4096  4096 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-15 15:00:57.108  4096  4096 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-15 15:00:57.108  4096  4096 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-15 15:00:57.108  4096  4096 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:00:57.108  4096  4096 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-15 15:00:57.108  4096  4096 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 15:00:57.108  4096  4096 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 15:00:57.108  4096  4096 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 15:00:57.108  4096  4096 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-15 15:00:57.108  4096  4096 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2039d302
,03-15 15:00:57.108  3947  3964 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 15:00:57.108  3947  3964 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:00:57.108  3947  3964 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:00:57.108   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 17.084ms
,03-15 15:00:57.108  4096  4096 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-15 15:00:57.108  4096  4096 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-15 15:00:57.128   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.823ms
,03-15 15:00:57.158  4041  4168 D OpenGLRenderer: Render dirty regions requested: true,
,03-15 15:00:57.158  1018  1539 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-15 15:00:57.158  1018  1539 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 15:00:57.158  1018  1539 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 15:00:57.158  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 15:00:57.158  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 15:00:57.168  4041  4041 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-15 15:00:57.168  4041  4041 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 15:00:57.178   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-15 15:00:57.188  1018  1514 D InputDispatcher: Focus entered window: 4041
,03-15 15:00:57.188  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:00:57.188  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:00:57.188  4041  4041 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 15:00:57.188  4041  4168 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 15:00:57.198  4041  4168 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-15 15:00:57.198  4041  4168 D OpenGLRenderer: Enabling debug mode 0
,03-15 15:00:57.268  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-15 15:00:57.268  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.268  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.268  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.288  4173  4173 E Zygote  : MountEmulatedStorage()
03-15 15:00:57.288  4173  4173 E Zygote  : v2
03-15 15:00:57.288  4173  4173 I libpersona: KNOX_SDCARD checking this for 10131
03-15 15:00:57.288  4173  4173 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:57.288  1018  1585 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4173 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-15 15:00:57.298  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.298  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.298  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.298  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.318  1018  1078 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,03-15 15:00:57.318  4180  4180 E Zygote  : MountEmulatedStorage(),
03-15 15:00:57.318  4180  4180 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:57.318  4180  4180 E Zygote  : v2
03-15 15:00:57.318  4180  4180 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:57.328  1018  1585 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 15:00:57.328  1018  4184 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:00:57.328  1018  1585 I ActivityManager: Killing 3362:com.sec.factory.camera/1000 (adj 15): empty #31
,03-15 15:00:57.328  1186  1186 D PanelView: There is/are notification(s) 
,03-15 15:00:57.348  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s302ms
,03-15 15:00:57.348  1018  1048 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:00:57.348  4041  4041 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3e3252bd time:43943
,03-15 15:00:57.348  1018  1048 W ActivityManager: mDVFSHelper.release()
03-15 15:00:57.348  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{726ec43 u0 com.test.thalitest/.MainActivity t11} time:43943
,03-15 15:00:57.348  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:00:57.358  4110  4110 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-15 15:00:57.368  4173  4173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:57.368  4180  4180 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:57.368  4173  4173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:57.368  4180  4180 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:57.368  4180  4180 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:00:57.368  4173  4173 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:00:57.378  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:57.378  3838  3856 I GFX raster: took 0.616354ms for 96*96 texture 0
03-15 15:00:57.378  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a72e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a6bfd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:57.388  3838  3856 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-15 15:00:57.388  1018  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-15 15:00:57.408  4180  4180 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:57.408  4173  4173 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:57.418  4180  4180 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:57.418  4173  4173 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:57.438  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 15:00:57.438  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:00:57.438  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:57.438  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:57.438  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:57.438  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:57.468  4173  4173 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 15:00:57.468  4173  4173 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:00:57.468  4173  4173 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:57.468  1854  1854 I SamsungIME: getCurrentCandidateView
,03-15 15:00:57.508  1018  2807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:00:57.548  1822  2768 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:00:57.558  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:57.558  1018  4218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-15 15:00:57.558  1018  1586 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:57.558  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 15:00:57.568   259  1565 I SurfaceFlinger: id=11 Removed uhalitest (7/8)
03-15 15:00:57.568   259   453 I SurfaceFlinger: id=11 Removed uhalitest (-2/8)
,03-15 15:00:57.578  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:57.578  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:57.578  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-15 15:00:57.578  1854  1854 D SamsungIME: Dismiss ExpandCandiate
,03-15 15:00:57.588  1018  2766 D SSRM:n  : SIOP:: AP = 410
,03-15 15:00:57.638  3495  3625 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 15:00:57.648  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:00:57.648  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.648  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.648  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.648  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.658  4223  4223 E Zygote  : MountEmulatedStorage(),
03-15 15:00:57.658  4223  4223 E Zygote  : v2
03-15 15:00:57.658  4223  4223 I libpersona: KNOX_SDCARD checking this for 10037
03-15 15:00:57.658  4223  4223 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:57.658  4223  4223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:57.668  4223  4223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-15 15:00:57.668  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-15 15:00:57.668  4223  4223 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-15 15:00:57.668  1018  1539 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4223 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:00:57.668  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:57.668  1018  1586 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:57.668  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 15:00:57.678  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.678  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.678  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.678  1018  3628 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.688  1854  1854 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 15:00:57.698  4180  4180 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-15 15:00:57.698  4223  4223 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:57.698  4223  4223 D ActivityThread: Added TimaKeyStore provider
03-15 15:00:57.698  4180  4180 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-15 15:00:57.708  4244  4244 E Zygote  : MountEmulatedStorage(),
,03-15 15:00:57.708  4244  4244 E Zygote  : v2,
03-15 15:00:57.708  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-15 15:00:57.708  4244  4244 I libpersona: KNOX_SDCARD checking this for 10135,
03-15 15:00:57.708  4244  4244 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:57.718  4180  4231 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-15 15:00:57.718  4244  4244 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:57.718  1018  3628 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4244 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-15 15:00:57.718  4180  4231 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-15 15:00:57.718  4244  4244 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:57.718  4244  4244 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:00:57.738  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3362/cgroup.procs: No such file or directory
,03-15 15:00:57.748  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-15 15:00:57.748  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-15 15:00:57.748  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-15 15:00:57.748  4244  4244 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:57.748  4244  4244 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:57.758  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-15 15:00:57.758  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-15 15:00:57.768  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-15 15:00:57.768  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-15 15:00:57.768  4180  4180 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-15 15:00:57.778  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:57.778  3838  3856 I GFX raster: took 0.631510ms for 96*96 texture 0
,03-15 15:00:57.778  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a73940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a71b20 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:57.778  4180  4180 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-15 15:00:57.778  4180  4180 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-15 15:00:57.778  4180  4180 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-15 15:00:57.788  3838  3856 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-15 15:00:57.788  4180  4180 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-15 15:00:57.788  2068  3802 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-15 15:00:57.798  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:57.798  4180  4180 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-15 15:00:57.798  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.798  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.798  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:57.798  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:57.798  3838  3856 I GFX raster: took 0.944740ms for 96*96 texture 0
,03-15 15:00:57.798  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a688e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a70840 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:57.808  3838  3856 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-15 15:00:57.828  4180  4231 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,03-15 15:00:57.828  4180  4231 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 15:00:57.838  4269  4269 E Zygote  : MountEmulatedStorage()
03-15 15:00:57.838  4269  4269 E Zygote  : v2
03-15 15:00:57.838  4269  4269 I libpersona: KNOX_SDCARD checking this for 10032
03-15 15:00:57.838  4269  4269 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:57.838  1018  3627 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4269 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:00:57.838  1018  3627 I ActivityManager: Killing 3387:com.fmm.dm/1000 (adj 15): empty #31
,03-15 15:00:57.838  4269  4269 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:57.858  4269  4269 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:57.858  4269  4269 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 15:00:57.868  4180  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-15 15:00:57.868  4180  4231 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-15 15:00:57.878  4180  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-15 15:00:57.878  1854  1854 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 15:00:57.898  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-15 15:00:57.898  4223  4223 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 15:00:57.898  4244  4244 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 15:00:57.898  4244  4244 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:00:57.908  4244  4244 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 15:00:57.908  4244  4244 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-15 15:00:57.908  4244  4244 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 15:00:57.908  4269  4269 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:57.908  4269  4269 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:57.928  1854  1854 I SamsungIME: KeybaordView init() : load resources
,03-15 15:00:57.958  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3387/cgroup.procs: No such file or directory
,03-15 15:00:57.958  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-15 15:00:57.988  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-15 15:00:57.988  4180  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-15 15:00:57.988  4180  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-15 15:00:57.988  4180  4232 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-15 15:00:57.998  4180  4232 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 15:00:57.998  4180  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-15 15:00:57.998  4180  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/15/15:00:58
,03-15 15:00:57.998  4180  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-15 15:00:57.998  4180  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-15 15:00:58.018  4110  4110 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-15 15:00:58.028  4041  4041 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-15 15:00:58.038  4180  4232 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-15 15:00:58.038  4180  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-15 15:00:58.038  4180  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-15 15:00:58.038  4180  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-15 15:00:58.038  4180  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-15 15:00:58.038  4180  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-15 15:00:58.038  4180  4232 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-15 15:00:58.058  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:58.058  3838  3856 I GFX raster: took 0.712865ms for 96*96 texture 0
03-15 15:00:58.058  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a6be10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a31000 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:58.068  4223  4223 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-15 15:00:58.068  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-15 15:00:58.078  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:58.078  3838  3856 I GFX raster: took 0.737657ms for 96*96 texture 0
03-15 15:00:58.078  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a3f8e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a6ed10 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:58.078  4110  4110 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 15:00:58.078  4110  4110 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 15:00:58.088  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-15 15:00:58.088  4180  4232 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-15 15:00:58.098  4269  4293 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-15 15:00:58.098  4269  4293 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-15 15:00:58.098  4180  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-15 15:00:58.108  1854  1854 I SamsungIME: getCurrentKeyboard
,03-15 15:00:58.108  1854  1854 I SamsungIME: getTextKeyboard
,03-15 15:00:58.108  1018  1043 I ActivityManager: Waited long enough for: ServiceRecord{34fac2a9 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,03-15 15:00:58.138  4180  4232 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-15 15:00:58.148  4110  4263 D Volley  : [618] DiskBasedCache.clear: Cache cleared.
,03-15 15:00:58.148  1018  3628 I ActivityManager: Killing 3457:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
03-15 15:00:58.148  4110  4201 D Volley  : [611] DiskBasedCache.clear: Cache cleared.
,03-15 15:00:58.148  1018  3628 I ActivityManager: Killing 3406:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #32
,03-15 15:00:58.148  4110  4296 D Ads     : Skipping gmscore version check
,03-15 15:00:58.168  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:58.168  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:58.168  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-15 15:00:58.168  4269  4269 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-15 15:00:58.198  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.198  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:58.198  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-15 15:00:58.218  4180  4232 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-15 15:00:58.228  1854  1854 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-15 15:00:58.228  4110  4110 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-15 15:00:58.228  4110  4110 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-15 15:00:58.238  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:58.238  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:58.238  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:58.238  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:58.238  4180  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-15 15:00:58.248  4299  4299 E Zygote  : MountEmulatedStorage(),
,03-15 15:00:58.258  4299  4299 E Zygote  : v2
,03-15 15:00:58.258  4299  4299 I libpersona: KNOX_SDCARD checking this for 10141
03-15 15:00:58.258  4299  4299 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:58.258  4299  4299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:58.258  4299  4299 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:58.258  4299  4299 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-15 15:00:58.258  1018  1210 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4299 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-15 15:00:58.268  4180  4231 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-15 15:00:58.288  4269  4293 D SPPClientService: PushLog.txt file is not deleted.
,03-15 15:00:58.288  4269  4293 D SPPClientService: PushLog.txt file is not deleted.
,03-15 15:00:58.288  4269  4293 D SPPClientService: ============PushLog. stop!
03-15 15:00:58.288  1018  1097 V AlarmManager: waitForAlarm result :8
,03-15 15:00:58.318  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.318  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.318  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.318  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:58.338  4317  4317 E Zygote  : MountEmulatedStorage()
03-15 15:00:58.338  4317  4317 I libpersona: KNOX_SDCARD checking this for 10036
03-15 15:00:58.338  4317  4317 E Zygote  : v2
03-15 15:00:58.338  4317  4317 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:58.338  4317  4317 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:58.348  4317  4317 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:58.348  4317  4317 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-15 15:00:58.348  1018  1210 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4317 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:00:58.348  1018  1210 I ActivityManager: Killing 3477:com.fmm.ds/1000 (adj 15): empty #31,
,03-15 15:00:58.368  4180  4232 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-15 15:00:58.388  4041  4242 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-15 15:00:58.388  4041  4242 I chromium: 
,03-15 15:00:58.418  4180  4232 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-15 15:00:58.438  4180  4232 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-15 15:00:58.438  4317  4317 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:58.448  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 15:00:58.448  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:00:58.448  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:58.448  4317  4317 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:58.448  4299  4299 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:58.448  4299  4299 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:58.448  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:58.448  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:00:58.448  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:00:58.508  4299  4299 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 15:00:58.508  4299  4299 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 15:00:58.508  4299  4299 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:58.508  4299  4299 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 15:00:58.518  1018  1522 I ActivityManager: Killing 3512:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,03-15 15:00:58.528  4110  4110 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-15 15:00:58.538  1018  3628 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:58.538  1018  3628 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 15:00:58.538  1018  3628 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-15 15:00:58.588  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:58.598  3838  3856 I GFX raster: took 0.538438ms for 96*96 texture 0
03-15 15:00:58.598  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76bd498 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a68988 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:58.598  4110  4110 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-15 15:00:58.598  1018  1042 W libprocessgroup: failed to open /acct/uid_10098/pid_3457/cgroup.procs: No such file or directory
,03-15 15:00:58.598  1018  1042 W libprocessgroup: failed to open /acct/uid_10095/pid_3406/cgroup.procs: No such file or directory
,03-15 15:00:58.608  3838  3856 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-15 15:00:58.608  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3477/cgroup.procs: No such file or directory
03-15 15:00:58.608  1018  1042 W libprocessgroup: failed to open /acct/uid_10055/pid_3512/cgroup.procs: No such file or directory
,03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:58.648  3838 , 3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: Resource data:2131034112
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-15 15:00:58.648  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:58.648  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:58.648  3838  3856 I GFX raster: took 0.671927ms for 96*96 texture 0
03-15 15:00:58.648  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a73940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a31000 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:58.658  1018  1522 D RCPManagerService: exchangeData() failure , invalid userId
03-15 15:00:58.668  1018  1586 D RCPManagerService: exchangeData() failure , invalid userId
03-15 15:00:58.668  3838  3856 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
03-15 15:00:58.668  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
03-15 15:00:58.668  4041  4333 D jxcore_app_log: JniHelper::setJavaVM(0xb76b7448), pthread_self() = -1210057848
03-15 15:00:58.678  4041  4333 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 15:00:58.678  4041  4333 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 15:00:58.678  4041  4333 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 15:00:58.678  4041  4333 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 15:00:58.678  4041  4333 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-15 15:00:58.678  4041  4333 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@227bbcb0 added. We now have 1 listener(s)
,03-15 15:00:58.688  1018  3628 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:00:58.688  4041  4333 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-15 15:00:58.688  1018  3636 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:00:58.688  4041  4333 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-15 15:00:58.688  4041  4333 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-15 15:00:58.688  4041  4333 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-15 15:00:58.688  4041  4333 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-15 15:00:58.688  4317  4317 I SA      : [SSP] onCreated
,03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-15 15:00:58.698  4041  4333 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901d04f added. We now have 1 listener(s)
,03-15 15:00:58.698  4041  4333 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 15:00:58.708  4041  4333 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-15 15:00:58.718  4041  4333 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-15 15:00:58.718  4041  4333 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-15 15:00:58.718  4041  4333 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-15 15:00:58.718  4041  4333 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-15 15:00:58.718  4041  4333 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-15 15:00:58.718  4041  4333 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 15:00:58.728  4041  4333 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-15 15:00:58.728  4041  4333 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 15:00:58.728  4041  4333 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 15:00:58.728  4041  4041 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 15:00:58.738  4041  4041 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 15:00:58.738  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:00:58.748  4317  4317 I SA      : [TPM] There is no property file
,03-15 15:00:58.748  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:58.748  3838  3856 I GFX raster: took 0.603906ms for 96*96 texture 0
03-15 15:00:58.748  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a73940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a6ab58 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:58.758  1018  1078 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:00:58.758  1018  2738 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:58.758  1018  2738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:58.758  1018  2738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-15 15:00:58.768  4317  4317 I SA      : [SCU] isHaveSA() - false
,03-15 15:00:58.778  4317  4317 I SA      : [TPM] getModelProperty : null
,03-15 15:00:58.778  4317  4317 I SA      : [TPM] getCSCProperty : null
03-15 15:00:58.778  4317  4317 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-15 15:00:58.778  4317  4317 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-15 15:00:58.778  4317  4317 I SA      : [DM] TFT FEATURE: false
,03-15 15:00:58.778  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:58.788  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.788  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.788  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.788  3838  3856 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
03-15 15:00:58.788  4317  4317 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0,
03-15 15:00:58.788  4317  4317 I SA      : [DM] init START
03-15 15:00:58.798  4041  4041 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-15 15:00:58.798  4317  4317 I SA      : [DM] This device is not a Vodafone
03-15 15:00:58.808  1018  2738 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4356 uid=10068 gids={50068, 9997} abi=armeabi-v7a
03-15 15:00:58.818  4356  4356 E Zygote  : MountEmulatedStorage()
03-15 15:00:58.818  4356  4356 E Zygote  : v2
03-15 15:00:58.818  4356  4356 I libpersona: KNOX_SDCARD checking this for 10068
03-15 15:00:58.818  4356  4356 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:58.818  4356  4356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:58.818  4356  4356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:58.828  4356  4356 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 15:00:58.838  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.838  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.838  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:58.838  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:58.848  4317  4317 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-15 15:00:58.858  4317  4317 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-15 15:00:58.858  4317  4317 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-15 15:00:58.858  4317  4317 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-15 15:00:58.858  4317  4317 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
03-15 15:00:58.858  4317  4317 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-15 15:00:58.858  4317  4317 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-15 15:00:58.868  4371  4371 E Zygote  : MountEmulatedStorage(),
03-15 15:00:58.868  4317  4317 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-15 15:00:58.868  1018  1521 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4371 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-15 15:00:58.868  4317  4317 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75),
03-15 15:00:58.868  4371  4371 E Zygote  : v2
03-15 15:00:58.868  4371  4371 I libpersona: KNOX_SDCARD checking this for 10142
03-15 15:00:58.868  4371  4371 I libpersona: KNOX_SDCARD not a persona,
,03-15 15:00:58.878  4371  4371 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-15 15:00:58.878  1018  1521 I ActivityManager: Killing 3535:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
03-15 15:00:58.878  4317  4317 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75),
,03-15 15:00:58.878  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-15 15:00:58.878  3838  3856 I GFX raster: took 0.670416ms for 96*96 texture 0
03-15 15:00:58.878  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a68b20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a68bc8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:58.888  4371  4371 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 15:00:58.888  4356  4356 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-15 15:00:58.888  4356  4356 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:58.888  4371  4371 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-15 15:00:58.908  1018  1587 I ActivityManager: Killing 3278:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,03-15 15:00:58.928  4371  4371 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:58.928  4371  4371 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:58.938  3838  3856 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-15 15:00:58.938  4317  4317 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-15 15:00:58.938  4317  4317 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-15 15:00:58.948  4317  4317 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-15 15:00:58.978  4317  4317 I SA      : [SCU] isHaveSA() - false
03-15 15:00:58.978  4317  4317 I SA      : support phone number id : false
03-15 15:00:58.978  4317  4317 I SA      : [DM] Supports Ref Jpn : true
,03-15 15:00:58.978  4317  4317 I SA      : [DM] init END
,03-15 15:00:58.988  4371  4371 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 15:00:58.998  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:58.998  3838  3856 I GFX raster: took 0.793490ms for 96*96 texture 0
03-15 15:00:58.998  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a30f78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7810ae8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.008  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-15 15:00:59.088  1018  3636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-15 15:00:59.088  1018  3636 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-15 15:00:59.088  1018  3636 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-15 15:00:59.088  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-15 15:00:59.098  1018  1018 I MotionRecognitionService: Plugged
,03-15 15:00:59.098  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-15 15:00:59.098  1186  1186 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-15 15:00:59.098  1186  1186 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-15 15:00:59.108  1460  1460 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-15 15:00:59.108  1460  1460 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-15 15:00:59.128  1186  1186 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 15:00:59.128  1186  1186 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 15:00:59.128  1186  1186 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 15:00:59.128  1186  1186 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-15 15:00:59.128  1186  1186 D SViewCoverView: level :100 plugged : 2
,03-15 15:00:59.128  2646  2646 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-15 15:00:59.128  2646  2743 D HeadsetStateMachine: Disconnected process message: 10
,03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-15 15:00:59.128  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsun,g.contacts.emergency.EmergencyMessageContactCreateActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: Resource data:2131034113
03-15 15:00:59.138  1018  1030 I art     : Explicit concurrent mark sweep GC freed 27795(1513KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 22MB/33MB, paused 3.338ms total 187.322ms
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 15:00:59.138  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:59.148  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:59.148  3838  3856 I GFX raster: took 0.832240ms for 96*96 texture 0
03-15 15:00:59.148  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a6af78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a4cdb8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 15:00:59.158  4317  4317 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-15 15:00:59.158  4317  4317 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
03-15 15:00:59.168  3838  3856 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-15 15:00:59.178  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:59.178  1018  1521 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,03-15 15:00:59.188  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
03-15 15:00:59.188  1018  1097 V AlarmManager: waitForAlarm result :4
03-15 15:00:59.188  1018  1042 W libprocessgroup: failed to open /acct/uid_10056/pid_3535/cgroup.procs: No such file or directory
03-15 15:00:59.188  1018  1042 W libprocessgroup: failed to open /acct/uid_10008/pid_3278/cgroup.procs: No such file or directory
,03-15 15:00:59.188  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:59.188  3838  3856 I GFX raster: took 0.820989ms for 96*96 texture 0
03-15 15:00:59.188  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a6af78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7810ae8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.198  4317  4317 I SA      : [OR] onReceive END
,03-15 15:00:59.198  3838  3856 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-15 15:00:59.218  4356  4356 D BadgeProvider: onCreate
03-15 15:00:59.218  4356  4356 D BadgeProvider: DatabaseHelper
,03-15 15:00:59.228  1018  3636 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:00:59.238  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:00:59.238  1018  1586 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:59.238  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-15 15:00:59.248  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.248  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.248  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.248  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:59.248  4356  4365 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-15 15:00:59.258  4395  4395 E Zygote  : MountEmulatedStorage()
,03-15 15:00:59.258  4395  4395 E Zygote  : v2
,03-15 15:00:59.258  4395  4395 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:59.258  1018  1585 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4395 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 15:00:59.258  4395  4395 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:59.268  4395  4395 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:59.268  4395  4395 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:59.268  4395  4395 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:00:59.288  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:59.288  3838  3856 I GFX raster: took 0.745208ms for 96*96 texture 0
,03-15 15:00:59.288  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a4cdb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7810ae8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.308  1018  1031 I ActivityManager: Killing 3558:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,03-15 15:00:59.308  4395  4395 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:59.308  4395  4395 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:59.308  4317  4317 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 15:00:59.308  4317  4317 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-15 15:00:59.318  3838  3856 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-15 15:00:59.338  4356  4365 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-15 15:00:59.338  1524  1524 D Launcher.Model: reloadBadges entered.
03-15 15:00:59.338  4356  4365 D BadgeProvider: sendNotify, [notify] : null
,03-15 15:00:59.338  4356  4365 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,03-15 15:00:59.338  4356  4365 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-15 15:00:59.338  4356  4365 D BadgeProvider: update, [UpdateCount] : 1
,03-15 15:00:59.358  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:59.358  3838  3856 I GFX raster: took 0.628385ms for 96*96 texture 0
03-15 15:00:59.358  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7810ae8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a7d6f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.378  4317  4317 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-15 15:00:59.378  4317  4317 I SA      : [LBE] REF_JPN : true
03-15 15:00:59.378  4317  4317 I SA      : [BDC] create
,03-15 15:00:59.378  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:59.378  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:59.378  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-15 15:00:59.378  3838  3856 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-15 15:00:59.378  1018  1514 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-15 15:00:59.388  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:59.388  3838  3856 I GFX raster: took 0.826511ms for 96*96 texture 0
03-15 15:00:59.388  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a491e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77ae228 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.398  3838  3856 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-15 15:00:59.418  1018  1042 W libprocessgroup: failed to open /acct/uid_10013/pid_3558/cgroup.procs: No such file or directory
,03-15 15:00:59.438  1018  1539 W ActivityManager: getTasks: caller 10142 does not hold GET_TASKS; limiting output
,03-15 15:00:59.438  1018  1210 W ActivityManager: getTasks: caller 10141 does not hold GET_TASKS; limiting output
,03-15 15:00:59.448  4317  4317 I SA      : [DBMV2] getEmailID
,03-15 15:00:59.448  1018  1587 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-15 15:00:59.458  4299  4354 I Process : Sending signal. PID: 4299 SIG: 9
,03-15 15:00:59.458  4371  4409 I Process : Sending signal. PID: 4371 SIG: 9
,03-15 15:00:59.468  4317  4317 I SA      : [DBMV2] getDataV02ForItems
,03-15 15:00:59.468  4317  4317 I SA      : [SSP] query invoked
,03-15 15:00:59.488  4317  4317 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-15 15:00:59.498  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.498  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.498  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.498  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:59.508  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:59.508  3838  3856 I GFX raster: took 0.663489ms for 96*96 texture 0
03-15 15:00:59.508  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a30f78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76bd498 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.508  4414  4414 E Zygote  : MountEmulatedStorage()
03-15 15:00:59.508  4414  4414 E Zygote  : v2
03-15 15:00:59.508  4414  4414 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:00:59.508  4414  4414 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:59.508  4414  4414 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:00:59.508  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-15 15:00:59.508  4414  4414 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:00:59.508  4414  4414 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:59.518  1018  3627 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4414 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:00:59.518   256   256 E lowmemorykiller: Error writing /proc/4371/oom_score_adj; errno=22
03-15 15:00:59.518   256   256 E lowmemorykiller: Error writing /proc/4299/oom_score_adj; errno=22
03-15 15:00:59.518  1018  3627 I ActivityManager: Killing 3582:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-15 15:00:59.528  1018  1030 I ActivityManager: Process com.android.exchange (pid 4371)(adj 11) has died(42,622)
,03-15 15:00:59.528   256   256 E lowmemorykiller: Error writing /proc/4299/oom_score_adj; errno=22
,03-15 15:00:59.538   309   309 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 28.060ms
03-15 15:00:59.538  4317  4317 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-15 15:00:59.538  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 15:00:59.538  3838  3856 I GFX raster: took 0.671146ms for 96*96 texture 0
03-15 15:00:59.538  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a6cb60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a7d6f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.548  4317  4317 I SA      : [BDC] destroy
03-15 15:00:59.548   256   256 E lowmemorykiller: Error writing /proc/4299/oom_score_adj; errno=22
,03-15 15:00:59.548  4414  4414 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:00:59.548  4414  4414 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:59.558   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 19.491ms
,03-15 15:00:59.558  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-15 15:00:59.568   290   290 E SMD     : DCD OFF
,03-15 15:00:59.578   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 687us total 16.654ms
,03-15 15:00:59.578  1018  1514 I ActivityManager: Process com.android.email (pid 4299)(adj 13) has died(40,623)
,03-15 15:00:59.578  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 15:00:59.588  3838  3856 I GFX raster: took 0.676562ms for 96*96 texture 0
03-15 15:00:59.588  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76bd498 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a7d6f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 15:00:59.588  3838  3856 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-15 15:00:59.588  1018  1042 W libprocessgroup: failed to open /acct/uid_10058/pid_3582/cgroup.procs: No such file or directory
,03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-15 15:00:59.618  3838  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 15:00:59.618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-15 15:00:59.,618  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
03-15 15:00:59.628  4414  4414 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 15:00:59.628  4414  4414 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 15:00:59.628  4414  4414 D SecurityLogAgent: StateMachine : Current State = 1
03-15 15:00:59.628  4414  4414 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
03-15 15:00:59.638  2068  4391 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 421 ms
03-15 15:00:59.638  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.638  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.638  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.638  1018  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:00:59.648  3838  3856 I AMMetaDataParserService: Resource data:2131165203
03-15 15:00:59.648  4430  4430 E Zygote  : MountEmulatedStorage()
03-15 15:00:59.648  4430  4430 I libpersona: KNOX_SDCARD checking this for 10148
03-15 15:00:59.648  4430  4430 E Zygote  : v2
03-15 15:00:59.648  4430  4430 I libpersona: KNOX_SDCARD not a persona
03-15 15:00:59.648  4430  4430 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:00:59.648  3838  3856 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 15:00:59.648  3838  3856 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:00:59.658  3838  3856 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-15 15:00:59.648  3838  3856 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:00:59.658  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
03-15 15:00:59.648  3838  3856 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:00:59.658  1018  1514 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4430 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
03-15 15:00:59.658  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-15 15:00:59.658  4430  4430 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:00:59.668  4430  4430 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:00:59.668  3838  3856 I GFX construct_block_size_descriptor_2d second part: took 3.863698ms for 0*0 texture 0
03-15 15:00:59.668  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-15 15:00:59.698  4430  4430 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:59.698  4430  4430 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:59.708  3838  3856 I GFX generate_partition_tables: took 17.390155ms for 0*0 texture 0
,03-15 15:00:59.708  3838  3856 I GFX raster: took 21.902394ms for 80*80 texture 0
03-15 15:00:59.708  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7a71f20 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb7dd9750 counterpartCT=4 counterpartW=80 counterparth=80
,03-15 15:00:59.708  3838  3856 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-15 15:00:59.718  1018  2738 I ActivityManager: Killing 3305:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,03-15 15:00:59.718  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-15 15:00:59.718  3838  3856 I GFX construct_block_size_descriptor_2d second part: took 2.539479ms for 0*0 texture 0
,03-15 15:00:59.728  3838  3856 I GFX generate_partition_tables: took 5.406769ms for 0*0 texture 0
,03-15 15:00:59.728  3838  3856 I GFX raster: took 9.142395ms for 80*80 texture 0
03-15 15:00:59.728  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7de0728 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7de0760 counterpartCT=4 counterpartW=80 counterparth=80
,03-15 15:00:59.738  3838  3856 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 15:00:59.768  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-15 15:00:59.778  3838  3856 I GFX raster: took 0.837656ms for 80*80 texture 0
,03-15 15:00:59.778  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7de0728 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7f890f0 counterpartCT=4 counterpartW=80 counterparth=80
,03-15 15:00:59.788  3838  3856 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 15:00:59.798  4430  4430 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-15 15:00:59.798  1018  1042 W libprocessgroup: failed to open /acct/uid_10014/pid_3305/cgroup.procs: No such file or directory
,03-15 15:00:59.808  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-15 15:00:59.808  3838  3856 I GFX raster: took 0.781510ms for 80*80 texture 0
03-15 15:00:59.808  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7de0728 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7de04a0 counterpartCT=4 counterpartW=80 counterparth=80
,03-15 15:00:59.808  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:59.808  1018  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:00:59.808  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-15 15:00:59.818  3838  3856 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 15:00:59.828  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.828  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.828  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:00:59.828  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:00:59.838  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80,
03-15 15:00:59.838  3838  3856 I GFX raster: took 0.619322ms for 80*80 texture 0
03-15 15:00:59.838  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ddfcd0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7ddfd78 counterpartCT=4 counterpartW=80 counterparth=80
,03-15 15:00:59.838  1018  3627 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4448 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 15:00:59.848  4448  4448 E Zygote  : MountEmulatedStorage(),
03-15 15:00:59.848  4448  4448 E Zygote  : v2
03-15 15:00:59.848  4448  4448 I libpersona: KNOX_SDCARD checking this for 1000,
03-15 15:00:59.848  4448  4448 I libpersona: KNOX_SDCARD not a persona
,03-15 15:00:59.848  4448  4448 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-15 15:00:59.858  4448  4448 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 15:00:59.858  4448  4448 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:00:59.898  2068  3802 I Icing   : Internal init done: storage state 0
,03-15 15:00:59.898  4448  4448 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:00:59.898  4448  4448 D ActivityThread: Added TimaKeyStore provider
,03-15 15:00:59.908  3838  3856 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-15 15:00:59.928  3838  3856 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-15 15:00:59.928  3838  3856 I GFX raster: took 0.621302ms for 80*80 texture 0
03-15 15:00:59.928  3838  3856 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ddfcd0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7de0728 counterpartCT=4 counterpartW=80 counterparth=80
,03-15 15:00:59.928  3838  3856 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-15 15:00:59.938  2068  3802 I Icing   : Post-init done
,03-15 15:00:59.968  1018  1522 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-15 15:00:59.968  1018  1522 I ActivityManager: Killing 1399:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-15 15:00:59.968  3838  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-15 15:00:59.968  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-15 15:00:59.978  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:00:59.978  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:00:59.978  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:00:59.988  1018  1097 V AlarmManager: waitForAlarm result :8
,03-15 15:00:59.998  1186  1186 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-15 15:00:59.998  1186  1186 D KeyguardUpdateMonitor: handleTimeUpdate
,03-15 15:01:00.008  3436  3436 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-15 15:01:00.008  3436  3436 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 15:01:00.008  3436  3436 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-15 15:01:00.008  3436  3436 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:00.018  1018  1521 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
03-15 15:01:00.018  1186  1186 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-15 15:01:00.018  1018  1521 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-15 15:01:00.018  1186  1186 D SecKeyguardClockView: HomeTimezone(): 1
03-15 15:01:00.018  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:00.018  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:00.018  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:00.018  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.028  1186  1186 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.028  1186  1186 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-15 15:01:00.028  1186  1186 I KeyguardEffectViewController: *** don't update sliding image ***
,03-15 15:01:00.028  4465  4465 E Zygote  : MountEmulatedStorage()
03-15 15:01:00.028  4465  4465 E Zygote  : v2
03-15 15:01:00.028  4465  4465 I libpersona: KNOX_SDCARD checking this for 10108
03-15 15:01:00.028  4465  4465 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:00.038  4465  4465 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:00.038  4465  4465 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:00.038  4465  4465 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 15:01:00.038  1018  1521 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4465 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:01:00.038  1018  1521 I ActivityManager: Killing 3638:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:00.048  3838  3856 I AMMetaDataParserService: Resource data:2131099648
,03-15 15:01:00.058  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:00.058  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:00.058  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:00.058  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.058  1778  1778 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 15:01:00.058  3838  3856 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-15 15:01:00.058  3838  3856 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:00.058  3838  3856 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:00.058  3838  3856 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:01:00.058  3838  3856 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 15:01:00.058  3838  3856 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-15 15:01:00.058  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:00.068  3608  3608 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 15 15:01:00 GMT+01:00 2016
,03-15 15:01:00.078  4465  4465 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:00.078  4465  4465 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:00.088  4481  4481 E Zygote  : MountEmulatedStorage()
03-15 15:01:00.088  4481  4481 I libpersona: KNOX_SDCARD checking this for 10141
03-15 15:01:00.088  4481  4481 E Zygote  : v2
03-15 15:01:00.088  4481  4481 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:00.088  4481  4481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:00.088  1018  1043 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4481 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
03-15 15:01:00.088  4481  4481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:00.088  4481  4481 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:00.098  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:00.098  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:00.098  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:00.098  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 15:01:00.118  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:00.118  1018  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:00.118  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 15:01:00.128  1186  1186 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.138  1186  1186 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.138  3608  3608 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-15 15:01:00.138  1186  1186 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.148  3608  3608 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-15 15:01:00.148  3608  3608 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 15:01:00.148  1822  1834 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,03-15 15:01:00.148  3608  3608 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 15:01:00.148  3608  4497 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-15 15:01:00.148  4481  4481 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:00.148  3608  4497 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
03-15 15:01:00.148  4481  4481 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:00.158  3838  3856 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 15:01:00.168  3608  4497 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-15 15:01:00.168  3608  4497 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,03-15 15:01:00.178  3608  4497 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,03-15 15:01:00.178  1186  1186 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-15 15:01:00.188  1778  1778 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-15 15:01:00.188  1778  1778 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-15 15:01:00.188  1778  1778 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-15 15:01:00.188  1778  1778 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-15 15:01:00.188  4180  4180 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:00.208  3608  4497 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,03-15 15:01:00.208  4481  4481 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 15:01:00.208  4481  4481 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:00.208  4481  4481 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:00.208  4481  4481 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 15:01:00.218  3608  4497 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,03-15 15:01:00.218  4180  4499 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 15:01:00.218  3608  3608 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-15 15:01:00.228  4269  4269 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-15 15:01:00.228  4041  4348 W jxcore-log: Initializing JXcore engine
03-15 15:01:00.228  4041  4348 W jxcore-log: JXcore engine is ready
,03-15 15:01:00.228  4317  4317 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-15 15:01:00.228  4317  4317 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-15 15:01:00.228  4317  4317 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-15 15:01:00.238  4317  4317 I SA      : [SLFUCHKMGR] constructor called
,03-15 15:01:00.248  1778  1778 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,03-15 15:01:00.248  1778  1778 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-15 15:01:00.248  1778  1778 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-15 15:01:00.248  3838  3856 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 15:01:00.268  1778  1778 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! ,
03-15 15:01:00.268  1778  1778 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-15 15:01:00.268  1778  1778 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-15 15:01:00.268  1778  1778 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,03-15 15:01:00.268  1778  1778 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-15 15:01:00.268  1778  1778 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-15 15:01:00.278  1778  1778 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 01,
03-15 15:01:00.278  4180  4499 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-15 15:01:00.288  1778  1778 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 15:01:00.288  1778  1778 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 15:01:00.298  4180  4499 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-15 15:01:00.298  1186  1186 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 15:01:00.298  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.298  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.298  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.298  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.318  4501  4501 E Zygote  : MountEmulatedStorage(),
03-15 15:01:00.318  4501  4501 I libpersona: KNOX_SDCARD checking this for 10077
03-15 15:01:00.318  4501  4501 E Zygote  : v2
03-15 15:01:00.318  4501  4501 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:00.318  1928  1928 E audit   : type=1400 msg=audit(1458050460.308:205): avc:  denied  { ioctl } for  pid=4348 comm="Thread-612" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-15 15:01:00.318  1928  1928 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:00.318  1928  1928 E audit   : type=1300 msg=audit(1458050460.308:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=92cdb8f8 items=0 ppid=309 ppcomm=main pid=4348 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-612" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-15 15:01:00.318  1928  1928 E audit   : type=1320 msg=audit(1458050460.308:205): 
,03-15 15:01:00.318  4180  4499 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:00.328  1018  1522 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4501 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:00.328  4041  4348 W jxcore-log: Starting JXcore engine
,03-15 15:01:00.328  4501  4501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-15 15:01:00.328  4501  4501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:01:00.338  4501  4501 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-15 15:01:00.358  4501  4501 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:00.368  4501  4501 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:00.368  3838  3856 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 15:01:00.378  4180  4499 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 15:01:00.378  4223  4223 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-15 15:01:00.388  1018  3636 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:00.388  1018  3636 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:00.388  1018  3636 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-15 15:01:00.388  1018  3627 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:00.398  4317  4317 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-15 15:01:00.398  4317  4317 I SA      : [OR] == isSIMCardReady false ==
,03-15 15:01:00.398  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 15:01:00.408  1018  1587 D RCPManagerService: exchangeData() failure , invalid userId,
,03-15 15:01:00.408  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts,
03-15 15:01:00.408  4317  4317 I SA      : [SCU] == networkStateCheck == true,
03-15 15:01:00.408  4317  4317 I SA      : [DM] getCountryCodeFromCSC : PL
03-15 15:01:00.408  4317  4317 I SA      : isChinaCountryCode : false
03-15 15:01:00.408  4317  4317 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-15 15:01:00.408  4317  4317 I SA      : [OR] == networkStateCheck true ==,
,03-15 15:01:00.418  4317  4317 I SA      : [OR] GetMyCountryZoneTask
,03-15 15:01:00.418  4317  4317 I SA      : [OR] onReceive END
,03-15 15:01:00.418  1018  1539 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:00.428  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 15:01:00.428  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-15 15:01:00.428  1018  1078 I ActivityManager: Killing 3656:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,03-15 15:01:00.428  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 15:01:00.428  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 15:01:00.428  4180  4499 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-15 15:01:00.428  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:00.438  1218  1218 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:00.438  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:00.438  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:00.438  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 15:01:00.438  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-15 15:01:00.448  4180  4499 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-15 15:01:00.448  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 15:01:00.458  1018  1585 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-15 15:01:00.458  1018  1585 D SecContentProvider2: mCursor = null
,03-15 15:01:00.458  4041  4348 W jxcore-log: Platform android
03-15 15:01:00.458  4041  4348 W jxcore-log: 
,03-15 15:01:00.458  4041  4348 W jxcore-log: Process ARCH arm
03-15 15:01:00.458  4041  4348 W jxcore-log: 
,03-15 15:01:00.498  4180  4499 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 15:01:00.498  4180  4499 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-15 15:01:00.508  4317  4521 I SA      : [SRS] prepareGetMyCountryZone
,03-15 15:01:00.528  3838  3856 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 15:01:00.548  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:00.548  1018  1210 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:00.558  4356  4411 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-15 15:01:00.558  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:00.558  4317  4521 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 15:01:00.558  4317  4521 I SA      : [SSP] query invoked
03-15 15:01:00.558  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 15:01:00.558  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:00.568  4317  4521 I SA      : [TPMU] GetMccFromDB : null
,03-15 15:01:00.588  4317  4521 I SA      : [SCU] getMccFromPreferece mcc = 260
03-15 15:01:00.588  4317  4521 I SA      : [TPM] isNoProxy(default) : true
,03-15 15:01:00.678  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-15 15:01:00.698  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-15 15:01:00.698  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-15 15:01:00.698  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:00.698  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:00.698  3838  3856 I AMMetaDataParserService: Resource data:2131099648
,03-15 15:01:00.698  3838  3856 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:01:00.698  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:00.698  4356  4365 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-15 15:01:00.698  4356  4365 D BadgeProvider: sendNotify, [notify] : null
03-15 15:01:00.698  4356  4365 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-15 15:01:00.698  4356  4365 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-15 15:01:00.698  4356  4365 D BadgeProvider: update, [UpdateCount] : 1
03-15 15:01:00.698  1524  1524 D Launcher.Model: reloadBadges entered.
,03-15 15:01:00.708  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 15:01:00.758  4465  4465 I MusicStore: Database version: 104
,03-15 15:01:00.808  4317  4521 E File    : fail readDirectory() errno=2
,03-15 15:01:00.818  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:00.818  1018  1042 W libprocessgroup: failed to open /acct/uid_10003/pid_1399/cgroup.procs: No such file or directory
03-15 15:01:00.818  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3638/cgroup.procs: No such file or directory
03-15 15:01:00.818  1018  1585 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-15 15:01:00.828  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 15:01:00.828  1018  1042 W libprocessgroup: failed to open /acct/uid_10020/pid_3656/cgroup.procs: No such file or directory
,03-15 15:01:00.828  3838  3856 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 15:01:00.838  4414  4414 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 15:01:00.838  4414  4414 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 15:01:00.838  4414  4414 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 15:01:00.838  4414  4414 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-15 15:01:00.838  1018  1539 I ActivityManager: Killing 3696:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-15 15:01:00.868  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:00.868  1018  1586 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:00.868  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:00.908  2068  4536 I iu.SyncManager: SYNC; picasa accounts
,03-15 15:01:00.958  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3696/cgroup.procs: No such file or directory
,03-15 15:01:00.988  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.988  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.988  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.988  1018  3627 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:00.988  4041  4348 I jxcore-log: JXcore Cordova bridge is ready!
03-15 15:01:00.988  4041  4348 I jxcore-log: 
03-15 15:01:00.988  4041  4348 W jxcore-log: JXcore engine is started
,03-15 15:01:00.988  2068  2068 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-15 15:01:00.998  2068  2068 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-15 15:01:00.998  4041  4333 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-15 15:01:00.998  2068  4536 I iu.UploadsManager: num queued entries: 0
03-15 15:01:00.998  2068  4536 I iu.UploadsManager: num updated entries: 0
03-15 15:01:00.998  4538  4538 E Zygote  : MountEmulatedStorage(),
03-15 15:01:00.998  4538  4538 E Zygote  : v2
03-15 15:01:00.998  4538  4538 I libpersona: KNOX_SDCARD checking this for 10110
03-15 15:01:00.998  2068  4536 I iu.SyncManager: NEXT; no task
03-15 15:01:00.998  4538  4538 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:00.998  4538  4538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-15 15:01:01.008  1018  3627 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4538 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:01:01.008  4538  4538 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:01.008  1018  3627 I ActivityManager: Killing 3682:com.wssnps/1000 (adj 15): empty #31
03-15 15:01:01.008  4538  4538 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 15:01:01.018  4041  4348 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-15 15:01:01.018  4041  4348 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-15 15:01:01.028  4041  4041 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-15 15:01:01.038  4538  4538 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:01.038  3838  3856 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-15 15:01:01.038  4538  4538 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:01.038  1018  1522 D FocusedStackFrame: Set to : 0
,03-15 15:01:01.048  3838  3856 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 15:01:01.058  1018  1522 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-15 15:01:01.058  1018  1522 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-15 15:01:01.058  1018  1522 D InputDispatcher: Focused application set to: xxxx
,03-15 15:01:01.058  1018  1522 D InputDispatcher: Focus left window: 4041
,03-15 15:01:01.058  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 15:01:01.068  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:01.068   259   451 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
,03-15 15:01:01.068  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 15:01:01.078  3838  3856 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: Resource data:2131099648
,03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:01:01.088  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:01.098  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 15:01:01.108  4041  4333 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 70ms. Plugin should use CordovaInterface.getThreadPool().
,03-15 15:01:01.118  3838  3856 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 15:01:01.118  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3682/cgroup.procs: No such file or directory
,03-15 15:01:01.128  3838  3856 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 15:01:01.128  1018  3628 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:01:01.128  1018  3628 W ActivityManager: mDVFSHelper.acquire()
,03-15 15:01:01.138  1018  3628 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 15:01:01.138  1018  3628 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 15:01:01.138  1018  3628 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 15:01:01.148  1524  1524 D Launcher: onRestart, Launcher: 540660482
,03-15 15:01:01.158  3838  3856 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 15:01:01.168  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-15 15:01:01.168  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-15 15:01:01.168  1018  1018 D SensorService: [SO] activate (ident=0xb7eaf3d0, enabled=0)
03-15 15:01:01.168  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 15:01:01.168  1018  3628 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.168  1018  3628 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:01.168  1018  3628 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:01.188  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.188  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.188  1018  1018 D SensorManager: unregisterListener ::   
03-15 15:01:01.188  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.188  1018  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:01.188  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-15 15:01:01.188  1018  1018 D SensorService: [SO] changed settle time [0]
03-15 15:01:01.188  1018  1018 D SensorService: [SO] setDelay [200000000]
03-15 15:01:01.188  1018  1018 D SensorService: [SO] activate (ident=0xb7eaf3d0, enabled=1)
03-15 15:01:01.188  1018  1018 D SensorService: [SO] AR_init
03-15 15:01:01.188  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-15 15:01:01.188  3838  3856 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 15:01:01.198  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-15 15:01:01.208  4554  4554 E Zygote  : MountEmulatedStorage(),
,03-15 15:01:01.208  4554  4554 E Zygote  : v2
03-15 15:01:01.208  4554  4554 I libpersona: KNOX_SDCARD checking this for 10009
03-15 15:01:01.208  4554  4554 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:01.208  4554  4554 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-15 15:01:01.208  4554  4554 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:01.208  1018  1078 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4554 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-15 15:01:01.208  4554  4554 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 15:01:01.218  1524  1524 D Launcher: onStart, Launcher: 540660482
03-15 15:01:01.218  1524  1524 D Launcher.HomeView: onStart
03-15 15:01:01.218  1524  1524 D Launcher: onResume, Launcher: 540660482
03-15 15:01:01.218  1018  1031 D SettingsProvider: name = kids_home_mode
03-15 15:01:01.218  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 15:01:01.218  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 15:01:01.218  1018  1031 D SettingsProvider: selectionArgs: false
03-15 15:01:01.218  1018  1031 D SettingsProvider: selectionArgs: 10006
03-15 15:01:01.218  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 15:01:01.218  1018  1031 D SettingsProvider: ret = -1
03-15 15:01:01.218  1524  1524 D Launcher.HomeView: onResume
,03-15 15:01:01.218  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-15 15:01:01.218  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:01.218  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:01.218  3838  3856 I AMMetaDataParserService: Resource data:2131099648
,03-15 15:01:01.228  1524  1524 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-15 15:01:01.228  3838  3856 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:01:01.228  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:01.228  1524  1524 D MenuAppsGridFragment: onResume
03-15 15:01:01.228  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 15:01:01.228  1018  1078 D ActivityManager: handle home activity for 0
03-15 15:01:01.228  1018  1078 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-15 15:01:01.228  1018  1078 D KnoxTimeoutHandler: post home show event for user 0
03-15 15:01:01.228  1018  1078 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 15:01:01.228  1018  1078 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 15:01:01.228  1018  1078 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 15:01:01.228  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-15 15:01:01.228  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-15 15:01:01.228  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-15 15:01:01.238   259   259 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,03-15 15:01:01.238  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 15:01:01.238  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 15:01:01.248  1018  1585 D InputDispatcher: Focus entered window: 1524
,03-15 15:01:01.248  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:01:01.248  1524  1524 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-15 15:01:01.248  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 15:01:01.248  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:01.258  4465  4465 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 15:01:01.258  4465  4465 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 15:01:01.258  3838  3856 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 15:01:01.268  4554  4554 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:01.268  4554  4554 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:01.278  1524  1524 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 15:01:01.278  1018  3628 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 15:01:01.278  1186  1186 D PanelView: There is/are notification(s) 
,03-15 15:01:01.288  4041  4041 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-15 15:01:01.288  1018  4571 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:01:01.288  1854  1854 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 15:01:01.298  4180  4231 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:01.298  3838  3856 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 15:01:01.318  1524  1813 W OpenGLRenderer: SFEffectCache::get: create texture(0xa342a724): name, size, mSize = 34, 78200, 207056
,03-15 15:01:01.328  1524  1524 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@109be989 time:47924
,03-15 15:01:01.328  4180  4231 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 15:01:01.328  1018  1048 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:01.328  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 15:01:01.328  4465  4465 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 15:01:01.328  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 15:01:01.338  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 15:01:01.338  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 15:01:01.338  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 15:01:01.338  4180  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 15:01:01.348  1018  1048 I ActivityManager: Displayed Component not be shown by security: +211ms
,03-15 15:01:01.398  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 15:01:01.428  3838  3856 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 15:01:01.448  4465  4465 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 15:01:01.448  4465  4465 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f563f6a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 15:01:01.448  4465  4465 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-15 15:01:01.448  4465  4465 D AndroidMusic: GMSCore installation verified
,03-15 15:01:01.488  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 15:01:01.518  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.518  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:01.518  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:01.518  4554  4554 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-15 15:01:01.528  4465  4465 I ConfigStore: Config Database version: 1
,03-15 15:01:01.598  1018  1040 D SensorService: [SO] currT = 48191092000, prevT = 47751084000, diff = 440008000, [-0.460 0.211 9.883]
,03-15 15:01:01.598  1018  1040 D SensorService: [SO] -0.460 0.211 9.883
03-15 15:01:01.598  1018  1040 D SensorService: [SO] [100 -> 255]
,03-15 15:01:01.628  1018  1043 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:01:01.628  1018  1043 W ActivityManager: mDVFSHelper.release()
,03-15 15:01:01.628  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:01:01.658  4554  4554 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-15 15:01:01.658  1018  1587 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-15 15:01:01.678   258   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 15:01:01.678   258   509 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:01.678  4465  4465 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
03-15 15:01:01.678  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-15 15:01:01.718   258   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 15:01:01.718   258   509 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:01.718  4465  4465 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 15:01:01.718   258   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 15:01:01.718   258   509 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:01.718  4465  4465 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 15:01:01.728  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:01.728  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:01.728  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 15:01:01.758  1018  2738 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 15:01:01.768  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12f9358a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:48368
,03-15 15:01:01.778   259  1565 I SurfaceFlinger: id=12 Removed NainActivit (7/8)
,03-15 15:01:01.778   259  1565 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,03-15 15:01:01.788  3838  3856 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 15:01:01.808  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-15 15:01:01.808  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:01.808  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:01.808  3838  3856 I AMMetaDataParserService: Resource data:2131099648
,03-15 15:01:01.808  3838  3856 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:01:01.808  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:01.808  1018  1583 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 15:01:01.808  1018  1586 I AudioService: getStreamVolume 3 index 0
,03-15 15:01:01.808  4465  4465 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-15 15:01:01.808  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 15:01:01.818   258   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 15:01:01.818   258   509 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:01.818  4538  4581 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 15:01:01.818   258   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 15:01:01.818   258   509 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:01.838  4538  4581 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 15:01:01.838  4041  4041 W ScreenOrientationListener: Removing an inexistent observer!
,03-15 15:01:01.838  3838  3856 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 15:01:01.848  4465  4465 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 15:01:01.848  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.848  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.848  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:01.848  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:01.858  4041  4041 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@ce80ce5 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:01.858  4041  4041 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@ce80ce5 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 15:01:01.858  4041  4041 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 15:01:01.868  3838  3856 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 15:01:01.868  4586  4586 E Zygote  : MountEmulatedStorage()
03-15 15:01:01.868  4586  4586 I libpersona: KNOX_SDCARD checking this for 10001
03-15 15:01:01.868  4586  4586 E Zygote  : v2
03-15 15:01:01.868  4586  4586 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:01.868  4586  4586 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:01:01.878  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4586 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:01.878  4586  4586 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:01.878  3838  3856 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
03-15 15:01:01.878  4586  4586 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:01.888   258   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 15:01:01.888   258   509 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:01.888  4538  4585 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 15:01:01.898   258   509 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 15:01:01.898   258   509 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 15:01:01.898  4538  4585 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 15:01:01.898  4041  4041 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@f57f3dc that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:01.898  4041  4041 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@f57f3dc that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 15:01:01.898  4041  4041 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 15:01:01.908  1018  1514 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 15:01:01.908  4586  4586 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:01.908  4586  4586 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:01.918  4465  4465 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-15 15:01:01.918  1018  1583 I ActivityManager: Killing 3718:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-15 15:01:01.928  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 15:01:01.938  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:01:01.938  1018  1210 I ActivityManager: Killing 3495:com.google.android.gm/u0a99 (adj 15): empty #31
,03-15 15:01:01.948  3838  3856 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 15:01:01.968  1018  1583 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:01.968  1018  1583 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-15 15:01:01.968  1018  1583 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-15 15:01:01.978  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-15 15:01:01.978  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:01.978  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:01.978  3838  3856 I AMMetaDataParserService: Resource data:2131099648
,03-15 15:01:01.978  3838  3856 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 15:01:01.978  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:01.978  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 15:01:01.988  4554  4554 D hcjo    : AutoUpdateManager:IDLE:execute
,03-15 15:01:01.998  4554  4554 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: exit::IDLE
,03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-15 15:01:02.008  4554  4554 D InitializeManagerStateMachine: entry::SUCCESS
03-15 15:01:02.008  4554  4554 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-15 15:01:02.018  3838  3856 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 15:01:02.018  4554  4554 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-15 15:01:02.028  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3718/cgroup.procs: No such file or directory
,03-15 15:01:02.028  1018  1042 W libprocessgroup: failed to open /acct/uid_10099/pid_3495/cgroup.procs: No such file or directory
,03-15 15:01:02.048  4554  4554 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,03-15 15:01:02.048  4554  4554 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-15 15:01:02.048  4554  4554 D InitializeManagerStateMachine: exit::SUCCESS
,03-15 15:01:02.048  4554  4554 D InitializeManagerStateMachine: entry::IDLE
,03-15 15:01:02.058  3838  3856 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 15:01:02.058  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.058  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.058  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.058  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.068  4617  4617 E Zygote  : MountEmulatedStorage()
03-15 15:01:02.068  4617  4617 E Zygote  : v2
03-15 15:01:02.068  4617  4617 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:01:02.068  4617  4617 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:02.068  4617  4617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:02.078  4617  4617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:02.078  1018  1031 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4617 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:01:02.078  4617  4617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:02.078  1018  1031 I ActivityManager: Killing 3743:com.google.android.talk/u0a102 (adj 15): empty #31
,03-15 15:01:02.108  4617  4617 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:02.108  4617  4617 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:02.118  3838  3856 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 15:01:02.128  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 15:01:02.138  1018  1587 I art     : Explicit concurrent mark sweep GC freed 26114(1421KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 3.722ms total 183.381ms
,03-15 15:01:02.158  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:02.158  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:02.158  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-15 15:01:02.188  4617  4617 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-15 15:01:02.208  3838  3856 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android,.mms.ui.PushMessageDialog
03-15 15:01:02.228  3838  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager,
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages,
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
,03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-15 15:01:02.228  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-15 15:01:02.238  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-15 15:01:02.238  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.238  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:02.238  3838  3856 I AMMetaDataParserService: Resource data:2131165197,
,03-15 15:01:02.248  3838  3856 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:01:02.248  3838  3856 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:02.248  3838  3856 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:02.248  3838  3856 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 15:01:02.248  3838  3856 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 15:01:02.248  3838  3856 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 15:01:02.248  3838  3856 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:01:02.248  3838  3856 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 15:01:02.248  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:02.268  3838  3856 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 15:01:02.278  4538  4538 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-15 15:01:02.288  3838  3856 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 15:01:02.298  4538  4538 I LibraryLoader: Loading: webviewchromium
,03-15 15:01:02.298  4538  4538 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8889-8894)
03-15 15:01:02.298  4538  4538 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:01:02.298  4538  4538 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19a7d0a4}
,03-15 15:01:02.308  4538  4538 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:01:02.308  4538  4538 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 15:01:02.308  1018  1042 W libprocessgroup: failed to open /acct/uid_10102/pid_3743/cgroup.procs: No such file or directory
,03-15 15:01:02.328  4538  4538 I BrowserStartupController: Initializing chromium process, renderers=0
,03-15 15:01:02.338  3838  3856 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 15:01:02.338  4538  4538 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:01:02.338  4617  4617 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-15 15:01:02.348  4538  4538 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-15 15:01:02.348  4538  4538 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,03-15 15:01:02.348  4538  4538 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,03-15 15:01:02.348  4617  4617 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-15 15:01:02.358  4617  4617 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:02.358  4538  4639 W AudioManagerAndroid: Requires BLUETOOTH permission
03-15 15:01:02.358  4617  4617 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-15 15:01:02.358  4617  4617 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-15 15:01:02.358  4617  4617 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-15 15:01:02.358  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 15:01:02.378  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-15 15:01:02.378  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.378  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:01:02.378  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:02.378  3838  3856 I AMMetaDataParserService: Resource data:2131165197
,03-15 15:01:02.378  3838  3856 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 15:01:02.378  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:02.398  4538  4538 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 15:01:02.398  4538  4538 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 15:01:02.398  4538  4538 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 15:01:02.398  4538  4538 I Adreno-EGL: Local Branch: 
03-15 15:01:02.398  4538  4538 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 15:01:02.398  4538  4538 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 15:01:02.398  4538  4538 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 15:01:02.398  3838  3856 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 15:01:02.408  3838  3856 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 15:01:02.458  3838  3856 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 15:01:02.468  4180  4207 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:02.468  4180  4207 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:02.468  4180  4207 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 15:01:02.468  4538  4538 I NSApplication: Starting up...
,03-15 15:01:02.478  1018  1338 E Watchdog: !@Sync 1
,03-15 15:01:02.478  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 15:01:02.478  4180  4205 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:02.488  4180  4205 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 15:01:02.488  4180  4205 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 15:01:02.488  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.488  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.488  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.488  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:02.508  4654  4654 E Zygote  : MountEmulatedStorage(),
03-15 15:01:02.508  4654  4654 I libpersona: KNOX_SDCARD checking this for 10008
03-15 15:01:02.508  4654  4654 E Zygote  : v2,
03-15 15:01:02.508  4654  4654 I libpersona: KNOX_SDCARD not a persona,
03-15 15:01:02.508  1018  1138 D SettingsProvider: name = audio_safe_volume_state,
,03-15 15:01:02.508  1018  2807 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:01:02.508  4654  4654 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:01:02.508  1018  1031 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4654 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 15:01:02.508  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery,
03-15 15:01:02.508  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery,
03-15 15:01:02.508  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.508  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.508  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant,
03-15 15:01:02.508  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.508  3838  3856 I AMMetaDataParserService: Resource data:2131165197
,03-15 15:01:02.508  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.508  3838  3856 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 15:01:02.508  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:02.508  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml,
03-15 15:01:02.508  4654  4654 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:02.518  4654  4654 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 15:01:02.528  4663  4663 E Zygote  : MountEmulatedStorage()
,03-15 15:01:02.528  4663  4663 I libpersona: KNOX_SDCARD checking this for 10117
03-15 15:01:02.528  4663  4663 E Zygote  : v2
03-15 15:01:02.528  4663  4663 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:02.528  3838  3856 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
03-15 15:01:02.528  1018  1522 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4663 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-15 15:01:02.538  1018  1522 I ActivityManager: Killing 3765:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,03-15 15:01:02.538  4654  4654 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:02.538  4654  4654 D ActivityThread: Added TimaKeyStore provider
03-15 15:01:02.538  4663  4663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:01:02.548  4663  4663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:01:02.548  4663  4663 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 15:01:02.568  3838  3856 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 15:01:02.568   309   309 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 37.330ms
,03-15 15:01:02.568   290   290 E SMD     : DCD OFF,
,03-15 15:01:02.578  4663  4663 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:02.578  4663  4663 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:02.588   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.830ms
,03-15 15:01:02.608  4663  4663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 15:01:02.608   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.780ms
03-15 15:01:02.608  1018  1042 W libprocessgroup: failed to open /acct/uid_10065/pid_3765/cgroup.procs: No such file or directory
,03-15 15:01:02.608  3838  3856 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 15:01:02.618  4317  4521 I SA      : [RC New] Execute method=[GET] start
,03-15 15:01:02.648  3838  3856 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 15:01:02.658  1018  1539 I ActivityManager: Killing 3910:com.samsung.helphub/1000 (adj 15): empty #31
,03-15 15:01:02.658  1018  1539 I ActivityManager: Killing 3882:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #32
,03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-15 15:01:02.658  3838  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-15 15:01:02.658  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
03-15 15:01:02.658  4654  4654 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-15 15:01:02.668  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-15 15:01:02.668  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.668  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-15 15:01:02.668  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 15:01:02.668  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-15 15:01:02.668  4654  4654 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
03-15 15:01:02.668  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:02.668  3838  3856 I AMMetaDataParserService: Resource data:2131099648
,03-15 15:01:02.668  4654  4654 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-15 15:01:02.668  4654  4654 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-15 15:01:02.678  3838  3856 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 15:01:02.678  3838  3856 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:01:02.678  3838  3856 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 15:01:02.678  3838  3856 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-15 15:01:02.678  3838  3856 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 15:01:02.678  3838  3856 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-15 15:01:02.678  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:02.678  1018  3628 I ActivityManager: Killing 3793:com.vlingo.midas/u0a28 (adj 15): empty #31,
,03-15 15:01:02.678  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-15 15:01:02.698  4317  4521 I SA      : [RC New] Security=[true]
,03-15 15:01:02.698  4317  4521 I System.out: Thread-650(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-15 15:01:02.698  4317  4521 I System.out: Thread-650(ApacheHTTPLog):isSBSettingEnabled false
,03-15 15:01:02.698  4317  4521 I System.out: Thread-650(ApacheHTTPLog):isShipBuild true
03-15 15:01:02.698  4317  4521 I System.out: Thread-650(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 15:01:02.698  4317  4521 I System.out: Thread-650(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 15:01:02.708  3838  3856 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-15 15:01:02.708   280   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-15 15:01:02.708   280   945 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,03-15 15:01:02.728  3838  3856 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-15 15:01:02.758  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,03-15 15:01:02.758  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-15 15:01:02.758  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,03-15 15:01:02.758  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-15 15:01:02.758  3838  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-15 15:01:02.788  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3910/cgroup.procs: No such file or directory
,03-15 15:01:02.788  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3882/cgroup.procs: No such file or directory
03-15 15:01:02.788  1018  1042 W libprocessgroup: failed to open /acct/uid_10028/pid_3793/cgroup.procs: No such file or directory
,03-15 15:01:02.858  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-15 15:01:02.858  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.858  3838  3856 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 15:01:02.858  3838  3856 I AMMetaDataParserService: Resource data:2131165220
,03-15 15:01:02.868  3838  3856 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-15 15:01:02.868  3838  3856 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 15:01:02.868  3838  3856 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:01:02.868  3838  3856 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:02.868  3838  3856 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:02.868  3838  3856 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 15:01:02.868  3838  3856 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-15 15:01:02.868  3838  3856 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 15:01:02.878  3838  3856 I AMMetaDataParserService: Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,03-15 15:01:02.898  3838  3856 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-15 15:01:02.938  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activi,tycom.android.settings.wifi.WifiWarningDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check,
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 15:01:02.958  3838  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.968  1018  3627 I ActivityManager: Killing 3838:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
,03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-15 15:01:02.948  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_,CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
,03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-15 15:01:02.958  3838  3856 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-15 15:01:03.028  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.028  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:03.028  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-15 15:01:03.088  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3838/cgroup.procs: No such file or directory
,03-15 15:01:03.228  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.228  1018  1521 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,03-15 15:01:03.228  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-15 15:01:03.278  4061  4061 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-15 15:01:03.278  4061  4061 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-15 15:01:03.278  4061  4061 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-15 15:01:03.278  1018  3636 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-15 15:01:03.278  1018  1018 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,03-15 15:01:03.278  1018  1018 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-15 15:01:03.288  4654  4654 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-15 15:01:03.288  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.288  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.288  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.288  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.308  4702  4702 E Zygote  : MountEmulatedStorage(),
03-15 15:01:03.308  4702  4702 E Zygote  : v2
03-15 15:01:03.308  4702  4702 I libpersona: KNOX_SDCARD checking this for 10058
03-15 15:01:03.308  4702  4702 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:03.308  1018  1043 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4702 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:03.308  4702  4702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:03.308  4702  4702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:01:03.308  4702  4702 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:03.318  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.318  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:03.318  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 15:01:03.318  1822  1822 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:03.318  1822  1822 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 15:01:03.318  1822  1822 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:03.328  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.328  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:03.328  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-15 15:01:03.338  1718  1718 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:01:03.338  1018  3628 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.338  4702  4702 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:01:03.338  1718  1718 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:01:03.338  1018  3628 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:03.338  4702  4702 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:03.338  1018  3628 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 15:01:03.338  1822  1822 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 15:01:03.338  4654  4654 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-15 15:01:03.348  1822  1822 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-15 15:01:03.348  4414  4414 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 15:01:03.348  4414  4414 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 15:01:03.348  4414  4414 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 15:01:03.348  1822  1822 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-15 15:01:03.358  1822  1822 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 15:01:03.358  1822  1822 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-15 15:01:03.358  1822  1822 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-15 15:01:03.358  1822  1822 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 15:01:03.358  1822  1822 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-15 15:01:03.358  1822  1822 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 15:01:03.358  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.358  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.358  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.368  1018  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.368  3608  3608 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Mar 15 15:01:03 GMT+01:00 2016
,03-15 15:01:03.368  1822  1822 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-15 15:01:03.378  1822  1822 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 15:01:03.378  1822  1822 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 15:01:03.378  1822  1822 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-15 15:01:03.378  4720  4720 E Zygote  : MountEmulatedStorage()
,03-15 15:01:03.378  4720  4720 E Zygote  : v2
03-15 15:01:03.378  4720  4720 I libpersona: KNOX_SDCARD checking this for 10153
03-15 15:01:03.378  4720  4720 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:03.378  4720  4720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:03.378  1018  1521 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4720 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-15 15:01:03.378  4720  4720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:01:03.388  4720  4720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:03.388  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:03.388  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:03.388  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 15:01:03.398  1822  1822 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 15:01:03.398  3608  3608 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-15 15:01:03.408  1822  1822 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-15 15:01:03.408  4317  4317 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-15 15:01:03.408  4720  4720 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:03.408  4720  4720 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:03.428  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.428  1018  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:03.428  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:03.428  3608  3608 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-15 15:01:03.428  4702  4702 I ExternalOEMControlProvider: onCreate
,03-15 15:01:03.428  1822  1822 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-15 15:01:03.428  3608  3608 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 15:01:03.428  1822  1822 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-15 15:01:03.438  3608  3608 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 15:01:03.448  3608  4735 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-15 15:01:03.448  3608  4735 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,03-15 15:01:03.448  4720  4720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:03.448  3608  4735 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Mar 15 15:01:03 GMT+01:00 2016
03-15 15:01:03.448  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.448  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.448  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.448  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.448  1778  1778 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-15 15:01:03.458  1778  1778 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 15:01:03.458  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 15:01:03.458  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:01:03.458  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:03.468  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
03-15 15:01:03.468  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:01:03.468  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:03.468  4737  4737 E Zygote  : MountEmulatedStorage()
03-15 15:01:03.468  4737  4737 E Zygote  : v2
03-15 15:01:03.468  4737  4737 I libpersona: KNOX_SDCARD checking this for 10041
03-15 15:01:03.468  4737  4737 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:03.468  4737  4737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:03.478  1018  1522 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4737 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-15 15:01:03.478  3608  4735 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,03-15 15:01:03.478  4737  4737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:01:03.478  4737  4737 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 15:01:03.478  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.478  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:03.478  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:03.488  3608  3608 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-15 15:01:03.498  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.498  4702  4736 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
03-15 15:01:03.498  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.498  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.498  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.498  4317  4521 I SA      : [RC New] [v2liruge] api execute + 802
03-15 15:01:03.498  4317  4521 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-15 15:01:03.498  4317  4521 I System.out: AsyncTask #1 calls detatch()
,03-15 15:01:03.508  4751  4751 E Zygote  : MountEmulatedStorage()
03-15 15:01:03.508  4751  4751 E Zygote  : v2
03-15 15:01:03.508  4751  4751 I libpersona: KNOX_SDCARD checking this for 10081
03-15 15:01:03.508  4751  4751 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:03.508  4751  4751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:03.518  1018  1522 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4751 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 15:01:03.518  4751  4751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:03.518  4317  4521 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-15 15:01:03.518  4751  4751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:03.518  2899  4336 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-15 15:01:03.528  4737  4737 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:01:03.528  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.528  4317  4521 I SA      : [OCP] update openData : PL
03-15 15:01:03.528  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.528  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.528  1018  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.528  4737  4737 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:03.528  4317  4521 I SA      : [TPMU] getNetworkMcc : 
,03-15 15:01:03.528  4317  4521 I SA      : [SCU] saveMccToPreferece Start
03-15 15:01:03.528  4317  4521 I SA      : [SCU] RegionMCC : 260
03-15 15:01:03.528  4317  4521 I SA      : [SSP] query invoked
,03-15 15:01:03.528  4317  4521 I SA      : [TPMU] GetMccFromDB : null
03-15 15:01:03.528  4317  4521 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-15 15:01:03.528  4317  4521 I SA      : [SCU] saveMccToPreferece End
,03-15 15:01:03.538  4317  4521 I SA      : [RC New] executeRequest [v2liruge] end. 915,
03-15 15:01:03.538  4317  4521 I SA      : [RC New] Execute end
03-15 15:01:03.538  4317  4317 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,03-15 15:01:03.538  4317  4317 I SA      : [OR] GetMyCountryZoneTask Success
,03-15 15:01:03.538  4766  4766 E Zygote  : MountEmulatedStorage(),
03-15 15:01:03.538  4766  4766 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:01:03.538  4766  4766 E Zygote  : v2
03-15 15:01:03.538  4766  4766 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:03.538  4766  4766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:03.548  4766  4766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 15:01:03.548  4766  4766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:03.548  1018  1522 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 15:01:03.548  3179  3179 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-15 15:01:03.558  4751  4751 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:03.558  4751  4751 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:03.558  3179  3179 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-15 15:01:03.568  3179  3179 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-15 15:01:03.568  2899  2899 I Process : Sending signal. PID: 2899 SIG: 9
,03-15 15:01:03.568  3179  3179 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 15:01:03.568  1018  1522 I ActivityManager: Killing 3929:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-15 15:01:03.578  4737  4737 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-15 15:01:03.578  4737  4737 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:03.578  4737  4737 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:03.578  4737  4737 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 15:01:03.578  4737  4737 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 15:01:03.588  4766  4766 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:03.588  4766  4766 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:03.598  1018  1585 I ActivityManager: Killing 3966:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-15 15:01:03.598  1018  1583 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.598  1018  1583 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:03.598  1018  1583 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:03.608  4751  4751 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 15:01:03.608  4751  4751 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 15:01:03.608  4751  4751 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:03.608  4751  4751 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:03.608  4751  4751 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-15 15:01:03.658  1018  1587 I ActivityManager: Process com.sec.android.app.sysscope (pid 2899)(adj 0) has died(22,617)
,03-15 15:01:03.658  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3929/cgroup.procs: No such file or directory
,03-15 15:01:03.658  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3966/cgroup.procs: No such file or directory
,03-15 15:01:03.688  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-15 15:01:03.688  3179  3219 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-15 15:01:03.688  3179  3219 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 15:01:03.708  3179  3219 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-15 15:01:03.708  4766  4766 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458050463720
,03-15 15:01:03.708  4766  4766 D         : TimeServiceNative: User Time to be set is 1458050463720
03-15 15:01:03.708  4766  4766 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-15 15:01:03.708  4766  4766 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-15 15:01:03.708  4766  4766 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458050463720
,03-15 15:01:03.708   319   551 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-15 15:01:03.718  4766  4766 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458050463720
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458050463720, operation = 0
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/10/70 17:37:43
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:Value read from RTC seconds = 21836263000
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:new time 1458050463720 
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon: delta 1436214200720 genoff 1436214200720 
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214200720 to memory
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-15 15:01:03.718   319  4786 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-15 15:01:03.768  1018  1031 D SettingsProvider: name = next_alarm_formatted
,03-15 15:01:03.768  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-15 15:01:03.768  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 15:01:03.768  1018  1031 D SettingsProvider: selectionArgs: false
03-15 15:01:03.768  1018  1031 D SettingsProvider: selectionArgs: 10081
,03-15 15:01:03.768  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 15:01:03.768  1018  1031 D SettingsProvider: ret = -1
,03-15 15:01:03.788  4737  4737 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-15 15:01:03.798  1018  1043 I ActivityManager: Waited long enough for: ServiceRecord{36bf3cd6 u0 com.samsung.android.providers.context/.ContextService}
,03-15 15:01:03.818   319  4786 D QC-time-services: Updating the TOD offset
03-15 15:01:03.818   319  4786 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214200720 to memory
03-15 15:01:03.818   319  4786 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-15 15:01:03.818   319  4786 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-15 15:01:03.818  3179  3219 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-15 15:01:03.818   319  4786 E QC-time-services: Daemon:Update to modem bit set
03-15 15:01:03.818   319  4786 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-15 15:01:03.818   319  4786 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249400720
03-15 15:01:03.828  4766  4766 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-15 15:01:03.828   319   549 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-15 15:01:03.828   319   551 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-15 15:01:03.838  3179  3219 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 15:01:03.848  1018  3627 I ActivityManager: Killing 4006:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-15 15:01:03.858  3179  3219 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-15 15:01:03.858  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-15 15:01:03.868  3179  3219 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-15 15:01:03.868  3179  3219 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-15 15:01:03.878  3179  3220 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-15 15:01:03.888  3179  3219 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-15 15:01:03.888  3179  3220 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-15 15:01:03.888  3179  3219 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-15 15:01:03.898  3179  3219 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-15 15:01:03.908  4751  4751 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 130.741ms
,03-15 15:01:03.908  3179  3220 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,03-15 15:01:03.908  3179  3220 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-15 15:01:03.918  3179  3220 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-15 15:01:03.928  3179  3220 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-15 15:01:03.948  3179  3220 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-15 15:01:03.948  3179  3220 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,03-15 15:01:03.948  3179  3179 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-15 15:01:03.958  3179  3179 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 15:01:03.958  3179  3179 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-15 15:01:03.958  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_4006/cgroup.procs: No such file or directory
03-15 15:01:03.958  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:03.958  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:03.958  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-15 15:01:03.968  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.968  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:03.968  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.968  1018  1585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:03.968  4737  4737 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 154.223ms
,03-15 15:01:03.978  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-15 15:01:03.978  3179  3220 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,03-15 15:01:03.978  3179  3179 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-15 15:01:03.978  3179  3179 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register,
03-15 15:01:03.978  4789  4789 E Zygote  : MountEmulatedStorage()
03-15 15:01:03.978  4789  4789 E Zygote  : v2
,03-15 15:01:03.978  4789  4789 I libpersona: KNOX_SDCARD checking this for 10090
03-15 15:01:03.978  4789  4789 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:03.978  3179  3179 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@c52d5d1
,03-15 15:01:03.978  4789  4789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:03.988  4789  4789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 15:01:03.988  4789  4789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-15 15:01:03.988  1018  1585 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4789 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-15 15:01:03.988  1018  1585 I ActivityManager: Killing 4096:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-15 15:01:03.998  4789  4789 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:03.998  4789  4789 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:04.008  3179  3220 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 15:01:04.018  3179  3179 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,03-15 15:01:04.018  3179  3179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,03-15 15:01:04.018  3179  3179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,03-15 15:01:04.018  3179  3179 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:50618
,03-15 15:01:04.018  1018  1210 E PersonaManagerService: inState():  stateMachine is null !!
03-15 15:01:04.018  1018  1210 I PersonaManagerService: PersonaId don't exist
03-15 15:01:04.018  1018  1210 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-15 15:01:04.028  1018  1210 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:04.028  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.028  1018  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.028  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 15:01:04.028  1018  1210 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:04.028  1018  1210 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:01:04.028  1018  1210 W ActivityManager: mDVFSHelper.acquire()
,03-15 15:01:04.038  1018  1210 D FocusedStackFrame: Set to : 0
,03-15 15:01:04.038  1524  1524 D Launcher.HomeView: onPause
,03-15 15:01:04.048  1524  1524 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 15:01:04.048  1018  1210 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 15:01:04.048  1018  1210 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:04.048  1018  1210 D InputDispatcher: Focused application set to: xxxx
03-15 15:01:04.048  1018  1210 D InputDispatcher: Focus left window: 1524
,03-15 15:01:04.048  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 15:01:04.048  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:04.048  4789  4789 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-15 15:01:04.048  4789  4789 D elm:15121: ELMEngine.ELMEngine( context ).
,03-15 15:01:04.058  4789  4789 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-15 15:01:04.058  1018  1042 W libprocessgroup: failed to open /acct/uid_10127/pid_4096/cgroup.procs: No such file or directory
,03-15 15:01:04.068  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.068  1018  1587 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.068  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-15 15:01:04.068  4737  4805 D Mms/ArtClassLoader: init before art
,03-15 15:01:04.078  4737  4737 D Mms/TelephonyPermission: start operation mode monitor
,03-15 15:01:04.078  4789  4789 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-15 15:01:04.088  1018  1043 I ActivityManager: Waited long enough for: ServiceRecord{1994693f u0 com.android.settings/.wifi.WifiCredService}
,03-15 15:01:04.088  4737  4737 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 15:01:04.088  4789  4789 D elm:15121: ElmAgentService : onCreate(),
03-15 15:01:04.088  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.088  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:04.088  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:04.088  1018  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:04.108  4789  4806 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-15 15:01:04.108  4789  4806 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-15 15:01:04.108  4789  4789 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,03-15 15:01:04.108  4789  4789 D elm:15121: ModuleBase.ModifySetAlarm()
03-15 15:01:04.108  4789  4789 D elm:15121: MDMBridge.getInstance()
03-15 15:01:04.108  4789  4789 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-15 15:01:04.118  4809  4809 E Zygote  : MountEmulatedStorage()
03-15 15:01:04.118  4809  4809 E Zygote  : v2
03-15 15:01:04.118  4809  4809 I libpersona: KNOX_SDCARD checking this for 10130
03-15 15:01:04.118  4809  4809 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:04.128  4809  4809 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:04.128  4809  4809 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:01:04.128  4809  4809 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-15 15:01:04.128  1018  1210 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4809 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,03-15 15:01:04.138  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66,
,03-15 15:01:04.138  1018  1018 D SensorService: [SO] activate (ident=0xb7eaf3d0, enabled=0)
03-15 15:01:04.138  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 15:01:04.148  4789  4789 D elm:15121: ElmAgentService : onDestroy().,
,03-15 15:01:04.148  4809  4809 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:04.148  4809  4809 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:04.158  1018  1018 D SensorManager: unregisterListener ::   
,03-15 15:01:04.158  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-15 15:01:04.158  1018  1018 D SensorService: [SO] changed settle time [1]
03-15 15:01:04.158  1018  1018 D SensorService: [SO] setDelay [66000000]
03-15 15:01:04.158  1018  1018 D SensorService: [SO] activate (ident=0xb7eaf3d0, enabled=1)
03-15 15:01:04.158  1018  1018 D SensorService: [SO] AR_init
03-15 15:01:04.158  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 15:01:04.158  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
03-15 15:01:04.158  1018  1539 I ActivityManager: Killing 4244:com.sec.android.app.camera/u0a135 (adj 15): empty #31
03-15 15:01:04.158  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,03-15 15:01:04.168  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-15 15:01:04.178  4737  4737 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,03-15 15:01:04.178  1018  1058 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-15 15:01:04.178  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:04.178  4737  4737 D Mms/TelephonyPermission: isDefault true
,03-15 15:01:04.178  4737  4737 D Mms/MmsApp: onCreate() com.android.mms
,03-15 15:01:04.198  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 15:01:04.198  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:04.208  1186  1186 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,03-15 15:01:04.208  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-15 15:01:04.208  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:04.208  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:04.218  3179  3179 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:50810
,03-15 15:01:04.218  1018  1586 E PersonaManagerService: inState():  stateMachine is null !!
,03-15 15:01:04.218  1018  1586 I PersonaManagerService: PersonaId don't exist
,03-15 15:01:04.218  1018  1586 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-15 15:01:04.238  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 15:01:04.238  1018  1018 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-15 15:01:04.238  4023  4023 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-15 15:01:04.258  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.258  1018  1586 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.258  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 15:01:04.258  4809  4809 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 15:01:04.258  4809  4809 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-15 15:01:04.288  1018  1586 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 15:01:04.288  1018  1586 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 15:01:04.288  1018  1586 W ActivityManager: mDVFSHelper.acquire()
,03-15 15:01:04.288  4737  4737 D Mms/MmsApp: [start]    initCountryIso consume time = 504.64552
,03-15 15:01:04.298  1018  1586 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:04.298  1018  1586 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-15 15:01:04.298  1018  1586 D InputDispatcher: Focused application set to: xxxx
,03-15 15:01:04.298  1482  1482 D RegisteredServicesCache: empty dynamic service
,03-15 15:01:04.308  1018  1040 D SensorService: [SO] currT = 50901115000, prevT = 50591073000, diff = 310042000, [-0.479 0.192 9.902]
,03-15 15:01:04.308  1018  1040 D SensorService: [SO] -0.479 0.192 9.902
03-15 15:01:04.308  1018  1040 D SensorService: [SO] [100 -> 255]
,03-15 15:01:04.308  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,03-15 15:01:04.308  1018  3627 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
03-15 15:01:04.308  1018  3627 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 15:01:04.308  1018  3627 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 15:01:04.318  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,03-15 15:01:04.318  1018  1586 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:01:04.318  1018  1586 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 15:01:04.318  1018  1586 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-15 15:01:04.328  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.348  1018  1210 I ActivityManager: Killing 4110:com.android.vending/u0a26 (adj 15): empty #31
,03-15 15:01:04.348  1018  3627 D CountryDetector: The first listener is added
,03-15 15:01:04.358  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 15:01:04.368  1018  1514 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-15 15:01:04.368  1018  1514 D SecContentProvider2: mCursor = null
,03-15 15:01:04.368  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:04.378  1018  1040 D SensorService: [SO] -0.479 0.192 9.883
,03-15 15:01:04.378  4737  4737 D Mms/MmsApp: [end]    initCountryIso consume time = 86.65823
03-15 15:01:04.378  4737  4737 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.10802
,03-15 15:01:04.388  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.388  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.398  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:04.398  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 24
,03-15 15:01:04.408  1018  1097 V AlarmManager: waitForAlarm result :4
,03-15 15:01:04.418  4737  4737 D Mms/MmsConfig: before partial update
,03-15 15:01:04.458  4737  4737 D Mms/MmsConfig: Load Resize quality : 80
,03-15 15:01:04.468  3179  3179 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 15:01:04.468  3179  3179 D PhoneWindow: *FMB* installDecor flags : -2139029248
,03-15 15:01:04.468  4737  4737 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-15 15:01:04.468  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.468  4737  4737 D EasySignUpManager_1.0.1: isAuth is false
,03-15 15:01:04.468  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-15 15:01:04.468  1018  1018 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 15:01:04.478  4737  4737 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-15 15:01:04.478  1018  1018 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 15:01:04.478  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 15:01:04.478  1018  1018 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
03-15 15:01:04.478  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 15:01:04.488  4737  4805 D Mms/ArtClassLoader: init [DONE] art
,03-15 15:01:04.528  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 15:01:04.528  3179  3179 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 15:01:04.538  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 15:01:04.558  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:04.578  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-15 15:01:04.578  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.588  1018  1539 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-15 15:01:04.588  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 15:01:04.588  1018  1539 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:04.588  1018  1031 I art     : Explicit concurrent mark sweep GC freed 29318(1743KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 4.949ms total 176.969ms
,03-15 15:01:04.598  1493  1900 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4737
,03-15 15:01:04.598  1493  1900 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.774 ms
,03-15 15:01:04.598  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 15:01:04.598  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-15 15:01:04.608  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
03-15 15:01:04.608  1018  1018 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 15:01:04.608  1018  1018 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@22b0675a
03-15 15:01:04.608  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.608  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:04.608  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 15:01:04.608  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 15:01:04.608  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:04.618  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.618  4737  4737 D EasySignUpManager_1.0.1: isAuth is false
03-15 15:01:04.618  4737  4737 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-15 15:01:04.618  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:04.618  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
03-15 15:01:04.618  1186  1203 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 15:01:04.628  4737  4737 E CscParser: mps_code.dat does not exist
03-15 15:01:04.628  4737  4737 E CscParser: customer_path =/system/csc/customer.xml
03-15 15:01:04.628  4737  4737 E CscParser: fileName + /system/csc/customer.xml
,03-15 15:01:04.638  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.648  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.648  4737  4737 E CscParser: mps_code.dat does not exist
03-15 15:01:04.648  4737  4737 E CscParser: customer_path =/system/csc/customer.xml
03-15 15:01:04.648  4737  4737 E CscParser: fileName + /system/csc/customer.xml
,03-15 15:01:04.648  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 15:01:04.648  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 15:01:04.658  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.658  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 15:01:04.658  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 15:01:04.658  4737  4737 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-15 15:01:04.658  4737  4737 D Mms/MmsConfig:  enable multiwindow = false
,03-15 15:01:04.658  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 15:01:04.658  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 15:01:04.668  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 15:01:04.668  4737  4737 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-15 15:01:04.668  4737  4737 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-15 15:01:04.678  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 15:01:04.678  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:04.678  1186  1186 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-15 15:01:04.678  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:04.678  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:04.688  4737  4737 D Mms/MmsConfig: [end]    init() consume time = 305.827292
,03-15 15:01:04.688  4737  4737 D Mms/Contact: [start]    init() consume time = 1.760312
,03-15 15:01:04.688  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
03-15 15:01:04.698  1186  1186 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-15 15:01:04.698  1186  1186 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0,
03-15 15:01:04.698  1186  1186 D PersonaManager: isKioskContainerExistOnDevice
03-15 15:01:04.698  1186  1186 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:04.698  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:04.698  1186  1186 D PanelView: There is/are notification(s) 
03-15 15:01:04.698  1186  1186 D PanelView: kidsfalse mQsExpansionEnabled:true,
,03-15 15:01:04.698  1186  1186 D PersonaManager: isKioskContainerExistOnDevice,
03-15 15:01:04.698  1186  1186 D PanelView: There is/are notification(s) 
03-15 15:01:04.698  1186  1186 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:04.708  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:04.708  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:04.708  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,03-15 15:01:04.718  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 15:01:04.718  1718  1718 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-15 15:01:04.718  1018  1042 W libprocessgroup: failed to open /acct/uid_10135/pid_4244/cgroup.procs: No such file or directory
,03-15 15:01:04.728  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:04.738  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:04.738  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 24
,03-15 15:01:04.738  1493  1877 D TP/MmsSmsProvider: query,matched:13, calling pid = 4737
,03-15 15:01:04.738  1493  1877 D TP/MmsSmsProvider: match 13:Elapsed time : 2.717 ms
,03-15 15:01:04.738  1018  1042 W libprocessgroup: failed to open /acct/uid_10026/pid_4110/cgroup.procs: No such file or directory
,03-15 15:01:04.738  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 15:01:04.748  3179  3179 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 15:01:04.748  1018  1042 D LocationProviderProxy: applying state to connected service
,03-15 15:01:04.758  4737  4737 D Mms/Contact: [end]    init consume time = 67.995469
,03-15 15:01:04.758  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 15:01:04.758  1018  1042 D LocationProviderProxy: applying state to connected service
,03-15 15:01:04.768  4737  4834 D Mms/DraftCache: [start]    rebuildCache consume time = 9.3425
,03-15 15:01:04.768  1493  1513 D TP/MmsSmsProvider: query,matched:12, calling pid = 4737
,03-15 15:01:04.768  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 15:01:04.768  1493  1513 D TP/MmsSmsProvider: match 12:Elapsed time : 2.100 ms
,03-15 15:01:04.768  4737  4737 D Mms/MethodReflector: getSubId is called
,03-15 15:01:04.768  4737  4737 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-15 15:01:04.768  4737  4737 D Mms/MethodReflector: getTelephonyProperty is called
,03-15 15:01:04.768  4737  4737 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 15:01:04.768  1186  1186 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-15 15:01:04.768  4737  4737 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 15:01:04.768  4737  4737 D Mms/DownloadManager: auto download without roaming -> true
03-15 15:01:04.768  4737  4737 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-15 15:01:04.768  4737  4737 D Mms/MethodReflector: getSubId is called
,03-15 15:01:04.778  4737  4737 D Mms/MethodReflector: getDefaultSmsSubId is called
03-15 15:01:04.778  4737  4737 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-15 15:01:04.778  4737  4737 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-15 15:01:04.778  4737  4737 D Mms/MethodReflector: getTelephonyProperty is called
03-15 15:01:04.778  4737  4737 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-15 15:01:04.778  4737  4737 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-15 15:01:04.778  4737  4737 D Mms/DownloadManager: auto download without roaming -> true
03-15 15:01:04.778  4737  4737 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-15 15:01:04.778  4737  4737 D Mms/DownloadManager: auto download during roaming secondary -> false
03-15 15:01:04.778  4737  4737 D Mms/DownloadManager: mAutoDownload ------> true
03-15 15:01:04.778  4737  4834 D Mms/DraftCache: [end]    rebuildCache consume time = 11.806146
,03-15 15:01:04.778  1018  3628 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-15 15:01:04.778  1018  3628 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 15:01:04.788  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 15:01:04.788  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 15:01:04.788  1186  1186 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-15 15:01:04.798  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 15:01:04.798  1186  1186 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:04.798  1186  1186 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:04.798  1186  1186 D PanelView: There is/are notification(s) 
03-15 15:01:04.798  1186  1186 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:04.798  1186  1186 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:04.798  1186  1186 D PanelView: There is/are notification(s) 
03-15 15:01:04.798  1186  1186 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 15:01:04.798  3179  3179 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 15:01:04.808  3179  3179 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 15:01:04.808  4737  4737 D ComposerPerformance: 1458050464815 ms / [DONE] Composer constructor
,03-15 15:01:04.808  3179  3179 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,03-15 15:01:04.808  3179  3179 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-15 15:01:04.808  4737  4835 D Mms/Conversation: [start]    init() consume time = 35.00875
,03-15 15:01:04.818  1493  1513 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-15 15:01:04.818  4737  4737 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-15 15:01:04.818  4737  4737 I Mms/ReservationManager: ReservationManager()
03-15 15:01:04.818  4737  4737 I Mms/ReservationManager: resetAfterConnected()
,03-15 15:01:04.818  1493  1513 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-15 15:01:04.818  1493  1513 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-15 15:01:04.818  1493  1877 D TP/MmsSmsProvider: query,matched:7, calling pid = 4737
,03-15 15:01:04.828  1493  1877 D TP/MmsSmsProvider: match 7:Elapsed time : 3.189 ms
,03-15 15:01:04.828  1493  1513 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-15 15:01:04.828  1493  1513 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:04.828  1493  1513 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:04.828  1493  1513 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:04.828  1493  1513 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:04.828  1493  1513 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 15:01:04.828  1493  1513 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-15 15:01:04.828  4737  4737 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-15 15:01:04.828  3179  4836 D OpenGLRenderer: Render dirty regions requested: true
,03-15 15:01:04.828  1018  1585 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-15 15:01:04.828  1018  1585 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-15 15:01:04.828  1018  1585 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 15:01:04.838  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 15:01:04.838  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 15:01:04.838  3179  3179 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 15:01:04.838  3179  3179 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 15:01:04.838  4737  4737 D Mms/MmsApp: [end]    onCreate() consume time = 28.794167
03-15 15:01:04.838  1493  1513 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-15 15:01:04.838  1493  1513 D TP/MmsSmsProvider: need read changed broadcast:false
,03-15 15:01:04.838  4737  4835 D Mms/Conversation: [end]    init consume time = 2.70802
,03-15 15:01:04.848  1018  1586 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-15 15:01:04.848  4737  4737 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-15 15:01:04.848  4737  4737 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-15 15:01:04.848  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.848  1018  1586 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.848  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.848  1018  1586 I ActivityManager: Killing 4395:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-15 15:01:04.858  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.858  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.858  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.858  4737  4835 D Mms/MessagingNotification: [start]    init() consume time = 14.640938
,03-15 15:01:04.858  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.858  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.858  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.858  4737  4737 D Mms/MethodReflector: getSubId is called
03-15 15:01:04.858  4737  4737 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-15 15:01:04.868  4737  4737 D Mms/MethodReflector: getTelephonyProperty is called
03-15 15:01:04.868  4737  4737 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 15:01:04.868  4737  4737 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 15:01:04.868  4737  4737 D Mms/DownloadManager: auto download without roaming -> true
03-15 15:01:04.868  4737  4737 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,03-15 15:01:04.868  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.868  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.868  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.868  4737  4737 D Mms/DownloadManager: mAutoDownload ------> true
,03-15 15:01:04.868  1186  1186 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-15 15:01:04.868  4737  4835 D Mms/MessagingNotification: [end]    init consume time = 13.863073
,03-15 15:01:04.868  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.868  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:04.868  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.878  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.878  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.878  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.878  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.878  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.878  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.878   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, YUIInstallC
,03-15 15:01:04.878  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.878  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.878  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.888  4737  4838 D Mms/Synchronizer: [start]    doSync consume time = 1.83401
,03-15 15:01:04.888  4737  4837 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 12.098073
,03-15 15:01:04.888  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 15:01:04.888  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.888  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.888  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.888  1493  1508 D TP/MmsSmsProvider: query,matched:0, calling pid = 4737
,03-15 15:01:04.888  1493  1508 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-15 15:01:04.888  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.888  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.888  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.888  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:01:04.888  1493  1508 D TP/MmsSmsProvider: match 0:Elapsed time : 2.663 ms
,03-15 15:01:04.898  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.898  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.898  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.898  1493  1513 D TP/MmsSmsProvider: update, matched:300, calling pid = 4737
03-15 15:01:04.898  1493  1513 V TP/MmsSmsProvider: syncDBData start
,03-15 15:01:04.898  1493  1513 V TP/MmsSmsProvider: syncDBData sms end
,03-15 15:01:04.898  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.898  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.898  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 15:01:04.898  1493  1513 V TP/MmsSmsProvider: syncDBData mms end
,03-15 15:01:04.898  1493  1513 V TP/MmsSmsProvider: syncDBData end
,03-15 15:01:04.898  1493  1508 D TP/MmsSmsProvider: query,matched:400, calling pid = 4737
03-15 15:01:04.898  1018  1522 D InputDispatcher: Focus entered window: 3179
,03-15 15:01:04.908  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.908  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.908  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.908  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.908  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.908  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.918  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.918  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:04.918  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 15:01:04.918  3179  3179 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 15:01:04.918  3179  4836 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 15:01:04.918  3179  4836 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 15:01:04.918  3179  4836 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 15:01:04.918  3179  4836 I Adreno-EGL: Local Branch: 
03-15 15:01:04.918  3179  4836 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 15:01:04.918  3179  4836 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 15:01:04.918  3179  4836 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 15:01:04.918  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 15:01:04.918  3179  4836 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 15:01:04.918  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 15:01:04.918  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.918  1018  1018 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.918  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.918  4737  4838 D Mms/Synchronizer: [end]    doSync consume time = 38.879427
,03-15 15:01:04.928  1018  1210 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 15:01:04.928  1018  1210 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-15 15:01:04.928  1018  1210 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-15 15:01:04.928  1018  1210 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
03-15 15:01:04.928  4737  4837 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 7.611406
,03-15 15:01:04.928  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.928  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.928  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.938  3179  4836 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-15 15:01:04.938  3179  4836 D OpenGLRenderer: Enabling debug mode 0
,03-15 15:01:04.948  4737  4835 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-15 15:01:04.948  1493  1900 D TP/SmsProvider: query,matched:26, calling pid = 4737
,03-15 15:01:04.958  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.958  1018  1586 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.958  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.958  1493  1900 D TP/SmsProvider: match 26:Elapsed time : 11.218 ms
,03-15 15:01:04.968  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.968  1018  1586 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.968  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.968  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.968  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.968  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.978  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_4395/cgroup.procs: No such file or directory
,03-15 15:01:04.978  1018  2738 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.978  1018  2738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 15:01:04.978  1018  2738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.988  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.988  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.988  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.988  1718  1718 D WearableService: callingUid 10011, callindPid: 1718
,03-15 15:01:04.988  1018  1078 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:04.988  1018  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.988  1018  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.998  1018  3627 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:04.998  1018  3627 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:04.998  1018  3627 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:04.998  1718  4840 E MDM     : [225] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 15:01:05.008  1493  1508 D TP/MmsSmsProvider: query,matched:6, calling pid = 4737
,03-15 15:01:05.008  1018  3627 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.008  1018  3627 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.008  1018  3627 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.008  1493  1508 D TP/MmsSmsProvider: match 6:Elapsed time : 2.263 ms
,03-15 15:01:05.008  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.008  1718  1718 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
03-15 15:01:05.008  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 15:01:05.008  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.018  2068  4841 D LocationInitializer: Restart initialization of location
,03-15 15:01:05.018  1018  3627 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.018  1018  3627 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.018  1018  3627 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.018  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.018  1018  1587 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 15:01:05.018  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.028  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.028  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.028  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.028  3436  3436 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,03-15 15:01:05.028  1018  1210 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 15:01:05.038  3436  4842 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-15 15:01:05.038  1018  2738 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.038  1018  1048 D PersonaManager: isKioskContainerExistOnDevice
,03-15 15:01:05.038  1018  2738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.038  1018  2738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.048  1718  1718 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:01:05.048  3436  4842 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-15 15:01:05.048  1186  1186 D PanelView: There is/are notification(s) 
,03-15 15:01:05.048  1018  1583 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.048  1018  1583 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.048  1018  1583 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.048  1018  4845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 15:01:05.058  3436  4842 I ReactiveServiceManager: Supported : 1
03-15 15:01:05.058  1018  3627 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-15 15:01:05.058  1018  3627 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 15:01:05.058  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.058  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.058  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.058  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.068  1854  1854 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-15 15:01:05.078  1018  3627 D QSEECOMAPI: : Loaded image: APP id = 10
,03-15 15:01:05.088  3179  3179 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@dceb79 time:51681
,03-15 15:01:05.088  4848  4848 E Zygote  : MountEmulatedStorage()
03-15 15:01:05.088  4848  4848 I libpersona: KNOX_SDCARD checking this for 10023
03-15 15:01:05.088  4848  4848 E Zygote  : v2
03-15 15:01:05.088  4848  4848 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:05.088  1018  1030 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4848 uid=10023 gids={50023, 9997} abi=armeabi-v7a
03-15 15:01:05.088  4848  4848 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:05.088  1018  1586 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.088  1018  1586 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.088  1018  1586 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:01:05.088  4848  4848 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 15:01:05.088  4848  4848 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:05.088  1018  1048 I ActivityManager: Displayed Component not be shown by security: +773ms (total +1s42ms)
,03-15 15:01:05.098  1018  3627 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 15:01:05.098  1018  3627 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
03-15 15:01:05.098  1018  3627 E terrier : handleString: Failed to handle string(-4)
03-15 15:01:05.098  1018  3627 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-15 15:01:05.098  1018  1078 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.098  1018  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.098  1018  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 15:01:05.098  3436  4842 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-15 15:01:05.098  3436  4842 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-15 15:01:05.098  3436  4842 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-15 15:01:05.098  3436  4842 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 15:01:05.098  3436  4842 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 15:01:05.098  3436  4842 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-15 15:01:05.118  1018  1585 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.118  1018  1585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:05.118  1018  1585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 15:01:05.118  1718  2132 W GCoreFlp: No location to return for getLastLocation()
,03-15 15:01:05.118  1718  4843 W FusedLocationProvider: location=null
,03-15 15:01:05.118  4848  4848 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:05.118  4848  4848 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:05.128  1018  1078 I ActivityManager: Killing 4430:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,03-15 15:01:05.148  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.148  1018  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:05.158  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 15:01:05.178  1018  1210 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.178  1018  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 15:01:05.178  1018  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 15:01:05.238  1018  1042 W libprocessgroup: failed to open /acct/uid_10148/pid_4430/cgroup.procs: No such file or directory
,03-15 15:01:05.258  4848  4848 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-15 15:01:05.268  4737  4835 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-15 15:01:05.288  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-15 15:01:05.288  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.288  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:05.288  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.288  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
03-15 15:01:05.288  1018  2738 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.288  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-15 15:01:05.298  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-15 15:01:05.298  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-15 15:01:05.298  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-15 15:01:05.298  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
03-15 15:01:05.298  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
03-15 15:01:05.298  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
03-15 15:01:05.308  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-15 15:01:05.308  4865  4865 E Zygote  : MountEmulatedStorage()
03-15 15:01:05.308  4865  4865 E Zygote  : v2
03-15 15:01:05.308  4865  4865 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:01:05.308  4865  4865 I libpersona: KNOX_SDCARD not a persona
,03-15 15:01:05.308  4865  4865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 15:01:05.308  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-15 15:01:05.308  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-15 15:01:05.308  4848  4848 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
03-15 15:01:05.308  1018  2738 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4865 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 15:01:05.308  4865  4865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 15:01:05.308  4865  4865 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 15:01:05.338  4865  4865 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 15:01:05.338  4865  4865 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:05.358  4865  4865 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-15 15:01:05.368  1018  1521 D SecContentProvider2: uri = 14 selection = getSealedState
,03-15 15:01:05.368  1018  1521 D SecContentProvider2: mCursor = null
,03-15 15:01:05.368  1018  1583 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-15 15:01:05.368  1018  1583 D SecContentProvider2: mCursor = null
,03-15 15:01:05.368  4865  4865 V MTPRx   : sealedState: false
03-15 15:01:05.368  4865  4865 V MTPRx   : sealedUsbMassStorageState: false
03-15 15:01:05.368  4865  4865 E MTPRx   : check value of boot_completed is1
03-15 15:01:05.368  4865  4865 E MTPRx   : check booting is completed_sys.boot_completed
,03-15 15:01:05.368  4865  4865 E MTPRx   : Sd-Card path/storage/extSdCard
,03-15 15:01:05.378  4865  4865 E MTPRx   : Status for mount/Unmount :removed
03-15 15:01:05.378  4865  4865 E MTPRx   : SDcard is not available
,03-15 15:01:05.378  4865  4865 W MTPRx   : value of connected istrue
03-15 15:01:05.378  4865  4865 W MTPRx   : value of configured istrue
03-15 15:01:05.378  4865  4865 W MTPRx   : value of mtpEnabled istrue
03-15 15:01:05.378  4865  4865 W MTPRx   : value of ptpEnabled isfalse
,03-15 15:01:05.378  4865  4865 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-15 15:01:05.378  4865  4865 E MTPRx   : mFirstTime: false
,03-15 15:01:05.388  4737  4737 D Mms/Contact: performUpdate:widgetCount=0
,03-15 15:01:05.388  4737  4737 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-15 15:01:05.388  4737  4881 D Mms/ContactsCache: [start]    invalidate() consume time = 461.649479
,03-15 15:01:05.388  4737  4881 D Mms/ContactsCache: [end]    invalidate() consume time = 0.437917
,03-15 15:01:05.398  1018  1018 I ValidateNoPeople: mEvictionCount: 0
,03-15 15:01:05.398  4865  4865 D         : MTP: reading debug level property
,03-15 15:01:05.398  4865  4865 E MTPJNIInterface: Getting CryptionKey from JAVA
03-15 15:01:05.398  4865  4865 E MTPRx   : currentUserId is 0
,03-15 15:01:05.408  4865  4865 E MTPRx   : Start observing USB_STATE_MATCH 
,03-15 15:01:05.408  4865  4865 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
,03-15 15:01:05.408  4865  4865 E MTPRx   : is_Privatemode is NOT 1
,03-15 15:01:05.408  1018  1522 D SettingsProvider: name = boot_time_connected
,03-15 15:01:05.408  4865  4865 E MTPRx   : Sending NORMAL_BOOT to stack
03-15 15:01:05.408  4865  4865 E MTPJNIInterface: noti = 17
,03-15 15:01:05.418  1018  1514 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 15:01:05.418  1018  2738 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-15 15:01:05.418  4865  4865 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-15 15:01:05.418  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
03-15 15:01:05.418  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:05.418  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 15:01:05.418  1018  1031 D SettingsProvider: name = mtp_running_status
,03-15 15:01:05.428  1018  3627 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 15:01:05.428  4865  4865 E MTPRx   : else part ... so first time!!!
,03-15 15:01:05.428  4865  4865 E MTPPlaObsrvr: inside setContext()
03-15 15:01:05.428  4865  4865 E MTPPlaObsrvr:  inside createplafiles
,03-15 15:01:05.438  4865  4865 E MTPPlaObsrvr: playlist count is0
03-15 15:01:05.438  4865  4865 E MTPPlaObsrvr:  inside try branch createplafiles
,03-15 15:01:05.438  4865  4865 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-15 15:01:05.438  1186  1186 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 15:01:05.438  4865  4865 E MTPPlaObsrvr: Inside registerContentObserver
,03-15 15:01:05.438  4865  4865 E MtpAdbObserver: inside setContext()
,03-15 15:01:05.438  4865  4865 E MtpAdbObserver: Inside registerContentObserver
03-15 15:01:05.438  4865  4865 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-15 15:01:05.438  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.438  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 15:01:05.438  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 15:01:05.448  1018  1514 D SettingsProvider: name = mtp_running_status
,03-15 15:01:05.448  1018  1210 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 15:01:05.448  4865  4865 E MtpService: onCreate.
,03-15 15:01:05.448  4865  4865 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-15 15:01:05.448  4865  4884 V MtpMediaDBManager: inside deleteAllDB
,03-15 15:01:05.448  1018  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-15 15:01:05.448  4865  4865 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
03-15 15:01:05.448  1018  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 15:01:05.458  1018  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 15:01:05.458  4865  4865 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-15 15:01:05.458  4865  4865 E MtpService: onStartCommand.
,03-15 15:01:05.458  4865  4865 W MTPRx   : calling native method
03-15 15:01:05.458  4865  4865 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-15 15:01:05.458  1218  1218 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-15 15:01:05.468  4865  4865 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-15 15:01:05.468  4865  4865 E MTPJNIInterface: noti = 10
,03-15 15:01:05.468  4865  4865 E MtpService: onStartCommand.
03-15 15:01:05.468  4865  4865 W MTPRx   : calling native method
03-15 15:01:05.468  4865  4865 E MTPRx   : Checking the driver time out
03-15 15:01:05.468  4865  4865 E MTPJNIInterface: noti = 2
03-15 15:01:05.468  4865  4865 D         : deleting sockets before message queue initialization
,03-15 15:01:05.468  4865  4885 E MtpService: handleMessage. msg= { when=-3ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-15 15:01:05.468  4865  4865 D         : event handler thread is created, so set the flag
,03-15 15:01:05.468  4865  4865 E MTPRx   : called native method
03-15 15:01:05.468  4865  4865 E MTPJNIInterface: setting Media scanner status0
03-15 15:01:05.468  4865  4865 E MTPJNIInterface: After setting Media scanner status0
,03-15 15:01:05.468  4865  4865 W MTPRx   : notification from stack 1
,03-15 15:01:05.468  4865  4886 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,03-15 15:01:05.468  4865  4885 E MtpService: handleMessage. msg= { when=-6ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-15 15:01:05.468  4865  4886 E MTPJNIInterface: Getting media scanner status0
,03-15 15:01:05.478  4865  4884 V MtpMediaDBManager: inside Thread updateDB
,03-15 15:01:05.478  4865  4886 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A3)
,03-15 15:01:05.478  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:05.478  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:05.478  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 15:01:05.478  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 15:01:05.478  1186  1186 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
03-15 15:01:05.478  1186  1186 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 15:01:05.478  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:05.488  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:01:05.488  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 15:01:05.488  1186  1186 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 15:01:05.488  4887  4887 E Zygote  : MountEmulatedStorage()
03-15 15:01:05.488  4887  4887 I libpersona: KNOX_SDCARD checking this for 1000
03-15 15:01:05.488  4887  4887 E Zygote  : v2
03-15 15:01:05.488  4887  4887 I libpersona: KNOX_SDCARD not a persona
03-15 15:01:05.488  1018  1031 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4887 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 15:01:05.498  4887  4887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 15:01:05.498  1018  1048 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7,
03-15 15:01:05.498  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f4aa589 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t12} time:52094,
03-15 15:01:05.498  1018  1048 W ActivityManager: mDVFSHelper.release()
,03-15 15:01:05.498  4887  4887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-15 15:01:05.498   259   451 I SurfaceFlinger: id=13 Removed Mauncher (5/8)
03-15 15:01:05.498  4887  4887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 15:01:05.508   259   453 I SurfaceFlinger: id=13 Removed Mauncher (-2/8)
,03-15 15:01:05.508  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 15:01:05.518  4865  4884 E MtpMediaDBManager: count : 26
,03-15 15:01:05.518  1524  1524 D Launcher.HomeView: onStop
,03-15 15:01:05.518  1524  1524 V ActivityThread: updateVisibility : ActivityRecord{2f21fa3f token=android.os.BinderProxy@109be989 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-15 15:01:05.518  1524  1524 D Launcher: onTrimMemory. Level: 20
,03-15 15:01:05.528  4887  4887 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 15:01:05.528  4887  4887 D ActivityThread: Added TimaKeyStore provider
,03-15 15:01:05.538  4865  4884 W MtpMediaDBManager: sending db update complete noti to stack
,03-15 15:01:05.538  4865  4884 E MTPJNIInterface: noti = 29
,03-15 15:01:05.548  4865  4886 E MTPJNIInterface: Status for mount/Unmount :removed
03-15 15:01:05.548  4865  4886 E MTPJNIInterface: SDcard is not available
,03-15 15:01:05.568  4865  4886 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-15 15:01:05.568   290   290 E SMD     : DCD OFF
,03-15 15:01:05.578  4865  4886 E MTPJNIInterface: Status for mount/Unmount :removed
03-15 15:01:05.578  4865  4886 E MTPJNIInterface: SDcard is not available
03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) API call with NULL database connection pointer
,03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 15:01:05.578  4865  4886 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-15 15:01:05.578  4865  4865 W MTPRx   : notification from stack 2
03-15 15:01:05.578  4865  4902 D         : [mtp_init_device] Library open with 32 bits.
03-15 15:01:05.578  4865  4902 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-15 15:01:05.578  4865  4902 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-15 15:01:05.578  4865  4902 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,03-15 15:01:05.578  4865  4902 E         :  [sua_support_present:1287] returning false 
03-15 15:01:05.578  4865  4902 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
