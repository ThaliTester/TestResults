#### Test 84265062d118465_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-12 18:13:24.669   346  6664 D QC-time-services: Updating the TOD offset
09-12 18:13:24.669   346  6664 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249840642 to memory
09-12 18:13:24.669   346  6664 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-12 18:13:24.669   346  6664 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
09-12 18:13:24.669   346  6664 E QC-time-services: Daemon:Update to modem bit set
09-12 18:13:24.669   346  6664 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-12 18:13:24.669   346  6664 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285040642
09-12 18:13:24.669  6645  6645 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
09-12 18:13:24.669   346   562 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
09-12 18:13:24.679   346   565 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
--------- beginning of system
09-12 18:13:24.679  1019  1561 I ActivityManager: Killing 5512:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
09-12 18:13:24.689  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
09-12 18:13:24.689  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-12 18:13:24.689  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
09-12 18:13:24.699  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
09-12 18:13:24.699  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
09-12 18:13:24.699  2675  2675 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
09-12 18:13:24.699  2675  2675 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-12 18:13:24.699  2675  2675 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
09-12 18:13:24.699  2675  2675 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-12 18:13:24.699  2675  2675 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-12 18:13:24.699  2675  2675 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
09-12 18:13:24.699  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
09-12 18:13:24.709  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
09-12 18:13:24.709  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
09-12 18:13:24.709  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-12 18:13:24.709  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
09-12 18:13:24.709  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
09-12 18:13:24.719  2675  2675 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
09-12 18:13:24.729  2675  2675 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
09-12 18:13:24.729  2675  2675 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,09-12 18:13:24.759  1469  1469 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
09-12 18:13:24.759  1019  1550 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 2 receivers.size=42
09-12 18:13:24.759  1019  1550 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
09-12 18:13:24.759  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
09-12 18:13:24.769  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.769  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.769  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.769  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.779  6670  6670 E Zygote  : MountEmulatedStorage()
09-12 18:13:24.789  6670  6670 I libpersona: KNOX_SDCARD checking this for 10029
09-12 18:13:24.789  6670  6670 E Zygote  : v2
09-12 18:13:24.789  6670  6670 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:24.789  6670  6670 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:24.789  1019  1044 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6670 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-12 18:13:24.789  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
09-12 18:13:24.789  2771  2771 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
09-12 18:13:24.799  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.799  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.799  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.799  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.799  6670  6670 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:24.799  2771  2771 I AASAservice-TokenRule: parseToken()
09-12 18:13:24.799  2771  2771 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
09-12 18:13:24.799  6670  6670 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:24.799  2771  2771 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-12 18:13:24.799  2771  2771 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:24.799  2771  2771 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-12 18:13:24.799  2771  2771 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
09-12 18:13:24.799  2771  2771 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
09-12 18:13:24.799  2771  2771 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-12 18:13:24.799  2771  2771 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-12 18:13:24.799  2771  2771 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-12 18:13:24.799  2771  2771 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:24.799  2771  2771 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:24.799  2771  2771 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:24.799  2771  2771 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:24.799  2771  2771 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:24.799  2771  2771 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:24.799  2771  2771 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:24.799  2771  2771 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
09-12 18:13:24.799  2771  2771 W System.err: 	at libcore.io.Posix.open(Native Method)
09-12 18:13:24.799  2771  2771 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:13:24.799  2771  2771 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 18:13:24.799  2771  2771 W System.err: 	... 14 more
09-12 18:13:24.799  2771  2771 E AASAservice-TokenRule: parseToken() : TokenFile is null
09-12 18:13:24.799  2771  2771 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
09-12 18:13:24.799  1019  1316 I TactileAssist: enable value -1
09-12 18:13:24.799  1019  1316 I TactileAssist: internal enable value -1
09-12 18:13:24.799  1019  1316 I TactileAssist: intensity value -1
09-12 18:13:24.799  1019  1316 I TactileAssist: saveAppList value true
09-12 18:13:24.799  2771  2771 I art     : System.exit called, status: 0
09-12 18:13:24.799  2771  2771 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-12 18:13:24.809  1019  1316 I TactileAssist: List of disabled apps :
09-12 18:13:24.819   322   322 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 930us total 38.313ms
09-12 18:13:24.849   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 678us total 19.435ms
09-12 18:13:24.869   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 868us total 20.075ms
09-12 18:13:24.869  6670  6670 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:24.869  6670  6670 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:24.879  2740  2740 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
09-12 18:13:24.899  6689  6689 E Zygote  : MountEmulatedStorage()
09-12 18:13:24.899  6689  6689 I libpersona: KNOX_SDCARD checking this for 10098
09-12 18:13:24.899  6689  6689 E Zygote  : v2
09-12 18:13:24.899  6689  6689 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:24.899  6689  6689 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:24.899  1019  1044 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6689 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-12 18:13:24.909  6689  6689 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:24.909  6689  6689 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:24.919  1019  1032 I ActivityManager: Process com.samsung.aasaservice (pid 2771)(adj 0) has died(100,718)
09-12 18:13:24.919  1019  1032 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
09-12 18:13:24.919  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
09-12 18:13:24.929  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.929  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.929  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.929  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.939  6700  6700 E Zygote  : MountEmulatedStorage()
09-12 18:13:24.939  6700  6700 E Zygote  : v2
09-12 18:13:24.939  6700  6700 I libpersona: KNOX_SDCARD checking this for 10048
09-12 18:13:24.939  6700  6700 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:24.939  6700  6700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:24.939  6700  6700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:24.939  6700  6700 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 18:13:24.939  6689  6689 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:24.939  1019  1031 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6700 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
09-12 18:13:24.949  6689  6689 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:24.949  1019  1523 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-12 18:13:24.949  1019  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
09-12 18:13:24.949  1019  1523 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:24.949  1019  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:24.949  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
09-12 18:13:24.959  1019  1138 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
09-12 18:13:24.959  1858  6713 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
09-12 18:13:24.969  1858  1858 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-12 18:13:24.969  6700  6700 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:24.969  1858  1858 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
09-12 18:13:24.969  6700  6700 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:24.979  1019  3816 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:24.979  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
09-12 18:13:24.979  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:24.979  1019  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:24.979  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:24.979  1019  1316 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:24.979  1019  1316 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
09-12 18:13:24.979  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:24.979  1019  1316 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:24.979  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:24.989  6670  6720 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
09-12 18:13:24.999  2740  2740 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
09-12 18:13:24.999  1019  1563 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:24.999  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:24.999  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
09-12 18:13:24.999  1019  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:24.999  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:24.999  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-12 18:13:24.999  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.999  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.999  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:24.999  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.009  6670  6720 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-12 18:13:25.009  6670  6720 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:25.009  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.009  6670  6720 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:25.009  6670  6720 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-12 18:13:25.019  6670  6720 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-12 18:13:25.019  6670  6720 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 18:13:25.019  6670  6720 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:25.019  6670  6720 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:25.019  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.019  6670  6720 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-12 18:13:25.019  6723  6723 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.019  6723  6723 E Zygote  : v2
09-12 18:13:25.019  6723  6723 I libpersona: KNOX_SDCARD checking this for 10032
09-12 18:13:25.019  6723  6723 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.019  6723  6723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.029  6723  6723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.029  1019  1316 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6723 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:13:25.029  6723  6723 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-12 18:13:25.029  1019  1550 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:25.029  1019  1550 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 18:13:25.029  6689  6689 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
09-12 18:13:25.029  6670  6720 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:25.029  6689  6689 D PackageIntentReceiver: Not GearManger package! 
09-12 18:13:25.029  6670  6720 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:25.029  1019  1550 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.029  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.029  1019  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:25.029  1019  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:25.029  6679  6679 D AndroidRuntime: 
09-12 18:13:25.029  6679  6679 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 18:13:25.039  6679  6679 D AndroidRuntime: CheckJNI is OFF
09-12 18:13:25.039  6679  6679 D AndroidRuntime: readGMSProperty: start
09-12 18:13:25.039  6679  6679 D AndroidRuntime: readGMSProperty: already setted!!
09-12 18:13:25.039  6679  6679 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 18:13:25.039  6679  6679 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 18:13:25.039  6679  6679 D AndroidRuntime: readGMSProperty: end
09-12 18:13:25.039  6679  6679 D AndroidRuntime: addProductProperty: start
09-12 18:13:25.039  1019  1561 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
09-12 18:13:25.039  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.039  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.039  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.039  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.049  6670  6720 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 18:13:25.049  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.049  6670  6720 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-12 18:13:25.059  6670  6720 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:25.059  6670  6720 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:25.059  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.059  6670  6720 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-12 18:13:25.059  6670  6720 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 18:13:25.059  6670  6720 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:25.059  6670  6720 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:25.069  6723  6723 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.069  6723  6723 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.069  6738  6738 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.069  6738  6738 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:25.069  6738  6738 E Zygote  : v2
09-12 18:13:25.069  6738  6738 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.069  1019  1561 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6738 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:13:25.069  1019  1561 I ActivityManager: Killing 5993:com.google.android.gm/u0a99 (adj 15): empty #21
09-12 18:13:25.069  1019  1561 I ActivityManager: Killing 5658:com.google.android.music:main/u0a108 (adj 15): empty #21
09-12 18:13:25.079  6738  6738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.079  6700  6700 D Compatibility: onReceive() it will make start service
09-12 18:13:25.079  6738  6738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.079  6738  6738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:25.079  1019  1523 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-12 18:13:25.079  1019  1523 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-12 18:13:25.089  1019  1523 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.089  1019  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:25.089  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.089  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
09-12 18:13:25.089  6670  6720 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:25.089  6670  6720 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:25.089  1019  1138 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
09-12 18:13:25.089  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.089  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.089  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.089  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.099  6700  6747 D Compatibility: onHandleIntent()
09-12 18:13:25.099  6700  6747 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10170, android.intent.extra.user_handle=0}]
09-12 18:13:25.099  6670  6720 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-12 18:13:25.099  6670  6720 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:25.099  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.099  6670  6720 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:25.099  6700  6747 D Compatibility: found: 2
09-12 18:13:25.109  6670  6720 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-12 18:13:25.109  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.109  6670  6720 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:25.109  6670  6720 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:25.119  6754  6754 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.119  6754  6754 E Zygote  : v2
09-12 18:13:25.119  6754  6754 I libpersona: KNOX_SDCARD checking this for 10052
09-12 18:13:25.119  6754  6754 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.119  6754  6754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.119  6738  6738 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.119  6754  6754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.119  6738  6738 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.119  6754  6754 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 18:13:25.129  1019  1138 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6754 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-12 18:13:25.139  6700  6747 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-12 18:13:25.149  6700  6747 D Compatibility: skipping ResolveInfo{12a17c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-12 18:13:25.149  6700  6747 D Compatibility: considering ResolveInfo{170aba05 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-12 18:13:25.149  6700  6747 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
09-12 18:13:25.149  6670  6720 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-12 18:13:25.149  6670  6720 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:25.149  6700  6747 D Compatibility: enabling receiver ResolveInfo{391cea5a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-12 18:13:25.149  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.149  6670  6720 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:25.149  6700  6747 D Compatibility: enabling receiver ResolveInfo{3c53648b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-12 18:13:25.159  6670  6720 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-12 18:13:25.169  6723  6773 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-12 18:13:25.169  1019  1550 I ActivityManager: Killing 6342:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
09-12 18:13:25.169  6723  6773 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-12 18:13:25.169  6754  6754 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.169  6754  6754 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.179  6700  6747 D Compatibility: enabling receiver ResolveInfo{26a65968 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-12 18:13:25.189  6723  6773 D SPPClientService: PushLog.txt file is not deleted.
09-12 18:13:25.189  6723  6773 D SPPClientService: PushLog.txt file is not deleted.
09-12 18:13:25.189  6723  6773 D SPPClientService: ============PushLog. stop!
09-12 18:13:25.199  6700  6747 D Compatibility: enabling receiver ResolveInfo{3281f181 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-12 18:13:25.199  6700  6747 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
09-12 18:13:25.209  1019  1316 I ActivityManager: Killing 6076:com.android.vending/u0a26 (adj 15): empty #21
09-12 18:13:25.209  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
09-12 18:13:25.209  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.209  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.209  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.209  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.219  6670  6720 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 18:13:25.219  6670  6720 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-12 18:13:25.219  6670  6720 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:25.219  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.219  6670  6720 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:25.219  6778  6778 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.219  6778  6778 I libpersona: KNOX_SDCARD checking this for 10039
09-12 18:13:25.219  6778  6778 E Zygote  : v2
09-12 18:13:25.219  6778  6778 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.229  6778  6778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.229  6679  6679 E AffinityControl: AffinityControl: registerfunction enter
09-12 18:13:25.229  6778  6778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.229  1019  1316 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6778 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-12 18:13:25.229  6778  6778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:25.229  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-12 18:13:25.229  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.229  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.229  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.229  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.239  6670  6720 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-12 18:13:25.239  6670  6720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.249  6793  6793 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.249  6793  6793 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:25.249  6793  6793 E Zygote  : v2
09-12 18:13:25.249  6793  6793 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.249  6793  6793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.259  1019  1316 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6793 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:13:25.259  6679  6679 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 18:13:25.259  1019  1316 I ActivityManager: Killing 6438:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-12 18:13:25.259  6793  6793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.259  6793  6793 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:25.259  6778  6778 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.259  6778  6778 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.279  1019  1032 E PersonaManagerService: inState():  stateMachine is null !!
09-12 18:13:25.279  1019  1032 I PersonaManagerService: PersonaId don't exist
09-12 18:13:25.279  1019  1032 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-12 18:13:25.279  6670  6720 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
09-12 18:13:25.289  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 18:13:25.289  6778  6778 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:25.289  6778  6778 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:25.289  6778  6778 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:25.289  6778  6778 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-12 18:13:25.289  6778  6778 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 18:13:25.289  6778  6778 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:25.289  6778  6778 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:25.299  6793  6793 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.299  6793  6793 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.309  1019  1032 W ActivityManager: mDVFSHelper.acquire()
09-12 18:13:25.309  1019  1032 D FocusedStackFrame: Set to : 0
09-12 18:13:25.309  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.309  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.309  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.309  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.319  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 18:13:25.319  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-12 18:13:25.329  6812  6812 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.329  6812  6812 E Zygote  : v2
09-12 18:13:25.329  6812  6812 I libpersona: KNOX_SDCARD checking this for 10170
09-12 18:13:25.329  6812  6812 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.329  6812  6812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.329  1019  1032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6812 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 18:13:25.329  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-12 18:13:25.329  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 18:13:25.329  1019  1032 D InputDispatcher: Focused application set to: xxxx
09-12 18:13:25.329  1019  1032 D InputDispatcher: Focus left window: 1506
09-12 18:13:25.339  6679  6679 D AndroidRuntime: Shutting down VM
09-12 18:13:25.339  6812  6812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.339  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 18:13:25.339  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-12 18:13:25.339   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-12 18:13:25.339  6812  6812 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-12 18:13:25.359  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 18:13:25.359  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 18:13:25.369  6812  6812 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.369  6812  6812 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.379  1019  1031 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-12 18:13:25.379  1019  1019 V ActivityManager: Display changed displayId=0
09-12 18:13:25.399  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-12 18:13:25.419  6793  6828 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
09-12 18:13:25.419  6793  6828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-12 18:13:25.419  1019  1031 D PersonaManager: isKioskContainerExistOnDevice
09-12 18:13:25.429   257  6830 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-12 18:13:25.429   257   432 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-12 18:13:25.439  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-12 18:13:25.439  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.439  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:25.439  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:25.449  1506  1506 V ActivityThread: updateVisibility : ActivityRecord{35adcd3c token=android.os.BinderProxy@101a0e31 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-12 18:13:25.449  1506  1506 D Launcher: onTrimMemory. Level: 20
09-12 18:13:25.449  1019  3813 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
09-12 18:13:25.449  1858  1858 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-12 18:13:25.449  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.449  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.449  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.449  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.459  6831  6831 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.459  6831  6831 E Zygote  : v2
09-12 18:13:25.459  6831  6831 I libpersona: KNOX_SDCARD checking this for 10117
09-12 18:13:25.459  6831  6831 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.459  6831  6831 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.469  1019  3813 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6831 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-12 18:13:25.469  1019  3813 I ActivityManager: Killing 6396:com.android.defcontainer/u0a3 (adj 15): empty #21
09-12 18:13:25.469  6831  6831 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.469  6831  6831 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 18:13:25.469  1858  1858 I ConfigFetchService: launchTask
09-12 18:13:25.469  1019  3816 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-12 18:13:25.469  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-12 18:13:25.469  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.479  1019  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:25.479  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-12 18:13:25.479  1019  1138 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-12 18:13:25.479  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-12 18:13:25.479  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.479  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:25.479  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-12 18:13:25.479  1019  3813 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-12 18:13:25.479  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-12 18:13:25.489  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.489  1019  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:25.489  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-12 18:13:25.489  6793  6793 D AcmsService: Enter Oncreate
09-12 18:13:25.489  6793  6793 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 18:13:25.489  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-12 18:13:25.489  6793  6793 D AcmsService: creating AcmsCore
09-12 18:13:25.499  6793  6793 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-12 18:13:25.499  6793  6793 D AcmsCore: AcmsCore
09-12 18:13:25.509  6831  6831 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.509  6831  6831 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.509  6793  6793 D AcmsCore: init
09-12 18:13:25.509  6793  6793 D AcmsCore: Looper handler is not null
09-12 18:13:25.509  6793  6793 D AcmsCore: Post to AcmsCoreHandler
09-12 18:13:25.509  6793  6793 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 18:13:25.509  6793  6793 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-12 18:13:25.509  6793  6793 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-12 18:13:25.509  6793  6793 D AcmsService: onStartCommand
09-12 18:13:25.509  6793  6793 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-12 18:13:25.509  6793  6793 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-12 18:13:25.509  6793  6793 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-12 18:13:25.509  6793  6793 D AcmsService: Incremented Counter Value : onStartCommand
09-12 18:13:25.519  6793  6841 D AcmsCertificateMngr: AcmsCertificateMngr
,09-12 18:13:25.519  1019  3816 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-12 18:13:25.519  6793  6841 D AcmsRevocationMngr: AcmsRevocationMngr
09-12 18:13:25.519  6793  6793 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-12 18:13:25.539  6831  6831 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:25.549  6679  6679 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-12 18:13:25.549  6778  6778 D NearbySource: Nearby Source Create!
09-12 18:13:25.559  1019  1563 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
09-12 18:13:25.559  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.559  6778  6778 D NearbyContext: Nearby Context Create!
09-12 18:13:25.559  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.559  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.559  1019  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.579  6852  6852 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.579  1019  1563 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:13:25.579  6852  6852 E Zygote  : v2
09-12 18:13:25.579  6852  6852 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:25.579  6852  6852 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.589  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:25.589  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 18:13:25.589  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.589  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:25.589  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:25.589  6852  6852 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.589  6852  6852 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.599  1019  1514 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-12 18:13:25.599  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
09-12 18:13:25.599  1858  1858 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-12 18:13:25.599  1858  1858 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-12 18:13:25.599  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.599  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:25.599  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-12 18:13:25.599  6597  6597 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
09-12 18:13:25.609  6852  6852 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:25.609  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
09-12 18:13:25.609  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.619  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:25.619  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
09-12 18:13:25.629  6812  6812 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-12 18:13:25.629  6852  6852 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.629  6852  6852 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.649  6812  6812 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4974-4976)
09-12 18:13:25.649  6812  6812 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 18:13:25.659  1858  6848 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WQNL73cHxk8tE0uVEyBdZc4_NbGYy9qlW-DJLwIt3g0E36pMHlIbZUcMc8rOhgBabzv4kW92IoaB_AHX2KUqEWUBWMBJVIClEVCffo2imGlHIPwWe2HmxthY5IrDZV56VLV9eazW9vnIgw_XPl3ky58z-ysb-TxWOo9gNf47G0KqrMsN00U14KitDLSVQ-LcChH7QFkgYnaquG4OzB4oZt2nAMXIx1D7pExVD3_rJZH4LwfBQ
09-12 18:13:25.659  1858  1858 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
09-12 18:13:25.669   294   294 E SMD     : DCD OFF
09-12 18:13:25.679  1858  6849 I PeopleContactsSync: CP2 sync disabled
09-12 18:13:25.679  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 18:13:25.679  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.679  1019  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:25.679  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:25.689  6793  6793 D AcmsService: Inside handle Intent
09-12 18:13:25.689  6793  6793 D AcmsService: App added - package name: com.test.thalitest
09-12 18:13:25.689  6793  6793 D AcmsCore: Post to AcmsCoreHandler
09-12 18:13:25.689  6793  6793 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 18:13:25.689  6793  6793 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-12 18:13:25.689  6793  6793 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-12 18:13:25.689  6793  6793 D AcmsService: Decremented Counter Value : handleStartIntent
09-12 18:13:25.689  6793  6793 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-12 18:13:25.699  6852  6852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
09-12 18:13:25.699  1858  6848 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
09-12 18:13:25.699  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-12 18:13:25.699  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
09-12 18:13:25.699  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.699  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:25.699  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
09-12 18:13:25.709  1019  1523 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
09-12 18:13:25.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.719  6877  6877 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.719  6877  6877 E Zygote  : v2
09-12 18:13:25.719  1019  1523 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6877 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-12 18:13:25.729  6877  6877 I libpersona: KNOX_SDCARD checking this for 10087
09-12 18:13:25.729  6877  6877 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.729  6877  6877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.739  6877  6877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.739  6877  6877 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 18:13:25.739  1019  3813 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-12 18:13:25.739  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
09-12 18:13:25.739  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:25.739  1019  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:25.739  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:25.749  1019  1561 I ActivityManager: Killing 6458:com.osp.app.signin/u0a36 (adj 15): empty #21
09-12 18:13:25.759   322   322 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 33.198ms
09-12 18:13:25.759  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
09-12 18:13:25.759  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.759  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.759  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.759  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.769  6877  6877 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.769  6877  6877 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.779   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 23.203ms
09-12 18:13:25.789  6480  6480 I Mms/MmsApp:  start initViewCache mms
09-12 18:13:25.789  6480  6480 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1950.283853
09-12 18:13:25.789  6480  6480 D Mms/ComposeMessageFragment: fillCache, easy = false
09-12 18:13:25.799   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 18.204ms
09-12 18:13:25.809  6778  6778 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
09-12 18:13:25.809   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-12 18:13:25.809  6778  6778 D SLinkSource: Samsung link source created
09-12 18:13:25.809   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 18:13:25.809  6812  6812 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23af5226}
09-12 18:13:25.809  6812  6812 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 18:13:25.829  6812  6812 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 18:13:25.829  6895  6895 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.829  6895  6895 I libpersona: KNOX_SDCARD checking this for 10014
09-12 18:13:25.829  6895  6895 E Zygote  : v2
09-12 18:13:25.829  6895  6895 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.829  6895  6895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.829  6895  6895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.829  6895  6895 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 18:13:25.839  1019  1316 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6895 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
09-12 18:13:25.889  6895  6895 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.889  1019  3816 I art     : Explicit concurrent mark sweep GC freed 143398(8MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 23MB/34MB, paused 3.212ms total 199.070ms
09-12 18:13:25.889  6895  6895 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:25.909  1019  3813 D LocationManagerService: getProviders()=[passive, gps]
09-12 18:13:25.909  6812  6812 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-12 18:13:25.909  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 18:13:25.929  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.929  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.929  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.929  6812  6812 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 18:13:25.929  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:25.949  6914  6914 E Zygote  : MountEmulatedStorage()
09-12 18:13:25.949  6914  6914 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:25.949  6914  6914 E Zygote  : v2
09-12 18:13:25.949  6914  6914 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:25.949  6914  6914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:25.949  1019  1044 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6914 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:13:25.949  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{9abdd25 u0 com.test.thalitest/.MainActivity t163}
09-12 18:13:25.949  6914  6914 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:25.949  6914  6914 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:25.959  1019  1138 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
09-12 18:13:25.979  6914  6914 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:25.979  6914  6914 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:26.009  6812  6812 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 18:13:26.009  6812  6812 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 18:13:26.009  6812  6812 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 18:13:26.009  6812  6812 I Adreno-EGL: Local Branch: 
09-12 18:13:26.009  6812  6812 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 18:13:26.009  6812  6812 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 18:13:26.009  6812  6812 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-12 18:13:26.009  1019  1561 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-12 18:13:26.009  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
09-12 18:13:26.029  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:26.029  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.029  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
09-12 18:13:26.039  6754  6840 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-12 18:13:26.069  6778  6940 D ContactProvider: getAllContactInfoList Start
09-12 18:13:26.099  1019  1561 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-12 18:13:26.099  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
09-12 18:13:26.109  1019  1138 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 18:13:26.109  6914  6914 D AASAservice: onCreate()
09-12 18:13:26.109  6914  6914 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
09-12 18:13:26.109  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:26.109  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.109  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
09-12 18:13:26.109  6778  6940 D ContactProvider: getAllContactInfoList End
09-12 18:13:26.109  6778  6940 I syncContacts: thread: 1248, sync time = 75
09-12 18:13:26.119  1858  6848 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-12 18:13:26.119  1858  6848 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 18:13:26.119  1858  6848 I System.out: (HTTPLog)-Static: isShipBuild true
09-12 18:13:26.119  1858  6848 I System.out: (HTTPLog)-Thread-238-150656777: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-12 18:13:26.119  1858  6848 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 18:13:26.129   277   974 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 18:13:26.129   277   974 D Netd    : getNetworkForDns: using netid 502 for uid 10011
09-12 18:13:26.129  1019  3816 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
09-12 18:13:26.129  2740  2740 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
09-12 18:13:26.139  1019  1562 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-12 18:13:26.139  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.139  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.139  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.139  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.149  6955  6955 E Zygote  : MountEmulatedStorage()
09-12 18:13:26.149  6955  6955 E Zygote  : v2
09-12 18:13:26.149  6955  6955 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:26.149  6955  6955 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:26.149  1019  3816 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:13:26.159  6955  6955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:26.159  6955  6955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:26.159  6955  6955 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:26.159  1019  1561 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 18:13:26.169  6778  6778 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-12 18:13:26.199  6955  6955 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:26.199  6955  6955 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:26.209  1019  1562 I ActivityManager: Killing 6480:com.android.mms/u0a41 (adj 15): empty #21
09-12 18:13:26.219  1019  3816 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-12 18:13:26.249  6955  6955 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-12 18:13:26.249  6955  6955 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-12 18:13:26.249  6955  6955 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
09-12 18:13:26.269  6955  6955 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-12 18:13:26.269  6955  6955 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 18:13:26.269  6955  6955 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 18:13:26.269  6955  6955 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
09-12 18:13:26.269  1019  6909 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
09-12 18:13:26.269  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.279  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.279  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.279  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.289  1019  6909 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6976 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:13:26.289  6976  6976 E Zygote  : MountEmulatedStorage()
09-12 18:13:26.289  6976  6976 I libpersona: KNOX_SDCARD checking this for 10026
09-12 18:13:26.289  6976  6976 E Zygote  : v2
09-12 18:13:26.289  6976  6976 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:26.289  1019  6909 I ActivityManager: Killing 6508:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
09-12 18:13:26.289  6976  6976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:26.289  6976  6976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:26.299  1858  6848 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 18:13:26.299  1858  6848 I qtaguid : Tagging socket 96 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1858, getuid(): 10011
,09-12 18:13:26.299  1019  1562 D CountryDetector: No listener is left
,09-12 18:13:26.299  6976  6976 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:13:26.309  1019  1523 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,09-12 18:13:26.309  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.309  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.309  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.309  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.319  6992  6992 E Zygote  : MountEmulatedStorage()
09-12 18:13:26.319  6992  6992 E Zygote  : v2
09-12 18:13:26.319  6992  6992 I libpersona: KNOX_SDCARD checking this for 10041
09-12 18:13:26.319  6992  6992 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:26.319  6992  6992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:26.329  6812  6812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 18:13:26.329  6992  6992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:26.329  6992  6992 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-12 18:13:26.329  1019  1523 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6992 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-12 18:13:26.329  6976  6976 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:26.329  1019  1523 I ActivityManager: Killing 6525:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-12 18:13:26.339  6976  6976 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:26.339  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-12 18:13:26.339  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-12 18:13:26.359  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-12 18:13:26.359  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-12 18:13:26.359  1858  6872 W BaseAppContext: Using Auth Proxy for data requests.
09-12 18:13:26.359  1858  6872 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 18:13:26.369  6992  6992 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:26.369  6992  6992 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:26.379  1019  3816 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-12 18:13:26.379  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
09-12 18:13:26.379  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:26.379  1019  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.379  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-12 18:13:26.389  1858  6848 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1858, getuid(): 10011
,09-12 18:13:26.409  6992  6992 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-12 18:13:26.409  6992  6992 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:26.409  6992  6992 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:26.409  6992  6992 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:26.409  6992  6992 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-12 18:13:26.429  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:26.429  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:26.429  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.429  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,09-12 18:13:26.439  1019  1561 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-12 18:13:26.439  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-12 18:13:26.439  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:26.439  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.439  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-12 18:13:26.439  1019  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:26.439  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-12 18:13:26.439  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:26.439  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.439  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:26.469  1019  1032 E EdmStorageProvider: Admin not in database, something went wrong
,09-12 18:13:26.469  1858  6872 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 18:13:26.489  6992  6992 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-12 18:13:26.499  1019  1514 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:26.499  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:26.509  1019  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.509  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 18:13:26.519  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.519  1707  4489 I art     : Explicit concurrent mark sweep GC freed 11893(579KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.090ms total 47.010ms
,09-12 18:13:26.529  1019  6909 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-12 18:13:26.539  1019  6909 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:26.539  1019  6909 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.539  1019  6909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:26.549  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.549  1019  1561 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-12 18:13:26.549  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.549  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.549  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.549  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.569  7021  7021 E Zygote  : MountEmulatedStorage(),
09-12 18:13:26.569  7021  7021 E Zygote  : v2
09-12 18:13:26.569  7021  7021 I libpersona: KNOX_SDCARD checking this for 10148,
09-12 18:13:26.569  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:26.569  7021  7021 I libpersona: KNOX_SDCARD not a persona,
,09-12 18:13:26.569  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:26.569  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 18:13:26.569  1019  1561 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7021 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
,09-12 18:13:26.579  1019  1562 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:26.589  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-12 18:13:26.589  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:26.589  1019  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:26.589  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:26.599  1019  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:13:26.599  1019  1138 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-12 18:13:26.599  1019  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 18:13:26.599  1019  1138 D BatteryService: stay LED for charging
09-12 18:13:26.599  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:13:26.629  7021  7021 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:26.629  7021  7021 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:26.639  1858  6872 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 18:13:26.639  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:13:26.659  6812  6812 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 18:13:26.669  1019  1563 I ActivityManager: Killing 6547:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-12 18:13:26.689  6812  6812 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 18:13:26.689  6812  6812 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-12 18:13:26.689  6976  6976 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-12 18:13:26.699  6754  6840 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 655 ms] updated apps [took 655 ms] 
,09-12 18:13:26.699  1858  1873 W art     : Suspending all threads took: 18.506ms
,09-12 18:13:26.699  1019  1019 I MotionRecognitionService: Plugged
09-12 18:13:26.699  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 18:13:26.699  6812  6812 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-12 18:13:26.699  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 18:13:26.709  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 18:13:26.709  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.709  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 18:13:26.709  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-12 18:13:26.719  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:26.729  3278  3278 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 18:13:26.729  3278  3410 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:13:26.739  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 18:13:26.739  6812  6812 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:13:26.739  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:26.739  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:26.739  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-12 18:13:26.739  1181  1181 D SViewCoverView: level :100 plugged : 2
,09-12 18:13:26.749  1019  1032 I ActivityManager: Killing 6564:com.wsomacp/u0a23 (adj 15): empty #21
,09-12 18:13:26.749  1019  1562 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6547, ws=null) (elapsedTime=2737)
,09-12 18:13:26.759  1858  6872 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 18:13:26.769  7021  7021 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-12 18:13:26.779  6812  7044 D OpenGLRenderer: Render dirty regions requested: true
,09-12 18:13:26.789  1019  1523 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-12 18:13:26.789  1019  1523 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 18:13:26.789  1019  1523 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 18:13:26.789  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 18:13:26.789  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 18:13:26.789  6812  6812 V ActivityThread: updateVisibility : ActivityRecord{2eb24461 token=android.os.BinderProxy@1806046b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-12 18:13:26.789  6812  6950 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-12 18:13:26.799  6812  6812 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 18:13:26.799  6812  6812 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-12 18:13:26.799  1019  1398 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,09-12 18:13:26.799  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.799  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.799  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.799  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.819  7050  7050 E Zygote  : MountEmulatedStorage()
09-12 18:13:26.819  7050  7050 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:26.819  7050  7050 E Zygote  : v2
09-12 18:13:26.819  7050  7050 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:26.819  7050  7050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:26.819  7050  7050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:26.819  1019  1398 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7050 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:13:26.819  1019  1398 I ActivityManager: Killing 6579:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-12 18:13:26.819  7050  7050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:26.829   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-12 18:13:26.839  1019  3813 D InputDispatcher: Focus entered window: 6812
,09-12 18:13:26.839  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 18:13:26.849  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:13:26.849  6812  6812 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 18:13:26.849  6812  7044 I OpenGLRenderer: Initialized EGL, version 1.4
09-12 18:13:26.849  6812  7044 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-12 18:13:26.849  6812  7044 D OpenGLRenderer: Enabling debug mode 0
,09-12 18:13:26.859  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:26.859  7050  7050 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:26.869  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.869  6992  6992 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 300.563ms
,09-12 18:13:26.879  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.879  1019  1563 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 18:13:26.879  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.889  7050  7050 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,09-12 18:13:26.889  1181  1181 D PanelView: There is/are notification(s) 
,09-12 18:13:26.889  1019  7074 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 18:13:26.899  1858  6872 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 18:13:26.899  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.909  1019  1049 I ActivityManager: Displayed Component not be shown by security: +1s475ms (total +1s597ms)
,09-12 18:13:26.909  6812  6812 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-12 18:13:26.909  1019  1049 W ActivityManager: mDVFSHelper.release()
09-12 18:13:26.909  6812  6812 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1806046b time:96235
09-12 18:13:26.909  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9abdd25 u0 com.test.thalitest/.MainActivity t163} time:96236
,09-12 18:13:26.919   257   444 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-12 18:13:26.919   257  1103 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-12 18:13:26.929  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.939  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.939  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,09-12 18:13:26.939  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,09-12 18:13:26.939  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.939  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.949  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.949  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.949  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.949  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.949  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.949  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:26.949  6976  6976 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-12 18:13:26.979  1019  6909 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-12 18:13:26.979  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:26.979  6976  6976 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 18:13:26.979  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.979  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.979  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.979  6976  6976 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 18:13:26.999  7080  7080 E Zygote  : MountEmulatedStorage(),
09-12 18:13:26.999  7080  7080 E Zygote  : v2
,09-12 18:13:26.999  7080  7080 I libpersona: KNOX_SDCARD checking this for 10152
09-12 18:13:26.999  7080  7080 I libpersona: KNOX_SDCARD not a persona,
,09-12 18:13:26.999  7080  7080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 18:13:27.009  1019  6909 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7080 uid=10152 gids={50152, 9997} abi=armeabi-v7a,
09-12 18:13:27.009  1019  6909 I ActivityManager: Killing 6294:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21,
,09-12 18:13:27.009  7080  7080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:13:27.009  7080  7080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:27.029  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:27.029  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:27.029  6976  6976 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-12 18:13:27.049  6992  6992 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 170.613ms
,09-12 18:13:27.049  7080  7080 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:27.049  7080  7080 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:27.049  6992  6992 D Mms/TelephonyPermission: start operation mode monitor
,09-12 18:13:27.059  1858  6848 I qtaguid : Untagging socket 96
,09-12 18:13:27.059  2020  2020 I SamsungIME: getCurrentCandidateView
09-12 18:13:27.059  1019  1032 I ActivityManager: Killing 6312:com.android.calendar/u0a131 (adj 15): empty #21
,09-12 18:13:27.069  6992  7096 D Mms/ArtClassLoader: init before art
,09-12 18:13:27.079  6992  6992 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 18:13:27.089  1858  1858 I ConfigFetchService: fetch service done; releasing wakelock
,09-12 18:13:27.089  1858  1858 I ConfigFetchService: stopping self
,09-12 18:13:27.109  6992  6992 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-12 18:13:27.109  6992  6992 D Mms/TelephonyPermission: isDefault true
,09-12 18:13:27.109  6992  6992 D Mms/MmsApp: onCreate() com.android.mms
,09-12 18:13:27.129  6812  6812 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6812
,09-12 18:13:27.149  7080  7080 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-12 18:13:27.149  7080  7080 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,09-12 18:13:27.169  7080  7080 I TapandpayWidget:Utils: Clear T&P info.
,09-12 18:13:27.179  6976  6976 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-12 18:13:27.179  1019  1031 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-12 18:13:27.189  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-12 18:13:27.189  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:27.189  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:27.189  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-12 18:13:27.199  7080  7080 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-12 18:13:27.199  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-12 18:13:27.199  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.199  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.199  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.199  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.219  6992  6992 D Mms/MmsApp: [start]    initCountryIso consume time = 732.054739,
,09-12 18:13:27.219  7106  7106 E Zygote  : MountEmulatedStorage(),
09-12 18:13:27.219  7106  7106 E Zygote  : v2
,09-12 18:13:27.219  7106  7106 I libpersona: KNOX_SDCARD checking this for 10009
,09-12 18:13:27.219  7106  7106 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:27.229  1019  1550 D CountryDetector: The first listener is added,
,09-12 18:13:27.229  1019  1316 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7106 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
09-12 18:13:27.229  7106  7106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 18:13:27.229  6976  6976 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,09-12 18:13:27.229  7106  7106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:13:27.239  1019  1550 I ActivityManager: Killing 6608:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-12 18:13:27.239  6992  6992 D Mms/MmsApp: [end]    initCountryIso consume time = 21.336355
09-12 18:13:27.239  6992  6992 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.108645
,09-12 18:13:27.239  7106  7106 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 18:13:27.249  6976  7104 D Ads     : Skipping gmscore version check
09-12 18:13:27.249  1019  1097 V AlarmManager: waitForAlarm result :4
,09-12 18:13:27.269  6992  6992 D Mms/MmsConfig: before partial update
,09-12 18:13:27.279  7106  7106 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:27.279  7106  7106 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:27.289  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:27.289  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:27.289  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:27.289  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-12 18:13:27.309  6992  6992 D Mms/MmsConfig: Load Resize quality : 80
,09-12 18:13:27.319  6976  6976 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-12 18:13:27.339  6992  6992 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,09-12 18:13:27.339  6992  6992 D EasySignUpManager_1.0.1: isAuth is false
,09-12 18:13:27.339  6992  6992 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,09-12 18:13:27.349  1482  2482 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6992
,09-12 18:13:27.349  1482  2482 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.114 ms
,09-12 18:13:27.359  6992  6992 D EasySignUpManager_1.0.1: isAuth is false
09-12 18:13:27.359  6992  6992 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-12 18:13:27.359  6992  6992 E CscParser: mps_code.dat does not exist
09-12 18:13:27.359  6992  6992 E CscParser: customer_path =/system/csc/customer.xml
09-12 18:13:27.359  6992  6992 E CscParser: fileName + /system/csc/customer.xml
,09-12 18:13:27.369  6992  6992 E CscParser: mps_code.dat does not exist
09-12 18:13:27.369  6992  6992 E CscParser: customer_path =/system/csc/customer.xml
09-12 18:13:27.369  6992  6992 E CscParser: fileName + /system/csc/customer.xml
,09-12 18:13:27.399  6992  6992 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-12 18:13:27.399  6992  6992 D Mms/MmsConfig:  enable multiwindow = false
09-12 18:13:27.409  1019  1561 I ActivityManager: Killing 6629:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-12 18:13:27.409  2020  2020 D SamsungIME: Dismiss ExpandCandiate
09-12 18:13:27.419  6992  6992 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-12 18:13:27.419  6992  6992 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-12 18:13:27.419  6992  6992 D Mms/MmsConfig: [end]    init() consume time = 182.215886
09-12 18:13:27.419  6992  6992 D Mms/Contact: [start]    init() consume time = 2.29
,09-12 18:13:27.439  6812  6812 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 18:13:27.449  1482  1679 D TP/MmsSmsProvider: query,matched:13, calling pid = 6992
,09-12 18:13:27.449  1482  1679 D TP/MmsSmsProvider: match 13:Elapsed time : 1.190 ms
,09-12 18:13:27.449  6992  6992 D Mms/Contact: [end]    init consume time = 25.986718
,09-12 18:13:27.489  6992  7127 D Mms/DraftCache: [start]    rebuildCache consume time = 35.054792
,09-12 18:13:27.489  1482  1497 D TP/MmsSmsProvider: query,matched:12, calling pid = 6992
09-12 18:13:27.489  1482  1497 D TP/MmsSmsProvider: match 12:Elapsed time : 1.817 ms
09-12 18:13:27.489  6992  6992 D Mms/MethodReflector: getSubId is called
09-12 18:13:27.489  6992  6992 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-12 18:13:27.489  6992  7127 D Mms/DraftCache: [end]    rebuildCache consume time = 8.748281
,09-12 18:13:27.509  6992  6992 D Mms/MethodReflector: getTelephonyProperty is called
09-12 18:13:27.509  6992  6992 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-12 18:13:27.509  6992  6992 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-12 18:13:27.509  6992  6992 D Mms/DownloadManager: auto download without roaming -> true
09-12 18:13:27.509  6992  6992 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-12 18:13:27.509  6992  6992 D Mms/MethodReflector: getSubId is called
,09-12 18:13:27.519  6992  6992 D Mms/MethodReflector: getDefaultSmsSubId is called
09-12 18:13:27.519  6992  6992 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-12 18:13:27.519  6992  6992 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-12 18:13:27.519  6992  6992 D Mms/MethodReflector: getTelephonyProperty is called
09-12 18:13:27.519  6992  6992 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-12 18:13:27.519  6992  6992 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-12 18:13:27.519  6992  6992 D Mms/DownloadManager: auto download without roaming -> true
09-12 18:13:27.519  6992  6992 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-12 18:13:27.519  6992  6992 D Mms/DownloadManager: auto download during roaming secondary -> false
09-12 18:13:27.519  6992  6992 D Mms/DownloadManager: mAutoDownload ------> true
,09-12 18:13:27.539  6812  7086 D jxcore_app_log: JniHelper::setJavaVM(0xb8c2b2b0), pthread_self() = -1189378464
,09-12 18:13:27.539  1858  6872 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 149.204ms
,09-12 18:13:27.549  6812  7086 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 18:13:27.549  6812  7086 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 18:13:27.549  6812  7086 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 18:13:27.549  6812  7086 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 18:13:27.549  6812  7086 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 18:13:27.549  6812  7086 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1865260c added. We now have 1 listener(s)
,09-12 18:13:27.569  6812  7086 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-12 18:13:27.569  6812  7086 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:13:27.569  6812  7086 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:13:27.569  6812  7086 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 18:13:27.579  6812  7086 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254de5b added. We now have 1 listener(s)
,09-12 18:13:27.579  6812  7086 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:27.589  6812  7086 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:13:27.589  6812  7086 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 18:13:27.589  6812  7086 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 18:13:27.589  6812  7086 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-12 18:13:27.589  6812  7086 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 18:13:27.599  6812  7086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:27.599  6992  7096 W art     : Verification of boolean com.android.mms.ui.ConversationListFragment.onOptionsItemSelected(android.view.MenuItem) took 109.980ms
,09-12 18:13:27.599  6812  7086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-12 18:13:27.599  1019  1031 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-12 18:13:27.609  6992  6992 D ComposerPerformance: 1473696807620 ms / [DONE] Composer constructor
,09-12 18:13:27.609  6992  6992 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-12 18:13:27.609  6992  6992 I Mms/ReservationManager: ReservationManager()
,09-12 18:13:27.609  6992  6992 I Mms/ReservationManager: resetAfterConnected()
,09-12 18:13:27.609  1482  1497 D TP/MmsSmsProvider: query,matched:7, calling pid = 6992
,09-12 18:13:27.619  6812  7086 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:27.619  6812  7086 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:27.619  6812  7086 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 18:13:27.619  6812  7086 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:27.619  6812  7086 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 18:13:27.619  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:27.619  6992  7130 D Mms/Conversation: [start]    init() consume time = 128.969011
,09-12 18:13:27.629  1482  1497 D TP/MmsSmsProvider: match 7:Elapsed time : 13.762 ms
,09-12 18:13:27.629  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:27.629  1482  1679 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-12 18:13:27.629  6992  6992 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-12 18:13:27.639  1482  1679 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,09-12 18:13:27.639  6992  6992 D Mms/MmsApp: [end]    onCreate() consume time = 14.530312
,09-12 18:13:27.639  1482  1679 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-12 18:13:27.639  6992  6992 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,09-12 18:13:27.639  6992  6992 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-12 18:13:27.649  1482  1679 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,09-12 18:13:27.649  6992  6992 D Mms/MethodReflector: getSubId is called
,09-12 18:13:27.649  6992  6992 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-12 18:13:27.649  6992  6992 D Mms/MethodReflector: getTelephonyProperty is called
,09-12 18:13:27.649  6992  6992 D Mms/DownloadManager: roaming -> false (slotId = 0)
,09-12 18:13:27.649  6992  6992 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-12 18:13:27.649  6992  6992 D Mms/DownloadManager: auto download without roaming -> true
,09-12 18:13:27.649  6992  6992 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-12 18:13:27.659  6992  6992 D Mms/DownloadManager: mAutoDownload ------> true,
,09-12 18:13:27.659  1482  1679 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-12 18:13:27.659  1482  1679 D TP/MmsSmsProvider: need read changed broadcast:false
,09-12 18:13:27.659  6992  7130 D Mms/Conversation: [end]    init consume time = 23.3025
,09-12 18:13:27.669  6992  7130 D Mms/MessagingNotification: [start]    init() consume time = 7.168959
,09-12 18:13:27.669  6812  6812 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 18:13:27.669  6992  7130 D Mms/MessagingNotification: [end]    init consume time = 4.184583
,09-12 18:13:27.679  6992  6992 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,09-12 18:13:27.679  1019  3816 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-12 18:13:27.679  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,09-12 18:13:27.679  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:27.679  1019  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:27.679  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-12 18:13:27.679  1482  1500 D TP/MmsSmsProvider: query,matched:0, calling pid = 6992
,09-12 18:13:27.679  1482  1500 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-12 18:13:27.679  1482  1500 D TP/MmsSmsProvider: match 0:Elapsed time : 2.053 ms
,09-12 18:13:27.679  1019  3813 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-12 18:13:27.689  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.689  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.689  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.689  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.699  7134  7134 E Zygote  : MountEmulatedStorage()
09-12 18:13:27.699  7134  7134 E Zygote  : v2
09-12 18:13:27.699  7134  7134 I libpersona: KNOX_SDCARD checking this for 10042
09-12 18:13:27.699  7134  7134 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:27.709  7134  7134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 18:13:27.719  7134  7134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:27.719  1019  3813 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7134 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-12 18:13:27.719  7134  7134 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,09-12 18:13:27.719  1019  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,09-12 18:13:27.719  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:27.719  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:27.719  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:27.719  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:27.719  6992  7140 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,09-12 18:13:27.719  6992  7140 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-12 18:13:27.749  7150  7150 E Zygote  : MountEmulatedStorage()
09-12 18:13:27.749  7150  7150 E Zygote  : v2
09-12 18:13:27.749  7150  7150 I libpersona: KNOX_SDCARD checking this for 10068
09-12 18:13:27.749  7150  7150 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:27.749  7150  7150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:27.749  7150  7150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 18:13:27.749  1019  1031 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7150 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-12 18:13:27.749  7150  7150 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 18:13:27.769  1019  1398 I ActivityManager: Killing 6645:com.qualcomm.timeservice/1000 (adj 15): empty #21,
,09-12 18:13:27.779   322   322 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 631us total 31.284ms
,09-12 18:13:27.779  7150  7150 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:27.789  7150  7150 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:27.789  6812  6826 W art     : Suspending all threads took: 20.589ms
,09-12 18:13:27.789  7134  7134 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:27.789  7134  7134 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:27.799  1019  1561 I ActivityManager: Killing 6597:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-12 18:13:27.799  6812  6826 I art     : Background partial concurrent mark sweep GC freed 7472(469KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 22.748ms total 62.221ms
,09-12 18:13:27.809   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 21.736ms
,09-12 18:13:27.819   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.566ms
,09-12 18:13:27.839  1858  4452 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,09-12 18:13:27.839  7134  7134 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 18:13:27.839  7134  7134 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:27.839  7134  7134 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 18:13:27.839  6992  7133 D Mms/Synchronizer: [start]    doSync consume time = 170.635573
,09-12 18:13:27.849  6992  7096 W art     : Verification of boolean com.android.mms.ui.ConversationListFragment.requestFocusOnConversationList(long) took 138.258ms
,09-12 18:13:27.859  1482  1497 D TP/MmsSmsProvider: update, matched:300, calling pid = 6992
09-12 18:13:27.859  1482  1497 V TP/MmsSmsProvider: syncDBData start
,09-12 18:13:27.859  1482  1497 V TP/MmsSmsProvider: syncDBData sms end
,09-12 18:13:27.859  6992  7132 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 13.701718
09-12 18:13:27.859  1482  1497 V TP/MmsSmsProvider: syncDBData mms end
,09-12 18:13:27.859  1482  1497 V TP/MmsSmsProvider: syncDBData end
,09-12 18:13:27.859  6992  7133 D Mms/Synchronizer: [end]    doSync consume time = 2.485469
,09-12 18:13:27.859  1482  1679 D TP/MmsSmsProvider: query,matched:400, calling pid = 6992
,09-12 18:13:27.869  6992  7132 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 9.277552
,09-12 18:13:27.899  2020  2020 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 18:13:27.899  7150  7150 D BadgeProvider: onCreate
,09-12 18:13:27.909  7150  7150 D BadgeProvider: DatabaseHelper
,09-12 18:13:27.909  1019  1032 I art     : Explicit concurrent mark sweep GC freed 17317(943KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.760ms total 156.097ms
,09-12 18:13:27.939  6992  7130 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-12 18:13:27.949  1482  1679 D TP/SmsProvider: query,matched:26, calling pid = 6992
,09-12 18:13:27.959  1482  1679 D TP/SmsProvider: match 26:Elapsed time : 1.433 ms
,09-12 18:13:27.969  1482  1497 D TP/MmsSmsProvider: query,matched:6, calling pid = 6992
,09-12 18:13:27.969  1482  1497 D TP/MmsSmsProvider: match 6:Elapsed time : 1.615 ms
,09-12 18:13:28.019  1019  1562 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,09-12 18:13:28.019  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.019  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.019  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.019  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.039  7169  7169 E Zygote  : MountEmulatedStorage(),
09-12 18:13:28.039  7169  7169 E Zygote  : v2
09-12 18:13:28.039  7169  7169 I libpersona: KNOX_SDCARD checking this for 10023
09-12 18:13:28.039  7169  7169 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:28.039  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 18:13:28.039  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 18:13:28.039  1019  1562 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7169 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,09-12 18:13:28.049  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:28.069  7134  7134 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-12 18:13:28.069  2020  2020 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 18:13:28.069  1019  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
,09-12 18:13:28.079  1019  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-12 18:13:28.089  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:28.089  7169  7169 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:28.099  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.099  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.099  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.099  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.109  2020  2020 I SamsungIME: KeybaordView init() : load resources
,09-12 18:13:28.109  7184  7184 E Zygote  : MountEmulatedStorage()
,09-12 18:13:28.109  7184  7184 E Zygote  : v2
09-12 18:13:28.109  7184  7184 I libpersona: KNOX_SDCARD checking this for 10003
09-12 18:13:28.109  7184  7184 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:28.109  7184  7184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 18:13:28.109  1019  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7184 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-12 18:13:28.109  1019  1550 I ActivityManager: Killing 6670:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-12 18:13:28.119  7184  7184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:28.119  7184  7184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:28.159  7184  7184 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:28.159  7184  7184 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:28.189  6877  6975 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-12 18:13:28.189  6877  6975 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 18:13:28.189  6877  6975 I GAv4    :   adb logcat -s GAv4
,09-12 18:13:28.209  7169  7169 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-12 18:13:28.229   283   283 E installd: system dir 0 : /system/app/
09-12 18:13:28.229   283   283 E installd: system dir 1 : /system/priv-app/
09-12 18:13:28.229   283   283 E installd: system dir 2 : /vendor/app/
09-12 18:13:28.229   283   283 E installd: system dir 3 : /oem/app/
,09-12 18:13:28.229  6877  6975 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:28.229  1019  1138 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-12 18:13:28.239   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c1d7c8
09-12 18:13:28.239   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,09-12 18:13:28.239   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-12 18:13:28.239   272   317 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1212032888)
,09-12 18:13:28.249  6992  7130 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-12 18:13:28.259  6992  7096 W art     : Verification of void com.android.mms.util.HandleComposerAttachment.processingActivityResult(int, int, android.content.Intent) took 156.584ms
,09-12 18:13:28.269  2020  2020 I SamsungIME: getCurrentKeyboard,
09-12 18:13:28.269  2020  2020 I SamsungIME: getTextKeyboard
,09-12 18:13:28.299  6877  6975 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:28.299   272   317 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-12 18:13:28.299   272   317 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-12 18:13:28.299   272   317 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1212032888) wakelock released: 1, error no: 0
09-12 18:13:28.299   272   317 I rmt_storage: 
,09-12 18:13:28.309   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7c1d7c8
,09-12 18:13:28.329  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-12 18:13:28.329  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-12 18:13:28.329  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-12 18:13:28.329  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-12 18:13:28.329  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-12 18:13:28.329  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-12 18:13:28.339  2020  2020 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-12 18:13:28.339  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-12 18:13:28.339  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-12 18:13:28.339  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-12 18:13:28.339  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-12 18:13:28.369  6992  7096 D Mms/ArtClassLoader: init [DONE] art
,09-12 18:13:28.379  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-12 18:13:28.379  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-12 18:13:28.379  7169  7169 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-12 18:13:28.399  6877  6975 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,09-12 18:13:28.399  1858  4452 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,09-12 18:13:28.409  1019  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-12 18:13:28.419  6877  7202 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:28.449  1019  1031 I ActivityManager: Killing 6689:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-12 18:13:28.519  1858  4452 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,09-12 18:13:28.539  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-12 18:13:28.539  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:28.539  1019  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:28.539  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:28.549  6812  7131 W jxcore-log: Initializing JXcore engine,
09-12 18:13:28.549  6812  7131 W jxcore-log: JXcore engine is ready
,09-12 18:13:28.609  2029  2029 E audit   : type=1400 msg=audit(1473696808.609:205): avc:  denied  { ioctl } for  pid=7131 comm="Thread-1280" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 18:13:28.609  2029  2029 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:28.609  2029  2029 E audit   : type=1300 msg=audit(1473696808.609:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e0018f8 items=0 ppid=322 ppcomm=main pid=7131 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1280" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-12 18:13:28.609  2029  2029 E audit   : type=1320 msg=audit(1473696808.609:205): 
,09-12 18:13:28.619  6812  7131 W jxcore-log: Starting JXcore engine
,09-12 18:13:28.639  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-12 18:13:28.639  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.639  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.639  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.639  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.659  7210  7210 E Zygote  : MountEmulatedStorage(),
09-12 18:13:28.659  7210  7210 E Zygote  : v2
09-12 18:13:28.659  7210  7210 I libpersona: KNOX_SDCARD checking this for 1000,
09-12 18:13:28.659  7210  7210 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:28.659  1019  1031 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7210 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 18:13:28.659  1019  1031 I ActivityManager: Killing 5284:com.google.android.gms.wearable/u0a11 (adj 15): empty #21,
09-12 18:13:28.659  7210  7210 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:28.659  7210  7210 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:28.659  7210  7210 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:28.669   294   294 E SMD     : DCD OFF,
,09-12 18:13:28.689  7210  7210 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:28.689  7210  7210 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:28.719  7210  7210 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-12 18:13:28.729  7210  7210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-12 18:13:28.729  1019  1562 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,09-12 18:13:28.729  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-12 18:13:28.729  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:28.729  1019  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:28.729  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-12 18:13:28.739  1019  3813 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-12 18:13:28.739  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
09-12 18:13:28.739  7210  7210 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-12 18:13:28.739  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.739  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.749  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.749  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.749  6812  7131 W jxcore-log: Platform android
09-12 18:13:28.749  6812  7131 W jxcore-log: 
,09-12 18:13:28.749  6812  7131 W jxcore-log: Process ARCH arm
09-12 18:13:28.749  6812  7131 W jxcore-log: 
,09-12 18:13:28.759  6877  7208 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-12 18:13:28.759  7228  7228 E Zygote  : MountEmulatedStorage()
09-12 18:13:28.759  7228  7228 E Zygote  : v2
09-12 18:13:28.759  7228  7228 I libpersona: KNOX_SDCARD checking this for 10130
09-12 18:13:28.759  7228  7228 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:28.759  6877  7208 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-12 18:13:28.759  7228  7228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:28.759  1019  1044 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7228 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-12 18:13:28.769  7228  7228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:28.769  7228  7228 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,09-12 18:13:28.779  7228  7228 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:28.779  7228  7228 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:28.809  7228  7228 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:28.809  7228  7228 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-12 18:13:28.829  6877  7208 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-12 18:13:28.829  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-12 18:13:28.829  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.829  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.829  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.829  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.839  7243  7243 E Zygote  : MountEmulatedStorage()
,09-12 18:13:28.839  7243  7243 E Zygote  : v2
09-12 18:13:28.849  7243  7243 I libpersona: KNOX_SDCARD checking this for 10131
09-12 18:13:28.849  7243  7243 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:28.849  7243  7243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:28.849  7243  7243 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:28.849  7243  7243 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:28.859  1019  1316 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7243 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-12 18:13:28.859  1019  1316 I ActivityManager: Killing 6723:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-12 18:13:28.869  7243  7243 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:28.869  7243  7243 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:28.879  7210  7227 E FilterInstaller: installFilters
,09-12 18:13:28.889  7210  7227 E FilterInstaller: There is no requred permission
,09-12 18:13:28.889  1019  1561 I ActivityManager: Killing 6700:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-12 18:13:28.899  7243  7243 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:28.899  6877  6891 W art     : Suspending all threads took: 13.568ms
,09-12 18:13:28.909  7243  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:13:28.909  7243  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 18:13:28.949  1019  1398 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-12 18:13:28.949  1019  1398 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-12 18:13:28.949  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:28.949  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:28.949  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 18:13:28.959  2675  2683 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-12 18:13:28.969  1019  1514 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-12 18:13:28.969  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-12 18:13:28.979  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:28.979  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:28.979  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 18:13:28.979  6877  7208 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 18:13:28.979  6877  7208 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12cc9515: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-12 18:13:28.979  6877  7208 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-12 18:13:28.979  1019  1550 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,09-12 18:13:28.979  1019  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.989  1019  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:28.989  1019  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.989  1019  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:28.989  6812  7131 I jxcore-log: JXcore Cordova bridge is ready!
09-12 18:13:28.989  6812  7131 I jxcore-log: 
09-12 18:13:28.989  6812  7131 W jxcore-log: JXcore engine is started
,09-12 18:13:28.989  6812  7086 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 18:13:28.989  6812  6812 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 18:13:28.999  7263  7263 E Zygote  : MountEmulatedStorage()
,09-12 18:13:29.009  7263  7263 E Zygote  : v2
09-12 18:13:29.009  7263  7263 I libpersona: KNOX_SDCARD checking this for 10037
,09-12 18:13:29.009  7263  7263 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:29.009  7263  7263 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:29.009  7263  7263 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 18:13:29.009  7263  7263 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 18:13:29.009  1019  1550 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7263 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:29.039  1019  1398 I ActivityManager: Killing 6738:com.samsung.helphub/1000 (adj 15): empty #21
,09-12 18:13:29.039  7263  7263 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:29.039  7263  7263 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:29.059  7263  7263 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,09-12 18:13:29.079  1019  6909 I ActivityManager: Killing 6778:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-12 18:13:29.079  7263  7263 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-12 18:13:29.149  1019  3816 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,09-12 18:13:29.149  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,09-12 18:13:29.159  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:29.159  1019  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:29.159  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 18:13:29.169  1019  6909 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
09-12 18:13:29.169  1019  6909 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-12 18:13:29.169  1019  6909 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:29.169  1019  6909 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:29.169  1019  6909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 18:13:29.169  7263  7281 E SQLiteLog: (284) automatic index on view_events(_id)
,09-12 18:13:29.189  7263  7281 D CalendarAlarmManager: sys current time:1473696809184
,09-12 18:13:29.189  7263  7281 D CalendarAlarmManager: reminder amount:0
,09-12 18:13:29.259  6793  6841 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-12 18:13:29.279  6793  6841 I AcmsKeyStoreHelper: Key Store exist
,09-12 18:13:29.279  6793  6841 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-12 18:13:29.329  6793  6841 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-12 18:13:29.329  6793  6841 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-12 18:13:29.329  6793  6841 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-12 18:13:29.329  6793  6841 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 18:13:29.329  6793  6841 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-12 18:13:29.329  6793  6841 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-12 18:13:29.329  6793  6841 D AcmsCore: This is NOT a valid MirrorLink app
09-12 18:13:29.329  6793  6841 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-12 18:13:29.329  6793  6841 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 18:13:29.329  6793  6841 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-12 18:13:29.329  6793  6841 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-12 18:13:29.339  6793  6793 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-12 18:13:29.339  6793  6793 D AcmsService: Enter onDestroy
09-12 18:13:29.339  6793  6793 I AcmsService: cleanUp(): inside service clean up
09-12 18:13:29.339  6793  6793 D AcmsCore: AcmsCore: inside DeInit
09-12 18:13:29.339  6793  6793 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-12 18:13:29.339  6793  6793 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-12 18:13:29.339  6793  6793 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-12 18:13:29.339  6793  6793 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-12 18:13:29.339  6793  6793 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-12 18:13:29.339  6793  6793 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-12 18:13:29.339  6793  6793 D AcmsService: killing acms process
09-12 18:13:29.339  6793  6793 I Process : Sending signal. PID: 6793 SIG: 9
,09-12 18:13:29.409  1019  3441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 18:13:29.419  1019  3813 I ActivityManager: Process ACMS.Process (pid 6793)(adj 0) has died(33,766)
,09-12 18:13:29.639  6992  6992 I Mms/MmsApp:  start initViewCache mms
,09-12 18:13:29.639  6992  6992 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1770.778854
,09-12 18:13:29.639  6992  6992 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-12 18:13:29.739  6992  6992 D AbsListView: Get MotionRecognitionManager
,09-12 18:13:29.739  1019  1514 D MotionRecognitionService:  ssp status : false
,09-12 18:13:29.749  6992  6992 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 107.768437
,09-12 18:13:29.829  6992  6992 D Mms/BubbleViewCache: fillCache bubble = 1
,09-12 18:13:30.179  7263  7263 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-12 18:13:30.179  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:30.179  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:30.179  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,09-12 18:13:30.179  1019  1523 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-12 18:13:30.179  1019  1523 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:30.179  1019  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:30.179  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 18:13:30.189  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:30.189  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:30.189  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-12 18:13:30.199  1019  3813 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-12 18:13:30.199  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-12 18:13:30.199  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:30.199  1019  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:30.199  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 18:13:30.209  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:30.209  1019  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:30.209  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-12 18:13:30.209  1019  1398 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-12 18:13:30.209  1019  1398 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-12 18:13:30.209  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:30.209  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:30.209  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 18:13:30.219  1019  1031 I ActivityManager: Killing 6754:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-12 18:13:31.669   294   294 E SMD     : DCD OFF
,09-12 18:13:32.119  1707  1707 I ConfigService: onDestroy
,09-12 18:13:32.259  1019  3428 D SSRM:n  : SIOP:: AP = 410
,09-12 18:13:34.409  1019  3441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 18:13:34.669   294   294 E SMD     : DCD OFF,
,09-12 18:13:35.349  1019  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-12 18:13:36.649  1019  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:13:36.649  1019  1138 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-12 18:13:36.649  1019  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 18:13:36.649  1019  1138 D BatteryService: stay LED for charging
,09-12 18:13:36.649  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:13:36.659  1019  1019 I MotionRecognitionService: Plugged
09-12 18:13:36.659  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 18:13:36.659  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 18:13:36.659  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 18:13:36.659  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 18:13:36.659  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-12 18:13:36.679  3278  3278 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 18:13:36.679  3278  3410 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:13:36.689  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:36.689  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:36.689  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-12 18:13:36.689  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-12 18:13:36.689  1181  1181 D SViewCoverView: level :100 plugged : 2
,09-12 18:13:37.679   294   294 E SMD     : DCD OFF,
,09-12 18:13:38.429  1019  1058 D PackageManager: [MSG] MCS_UNBIND
,09-12 18:13:38.429  1019  1563 I ActivityManager: Killing 6219:com.samsung.android.sm/1000 (adj 15): empty #21
,09-12 18:13:39.029  1019  1332 E Watchdog: !@Sync 3
,09-12 18:13:39.739   344   344 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-12 18:13:39.739   344   344 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-12 18:13:40.679   294   294 E SMD     : DCD OFF
,09-12 18:13:41.189  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 18:13:41.189  6812  7131 I jxcore-log: 
,09-12 18:13:41.189  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-12 18:13:41.189  6812  7131 I jxcore-log: 
,09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.199  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.199  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-12 18:13:41.199  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 18:13:41.199  6812  7131 I jxcore-log: 
,09-12 18:13:41.199  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 18:13:41.199  6812  7131 I jxcore-log: 
,09-12 18:13:41.869  6812  7131 D executeNativeTests: Running unit tests
,09-12 18:13:41.959  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:13:41.959  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc added. We now have 2 listener(s)
,09-12 18:13:41.959  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:13:41.959  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:13:41.959  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:13:41.959  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:41.959  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 added. We now have 2 listener(s)
09-12 18:13:41.959  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:13:41.959  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:13:41.959  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.969  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.969  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:41.969  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:41.969  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.969  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 18:13:41.969  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:41.969  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 18:13:41.969  6812  7131 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 18:13:41.969  6812  7131 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:13:41.969  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:13:41.969  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:41.969  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 18:13:41.969  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.969  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.969  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:13:41.969  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.969  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.969  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:41.969  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:13:41.969  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc removed from the list
09-12 18:13:41.969  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.969  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 removed from the list
,09-12 18:13:41.979  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.979  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.979  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.979  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.979  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.979  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:41.979  6812  7131 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 18:13:41.979  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.979  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.979  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.979  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.979  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.979  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.979  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:41.979  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.979  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.979  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.979  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.979  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.979  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:13:41.989  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.989  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.989  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.989  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.989  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.989  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.989  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:41.989  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.989  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:41.989  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.989  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.989  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.989  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.989  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.989  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.989  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.989  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.989  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:41.989  6812  7131 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 18:13:41.989  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.999  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:41.999  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.999  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:13:41.999  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:41.999  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:41.999  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:13:41.999  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:41.999  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:13:41.999  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:41.999  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:13:41.999  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:42.009  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:13:42.009  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 18:13:42.019  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 18:13:42.019  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 18:13:42.019  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 18:13:42.019  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:13:42.019  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 18:13:42.029  3278  3398 D BtGatt.GattService: registerClient() - UUID=6980b7b4-8aa9-4cd4-af34-2573c64651f2
,09-12 18:13:42.039  1019  1097 V AlarmManager: waitForAlarm result :4
09-12 18:13:42.039  1019  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.069  3278  3358 D BtGatt.GattService: onClientRegistered() - UUID=6980b7b4-8aa9-4cd4-af34-2573c64651f2, clientIf=6
,09-12 18:13:42.079  6812  6820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:13:42.079  3278  3291 D BtGatt.GattService: start scan with filters
,09-12 18:13:42.079  3278  3401 D BtGatt.ScanManager: handling starting scan
,09-12 18:13:42.079  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:13:42.079  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 18:13:42.079  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 18:13:42.079  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:42.079  3278  3401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:42.089  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:42.089  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:13:42.089  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:42.089  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:42.089  6812  7131 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:13:42.099  3278  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:13:42.099  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:42.099  3278  3401 D BtGatt.ScanManager: allow scan with filters
09-12 18:13:42.099  3278  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 18:13:42.099  3278  3401 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-12 18:13:42.099  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:42.099  6812  7131 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 18:13:42.099  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.099  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:13:42.099  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.099  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:13:42.099  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:42.099  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:42.099  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:42.099  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:13:42.099  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:13:42.099  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:13:42.099  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:42.099  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:13:42.099  3278  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:42.099  3278  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 18:13:42.109  3278  3397 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:13:42.109  3278  3398 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
09-12 18:13:42.109  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:13:42.109  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:13:42.109  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:42.109  3278  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 18:13:42.109  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.109  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.109  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:42.109  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.109  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.109  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.109  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.109  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.109  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.109  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.109  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:42.109  6812  7131 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:13:42.119  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:42.119  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 18:13:42.119  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:42.119  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:42.119  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:42.119  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:42.119  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:42.119  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:42.119  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:13:42.119  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:42.119  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:13:42.129  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.129  3278  3401 D BtGatt.ScanManager: filter size is 1
09-12 18:13:42.129  3278  3401 D BtGatt.ScanManager: delete FilterIndex - 3
,09-12 18:13:42.129  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:13:42.129  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.129  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 18:13:42.129  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.129  3278  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:42.129  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:13:42.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:13:42.139  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 18:13:42.139  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.139  3278  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:13:42.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:13:42.139  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:13:42.139  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:13:42.149  3278  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 18:13:42.149  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.149  3278  3398 D BtGatt.GattService: registerClient() - UUID=e4568c8b-b643-403e-98a5-35d3b747892c
,09-12 18:13:42.189  3278  3358 D BtGatt.GattService: onClientRegistered() - UUID=e4568c8b-b643-403e-98a5-35d3b747892c, clientIf=6
,09-12 18:13:42.189  6812  6820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:13:42.189  3278  3293 D BtGatt.GattService: start scan with filters
,09-12 18:13:42.189  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:13:42.189  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:42.189  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:13:42.189  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:42.189  3278  3401 D BtGatt.ScanManager: handling starting scan
,09-12 18:13:42.199  3278  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 18:13:42.199  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:42.199  3278  3401 D BtGatt.ScanManager: allow scan with filters
09-12 18:13:42.199  3278  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:13:42.199  3278  3401 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-12 18:13:42.199  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:42.199  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:13:42.199  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:42.209  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 18:13:42.209  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:42.209  3278  3401 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 18:13:42.209  3278  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 18:13:42.209  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:42.209  6812  7131 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:13:42.209  3278  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 18:13:42.209  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.219  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:42.219  6812  7131 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 18:13:42.219  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.219  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 18:13:42.219  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.219  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:13:42.219  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:42.219  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:42.219  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:42.219  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:42.219  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:13:42.219  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:13:42.219  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 18:13:42.219  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.219  3278  3291 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:13:42.229  3278  3398 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:13:42.229  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:13:42.229  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:13:42.229  3278  3401 D BtGatt.ScanManager: filter size is 1
,09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:42.229  3278  3401 D BtGatt.ScanManager: delete FilterIndex - 4
09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:13:42.229  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:42.229  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.229  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.229  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:42.229  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.229  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:42.229  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.229  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.229  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.229  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.229  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.229  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.239  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.239  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.239  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.239  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.239  6812  7131 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:13:42.239  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 18:13:42.239  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.239  3278  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:42.239  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:42.239  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 18:13:42.239  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:42.239  3278  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:42.249  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:42.249  3278  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 18:13:42.249  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.249  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:42.249  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:42.259  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:42.259  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:42.259  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:13:42.259  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:42.259  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:13:42.259  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.259  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.259  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:13:42.269  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:13:42.269  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:13:42.269  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:13:42.269  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 18:13:42.269  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:13:42.279  3278  3293 D BtGatt.GattService: registerClient() - UUID=d7fa2e38-7625-414d-a8d8-ef37f6447604
,09-12 18:13:42.289  1019  3428 D SSRM:n  : SIOP:: AP = 390
,09-12 18:13:42.319  3278  3358 D BtGatt.GattService: onClientRegistered() - UUID=d7fa2e38-7625-414d-a8d8-ef37f6447604, clientIf=6
,09-12 18:13:42.319  6812  6824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:13:42.319  3278  3397 D BtGatt.GattService: start scan with filters
,09-12 18:13:42.319  3278  3401 D BtGatt.ScanManager: handling starting scan
,09-12 18:13:42.329  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:13:42.329  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:42.329  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:13:42.329  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:13:42.329  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:13:42.329  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:13:42.329  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:42.329  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:42.329  3278  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:13:42.329  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.329  3278  3401 D BtGatt.ScanManager: allow scan with filters
,09-12 18:13:42.339  3278  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:13:42.339  3278  3401 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-12 18:13:42.339  6812  7131 I io.jxcore.node.ConnectionHelper: start: OK
09-12 18:13:42.339  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.339  6812  7131 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:13:42.339  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.339  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:13:42.339  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.339  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:13:42.339  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:42.339  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:42.339  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:42.339  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:42.339  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:13:42.339  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:13:42.339  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 18:13:42.339  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:42.339  3278  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:42.339  3278  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 18:13:42.339  3278  3293 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:13:42.339  3278  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 18:13:42.349  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.349  3278  3291 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:13:42.349  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:13:42.349  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:13:42.349  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:42.349  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:13:42.349  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:13:42.349  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 18:13:42.349  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:42.349  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.349  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:13:42.349  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:13:42.349  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:42.349  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:42.359  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.359  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.359  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:42.359  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.359  6812  7131 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:13:42.359  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.359  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.359  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.359  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.359  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:42.359  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.359  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.359  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.359  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.359  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.359  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.359  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.359  3278  3401 D BtGatt.ScanManager: filter size is 1
,09-12 18:13:42.359  3278  3401 D BtGatt.ScanManager: delete FilterIndex - 5
,09-12 18:13:42.359  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:42.359  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.359  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.359  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.359  6812  7131 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 18:13:42.359  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:42.369  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.369  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:13:42.369  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.369  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.369  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.369  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.369  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.369  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.369  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.369  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.369  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.369  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.369  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.369  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 18:13:42.369  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:42.369  3278  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:42.369  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:42.369  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.369  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:42.369  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.369  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 18:13:42.369  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.369  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.369  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.369  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.369  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.369  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.369  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.369  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.369  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.369  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.369  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.369  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.369  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.369  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.369  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:13:42.369  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.369  3278  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:42.379  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.379  6812  7131 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 18:13:42.379  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.379  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.379  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.379  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.379  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.379  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.379  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.379  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.379  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.379  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.379  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.379  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.379  3278  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 18:13:42.379  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.379  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.379  6812  7131 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 18:13:42.379  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.379  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.379  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.379  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.379  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.379  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.379  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.379  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.379  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.379  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.379  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.379  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.379  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.389  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:13:42.389  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 18:13:42.389  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 18:13:42.389  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:42.389  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:42.389  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.389  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.389  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.389  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.389  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.389  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.389  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.389  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.389  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.389  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.389  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.389  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.389  6812  7131 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 18:13:42.389  6812  7131 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 18:13:42.389  6812  7131 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:42.389  6812  7131 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:13:42.389  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<,no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:13:42.399  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:13:42.399  6812  7131 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 18:13:42.399  6812  7131 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:42.399  6812  7131 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 18:13:42.399  6812  7131 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:42.399  6812  7131 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:42.399  6812  7131 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
09-12 18:13:42.399  6812  7131 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:42.399  6812  7131 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:42.399  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-12 18:13:42.399  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-12 18:13:42.399  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 18:13:42.399  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-12 18:13:42.399  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-12 18:13:42.399  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 18:13:42.399  6812  7131 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-12 18:13:42.409  6812  7131 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:42.409  6812  7131 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-12 18:13:42.409  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.409  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.409  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-12 18:13:42.409  6812  7293 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1344)
,09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.409  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.409  6812  7131 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-12 18:13:42.409  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.409  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.409  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.409  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.409  6812  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1344
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.409  6812  7131 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 18:13:42.409  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.409  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.409  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.409  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.409  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.409  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.409  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.409  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 18:13:42.419  6812  7131 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:42.419  6812  7131 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:13:42.419  6812  7131 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:42.419  6812  7131 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:13:42.419  6812  7131 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:42.419  6812  7131 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 18:13:42.419  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.419  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.419  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
,09-12 18:13:42.419  6812  7293 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.419  6812  7293 D BluetoothSocket: connect(): myUserId = 0
09-12 18:13:42.419  6812  7293 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.419  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.419  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.419  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.419  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.419  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.4,19  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.419  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.419  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.419  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.429  1019  1051 I PowerManagerService: [PWL] Off : 50s ago
,09-12 18:13:42.429  1019  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 18:13:42.429  3278  3293 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:13:42.429  1019  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:42.429  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3278, ws=null) (elapsedTime=341)
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 18:13:42.429  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:42.429  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.429  6812  6812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 18:13:42.429  6812  6812 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 18:13:42.429  6812  7293 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:42.429  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.429  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.429  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.429  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:42.429  6812  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 18:13:42.429  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:42.429  6812  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 18:13:42.429  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.429  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.429  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.429  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.429  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.429  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.429  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.429  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.429  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.429  6812  6812 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.429  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.429  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.439  6812  7131 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-12 18:13:42.439  6812  7131 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:13:42.439  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:42.439  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.439  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.439  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.439  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.439  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.439  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.439  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.439  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.439  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.439  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.439  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.439  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.439  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.439  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.439  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.439  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.439  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.439  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.439  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.439  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.439  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.439  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.439  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.439  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.439  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.439  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.439  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.449  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:42.449  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:42.449  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:42.449  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:42.449  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.449  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.449  6812  7131 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e0061dc not in the list
09-12 18:13:42.449  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.449  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:42.449  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.449  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:42.449  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:42.449  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:42.449  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:42.449  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:42.449  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:42.449  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2022e2e5 not in the list
,09-12 18:13:42.449  6812  7131 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:42.449  6812  7131 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:42.449  6812  7131 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 18:13:42.449  6812  7131 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:13:42.449  6812  7131 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:13:42.449  6812  7131 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 18:13:42.449  6812  7131 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-12 18:13:42.459  6812  7131 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-12 18:13:42.459  6812  7131 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 18:13:42.459  6812  7131 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 18:13:42.459  6812  7131 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-12 18:13:42.459  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:42.459  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b0513f added. We now have 2 listener(s)
09-12 18:13:42.459  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:42.459  6812  7131 D BluetoothAdapter: enable()
,09-12 18:13:42.459  6812  7131 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 18:13:42.469  1019  1138 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 18:13:42.469  1019  1138 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:42.469  1019  1138 D SecContentProvider2: mCursor = null
,09-12 18:13:42.469  1019  1138 D WifiService: setWifiEnabled: true pid=6812, uid=10170
09-12 18:13:42.469  1019  1138 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:13:42.469  1019  1138 W WifiService: Failed getting userId using ActivityManagerNative
09-12 18:13:42.469  1019  1138 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:13:42.469  1019  1138 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 18:13:42.469  1019  1138 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 18:13:42.469  1019  1138 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 18:13:42.469  1019  1138 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 18:13:42.469  1019  1138 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:13:42.469  1019  1138 D SettingsProvider: name = wifi_on
,09-12 18:13:42.469  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:42.469  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@208dfa0c added. We now have 3 listener(s)
09-12 18:13:42.469  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:42.479  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:13:42.479  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@feb4f55 added. We now have 4 listener(s)
09-12 18:13:42.479  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:42.479  6976  7078 D Finsky  : [1309] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-12 18:13:42.479  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:13:42.479  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a1add6a added. We now have 5 listener(s)
09-12 18:13:42.479  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:42.479  6976  6976 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-12 18:13:42.489  1019  1562 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 18:13:42.489  1019  1562 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:42.489  1019  1562 D SecContentProvider2: mCursor = null
,09-12 18:13:42.489  1019  1562 D WifiService: setWifiEnabled: false pid=6812, uid=10170
,09-12 18:13:42.489  1019  1562 D SettingsProvider: name = wifi_on
,09-12 18:13:42.489  6812  7131 D BluetoothAdapter: disable()
,09-12 18:13:42.499  1019  1130 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 18:13:42.499  1364  1364 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 18:13:42.499  1364  1364 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-12 18:13:42.499  1364  1364 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 18:13:42.499  1364  1364 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 18:13:42.499  1019  1563 D SettingsProvider: name = bluetooth_on,
,09-12 18:13:42.499  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:13:42.529  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:42.529  3278  3355 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 18:13:42.529  3278  3355 D BluetoothAdapterProperties: Setting state to 13
,09-12 18:13:42.529  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:13:42.529  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 18:13:42.529  3278  3355 D BluetoothAdapterService: updateAdapterState state is 13
,09-12 18:13:42.539  1364  1364 I wpa_supplicant: nl80211: Received scan results (18 BSSes),
09-12 18:13:42.539  1019  1130 E WifiNative-wlan0: do suspend true
09-12 18:13:42.539  1019  1129 D WifiP2pService: InactiveState{ what=147461 }
09-12 18:13:42.539  1019  1129 D WifiP2pService: P2pEnabledState{ what=147461 }
09-12 18:13:42.539  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.539  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-12 18:13:42.539  1019  1129 D WifiP2pService: DefaultState{ what=147461 }
,09-12 18:13:42.539  1019  1031 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:13:42.539  1019  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.539  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.539  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.539  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:42.539  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:42.539  3278  3278 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-12 18:13:42.539  3278  3355 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:42.539  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 18:13:42.539  3278  3355 D BluetoothAdapterService: terminating service from this receiver
09-12 18:13:42.539  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:42.539  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:42.539  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:13:42.539  1019  1550 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.539  1019  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.539  1019  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.539  3278  3278 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@dc58741, channel: 19, state: LISTENING
09-12 18:13:42.539  3278  3278 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@dc58741, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@271e520e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@299694e6mSocket: android.net.LocalSocket@265faa27 impl:android.net.LocalSocketImpl@3dbd84d4 fd:FileDescriptor[80]
09-12 18:13:42.539  3278  3278 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@265faa27 impl:android.net.LocalSocketImpl@3dbd84d4 fd:FileDescriptor[80]
09-12 18:13:42.539  3278  3355 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 18:13:42.539  3278  3355 D BluetoothAdapterProperties: mDiscovering is false
09-12 18:13:42.549  1019  1523 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 18:13:42.549  3278  3355 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 18:13:42.549  4893  4893 D BluetoothPbap: Proxy object disconnected
09-12 18:13:42.549  4893  4893 D PbapServerProfile: Bluetooth service disconnected
,09-12 18:13:42.549  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.559  3278  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 18:13:42.559  3278  3358 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:13:42.559  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-12 18:13:42.559  3278  3355 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-12 18:13:42.559  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:42.559  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:42.559  3278  3355 E bt-btif : cmd socket is not created
,09-12 18:13:42.559  3278  5281 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:13:42.559  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:42.559  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:42.559  3278  3360 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-12 18:13:42.559  6812  7293 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3326aaf8, channel: -1, state: INIT
09-12 18:13:42.559  6812  7293 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3326aaf8, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35e8bd1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32816636mSocket: android.net.LocalSocket@32012937 impl:android.net.LocalSocketImpl@3c977ea4 fd:FileDescriptor[105]
09-12 18:13:42.559  6812  7293 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32012937 impl:android.net.LocalSocketImpl@3c977ea4 fd:FileDescriptor[105]
09-12 18:13:42.559  6812  7293 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1344)
,09-12 18:13:42.559  3278  3355 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 18:13:42.569  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.569  3278  3360 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-12 18:13:42.569  3278  3360 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-12 18:13:42.569  3278  3360 W bt-btif : invalid rfc slot id: 4
,09-12 18:13:42.579  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 18:13:42.579  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 18:13:42.579  3278  3360 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:13:42.579  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:42.579  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 18:13:42.579  3278  3360 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 18:13:42.589  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:42.589  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-12 18:13:42.589  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:13:42.589  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
09-12 18:13:42.589  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 18:13:42.599  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:42.599  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 18:13:42.599  1181  1181 D BluetoothTile:  getBluetoothState : 13
,09-12 18:13:42.599  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:42.599  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:42.599  2020  2020 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:13:42.599  3278  3278 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ea71972, channel: 5, state: LISTENING
,09-12 18:13:42.599  3278  3278 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ea71972, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10dee009, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1712c1c3mSocket: android.net.LocalSocket@29d81a40 impl:android.net.LocalSocketImpl@3682dd79 fd:FileDescriptor[82]
,09-12 18:13:42.599  3278  3278 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29d81a40 impl:android.net.LocalSocketImpl@3682dd79 fd:FileDescriptor[82]
,09-12 18:13:42.599  1019  1316 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:42.599  1019  1562 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:42.609  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 18:13:42.609  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 18:13:42.609  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:42.609  3278  3278 I BtOppRfcommListener: stopping Accept Thread
,09-12 18:13:42.609  3278  3278 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19c95abe, channel: 12, state: LISTENING
09-12 18:13:42.609  3278  3278 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19c95abe, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a87ae28, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@155b71fmSocket: android.net.LocalSocket@30449a6c impl:android.net.LocalSocketImpl@fcad835 fd:FileDescriptor[85]
09-12 18:13:42.609  3278  3278 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@30449a6c impl:android.net.LocalSocketImpl@fcad835 fd:FileDescriptor[85]
,09-12 18:13:42.609  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:42.609  3278  5281 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 18:13:42.609  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.619   277   978 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:42.619  1707  2528 V NativeCrypto: Read error: ssl=0xb9197ca8: I/O error during system call, Connection timed out
,09-12 18:13:42.619  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.619  3278  3278 V BluetoothOppManager: cleanUp...
,09-12 18:13:42.619  1707  2528 V NativeCrypto: SSL shutdown failed: ssl=0xb9197ca8: I/O error during system call, Broken pipe
,09-12 18:13:42.629  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:13:42.629  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:13:42.629  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:13:42.629  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-12 18:13:42.629  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:13:42.629  1019  3816 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-12 18:13:42.629  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 18:13:42.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.629  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:42.629  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:13:42.629  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 18:13:42.629  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:42.629  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-12 18:13:42.629  1019  1763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-12 18:13:42.629  1019  1763 I qtaguid : Tagging socket 350 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,09-12 18:13:42.629  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 18:13:42.629  4893  4893 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:42.639  1019  1763 I qtaguid : Untagging socket 350
09-12 18:13:42.639  1019  1763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:42.639  1019  1562 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 18:13:42.639  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.639  1019  1129 D WifiP2pService: InactiveState{ what=131204 }
09-12 18:13:42.639  1019  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 18:13:42.639  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.639  1019  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.639  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:42.649  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 18:13:42.649  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-12 18:13:42.649  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:42.649  1019  1019 D RttService: SCAN_AVAILABLE : 1
09-12 18:13:42.649  1019  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:13:42.649  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:13:42.649  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
,09-12 18:13:42.659  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:13:42.659  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:42.659  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:42.659  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.659  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.659  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.659  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:42.669  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:42.679  4893  4893 D DockEventReceiver: finishStartingService: stopping service
09-12 18:13:42.679  1019  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 18:13:42.679  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:42.679  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 18:13:42.679  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:42.679  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 18:13:42.679  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-12 18:13:42.679  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:42.679  1019  1049 D WifiDisplayController: disconnect
09-12 18:13:42.679  1019  1049 D WifiDisplayController: updateConnection
09-12 18:13:42.679  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:42.679  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 18:13:42.679  1019  1129 D WifiP2pService: P2pDisablingState
09-12 18:13:42.679  1019  1129 D WifiP2pService: P2pDisablingState{ what=147458 },
09-12 18:13:42.679  1019  1129 D WifiP2pService: p2p socket connection lost
09-12 18:13:42.679  1019  1129 D WifiP2pService: P2pDisabledState
,09-12 18:13:42.679  1019  1130 E WifiNative-wlan0: do suspend true,
09-12 18:13:42.679  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:13:42.689  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 18:13:42.689  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:42.689  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:42.689   277   974 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 18:13:42.689   277   974 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-12 18:13:42.689  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 18:13:42.689  1019  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-12 18:13:42.689  1019  1132 V NetworkStats: updateIfacesLocked()
09-12 18:13:42.689  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.689  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:13:42.689  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:42.689  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 18:13:42.689  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 18:13:42.689  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-12 18:13:42.689  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-12 18:13:42.689  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.689  1019  1132 V NetworkStats: performPollLocked() took 5ms
,09-12 18:13:42.689  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.689  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.699  1019  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-12 18:13:42.699  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
09-12 18:13:42.699  1019  1132 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:13:42.699  1019  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:42.699  1019  1550 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 18:13:42.699  1019  1129 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 18:13:42.699  1019  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-12 18:13:42.699  1181  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
09-12 18:13:42.699  1019  1132 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-12 18:13:42.699  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-12 18:13:42.699  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 18:13:42.699  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
09-12 18:13:42.699  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-12 18:13:42.699  1482  1482 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 18:13:42.699  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:13:42.699  1482  1482 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:13:42.699  1019  1132 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 18:13:42.699  1019  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-12 18:13:42.699  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:13:42.699  1019  1132 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:42.699  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 18:13:42.699  1019  1133 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:13:42.699  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.699  1019  1127 V NetworkStats: updateIfacesLocked()
09-12 18:13:42.699  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-12 18:13:42.699  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:13:42.699  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:42.699  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:13:42.709  1019  1523 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-12 18:13:42.709  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
09-12 18:13:42.709  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 18:13:42.709  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 18:13:42.709  1181  1181 D StatusBar.NetworkController: updateDataNetType()
09-12 18:13:42.709  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.709  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:42.709  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.709  1019  1127 V NetworkStats: performPollLocked() took 5ms
09-12 18:13:42.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.709  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.709  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.709  1019  1128 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 18:13:42.709  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:42.719  1019  1129 D WifiP2pService: P2pDisabledState{ what=143375 }
09-12 18:13:42.719  1019  1129 D WifiP2pService: DefaultState{ what=143375 }
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:13:42.719  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:42.719  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:42.719  7306  7306 E Zygote  : MountEmulatedStorage()
,09-12 18:13:42.719  7306  7306 E Zygote  : v2
09-12 18:13:42.719  7306  7306 I libpersona: KNOX_SDCARD checking this for 10055
09-12 18:13:42.719  7306  7306 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:42.729  1019  1523 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7306 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-12 18:13:42.729  7306  7306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:42.729   277   978 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:42.729  7306  7306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:42.739  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.739  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.739  1364  1364 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-12 18:13:42.739  7306  7306 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:42.739  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:13:42.739  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:42.739  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:42.739  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.739  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 18:13:42.739  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.739  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.739  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:42.749  1019  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 18:13:42.749  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:13:42.749  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:42.749  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:42.749  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:42.749  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:42.749  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.749  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.749  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.749  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:42.759  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:42.759  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:13:42.759  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:42.759  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:42.759  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:42.759  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.759  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.759  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.759  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:42.759  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 18:13:42.759  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:42.759  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:42.759  1181  1181 D HotspotTile: onReceive : 0, 0
09-12 18:13:42.759  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:42.759  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:42.759  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:42.759  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:42.769  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:42.769  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:42.769  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 18:13:42.769  3278  3355 D BtConfig.SecureMode: isSecureModeOn:false
09-12 18:13:42.769  3278  3355 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 18:13:42.769  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-12 18:13:42.769  3278  3355 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-12 18:13:42.769  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 18:13:42.769  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:42.769  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:42.769  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:42.769  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:42.769  1019  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.769  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.769  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.769  1019  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.769  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.769  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 18:13:42.769  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 18:13:42.769  7306  7306 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:42.769  7306  7306 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:42.779  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:42.779  3278  3278 D HeadsetService: Received stop request...Stopping profile...
,09-12 18:13:42.779  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.779  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.779  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:42.779  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.779  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.789  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-12 18:13:42.789  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:42.789  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:42.789  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:13:42.789  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 18:13:42.789  3278  3278 D A2dpService: Received stop request...Stopping profile...
09-12 18:13:42.789  3278  3419 D A2dpStateMachine: Exit Disconnected: -1
,09-12 18:13:42.789  1019  6909 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.789  1019  6909 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.789  4893  4893 D HeadsetProfile: Bluetooth service disconnected
09-12 18:13:42.789  1019  6909 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.789  1019  6909 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.789  1019  6909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.799  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-12 18:13:42.799  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
09-12 18:13:42.799  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:42.799  4893  4893 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:42.799  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:42.799  4893  4893 D A2dpProfile: Bluetooth service disconnected
09-12 18:13:42.799  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 18:13:42.799  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 18:13:42.799  1019  1523 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.799  1019  1523 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.809  1019  1523 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.809  1019  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.809  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.809  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 18:13:42.809  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.809  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:13:42.809  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 18:13:42.809  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-12 18:13:42.809  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.809  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.809  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.809  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.809  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:42.809  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:42.809  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:42.809  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.819  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.819  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:42.819  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.819  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-12 18:13:42.819  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 18:13:42.819  3278  3355 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-12 18:13:42.819  1019  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.819  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-12 18:13:42.819  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.819  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.819  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.819  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:42.819  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:42.819  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:42.819  7306  7306 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-12 18:13:42.819  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:42.819  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:42.829  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:42.829  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:13:42.829  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:42.829  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:13:42.829  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:13:42.829  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:13:42.829  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 18:13:42.829  3278  3355 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 18:13:42.829  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 18:13:42.829  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:42.829  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 18:13:42.829  3278  3278 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 18:13:42.829  3278  3278 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:13:42.829  3278  3278 D HidService: Received stop request...Stopping profile...
09-12 18:13:42.829  3278  3278 D HidService: Stopping Bluetooth HidService
09-12 18:13:42.829  3278  3278 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 18:13:42.829  3278  3278 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 18:13:42.829  3278  3278 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 18:13:42.829  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:42.839  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 18:13:42.839  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:42.839  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 18:13:42.839  3278  3278 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:42.839  3278  3278 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-12 18:13:42.839  3278  3420 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 18:13:42.839  3278  3278 I GKI_LINUX: GKI_exit_task 2 done
09-12 18:13:42.839  3278  3278 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-12 18:13:42.839  3278  3278 D HealthService: Received stop request...Stopping profile...
09-12 18:13:42.839  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:42.839  4893  4893 D BluetoothInputDevice: Proxy object disconnected
09-12 18:13:42.839  4893  4893 D HidProfile: Bluetooth service disconnected
,09-12 18:13:42.839  3278  3278 D PanService: Received stop request...Stopping profile...
09-12 18:13:42.839  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:42.849  4893  4893 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:13:42.849  4893  4893 D PanProfile: Bluetooth service disconnected
09-12 18:13:42.849  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 18:13:42.849  3278  3278 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 18:13:42.849  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:42.859  4893  4893 D BluetoothMap: Proxy object disconnected
09-12 18:13:42.859  4893  4893 D MapProfile: Bluetooth service disconnected
,09-12 18:13:42.859  3278  3278 D SapService: Received stop request...Stopping profile...
09-12 18:13:42.859  3278  3278 D SapService: Stopping Bluetooth SapService
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:42.859  1364  1364 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:42.859  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 18:13:42.859  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.859  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 18:13:42.859  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.859  3278  3278 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 18:13:42.859  3278  3278 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:13:42.859  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-12 18:13:42.859  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.859  3278  3278 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:13:42.859  3278  3278 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 18:13:42.859  7306  7306 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-12 18:13:42.859  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 18:13:42.859  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 18:13:42.859  7306  7306 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-12 18:13:42.859  7306  7306 D UserAnalysis: Create SecureDbHelper
09-12 18:13:42.859  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 18:13:42.859  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. ,
09-12 18:13:42.859  3278  3278 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 18:13:42.859  3278  3278 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 18:13:42.859  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-12 18:13:42.859  3278  3355 D BluetoothAdapterProperties: Setting state to 10
09-12 18:13:42.859  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 18:13:42.859  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:42.859  3278  3355 D BluetoothAdapterService: updateAdapterState state is 10
09-12 18:13:42.859  3278  3355 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:42.859  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 18:13:42.859  3278  3355 I BluetoothAdapterState: Entering OffState
,09-12 18:13:42.869  4893  5001 D Bluetoothsap: onBluetoothStateChange: up=false,
09-12 18:13:42.869  4893  5001 D Bluetoothsap: Unbinding service...
,09-12 18:13:42.869  4893  4893 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 18:13:42.869  4893  4893 D SapProfile: Bluetooth service disconnected
,09-12 18:13:42.869  4893  4901 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:42.869  7306  7306 D IntelligenceServiceApplication: onCreate()
,09-12 18:13:42.879  1019  3816 I ActivityManager: Killing 6852:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-12 18:13:42.879  4893  4905 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 18:13:42.879  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:42.879  1181  1877 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:42.879  7306  7306 D IntelligenceServiceApplication: no applications having user consent for prediction
09-12 18:13:42.879  1181  1877 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:42.879  1707  4492 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.889  1707  4492 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:42.889  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.889  1482  2482 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.889  1019  3816 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-12 18:13:42.889  1482  2482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:42.889  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.889  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.889  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.889  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.889  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.889  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.889  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.889  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.889  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.899  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.899  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.899  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.899  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.899  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.899  7327  7327 E Zygote  : MountEmulatedStorage()
09-12 18:13:42.899  7327  7327 E Zygote  : v2
,09-12 18:13:42.899  7327  7327 I libpersona: KNOX_SDCARD checking this for 10105
09-12 18:13:42.899  7327  7327 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:42.899  7327  7327 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:42.899  1364  1364 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 18:13:42.899  1019  3816 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7327 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-12 18:13:42.909  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:42.909  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:13:42.909  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 18:13:42.909  7327  7327 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:42.909  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 18:13:42.909  1469  1496 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.909  1469  1496 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.909  4893  5001 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.909  4893  5001 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.909  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.909  4893  4901 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 18:13:42.909  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 18:13:42.909  7306  7306 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-12 18:13:42.909  7327  7327 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 18:13:42.909  6812  6824 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.909  6812  6824 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.909  6812  6824 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 18:13:42.909  6812  6824 D BluetoothLeAdvertiser: Exit stop advertising
09-12 18:13:42.909  6812  6824 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 18:13:42.909  6812  6824 D BluetoothLeScanner: Exiting stopAllScan
09-12 18:13:42.909  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.909  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.909  1685  1693 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.909  1685  1693 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:42.909  1456  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.909  1456  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:42.909  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:42.909  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 18:13:42.909  4893  5001 D BluetoothMap: onBluetoothStateChange: up=false
09-12 18:13:42.909  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:42.909  3278  3291 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.909  3278  3291 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.909  3278  3397 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:42.909  7306  7306 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-12 18:13:42.919  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 18:13:42.919  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:42.919  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 18:13:42.919  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:42.919  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-12 18:13:42.919  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-12 18:13:42.919  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:42.919  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.929  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:42.929  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.929  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:42.929  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 18:13:42.929  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:42.929  1181  1181 D BluetoothTile:  getBluetoothState : 10
,09-12 18:13:42.929  1364  1364 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-12 18:13:42.929  1364  1364 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 18:13:42.929  1364  1364 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 18:13:42.929  1364  1364 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 18:13:42.929  1364  1364 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:13:42.929  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:42.929  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:13:42.929  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:13:42.929  1019  1133 D Tethering: InitialState.processMessage what=4
,09-12 18:13:42.929  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:42.929  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:42.939  1019  1133 E Tethering: No numeric data
09-12 18:13:42.939  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:13:42.939  1019  1133 D Tethering: clearTetheredNotification()
09-12 18:13:42.939  2020  2020 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 18:13:42.939  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:42.939  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:42.939  1019  1562 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 18:13:42.939  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:42.939  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:13:42.939  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:13:42.939  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:42.939  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.939  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:42.939  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 18:13:42.939  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.939  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:13:42.939  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 18:13:42.939  1019  1138 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-12 18:13:42.939  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:42.939  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:13:42.939  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-12 18:13:42.939  1181  1181 D HotspotTile: updateTetherState():false, false
09-12 18:13:42.939  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 18:13:42.939  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:42.939  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:13:42.939  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:13:42.939  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.939  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.949  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.949  1019  1127 V NetworkStats: performPollLocked() took 5ms
,09-12 18:13:42.949  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:42.949  1482  1482 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:42.949  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:42.949  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:42.949  1482  1482 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:42.949  7327  7327 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:42.949  7327  7327 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.049   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 18:13:43.049   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:43.049  7327  7358 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 18:13:43.059   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 18:13:43.059   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:43.059  7327  7358 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 18:13:43.139  1364  1364 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:43.179  1364  1364 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 18:13:43.179  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:43.179  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:43.179  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:43.189  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 18:13:43.189  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 18:13:43.189  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:43.199  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:43.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:43.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:43.199  1685  2071 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:43.199  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:43.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:43.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-12 18:13:43.199  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:43.199  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:43.199  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:13:43.199  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:43.199  1181  1181 D HotspotTile: onReceive : 1, 0
,09-12 18:13:43.199  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:43.209  1019  1019 I ApplicationPolicy: updateDataUsageMap
,09-12 18:13:43.229  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:43.239  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 18:13:43.249  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=196 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.k.d(PG:583)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:43.259  7327  7327 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:43.259  7327  7327 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:43.269  1019  1138 I ActivityManager: Killing 6877:com.google.android.apps.docs/u0a87 (adj 15): empty #21
09-12 18:13:43.269  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:43.269  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 18:13:43.269  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.269  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.269  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:13:43.279  1543  1543 I Hs20UtilService: Starting #8
09-12 18:13:43.279  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:13:43.279  1543  1608 I Hs20UtilService: Message received 5007
09-12 18:13:43.279  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 18:13:43.279  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 18:13:43.279  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:43.289  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:43.289  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:13:43.289  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 18:13:43.289  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.289  1019  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:43.289  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-12 18:13:43.289  1019  3816 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-12 18:13:43.299  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.299  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.299  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.299  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.309  7369  7369 E Zygote  : MountEmulatedStorage()
09-12 18:13:43.309  7369  7369 E Zygote  : v2
09-12 18:13:43.309  7369  7369 I libpersona: KNOX_SDCARD checking this for 10102
09-12 18:13:43.309  7369  7369 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:43.309  7369  7369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:43.309  1019  3816 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7369 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-12 18:13:43.309  7369  7369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:43.319  7369  7369 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 18:13:43.329  7327  7368 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 18:13:43.339  7369  7369 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:43.339  7369  7369 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.359  7369  7369 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 18:13:43.369  1019  1398 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:43.369  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.369  1019  1398 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:43.369  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 18:13:43.539  7369  7391 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-12 18:13:43.549  7369  7391 I Babel_SMS: MmsConfig.loadMmsSettings
,09-12 18:13:43.549  7369  7391 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-12 18:13:43.549  7369  7391 I Babel_SMS: MmsConfig.loadFromDatabase
,09-12 18:13:43.569  7369  7391 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-12 18:13:43.569  7369  7391 I Babel_SMS: MmsConfig.loadFromResources
,09-12 18:13:43.569  7369  7391 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-12 18:13:43.579  7369  7391 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-12 18:13:43.599  1019  1514 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-12 18:13:43.599  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-12 18:13:43.599  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.599  1019  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:43.599  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 18:13:43.619  7369  7369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:43.619  7369  7369 I Babel_Crash: startup - clean
,09-12 18:13:43.649  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:13:43.649  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:43.649  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:43.659  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:43.659  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:43.659  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:43.659  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:43.659  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 18:13:43.659  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.659  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.659  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.659  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.669  7369  7369 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-12 18:13:43.669  7369  7369 W AudioCapabilities: Unsupported mime audio/evrc
09-12 18:13:43.669  7369  7369 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 18:13:43.669  7394  7394 E Zygote  : MountEmulatedStorage(),
09-12 18:13:43.669  7394  7394 I libpersona: KNOX_SDCARD checking this for 10064
09-12 18:13:43.669  7394  7394 E Zygote  : v2
09-12 18:13:43.669  7394  7394 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:43.669  7394  7394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:43.669  1019  1316 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7394 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:43.679  7394  7394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:13:43.679  7394  7394 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:43.679   294   294 E SMD     : DCD OFF
,09-12 18:13:43.679  7369  7369 W AudioCapabilities: Unsupported mime audio/mpeg-L1
09-12 18:13:43.679  7369  7369 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-12 18:13:43.689  7369  7369 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-12 18:13:43.689  7369  7369 W AudioCapabilities: Unsupported mime audio/x-ima
,09-12 18:13:43.689  7369  7369 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 18:13:43.699  7394  7394 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:43.699  7394  7394 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.699  7369  7369 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 18:13:43.709  7394  7394 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 18:13:43.709  7369  7369 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 18:13:43.719  7369  7369 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 18:13:43.719  7369  7369 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-12 18:13:43.729  7369  7369 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 18:13:43.729  7369  7369 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 18:13:43.729  7369  7369 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-12 18:13:43.729  7394  7394 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:43.729  7369  7369 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-12 18:13:43.739  7369  7369 W VideoCapabilities: Unsupported mime video/mp43
,09-12 18:13:43.739  7394  7394 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 18:13:43.739  7369  7369 W VideoCapabilities: Unsupported mime video/sorenson
,09-12 18:13:43.749  7369  7369 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-12 18:13:43.759  7369  7369 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 18:13:43.769  7394  7394 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:13:43.769  1019  3813 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-12 18:13:43.769  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.769  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.769  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.769  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.779  7409  7409 E Zygote  : MountEmulatedStorage(),
09-12 18:13:43.779  7409  7409 E Zygote  : v2,
09-12 18:13:43.779  7409  7409 I libpersona: KNOX_SDCARD checking this for 10065
09-12 18:13:43.779  7409  7409 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:43.789  7409  7409 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:43.789  7409  7409 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:43.789  1019  3813 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7409 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:13:43.789  1019  3813 I ActivityManager: Killing 6895:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-12 18:13:43.789  7409  7409 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:43.809  7409  7409 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:43.809  7409  7409 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.809  7369  7369 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:43.809   322   322 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 22.770ms
09-12 18:13:43.809  7369  7369 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:43.819  7369  7369 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:43.819  7369  7369 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:43.829  1019  3813 I ActivityManager: Killing 6955:com.sec.pcw.device/1000 (adj 15): empty #21
,09-12 18:13:43.829  7369  7369 I vclib   : onServiceConnected
,09-12 18:13:43.829   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 17.444ms
,09-12 18:13:43.829  7409  7409 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:43.849  1019  1398 I ActivityManager: Killing 6831:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-12 18:13:43.849  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.849  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.849  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-12 18:13:43.849   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 836us total 18.809ms
,09-12 18:13:43.859  1019  3813 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:43.859  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:43.859  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.859  1019  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.859  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:43.859  1543  1543 I Hs20UtilService: Starting #9
,09-12 18:13:43.869  1543  1608 I Hs20UtilService: Message received 5007
,09-12 18:13:43.869  1019  1046 D Tethering: interfaceRemoved wlan0
09-12 18:13:43.869  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
09-12 18:13:43.869  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:13:43.869  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:43.869  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:43.869  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:43.869  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:43.869  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:13:43.869  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:43.879  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.879  1019  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.879  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.879  1019  1398 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:43.879  1019  1398 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:43.889  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.889  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:43.889  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:43.889  1543  1543 I Hs20UtilService: Starting #10
,09-12 18:13:43.889  1543  1608 I Hs20UtilService: Message received 5011
09-12 18:13:43.889  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-12 18:13:43.889  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.889  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.889  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.889  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.899  7424  7424 E Zygote  : MountEmulatedStorage()
,09-12 18:13:43.899  7424  7424 E Zygote  : v2
09-12 18:13:43.899  7424  7424 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:43.899  7424  7424 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:43.899  7424  7424 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:43.899  1019  1031 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7424 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-12 18:13:43.909  7424  7424 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:13:43.909  7424  7424 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:43.929  7424  7424 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:43.929  7424  7424 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.959  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:43.959  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:43.959  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 18:13:43.959  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:43.959  1019  1563 I ActivityManager: Killing 7021:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-12 18:13:43.969  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.969  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.969  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.979  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.979  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.979  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.979  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.979  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.989  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.989  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,09-12 18:13:43.989  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.989  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.989  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.999  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.999  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.999  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.999  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.999  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:44.009  4893  4893 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:44.009  1019  1561 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 18:13:44.009  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:44.009  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.009  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:44.009  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:44.019  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:44.019  4893  4893 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:44.019  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:44.029  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:44.029  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 18:13:44.039  1019  1316 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:44.049  1019  1316 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:44.049  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:44.049  1019  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:44.049  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:44.049  1543  1543 I Hs20UtilService: Starting #11
,09-12 18:13:44.049  1543  1608 I Hs20UtilService: Message received 5011
,09-12 18:13:44.049  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:13:44.049  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:44.049  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:44.049  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:44.059  1019  3816 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-12 18:13:44.059  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.059  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.059  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.059  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.069  7442  7442 E Zygote  : MountEmulatedStorage()
,09-12 18:13:44.069  7442  7442 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:44.069  7442  7442 E Zygote  : v2
09-12 18:13:44.069  7442  7442 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:44.069  7442  7442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:44.069  1019  3816 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 18:13:44.069  7442  7442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:44.069  7442  7442 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.089  7442  7442 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.089  7442  7442 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.109  7442  7442 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-12 18:13:44.109  7442  7442 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-12 18:13:44.109  7442  7442 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-12 18:13:44.119  7442  7442 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 18:13:44.119  7442  7442 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 18:13:44.119  7442  7442 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 18:13:44.119  7442  7442 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:44.129  1019  6909 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-12 18:13:44.129  1019  6909 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-12 18:13:44.129  1019  6909 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-12 18:13:44.129  1019  6909 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-12 18:13:44.129  1019  6909 I ActivityManager: Killing 7050:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-12 18:13:44.129  7442  7457 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-12 18:13:44.139  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-12 18:13:44.139  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.139  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.139  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.139  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.149  7459  7459 E Zygote  : MountEmulatedStorage()
,09-12 18:13:44.149  7459  7459 E Zygote  : v2
09-12 18:13:44.149  7459  7459 I libpersona: KNOX_SDCARD checking this for 10001
09-12 18:13:44.149  7459  7459 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.149  7459  7459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 18:13:44.149  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7459 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:44.159  7459  7459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:13:44.159  7459  7459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.179  7459  7459 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 18:13:44.179  7459  7459 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.189  1019  1046 D Tethering: interfaceRemoved p2p0
,09-12 18:13:44.189  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 18:13:44.249  1019  1523 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-12 18:13:44.249  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.249  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.249  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.249  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.269  7476  7476 E Zygote  : MountEmulatedStorage()
,09-12 18:13:44.269  7476  7476 E Zygote  : v2
09-12 18:13:44.269  7476  7476 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:44.269  7476  7476 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.269  7476  7476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:44.269  1019  1523 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7476 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:13:44.269  1019  1523 I ActivityManager: Killing 7080:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-12 18:13:44.269  7476  7476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:44.269  7476  7476 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.289  7476  7476 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 18:13:44.289  7476  7476 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.329  7476  7476 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-12 18:13:44.459  7476  7476 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-12 18:13:44.479  7476  7476 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-12 18:13:44.479  7476  7476 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:44.479  7476  7476 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-12 18:13:44.479  7476  7476 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-12 18:13:44.479  7476  7476 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-12 18:13:44.479  1019  1398 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-12 18:13:44.489  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.489  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.489  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.489  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.509  1019  1398 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7491 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:44.509  7491  7491 E Zygote  : MountEmulatedStorage()
09-12 18:13:44.509  7491  7491 E Zygote  : v2
09-12 18:13:44.509  1019  1398 I ActivityManager: Killing 7106:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
09-12 18:13:44.509  7491  7491 I libpersona: KNOX_SDCARD checking this for 10008
09-12 18:13:44.509  7491  7491 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:44.509  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:44.519  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:44.519  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.539  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.549  7491  7491 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.619  1019  1562 I ActivityManager: Killing 6992:com.android.mms/u0a41 (adj 15): empty #21
,09-12 18:13:44.619  1019  1514 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-12 18:13:44.619  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
09-12 18:13:44.629  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:44.629  1019  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:44.629  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 18:13:44.639  1858  1858 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 18:13:44.639  1858  2798 I iu.UploadsManager: num queued entries: 0
,09-12 18:13:44.639  1858  2798 I iu.UploadsManager: num updated entries: 0
,09-12 18:13:44.639  1019  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:44.639  1019  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-12 18:13:44.639  1019  1523 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:44.639  1858  2798 I iu.SyncManager: NEXT; no task
,09-12 18:13:44.639  1019  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:44.639  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:44.649  1858  1858 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 18:13:44.649  1858  1858 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-12 18:13:44.659  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 18:13:44 GMT+02:00 2016
,09-12 18:13:44.659  1019  1523 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 18:13:44.659  1019  1523 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 18:13:44.669  1019  1523 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.669  1019  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:44.669  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 18:13:44.669  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-12 18:13:44.669  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-12 18:13:44.679  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-12 18:13:44.679  2804  2804 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 18:13:44.679  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.679  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.679  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.679  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.679  2804  2804 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 18:13:44.689  2804  7507 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 18:13:44.689  2804  7507 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-12 18:13:44.689  7508  7508 E Zygote  : MountEmulatedStorage()
,09-12 18:13:44.689  7508  7508 E Zygote  : v2
09-12 18:13:44.689  7508  7508 I libpersona: KNOX_SDCARD checking this for 10031
09-12 18:13:44.689  7508  7508 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.689  7508  7508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:44.699  7508  7508 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 18:13:44.699  2804  7507 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-12 18:13:44.699  7508  7508 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.699  2804  7507 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-12 18:13:44.699  1019  1316 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7508 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-12 18:13:44.709  1019  6909 D CountryDetector: No listener is left
,09-12 18:13:44.709  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-12 18:13:44.729  7508  7508 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.729  7508  7508 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.739   344   344 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:44.759  7508  7508 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-12 18:13:44.769  1019  1523 I ActivityManager: Killing 7150:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-12 18:13:44.789  1019  6909 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 18:13:44.789  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.789  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.789  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.789  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.789  2740  7523 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-12 18:13:44.799  2740  7523 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
09-12 18:13:44.799  2740  7523 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-12 18:13:44.799  2740  7523 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-12 18:13:44.799  2740  7523 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-12 18:13:44.819  1019  6909 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7524 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-12 18:13:44.819  7524  7524 E Zygote  : MountEmulatedStorage(),
09-12 18:13:44.819  7524  7524 E Zygote  : v2
,09-12 18:13:44.819  7524  7524 I libpersona: KNOX_SDCARD checking this for 10032
09-12 18:13:44.819  7524  7524 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.819  7524  7524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:44.829  7524  7524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:13:44.829  7524  7524 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.859  7524  7524 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.859  7524  7524 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.939  7524  7539 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-12 18:13:44.939  7524  7539 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 18:13:44.939  7524  7524 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-12 18:13:44.949  1019  3813 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-12 18:13:44.949  7524  7539 D SPPClientService: PushLog.txt file is not deleted.
09-12 18:13:44.949  7524  7539 D SPPClientService: PushLog.txt file is not deleted.
09-12 18:13:44.949  7524  7539 D SPPClientService: ============PushLog. stop!
,09-12 18:13:44.949  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.949  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.949  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.949  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.969  7541  7541 E Zygote  : MountEmulatedStorage(),
09-12 18:13:44.969  7541  7541 E Zygote  : v2
09-12 18:13:44.969  7541  7541 I libpersona: KNOX_SDCARD checking this for 10036
,09-12 18:13:44.969  7541  7541 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.969  1019  3813 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7541 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:13:44.969  1019  1138 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-12 18:13:44.969  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:44.969  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-12 18:13:44.969  1019  1138 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 18:13:44.969  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-12 18:13:44.969  7541  7541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:44.969  7541  7541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:44.979  7541  7541 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.999  7541  7541 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.999  7541  7541 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.999  7524  7547 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-12 18:13:45.009  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 18:13:45.029  1019  3816 I ActivityManager: Killing 7134:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-12 18:13:45.039  7541  7541 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2449a74e
,09-12 18:13:45.049  7541  7541 I SA      : [SSP] onCreated
,09-12 18:13:45.069  7541  7541 I SA      : [TPM] There is no property file
,09-12 18:13:45.069  7541  7541 I SA      : [SCU] isHaveSA() - false
,09-12 18:13:45.069  7541  7541 I SA      : [TPM] getModelProperty : null
,09-12 18:13:45.069  7541  7541 I SA      : [TPM] getCSCProperty : null
,09-12 18:13:45.069  7541  7541 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-12 18:13:45.069  7541  7541 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-12 18:13:45.069  7541  7541 I SA      : [DM] TFT FEATURE: false
,09-12 18:13:45.079  7541  7541 I SA      : [DM] init START
,09-12 18:13:45.079  7541  7541 I SA      : [DM] This device is not a Vodafone
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-12 18:13:45.089  7541  7541 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-12 18:13:45.099  7541  7541 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-12 18:13:45.099  7541  7541 I SA      : [SCU] isHaveSA() - false,
09-12 18:13:45.099  7541  7541 I SA      : support phone number id : false,
09-12 18:13:45.099  7541  7541 I SA      : [DM] Supports Ref Jpn : true
,09-12 18:13:45.099  7541  7541 I SA      : [DM] init END
09-12 18:13:45.109  7541  7541 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-12 18:13:45.109  7541  7541 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
09-12 18:13:45.109  7541  7541 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-12 18:13:45.109  7541  7541 I SA      : [SLFUCHKMGR] constructor called,
,09-12 18:13:45.119  7541  7541 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-12 18:13:45.119  7541  7541 I SA      : [OR] == isSIMCardReady false ==
,09-12 18:13:45.119  7541  7541 I SA      : [SCU] == networkStateCheck == false
,09-12 18:13:45.119  7541  7541 I SA      : [OR] onReceive END
,09-12 18:13:45.129  1019  1523 I ActivityManager: Killing 7169:com.wsomacp/u0a23 (adj 15): empty #21
,09-12 18:13:45.129  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:45.139  1839  1839 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 18:13:45.149  2675  2683 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-12 18:13:45.149  1839  1839 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-12 18:13:45.149  1839  1839 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-12 18:13:45.149  1839  1839 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-12 18:13:45.149  1839  1839 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 18:13:45.149  1839  1839 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 18:13:45.149  1839  1839 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-12 18:13:45.159  1019  3816 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-12 18:13:45.159  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.159  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.159  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.159  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.169  1019  3816 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7563 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-12 18:13:45.179  7563  7563 E Zygote  : MountEmulatedStorage()
09-12 18:13:45.179  7563  7563 E Zygote  : v2
09-12 18:13:45.179  7563  7563 I libpersona: KNOX_SDCARD checking this for 10077
09-12 18:13:45.179  7563  7563 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:45.179  7563  7563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:45.179  7563  7563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 18:13:45.179  7563  7563 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-12 18:13:45.199  7563  7563 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:45.199  7563  7563 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:45.389  1019  3813 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-12 18:13:45.389  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-12 18:13:45.389  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:45.389  1019  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:45.389  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 18:13:45.399  1019  3816 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-12 18:13:45.399  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.399  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.399  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.399  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.409  7581  7581 E Zygote  : MountEmulatedStorage()
09-12 18:13:45.409  1019  3816 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7581 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:13:45.409  7581  7581 E Zygote  : v2
09-12 18:13:45.409  7581  7581 I libpersona: KNOX_SDCARD checking this for 10110
09-12 18:13:45.409  7581  7581 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:45.409  7581  7581 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:45.409  1019  1316 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-12 18:13:45.409  1019  1316 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-12 18:13:45.409  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:45.409  1019  1316 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:45.409  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 18:13:45.419  7581  7581 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 18:13:45.419  7369  7580 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 18:13:45.419  7581  7581 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-12 18:13:45.429  1019  1032 I ActivityManager: Killing 7210:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-12 18:13:45.439  7581  7581 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:45.439  7581  7581 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:45.549  1019  3816 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 18:13:45.549  1019  3816 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:45.549  1019  3816 D SecContentProvider2: mCursor = null
,09-12 18:13:45.549  1019  3816 D WifiService: setWifiEnabled: true pid=6812, uid=10170
09-12 18:13:45.549  1019  3816 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:13:45.549  1019  3816 W WifiService: Failed getting userId using ActivityManagerNative
09-12 18:13:45.549  1019  3816 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:13:45.549  1019  3816 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 18:13:45.549  1019  3816 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 18:13:45.549  1019  3816 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 18:13:45.549  1019  3816 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 18:13:45.549  1019  3816 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 18:13:45.549  1019  3816 D SettingsProvider: name = wifi_on
,09-12 18:13:45.559  1019  1130 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 18:13:45.589  1019  1562 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 18:13:45.739   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 18:13:45.739   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:45.739   344   344 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:45.739  7581  7601 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 18:13:45.749   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 18:13:45.749   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:45.749  7581  7601 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 18:13:45.759   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 18:13:45.759   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:45.759  7581  7602 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 18:13:45.769   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 18:13:45.769   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:45.769  7581  7602 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 18:13:45.789  7581  7581 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 18:13:45.789  7581  7581 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 18:13:45.789  7581  7581 I GAv4    :   adb logcat -s GAv4
,09-12 18:13:45.819  7581  7581 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:45.819  1019  1563 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 18:13:45.829  7581  7581 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:45.839  7581  7610 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 18:13:45.949  1019  1046 D Tethering: interfaceAdded wlan0
,09-12 18:13:45.959  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:45.959  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:45.959  1019  1133 E Tethering: No numeric data
,09-12 18:13:45.959  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 18:13:45.959  1019  1133 D Tethering: clearTetheredNotification()
09-12 18:13:45.959  1019  1133 D Tethering: InitialState.processMessage what=4
09-12 18:13:45.959  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:45.959  1019  1133 E Tethering: No numeric data
,09-12 18:13:45.959  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 18:13:45.959  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:13:45.959  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:45.959  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:13:45.959  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 18:13:45.959  1181  1181 D HotspotTile: updateTetherState():false, false
09-12 18:13:45.969  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-12 18:13:45.969  1019  1133 D Tethering: clearTetheredNotification()
,09-12 18:13:45.969  1019  1046 D Tethering: interfaceAdded p2p0
,09-12 18:13:45.969  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-12 18:13:45.969   277   978 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 18:13:45.969  1019  1127 V NetworkStats: performPollLocked() took 7ms
09-12 18:13:45.969  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:45.969   277   978 D SoftapController: Softap fwReload - Ok
,09-12 18:13:45.969  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:45.969  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:13:45.969   277   978 D CommandListener: Setting iface cfg
09-12 18:13:45.969   277   978 D CommandListener: Trying to bring down wlan0
,09-12 18:13:45.969  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:13:45.969  1181  1181 D HotspotTile: updateTetherState():false, false
,09-12 18:13:45.969   277   978 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:45.969  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:45.969  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:45.979  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:45.979  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:13:45.979  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 18:13:45.979  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:45.979  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:13:45.979  1019  1130 E WifiHW  : supplicant_name : p2p_supplicant
09-12 18:13:45.979  1019  1127 V NetworkStats: performPollLocked() took 3ms
09-12 18:13:45.979  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:45.979  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:45.979  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:45.979  1019  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 18:13:45.979  1019  1130 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,09-12 18:13:45.989  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-12 18:13:45.999  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:45.999  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:45.999  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:45.999  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:45.999  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:45.999  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:45.999  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:45.999  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:45.999  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:45.999  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:45.999  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-12 18:13:45.999  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 18:13:45.999  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:45.999  1181  1181 D HotspotTile: onReceive : 2, 0
,09-12 18:13:46.029  7625  7625 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 18:13:46.029  7625  7625 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 18:13:46.029  7625  7625 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 18:13:46.059  7625  7625 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-12 18:13:46.059   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7625
09-12 18:13:46.059   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,09-12 18:13:46.059  7625  7625 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-12 18:13:46.059  7625  7625 I wpa_supplicant: ssSupport state is = 1
09-12 18:13:46.059  7625  7625 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 18:13:46.059  7625  7625 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-12 18:13:46.059   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7625
09-12 18:13:46.059   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-12 18:13:46.109  1019  1523 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:46.109  1019  1523 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:13:46.109  1019  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:46.109  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 18:13:46.149  7581  7581 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-12 18:13:46.169  7581  7581 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 5496-5499)
,09-12 18:13:46.179  7581  7581 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-12 18:13:46.209  7581  7581 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dc58741}
,09-12 18:13:46.209  7581  7581 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-12 18:13:46.209  7581  7581 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 18:13:46.229  7581  7581 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-12 18:13:46.229  7581  7581 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:13:46.239  7581  7581 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 18:13:46.239   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-12 18:13:46.249  7581  7581 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-12 18:13:46.249  7581  7581 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 18:13:46.249  7581  7581 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 18:13:46.249  7581  7581 I Adreno-EGL: Local Branch: 
09-12 18:13:46.249  7581  7581 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 18:13:46.249  7581  7581 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 18:13:46.249  7581  7581 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 18:13:46.249  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-12 18:13:46.299  7625  7625 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 18:13:46.299  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 18:13:46.309  7581  7581 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 18:13:46.319  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-12 18:13:46.319   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7625
09-12 18:13:46.319   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 18:13:46.319  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-12 18:13:46.319  7625  7625 I wpa_supplicant: ssSupport state is = 1
09-12 18:13:46.319  7625  7625 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 18:13:46.319  7625  7625 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:46.319  7625  7625 E wpa_supplicant: SIM READ ERROR
09-12 18:13:46.319  7625  7625 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:13:46.319  7625  7625 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:46.319  7625  7625 E wpa_supplicant: SIM READ ERROR
09-12 18:13:46.319  7625  7625 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:46.319  7625  7625 I wpa_supplicant: wpa_default_ap_write_once
09-12 18:13:46.319  7625  7625 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:13:46.319  7625  7625 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:13:46.319  7625  7625 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 18:13:46.319  7625  7625 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:13:46.319  7625  7625 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-12 18:13:46.319  7625  7625 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:13:46.319  7581  7641 W cr.media: Requires BLUETOOTH permission
,09-12 18:13:46.329  7581  7581 I NSApplication: Starting up...
,09-12 18:13:46.329  1019  1563 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
09-12 18:13:46.329  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:46.329  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:13:46.329  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:46.329  1019  1138 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 18:13:46.339  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-12 18:13:46.339  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:46.339  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:46.339  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:46.339  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:46.349  7647  7647 E Zygote  : MountEmulatedStorage(),
09-12 18:13:46.349  7647  7647 E Zygote  : v2
09-12 18:13:46.349  7647  7647 I libpersona: KNOX_SDCARD checking this for 10117
09-12 18:13:46.349  7647  7647 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:46.349  1019  1316 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7647 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:46.359  7647  7647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 18:13:46.359  1019  1316 I ActivityManager: Killing 7263:com.android.providers.calendar/u0a37 (adj 15): empty #21
09-12 18:13:46.359  7647  7647 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:46.369  7647  7647 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:13:46.369  7625  7625 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-12 18:13:46.379   322   322 I art     : Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 731us total 28.129ms
,09-12 18:13:46.399  7647  7647 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:46.399  7647  7647 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:46.399   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 682us total 22.250ms
,09-12 18:13:46.419  7647  7647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:13:46.419   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.273ms
,09-12 18:13:46.459  7625  7625 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:13:46.459  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 18:13:46.469  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-12 18:13:46.469   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7625
09-12 18:13:46.469   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 18:13:46.469  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-12 18:13:46.469  7625  7625 I wpa_supplicant: ssSupport state is = 1
,09-12 18:13:46.469  7625  7625 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 18:13:46.469  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 18:13:46.489  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-12 18:13:46.489   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7625
09-12 18:13:46.489   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 18:13:46.489  7625  7625 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-12 18:13:46.489  7625  7625 I wpa_supplicant: ssSupport state is = 1
09-12 18:13:46.489  7625  7625 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 18:13:46.489  7625  7625 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:46.489  7625  7625 E wpa_supplicant: SIM READ ERROR
,09-12 18:13:46.489  7625  7625 I wpa_supplicant: wpa_default_ap_write_once
09-12 18:13:46.489  7625  7625 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:13:46.489  7625  7625 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-12 18:13:46.489  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.489  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:13:46.489  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.489  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:46.489  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:13:46.489  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.539  7625  7625 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-12 18:13:46.539  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 18:13:46.599  7625  7625 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 18:13:46.599  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-12 18:13:46.599  7625  7625 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 18:13:46.679   294   294 E SMD     : DCD OFF
,09-12 18:13:46.699  1019  1316 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:13:46.699  1019  1316 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-12 18:13:46.699  1019  1316 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 18:13:46.699  1019  1316 D BatteryService: stay LED for charging
09-12 18:13:46.699  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:13:46.699  1019  1019 I MotionRecognitionService: Plugged
,09-12 18:13:46.699  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false,
,09-12 18:13:46.709  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 18:13:46.709  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
09-12 18:13:46.709  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 18:13:46.709  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-12 18:13:46.729  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:46.729  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:46.729  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-12 18:13:46.729  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-12 18:13:46.729  1181  1181 D SViewCoverView: level :100 plugged : 2
,09-12 18:13:46.739   344   344 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:46.799  1019  1514 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast,
,09-12 18:13:46.799  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:46.799  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:46.799  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 18:13:46.799  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:46.819  7670  7670 E Zygote  : MountEmulatedStorage(),
09-12 18:13:46.819  7670  7670 E Zygote  : v2
09-12 18:13:46.819  7670  7670 I libpersona: KNOX_SDCARD checking this for 10121
09-12 18:13:46.819  7670  7670 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:46.819  7670  7670 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:46.819  7670  7670 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:46.819  7670  7670 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:13:46.819  1019  1514 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7670 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-12 18:13:46.829  1019  1514 I ActivityManager: Killing 7228:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-12 18:13:46.849  7670  7670 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:46.849  7670  7670 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:46.859  7670  7670 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:13:46.859  7670  7670 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 18:13:46.859  7670  7670 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 18:13:46.879  7670  7670 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:46.879  7670  7670 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-12 18:13:46.879  7670  7670 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-12 18:13:46.879  1019  1562 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-12 18:13:46.879  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:46.889  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:46.889  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:46.889  1019  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:46.899  7687  7687 E Zygote  : MountEmulatedStorage()
,09-12 18:13:46.899  1019  1562 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7687 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-12 18:13:46.899  7687  7687 E Zygote  : v2,
09-12 18:13:46.899  7687  7687 I libpersona: KNOX_SDCARD checking this for 10141
09-12 18:13:46.899  7687  7687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:46.899  7687  7687 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:46.899  7687  7687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:46.899  1019  1562 I ActivityManager: Killing 7243:com.android.calendar/u0a131 (adj 15): empty #21
09-12 18:13:46.899  7687  7687 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:46.919  7687  7687 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:46.919  7687  7687 D ActivityThread: Added TimaKeyStore provider,
,09-12 18:13:46.939  7687  7687 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-12 18:13:46.939  7687  7687 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:46.939  7687  7687 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:46.939  7687  7687 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 18:13:46.959  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.959  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:13:46.959  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.989  1019  1032 D RCPManagerService: exchangeData() failure , invalid userId,
09-12 18:13:46.989  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-12 18:13:46.989  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-12 18:13:46.989  7625  7625 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 18:13:46.989  7625  7625 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 18:13:46.989  7625  7625 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:46.989  7625  7625 E wpa_supplicant: SIM READ ERROR
09-12 18:13:46.989  7625  7625 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:46.999  1019  1138 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:47.019  7625  7625 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-12 18:13:47.029  7625  7625 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 18:13:47.029  1019  6909 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:47.029  1019  1130 D WifiConfigStore: Loading config and enabling all networks 
,09-12 18:13:47.029  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:47.029  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:47.029  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:47.029  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:47.029  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:47.029  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.039  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.039  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:47.039  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-12 18:13:47.039  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:47.039  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:47.039  1181  1181 D HotspotTile: onReceive : 3, 0
,09-12 18:13:47.039  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:47.039  1019  1130 E WifiConfigStore: Not a HS20
,09-12 18:13:47.039  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:47.039  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:47.049  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:47.049  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:47.049  1019  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
09-12 18:13:47.049  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:47.049  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:47.049  1019  1523 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:47.049  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:47.049  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:47.049  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 18:13:47.049  7625  7625 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 18:13:47.049  7625  7625 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 18:13:47.049  7625  7625 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 18:13:47.049  7625  7625 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 18:13:47.049  7625  7625 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 18:13:47.049  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 18:13:47.049  7625  7625 I wpa_supplicant: First Scan Start
09-12 18:13:47.049  7625  7625 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 18:13:47.059  1019  1130 D WifiNative-wlan0: Setting external_sim to 1
,09-12 18:13:47.059  1019  1130 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:13:47.059  1019  1130 I WifiNative-HAL: startHal
09-12 18:13:47.059  1019  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9e80588c
09-12 18:13:47.059  1019  1130 I WifiNative-HAL: Could not start hal
,09-12 18:13:47.059  1019  1130 E WifiNative-wlan0: do suspend true
,09-12 18:13:47.059  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-12 18:13:47.059  1019  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-12 18:13:47.059   277   978 D CommandListener: Setting iface cfg
09-12 18:13:47.059   277   978 D CommandListener: Trying to bring up p2p0
,09-12 18:13:47.059  1019  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 18:13:47.059  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 18:13:47.059  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:13:47.059  1019  1130 E WifiNative-wlan0: invaild command id : 215
,09-12 18:13:47.059  1019  1129 D WifiP2pService: P2pEnablingState
09-12 18:13:47.059  1019  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 18:13:47.059  1019  1129 D WifiP2pService: P2p socket connection successful
,09-12 18:13:47.069  1019  1129 D WifiP2pService: P2pEnabledState
,09-12 18:13:47.069  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 18:13:47.069  1019  1132 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:47.069  7625  7625 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 18:13:47.069  7625  7625 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 18:13:47.069  7625  7625 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
,09-12 18:13:47.069  1019  1130 E WifiStateMachine: Failed to set frequency band 0
09-12 18:13:47.069  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:13:47.069  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:47.079  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress
,09-12 18:13:47.079  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-12 18:13:47.079  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:13:47.079  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:47.079  1019  1129 D WifiP2pService: DeviceAddress: 0a:75:42
,09-12 18:13:47.099  1019  1129 D WifiP2pService: sending p2p persistent groups changed broadcast,
09-12 18:13:47.099  7625  7625 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 18:13:47.099  1019  1129 D WifiP2pService: InactiveState
,09-12 18:13:47.099  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
09-12 18:13:47.099  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:13:47.099  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
09-12 18:13:47.099  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:13:47.109  1019  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-12 18:13:47.109  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.109  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:47.109  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.109  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.119  7714  7714 E Zygote  : MountEmulatedStorage(),
09-12 18:13:47.119  7714  7714 E Zygote  : v2
09-12 18:13:47.119  7714  7714 I libpersona: KNOX_SDCARD checking this for 10068
09-12 18:13:47.119  7714  7714 I libpersona: KNOX_SDCARD not a persona,
,09-12 18:13:47.119  1019  1031 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7714 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-12 18:13:47.129  7714  7714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:13:47.119  1019  1032 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:47.129  7714  7714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:47.129  7714  7714 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 18:13:47.129  1019  1563 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:47.139  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 18:13:47.139  7369  7369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:47.139  1019  1019 D RttService: SCAN_AVAILABLE : 3
09-12 18:13:47.139  1019  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:47.139  1019  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:13:47.139  1019  1154 I WifiNative-HAL: startHal
09-12 18:13:47.139  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9d6c79bc
09-12 18:13:47.139  1019  1154 I WifiNative-HAL: Could not start hal
09-12 18:13:47.139  1019  1154 E WifiScanningService: could not start HAL
,09-12 18:13:47.139  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:13:47.139  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 18:13:47.139  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:47.139  1019  1049 D WifiDisplayController: disconnect
09-12 18:13:47.139  1019  1049 D WifiDisplayController: updateConnection
09-12 18:13:47.139  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:47.139  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:47.149  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:13:47.149  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:47.149  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:47.149  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 18:13:47.149  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  secondary type: null
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  wps: 0
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  grpcapab: 0
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  devcapab: 0
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  status: 3
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  wfdInfo: null
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  groupownerAddress: null
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  GOdeviceName: null
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  interfaceAddress: 
09-12 18:13:47.149  1019  1049 D WifiDisplayController:  SConnectInfo : null
,09-12 18:13:47.149  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 18:13:47.149  1019  1562 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:47.149  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 18:13:47.159  7714  7714 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:47.159  7714  7714 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:47.169  1019  3813 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:47.169  1019  6909 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-12 18:13:47.179  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.179  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.179  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:47.179  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.189  7714  7714 D BadgeProvider: onCreate,
09-12 18:13:47.189  7730  7730 I libpersona: KNOX_SDCARD checking this for 10009
09-12 18:13:47.189  7714  7714 D BadgeProvider: DatabaseHelper
09-12 18:13:47.189  7730  7730 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:47.189  7730  7730 E Zygote  : MountEmulatedStorage()
09-12 18:13:47.189  7730  7730 E Zygote  : v2
09-12 18:13:47.189  7730  7730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:47.189  1019  6909 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7730 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-12 18:13:47.189  1019  6909 I ActivityManager: Killing 6976:com.android.vending/u0a26 (adj 15): empty #21
,09-12 18:13:47.199  7730  7730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:47.199  1019  6909 I ActivityManager: Killing 7184:com.android.defcontainer/u0a3 (adj 15): empty #22
,09-12 18:13:47.199  7730  7730 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 18:13:47.229  7730  7730 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:47.229  7730  7730 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:47.289  1019  3813 I ActivityManager: Killing 7394:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-12 18:13:47.299  1019  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:47.299  1019  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:47.299  1019  1550 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:47.299  1019  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:47.299  1019  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:47.299  1543  1543 I Hs20UtilService: Starting #12
,09-12 18:13:47.309  1543  1608 I Hs20UtilService: Message received 5011
,09-12 18:13:47.309  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:13:47.309  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:47.309  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:47.309  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:47.319  1019  1514 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:47.319  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:47.319  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:47.319  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:47.319  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:47.319  1543  1543 I Hs20UtilService: Starting #13
,09-12 18:13:47.329  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:13:47.329  1543  1608 I Hs20UtilService: Message received 5011
,09-12 18:13:47.329  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:47.329  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:47.329  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:47.329  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-12 18:13:47.329  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:13:47.329  1019  1130 E WifiNative-wlan0: invaild command id : 215
,09-12 18:13:47.339  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:13:47.339  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:47.339  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:47.339  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 18:13:47.339  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-12 18:13:47.339  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:47.339  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:47.349  1019  1514 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 18:13:47.349  1019  1514 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
09-12 18:13:47.349  1019  1514 W BroadcastQueue: android.os.TransactionTooLargeException
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-12 18:13:47.349  1019  1514 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 18:13:47.349  1019  1514 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 18:13:47.359  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.359  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.359  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:47.359  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:47.359  1019  1031 I art     : Explicit concurrent mark sweep GC freed 73819(4MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.739ms total 164.306ms
,09-12 18:13:47.369  7747  7747 E Zygote  : MountEmulatedStorage()
09-12 18:13:47.369  7747  7747 E Zygote  : v2
09-12 18:13:47.369  7747  7747 I libpersona: KNOX_SDCARD checking this for 10064
09-12 18:13:47.369  7747  7747 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:47.379  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:47.379  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:47.379  1019  1514 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7747 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:13:47.379  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:47.379  7714  7728 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-12 18:13:47.379  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-12 18:13:47.379  1019  1138 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-12 18:13:47.389  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-12 18:13:47.389  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-12 18:13:47.399  7714  7728 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-12 18:13:47.399  7714  7728 D BadgeProvider: sendNotify, [notify] : null
09-12 18:13:47.399  7714  7728 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-12 18:13:47.399  7714  7728 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 18:13:47.399  7714  7728 D BadgeProvider: update, [UpdateCount] : 1
,09-12 18:13:47.399  1506  1506 D Launcher.Model: reloadBadges entered.
,09-12 18:13:47.399  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:47.409  7747  7747 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:47.419  7747  7747 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 18:13:47.429  7747  7747 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:47.429  7747  7747 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 18:13:47.429  1019  1043 W libprocessgroup: failed to open /acct/uid_10064/pid_7394/cgroup.procs: No such file or directory
,09-12 18:13:47.459  7747  7747 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:13:47.459  7409  7409 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:47.459  1019  1031 I ActivityManager: Killing 7306:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-12 18:13:47.749   344   344 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:48.329  7625  7625 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
,09-12 18:13:48.329  7625  7625 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-12 18:13:48.329  1019  7704 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-12 18:13:48.329  7625  7625 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-12 18:13:48.329  7625  7625 I wpa_supplicant: Trying to associate with  'G700'
,09-12 18:13:48.329  7625  7625 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-12 18:13:48.329  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-12 18:13:48.349  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:13:48.349  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:48.459  7625  7625 E wpa_supplicant: Cmd 35605 not handled
,09-12 18:13:48.459  7625  7625 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 18:13:48.459  7625  7625 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-12 18:13:48.459  7625  7625 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-12 18:13:48.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:48.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:13:48.459  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 18:13:48.459  7625  7625 I wpa_supplicant: Associated with F4.99.3E
,09-12 18:13:48.459  7625  7625 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 18:13:48.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:13:48.459  7625  7625 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 18:13:48.459  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-12 18:13:48.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:48.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:48.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:48.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:48.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:48.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:48.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
,09-12 18:13:48.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
09-12 18:13:48.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-12 18:13:48.459  1019  1133 E Tethering: No numeric data
,09-12 18:13:48.459  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 18:13:48.459  1019  1133 D Tethering: clearTetheredNotification()
,09-12 18:13:48.459  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:13:48.459  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:48.459  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-12 18:13:48.459  1181  1181 D HotspotTile: updateTetherState():false, false
,09-12 18:13:48.459  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 18:13:48.459  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:13:48.459  7625  7625 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 18:13:48.459  7625  7625 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 18:13:48.469  7625  7625 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-12 18:13:48.469  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-12 18:13:48.469  7625  7625 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:13:48.469  7625  7625 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
,09-12 18:13:48.469  7625  7625 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-12 18:13:48.469  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 18:13:48.469  7625  7625 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 18:13:48.469  1019  1127 V NetworkStats: performPollLocked() took 8ms
,09-12 18:13:48.469  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 18:13:48.469  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 18:13:48.469  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
09-12 18:13:48.469  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:13:48.469  1019  1130 D SecContentProvider2: mCursor = null
09-12 18:13:48.469  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:48.469  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:48.469  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:48.479  1019  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 18:13:48.479  1019  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 18:13:48.479  1019  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 18:13:48.479  1019  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 18:13:48.479  1019  1132 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:48.479  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 18:13:48.489  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:13:48.489  1019  1561 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-12 18:13:48.489  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 18:13:48.489  1019  1561 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:13:48.489  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:48.489  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,09-12 18:13:48.489  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:13:48.489  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:48.489  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:48.489  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.499  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.499  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-12 18:13:48.499  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.499  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,09-12 18:13:48.499  1543  1543 I Hs20UtilService: Starting #14
09-12 18:13:48.499  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 18:13:48.499  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 18:13:48.499  1543  1608 I Hs20UtilService: Message received 5007
09-12 18:13:48.499  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:48.499  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:48.499  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:13:48.499  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:48.509  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:13:48.519   277   978 D CommandListener: Setting iface cfg,
09-12 18:13:48.519  1019  1130 E WifiStateMachine: Start Dhcp Watchdog 2
,09-12 18:13:48.519  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-12 18:13:48.519  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:48.529  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:13:48.529  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:48.539  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:48.539  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:13:48.539  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 18:13:48.539  1019  1130 E WifiNative-wlan0: do suspend false
,09-12 18:13:48.539  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.539  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:13:48.539  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:48.539  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,09-12 18:13:48.549  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
09-12 18:13:48.549  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.549  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.549  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.569  1019  1563 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 18:13:48.569  1019  1563 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:48.569  1019  1563 D SecContentProvider2: mCursor = null
,09-12 18:13:48.569  1019  1563 D WifiService: setWifiEnabled: false pid=6812, uid=10170
,09-12 18:13:48.569  1019  1563 D SettingsProvider: name = wifi_on
,09-12 18:13:48.569  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-12 18:13:48.579  1019  1130 E WifiNative-wlan0: do suspend true,
,09-12 18:13:48.609  1019  1129 D WifiP2pService: InactiveState{ what=143375 },
,09-12 18:13:48.609  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 18:13:48.609   277   978 D CommandListener: Clearing all IP addresses on wlan0,
09-12 18:13:48.609  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:13:48.609  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 18:13:48.609  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:48.609  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.609  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.609  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.609  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.609  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
09-12 18:13:48.609  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:13:48.609  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-12 18:13:48.609  1019  1132 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:48.609   277   978 E Netd    : no such netId 503
,09-12 18:13:48.619  1019  1132 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-12 18:13:48.619  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 18:13:48.619  1019  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-12 18:13:48.619  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:48.619  1019  1132 V NetworkStats: updateIfacesLocked()
09-12 18:13:48.619  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:48.619  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:13:48.619  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:13:48.619  1019  1132 V NetworkStats: performPollLocked() took 5ms
09-12 18:13:48.619  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:48.629  1019  1129 D WifiP2pService: InactiveState{ what=131204 }
,09-12 18:13:48.629  1019  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 18:13:48.629  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
,09-12 18:13:48.629  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:48.629  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-12 18:13:48.629  1019  1019 D RttService: SCAN_AVAILABLE : 1
09-12 18:13:48.629  1019  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:13:48.629  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:48.629  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:13:48.629  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:48.629  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:48.629  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 18:13:48.629  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:48.629  1019  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 18:13:48.629  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:48.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.639  1019  1398 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:48.639  1019  1398 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:48.639  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:48.639  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:48.639  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:48.639  1543  1543 I Hs20UtilService: Starting #15
09-12 18:13:48.639  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 18:13:48.639  1019  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-12 18:13:48.639  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:48.639  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:48.639  1543  1608 I Hs20UtilService: Message received 5007
09-12 18:13:48.639  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:13:48.639  1019  1132 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 18:13:48.639  1019  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 18:13:48.639  1019  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,09-12 18:13:48.639  1019  7763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:48.639  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:13:48.639  1019  1132 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:48.639  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 18:13:48.639  1019  7763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 18:13:48.639  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:48.639  1019  1049 D WifiDisplayController: disconnect
09-12 18:13:48.639  1019  1049 D WifiDisplayController: updateConnection
09-12 18:13:48.639  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:48.639  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:48.649  1019  1129 D WifiP2pService: P2pDisablingState
,09-12 18:13:48.649  1019  1129 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 18:13:48.649  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:13:48.649  1019  1129 D WifiP2pService: p2p socket connection lost
,09-12 18:13:48.649  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:48.649  1019  1129 D WifiP2pService: P2pDisabledState
09-12 18:13:48.649  1019  1130 E WifiNative-wlan0: do suspend true
,09-12 18:13:48.649  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:48.649  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:48.649  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 18:13:48.649  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:48.649  1019  1562 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:48.649  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-12 18:13:48.649  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:48.649  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:48.659  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 18:13:48.659  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:48.659  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:48.659  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 18:13:48.659  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:13:48.659  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:48.659  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:48.659  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 18:13:48.659  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:48.659  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:48.669  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:48.669  7747  7747 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:48.669  7747  7747 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 18:13:48.669  7747  7747 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:13:48.669  7409  7409 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:48.679  1019  1129 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-12 18:13:48.679  1019  1129 D WifiP2pService: DefaultState{ what=143375 }
,09-12 18:13:48.689   277   978 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:48.689  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 18:13:48.689  7625  7625 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:13:48.689  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:48.689  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:48.689  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:48.689  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.689  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.689  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.689  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.699  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:48.699  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:13:48.699  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 18:13:48.699  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.699  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.699  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.709  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.709  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:13:48.709  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:13:48.709  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:48.709  1019  1138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:48.719  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:48.719  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:48.719  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:48.719  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:48.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.719  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.719  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:48.719  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 18:13:48.719  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:48.719  1181  1181 D HotspotTile: onReceive : 0, 0
,09-12 18:13:48.719  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 18:13:48.719  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:48.719  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:48.719  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:48.719  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:48.719  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:48.719  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:48.719  1543  1543 I Hs20UtilService: Starting #16
09-12 18:13:48.719  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:48.719  1543  1608 I Hs20UtilService: Message received 5007
,09-12 18:13:48.729  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:48.729  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:48.729  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:13:48.729  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:48.729  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:48.729  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:48.729  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:48.729  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 18:13:48.729  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:48.729  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:48.729  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:48.739  1019  1138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:48.739  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:48.739  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:48.739  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:48.739  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:48.749  1543  1543 I Hs20UtilService: Starting #17
09-12 18:13:48.749   344   344 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:48.749  1543  1608 I Hs20UtilService: Message received 5011
,09-12 18:13:48.749  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:48.749  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:48.749  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 18:13:48.749  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:48.759  7766  7766 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 18:13:48.759  7766  7766 I dhcpcd  : version 5.5.6 starting
,09-12 18:13:48.759  7766  7766 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 18:13:48.809  7766  7766 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-12 18:13:48.809  7766  7766 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-12 18:13:48.809  7766  7766 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-12 18:13:48.809  7766  7766 I dhcpcd  : bssid match
,09-12 18:13:48.809  7766  7766 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-12 18:13:48.819  7625  7625 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:48.859  7766  7766 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-12 18:13:48.909  7625  7625 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-12 18:13:48.909  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:48.909  1019  1046 D Tethering: interfaceStatusChanged p2p0, false,
09-12 18:13:48.909  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,09-12 18:13:48.939  7625  7625 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-12 18:13:48.939  7625  7625 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 18:13:48.939  7625  7625 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 18:13:48.939  7625  7625 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 18:13:48.939  7625  7625 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:13:48.939  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:48.939  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:13:48.939  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:13:48.939  1019  1133 D Tethering: InitialState.processMessage what=4
,09-12 18:13:48.939  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 18:13:48.939  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:48.949  1019  1133 E Tethering: No numeric data
,09-12 18:13:48.949  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:48.949  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:13:48.949  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:48.949  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:13:48.949  1181  1181 D HotspotTile: updateTetherState():false, false
,09-12 18:13:48.949  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-12 18:13:48.949  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:48.949  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:13:48.959  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:48.959  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:48.959  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:48.959  1019  1127 V NetworkStats: performPollLocked() took 8ms
09-12 18:13:48.959  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:48.959  1019  1133 D Tethering: clearTetheredNotification()
,09-12 18:13:48.959  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 18:13:48.959  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:48.969  7766  7766 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-12 18:13:48.969  5951  5951 D FactoryTest: Not factory mode
09-12 18:13:48.969  5951  5951 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-12 18:13:48.979  5951  5951 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-12 18:13:48.979  5951  5951 D MTPRx   : still no open session command from host, so toast
,09-12 18:13:48.979  5951  5951 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-12 18:13:48.979  5951  5951 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-12 18:13:48.979  5951  5951 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118306
09-12 18:13:48.979  1019  1523 E PersonaManagerService: inState():  stateMachine is null !!
09-12 18:13:48.979  1019  1523 I PersonaManagerService: PersonaId don't exist
09-12 18:13:48.979  1019  1523 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-12 18:13:48.989  1019  1523 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 18:13:48.989  1019  1523 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:48.989  1019  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:48.989  1019  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-12 18:13:48.999  1019  1523 W ActivityManager: mDVFSHelper.acquire()
,09-12 18:13:49.029  1019  1523 D PersonaManager: isKioskContainerExistOnDevice,
,09-12 18:13:49.029  1019  1523 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 18:13:49.029  1019  1523 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
09-12 18:13:49.029  1019  1523 D InputDispatcher: Focused application set to: xxxx
09-12 18:13:49.029  1019  1523 D InputDispatcher: Focus left window: 6812
,09-12 18:13:49.039  5951  5951 E MTPRx   : started activity for popup
,09-12 18:13:49.039  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 18:13:49.039  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:13:49.069  5951  5951 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-12 18:13:49.069  5951  5951 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-12 18:13:49.069  5951  5951 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:13:49.069  5951  5951 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
09-12 18:13:49.069  5951  5951 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:49.069  5951  5951 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 18:13:49.109  5951  5951 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-12 18:13:49.119  1019  1562 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-12 18:13:49.119  1019  1562 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 18:13:49.119  1019  1562 D InputDispatcher: Focused application set to: xxxx,
09-12 18:13:49.129  1019  1562 D InputDispatcher: Focus entered window: 6812
,09-12 18:13:49.129  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 18:13:49.129  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:13:49.129  1019  1523 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,09-12 18:13:49.129  1019  1523 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@340bfd38 attribute=null, token = android.os.BinderProxy@f30216a
,09-12 18:13:49.159  5951  5951 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,09-12 18:13:49.169  7625  7625 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:49.169  5951  5951 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-12 18:13:49.169  5951  5951 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-12 18:13:49.189  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 18:13:49.189  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-12 18:13:49.189  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 18:13:49.189  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-12 18:13:49.199  1019  3816 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 18:13:49.199  1019  3816 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 18:13:49.199  1019  3816 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-12 18:13:49.199  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 18:13:49.199  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 18:13:49.209  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 18:13:49.209  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 18:13:49.219  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@37f10f57 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@bef140d, 16908290=android.view.AbsSavedState$1@bef140d}, android:focusedViewId=100}]}]
09-12 18:13:49.219  6812  6812 V ActivityThread: updateVisibility : ActivityRecord{2eb24461 token=android.os.BinderProxy@1806046b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-12 18:13:49.219  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 18:13:49.219  6812  6812 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 18:13:49.219  6812  6812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 18:13:49.219  6812  6812 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1806046b time:118541
,09-12 18:13:49.219  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:49.219  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:49.219  7625  7625 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 18:13:49.219  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:49.229  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 18:13:49.229  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:49.229  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-12 18:13:49.229  1019  1563 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:13:49.329  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 18:13:49.329  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 18:13:49.329  7369  7369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:49.339  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:49.339  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:13:49.339  1685  2071 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:49.339  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:49.339  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:49.339  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:49.339  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:49.339  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:49.339  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:49.339  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:49.339  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:49.339  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-12 18:13:49.339  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:49.339  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:49.339  1181  1181 D HotspotTile: onReceive : 1, 0
,09-12 18:13:49.349  1019  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:49.349  1019  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:49.349  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:49.349  1019  1550 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:49.349  1019  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:49.349  1019  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:49.349  1543  1543 I Hs20UtilService: Starting #18
,09-12 18:13:49.349  1543  1608 I Hs20UtilService: Message received 5011
,09-12 18:13:49.359  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:49.359  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 18:13:49.359  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 18:13:49.359  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:49.679   294   294 E SMD     : DCD OFF
,09-12 18:13:49.749   344   344 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-12 18:13:50.019   277   972 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-12 18:13:50.029  1019  1046 D Tethering: interfaceRemoved wlan0
,09-12 18:13:50.029  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 18:13:50.229  1019  1046 D Tethering: interfaceRemoved p2p0
,09-12 18:13:50.229  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 18:13:50.399  1019  1097 V AlarmManager: waitForAlarm result :4
,09-12 18:13:50.409   277   974 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-12 18:13:50.409   277   974 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-12 18:13:50.419  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:50.419  1019  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.419  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-12 18:13:51.059  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 18:13:51.579  6812  7131 D BluetoothAdapter: enable()
,09-12 18:13:51.579  1019  1561 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:13:51.579  1019  1561 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 18:13:51.579  1019  1561 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:13:51.579  1019  1561 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 18:13:51.579  1019  1561 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-12 18:13:51.579  1019  1561 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-12 18:13:51.579  1019  1561 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-12 18:13:51.579  1019  1561 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:13:51.579  1019  1561 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 18:13:51.579  1019  1561 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:51.579  1019  1561 D SettingsProvider: name = bluetooth_on,
,09-12 18:13:51.579  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:51.579  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:51.579  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 18:13:51.589  3278  3355 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
09-12 18:13:51.589  1019  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.589  3278  3355 D BluetoothAdapterProperties: Setting state to 11
09-12 18:13:51.589  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 18:13:51.589  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 18:13:51.589  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:51.589  3278  3355 D BluetoothAdapterService: updateAdapterState state is 11
09-12 18:13:51.589  3278  3355 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:51.589  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-12 18:13:51.589  3278  3355 D BtConfig.SecureMode: isSecureModeOn:false
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: processStart(): removed Client ,profile: com.android.bluetooth.hid.HidDevService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-12 18:13:51.589  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.589  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.589  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 18:13:51.589  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 18:13:51.589  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:51.599  3278  3278 D HeadsetService: Received start request. Starting profile...
09-12 18:13:51.599  3278  3278 D HeadsetService: start()
09-12 18:13:51.599  3278  3278 D HeadsetStateMachine: make
,09-12 18:13:51.599  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-12 18:13:51.599  1019  1019 I InputMethodManagerService: [BT Setting State] State =11,
,09-12 18:13:51.599  3278  3278 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 18:13:51.609  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:13:51.609  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:51.609  1181  1181 D BluetoothTile:  getBluetoothState : 11
,09-12 18:13:51.609  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
09-12 18:13:51.609  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:51.609  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 18:13:51.609  2020  2020 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:13:51.609  1019  1398 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:51.609  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:51.609  1019  3813 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.609  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.619  1019  1316 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:51.619  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:51.619  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:51.619  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.619  1019  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.619  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.619  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:51.619  1019  1032 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 18:13:51.619  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-12 18:13:51.619  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-12 18:13:51.619  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 18:13:51.619  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:13:51.619  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.619  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.619  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:13:51.619  1019  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.619  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.629  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.629  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.629  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.629  1019  1398 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 18:13:51.629  1019  1398 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.629  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-12 18:13:51.629  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 18:13:51.629  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 18:13:51.629  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.629  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.629  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:13:51.629  3278  3278 I bluedroid: get_profile_interface handsfree
,09-12 18:13:51.629  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.629  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.639  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.639  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.639  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.639  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-12 18:13:51.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:13:51.639  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 18:13:51.639  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:51.639  1019  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.639  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.649  1019  1563 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:13:51.649  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.649  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.649  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 18:13:51.649  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:51.649  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:51.649  1019  3816 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.649  3278  3278 E DualScoManager: Dual Sco Manager already instantiated
09-12 18:13:51.649  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-12 18:13:51.649  3278  3278 I DualScoManager: Set HeadsetServiceHelper
09-12 18:13:51.649  3278  3278 D BluetoothAtMessage: createCMTIContentObservers
,09-12 18:13:51.649  1019  6909 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-12 18:13:51.649  1019  6909 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:51.649  1019  6909 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:13:51.649  1019  6909 D SettingsProvider: selectionArgs: false
09-12 18:13:51.649  1019  6909 D SettingsProvider: selectionArgs: 1002
,09-12 18:13:51.649  1019  6909 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:51.649  1019  6909 D SettingsProvider: ret = -1
,09-12 18:13:51.649  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.649  1019  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.649  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.659  3278  7799 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-12 18:13:51.659  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-12 18:13:51.659  3278  3278 D HeadsetService: mStartError = false
09-12 18:13:51.659  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:51.659  3278  3278 D A2dpService: Received start request. Starting profile...
09-12 18:13:51.659  3278  3278 D A2dpService: start()
09-12 18:13:51.659  3278  3278 I bluedroid: get_profile_interface avrcp
,09-12 18:13:51.659  1019  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.659  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.659  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.659  1019  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.659  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
09-12 18:13:51.659  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:51.659  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.659  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.659  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:13:51.659  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:13:51.659  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 18:13:51.659  3278  3355 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 18:13:51.669  3278  7799 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-12 18:13:51.669  3278  7799 D HeadsetStateMachine: map size, before remove : 0
09-12 18:13:51.669  3278  7799 D HeadsetStateMachine: map size, after remove: 0
,09-12 18:13:51.669  3278  3278 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 18:13:51.669  3278  3278 D Avrcp   : Initialize Media Controller
09-12 18:13:51.669  3278  3278 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-12 18:13:51.669  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:51.669  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 18:13:51.669  1019  3816 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-12 18:13:51.679  3278  3278 E Avrcp   : getActiveSessions
09-12 18:13:51.679  3278  3278 D Avrcp   : pick active media Controller
09-12 18:13:51.679  3278  3278 D Avrcp   : Get the active Media Controller 
,09-12 18:13:51.679  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:51.679  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:51.679  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:51.679  1019  3816 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:51.689  1019  3816 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7801 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-12 18:13:51.689  7801  7801 E Zygote  : MountEmulatedStorage(),
09-12 18:13:51.689  7801  7801 I libpersona: KNOX_SDCARD checking this for 10055
09-12 18:13:51.689  7801  7801 E Zygote  : v2
09-12 18:13:51.689  7801  7801 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:51.689  7801  7801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:51.699  3278  3278 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 18:13:51.699  3278  7800 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-12 18:13:51.699  3278  3278 D A2dpStateMachine: make
09-12 18:13:51.699  3278  3278 I bluedroid: get_profile_interface a2dp
09-12 18:13:51.699  7801  7801 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:13:51.699  3278  7808 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-12 18:13:51.699  7801  7801 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:51.699  3278  3278 E bt-btif : warning : media task started media_task_refcnt 1 ,
09-12 18:13:51.709  3278  3278 D A2dpService: mStartError = false
,09-12 18:13:51.709  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:51.709  3278  3278 D HeadsetStateMachine: Try to query the phonestate on bind
09-12 18:13:51.709  1456  1481 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 18:13:51.709  3278  7807 D A2dpStateMachine: Enter Disconnected: -2,
09-12 18:13:51.709  1456  1456 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-12 18:13:51.709  1456  1456 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-12 18:13:51.709  3278  3278 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-12 18:13:51.709  1456  1481 I Telecom : BluetoothPhoneService: Result of Message : true
09-12 18:13:51.709  3278  7799 D HeadsetStateMachine: Disconnected process message: 11
09-12 18:13:51.709  3278  3278 D HeadsetStateMachine: Proxy object connected
,09-12 18:13:51.709  3278  3278 D HidService: Received start request. Starting profile...
09-12 18:13:51.709  3278  3278 D HidService: start()
09-12 18:13:51.709  3278  3278 I bluedroid: get_profile_interface hidhost
09-12 18:13:51.709  3278  3278 D HidService: setHidService(): set to: null
09-12 18:13:51.709  3278  3278 D HidService: mStartError = false
09-12 18:13:51.709  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:51.709  3278  3278 D HealthService: Received start request. Starting profile...
09-12 18:13:51.709  3278  3278 D HealthService: start()
,09-12 18:13:51.709  3278  7800 D BluetoothMediaBrowser: no now playing list
09-12 18:13:51.709  3278  7800 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 18:13:51.719  3278  3278 I bluedroid: get_profile_interface health
09-12 18:13:51.719  3278  3278 D HealthService: mStartError = false
09-12 18:13:51.719  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:51.719  3278  3278 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 18:13:51.719  3278  7799 D HeadsetStateMachine: Disconnected process message: 18
09-12 18:13:51.719  3278  3278 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-12 18:13:51.719  3278  3278 D PanService: Received start request. Starting profile...
09-12 18:13:51.719  3278  3278 D PanService: start()
09-12 18:13:51.719  3278  3278 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 18:13:51.719  3278  3278 I bluedroid: get_profile_interface pan
09-12 18:13:51.719  3278  3278 D PanService: mStartError = false
09-12 18:13:51.719  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:51.719  3278  3278 D BluetoothMapService: Received start request. Starting profile...
09-12 18:13:51.719  3278  3278 D BluetoothMapService: start()
,09-12 18:13:51.719  3278  3278 D BluetoothMapService: mStartError = false
09-12 18:13:51.719  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:51.719  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 18:13:51.719  3278  3278 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 18:13:51.719  3278  7799 D HeadsetStateMachine: Disconnected process message: 10
09-12 18:13:51.719  3278  7799 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 18:13:51.719  3278  7799 D HeadsetStateMachine: Disconnected process message: 11
09-12 18:13:51.719  3278  3278 D SapService: Received start request. Starting profile...
09-12 18:13:51.719  3278  3278 D SapService: start()
09-12 18:13:51.719  3278  3278 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 18:13:51.719  3278  3278 I bluedroid: get_profile_interface sap
09-12 18:13:51.719  3278  3278 D SapService: mStartError = false
09-12 18:13:51.719  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:13:51.719  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 18:13:51.719  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-12 18:13:51.719  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 18:13:51.719  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 18:13:51.729  7801  7801 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:51.729  7801  7801 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:51.739  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 18:13:51.739  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 18:13:51.739  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 18:13:51.739  3278  3355 I bluedroid: enable
,09-12 18:13:51.739  3278  3358 E bt-btif : Calling BTA_HhEnable
,09-12 18:13:51.749  3278  3358 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0017
09-12 18:13:51.749  3278  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-12 18:13:51.749  3278  3358 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 18:13:51.749  3278  3358 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-12 18:13:51.749  3278  3358 E BluetoothServiceJni: populateRssiValuesNative
09-12 18:13:51.749  3278  3358 I bluedroid: getModelRssiValues
09-12 18:13:51.749  3278  3358 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 18:13:51.749  3278  3358 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 18:13:51.749  1019  1019 D SettingsProvider: name = bluetooth_name
,09-12 18:13:51.749  3278  3358 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-12 18:13:51.749  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:51.749  3278  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:13:51.749  3278  3358 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:13:51.749  3278  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 18:13:51.749  3278  3358 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-12 18:13:51.749  3278  3358 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-12 18:13:51.749  3278  3358 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-12 18:13:51.749  3278  3358 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 18:13:51.749  3278  3358 E bt-btif : JVenable fails
,09-12 18:13:51.759  3278  3358 D bte_conf: Device ID record 1 : primary
09-12 18:13:51.759  3278  3358 D bte_conf:   vendorId            = 0075
09-12 18:13:51.759  3278  3358 D bte_conf:   vendorIdSource      = 0001
09-12 18:13:51.759  3278  3358 D bte_conf:   product             = 0100
09-12 18:13:51.759  3278  3358 D bte_conf:   version             = 0200
09-12 18:13:51.759  3278  3358 D bte_conf:   clientExecutableURL = 
09-12 18:13:51.759  3278  3358 D bte_conf:   serviceDescription  = 
09-12 18:13:51.759  3278  3358 D bte_conf:   documentationURL    = 
09-12 18:13:51.759  3278  3358 D bte_conf: bte_load_did_conf no section named DID2.
,09-12 18:13:51.759  3278  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-12 18:13:51.759  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 18:13:51.759  3278  3355 D BluetoothAdapterProperties: ScanMode =  20
,09-12 18:13:51.759  3278  3355 D BluetoothAdapterProperties: State =  11
09-12 18:13:51.759  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:51.759  3278  3358 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 18:13:51.759  1019  1398 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 18:13:51.759  7801  7801 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-12 18:13:51.759  3278  3355 D BluetoothAdapterProperties: Setting state to 12
09-12 18:13:51.759  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 18:13:51.759  1019  1138 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-12 18:13:51.759  1019  1138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:51.759  1019  1138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:51.759  1019  1138 D SettingsProvider: selectionArgs: false
09-12 18:13:51.759  1019  1138 D SettingsProvider: selectionArgs: 1002
09-12 18:13:51.759  1019  1138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:51.759  1019  1138 D SettingsProvider: ret = -1
09-12 18:13:51.759  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:51.759  3278  3355 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 18:13:51.759  1019  1316 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.759  1019  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.769  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.769  1019  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.769  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.769  3278  3355 D BluetoothAdapterService: Autoconnection is available 
,09-12 18:13:51.769  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 18:13:51.769  3278  3355 D BluetoothAdapterService: starting service from this receiver
,09-12 18:13:51.769  3278  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:13:51.769  3278  3358 D BluetoothAdapterProperties: Scan Mode:21
09-12 18:13:51.769  3278  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:13:51.769  1019  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:51.769  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.769  3278  3278 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-12 18:13:51.769  3278  3278 I BluetoothPbapService: Handler(): got msg=1
,09-12 18:13:51.779  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.779  1019  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.779  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.779  1019  3813 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-12 18:13:51.779  3278  3355 I BluetoothAdapterState: Entering On State from state = 11
,09-12 18:13:51.779  1456  1477 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.779  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:13:51.779  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.779  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.779  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.779  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:51.779  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:51.789  1456  1477 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.789  4893  4905 D Bluetoothsap: onBluetoothStateChange: up=true
09-12 18:13:51.789  4893  4905 D Bluetoothsap: Binding service...
,09-12 18:13:51.789  3278  7822 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-12 18:13:51.789  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:51.789  4893  4905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 18:13:51.789  3278  7822 D BluetoothSocket: bindListen(): myUserId = 0
09-12 18:13:51.789  3278  7822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:13:51.789  7801  7801 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-12 18:13:51.799  3278  7822 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-12 18:13:51.799  3278  7822 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:13:51.799  3278  7822 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:13:51.799  3278  7822 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31fc7a82
,09-12 18:13:51.799  7801  7801 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 18:13:51.799  7801  7801 D UserAnalysis: Create SecureDbHelper
09-12 18:13:51.799  3278  7822 D BluetoothSocket: channel: 19
09-12 18:13:51.799  3278  7822 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:51.799  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:51.799  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 18:13:51.799  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.799  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.799  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.799  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.799  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:51.799  4893  4905 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 18:13:51.799  7801  7801 D IntelligenceServiceApplication: onCreate()
,09-12 18:13:51.799  4893  4901 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:13:51.809  4893  4901 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.809  4893  4893 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-12 18:13:51.809  4893  4893 D SapProfile: Bluetooth service connected
09-12 18:13:51.809  4893  4893 D Bluetoothsap: getConnectedDevices()
,09-12 18:13:51.809  1019  6909 I ActivityManager: Killing 7327:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-12 18:13:51.809  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:13:51.809  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.809  7801  7801 D IntelligenceServiceApplication: no applications having user consent for prediction
09-12 18:13:51.809  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.809  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.809  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.819  4893  4893 D BluetoothA2dp: Proxy object connected
09-12 18:13:51.819  4893  4893 D A2dpProfile: Bluetooth service connected
,09-12 18:13:51.819  1482  2482 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.819  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:13:51.819  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.819  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.819  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.819  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.819  1482  2482 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.819  4893  4905 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 18:13:51.829  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 18:13:51.829  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 18:13:51.829  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.829  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.829  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-12 18:13:51.829  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.829  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.829  4893  4893 D BluetoothPbap: Proxy object connected
09-12 18:13:51.829  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:13:51.829  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.829  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:13:51.829  4893  4893 D PbapServerProfile: Bluetooth service connected
09-12 18:13:51.829  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.829  1181  2216 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.829  1019  1019 D BluetoothA2dp: Proxy object connected
,09-12 18:13:51.829  1181  2216 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.829  1707  4489 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.829  1707  4489 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.829  1482  1679 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.829  1482  1679 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.829  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.829  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:13:51.829  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 18:13:51.829  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.829  1469  1496 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.829  1469  1496 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.829  4893  5001 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.829  4893  5001 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.839  4893  4901 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 18:13:51.839  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-12 18:13:51.839  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.839  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.839  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.839  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.839  4893  4893 D BluetoothInputDevice: Proxy object connected
09-12 18:13:51.839  4893  4893 D HidProfile: Bluetooth service connected
,09-12 18:13:51.839  6812  6820 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:13:51.839  6812  6820 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.839  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.839  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.839  1685  1693 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.839  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 18:13:51.839  1685  1693 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.839  1456  1477 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.839  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:13:51.839  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.839  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.839  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.839  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.849  1456  1477 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.849  1456  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.849  1456  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.849  4893  5001 D BluetoothPan: Binding service...
,09-12 18:13:51.849  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan,
,09-12 18:13:51.849  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 18:13:51.849  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.849  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 18:13:51.849  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.849  4893  4901 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 18:13:51.849  4893  4893 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:13:51.849  4893  4893 D PanProfile: Bluetooth service connected
,09-12 18:13:51.849  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-12 18:13:51.849  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.859  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.859  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.859  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.859  1019  1048 D BluetoothPan: Binding service...
,09-12 18:13:51.859  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 18:13:51.859  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 18:13:51.859  1019  1048 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 18:13:51.859  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 18:13:51.859  4893  4893 D BluetoothMap: Proxy object connected
,09-12 18:13:51.859  4893  4893 D MapProfile: Bluetooth service connected
09-12 18:13:51.859  4893  4893 D BluetoothMap: getConnectedDevices()
,09-12 18:13:51.869  1019  1048 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #21
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: android.os.TransactionTooLargeException
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 18:13:51.869  1019  1048 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-12 18:13:51.869  4893  4905 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.869  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:13:51.869  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.869  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.869  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.869  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.869  4893  4905 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 18:13:51.869  3278  3398 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.869  3278  3398 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.869  4893  4893 D HeadsetProfile: Bluetooth service connected
09-12 18:13:51.869  3278  3293 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:13:51.879  3278  3293 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.879  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:13:51.879  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.879  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.879  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.879  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.879  3278  3278 D BluetoothA2dp: Proxy object connected
09-12 18:13:51.879  3278  3278 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-12 18:13:51.879  1456  1477 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.879  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:13:51.879  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 18:13:51.879  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.879  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.879  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.879  1456  1477 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.889  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 18:13:51.889  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 18:13:51.889  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:51.889  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
09-12 18:13:51.889  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 18:13:51.889  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:13:51.899  1456  1456 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1865260c, true
,09-12 18:13:51.899  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:51.899  1456  1456 D BluetoothHeadset: registerMessageListener
,09-12 18:13:51.899  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:51.899  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 18:13:51.899  2020  2020 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 18:13:51.899  1181  1181 D BluetoothTile:  getBluetoothState : 12
,09-12 18:13:51.899  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
,09-12 18:13:51.909  3278  3397 D HeadsetService: registerMessageListener
,09-12 18:13:51.909  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:51.909  3278  3397 D HeadsetService: registerMessageListener
09-12 18:13:51.909  3278  7799 D HeadsetStateMachine: Disconnected process message: 70
,09-12 18:13:51.909  1456  1456 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-12 18:13:51.909  3278  7799 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@385ff593
09-12 18:13:51.909  1456  1456 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 18:13:51.909  4893  4893 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-12 18:13:51.909  4893  4893 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 18:13:51.909  4893  4893 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 18:13:51.909  4893  4893 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 18:13:51.909  1019  3813 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:51.909  1019  3816 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 18:13:51.909  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
09-12 18:13:51.909  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:51.919  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 18:13:51.919  1456  1456 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 18:13:51.919  1456  1456 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-12 18:13:51.919  1456  1456 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 18:13:51.919  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:51.919  3278  7825 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 18:13:51.919  3278  7799 D HeadsetStateMachine: Disconnected process message: 9
,09-12 18:13:51.919  3278  7799 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 18:13:51.919  3278  7825 D BluetoothSocket: bindListen(): myUserId = 0
09-12 18:13:51.919  3278  7825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:13:51.919   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 18:13:51.919   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 18:13:51.919   282   282 V voice   : voice_set_parameters: exit with code(-2)
09-12 18:13:51.919   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 18:13:51.919   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 18:13:51.919   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 18:13:51.919   282   282 V audio_hw_primary: adev_set_parameters: exit
09-12 18:13:51.919  3278  7799 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-12 18:13:51.919  3278  7825 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-12 18:13:51.919  3278  7825 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:13:51.919  3278  7825 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:13:51.919  3278  7825 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6089d0
09-12 18:13:51.919  3278  7825 D BluetoothSocket: channel: 5
,09-12 18:13:51.929  4893  4893 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:51.929  1019  1398 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 18:13:51.929  1019  1398 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.929  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.929  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.929  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:51.939  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:51.949  4893  4893 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:51.949  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:51.949  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:51.949  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 18:13:51.959  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:51.959  3278  3278 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 18:13:51.959  1019  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:51.959  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.959  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.959  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.959  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.969  1019  3813 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-12 18:13:51.969  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:51.969  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:51.969  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:51.969  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:51.989  7828  7828 E Zygote  : MountEmulatedStorage()
09-12 18:13:51.989  7828  7828 E Zygote  : v2
09-12 18:13:51.989  7828  7828 I libpersona: KNOX_SDCARD checking this for 10105
09-12 18:13:51.989  7828  7828 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:51.989  7828  7828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:13:51.989  1019  3813 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7828 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-12 18:13:51.989  7828  7828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:13:51.989  1019  1563 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 18:13:51.989  7828  7828 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:13:51.999  3278  7836 D BluetoothSocket: bindListen(): myUserId = 0
09-12 18:13:51.999  3278  7836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:13:51.999  3278  7836 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
09-12 18:13:51.999  3278  7836 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:13:51.999  3278  7836 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:13:51.999  3278  7836 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c0c72fc
09-12 18:13:51.999  3278  7836 D BluetoothSocket: channel: 12
09-12 18:13:51.999  3278  7836 I BtOppRfcommListener: Accept thread started.
,09-12 18:13:51.999  1019  1044 W ActivityManager: mDVFSHelper.release()
,09-12 18:13:52.009  7828  7828 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:52.009  7828  7828 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:52.119   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 18:13:52.119   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:52.119  7828  7850 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 18:13:52.119   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 18:13:52.119   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:52.119  7828  7850 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.k.d(PG:583)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:52.279  7828  7828 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:52.279  7828  7828 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:52.289  1019  3816 I ActivityManager: Killing 7442:com.sec.pcw.device/1000 (adj 15): empty #21
09-12 18:13:52.299  1019  3428 D SSRM:n  : SIOP:: AP = 380
,09-12 18:13:52.339  7828  7859 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 18:13:52.369  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:52.369  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:52.369  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:52.369  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 18:13:52.679   294   294 E SMD     : DCD OFF,
,09-12 18:13:54.419  1019  3441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 18:13:54.599  6812  7131 D BluetoothAdapter: disable()
,09-12 18:13:54.599  1019  1550 D SettingsProvider: name = bluetooth_on
,09-12 18:13:54.599  3278  3355 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 18:13:54.599  3278  3355 D BluetoothAdapterProperties: Setting state to 13,
09-12 18:13:54.599  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:13:54.599  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:54.599  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:54.599  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-12 18:13:54.599  3278  3355 D BluetoothAdapterService: updateAdapterState state is 13
09-12 18:13:54.599  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.599  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.599  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:54.609  3278  3278 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-12 18:13:54.609  3278  3278 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@273ded85, channel: 19, state: LISTENING
,09-12 18:13:54.609  3278  3278 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@273ded85, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31fc7a82, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d9ad7damSocket: android.net.LocalSocket@54e840b impl:android.net.LocalSocketImpl@1a2bc2e8 fd:FileDescriptor[80]
09-12 18:13:54.609  3278  3278 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@54e840b impl:android.net.LocalSocketImpl@1a2bc2e8 fd:FileDescriptor[80]
,09-12 18:13:54.609  3278  3355 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:54.609  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-12 18:13:54.609  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 18:13:54.609  3278  3355 D BluetoothAdapterService: terminating service from this receiver
09-12 18:13:54.609  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.609  1019  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:54.609  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:54.609  3278  3355 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 18:13:54.609  3278  3355 D BluetoothAdapterProperties: mDiscovering is false
,09-12 18:13:54.609  1019  1523 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 18:13:54.609  3278  3355 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 18:13:54.619  4893  4893 D BluetoothPbap: Proxy object disconnected
09-12 18:13:54.619  4893  4893 D PbapServerProfile: Bluetooth service disconnected
,09-12 18:13:54.629  3278  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:13:54.629  3278  3358 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:13:54.629  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 18:13:54.629  3278  3355 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-12 18:13:54.629  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:54.629  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:54.629  3278  3355 E bt-btif : cmd socket is not created
,09-12 18:13:54.629  3278  3360 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-12 18:13:54.639  3278  7836 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 18:13:54.639  3278  3355 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 18:13:54.639  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:54.639  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:54.639  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:54.639  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:54.649  6812  6812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:54.649  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:54.649  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.649  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-12 18:13:54.659  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:13:54.669  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 18:13:54.669  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:54.669  3278  3360 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 18:13:54.669  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:54.669  3278  3360 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:54.669  3278  3360 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 18:13:54.669  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:13:54.669  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:54.669  1181  1181 D BluetoothTile:  getBluetoothState : 13
,09-12 18:13:54.669  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:54.669  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:54.669  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:54.679  2020  2020 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:13:54.679  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.679  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 18:13:54.679  1019  1398 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:54.679  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:54.679  3278  3278 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9de97a6, channel: 5, state: LISTENING
,09-12 18:13:54.679  3278  3278 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9de97a6, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6089d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@365f55e7mSocket: android.net.LocalSocket@a6e2594 impl:android.net.LocalSocketImpl@24d1483d fd:FileDescriptor[82]
,09-12 18:13:54.679  3278  3278 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a6e2594 impl:android.net.LocalSocketImpl@24d1483d fd:FileDescriptor[82]
,09-12 18:13:54.679  3278  3278 I BtOppRfcommListener: stopping Accept Thread
,09-12 18:13:54.679  3278  3278 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d4c8832, channel: 12, state: LISTENING
,09-12 18:13:54.679  3278  3278 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d4c8832, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c0c72fc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c16983mSocket: android.net.LocalSocket@25d20700 impl:android.net.LocalSocketImpl@28f2b39 fd:FileDescriptor[86]
09-12 18:13:54.689  3278  3278 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25d20700 impl:android.net.LocalSocketImpl@28f2b39 fd:FileDescriptor[86]
,09-12 18:13:54.689  3278  7836 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 18:13:54.689  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:54.689  3278  3278 V BluetoothOppManager: cleanUp...
,09-12 18:13:54.689  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:54.689  4893  4893 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:54.689  1019  1561 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 18:13:54.689  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.699  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:54.699  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:54.699  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:54.699  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:54.709  4893  4893 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:54.709  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:54.709  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:54.709  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 18:13:54.759   344   344 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:54.839  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 18:13:54.839  3278  3355 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 18:13:54.839  3278  3355 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-12 18:13:54.839  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,09-12 18:13:54.839  3278  3355 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-12 18:13:54.839  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:54.849  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:54.849  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:54.849  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-12 18:13:54.849  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
,09-12 18:13:54.849  1019  1032 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:13:54.849  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.849  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-12 18:13:54.849  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
,09-12 18:13:54.849  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 18:13:54.849  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService,
,09-12 18:13:54.849  1019  3813 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:54.849  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.859  3278  3278 D HeadsetService: Received stop request...Stopping profile...
,09-12 18:13:54.859  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:54.859  1019  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:54.859  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:54.859  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:54.859  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 18:13:54.859  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-12 18:13:54.859  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:54.859  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:13:54.869  4893  4893 D HeadsetProfile: Bluetooth service disconnected
09-12 18:13:54.869  1019  6909 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:54.869  1019  6909 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.869  1019  6909 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.869  1019  6909 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.869  1019  6909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:54.869  3278  3278 D A2dpService: Received stop request...Stopping profile...
09-12 18:13:54.869  3278  7807 D A2dpStateMachine: Exit Disconnected: -1
,09-12 18:13:54.869  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-12 18:13:54.869  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 18:13:54.869  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-12 18:13:54.869  1019  1398 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:54.869  1019  1398 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.869  1019  1398 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.869  1019  1398 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.869  1019  1398 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:54.869  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 18:13:54.869  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:13:54.869  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-12 18:13:54.869  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:54.869  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.879  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.879  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.879  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:54.879  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:54.879  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 18:13:54.879  1019  3813 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:54.879  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:54.879  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-12 18:13:54.879  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:54.879  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.879  1019  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.879  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:54.879  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:54.879  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-12 18:13:54.879  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 18:13:54.879  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:13:54.879  3278  3355 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 18:13:54.879  1019  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:54.879  4893  4893 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:54.879  4893  4893 D A2dpProfile: Bluetooth service disconnected
,09-12 18:13:54.879  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.879  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.879  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.879  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:54.879  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:54.889  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:54.889  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:54.889  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:54.889  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:54.889  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:54.889  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:13:54.889  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:54.889  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:13:54.889  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:13:54.889  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:13:54.889  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 18:13:54.889  3278  3355 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 18:13:54.889  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 18:13:54.889  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:54.889  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 18:13:54.889  3278  3278 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 18:13:54.889  3278  3278 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 18:13:54.889  3278  3278 D HidService: Received stop request...Stopping profile...
,09-12 18:13:54.889  3278  3278 D HidService: Stopping Bluetooth HidService
,09-12 18:13:54.889  3278  3278 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 18:13:54.889  3278  3278 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-12 18:13:54.889  3278  3278 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 18:13:54.889  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:54.899  3278  3278 D HealthService: Received stop request...Stopping profile...
09-12 18:13:54.899  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:54.899  4893  4893 D BluetoothInputDevice: Proxy object disconnected
09-12 18:13:54.899  4893  4893 D HidProfile: Bluetooth service disconnected
,09-12 18:13:54.899  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-12 18:13:54.899  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 18:13:54.899  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 18:13:54.899  3278  3278 D BluetoothA2dp: Proxy object disconnected
,09-12 18:13:54.899  3278  3278 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-12 18:13:54.899  3278  3278 D PanService: Received stop request...Stopping profile...
,09-12 18:13:54.899  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:54.899  3278  7808 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-12 18:13:54.899  3278  3278 I GKI_LINUX: GKI_exit_task 2 done
09-12 18:13:54.899  3278  3278 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 18:13:54.909  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 18:13:54.909  4893  4893 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:13:54.909  4893  4893 D PanProfile: Bluetooth service disconnected
,09-12 18:13:54.909  3278  3278 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 18:13:54.909  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:54.909  3278  3278 D SapService: Received stop request...Stopping profile...
,09-12 18:13:54.909  3278  3278 D SapService: Stopping Bluetooth SapService
,09-12 18:13:54.909  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:13:54.909  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-12 18:13:54.909  4893  4893 D BluetoothMap: Proxy object disconnected
09-12 18:13:54.909  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 18:13:54.919  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:54.919  4893  4893 D MapProfile: Bluetooth service disconnected
,09-12 18:13:54.919  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 18:13:54.919  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:54.919  3278  3278 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:13:54.919  4893  4893 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 18:13:54.919  3278  3278 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-12 18:13:54.919  4893  4893 D SapProfile: Bluetooth service disconnected
09-12 18:13:54.919  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 18:13:54.919  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:54.919  3278  3278 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:13:54.919  3278  3278 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 18:13:54.919  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-12 18:13:54.919  3278  3278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-12 18:13:54.919  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-12 18:13:54.919  3278  3278 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-12 18:13:54.919  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-12 18:13:54.919  3278  3355 D BluetoothAdapterProperties: Setting state to 10
09-12 18:13:54.919  3278  3278 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 18:13:54.919  3278  3278 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 18:13:54.919  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 18:13:54.919  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 18:13:54.919  3278  3355 D BluetoothAdapterService: updateAdapterState state is 10
09-12 18:13:54.929  3278  3355 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:54.929  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 18:13:54.929  3278  3355 I BluetoothAdapterState: Entering OffState
,09-12 18:13:54.929  4893  4905 D Bluetoothsap: onBluetoothStateChange: up=false
09-12 18:13:54.929  4893  4905 D Bluetoothsap: Unbinding service...
,09-12 18:13:54.929  4893  5001 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:54.929  4893  4901 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 18:13:54.929  7828  7842 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.929  7828  7842 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.929  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:54.929  1181  1775 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:54.929  1181  1775 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.929  1707  5858 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.929  1707  5858 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.929  1482  2482 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.929  1482  2482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.939  1469  1496 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.939  1469  1496 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:54.939  4893  4905 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.939  4893  4905 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:54.939  4893  5001 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 18:13:54.939  6812  6820 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.939  6812  6820 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.939  6812  6820 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 18:13:54.939  6812  6820 D BluetoothLeAdvertiser: Exit stop advertising
,09-12 18:13:54.939  6812  6820 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 18:13:54.939  6812  6820 D BluetoothLeScanner: Exiting stopAllScan
,09-12 18:13:54.939  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.939  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.939  1685  1703 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.939  1685  1703 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.939  1456  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.949  1456  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.949  4893  4905 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 18:13:54.949  3278  3293 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:54.949  3278  3293 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:54.949  3278  7348 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:54.949  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.949  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
,09-12 18:13:54.949  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 18:13:54.959  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:13:54.959  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.959  1181  1181 D BluetoothTile:  getBluetoothState : 10
,09-12 18:13:54.959  1019  1138 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:54.959  1019  3816 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:54.969  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:54.969  2020  2020 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0,
,09-12 18:13:54.969  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.969  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:54.969  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:54.969  4893  4893 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:54.979  1019  1514 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 18:13:54.979  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.979  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:54.979  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.979  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:54.979  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:54.989  4893  4893 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:54.989  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:54.989  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.989  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 18:13:55.679   294   294 E SMD     : DCD OFF
,09-12 18:13:55.749   344   344 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:56.749   344   344 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:56.769  1019  1523 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:13:56.769  1019  1523 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4306, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-12 18:13:56.769  1019  1523 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-12 18:13:56.769  1019  1523 D BatteryService: stay LED for charging
09-12 18:13:56.769  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:13:56.769  1019  1019 I MotionRecognitionService: Plugged
,09-12 18:13:56.769  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 18:13:56.779  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 18:13:56.779  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 18:13:56.779  1442  1442 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 18:13:56.779  1442  1442 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,09-12 18:13:56.809  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:56.809  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:56.809  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-12 18:13:56.809  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-12 18:13:56.809  1181  1181 D SViewCoverView: level :100 plugged : 2
,09-12 18:13:57.609  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:57.609  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:57.749   344   344 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:58.689   294   294 E SMD     : DCD OFF
,09-12 18:13:58.749   344   344 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:59.749   344   344 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-12 18:13:59.989  1019  1097 V AlarmManager: waitForAlarm result :8
,09-12 18:14:00.609  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:00.609  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bf5afc2 added. We now have 6 listener(s)
09-12 18:14:00.609  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,09-12 18:14:00.609  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-12 18:14:00.609  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@153521d3 added. We now have 7 listener(s)
,09-12 18:14:00.609  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:00.609  6812  7131 I System.out: IsBluetoothEnabled,
,09-12 18:14:00.609  6812  7131 D BluetoothAdapter: disable(),
,09-12 18:14:00.609  1019  1562 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-12 18:14:00.619  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:00.619  6812  7131 D BluetoothAdapter: enable()
,09-12 18:14:00.619  1019  1032 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:14:00.619  1019  1032 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 18:14:00.619  1019  1032 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:14:00.619  1019  1032 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 18:14:00.619  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-12 18:14:00.619  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-12 18:14:00.619  1019  1032 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-12 18:14:00.619  1019  1032 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:14:00.619  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 18:14:00.619  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:14:00.619  1019  1032 D SettingsProvider: name = bluetooth_on
,09-12 18:14:00.629  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 18:14:00.629  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:14:00.639  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 18:14:00.639  3278  3355 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 18:14:00.639  3278  3355 D BluetoothAdapterProperties: Setting state to 11
09-12 18:14:00.639  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-12 18:14:00.639  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:14:00.639  3278  3355 D BluetoothAdapterService: updateAdapterState state is 11
09-12 18:14:00.639  3278  3355 D BluetoothAdapterService: Autoconnection is available 
09-12 18:14:00.639  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-12 18:14:00.639  3278  3355 D BtConfig.SecureMode: isSecureModeOn:false
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-12 18:14:00.639  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 18:14:00.,639  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
09-12 18:14:00.639  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 18:14:00.639  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 18:14:00.649  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:14:00.649  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:00.649  1181  1181 D BluetoothTile:  getBluetoothState : 11
,09-12 18:14:00.649  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
09-12 18:14:00.649  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 18:14:00.659  2020  2020 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:14:00.659  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:00.659  1019  1138 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 18:14:00.659  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-12 18:14:00.659  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:14:00.659  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:00.659  1019  3816 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.659  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.659  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.669  1019  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.669  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.669  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-12 18:14:00.669  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 18:14:00.669  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 18:14:00.669  1019  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.669  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.669  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.669  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.669  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.679  3278  3278 D HeadsetService: Received start request. Starting profile...
,09-12 18:14:00.679  3278  3278 D HeadsetService: start()
09-12 18:14:00.679  3278  3278 D HeadsetStateMachine: make
,09-12 18:14:00.679  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:14:00.679  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-12 18:14:00.679  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:14:00.679  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:14:00.679  1019  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.679  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.679  3278  3278 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 18:14:00.679  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.679  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.679  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.689  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-12 18:14:00.689  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 18:14:00.689  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 18:14:00.689  1019  3813 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 18:14:00.689  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.689  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.689  1019  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.689  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:14:00.699  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:14:00.699  1019  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.699  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.699  1019  1562 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.699  1019  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.699  1019  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.699  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 18:14:00.699  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:14:00.699  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 18:14:00.699  1019  6909 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 18:14:00.699  1019  6909 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.699  1019  6909 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.699  1019  6909 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.699  1019  6909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:14:00.699  3278  3278 I bluedroid: get_profile_interface handsfree
,09-12 18:14:00.699  1019  3816 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.699  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.709  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.709  1019  3816 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.709  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.709  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 18:14:00.709  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:14:00.709  3278  3355 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:14:00.709  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:00.709  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 18:14:00.709  1019  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.709  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.709  3278  3278 E DualScoManager: Dual Sco Manager already instantiated
09-12 18:14:00.709  3278  3278 I DualScoManager: Set HeadsetServiceHelper
09-12 18:14:00.709  3278  3278 D BluetoothAtMessage: createCMTIContentObservers
,09-12 18:14:00.719  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.719  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:00.719  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-12 18:14:00.719  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 18:14:00.719  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.719  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.719  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.719  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.719  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.719  1019  1316 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-12 18:14:00.719  1019  1316 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.719  1019  1316 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.719  1019  1316 D SettingsProvider: selectionArgs: false
09-12 18:14:00.719  1019  1316 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.719  1019  1316 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.719  1019  1316 D SettingsProvider: ret = -1
,09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.719  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.719  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.719  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:14:00.719  3278  3355 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:14:00.719  3278  3355 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 18:14:00.719  3278  3355 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-12 18:14:00.719  3278  7874 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 18:14:00.729  3278  3278 D HeadsetService: mStartError = false
09-12 18:14:00.729  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:14:00.729  3278  3278 D A2dpService: Received start request. Starting profile...
,09-12 18:14:00.729  3278  3278 D A2dpService: start()
09-12 18:14:00.729  3278  3278 I bluedroid: get_profile_interface avrcp
,09-12 18:14:00.729  3278  3278 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 18:14:00.729  3278  3278 D Avrcp   : Initialize Media Controller
09-12 18:14:00.729  3278  3278 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-12 18:14:00.729  3278  3278 E Avrcp   : getActiveSessions
09-12 18:14:00.729  3278  3278 D Avrcp   : pick active media Controller
09-12 18:14:00.729  3278  3278 D Avrcp   : Get the active Media Controller 
,09-12 18:14:00.729  3278  7874 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-12 18:14:00.729  3278  7874 D HeadsetStateMachine: map size, before remove : 0
09-12 18:14:00.739  3278  7874 D HeadsetStateMachine: map size, after remove: 0
,09-12 18:14:00.739  3278  3278 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 18:14:00.739  3278  7875 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 18:14:00.739  3278  3278 D A2dpStateMachine: make
,09-12 18:14:00.749  3278  3278 I bluedroid: get_profile_interface a2dp
,09-12 18:14:00.749  3278  7877 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-12 18:14:00.749  3278  3278 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 18:14:00.749  3278  3278 D A2dpService: mStartError = false
09-12 18:14:00.749  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:14:00.749  3278  3278 D HidService: Received start request. Starting profile...
09-12 18:14:00.749  3278  3278 D HidService: start()
09-12 18:14:00.749  3278  3278 I bluedroid: get_profile_interface hidhost
09-12 18:14:00.749  3278  3278 D HidService: setHidService(): set to: null
09-12 18:14:00.749  3278  3278 D HidService: mStartError = false
09-12 18:14:00.749  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:14:00.749  3278  7876 D A2dpStateMachine: Enter Disconnected: -2
,09-12 18:14:00.749  3278  3278 D HeadsetStateMachine: Try to query the phonestate on bind
09-12 18:14:00.749  1456  7824 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 18:14:00.749  1456  1456 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-12 18:14:00.749  1456  1456 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 18:14:00.749  1456  7824 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 18:14:00.749  3278  3278 D HealthService: Received start request. Starting profile...
09-12 18:14:00.749  3278  3278 D HealthService: start()
,09-12 18:14:00.749  3278  7875 D BluetoothMediaBrowser: no now playing list
09-12 18:14:00.749  3278  7875 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 18:14:00.749  3278  3278 I bluedroid: get_profile_interface health
09-12 18:14:00.749  3278  3278 D HealthService: mStartError = false
09-12 18:14:00.749  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:14:00.749  3278  3278 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-12 18:14:00.759  3278  7874 D HeadsetStateMachine: Disconnected process message: 11
09-12 18:14:00.759  3278  3278 D HeadsetStateMachine: Proxy object connected
,09-12 18:14:00.759  3278  3278 D PanService: Received start request. Starting profile...
,09-12 18:14:00.759  3278  3278 D PanService: start()
09-12 18:14:00.759  3278  3278 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 18:14:00.759  3278  3278 I bluedroid: get_profile_interface pan
09-12 18:14:00.759  3278  3278 D PanService: mStartError = false
,09-12 18:14:00.759  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:14:00.759  3278  3278 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-12 18:14:00.759  3278  3278 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-12 18:14:00.759  3278  7874 D HeadsetStateMachine: Disconnected process message: 18
,09-12 18:14:00.759  3278  3278 D BluetoothMapService: Received start request. Starting profile...
09-12 18:14:00.759  3278  3278 D BluetoothMapService: start()
,09-12 18:14:00.759  3278  3278 D BluetoothMapService: mStartError = false
,09-12 18:14:00.759  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
,09-12 18:14:00.759  3278  3278 D SapService: Received start request. Starting profile...
,09-12 18:14:00.759  3278  3278 D SapService: start()
09-12 18:14:00.759  3278  3278 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 18:14:00.759  3278  3278 I bluedroid: get_profile_interface sap
09-12 18:14:00.759  3278  3278 D SapService: mStartError = false
09-12 18:14:00.759  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:14:00.759  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 18:14:00.759  3278  3278 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 18:14:00.759  3278  7874 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:14:00.759  3278  7874 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 18:14:00.759  3278  7874 D HeadsetStateMachine: Disconnected process message: 11
09-12 18:14:00.759  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 18:14:00.759  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-12 18:14:00.769  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-12 18:14:00.769  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 18:14:00.779  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 18:14:00.779  3278  3278 E BluetoothAdapterService(847376769): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true,
,09-12 18:14:00.779  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 18:14:00.779  3278  3355 I bluedroid: enable
,09-12 18:14:00.789  3278  3358 E bt-btif : Calling BTA_HhEnable
,09-12 18:14:00.789  3278  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-12 18:14:00.789  3278  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-12 18:14:00.789  3278  3358 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 18:14:00.789  3278  3358 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-12 18:14:00.789  3278  3358 E BluetoothServiceJni: populateRssiValuesNative
09-12 18:14:00.789  3278  3358 I bluedroid: getModelRssiValues
,09-12 18:14:00.789  3278  3358 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 18:14:00.789  3278  3358 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 18:14:00.799  1019  1019 D SettingsProvider: name = bluetooth_name
09-12 18:14:00.799  3278  3358 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-12 18:14:00.799  3278  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:14:00.799  3278  3358 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:14:00.799  3278  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 18:14:00.799  3278  3358 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-12 18:14:00.799  3278  3358 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-12 18:14:00.799  3278  3358 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-12 18:14:00.799  3278  3358 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 18:14:00.799  3278  3358 E bt-btif : JVenable fails
,09-12 18:14:00.799  3278  3358 D bte_conf: Device ID record 1 : primary
09-12 18:14:00.799  3278  3358 D bte_conf:   vendorId            = 0075
09-12 18:14:00.799  3278  3358 D bte_conf:   vendorIdSource      = 0001
09-12 18:14:00.799  3278  3358 D bte_conf:   product             = 0100
09-12 18:14:00.799  3278  3358 D bte_conf:   version             = 0200
09-12 18:14:00.799  3278  3358 D bte_conf:   clientExecutableURL = 
09-12 18:14:00.799  3278  3358 D bte_conf:   serviceDescription  = 
09-12 18:14:00.799  3278  3358 D bte_conf:   documentationURL    = 
,09-12 18:14:00.799  3278  3358 D bte_conf: bte_load_did_conf no section named DID2.
09-12 18:14:00.799  3278  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-12 18:14:00.799  3278  3358 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 18:14:00.799  3278  3355 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 18:14:00.799  3278  3355 D BluetoothAdapterProperties: ScanMode =  20
09-12 18:14:00.799  3278  3355 D BluetoothAdapterProperties: State =  11
,09-12 18:14:00.799  1019  6909 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 18:14:00.799  3278  3355 D BluetoothAdapterProperties: Setting state to 12
,09-12 18:14:00.799  3278  3355 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 18:14:00.809  3278  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:14:00.809  3278  3358 D BluetoothAdapterProperties: Scan Mode:21
,09-12 18:14:00.809  3278  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:14:00.809  1019  1031 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 18:14:00.809  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.809  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.809  1019  1031 D SettingsProvider: selectionArgs: false
09-12 18:14:00.809  1019  1031 D SettingsProvider: selectionArgs: 1002
,09-12 18:14:00.809  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.809  1019  1031 D SettingsProvider: ret = -1
,09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:00.809  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:00.809  3278  3355 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 18:14:00.809  3278  3355 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 18:14:00.809  1019  3813 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.809  1019  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
09-12 18:14:00.809  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.809  1019  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.809  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.819  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:00.819  3278  3355 D BluetoothAdapterService: Autoconnection is available 
09-12 18:14:00.819  3278  3355 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 18:14:00.819  3278  3355 D BluetoothAdapterService: starting service from this receiver
,09-12 18:14:00.819  1019  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.819  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.819  3278  3278 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 18:14:00.819  1456  1481 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:00.819  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.819  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.819  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.819  3278  3278 I BluetoothPbapService: Handler(): got msg=1
09-12 18:14:00.819  1019  1316 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-12 18:14:00.819  3278  3355 I BluetoothAdapterState: Entering On State from state = 11
,09-12 18:14:00.829  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:00.829  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:00.829  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:00.829  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.829  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.829  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.839  1456  1481 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:00.839  4893  4901 D Bluetoothsap: onBluetoothStateChange: up=true
09-12 18:14:00.839  4893  4901 D Bluetoothsap: Binding service...
,09-12 18:14:00.839  4893  4901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 18:14:00.839  3278  7882 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-12 18:14:00.849  3278  7882 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 18:14:00.849  3278  7882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:00.849  3278  7882 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-12 18:14:00.849  3278  7882 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:14:00.849  3278  7882 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:14:00.849  3278  7882 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12949351
09-12 18:14:00.849  3278  7882 D BluetoothSocket: channel: 19
09-12 18:14:00.849  3278  7882 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 18:14:00.979  1019  1048 I art     : Explicit concurrent mark sweep GC freed 55441(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.298ms total 141.810ms
09-12 18:14:00.979  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 18:14:00.979  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.979  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.979  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.979  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.979  4893  4901 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 18:14:00.989  4893  5001 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:00.989  4893  4893 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 18:14:00.989  4893  4893 D SapProfile: Bluetooth service connected
09-12 18:14:00.989  4893  4893 D Bluetoothsap: getConnectedDevices()
,09-12 18:14:00.989  4893  5001 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:00.989  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:14:00.989  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.989  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.989  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.989  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.989  4893  4893 D BluetoothA2dp: Proxy object connected
09-12 18:14:00.989  1482  1497 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 18:14:00.989  4893  4893 D A2dpProfile: Bluetooth service connected
,09-12 18:14:00.989  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:00.989  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:00.989  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.989  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.989  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.989  1482  1497 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 18:14:00.989  4893  4905 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 18:14:00.989  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-12 18:14:00.999  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.999  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.999  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.999  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.999  7828  7839 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:00.999  7828  7839 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:00.999  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:14:00.999  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:00.999  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:14:00.999  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 18:14:00.999  4893  4893 D BluetoothPbap: Proxy object connected
09-12 18:14:00.999  4893  4893 D PbapServerProfile: Bluetooth service connected
,09-12 18:14:00.999  1019  1019 D BluetoothA2dp: Proxy object connected
09-12 18:14:00.999  1181  2216 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:00.999  1181  2216 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:00.999  1707  1783 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:00.999  1707  1783 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:00.999  1482  1679 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:00.999  1482  1679 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:00.999  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 18:14:00.999  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:00.999  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 18:14:00.999  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:00.999  1469  1496 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:00.999  1469  1496 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.009  4893  5001 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.009  4893  5001 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.009  4893  4901 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 18:14:01.009  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-12 18:14:01.009  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.009  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.009  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.009  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.009  6812  6824 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.009  6812  6824 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:01.009  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.009  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:01.009  4893  4893 D BluetoothInputDevice: Proxy object connected
09-12 18:14:01.009  1685  1693 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.009  1685  1693 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:01.009  4893  4893 D HidProfile: Bluetooth service connected
,09-12 18:14:01.009  1456  1481 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.019  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.019  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.019  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.019  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.019  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 18:14:01.019  1456  1481 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.019  1456  7824 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.019  1456  7824 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:01.019  4893  4905 D BluetoothPan: Binding service...
,09-12 18:14:01.019  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-12 18:14:01.019  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.019  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.019  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:01.019  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.019  4893  5001 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 18:14:01.019  4893  4893 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:14:01.019  4893  4893 D PanProfile: Bluetooth service connected
,09-12 18:14:01.019  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-12 18:14:01.019  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.019  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.019  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.019  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.019  1019  1048 D BluetoothPan: Binding service...
,09-12 18:14:01.019  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 18:14:01.019  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.029  4893  4901 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.029  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 18:14:01.029  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.029  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.029  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.029  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.029  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-12 18:14:01.029  4893  4901 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.029  3278  3397 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.029  3278  3397 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.029  3278  7348 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:01.029  3278  7348 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.029  4893  4893 D HeadsetProfile: Bluetooth service connected
,09-12 18:14:01.029  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:14:01.029  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.029  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.029  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.029  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.029  3278  3278 D BluetoothA2dp: Proxy object connected
09-12 18:14:01.029  3278  3278 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-12 18:14:01.029  1456  1481 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.029  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.039  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.039  4893  4893 D BluetoothMap: Proxy object connected
09-12 18:14:01.039  4893  4893 D MapProfile: Bluetooth service connected
09-12 18:14:01.039  4893  4893 D BluetoothMap: getConnectedDevices()
09-12 18:14:01.039  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.039  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.039  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.039  1456  1481 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.039  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 18:14:01.039  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 18:14:01.039  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:14:01.039  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,09-12 18:14:01.039  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 18:14:01.039  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:14:01.049  1456  1456 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2df10b55, true
,09-12 18:14:01.049  1456  1456 D BluetoothHeadset: registerMessageListener
,09-12 18:14:01.049  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:14:01.049  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:14:01.049  1181  1181 D BluetoothTile:  getBluetoothState : 12
,09-12 18:14:01.049  4893  4893 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:01.049  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:01.049  2020  2020 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 18:14:01.049  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:14:01.059  3278  3293 D HeadsetService: registerMessageListener
,09-12 18:14:01.059  3278  3293 D HeadsetService: registerMessageListener
09-12 18:14:01.059  3278  7874 D HeadsetStateMachine: Disconnected process message: 70
09-12 18:14:01.059  1456  1456 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-12 18:14:01.059  1456  1456 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-12 18:14:01.059  3278  7874 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2fcb97b6
,09-12 18:14:01.059  3278  7885 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 18:14:01.059  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:14:01.059  1456  1456 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-12 18:14:01.059  1456  1456 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-12 18:14:01.059  1456  1456 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 18:14:01.059  3278  7885 D BluetoothSocket: bindListen(): myUserId = 0
09-12 18:14:01.059  3278  7885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:01.059  1019  1523 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:14:01.059  4893  4893 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-12 18:14:01.059  4893  4893 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 18:14:01.059  4893  4893 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 18:14:01.059  4893  4893 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 18:14:01.059  3278  7885 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-12 18:14:01.059  3278  7885 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:14:01.059  3278  7885 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:14:01.059  3278  7885 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ead3cb7
09-12 18:14:01.069  3278  7874 D HeadsetStateMachine: Disconnected process message: 9
09-12 18:14:01.069  3278  7874 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 18:14:01.069  3278  7885 D BluetoothSocket: channel: 5
,09-12 18:14:01.069  1019  3813 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 18:14:01.069  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:14:01.069  1181  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:14:01.069   282  1017 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 18:14:01.069   282  1017 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 18:14:01.069   282  1017 V voice   : voice_set_parameters: exit with code(-2)
09-12 18:14:01.069   282  1017 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 18:14:01.069   282  1017 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 18:14:01.069   282  1017 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 18:14:01.069   282  1017 V audio_hw_primary: adev_set_parameters: exit
09-12 18:14:01.069  3278  7874 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 18:14:01.069  4893  4893 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:14:01.069  1019  1563 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 18:14:01.069  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.069  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.069  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.069  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:14:01.079  1707  1707 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:14:01.089  4893  4893 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:14:01.089  4893  4893 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:14:01.089  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:01.089  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 18:14:01.099  3278  3278 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3281f181
09-12 18:14:01.099  3278  3278 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 18:14:01.099  1019  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:01.099  1019  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.109  1019  1550 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.109  1019  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.109  1019  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.109  1019  1550 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 18:14:01.119  3278  7890 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 18:14:01.119  3278  7890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:01.129  3278  7890 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
09-12 18:14:01.129  3278  7890 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:14:01.129  3278  7890 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:14:01.129  3278  7890 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f4eed53
,09-12 18:14:01.129  3278  7890 D BluetoothSocket: channel: 12
09-12 18:14:01.129  3278  7890 I BtOppRfcommListener: Accept thread started.
,09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:01.649  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:01.649  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:01.649  1019  1523 D WifiService: setWifiEnabled: false pid=6812, uid=10170
,09-12 18:14:01.649  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:01.649  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@341fe110 added. We now have 8 listener(s)
,09-12 18:14:01.649  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:01.649  1019  1523 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 18:14:01.649  1019  1523 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:14:01.649  1019  1523 D SecContentProvider2: mCursor = null
,09-12 18:14:01.649  1019  1523 D SettingsProvider: name = wifi_on
,09-12 18:14:01.659  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:01.659  1019  1514 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 18:14:01.659  1019  1514 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 18:14:01.659  1019  1514 D SecContentProvider2: mCursor = null
,09-12 18:14:01.659  1019  1514 D WifiService: setWifiEnabled: true pid=6812, uid=10170
,09-12 18:14:01.659  1019  1514 W ActivityManager: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:14:01.659  1019  1514 W WifiService: Failed getting userId using ActivityManagerNative
09-12 18:14:01.659  1019  1514 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6812, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:14:01.659  1019  1514 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 18:14:01.659  1019  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 18:14:01.659  1019  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 18:14:01.659  1019  1514 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 18:14:01.659  1019  1514 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:14:01.669  1019  1514 D SettingsProvider: name = wifi_on
,09-12 18:14:01.669  1019  1130 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 18:14:01.689   294   294 E SMD     : DCD OFF,
,09-12 18:14:02.009  1019  1046 D Tethering: interfaceAdded wlan0
,09-12 18:14:02.009  1019  1133 E Tethering: No numeric data
,09-12 18:14:02.019  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 18:14:02.019  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:02.019  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.019  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:02.019  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:02.019  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:14:02.019  1181  1181 D HotspotTile: updateTetherState():false, false
,09-12 18:14:02.019  1019  1133 D Tethering: clearTetheredNotification()
,09-12 18:14:02.019  1019  1127 V NetworkStats: performPollLocked() took 9ms
,09-12 18:14:02.019  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.029  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.029  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.029  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 18:14:02.029  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:14:02.029  1019  1133 D Tethering: InitialState.processMessage what=4,
09-12 18:14:02.029  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-12 18:14:02.029  1019  1133 E Tethering: No numeric data
,09-12 18:14:02.029  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:14:02.029  1019  1133 D Tethering: clearTetheredNotification()
09-12 18:14:02.039  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:14:02.039  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-12 18:14:02.039  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:14:02.039  1181  1181 D HotspotTile: updateTetherState():false, false
,09-12 18:14:02.039  1019  1046 D Tethering: interfaceAdded p2p0
,09-12 18:14:02.049  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 18:14:02.049  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:02.049  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-12 18:14:02.049  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:02.049  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:14:02.049  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
09-12 18:14:02.049   277   978 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 18:14:02.049   277   978 D SoftapController: Softap fwReload - Ok
,09-12 18:14:02.059  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:02.059  1019  1127 V NetworkStats: performPollLocked() took 17ms
09-12 18:14:02.059   277   978 D CommandListener: Setting iface cfg
09-12 18:14:02.059   277   978 D CommandListener: Trying to bring down wlan0
,09-12 18:14:02.059   277   978 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:14:02.059  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:02.059  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.059  1019  1130 E WifiHW  : supplicant_name : p2p_supplicant
,09-12 18:14:02.069  1019  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-12 18:14:02.079  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:14:02.079  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:14:02.079  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:02.079  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:14:02.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.079  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:14:02.079  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-12 18:14:02.089  1181  1181 D HotspotTile: onReceive : 2, 0
09-12 18:14:02.089  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-12 18:14:02.089  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:14:02.089  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 18:14:02.089  1019  1563 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:14:02.089  1019  1563 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:02.089  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 18:14:02.089  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 18:14:02.089  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:14:02.089  1543  1543 I Hs20UtilService: Starting #19
,09-12 18:14:02.099  1543  1608 I Hs20UtilService: Message received 5011
,09-12 18:14:02.099  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:14:02.099  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:14:02.099  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:14:02.099  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:14:02.109  7902  7902 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-12 18:14:02.119  7902  7902 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 18:14:02.119  7902  7902 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 18:14:02.129  7902  7902 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-12 18:14:02.129   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7902
09-12 18:14:02.129   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 18:14:02.129  7902  7902 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 18:14:02.129  7902  7902 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:02.129  7902  7902 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 18:14:02.129  7902  7902 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 18:14:02.129   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7902
09-12 18:14:02.129   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-12 18:14:02.279   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-12 18:14:02.289  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-12 18:14:02.319  1019  3428 D SSRM:n  : SIOP:: AP = 340
,09-12 18:14:02.329  7902  7902 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 18:14:02.329  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 18:14:02.339  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 18:14:02.339   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7902
09-12 18:14:02.339   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 18:14:02.339  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-12 18:14:02.339  7902  7902 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:02.339  7902  7902 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:14:02.339  7902  7902 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:14:02.339  7902  7902 E wpa_supplicant: SIM READ ERROR,
09-12 18:14:02.339  7902  7902 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:14:02.339  7902  7902 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:14:02.339  7902  7902 E wpa_supplicant: SIM READ ERROR
09-12 18:14:02.339  7902  7902 I wpa_supplicant: Blacklist: Clear (all) ,
09-12 18:14:02.339  7902  7902 I wpa_supplicant: wpa_default_ap_write_once
09-12 18:14:02.339  7902  7902 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:14:02.339  7902  7902 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:14:02.339  7902  7902 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-12 18:14:02.339  7902  7902 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:14:02.339  7902  7902 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 18:14:02.349  7902  7902 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-12 18:14:02.349  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 18:14:02.349  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:14:02.349  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:14:02.509  7902  7902 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-12 18:14:02.639  7902  7902 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:14:02.639  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 18:14:02.649  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-12 18:14:02.649   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7902
09-12 18:14:02.649   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 18:14:02.649  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 18:14:02.649  7902  7902 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:02.649  7902  7902 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 18:14:02.649  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 18:14:02.669  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 18:14:02.669   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7902,
09-12 18:14:02.669   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,09-12 18:14:02.669  7902  7902 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 18:14:02.669  7902  7902 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:02.669  7902  7902 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 18:14:02.669  7902  7902 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:14:02.669  7902  7902 E wpa_supplicant: SIM READ ERROR,
09-12 18:14:02.669  7902  7902 I wpa_supplicant: wpa_default_ap_write_once
09-12 18:14:02.669  7902  7902 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:14:02.669  7902  7902 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:14:02.679  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:02.679  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:14:02.679  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
09-12 18:14:02.679  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 18:14:02.679  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:02.679  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:14:02.789  7902  7902 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-12 18:14:02.789  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 18:14:02.869  7902  7902 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 18:14:02.869  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
09-12 18:14:02.869  7902  7902 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-12 18:14:02.879  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-12 18:14:02.879  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 18:14:02.889  7902  7902 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-12 18:14:02.889  7902  7902 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 18:14:02.889  7902  7902 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 18:14:02.889  7902  7902 E wpa_supplicant: SIM READ ERROR
,09-12 18:14:02.889  7902  7902 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:14:02.899  7902  7902 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 18:14:02.909  7902  7902 I wpa_supplicant: Skip scan - bUseNetwork false
09-12 18:14:02.909  1019  1130 D WifiConfigStore: Loading config and enabling all networks 
,09-12 18:14:02.919  4893  4893 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:14:02.919  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:14:02.919  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 18:14:02.919  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:14:02.919  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:02.919  1181  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 18:14:02.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:02.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.919  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:14:02.919  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-12 18:14:02.919  1181  1181 D HotspotTile: onReceive : 3, 0
09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:02.919  6812  6812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:02.929  1019  6909 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:02.929  1019  6909 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:02.929  1019  1130 E WifiConfigStore: Not a HS20
,09-12 18:14:02.929  6812  6812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:02.929  1019  6909 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:02.929  1019  6909 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:02.929  1019  6909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:14:02.929  1543  1543 I Hs20UtilService: Starting #20
,09-12 18:14:02.939  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:14:02.939  1019  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
09-12 18:14:02.939  7424  7424 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:14:02.939  7424  7424 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:14:02.939  7424  7424 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:14:02.939  1543  1608 I Hs20UtilService: Message received 5011
,09-12 18:14:02.939  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 18:14:02.939  7902  7902 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 18:14:02.939  7902  7902 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 18:14:02.939  7902  7902 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 18:14:02.939  7902  7902 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 18:14:02.939  7902  7902 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 18:14:02.939  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 18:14:02.939  7902  7902 I wpa_supplicant: First Scan Start
,09-12 18:14:02.939  7902  7902 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 18:14:02.949  7369  7369 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:14:02.949  1019  1130 D WifiNative-wlan0: Setting external_sim to 1
,09-12 18:14:02.949  1019  1130 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:14:02.949  1019  1130 I WifiNative-HAL: startHal
09-12 18:14:02.949  1019  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9e80588c
09-12 18:14:02.949  1019  1130 I WifiNative-HAL: Could not start hal
,09-12 18:14:02.949  1019  1130 E WifiNative-wlan0: do suspend true
,09-12 18:14:02.949  1019  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-12 18:14:02.949  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-12 18:14:02.949  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,09-12 18:14:02.959   277   978 D CommandListener: Setting iface cfg
,09-12 18:14:02.959  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:02.959   277   978 D CommandListener: Trying to bring up p2p0
09-12 18:14:02.959  1019  1154 I WifiNative-HAL: startHal
09-12 18:14:02.959  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9d6c79bc
09-12 18:14:02.959  1019  1154 I WifiNative-HAL: Could not start hal
09-12 18:14:02.959  1019  1154 E WifiScanningService: could not start HAL
,09-12 18:14:02.959  1019  1019 D RttService: SCAN_AVAILABLE : 3
09-12 18:14:02.959  1019  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 18:14:02.959  1019  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:02.959  1019  1129 D WifiP2pService: P2pEnablingState
09-12 18:14:02.959  1019  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 18:14:02.959  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 18:14:02.959  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:14:02.959  1019  1130 E WifiNative-wlan0: invaild command id : 215
,09-12 18:14:02.959  1019  1129 D WifiP2pService: P2p socket connection successful
,09-12 18:14:02.959  1019  1129 D WifiP2pService: P2pEnabledState
,09-12 18:14:02.959  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 18:14:02.959  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:14:02.959  1019  1130 E WifiNative-wlan0: invaild command id : 215
,09-12 18:14:02.959  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 18:14:02.959  7902  7902 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 18:14:02.959  1019  1132 E ConnectivityService: updateNetworkInfo()
,09-12 18:14:02.959  7902  7902 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 18:14:02.969  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:14:02.969  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 18:14:02.969  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:14:02.969  1019  1049 D WifiDisplayController: disconnect
09-12 18:14:02.969  1019  1049 D WifiDisplayController: updateConnection
09-12 18:14:02.969  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:14:02.969  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:14:02.969  7902  7902 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-12 18:14:02.969  1019  1130 E WifiStateMachine: Failed to set frequency band 0
,09-12 18:14:02.969  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:14:02.969  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:14:02.969  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress
,09-12 18:14:02.969  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-12 18:14:02.969  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:14:02.969  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:14:02.969  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:14:02.969  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:14:02.969  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 18:14:02.979  1019  1129 D WifiP2pService: DeviceAddress: 0a:75:42
09-12 18:14:02.979  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 18:14:02.979  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:02.979  1019  1130 D SecContentProvider2: mCursor = null
09-12 18:14:02.979  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:14:02.979  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 18:14:02.979  1019  1514 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 18:14:02.979  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 18:14:02.979  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:14:02.979  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:14:02.979  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:14:02.979  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:14:02.979  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  secondary type: null
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  wps: 0
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  grpcapab: 0
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  devcapab: 0
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  status: 3
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  wfdInfo: null
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  groupownerAddress: null
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  GOdeviceName: null
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  interfaceAddress: 
09-12 18:14:02.979  1019  1049 D WifiDisplayController:  SConnectInfo : null
,09-12 18:14:02.989  7747  7747 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:14:02.989  7747  7747 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 18:14:02.989  7747  7747 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:14:02.999  1019  1129 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 18:14:02.999  7409  7409 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:14:02.999  1019  1129 D WifiP2pService: InactiveState
,09-12 18:14:02.999  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
,09-12 18:14:02.999  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:14:02.999  7902  7902 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 18:14:02.999  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
,09-12 18:14:02.999  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:14:03.029  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:03.029  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:14:03.029  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:03.679  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:14:03.679  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:03.689  6812  7131 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 18:14:03.689  6812  7131 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 18:14:03.689  6812  7131 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@37f10f57 Bundle[{}]
,09-12 18:14:03.689  6812  7131 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 18:14:03.689  6812  7131 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 18:14:03.689  6812  7131 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 18:14:03.699  6812  7131 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
09-12 18:14:03.699  6812  7131 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
09-12 18:14:03.699  6812  7131 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 18:14:03.699  6812  7131 I System.out: Running OutgoingSocketThread
,09-12 18:14:03.699  6812  7912 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1374)
09-12 18:14:03.699  6812  7912 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55145,
,09-12 18:14:03.699  6812  7912 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 18:14:04.189  7902  7902 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
,09-12 18:14:04.189  7902  7902 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 18:14:04.189  1019  7908 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-12 18:14:04.189  7902  7902 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-12 18:14:04.189  7902  7902 I wpa_supplicant: Trying to associate with  'G700'
,09-12 18:14:04.189  7902  7902 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-12 18:14:04.189  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-12 18:14:04.209  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:14:04.209  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:14:04.439  7902  7902 E wpa_supplicant: Cmd 35605 not handled
,09-12 18:14:04.439  7902  7902 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 18:14:04.439  7902  7902 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-12 18:14:04.439  7902  7902 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-12 18:14:04.439  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:14:04.439  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:14:04.439  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,09-12 18:14:04.439  7902  7902 I wpa_supplicant: Associated with F4.99.3E
09-12 18:14:04.439  7902  7902 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 18:14:04.439  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:14:04.439  7902  7902 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,09-12 18:14:04.439  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-12 18:14:04.439  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:14:04.439  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:14:04.439  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:14:04.439  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true,
09-12 18:14:04.439  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-12 18:14:04.439  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,09-12 18:14:04.439  1019  1133 E Tethering: No numeric data
09-12 18:14:04.439  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:04.439  1019  1130 D SecContentProvider2: mCursor = null
09-12 18:14:04.439  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 18:14:04.439  1019  1133 D Tethering: clearTetheredNotification()
09-12 18:14:04.449  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-12 18:14:04.449  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:14:04.449  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:04.449  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:14:04.449  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 18:14:04.449  1181  1181 D HotspotTile: updateTetherState():false, false
09-12 18:14:04.449  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:04.449  1019  1127 V NetworkStats: performPollLocked() took 6ms
09-12 18:14:04.449  1019  1130 D SecContentProvider2: mCursor = null
09-12 18:14:04.449  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:04.459  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:04.459  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:04.459  7902  7902 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 18:14:04.459  7902  7902 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-12 18:14:04.459  7902  7902 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-12 18:14:04.459  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-12 18:14:04.459  7902  7902 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:14:04.459  7902  7902 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 18:14:04.459  7902  7902 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-12 18:14:04.459  7902  7902 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 18:14:04.459  7902  7902 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-12 18:14:04.459  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 18:14:04.459  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,09-12 18:14:04.459  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-12 18:14:04.459  1019  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 18:14:04.469  1019  1130 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-12 18:14:04.479  1019  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 18:14:04.479  1019  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 18:14:04.479  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:14:04.479  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:14:04.479  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:14:04.479  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:14:04.479  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-12 18:14:04.479  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:14:04.479  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 18:14:04.479  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:04.479  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:04.479  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:14:04.479  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:04.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:04.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:04.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.489  1543  1543 I Hs20UtilService: Starting #21,
,09-12 18:14:04.489  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:14:04.489  1543  1608 I Hs20UtilService: Message received 5007
,09-12 18:14:04.489  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:14:04.489  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:14:04.489  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-12 18:14:04.489  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 18:14:04.489  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-12 18:14:04.489  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:14:04.499  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 18:14:04.499   277   978 D CommandListener: Setting iface cfg
,09-12 18:14:04.499  1019  1130 E WifiStateMachine: Start Dhcp Watchdog 3
,09-12 18:14:04.509  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:04.509  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:14:04.519  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:14:04.519  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:04.519  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:04.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:04.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 18:14:04.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.519  1019  1130 E WifiNative-wlan0: do suspend false
,09-12 18:14:04.519  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,09-12 18:14:04.519  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 18:14:04.529  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:04.529  1019  1130 D SecContentProvider2: mCursor = null
,09-12 18:14:04.699   294   294 E SMD     : DCD OFF,
,09-12 18:14:04.699  6812  7131 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1375)
,09-12 18:14:04.699  6812  7131 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1375),
,09-12 18:14:04.709  6812  7131 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1380)
,09-12 18:14:04.709  6812  7131 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 18:14:04.709  6812  7131 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1381)
,09-12 18:14:04.709  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:14:04.709  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a85e409 added. We now have 2 listener(s)
09-12 18:14:04.709  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 18:14:04.709  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:04.709  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:04.709  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:04.709  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e73060e added. We now have 9 listener(s)
09-12 18:14:04.709  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:04.709  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:04.719  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:04.719  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:04.729  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:04.729  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:04.729  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:04.729  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@389fe3c added. We now have 3 listener(s)
,09-12 18:14:04.729  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:04.729  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:14:04.729  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:04.729  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:04.729  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:04.729  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b9fb7c5 added. We now have 10 listener(s)
09-12 18:14:04.729  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:04.729  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:14:04.729  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:04.729  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:04.729  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:04.729  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.729  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:04.729  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:04.729  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a85e409 removed from the list
09-12 18:14:04.729  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:04.729  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e73060e removed from the list
,09-12 18:14:04.739  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:04.739  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:04.739  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:04.739  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.739  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:04.739  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e73060e not in the list
09-12 18:14:04.739  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.739  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:04.739  7915  7915 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:04.739  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b9fb7c5 removed from the list
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:04.739  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.739  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:04.739  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:04.739  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@389fe3c removed from the list
09-12 18:14:04.749  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:04.749  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245d751a added. We now have 2 listener(s)
,09-12 18:14:04.749  7915  7915 I dhcpcd  : version 5.5.6 starting,
09-12 18:14:04.749  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 18:14:04.749  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:04.749  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-12 18:14:04.749  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:04.749  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2194f84b added. We now have 9 listener(s)
09-12 18:14:04.749  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:04.749  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:14:04.749  7915  7915 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 18:14:04.759  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:04.759  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:04.769  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:14:04.769  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:04.769  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:04.769  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc90b41 added. We now have 3 listener(s)
09-12 18:14:04.769  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:04.769  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:04.779  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 18:14:04.779  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:04.779  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:04.779  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:04.779  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84dc8e6 added. We now have 10 listener(s)
09-12 18:14:04.779  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:04.779  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:04.779  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:04.779  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:14:04.779  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:14:04.779  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:14:04.779  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:04.789  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:04.789  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:04.799  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-12 18:14:04.799  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:14:04.799  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:04.809  3278  7348 D BtGatt.GattService: registerClient() - UUID=8fb0dda8-c066-450f-8a8b-2941ee0a24e0
,09-12 18:14:04.839  7915  7915 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,09-12 18:14:04.839  7915  7915 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
,09-12 18:14:04.839  7915  7915 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-12 18:14:04.839  7915  7915 I dhcpcd  : bssid match,
,09-12 18:14:04.839  7915  7915 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
,09-12 18:14:04.859  3278  3358 D BtGatt.GattService: onClientRegistered() - UUID=8fb0dda8-c066-450f-8a8b-2941ee0a24e0, clientIf=6,
09-12 18:14:04.859  6812  6824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:14:04.859  3278  7883 D BtGatt.GattService: start scan with filters,
,09-12 18:14:04.859  3278  3401 D BtGatt.ScanManager: handling starting scan
09-12 18:14:04.859  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:14:04.859  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:04.859  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:14:04.859  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-12 18:14:04.859  3278  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:14:04.859  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:04.859  3278  3401 D BtGatt.ScanManager: allow scan with filters
09-12 18:14:04.859  3278  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:14:04.859  3278  3401 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,09-12 18:14:04.859  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:14:04.859  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:04.859  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:04.859  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:14:04.859  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:04.859  3278  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:14:04.859  3278  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 18:14:04.869  3278  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 18:14:04.869  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.869  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:04.869  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 18:14:04.869  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.869  6812  7131 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:14:04.869  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:04.869  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:14:04.869  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.869  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:04.869  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:14:04.869  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:14:04.869  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:14:04.869  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:14:04.869  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:14:04.869  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:14:04.869  3278  3293 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:14:04.879  3278  3291 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:14:04.879  3278  3401 D BtGatt.ScanManager: filter size is 1,
09-12 18:14:04.879  3278  3401 D BtGatt.ScanManager: delete FilterIndex - 6
,09-12 18:14:04.879  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:14:04.879  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-12 18:14:04.879  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:04.879  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:14:04.879  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.879  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:04.879  3278  3401 D BtGatt.ScanManager: stopping BLe Batch
09-12 18:14:04.879  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:14:04.879  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:04.879  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:14:04.879  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:04.879  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:14:04.879  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:04.879  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:04.879  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:04.879  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:04.879  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:14:04.879  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.889  3278  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:14:04.889  3278  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 18:14:04.889  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.889  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:04.889  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:04.889  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:04.889  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.889  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:04.889  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245d751a removed from the list
09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:04.889  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2194f84b removed from the list
09-12 18:14:04.889  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:04.889  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:04.889  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.889  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:04.889  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2194f84b not in the list
09-12 18:14:04.889  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:04.889  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:04.889  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84dc8e6 removed from the list
,09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:14:04.889  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:04.889  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:04.889  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:04.889  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc90b41 removed from the list
,09-12 18:14:04.899  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:14:04.899  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39d8d72 added. We now have 2 listener(s)
,09-12 18:14:04.899  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:14:04.899  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:14:04.899  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:04.899  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:04.899  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235a25c3 added. We now have 9 listener(s)
09-12 18:14:04.899  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:04.899  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:04.909  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:04.909  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:04.909  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:04.909  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:14:04.909  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 18:14:04.909  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 18:14:04.909  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f2e179 added. We now have 3 listener(s)
09-12 18:14:04.909  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:04.919  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:14:04.919  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:14:04.919  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:04.919  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:04.919  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b30ebe added. We now have 10 listener(s)
09-12 18:14:04.919  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:04.919  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:14:04.919  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:04.919  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:04.919  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:14:04.919  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:04.919  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:14:04.919  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:04.919  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:04.919  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:04.929  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-12 18:14:04.929  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:14:04.929  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:04.929  3278  3398 D BtGatt.GattService: registerClient() - UUID=4ea71f1d-0833-49fb-8b1b-5c2d65571289,
,09-12 18:14:04.969  7915  7915 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-12 18:14:04.969  3278  3358 D BtGatt.GattService: onClientRegistered() - UUID=4ea71f1d-0833-49fb-8b1b-5c2d65571289, clientIf=6
,09-12 18:14:04.969  6812  6820 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:14:04.969  3278  7883 D BtGatt.GattService: start scan with filters
,09-12 18:14:04.969  3278  3401 D BtGatt.ScanManager: handling starting scan
,09-12 18:14:04.979  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:14:04.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:04.979  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:14:04.979  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:14:04.979  3278  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 18:14:04.979  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.979  3278  3401 D BtGatt.ScanManager: allow scan with filters
,09-12 18:14:04.979  3278  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 18:14:04.979  3278  3401 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-12 18:14:04.979  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 18:14:04.979  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.979  3278  3401 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 18:14:04.979  3278  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 18:14:04.989  3278  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 18:14:04.989  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.989  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:04.989  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:04.989  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:14:04.999  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 18:14:04.999  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:04.999  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:04.999  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:14:04.999  6812  7131 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:14:05.009  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:14:05.009  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:14:05.009  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:14:05.009  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:14:05.009  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:05.009  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:14:05.009  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 18:14:05.009  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39d8d72 removed from the list
,09-12 18:14:05.009  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:05.009  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235a25c3 removed from the list
,09-12 18:14:05.009  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:14:05.009  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.009  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:05.009  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-12 18:14:05.009  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:05.009  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.019  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:05.019  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:14:05.019  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:05.019  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235a25c3 not in the list
,09-12 18:14:05.019  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:14:05.019  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:14:05.019  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:14:05.019  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:14:05.019  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:14:05.019  3278  3293 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:14:05.019  3278  3401 D BtGatt.ScanManager: filter size is 1
09-12 18:14:05.019  3278  3401 D BtGatt.ScanManager: delete FilterIndex - 7
,09-12 18:14:05.019  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 18:14:05.019  3278  3291 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:14:05.019  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.029  3278  3401 D BtGatt.ScanManager: stopping BLe Batch,
09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:14:05.029  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:14:05.029  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.029  3278  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:14:05.029  3278  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.029  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b30ebe removed from the list
09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.029  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.029  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.029  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.029  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f2e179 removed from the list
,09-12 18:14:05.029  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:14:05.029  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.029  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d58ca added. We now have 2 listener(s)
09-12 18:14:05.029  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:14:05.029  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:05.039  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.039  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:14:05.039  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:14:05.039  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.039  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.039  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f88a3b added. We now have 9 listener(s)
09-12 18:14:05.039  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:05.039  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:05.039  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:05.049  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:05.049  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:05.049  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:05.049  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.049  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@144a46b1 added. We now have 3 listener(s)
,09-12 18:14:05.049  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.049  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 18:14:05.049  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:14:05.049  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.049  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:14:05.049  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.049  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23103796 added. We now have 10 listener(s)
09-12 18:14:05.049  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:05.049  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:05.049  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:05.049  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:14:05.049  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:14:05.049  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:14:05.059  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:05.069  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:05.069  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:05.069  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:14:05.069  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 18:14:05.069  6812  7131 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:05.079  3278  7348 D BtGatt.GattService: registerClient() - UUID=7fa723e8-f052-40a4-be24-cfde5ae065fe
,09-12 18:14:05.099  7915  7915 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-12 18:14:05.109  6812  6822 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3326aaf8, channel: -1, state: CLOSED,
,09-12 18:14:05.119  3278  3358 D BtGatt.GattService: onClientRegistered() - UUID=7fa723e8-f052-40a4-be24-cfde5ae065fe, clientIf=6,
09-12 18:14:05.119  6812  6824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 18:14:05.119  3278  7883 D BtGatt.GattService: start scan with filters,
09-12 18:14:05.119  3278  3401 D BtGatt.ScanManager: handling starting scan
09-12 18:14:05.119  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:14:05.119  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:05.119  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-12 18:14:05.119  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:14:05.119  3278  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:14:05.119  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-12 18:14:05.119  3278  3401 D BtGatt.ScanManager: allow scan with filters
09-12 18:14:05.119  3278  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:14:05.119  3278  3401 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
09-12 18:14:05.119  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-12 18:14:05.119  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:05.129  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:14:05.129  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:14:05.129  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-12 18:14:05.129  3278  3401 D BtGatt.ScanManager: Starting BLE batch scan,
09-12 18:14:05.129  3278  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 18:14:05.129  3278  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 18:14:05.129  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.129  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:05.129  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-12 18:14:05.129  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.139  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:05.139  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:05.139  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.139  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.139  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.139  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d58ca removed from the list
09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.139  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f88a3b removed from the list
09-12 18:14:05.139  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:05.139  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.139  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.139  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 18:14:05.139  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.139  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.139  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f88a3b not in the list
09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:14:05.139  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-12 18:14:05.139  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:14:05.139  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:14:05.139  3278  7348 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:14:05.139  3278  3401 D BtGatt.ScanManager: filter size is 1
,09-12 18:14:05.139  3278  3401 D BtGatt.ScanManager: delete FilterIndex - 8
,09-12 18:14:05.139  3278  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 18:14:05.139  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.139  3278  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:14:05.149  3278  7883 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:05.149  3278  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:14:05.149  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:14:05.149  3278  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:14:05.149  3278  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 18:14:05.149  3278  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.149  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23103796 removed from the list
09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.149  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.149  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.149  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.149  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@144a46b1 removed from the list
,09-12 18:14:05.149  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:05.149  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.149  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37903722 added. We now have 2 listener(s)
09-12 18:14:05.149  6812  6812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:05.149  6812  6812 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:05.159  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 18:14:05.159  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.159  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.159  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.159  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8005b3 added. We now have 9 listener(s)
09-12 18:14:05.159  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:05.159  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:05.159  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:05.169  6812  7131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:05.169  6812  7131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:05.169  6812  7131 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:05.169  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.169  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4121ae9 added. We now have 3 listener(s)
,09-12 18:14:05.169  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 18:14:05.169  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.169  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.179  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.179  6812  6812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.179  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:05.179  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@391ea36e added. We now have 10 listener(s)
09-12 18:14:05.179  6812  7131 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.179  6812  7131 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.179  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.179  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.179  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37903722 removed from the list
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.179  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8005b3 removed from the list
09-12 18:14:05.179  6812  7131 D io.jxcore.node.ConnectivityMonitor: stop,
09-12 18:14:05.179  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.179  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.179  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.179  6812  7131 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8005b3 not in the list
09-12 18:14:05.179  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.179  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.179  6812  7131 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@391ea36e removed from the list
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.179  6812  7131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.179  6812  7131 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.179  6812  7131 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.179  6812  7131 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4121ae9 removed from the list
09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 18:14:05.179  6812  7131 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:14:05.189  6812  7934 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1388, name: My test thread name)
09-12 18:14:05.189  6812  7934 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1388, thread name: My test thread name)
09-12 18:14:05.189  6812  7934 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1388, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 18:14:05.189  6812  7935 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1390, name: My test thread name)
,09-12 18:14:05.189  6812  7935 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1390, thread name: My test thread name)
09-12 18:14:05.189  6812  7935 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1390, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 18:14:05.199  6812  7131 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-12 18:14:05.199  6812  7131 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 18:14:05.199  6812  7131 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 18:14:05.199  6812  7131 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 18:14:05.199  6812  7131 D com.test.thalitest.ThaliTestRunner: Total duration: 23243 ms,
,09-12 18:14:05.199  6812  7131 I jxcore-log: *Native tests were executed*
09-12 18:14:05.199  6812  7131 I jxcore-log: 
09-12 18:14:05.199  6812  7131 I jxcore-log: Total number of executed tests:  80
09-12 18:14:05.199  6812  7131 I jxcore-log: 
09-12 18:14:05.199  6812  7131 I jxcore-log: Number of passed tests:  80,
09-12 18:14:05.199  6812  7131 I jxcore-log: 
09-12 18:14:05.199  6812  7131 I jxcore-log: Number of failed tests:  0
09-12 18:14:05.199  6812  7131 I jxcore-log: 
09-12 18:14:05.199  6812  7131 I jxcore-log: Number of ignored tests:  0,
09-12 18:14:05.199  6812  7131 I jxcore-log: 
,09-12 18:14:05.199  6812  7131 I jxcore-log: Total duration:  23243
09-12 18:14:05.199  6812  7131 I jxcore-log: 
09-12 18:14:05.199  6812  7131 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 18:14:05.199  6812  7131 I jxcore-log: 
,09-12 18:14:05.199  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.199  6812  7131 I jxcore-log: 
09-12 18:14:05.209  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.209  6812  7131 I jxcore-log: 
09-12 18:14:05.209  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.209  6812  7131 I jxcore-log: 
09-12 18:14:05.209  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.209  6812  7131 I jxcore-log: 
09-12 18:14:05.209  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.209  6812  7131 I jxcore-log: 
09-12 18:14:05.209  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.209  6812  7131 I jxcore-log: 
09-12 18:14:05.209  6812  6812 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
,09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
,09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
09-12 18:14:05.219  6812  7131 I jxcore-log: 
09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-12 18:14:05.219  6812  7131 I jxcore-log: 
,09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
,09-12 18:14:05.219  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.219  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.229  6812  7131 I jxcore-log: 
,09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.229  6812  7131 I jxcore-log: 
,09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.229  6812  7131 I jxcore-log: 
,09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.229  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 18:14:05.229  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 18:14:05.229  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 18:14:05.229  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-12 18:14:05.229  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 18:14:05.229  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 18:14:05.229  6812  7131 I jxcore-log: 
09-12 18:14:05.229  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-12 18:14:05.229  6812  7131 I jxcore-log: 
,09-12 18:14:05.339  1019  1130 E WifiNative-wlan0: do suspend true
,09-12 18:14:05.359  1019  1129 D WifiP2pService: InactiveState{ what=143375 },
09-12 18:14:05.359  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 18:14:05.369  1019  1130 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 18:14:05.369  1019  1130 E WifiStateMachine: VerifyingLinkState enter
,09-12 18:14:05.369  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 18:14:05.369  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.369  1019  1132 E ConnectivityService: updateNetworkInfo()
,09-12 18:14:05.369  1019  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
09-12 18:14:05.369  1019  1132 D ConnectivityService: Adding iface wlan0 to network 504
,09-12 18:14:05.379  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:05.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.379  1019  1148 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-12 18:14:05.379  1019  1148 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 18:14:05.379  1019  1148 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 18:14:05.379  1019  1148 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 18:14:05.379  1019  1148 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 18:14:05.379  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-12 18:14:05.389  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:05.389  6812  7131 I jxcore-log: 
,09-12 18:14:05.389  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:14:05.389  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.389  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:05.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.389  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:05.389  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-12 18:14:05.389  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:05.389  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:05.389  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:14:05.389  1543  1543 I Hs20UtilService: Starting #22
09-12 18:14:05.389  1543  1608 I Hs20UtilService: Message received 5007
,09-12 18:14:05.409  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 18:14:05.409  4893  4893 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 18:14:05.409  1019  1130 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-12 18:14:05.419  1019  1132 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
,09-12 18:14:05.419  1019  1132 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-12 18:14:05.419  1019  1132 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-12 18:14:05.429  1019  1132 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 18:14:05.429  1019  1132 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-12 18:14:05.429  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 18:14:05.429  1019  1132 D ConnectivityService: LTETest block dns file not exists
,09-12 18:14:05.439  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-12 18:14:05.439  1019  1132 V NetworkStats: updateIfacesLocked()
09-12 18:14:05.439  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 18:14:05.439  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:05.439  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:05.439  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.439  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.439  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.439  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.439  1019  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 18:14:05.439  1019  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 18:14:05.439  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.439  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:05.439  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:05.439  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.439  1019  1132 V NetworkStats: performPollLocked() took 5ms
,09-12 18:14:05.449  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 18:14:05.449  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
09-12 18:14:05.449  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
,09-12 18:14:05.459  1019  1563 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:05.459  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:05.459  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.459  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 18:14:05.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.459  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:05.459  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:05.459  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:14:05.459  1543  1543 I Hs20UtilService: Starting #23
09-12 18:14:05.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.459  1543  1608 I Hs20UtilService: Message received 5007
09-12 18:14:05.459  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:14:05.459  4893  4893 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:14:05.459  1019  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-12 18:14:05.459  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:14:05.459  1019  1132 E ConnectivityService: updateNetworkInfo()
09-12 18:14:05.459  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:14:05.459  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.459  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.469  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.469  1019  1132 V NetworkStats: updateIfacesLocked()
09-12 18:14:05.469  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:05.469  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 18:14:05.469  7943  7943 D AndroidRuntime: 
09-12 18:14:05.469  7943  7943 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 18:14:05.469  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:05.469  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:05.469  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:14:05.469  4893  4893 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:14:05.469  4893  4893 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:14:05.469  4893  4967 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 18:14:05.469  7943  7943 D AndroidRuntime: CheckJNI is OFF
,09-12 18:14:05.469  7943  7943 D AndroidRuntime: readGMSProperty: start
09-12 18:14:05.469  1019  1132 V NetworkStats: performPollLocked() took 5ms
,09-12 18:14:05.469  7943  7943 D AndroidRuntime: readGMSProperty: already setted!!
09-12 18:14:05.469  1019  1132 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,09-12 18:14:05.469  7943  7943 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 18:14:05.469  1019  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
09-12 18:14:05.469  7943  7943 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,09-12 18:14:05.469  7943  7943 D AndroidRuntime: readGMSProperty: end
09-12 18:14:05.469  7943  7943 D AndroidRuntime: addProductProperty: start
09-12 18:14:05.469  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.469  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.469  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.469  1019  7913 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:05.469  1019  7913 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-12 18:14:05.469  1019  7913 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:05.469  1019  7913 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-12 18:14:05.469  1019  7913 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 18:14:05.479   277   974 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 18:14:05.479   277   974 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-12 18:14:05.479  1019  1132 D ConnectivityService:    accepting network in place of null
09-12 18:14:05.479  1019  1129 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 18:14:05.479  1019  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-12 18:14:05.479  1482  1482 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 18:14:05.479  1482  1482 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:14:05.479  1019  1132 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-12 18:14:05.479  1019  1132 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 18:14:05.479  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 18:14:05.489  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 18:14:05.489  1019  1132 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-12 18:14:05.489  1019  1133 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:14:05.489  1019  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-12 18:14:05.489  1019  1127 V NetworkStats: updateIfacesLocked()
09-12 18:14:05.489  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.489  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:05.489  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-12 18:14:05.489  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:05.489  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 18:14:05.489  1181  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 18:14:05.489  1019  1316 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:05.489  1019  1316 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:05.489  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:05.489  1019  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:05.489  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:14:05.489  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
09-12 18:14:05.489  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 18:14:05.489  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 18:14:05.489  1181  1181 D StatusBar.NetworkController: updateDataNetType()
,09-12 18:14:05.489  1019  1127 V NetworkStats: performPollLocked() took 6ms
09-12 18:14:05.489  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.489  1543  1543 I Hs20UtilService: Starting #24
,09-12 18:14:05.499  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.499  1019  1128 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 18:14:05.499  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.499  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.499  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.499  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.499  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.499  4893  4893 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 18:14:05.499  1543  1608 I Hs20UtilService: Message received 5007
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:14:05.499  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.499  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.499  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.499  4893  4893 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 18:14:05.509  1019  1563 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-12 18:14:05.509  1019  1514 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-12 18:14:05.509  1019  1514 D SecContentProvider2: mCursor = null
,09-12 18:14:05.509  1019  1398 D SecContentProvider2: uri = 15 selection = getToastGravity
09-12 18:14:05.509  1019  1398 D SecContentProvider2: mCursor = null
,09-12 18:14:05.509  1019  1550 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
09-12 18:14:05.509  1019  1550 D SecContentProvider2: mCursor = null
,09-12 18:14:05.519  1019  1316 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-12 18:14:05.519  1019  1316 D SecContentProvider2: mCursor = null
,09-12 18:14:05.519  1019  1561 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
09-12 18:14:05.519  1019  1561 D SecContentProvider2: mCursor = null
,09-12 18:14:05.529  1019  1031 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-12 18:14:05.529  1019  1031 D SecContentProvider2: mCursor = null
,09-12 18:14:05.539  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:14:05.539  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:05.539  6812  7131 I jxcore-log: 
,09-12 18:14:05.549   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-12 18:14:05.569  1019  1563 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,09-12 18:14:05.579  1181  1181 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 18:14:05.589  1019  7913 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 18:14:05.599  7943  7943 E AffinityControl: AffinityControl: registerfunction enter
,09-12 18:14:05.619  7943  7943 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 18:14:05.639  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-12 18:14:05.639  1019  1032 D PackageManager: START PACKAGE DELETE: observer{600680855}
09-12 18:14:05.639  1019  1032 D PackageManager: pkg{<packageName>}
09-12 18:14:05.639  1019  1032 D PackageManager: user{0}
09-12 18:14:05.639  1019  1032 D PackageManager: caller{2000}
09-12 18:14:05.639  1019  1032 D PackageManager: flags{2}
09-12 18:14:05.639  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-12 18:14:05.639  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-12 18:14:05.639  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-12 18:14:05.639  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-12 18:14:05.649  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-12 18:14:05.649  1019  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-12 18:14:05.649  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-12 18:14:05.649  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
09-12 18:14:05.649  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-12 18:14:05.649  1019  7913 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:14:05 GMT], X-Android-Received-Millis=[1473696845664], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473696845633]}
09-12 18:14:05.649  1019  1132 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-12 18:14:05.649  1019  7913 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 18:14:05.649  1019  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-12 18:14:05.649  1019  7913 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-12 18:14:05.649  1019  1132 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-12 18:14:05.649  1019  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-12 18:14:05.649  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 18:14:05.649  1181  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
09-12 18:14:05.649  6812  6812 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 18:14:05.649  6812  7131 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-12 18:14:05.649  6812  7131 I jxcore-log: 
,09-12 18:14:05.659  1019  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: EthernetConnected: false,
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: updateDataNetType()
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 18:14:05.659  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-12 18:14:05.659  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-12 18:14:05.669  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.669  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 18:14:05.669  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.669  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.669  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.669  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.739  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-12 18:14:05.739  1019  1044 I ActivityManager: Killing 6812:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-12 18:14:05.789  1019  1044 I ActivityManager:   Force finishing activity ActivityRecord{9abdd25 u0 com.test.thalitest/.MainActivity t163}
,09-12 18:14:05.799  1019  1044 D InputDispatcher: Focus left window: 6812
,09-12 18:14:05.799   257  6830 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-12 18:14:05.799   257  1103 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-12 18:14:05.829  1019  1044 D InputDispatcher: Focused application released
,09-12 18:14:05.829  1019  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 18:14:05.829  1019  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-12 18:14:05.839  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 18:14:05.839  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:14:05.859  1019  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-12 18:14:05.879  2820  2820 I art     : Explicit concurrent mark sweep GC freed 16599(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 858us total 35.171ms
,09-12 18:14:05.889  1019  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 18:14:05.899  2020  2020 E SamsungIME: mOCRHelper is null
,09-12 18:14:05.899  1685  1908 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 18:14:05.909  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,09-12 18:14:05.909  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-12 18:14:05.909  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 18:14:05 GMT+02:00 2016
,09-12 18:14:05.909  1469  1469 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:05.919  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-12 18:14:05.929  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-12 18:14:05.939  1019  1561 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-12 18:14:05.939  1019  1561 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 18:14:05.939  1019  1097 V AlarmManager: waitForAlarm result :4
,09-12 18:14:05.939  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:05.949  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
09-12 18:14:05.949  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:05.949  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 18:14:05.949  1019  1127 V NetworkStats: removeUidsLocked() for UIDs [10170]
,09-12 18:14:05.949  1019  1127 V NetworkStats: performPollLocked(flags=0x3)
09-12 18:14:05.949  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.949  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:05.949  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:05.949  1019  1127 V NetworkStats: performPollLocked() took 6ms
09-12 18:14:05.949  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.949  1469  1469 D RegisteredServicesCache: empty dynamic service
,09-12 18:14:05.959  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-12 18:14:05.959  1019  1032 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
09-12 18:14:05.959  1019  1032 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-12 18:14:05.959  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-12 18:14:05.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:05.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:05.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:05.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:05.969  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-12 18:14:05.979  2804  2804 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 18:14:05.979  1019  1398 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin,
09-12 18:14:05.979  1019  1398 D SecContentProvider2: mCursor = null,
,09-12 18:14:05.979  7966  7966 E Zygote  : MountEmulatedStorage()
,09-12 18:14:05.979  7966  7966 E Zygote  : v2
09-12 18:14:05.979  7966  7966 I libpersona: KNOX_SDCARD checking this for 10090
09-12 18:14:05.979  7966  7966 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:05.989  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
09-12 18:14:05.989  7966  7966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:05.989  7966  7966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:14:05.989  7966  7966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-12 18:14:05.989  1019  1032 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7966 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-12 18:14:05.999  1469  1469 D RegisteredComponentCache: Collect Tech packages for Knox
,09-12 18:14:05.999  1469  1469 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:06.009  2804  2804 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 18:14:06.019  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:06.019  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:06.029  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,09-12 18:14:06.029  2804  7965 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 18:14:06.029  2804  7965 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
09-12 18:14:06.029  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-12 18:14:06.029  7966  7966 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:14:06.029  7966  7966 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.039  2804  7965 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-12 18:14:06.049  2804  7965 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-12 18:14:06.069  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-12 18:14:06.079  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.079  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.079  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.079  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.089  7981  7981 E Zygote  : MountEmulatedStorage()
09-12 18:14:06.089  7981  7981 E Zygote  : v2
09-12 18:14:06.089  7981  7981 I libpersona: KNOX_SDCARD checking this for 10052
09-12 18:14:06.089  7981  7981 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:06.089  7981  7981 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.099  7981  7981 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.099  7981  7981 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.109  1019  1044 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7981 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-12 18:14:06.109  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-12 18:14:06.109  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.119  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.119  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.119  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.129  7996  7996 E Zygote  : MountEmulatedStorage(),
09-12 18:14:06.129  7996  7996 E Zygote  : v2
,09-12 18:14:06.129  7996  7996 I libpersona: KNOX_SDCARD checking this for 10098
09-12 18:14:06.129  7996  7996 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:06.129  7996  7996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 18:14:06.129  1019  1044 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7996 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-12 18:14:06.139  7981  7981 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 18:14:06.139  7981  7981 D ActivityThread: Added TimaKeyStore provider
09-12 18:14:06.139  7996  7996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.139  7996  7996 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.139  7966  7966 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-12 18:14:06.149  7966  7966 D elm:15121: ELMEngine.ELMEngine( context ).
,09-12 18:14:06.149  7966  7966 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-12 18:14:06.169  1019  1523 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 18:14:06.169  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.169  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.169  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.169  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.179  7996  7996 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-12 18:14:06.179  7996  7996 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.179  8011  8011 E Zygote  : MountEmulatedStorage()
09-12 18:14:06.179  8011  8011 E Zygote  : v2
09-12 18:14:06.179  8011  8011 I libpersona: KNOX_SDCARD checking this for 10032
09-12 18:14:06.179  8011  8011 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:06.179  8011  8011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.179  8011  8011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 18:14:06.189  8011  8011 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.199  1019  1523 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8011 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:14:06.199  1019  1563 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-12 18:14:06.199  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.209  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:06.209  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:06.209  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-12 18:14:06.209  1019  1058 I art     : Explicit concurrent mark sweep GC freed 66326(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 5.077ms total 284.188ms
,09-12 18:14:06.209  7966  7966 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-12 18:14:06.209   322   322 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 23.531ms
,09-12 18:14:06.219  1019  1029 I art     : WaitForGcToComplete blocked for 238.417ms for cause HeapTrim
,09-12 18:14:06.229  8011  8011 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:06.229   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 17.968ms
09-12 18:14:06.229  8011  8011 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.239  7966  7966 D elm:15121: ElmAgentService : onCreate()
,09-12 18:14:06.239  7966  8021 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-12 18:14:06.239  7966  8021 D elm:15121: MainReceiver.listeningToPackageRemoved()
,09-12 18:14:06.239  7966  8021 D elm:15121: MDMBridge.getInstance()
,09-12 18:14:06.239  7966  8021 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 18:14:06.239  7966  8021 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 18:14:06.249   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 19.728ms
,09-12 18:14:06.269  7966  7966 D elm:15121: ElmAgentService : onDestroy().
,09-12 18:14:06.269  1019  1523 I ActivityManager: Killing 7459:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-12 18:14:06.279  2804  7965 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-12 18:14:06.289  1019  1316 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-12 18:14:06.289  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.289  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.289  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.289  1019  1316 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.299  2804  7965 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-12 18:14:06.299  2804  7965 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-12 18:14:06.309  8028  8028 E Zygote  : MountEmulatedStorage()
09-12 18:14:06.309  8028  8028 E Zygote  : v2
09-12 18:14:06.309  8028  8028 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:14:06.309  8028  8028 I libpersona: KNOX_SDCARD not a persona
09-12 18:14:06.309  8028  8028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.309  8028  8028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.309  8028  8028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:14:06.309  1019  1316 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=8028 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 18:14:06.309  1019  1316 I ActivityManager: Killing 7476:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-12 18:14:06.319  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-12 18:14:06.339  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-12 18:14:06.339  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-12 18:14:06.339  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 18:14:06.349  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 18:14:06.349  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-12 18:14:06.349  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-12 18:14:06.349  1019  3428 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-12 18:14:06.359  8028  8028 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:06.359  1019  6909 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-12 18:14:06.359  8028  8028 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.359  1019  6909 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.359  1019  6909 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:06.359  1019  6909 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:06.359  1019  6909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-12 18:14:06.359  8011  8043 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 18:14:06.359  8011  8043 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 18:14:06.369  1019  1058 D PackageManager: delete codoeFile: 
,09-12 18:14:06.369  1019  1031 I ActivityManager: Killing 7491:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-12 18:14:06.369  8011  8043 D SPPClientService: PushLog.txt file is not deleted.
,09-12 18:14:06.369  8011  8043 D SPPClientService: PushLog.txt file is not deleted.
09-12 18:14:06.369  8011  8043 D SPPClientService: ============PushLog. stop!
,09-12 18:14:06.379  1019  1316 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-12 18:14:06.379  1019  1316 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.379  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
09-12 18:14:06.379  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-12 18:14:06.379  1019  1043 W TextServicesManagerService: no available spell checker services found
,09-12 18:14:06.379  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:06.379  1019  1316 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:06.379  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-12 18:14:06.379  1019  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
09-12 18:14:06.379  1019  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-12 18:14:06.379  1019  1563 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-12 18:14:06.379  1019  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.389  1019  1058 D PackageManager: result of delete: 1{600680855}
,09-12 18:14:06.389  1019  1563 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:06.389  1019  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:06.389  1019  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-12 18:14:06.399  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.399  1019  6909 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-12 18:14:06.399  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.399  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.399  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.399  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.399  1019  6909 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.399  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.409  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.409  8047  8047 E Zygote  : MountEmulatedStorage()
09-12 18:14:06.409  8047  8047 E Zygote  : v2
09-12 18:14:06.409  8047  8047 I libpersona: KNOX_SDCARD checking this for 10039
09-12 18:14:06.409  8047  8047 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:06.419  8047  8047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.419  8047  8047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.419  8047  8047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.429  7943  7943 D AndroidRuntime: Shutting down VM
,09-12 18:14:06.429  1019  6909 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8047 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-12 18:14:06.439  7801  7801 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-12 18:14:06.439  1019  1398 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,09-12 18:14:06.449  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.449  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.449  8047  8047 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:06.449  8047  8047 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.449  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.449  1019  1398 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.459  1019  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest},
09-12 18:14:06.459  1019  1058 D PackageManager: userId{-1}
09-12 18:14:06.459  1019  1058 D PackageManager: andCode{true}
,09-12 18:14:06.479  8062  8062 E Zygote  : MountEmulatedStorage()
09-12 18:14:06.479  8062  8062 E Zygote  : v2
09-12 18:14:06.479  8062  8062 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:14:06.479  8062  8062 I libpersona: KNOX_SDCARD not a persona
09-12 18:14:06.479  8062  8062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.479  8062  8062 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.479  8062  8062 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.479  1019  1398 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=8062 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 18:14:06.489  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-12 18:14:06.489  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.489  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.489  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.489  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.489  1019  1132 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-12 18:14:06.489  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-12 18:14:06.499  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 18:14:06.499  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,09-12 18:14:06.499  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-12 18:14:06.499  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
09-12 18:14:06.499  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-12 18:14:06.509  8062  8062 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-12 18:14:06.509  8062  8062 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.509  8077  8077 E Zygote  : MountEmulatedStorage()
,09-12 18:14:06.509  8077  8077 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:14:06.509  8077  8077 E Zygote  : v2
09-12 18:14:06.509  8077  8077 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:06.509  8077  8077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
09-12 18:14:06.519  1019  1031 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8077 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-12 18:14:06.519  1019  1031 I ActivityManager: Killing 7508:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,09-12 18:14:06.519  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-12 18:14:06.519  8077  8077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-12 18:14:06.529  8077  8077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-12 18:14:06.529  1019  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.529  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
09-12 18:14:06.529  1181  1181 D KeyguardUpdateMonitor: handleTimeUpdate
09-12 18:14:06.529  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,09-12 18:14:06.549  1181  1181 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
09-12 18:14:06.549  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.549  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.549  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.549  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.549  8047  8047 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 18:14:06.549  8047  8047 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:14:06.549  8047  8047 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:14:06.549  8047  8047 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-12 18:14:06.549  8047  8047 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 18:14:06.549  7801  7801 D BluetoothAdapter: cancelDiscovery
09-12 18:14:06.549  8047  8047 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 18:14:06.559  8047  8047 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 18:14:06.559  1181  1181 D SecKeyguardClockView: HomeTimezone(): 1
,09-12 18:14:06.559  8077  8077 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:06.559  8077  8077 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.569  1181  1181 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 18:14:06.569  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-12 18:14:06.569  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-12 18:14:06.569  8093  8093 I libpersona: KNOX_SDCARD checking this for 10003
09-12 18:14:06.569  8093  8093 E Zygote  : MountEmulatedStorage()
,09-12 18:14:06.569  8093  8093 I libpersona: KNOX_SDCARD not a persona
09-12 18:14:06.569  8093  8093 E Zygote  : v2
09-12 18:14:06.579  8093  8093 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.579  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 18:14:06.579  8093  8093 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 18:14:06.579  8093  8093 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.579  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.579  1019  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8093 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-12 18:14:06.589  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:14:06.589  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:14:06.589  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 18:14:06.589  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.619  8093  8093 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:06.619  8093  8093 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.629  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.629  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.629  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 18:14:06.629  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 18:14:06.639  7943  7943 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-12 18:14:06.639  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.639  8062  8062 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 18:14:06.649  1181  1181 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-12 18:14:06.659  1181  1181 I KeyguardEffectViewController: *** don't update sliding image ***
,09-12 18:14:06.659  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.669  1707  1707 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-12 18:14:06.669  1707  1707 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-12 18:14:06.669  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 18:14:06.669  3278  7883 D BluetoothAdapterProperties: mDiscovering is false
,09-12 18:14:06.669  3278  7883 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,09-12 18:14:06.669  7801  7801 D BluetoothAdapter: cancelDiscovery = true
,09-12 18:14:06.669  7801  7801 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-12 18:14:06.679  1019  1562 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 18:14:06.689  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-12 18:14:06.689  7801  7801 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 18:14:06.689  8077  8077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-12 18:14:06.689  1019  1031 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-12 18:14:06.689  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.689  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:06.689  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:06.689  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-12 18:14:06.709  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-12 18:14:06.709  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.709  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.709  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.709  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.709  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 18:14:06.709  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 18:14:06.709  1019  3813 D LocationManagerService: getProviders()=[passive, gps]
,09-12 18:14:06.719  8117  8117 E Zygote  : MountEmulatedStorage(),
09-12 18:14:06.719  1019  1032 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=8117 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 18:14:06.719  8117  8117 E Zygote  : v2,
09-12 18:14:06.719  8117  8117 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:14:06.719  8117  8117 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 18:14:06.719  8117  8117 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:06.719  1019  3816 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-12 18:14:06.719  1019  3816 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0,
,09-12 18:14:06.729  1019  3816 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:06.729  1019  3816 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:06.729  1019  3816 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 18:14:06.729  8117  8117 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.729  8117  8117 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.739  1019  1523 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,09-12 18:14:06.749  8117  8117 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:06.749  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.749  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.749  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:06.749  1019  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:06.749  8117  8117 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:06.749  8077  8123 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-12 18:14:06.749  8077  8123 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-12 18:14:06.749  8077  8123 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
09-12 18:14:06.749  8077  8123 E AndroidRuntime: Process: com.android.keychain, PID: 8077
09-12 18:14:06.749  8077  8123 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:569)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:561)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:14:06.749  8077  8123 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 18:14:06.749  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-12 18:14:06.759  1858  8128 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-12 18:14:06.759  1858  8128 D AccountUtils: Clearing selected account for com.test.thalitest
,09-12 18:14:06.769  1019  1523 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8135 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
09-12 18:14:06.769  1019  1561 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.keychain
,09-12 18:14:06.769  8135  8135 E Zygote  : MountEmulatedStorage()
09-12 18:14:06.769  8135  8135 E Zygote  : v2
09-12 18:14:06.769  8135  8135 I libpersona: KNOX_SDCARD checking this for 10014
09-12 18:14:06.769  8135  8135 I libpersona: KNOX_SDCARD not a persona
09-12 18:14:06.769  8135  8135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 18:14:06.769  8135  8135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 18:14:06.779  8135  8135 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:14:06.789  1019  1316 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:14:06.789  1019  1316 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:06.789  1019  1316 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:06.789  1019  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:14:06.799  1181  1181 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 18:14:06.799  1019  1031 I ActivityManager: Killing 7541:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-12 18:14:06.809  3278  3356 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 18:14:06.809  1019  8143 E DropBoxManagerService: Can't write: system_app_crash
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 18:14:06.809  1019  8143 E DropBoxManagerService: 	... 5 more
,09-12 18:14:06.819  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-12 18:14:06.819  1019  1514 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:14:06.819  1019  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-12 18:14:06.829  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-12 18:14:06.819  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
09-12 18:14:06.829  8077  8123 I Process : Sending signal. PID: 8077 SIG: 9
09-12 18:14:06.819  1019  1032 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-12 18:14:06.829  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 18:14:06.829  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:06.829  1019  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:06.829  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:14:06.829  1019  1032 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 18:14:06.829  1019  1032 D BatteryService: stay LED for charging
09-12 18:14:06.829  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:14:06.829  8135  8135 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:14:06.829  8135  8135 D ActivityThread: Added TimaKeyStore provider
09-12 18:14:06.829  1181  1181 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-12 18:14:06.829  8047  8047 D NearbySource: Nearby Source Create!
09-12 18:14:06.829  8047  8047 D NearbyContext: Nearby Context Create!
09-12 18:14:06.839  8062  8062 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)

```
