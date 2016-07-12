#### Test 757892685a40176_thali01_samsung-SM-A300FU Logs


```
--------- beginning of main
07-12 17:44:57.950  1447  1666 D TP/MmsSmsProvider: query,matched:400, calling pid = 5724
07-12 17:44:57.970  5833  5833 E Zygote  : MountEmulatedStorage()
07-12 17:44:57.970  5833  5833 E Zygote  : v2
07-12 17:44:57.970  5833  5833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:57.970  5833  5833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:57.970  5833  5833 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
--------- beginning of system
07-12 17:44:57.970  5833  5833 I libpersona: KNOX_SDCARD checking this for 10042
07-12 17:44:57.970  5833  5833 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:57.970  1018  1679 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5833 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
07-12 17:44:57.980  1018  1224 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
07-12 17:44:57.980  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.980  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.980  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.980  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.990  5843  5843 E Zygote  : MountEmulatedStorage()
07-12 17:44:57.990  5843  5843 E Zygote  : v2
07-12 17:44:57.990  5843  5843 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:57.990  5843  5843 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:57.990  5843  5843 I libpersona: KNOX_SDCARD checking this for 10068
07-12 17:44:57.990  5843  5843 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:58.000  5833  5833 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.000  5833  5833 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.000  5843  5843 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
07-12 17:44:58.000  5724  5821 D Mms/Synchronizer: [end]    doSync consume time = 76.051146
07-12 17:44:58.000  1018  1224 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5843 uid=10068 gids={50068, 9997} abi=armeabi-v7a
07-12 17:44:58.010  5724  5838 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
07-12 17:44:58.010  5724  5838 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
07-12 17:44:58.010  1018  1138 I ActivityManager: Killing 5268:com.google.android.gm/u0a99 (adj 15): empty #21
07-12 17:44:58.020  5724  5798 D Mms/ArtClassLoader: init [DONE] art
07-12 17:44:58.030  5724  5814 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 26.603906
07-12 17:44:58.040  5843  5843 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.040  5843  5843 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.040  1018  1480 I ActivityManager: Killing 4890:com.google.android.music:main/u0a108 (adj 15): empty #21
07-12 17:44:58.070  5833  5833 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 17:44:58.070  5833  5833 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-12 17:44:58.070  5833  5833 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-12 17:44:58.080  5843  5843 D BadgeProvider: onCreate
07-12 17:44:58.080  5843  5843 D BadgeProvider: DatabaseHelper
07-12 17:44:58.170  3231  5678 W art     : Verification of com.google.android.gms.common.api.GoogleApiClient com.google.android.gms.games.broker.PlayerAgent.getConnectedPeopleClient(com.google.android.gms.games.broker.GamesClientContext) took 118.695ms
07-12 17:44:58.250  1018  1500 I art     : Explicit concurrent mark sweep GC freed 143142(7MB) AllocSpace objects, 3(1855KB) LOS objects, 33% free, 22MB/33MB, paused 2.573ms total 169.426ms
07-12 17:44:58.250  5641  5717 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
07-12 17:44:58.270  5724  5813 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
07-12 17:44:58.280  5833  5833 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
07-12 17:44:58.280  1447  1475 D TP/SmsProvider: query,matched:26, calling pid = 5724
07-12 17:44:58.280  1447  1475 D TP/SmsProvider: match 26:Elapsed time : 3.574 ms
07-12 17:44:58.290  1018  1138 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
07-12 17:44:58.290  1018  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
07-12 17:44:58.290  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:58.290  1018  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:58.290  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
07-12 17:44:58.290  5641  5717 I AcmsKeyStoreHelper: Key Store exist
07-12 17:44:58.290  5641  5717 I AcmsKeyStoreHelper: Hence loading the keystore file
07-12 17:44:58.300  1018  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
07-12 17:44:58.300  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-12 17:44:58.310   286   286 E installd: system dir 0 : /system/app/
07-12 17:44:58.310   286   286 E installd: system dir 1 : /system/priv-app/
07-12 17:44:58.310   286   286 E installd: system dir 2 : /vendor/app/
07-12 17:44:58.310   286   286 E installd: system dir 3 : /oem/app/
07-12 17:44:58.320  1447  4358 D TP/MmsSmsProvider: query,matched:6, calling pid = 5724
07-12 17:44:58.320  1447  4358 D TP/MmsSmsProvider: match 6:Elapsed time : 1.246 ms
07-12 17:44:58.330  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
07-12 17:44:58.330  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
07-12 17:44:58.330  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:58.340  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:58.340  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
07-12 17:44:58.370  1018  1138 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
07-12 17:44:58.370  5641  5717 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
07-12 17:44:58.370  5641  5717 I AcmsCertificateMngr: getKeyStoreForApplication success 
07-12 17:44:58.370  5641  5717 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
07-12 17:44:58.370  5641  5717 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-12 17:44:58.370  5641  5717 D AcmsServiceMonitor: Decrementing - Counter value: 1
07-12 17:44:58.370  5641  5717 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
07-12 17:44:58.370  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.370  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.370  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.370  5641  5717 D AcmsCore: This is NOT a valid MirrorLink app
07-12 17:44:58.370  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.370  5641  5717 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
07-12 17:44:58.370  5641  5717 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-12 17:44:58.370  5641  5717 D AcmsServiceMonitor: Decrementing - Counter value: 0
07-12 17:44:58.370  5641  5717 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
07-12 17:44:58.370  1018  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
07-12 17:44:58.390  5886  5886 E Zygote  : MountEmulatedStorage()
07-12 17:44:58.390  5886  5886 E Zygote  : v2
07-12 17:44:58.390  5886  5886 I libpersona: KNOX_SDCARD checking this for 10023
07-12 17:44:58.390  5886  5886 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:58.390  5886  5886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:58.390  5886  5886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:58.390  1018  1138 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5886 uid=10023 gids={50023, 9997} abi=armeabi-v7a
07-12 17:44:58.390  5886  5886 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:44:58.400  5641  5641 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-12 17:44:58.400  5641  5641 D AcmsService: Enter onDestroy
07-12 17:44:58.400  5641  5641 I AcmsService: cleanUp(): inside service clean up
07-12 17:44:58.400  5641  5641 D AcmsCore: AcmsCore: inside DeInit
07-12 17:44:58.400  5641  5641 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
07-12 17:44:58.400  5641  5641 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
07-12 17:44:58.400  5641  5641 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
07-12 17:44:58.400  5641  5641 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
07-12 17:44:58.400  5641  5641 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
07-12 17:44:58.400  5641  5641 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-12 17:44:58.400  5641  5641 D AcmsService: killing acms process
07-12 17:44:58.400  5641  5641 I Process : Sending signal. PID: 5641 SIG: 9
07-12 17:44:58.420  5886  5886 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.420  5886  5886 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.420  1018  1224 I ActivityManager: Killing 5364:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
07-12 17:44:58.440  1018  1224 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
07-12 17:44:58.450  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.450  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.450  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.450  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.460  5902  5902 E Zygote  : MountEmulatedStorage()
07-12 17:44:58.460  5902  5902 E Zygote  : v2
07-12 17:44:58.460  5902  5902 I libpersona: KNOX_SDCARD checking this for 10148
07-12 17:44:58.460  5902  5902 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:58.460  1018  1224 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5902 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
07-12 17:44:58.460  5902  5902 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:58.470  1018  1480 I ActivityManager: Process ACMS.Process (pid 5641)(adj 0) has died(44,787)
07-12 17:44:58.470  5902  5902 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:58.470  5902  5902 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:44:58.480  5886  5886 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
07-12 17:44:58.480  1018  1030 I ActivityManager: Killing 4623:com.google.android.talk/u0a102 (adj 15): empty #21
07-12 17:44:58.490  5902  5902 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.500  5902  5902 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.500  5724  5813 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
07-12 17:44:58.530  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
07-12 17:44:58.540  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
07-12 17:44:58.540  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
07-12 17:44:58.540  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
07-12 17:44:58.540  5902  5902 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
07-12 17:44:58.540  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
07-12 17:44:58.540  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
07-12 17:44:58.540  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
07-12 17:44:58.540  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
07-12 17:44:58.560  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
07-12 17:44:58.560  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
07-12 17:44:58.560  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
07-12 17:44:58.560  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
07-12 17:44:58.560  5886  5886 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
07-12 17:44:58.560  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
07-12 17:44:58.570  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.570  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.570  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.570  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.580  1018  1031 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-12 17:44:58.580  1018  1031 I ActivityManager: Killing 5207:com.google.android.gms:car/u0a11 (adj 15): empty #21
07-12 17:44:58.590  5918  5918 E Zygote  : MountEmulatedStorage()
07-12 17:44:58.590  5918  5918 E Zygote  : v2
07-12 17:44:58.590  5918  5918 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:44:58.590  5918  5918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:58.590  5918  5918 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:58.590  5918  5918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:58.590  5918  5918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:44:58.600  1018  1500 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
07-12 17:44:58.610  5754  5775 W art     : Suspending all threads took: 7.032ms
07-12 17:44:58.610  5918  5918 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.610   313   313 I art     : Explicit concurrent mark sweep GC freed 8716(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 27.486ms
07-12 17:44:58.610  5918  5918 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.620  5918  5918 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
07-12 17:44:58.630   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 644us total 17.268ms
07-12 17:44:58.640   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.633ms
07-12 17:44:58.650  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
07-12 17:44:58.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.670  5933  5933 E Zygote  : MountEmulatedStorage()
07-12 17:44:58.670  5933  5933 E Zygote  : v2
07-12 17:44:58.670  5933  5933 I libpersona: KNOX_SDCARD checking this for 10152
07-12 17:44:58.670  5933  5933 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:58.670  5933  5933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:58.670  1018  1565 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5933 uid=10152 gids={50152, 9997} abi=armeabi-v7a
07-12 17:44:58.670  5933  5933 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:58.670  1018  1565 I ActivityManager: Killing 5540:com.sec.spp.push/u0a32 (adj 15): empty #21
07-12 17:44:58.680  5933  5933 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:44:58.690  5933  5933 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.690  5933  5933 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.710  5933  5933 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
07-12 17:44:58.710  5933  5933 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
07-12 17:44:58.720  5933  5933 I TapandpayWidget:Utils: Clear T&P info.
07-12 17:44:58.720  5933  5933 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
07-12 17:44:58.730  1018  1464 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
07-12 17:44:58.730  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.730  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.730  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.730  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.740  5754  5754 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-12 17:44:58.740  5951  5951 E Zygote  : MountEmulatedStorage()
07-12 17:44:58.750  5951  5951 E Zygote  : v2
07-12 17:44:58.750  5951  5951 I libpersona: KNOX_SDCARD checking this for 10009
07-12 17:44:58.750  5951  5951 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:58.750  5951  5951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:58.750  1018  1464 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5951 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
07-12 17:44:58.750  1018  1464 I ActivityManager: Killing 5548:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
07-12 17:44:58.750  5951  5951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:58.750  5951  5951 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-12 17:44:58.770  3231  3966 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
07-12 17:44:58.780  5951  5951 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.780  5951  5951 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.820  3231  3966 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-12 17:44:58.860  3231  3966 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
07-12 17:44:58.880  1018  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-12 17:44:58.880  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:58.880  1018  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:58.880  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:58.930  1018  1679 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
07-12 17:44:58.930  1018  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.930  1018  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.930  1018  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.930  1018  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:58.950  5972  5972 E Zygote  : MountEmulatedStorage()
07-12 17:44:58.950  5972  5972 E Zygote  : v2
07-12 17:44:58.950  5972  5972 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:44:58.950  5972  5972 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:58.950  5972  5972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:58.950  5972  5972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:58.950  5972  5972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:44:58.950  1018  1679 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-12 17:44:58.950  1018  1679 I ActivityManager: Killing 5564:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
07-12 17:44:58.950  1018  1138 D ActivityManager: startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
07-12 17:44:58.960  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:58.950  1018  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
07-12 17:44:58.960  1018  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:58.960  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
07-12 17:44:58.960  5754  5754 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-12 17:44:58.970  5972  5972 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:58.970  5972  5972 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:58.990  1018  1466 I ActivityManager: Killing 4611:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
07-12 17:44:58.990  5972  5972 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
07-12 17:44:58.990  5972  5972 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
07-12 17:44:59.000  1018  1138 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-12 17:44:59.000  1018  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
07-12 17:44:59.000  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.000  1018  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.000  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
07-12 17:44:59.000  1018  1464 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
07-12 17:44:59.000  5972  5972 I FilterInstaller: FilterPackageService : ACTION_CHANGED
07-12 17:44:59.020  5972  5991 E FilterInstaller: installFilters
07-12 17:44:59.020  5972  5991 E FilterInstaller: There is no requred permission
07-12 17:44:59.020  1018  1565 I ActivityManager: Killing 5620:com.samsung.helphub/1000 (adj 15): empty #21
07-12 17:44:59.170  5815  5867 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 17:44:59.190  5815  5867 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 17:44:59.190  5815  5867 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 17:44:59.190  5815  5867 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 17:44:59.600  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.600  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.600  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.600  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.620  5992  5992 E Zygote  : MountEmulatedStorage()
07-12 17:44:59.620  5992  5992 E Zygote  : v2
07-12 17:44:59.620  5992  5992 I libpersona: KNOX_SDCARD checking this for 10011
07-12 17:44:59.620  5992  5992 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:59.620  5992  5992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:59.620  1018  1043 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=5992 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
07-12 17:44:59.620  5992  5992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:59.630  5992  5992 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-12 17:44:59.650  5992  5992 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:59.650  5992  5992 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:59.670  5992  5992 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 17:44:59.670  5992  5992 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-12 17:44:59.700  5992  5992 I MultiDex: VM with version 2.1.0 has multidex support
07-12 17:44:59.700  5992  5992 I MultiDex: install
07-12 17:44:59.700  5992  5992 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-12 17:44:59.710  5992  5992 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-12 17:44:59.720  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.720  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.720  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.720  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 17:44:59.720  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
07-12 17:44:59.720  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.720  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.730  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.730  1018  1224 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
07-12 17:44:59.730  1018  1224 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
07-12 17:44:59.730  1018  1224 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
07-12 17:44:59.730  1018  1224 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
07-12 17:44:59.730  1623  2616 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-12 17:44:59.730  1018  1224 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.730  1018  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.730  1018  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:44:59.740  1018  1678 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.740  1018  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.740  1018  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.740  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.740  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.740  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.750  1018  1031 I ActivityManager: Killing 5588:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
07-12 17:44:59.750  1623  1623 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-12 17:44:59.750  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.750  1018  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.750  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.760  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.760  1018  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.760  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.760  3231  3231 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
07-12 17:44:59.760  1018  1679 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:44:59.760  1018  1679 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
07-12 17:44:59.760  1018  1679 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.760  1018  1679 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.760  1018  1679 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.770  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.770  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.770  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.770  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.770  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.770  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.780  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.780  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.780  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.780  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.790  1018  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.790  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.790  1018  1679 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.790  1018  1679 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.790  1018  1679 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.800  1018  1464 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-12 17:44:59.800  1018  1464 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.800  1018  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.800  1018  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.800  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.800  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.800  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.800  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.820  6011  6011 E Zygote  : MountEmulatedStorage()
07-12 17:44:59.820  6011  6011 E Zygote  : v2
07-12 17:44:59.820  6011  6011 I libpersona: KNOX_SDCARD checking this for 10011
07-12 17:44:59.820  6011  6011 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:59.820  6011  6011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:59.820  1018  1464 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6011 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
07-12 17:44:59.820  1018  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-12 17:44:59.820  6011  6011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:59.820  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.820  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.820  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.820  6011  6011 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-12 17:44:59.830  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.830  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.830  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.830  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.830  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.830  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.840  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.840  1018  1500 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:44:59.840  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.840  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
07-12 17:44:59.840  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.850  3231  6020 D LocationInitializer: Restart initialization of location
07-12 17:44:59.850  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.850  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.850  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.850  1018  1464 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 17:44:59.850  1018  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
07-12 17:44:59.850  1018  1464 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.850  1018  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.850  1018  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.860  6011  6011 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:59.860  6011  6011 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:59.860  1018  1679 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-12 17:44:59.860  1018  1679 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.860  1018  1679 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.860  1018  1679 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.870  1018  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-12 17:44:59.870  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.870  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.870  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.880  5724  5724 I Mms/MmsApp:  start initViewCache mms
07-12 17:44:59.890  5724  5724 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1856.450781
07-12 17:44:59.890  5724  5724 D Mms/ComposeMessageFragment: fillCache, easy = false
07-12 17:44:59.890  6011  6011 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 17:44:59.890  6011  6011 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-12 17:44:59.910  6011  6011 I MultiDex: VM with version 2.1.0 has multidex support
07-12 17:44:59.910  6011  6011 I MultiDex: install
07-12 17:44:59.910  6011  6011 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-12 17:44:59.930  6011  6011 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-12 17:44:59.930  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.930  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:44:59.930  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:44:59.950  6011  6011 D WearableService: callingUid 10011, callindPid: 6011
07-12 17:44:59.980  1600  2417 E MDM     : [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-12 17:44:59.990  1018  1096 V AlarmManager: waitForAlarm result :8
07-12 17:45:00.000  1018  1224 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 17:45:00.000  1018  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
07-12 17:45:00.000  1018  1224 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.000  1018  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.000  1018  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.000  1018  1679 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
07-12 17:45:00.000  1018  1679 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
07-12 17:45:00.000  1018  1679 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
07-12 17:45:00.000  1018  1679 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
07-12 17:45:00.000  5724  5724 D AbsListView: Get MotionRecognitionManager
07-12 17:45:00.000  1623  3832 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-12 17:45:00.000  1018  1031 D MotionRecognitionService:  ssp status : false
07-12 17:45:00.000  1018  1679 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.000  1018  1679 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.000  1018  1679 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.010  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.010  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.010  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.010  5724  5724 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 123.98401
07-12 17:45:00.010  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.010  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.010  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.010  6009  6009 D AndroidRuntime: 
07-12 17:45:00.010  6009  6009 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-12 17:45:00.010  1623  1623 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-12 17:45:00.020  6009  6009 D AndroidRuntime: CheckJNI is OFF
07-12 17:45:00.020  6009  6009 D AndroidRuntime: readGMSProperty: start
07-12 17:45:00.020  6009  6009 D AndroidRuntime: readGMSProperty: already setted!!
07-12 17:45:00.020  6009  6009 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-12 17:45:00.020  6009  6009 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-12 17:45:00.020  6009  6009 D AndroidRuntime: readGMSProperty: end
07-12 17:45:00.020  6009  6009 D AndroidRuntime: addProductProperty: start
07-12 17:45:00.020  1018  1224 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.020  1018  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.020  1018  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.020  1018  1678 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.030  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:45:00.020  1018  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.030  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
07-12 17:45:00.020  1018  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.030  3231  3231 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
07-12 17:45:00.030  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.030  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.030  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.030  1018  1464 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.030  1018  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.030  1018  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.040  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.040  1018  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.040  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.040  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.040  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.040  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.050  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.050  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.050  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.060  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.060  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.060  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.060  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-12 17:45:00.070  1600  2556 E MDM     : [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-12 17:45:00.070  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.070  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.070  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.070  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.070  1018  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.070  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.070  1018  1224 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.070  1018  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.070  1018  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.080  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:45:00.080  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
07-12 17:45:00.080  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.080  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.080  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.080  3231  6037 D LocationInitializer: Restart initialization of location
07-12 17:45:00.080  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.080  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.080  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.090  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 17:45:00.090  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
07-12 17:45:00.090  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.090  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:00.090  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
07-12 17:45:00.100  5724  5724 D Mms/BubbleViewCache: fillCache bubble = 1
07-12 17:45:00.160  6009  6009 E AffinityControl: AffinityControl: registerfunction enter
07-12 17:45:00.180  6009  6009 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 17:45:00.190  1018  1480 E PersonaManagerService: inState():  stateMachine is null !!
07-12 17:45:00.190  1018  1480 I PersonaManagerService: PersonaId don't exist
07-12 17:45:00.190  1018  1480 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-12 17:45:00.190  1018  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-12 17:45:00.210  1018  1480 W ActivityManager: mDVFSHelper.acquire()
07-12 17:45:00.220  1018  1480 D FocusedStackFrame: Set to : 0
07-12 17:45:00.220  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-12 17:45:00.220  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-12 17:45:00.230  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.230  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.230  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.230  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.240  1018  1480 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6043 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-12 17:45:00.240  1018  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-12 17:45:00.240  1018  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-12 17:45:00.240  1018  1480 D InputDispatcher: Focused application set to: xxxx
07-12 17:45:00.240  6043  6043 E Zygote  : MountEmulatedStorage()
07-12 17:45:00.240  6043  6043 I libpersona: KNOX_SDCARD checking this for 10151
07-12 17:45:00.240  6043  6043 E Zygote  : v2
07-12 17:45:00.240  6043  6043 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:00.240  1018  1480 D InputDispatcher: Focus left window: 1481
07-12 17:45:00.240  6043  6043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:00.240  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-12 17:45:00.240  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-12 17:45:00.240  6009  6009 D AndroidRuntime: Shutting down VM
07-12 17:45:00.250   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
07-12 17:45:00.250  6043  6043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:00.250  6043  6043 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-12 17:45:00.260  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-12 17:45:00.260  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 17:45:00.260  6043  6043 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:00.260  6043  6043 D ActivityThread: Added TimaKeyStore provider
07-12 17:45:00.270  1018  1138 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-12 17:45:00.270  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:45:00.290  1018  1138 D PersonaManager: isKioskContainerExistOnDevice
07-12 17:45:00.300  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-12 17:45:00.320   258  1104 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-12 17:45:00.330  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{10fee3dc token=android.os.BinderProxy@d614378 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-12 17:45:00.330  1481  1481 D Launcher: onTrimMemory. Level: 20
07-12 17:45:00.400  6043  6043 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-12 17:45:00.410  6043  6043 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1392-1393)
07-12 17:45:00.410  6043  6043 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:00.450  6043  6043 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {245d0add}
07-12 17:45:00.450  6009  6009 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-12 17:45:00.460  6043  6043 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:45:00.460  6043  6043 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 17:45:00.500  6043  6043 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 17:45:00.500  6043  6043 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:45:00.500  6043  6043 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 17:45:00.550  6043  6062 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-12 17:45:00.570  6043  6043 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-12 17:45:00.570  6043  6043 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-12 17:45:00.570  6043  6043 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-12 17:45:00.580  6043  6043 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-12 17:45:00.580  6043  6043 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-12 17:45:00.580  6043  6043 I Adreno-EGL: Build Date: 04/06/15 Mon
07-12 17:45:00.580  6043  6043 I Adreno-EGL: Local Branch: 
07-12 17:45:00.580  6043  6043 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-12 17:45:00.580  6043  6043 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-12 17:45:00.580  6043  6043 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-12 17:45:00.730  6043  6071 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-12 17:45:00.780  6043  6043 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:45:00.790  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{12388ad2 u0 com.test.thalitest/.MainActivity t98}
,07-12 17:45:00.790  6043  6043 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 17:45:00.800  6043  6043 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-12 17:45:00.800  6043  6043 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-12 17:45:00.810  6043  6043 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-12 17:45:00.810   292   292 E SMD     : DCD OFF,
,07-12 17:45:00.820  6043  6043 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:45:00.820  6043  6043 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:45:00.870  6043  6084 D OpenGLRenderer: Render dirty regions requested: true
,07-12 17:45:00.870  1018  1500 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-12 17:45:00.870  1018  1500 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-12 17:45:00.870  1018  1500 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-12 17:45:00.870  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-12 17:45:00.870  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,07-12 17:45:00.880  6043  6043 V ActivityThread: updateVisibility : ActivityRecord{53f547c token=android.os.BinderProxy@f5c624e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-12 17:45:00.890  6043  6043 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-12 17:45:00.890  6043  6043 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-12 17:45:00.890   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,07-12 17:45:00.910  1018  1480 D InputDispatcher: Focus entered window: 6043
,07-12 17:45:00.910  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-12 17:45:00.910  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-12 17:45:00.910  6043  6043 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-12 17:45:00.910  6043  6084 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 17:45:00.920  6043  6084 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-12 17:45:00.920  6043  6084 D OpenGLRenderer: Enabling debug mode 0
,07-12 17:45:00.940  1018  1479 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
07-12 17:45:00.940  1174  1174 I StatusBar: Icon Only
07-12 17:45:00.950  1174  1174 D PanelView: There is/are notification(s) 
,07-12 17:45:00.950  6043  6043 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f5c624e time:121932
,07-12 17:45:00.950  1018  6086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 17:45:00.950  6043  6043 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-12 17:45:00.960  1018  1048 I ActivityManager: Displayed Component not be shown by security: +669ms (total +14s37ms),
07-12 17:45:00.960  1018  1048 W ActivityManager: mDVFSHelper.release()
07-12 17:45:00.960  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12388ad2 u0 com.test.thalitest/.MainActivity t98} time:121946
,07-12 17:45:00.970  1783  1783 I SamsungIME: getCurrentCandidateView
,07-12 17:45:00.970   258   443 I SurfaceFlinger: id=11 Removed uhalitest (7/9),
07-12 17:45:00.970   258  1102 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
,07-12 17:45:01.070  6043  6043 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6043
,07-12 17:45:01.120  1783  1783 D SamsungIME: Dismiss ExpandCandiate
,07-12 17:45:01.210  6043  6043 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 17:45:01.270  1783  1783 I SamsungIME: getDebugLevel  : 0x4f4c
,07-12 17:45:01.300  1783  1783 I SamsungIME: getDebugLevel  : 0x4f4c
,07-12 17:45:01.310  1783  1783 I SamsungIME: KeybaordView init() : load resources
,07-12 17:45:01.320  6043  6089 D jxcore_app_log: JniHelper::setJavaVM(0xb8b862f0), pthread_self() = -1190257528
,07-12 17:45:01.330  6043  6089 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:45:01.330  6043  6089 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:45:01.330  6043  6089 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:45:01.330  6043  6089 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:45:01.330  6043  6089 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 17:45:01.330  6043  6089 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f3ed4ac added. We now have 1 listener(s)
,07-12 17:45:01.340  6043  6089 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,07-12 17:45:01.340  6043  6089 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,07-12 17:45:01.340  1783  1783 I SamsungIME: getCurrentKeyboard
07-12 17:45:01.340  1783  1783 I SamsungIME: getTextKeyboard
,07-12 17:45:01.340  6043  6089 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:01.340  6043  6089 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:45:01.340  1018  2738 D SSRM:n  : SIOP:: AP = 390
,07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 17:45:01.350  6043  6089 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9ad57b added. We now have 1 listener(s)
,07-12 17:45:01.350  6043  6089 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:01.350  6043  6089 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 17:45:01.350  6043  6089 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-12 17:45:01.350  6043  6089 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:01.350  6043  6089 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-12 17:45:01.350  6043  6089 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 17:45:01.350  6043  6089 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 17:45:01.360  6043  6089 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:01.360  6043  6089 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,07-12 17:45:01.360  6043  6089 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:01.360  6043  6089 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:01.360  6043  6089 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:45:01.360  6043  6089 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:01.360  6043  6089 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 17:45:01.370  1783  1783 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-12 17:45:01.400  6043  6043 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 17:45:01.970  6043  6094 W jxcore-log: Initializing JXcore engine
07-12 17:45:01.970  6043  6094 W jxcore-log: JXcore engine is ready
,07-12 17:45:02.030  1875  1875 E audit   : type=1400 msg=audit(1468338302.030:203): avc:  denied  { ioctl } for  pid=6094 comm="Thread-1103" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 17:45:02.030  1875  1875 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:02.030  1875  1875 E audit   : type=1300 msg=audit(1468338302.030:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9dbfe8f8 items=0 ppid=313 ppcomm=main pid=6094 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1103" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-12 17:45:02.030  1875  1875 E audit   : type=1320 msg=audit(1468338302.030:203): 
,07-12 17:45:02.040  6043  6094 W jxcore-log: Starting JXcore engine
,07-12 17:45:02.150  6043  6094 W jxcore-log: Platform android
07-12 17:45:02.150  6043  6094 W jxcore-log: 
07-12 17:45:02.150  6043  6094 W jxcore-log: Process ARCH arm
07-12 17:45:02.150  6043  6094 W jxcore-log: 
,07-12 17:45:02.360  6043  6094 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:45:02.360  6043  6094 I jxcore-log: 
,07-12 17:45:02.360  6043  6094 W jxcore-log: JXcore engine is started
,07-12 17:45:02.360  6043  6089 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:45:02.370  6043  6043 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:45:02.370  6043  6094 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-12 17:45:02.370  6043  6094 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-12 17:45:02.380  6043  6043 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-12 17:45:02.380  6043  6043 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-12 17:45:02.380  1018  1565 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-12 17:45:02.380  1018  1565 D FocusedStackFrame: Set to : 0
07-12 17:45:02.380  1018  1565 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-12 17:45:02.380  1018  1565 D InputDispatcher: Focused application set to: xxxx
07-12 17:45:02.380  1018  1565 D InputDispatcher: Focus left window: 6043
07-12 17:45:02.390  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-12 17:45:02.390  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-12 17:45:02.400  6043  6043 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-12 17:45:02.400  6043  6089 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
07-12 17:45:02.400  6043  6043 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-12 17:45:02.400  6043  6043 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:02.400  6043  6043 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:02.400  6043  6043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:02.400  6043  6043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:02.400  6043  6043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f3ed4ac removed from the list
07-12 17:45:02.400  6043  6043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:02.400  6043  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9ad57b removed from the list
07-12 17:45:02.400  6043  6043 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:02.400  6043  6043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-12 17:45:02.400  6043  6043 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:45:02.410   258   437 I SurfaceFlinger: id=12 Removed NainActivit (6/8),
,07-12 17:45:02.410   258   443 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,07-12 17:45:02.420  1018  1479 W ActivityManager: mDVFSHelper.acquire()
,07-12 17:45:02.430  1018  1479 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-12 17:45:02.450  1481  1481 D Launcher: onRestart, Launcher: 539260889
,07-12 17:45:02.450  1481  1481 D Launcher: onStart, Launcher: 539260889
07-12 17:45:02.450  1481  1481 D Launcher.HomeView: onStart
,07-12 17:45:02.450  1481  1481 D Launcher: onResume, Launcher: 539260889
,07-12 17:45:02.450  1018  1565 D SettingsProvider: name = kids_home_mode
,07-12 17:45:02.450  1018  1565 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 17:45:02.450  1018  1565 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 17:45:02.450  1018  1565 D SettingsProvider: selectionArgs: false
07-12 17:45:02.450  1018  1565 D SettingsProvider: selectionArgs: 10006
07-12 17:45:02.450  1018  1565 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-12 17:45:02.450  1018  1565 D SettingsProvider: ret = -1
07-12 17:45:02.450  1481  1481 D Launcher.HomeView: onResume
,07-12 17:45:02.460  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-12 17:45:02.460  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:02.460  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.460  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-12 17:45:02.470  1481  1481 D MenuAppsGridFragment: onResume
,07-12 17:45:02.470  1018  1138 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
07-12 17:45:02.470  1018  1138 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-12 17:45:02.470  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-12 17:45:02.470  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:02.470  1018  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.470  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-12 17:45:02.470  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-12 17:45:02.470  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:02.470  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.470  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-12 17:45:02.480  4973  4973 D GalleryCacheReady: Receive : home resume
,07-12 17:45:02.480  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:02.480  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.480  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-12 17:45:02.490  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:02.490  5724  5724 D Mms/UIEventReceiver: ui event
,07-12 17:45:02.490  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.490  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-12 17:45:02.490  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,07-12 17:45:02.490  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.490  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.490  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.490  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:02.500  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6099 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-12 17:45:02.500  6099  6099 E Zygote  : MountEmulatedStorage()
07-12 17:45:02.500  6099  6099 I libpersona: KNOX_SDCARD checking this for 10089
07-12 17:45:02.500  6099  6099 E Zygote  : v2
07-12 17:45:02.500  6099  6099 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:02.510  1018  1043 W ActivityManager: userId = 0, bbcId = -10000,
07-12 17:45:02.510  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.510  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-12 17:45:02.510  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-12 17:45:02.510  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.510  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:02.510  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.510  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:02.510  6099  6099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:02.510  6099  6099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:02.520  6099  6099 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-12 17:45:02.530  6108  6108 E Zygote  : MountEmulatedStorage()
07-12 17:45:02.530  6108  6108 I libpersona: KNOX_SDCARD checking this for 10139
07-12 17:45:02.530  6108  6108 E Zygote  : v2
07-12 17:45:02.530  6108  6108 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:02.530  6108  6108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-12 17:45:02.530  6108  6108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:02.530  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6108 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
07-12 17:45:02.540  6108  6108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:45:02.540  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
07-12 17:45:02.540  1018  1466 D ActivityManager: handle home activity for 0
07-12 17:45:02.540  1018  1466 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,07-12 17:45:02.540  1018  1466 D KnoxTimeoutHandler: post home show event for user 0
07-12 17:45:02.540  1018  1466 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-12 17:45:02.540  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-12 17:45:02.540  1018  1466 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-12 17:45:02.540  1018  1466 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false,
07-12 17:45:02.540  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-12 17:45:02.540  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-12 17:45:02.540  1481  1481 D Launcher.HomeView: onPause
07-12 17:45:02.540  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-12 17:45:02.550  6099  6099 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-12 17:45:02.550  6099  6099 D ActivityThread: Added TimaKeyStore provider,
,07-12 17:45:02.550  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:02.560  1018  1480 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-12 17:45:02.550  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.550  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-12 17:45:02.560   258   258 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,07-12 17:45:02.560  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:02.560  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.560  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-12 17:45:02.560  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-12 17:45:02.570  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-12 17:45:02.570  1018  1030 D InputDispatcher: Focus entered window: 1481
,07-12 17:45:02.570  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-12 17:45:02.570  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-12 17:45:02.570  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-12 17:45:02.570  6108  6108 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:02.580  6099  6099 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 17:45:02.580  6108  6108 D ActivityThread: Added TimaKeyStore provider
07-12 17:45:02.580  6099  6099 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-12 17:45:02.580  2487  2487 D Recents_RecreateReceiver: onReceive by home
,07-12 17:45:02.580  1481  1481 D Launcher.HomeView: onStop
07-12 17:45:02.580  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{10fee3dc token=android.os.BinderProxy@d614378 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-12 17:45:02.590  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:02.590  1018  1224 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-12 17:45:02.590  1018  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.590  1018  1138 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-12 17:45:02.590  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-12 17:45:02.590  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.590  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.590  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.590  1018  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.590  1018  6130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 17:45:02.590  6043  6043 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-12 17:45:02.590  1783  1783 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-12 17:45:02.600  1174  1174 I StatusBar: Icon Only
07-12 17:45:02.600  1174  1174 D PanelView: There is/are notification(s) 
,07-12 17:45:02.610  6132  6132 E Zygote  : MountEmulatedStorage()
07-12 17:45:02.610  6132  6132 E Zygote  : v2
07-12 17:45:02.610  6132  6132 I libpersona: KNOX_SDCARD checking this for 10084
07-12 17:45:02.610  6132  6132 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:02.610  6132  6132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-12 17:45:02.610  6132  6132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:02.610  6132  6132 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-12 17:45:02.620  1018  1138 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6132 uid=10084 gids={50084, 9997} abi=armeabi-v7a,
,07-12 17:45:02.620  6108  6108 V TaskCloserActivity: TaskCloserActivity enter()
,07-12 17:45:02.620  1623  1623 I ConfigService: onDestroy
,07-12 17:45:02.630  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d614378 time:123614
,07-12 17:45:02.640  6108  6108 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-12 17:45:02.640  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:02.640  1018  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-12 17:45:02.640  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
07-12 17:45:02.640  1018  1466 I ActivityManager: Killing 5603:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-12 17:45:02.650  6132  6132 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:02.650  6132  6132 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:02.650  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4ca7324 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t96} time:123639
07-12 17:45:02.650  1018  1048 W ActivityManager: mDVFSHelper.release()
,07-12 17:45:02.660  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:02.660  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.660  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-12 17:45:02.660  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-12 17:45:02.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:02.660  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:02.670  6132  6132 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 17:45:02.680  1018  1565 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6149 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-12 17:45:02.680  6149  6149 E Zygote  : MountEmulatedStorage()
07-12 17:45:02.680  6149  6149 I libpersona: KNOX_SDCARD checking this for 10135
07-12 17:45:02.680  6149  6149 E Zygote  : v2
07-12 17:45:02.680  6149  6149 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:02.680  1018  1565 I ActivityManager: Killing 5385:com.samsung.android.sm/1000 (adj 15): empty #21
,07-12 17:45:02.680  6149  6149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:02.680  6096  6096 D AndroidRuntime: 
07-12 17:45:02.680  6096  6096 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-12 17:45:02.680  6149  6149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:02.680  6096  6096 D AndroidRuntime: CheckJNI is OFF
,07-12 17:45:02.680  6096  6096 D AndroidRuntime: readGMSProperty: start
07-12 17:45:02.680  6096  6096 D AndroidRuntime: readGMSProperty: already setted!!
07-12 17:45:02.680  6096  6096 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-12 17:45:02.680  6096  6096 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-12 17:45:02.680  6096  6096 D AndroidRuntime: readGMSProperty: end
07-12 17:45:02.680  6096  6096 D AndroidRuntime: addProductProperty: start
07-12 17:45:02.680  6149  6149 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:45:02.700  1018  1500 I ActivityManager: Killing 5657:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,07-12 17:45:02.700  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-12 17:45:02.710  6149  6149 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:02.710  6149  6149 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:02.710  1018  1224 D PersonaManager: isKioskContainerExistOnDevice
,07-12 17:45:02.730  6149  6149 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,07-12 17:45:02.730  6149  6149 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 17:45:02.730  6149  6149 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-12 17:45:02.730  6149  6149 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-12 17:45:02.730  6149  6149 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-12 17:45:02.750  1018  1500 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,07-12 17:45:02.760  1018  1500 I ActivityManager: Killing 5681:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,07-12 17:45:02.760  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:02.760  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:02.760  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-12 17:45:02.760  6108  6108 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-12 17:45:02.810  6096  6096 E AffinityControl: AffinityControl: registerfunction enter
,07-12 17:45:02.810   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,07-12 17:45:02.820  5754  5754 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-12 17:45:02.830  1018  1480 I ActivityManager: Killing 5747:com.sec.pcw.device/1000 (adj 15): empty #21
,07-12 17:45:02.830  6096  6096 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-12 17:45:02.840  1018  1466 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-12 17:45:02.840  1018  1466 D PackageManager: START PACKAGE DELETE: observer{948933805}
07-12 17:45:02.840  1018  1466 D PackageManager: pkg{<packageName>}
07-12 17:45:02.840  1018  1466 D PackageManager: user{0}
07-12 17:45:02.840  1018  1466 D PackageManager: caller{2000}
07-12 17:45:02.840  1018  1466 D PackageManager: flags{2}
07-12 17:45:02.840  1018  1466 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-12 17:45:02.840  1018  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-12 17:45:02.840  1018  1466 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-12 17:45:02.840  1018  1466 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-12 17:45:02.840  1018  1466 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-12 17:45:02.840  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-12 17:45:02.840  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-12 17:45:02.840  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
07-12 17:45:02.840  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-12 17:45:02.840  1018  1057 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
,07-12 17:45:02.850  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
,07-12 17:45:02.850  1018  1043 I ActivityManager: Killing 6043:com.test.thalitest/u0a151 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-12 17:45:02.970  1018  1057 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
,07-12 17:45:02.980  1018  1057 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,07-12 17:45:02.990  1018  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-12 17:45:03.020  5815  5815 I art     : Explicit concurrent mark sweep GC freed 18978(1025KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 853us total 34.476ms
,07-12 17:45:03.040  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,07-12 17:45:03.040  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-12 17:45:03.040  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 17:45:03.040  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-12 17:45:03.040  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-12 17:45:03.040  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
,07-12 17:45:03.050  1600  1790 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 17:45:03.050  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,07-12 17:45:03.050  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-12 17:45:03.060  1783  1783 E SamsungIME: mOCRHelper is null
,07-12 17:45:03.070  4024  4024 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 12 17:45:03 GMT+02:00 2016
,07-12 17:45:03.090  1018  1565 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-12 17:45:03.090  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.090  1434  1434 D PersonaManager: isKioskContainerExistOnDevice
,07-12 17:45:03.090  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.090  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-12 17:45:03.090  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-12 17:45:03.100  1434  1434 D RegisteredServicesCache: empty dynamic service
,07-12 17:45:03.100  4024  4024 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-12 17:45:03.100  1018  1480 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-12 17:45:03.100  1018  1480 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-12 17:45:03.110  1018  1125 V NetworkStats: removeUidsLocked() for UIDs [10151]
07-12 17:45:03.110  1018  1125 V NetworkStats: performPollLocked(flags=0x3)
,07-12 17:45:03.120  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
07-12 17:45:03.120  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-12 17:45:03.130  4024  4024 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-12 17:45:03.130  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-12 17:45:03.130  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-12 17:45:03.130  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-12 17:45:03.130  1018  1125 V NetworkStats: performPollLocked() took 20ms
,07-12 17:45:03.130  1018  1464 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,07-12 17:45:03.130  1018  1464 D SecContentProvider2: mCursor = null
,07-12 17:45:03.130  4024  4024 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-12 17:45:03.130  1018  1042 W TextServicesManagerService: no available spell checker services found
,07-12 17:45:03.130  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.130  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.130  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.130  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.150  6175  6175 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.150  6175  6175 I libpersona: KNOX_SDCARD checking this for 10090
07-12 17:45:03.150  6175  6175 E Zygote  : v2
07-12 17:45:03.150  6175  6175 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:03.150  6175  6175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:03.150  1018  1480 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6175 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-12 17:45:03.150  6175  6175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-12 17:45:03.150  6175  6175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.170   313   313 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 20.096ms
,07-12 17:45:03.180  6175  6175 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.180  6175  6175 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.180   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 16.178ms
,07-12 17:45:03.200  4024  4024 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-12 17:45:03.200   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.457ms
07-12 17:45:03.200  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-12 17:45:03.200  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-12 17:45:03.200  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.200  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.200  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.210  4024  6174 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-12 17:45:03.210  4024  6174 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-12 17:45:03.220  4024  6174 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-12 17:45:03.220  6190  6190 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.220  6190  6190 I libpersona: KNOX_SDCARD checking this for 10032
07-12 17:45:03.220  6190  6190 E Zygote  : v2
07-12 17:45:03.220  6190  6190 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:03.220  6190  6190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:03.220  1018  1043 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6190 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 17:45:03.220  6190  6190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:03.220  6190  6190 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-12 17:45:03.230  4024  6174 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
07-12 17:45:03.240  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
07-12 17:45:03.240  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-12 17:45:03.240  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicy: uID is 10151
07-12 17:45:03.240  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
07-12 17:45:03.240  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-12 17:45:03.240  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-12 17:45:03.240  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-12 17:45:03.240  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-12 17:45:03.250  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:03.250  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:03.250  1018  1018 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
,07-12 17:45:03.250  6199  6199 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.250  6199  6199 E Zygote  : v2
07-12 17:45:03.250  6199  6199 I libpersona: KNOX_SDCARD checking this for 10052
07-12 17:45:03.250  6199  6199 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:03.260  6199  6199 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:03.260  6199  6199 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:03.260  6199  6199 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.260  1018  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6199 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
07-12 17:45:03.260  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.270  1018  1126 D NtpTrustedTime: forceRefresh() from cache miss
,07-12 17:45:03.280  1434  1434 D RegisteredComponentCache: Collect Tech packages for Knox
07-12 17:45:03.280  6190  6190 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:03.280  6190  6190 D ActivityThread: Added TimaKeyStore provider
07-12 17:45:03.280   280   983 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
07-12 17:45:03.280   280   983 D Netd    : getNetworkForDns: using netid 0 for uid 1000
07-12 17:45:03.280  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
07-12 17:45:03.280   280   983 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
07-12 17:45:03.280   280   983 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,07-12 17:45:03.280  1018  1126 D NtpTrustedTime: forceRefresh Fail.,
,07-12 17:45:03.290  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.290  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.290  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.290  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,07-12 17:45:03.290  6199  6199 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.290  6199  6199 D ActivityThread: Added TimaKeyStore provider
07-12 17:45:03.290  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.310  6222  6222 E Zygote  : MountEmulatedStorage()
,07-12 17:45:03.310  6222  6222 E Zygote  : v2,
07-12 17:45:03.310  1434  1434 D PersonaManager: isKioskContainerExistOnDevice
07-12 17:45:03.310  1018  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6222 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-12 17:45:03.310  6222  6222 I libpersona: KNOX_SDCARD checking this for 10098
07-12 17:45:03.310  6222  6222 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:03.320  6222  6222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:03.320  6222  6222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:03.320  6222  6222 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.340  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-12 17:45:03.340  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-12 17:45:03.340  1018  1018 V EnterpriseBillingPolicy: uID is 10151
07-12 17:45:03.340  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
07-12 17:45:03.340  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-12 17:45:03.340  1018  2738 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,07-12 17:45:03.350  1018  1164 D TaskPersister: removeObsoleteFile: deleting file=98_task.xml
,07-12 17:45:03.350  4024  6174 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-12 17:45:03.350  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,07-12 17:45:03.350  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-12 17:45:03.350  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-12 17:45:03.350  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-12 17:45:03.350  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-12 17:45:03.360  6222  6222 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.360  4024  6174 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-12 17:45:03.360  6222  6222 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.360  4024  6174 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-12 17:45:03.370  4024  4024 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-12 17:45:03.380  6175  6175 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-12 17:45:03.380  6175  6175 D elm:15121: ELMEngine.ELMEngine( context ).
,07-12 17:45:03.380  6175  6175 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-12 17:45:03.380  1018  1678 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-12 17:45:03.380  1018  1678 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.390  1018  1678 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:03.390  1018  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-12 17:45:03.390  1018  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-12 17:45:03.390  6175  6175 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-12 17:45:03.390  3468  3468 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-12 17:45:03.400  3468  3468 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-12 17:45:03.410  3468  3468 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-12 17:45:03.410  3468  3468 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-12 17:45:03.410  3468  3468 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-12 17:45:03.410  3468  3468 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-12 17:45:03.410  3468  3468 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-12 17:45:03.410  3468  3468 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:03.410  3468  3468 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 17:45:03.410  3468  3468 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-12 17:45:03.410  6175  6175 D elm:15121: ElmAgentService : onCreate()
07-12 17:45:03.410  3468  3468 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:03.410  3468  3468 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:45:03.410  3468  3468 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-12 17:45:03.410  3468  3468 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-12 17:45:03.410  6175  6237 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-12 17:45:03.410  6175  6237 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-12 17:45:03.410  6175  6237 D elm:15121: MDMBridge.getInstance()
,07-12 17:45:03.410  6175  6237 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-12 17:45:03.420  6175  6237 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-12 17:45:03.420  1018  1500 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,07-12 17:45:03.430  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.430  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.430  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.430  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.430  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-12 17:45:03.430  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.440  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.440  6240  6240 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.440  6240  6240 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:45:03.440  6240  6240 E Zygote  : v2
07-12 17:45:03.440  6240  6240 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:03.440  6240  6240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:03.450  6240  6240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:03.450  1018  1500 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6240 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-12 17:45:03.450  6240  6240 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.470  6175  6175 D elm:15121: ElmAgentService : onDestroy().
,07-12 17:45:03.470  1623  1623 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-12 17:45:03.470  1623  1623 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-12 17:45:03.470  1018  1057 I art     : Explicit concurrent mark sweep GC freed 52269(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 22MB/34MB, paused 6.501ms total 358.169ms
,07-12 17:45:03.480  1018  1466 I ActivityManager: Killing 5477:com.android.vending/u0a26 (adj 15): empty #21
,07-12 17:45:03.490  6240  6240 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.490  6240  6240 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.500  1018  1678 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 17:45:03.500  1018  1678 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.500  1018  1678 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.500  1018  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.500  1018  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.500  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-12 17:45:03.510  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.510  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.510  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.510  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.520  6257  6257 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.520  6257  6257 E Zygote  : v2
07-12 17:45:03.520  6257  6257 I libpersona: KNOX_SDCARD checking this for 10032
07-12 17:45:03.520  6257  6257 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:03.520  3231  3231 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-12 17:45:03.520  3231  3231 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-12 17:45:03.520  3231  3231 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 17:45:03.520  3231  3231 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-12 17:45:03.520  3231  6256 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-12 17:45:03.520  6257  6257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:03.520  6190  6255 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-12 17:45:03.520  6190  6255 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-12 17:45:03.520  3231  6256 D AccountUtils: Clearing selected account for com.test.thalitest
07-12 17:45:03.520  6257  6257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:03.520  6257  6257 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.530  1018  1565 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6257 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 17:45:03.530  1018  1565 I ActivityManager: Killing 5781:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,07-12 17:45:03.530  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-12 17:45:03.540  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.540  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.540  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.540  6190  6255 D SPPClientService: PushLog.txt file is not deleted.
07-12 17:45:03.540  6190  6255 D SPPClientService: PushLog.txt file is not deleted.
07-12 17:45:03.540  6190  6255 D SPPClientService: ============PushLog. stop!
07-12 17:45:03.540  1018  1679 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-12 17:45:03.540  3231  3231 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-12 17:45:03.540  3231  3231 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-12 17:45:03.540  3231  3231 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 17:45:03.540  3231  3231 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-12 17:45:03.550  1018  1679 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:03.550  1018  1679 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.550  1018  1679 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.560  1018  1138 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:45:03.560  1018  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.560  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.560  1018  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.560  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.560  6257  6257 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.560  6257  6257 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.570  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,07-12 17:45:03.570  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.570  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.570  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:03.580  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-12 17:45:03.580  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-12 17:45:03.590  1018  1057 D PackageManager: delete codoeFile: 
,07-12 17:45:03.590  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 17:45:03.590  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 17:45:03.590  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 17:45:03.590  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.600  1018  1057 I AASA_removePackage: UID=10151 Target=com.test.thalitest
07-12 17:45:03.600  1018  1057 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
,07-12 17:45:03.600  1018  1466 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
07-12 17:45:03.600  1018  1057 D PackageManager: result of delete: 1{948933805}
07-12 17:45:03.600  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.600  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.600  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.600  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.600  6096  6096 D AndroidRuntime: Shutting down VM
,07-12 17:45:03.600  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.610  3231  6256 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-12 17:45:03.610  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.610  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:03.610  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-12 17:45:03.630  6278  6278 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.630  6278  6278 E Zygote  : v2
07-12 17:45:03.630  6278  6278 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:45:03.630  6278  6278 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:03.630  6278  6278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:03.630  6278  6278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:03.630  6278  6278 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:45:03.630  1018  1466 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6278 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-12 17:45:03.640  1018  1466 I ActivityManager: Killing 5833:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-12 17:45:03.640  1018  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-12 17:45:03.640  1018  1057 D PackageManager: userId{-1}
07-12 17:45:03.640  1018  1057 D PackageManager: andCode{true}
,07-12 17:45:03.650  1018  1224 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-12 17:45:03.650  1018  1224 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.650  1018  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.650  1018  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:03.650  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.650  1018  1500 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-12 17:45:03.650  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.650  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.650  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.650  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.650  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.660  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-12 17:45:03.660  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:03.660  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.660  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.670  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:03.670  1018  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-12 17:45:03.670  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-12 17:45:03.670  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.670  6278  6278 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:03.670  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.670  6278  6278 D ActivityThread: Added TimaKeyStore provider
07-12 17:45:03.670  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.670  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.680  6295  6295 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.680  6295  6295 E Zygote  : v2
07-12 17:45:03.680  6295  6295 I libpersona: KNOX_SDCARD checking this for 10055
07-12 17:45:03.680  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:03.680  6295  6295 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:03.680  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-12 17:45:03.680  6295  6295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:03.690  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:03.690  6295  6295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:03.690  1018  1479 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6295 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,07-12 17:45:03.690  6295  6295 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:45:03.690  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
07-12 17:45:03.690  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.690  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.690  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.690  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.700  6199  6276 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-12 17:45:03.700  6257  6296 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-12 17:45:03.710  3231  6294 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-12 17:45:03.710  3231  6294 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,07-12 17:45:03.710  3231  6294 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,07-12 17:45:03.710  3231  6294 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,07-12 17:45:03.720  6308  6308 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.720  6308  6308 E Zygote  : v2
07-12 17:45:03.720  6308  6308 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:45:03.720  6308  6308 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:03.720  6308  6308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:03.720  6257  6296 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-12 17:45:03.720  6308  6308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-12 17:45:03.720  6308  6308 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.720  1018  1031 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6308 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-12 17:45:03.720  3231  6294 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-12 17:45:03.720  3231  6294 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,07-12 17:45:03.730  6295  6295 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:03.730  3231  6294 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-12 17:45:03.730  6295  6295 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.730  1018  1678 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 17:45:03.730  1018  1678 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.740  6257  6296 D SPPClientService: PushLog.txt file is not deleted.
07-12 17:45:03.740  6257  6296 D SPPClientService: PushLog.txt file is not deleted.
07-12 17:45:03.740  6257  6296 D SPPClientService: ============PushLog. stop!
,07-12 17:45:03.740  1018  1678 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:03.740  1018  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.740  1018  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.740  3231  6294 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-12 17:45:03.740  3231  6294 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,07-12 17:45:03.750  3231  6294 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,07-12 17:45:03.750  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
07-12 17:45:03.750  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-12 17:45:03.760  6308  6308 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.760  6308  6308 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.770  1018  1679 D ActivityManager: bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
07-12 17:45:03.770  1018  1679 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.770  1018  1679 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.770  1018  1679 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.770  1018  1679 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.770  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,07-12 17:45:03.770  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.770  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.770  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.770  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.790  6331  6331 E Zygote  : MountEmulatedStorage(),
07-12 17:45:03.790  6331  6331 I libpersona: KNOX_SDCARD checking this for 10036
07-12 17:45:03.790  6331  6331 E Zygote  : v2
07-12 17:45:03.790  6331  6331 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:03.790  6331  6331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:03.790  1018  1031 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6331 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 17:45:03.790  1018  1031 I ActivityManager: Killing 5843:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,07-12 17:45:03.800  6295  6295 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-12 17:45:03.800  6331  6331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:03.800  6331  6331 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.810  6308  6308 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-12 17:45:03.810  6308  6308 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-12 17:45:03.810  6308  6308 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
07-12 17:45:03.810  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:45:03.810  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
07-12 17:45:03.810  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.810  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.810  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:03.810   324   324 I ServiceManager: Waiting for service AtCmdFwd...
07-12 17:45:03.810  6096  6096 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-12 17:45:03.820   292   292 E SMD     : DCD OFF
,07-12 17:45:03.820  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-12 17:45:03.820  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.820  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.820  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.830  1623  1623 I ConfigService: onCreate
07-12 17:45:03.830  1623  1623 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-12 17:45:03.830  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:45:03.830  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
07-12 17:45:03.830  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:03.830  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.840  6278  6278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
07-12 17:45:03.830  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.840  1018  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-12 17:45:03.840  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.840  1018  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.840  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-12 17:45:03.840  1018  1678 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,07-12 17:45:03.840  3231  3231 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-12 17:45:03.840  1018  1678 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.850  1018  1678 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:45:03.850  1018  1678 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:03.850  1018  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,07-12 17:45:03.850  1623  1623 I ConfigService: onBind returning update interface
,07-12 17:45:03.850  1018  1500 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:45:03.850  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-12 17:45:03.850  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.850  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.850  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.860  6331  6331 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.860  6331  6331 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.860  1623  1623 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 17:45:03.860  1623  1623 I ConfigService: onBind returning service broker
07-12 17:45:03.860  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,07-12 17:45:03.870  6308  6308 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-12 17:45:03.870  6308  6308 I PCWCLIENTTRACE_PushUtil: sales region : global
07-12 17:45:03.870  6308  6308 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-12 17:45:03.870  6308  6308 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-12 17:45:03.870  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.870  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.870  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.870  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.880  6350  6350 E Zygote  : MountEmulatedStorage(),
07-12 17:45:03.880  6350  6350 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:45:03.880  6350  6350 E Zygote  : v2
,07-12 17:45:03.880  6350  6350 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:03.880  6350  6350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:03.890  1018  1565 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6350 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,07-12 17:45:03.890  1018  1138 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 17:45:03.890  1018  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.disconnect.FitCleanupService; callingUser = 0; userId(target) = 0,
07-12 17:45:03.890  6350  6350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:03.890  6295  6295 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
07-12 17:45:03.890  6350  6350 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.890  6295  6295 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-12 17:45:03.890  6295  6295 D UserAnalysis: Create SecureDbHelper
,07-12 17:45:03.890  1018  1138 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:03.890  1018  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-12 17:45:03.890  1018  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-12 17:45:03.890  1018  1138 I ActivityManager: Killing 5700:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,07-12 17:45:03.900  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,07-12 17:45:03.900  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.900  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.900  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.900  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.910  6350  6350 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:03.910  3231  3246 I art     : Background sticky concurrent mark sweep GC freed 2281(180KB) AllocSpace objects, 3(48KB) LOS objects, 2% free, 9MB/9MB, paused 39.915ms total 106.776ms
,07-12 17:45:03.910  3231  3243 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+auto_complete_suggestions_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-12 17:45:03.920  3231  3243 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+help_responses_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-12 17:45:03.920  3231  3243 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+metrics_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-12 17:45:03.920  6350  6350 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.920  6361  6361 E Zygote  : MountEmulatedStorage()
07-12 17:45:03.920  6361  6361 E Zygote  : v2
07-12 17:45:03.920  6361  6361 I libpersona: KNOX_SDCARD checking this for 10026
07-12 17:45:03.920  6361  6361 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:03.930  1018  1565 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6361 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 17:45:03.930  6361  6361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:03.940  6361  6361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:03.940  6361  6361 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 17:45:03.950   313   313 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 30.402ms
07-12 17:45:03.950  1018  1565 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,07-12 17:45:03.960  6361  6361 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:03.960  6361  6361 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:03.970  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.970  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.970  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:03.970  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:03.970  1018  1464 D LocationManagerService: getProviders()=[passive, gps]
,07-12 17:45:03.970   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 18.067ms
,07-12 17:45:03.980  6350  6388 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,07-12 17:45:03.980  6350  6388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,07-12 17:45:03.990  6295  6295 D IntelligenceServiceApplication: onCreate()
07-12 17:45:03.990  6295  6295 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-12 17:45:03.990   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 666us total 19.409ms
,07-12 17:45:04.000  6295  6295 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,07-12 17:45:04.000  6295  6295 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.,
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	,at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-12 17:45:04.000  6295  6295 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908),
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-12 17:45:04.000  6295  6295 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-12 17:45:04.000  6331  6331 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/openData.db" with flag (131138) and mode_t (0) due to error (30)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/openData.db'.
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at com.msc.openprovider.OpenContentProvider.onCreate(OpenContentProvider.java:214)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-12 17:45:04.000  6331  6331 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-12 17:45:04.000  6295  6295 W SQLiteOpenHelper: Opened privacy in read-only mode
07-12 17:45:04.010  6295  6295 D IntelligenceServiceApplication: no applications having user consent for prediction
07-12 17:45:04.010  6331  6331 I SA      : [SSP] onCreated
07-12 17:45:04.010  6331  6331 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/samsungaccount.db" with flag (131138) and mode_t (0) due to error (30)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/samsungaccount.db'.
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:45:04.010  6331  6331 E SQLiteDatab,ase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at com.msc.contentprovider.SamsungServiceProvider.onCreate(SamsungServiceProvider.java:575)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-12 17:45:04.010  6331  6331 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-12 17:45:04.020  6389  6389 E Zygote  : MountEmulatedStorage()
07-12 17:45:04.020  6389  6389 E Zygote  : v2
07-12 17:45:04.020  6389  6389 I libpersona: KNOX_SDCARD checking this for 10014
07-12 17:45:04.020  6389  6389 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:04.020  1018  1565 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6389 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
07-12 17:45:04.020  6389  6389 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:04.020  1018  1224 I ActivityManager: Killing 5886:com.wsomacp/u0a23 (adj 15): empty #21
07-12 17:45:04.020  1018  1224 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
07-12 17:45:04.020  1018  1224 W BroadcastQueue: android.os.DeadObjectException
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20435)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
07-12 17:45:04.020  1018  1224 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
07-12 17:45:04.020  1018  1224 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
07-12 17:45:04.030  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.030  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.030  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.030  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.030  3231  3231 I ConfigFetchService: service connected
07-12 17:45:04.030  3231  6395 I PeopleContactsSync: CP2 sync disabled
07-12 17:45:04.030  6389  6389 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:04.030  6389  6389 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-12 17:45:04.040  6401  6401 E Zygote  : MountEmulatedStorage()
07-12 17:45:04.040  6401  6401 I libpersona: KNOX_SDCARD checking this for 10117
07-12 17:45:04.040  6401  6401 E Zygote  : v2
07-12 17:45:04.040  6401  6401 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:04.040  6401  6401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:04.040  1018  1224 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6401 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-12 17:45:04.040  1018  1224 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
07-12 17:45:04.040  6401  6401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:04.040  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.040  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.040  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.040  1018  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:04.050  6401  6401 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL

```
