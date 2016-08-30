#### Test 832611203a07957_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-30 17:40:13.424  1017  1135 I TactileAssist: enable value -1
08-30 17:40:13.424  1017  1135 I TactileAssist: internal enable value -1
08-30 17:40:13.424  1017  1135 I TactileAssist: intensity value -1
08-30 17:40:13.424  1017  1135 I TactileAssist: saveAppList value true
08-30 17:40:13.434  6663  6663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:13.434  1017  1135 I TactileAssist: List of disabled apps :
08-30 17:40:13.444  6673  6673 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.444  6673  6673 E Zygote  : v2
08-30 17:40:13.444  6673  6673 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.444  6673  6673 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.444  6673  6673 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
--------- beginning of system
08-30 17:40:13.444  6673  6673 I libpersona: KNOX_SDCARD checking this for 10098
08-30 17:40:13.444  6673  6673 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.444  1017  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6673 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-30 17:40:13.464   319   319 I art     : Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 21.674ms
08-30 17:40:13.464  6673  6673 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.464  6673  6673 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.464  1017  4290 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-30 17:40:13.464  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.464  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.464  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.464  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.474  6663  6663 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.474  6663  6663 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.484   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.789ms
08-30 17:40:13.484  2749  2749 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
08-30 17:40:13.494   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.352ms
08-30 17:40:13.514  6697  6697 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.514  6697  6697 I libpersona: KNOX_SDCARD checking this for 10048
08-30 17:40:13.514  6697  6697 E Zygote  : v2
08-30 17:40:13.514  6697  6697 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.514  6697  6697 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.514  1017  4290 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6697 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-30 17:40:13.514  6697  6697 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.514  6697  6697 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 17:40:13.524  1017  1485 I ActivityManager: Process com.samsung.aasaservice (pid 2781)(adj 0) has died(99,723)
08-30 17:40:13.524,  1017  1485 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-30 17:40:13.534  1017  1339 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-30 17:40:13.534  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-30 17:40:13.534  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.534  1017  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:13.534  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-30 17:40:13.544  3768  6712 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-30 17:40:13.544  3768  3768 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 17:40:13.544  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
08-30 17:40:13.554  3768  3768 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
08-30 17:40:13.554  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:40:13.554  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
08-30 17:40:13.554  6697  6697 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.554  6697  6697 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.554  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.554  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:13.554  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:40:13.554  6673  6673 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
08-30 17:40:13.554  6673  6673 D PackageIntentReceiver: Not GearManger package! 
08-30 17:40:13.554  1017  1859 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-30 17:40:13.554  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.554  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.554  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.554  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.564  6663  6713 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
08-30 17:40:13.574  6716  6716 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.574  6716  6716 E Zygote  : v2
08-30 17:40:13.574  6716  6716 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:13.574  6716  6716 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.574  6716  6716 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.574  1017  1859 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6716 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 17:40:13.584  6716  6716 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.584  6716  6716 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:13.584  1017  4290 I ActivityManager: Killing 6314:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
08-30 17:40:13.584  6663  6713 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-30 17:40:13.584  6663  6713 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:13.584  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.584  6663  6713 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:13.584  6663  6713 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-30 17:40:13.584  1017  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:40:13.584  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
08-30 17:40:13.584  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.584  2749  2749 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
08-30 17:40:13.584  1017  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:13.584  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:40:13.594  1017  4290 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-30 17:40:13.594  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.594  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.594  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.594  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.604  6663  6713 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 17:40:13.604  6663  6713 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:40:13.604  6663  6713 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:40:13.604  6663  6713 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:13.604  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.604  6663  6713 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 17:40:13.604  6716  6716 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.604  6716  6716 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.614  6733  6733 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.614  6733  6733 E Zygote  : v2
08-30 17:40:13.614  6733  6733 I libpersona: KNOX_SDCARD checking this for 10032
08-30 17:40:13.614  6733  6733 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.624  6733  6733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.624  1017  4290 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6733 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:13.624  6733  6733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.624  1017  4290 I ActivityManager: Killing 6179:com.google.android.music:main/u0a108 (adj 15): empty #21
08-30 17:40:13.624  6733  6733 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-30 17:40:13.624  1017  4291 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:40:13.624  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
08-30 17:40:13.634  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.634  1017  4291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:13.634  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:40:13.634  6663  6713 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:40:13.634  6663  6713 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:13.634  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.634  1017  1224 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:40:13.634  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 17:40:13.634  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.634  1017  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:13.634  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:40:13.654  6663  6713 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:40:13.654  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.654  6663  6713 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-30 17:40:13.654  6733  6733 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.654  6733  6733 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.674  6663  6713 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:40:13.674  6663  6713 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:13.674  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.674  6663  6713 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-30 17:40:13.674  6663  6713 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:40:13.674  6663  6713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:40:13.674  6663  6713 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:13.684  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.684  6663  6713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:40:13.684  6663  6713 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:13.694  1017  1458 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
08-30 17:40:13.694  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.694  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.694  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.694  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.694  6663  6713 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-30 17:40:13.694  6663  6713 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:40:13.694  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.694  6663  6713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:40:13.714  6663  6713 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-30 17:40:13.714  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.714  6663  6713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:40:13.714  6663  6713 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:13.714  6748  6748 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.714  6748  6748 E Zygote  : v2
08-30 17:40:13.714  6748  6748 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:13.714  6748  6748 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.714  6748  6748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.724  6748  6748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.724  1017  1458 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6748 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 17:40:13.724  6748  6748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:13.724  1017  1458 I ActivityManager: Killing 6024:com.google.android.talk/u0a102 (adj 15): empty #21
08-30 17:40:13.734  6697  6697 D Compatibility: onReceive() it will make start service
08-30 17:40:13.734  1017  1485 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-30 17:40:13.734  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-30 17:40:13.734  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.734  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:13.734  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
08-30 17:40:13.744  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-30 17:40:13.744  6748  6748 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.744  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.744  6748  6748 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.744  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.744  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.744  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.744  6663  6713 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-30 17:40:13.744  6663  6713 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:13.744  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.744  6663  6713 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:13.754  6663  6713 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-30 17:40:13.754  6733  6764 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-30 17:40:13.754  6733  6764 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-30 17:40:13.754  6765  6765 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.764  6765  6765 E Zygote  : v2
08-30 17:40:13.764  6765  6765 I libpersona: KNOX_SDCARD checking this for 10052
08-30 17:40:13.764  6765  6765 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.764  6765  6765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.764  6765  6765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.764  1017  1030 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6765 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-30 17:40:13.764  6765  6765 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 17:40:13.764  6697  6762 D Compatibility: onHandleIntent()
08-30 17:40:13.774  6697  6762 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10170, android.intent.extra.user_handle=0}]
08-30 17:40:13.774  6697  6762 D Compatibility: found: 2
08-30 17:40:13.774  1017  1485 I ActivityManager: Killing 6038:com.android.vending/u0a26 (adj 15): empty #21
08-30 17:40:13.794  6733  6764 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:40:13.794  6733  6764 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:40:13.794  6733  6764 D SPPClientService: ============PushLog. stop!
08-30 17:40:13.794  6697  6762 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-30 17:40:13.794  6697  6762 D Compatibility: skipping ResolveInfo{14baea27 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-30 17:40:13.794  6697  6762 D Compatibility: considering ResolveInfo{817c4d4 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-30 17:40:13.794  6697  6762 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-30 17:40:13.794  1017  1859 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-30 17:40:13.804  6718  6718 D AndroidRuntime: 
08-30 17:40:13.804  6718  6718 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:40:13.804  6697  6762 D Compatibility: enabling receiver ResolveInfo{f967d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-30 17:40:13.804  6718  6718 D AndroidRuntime: CheckJNI is OFF
08-30 17:40:13.804  6718  6718 D AndroidRuntime: readGMSProperty: start
08-30 17:40:13.804  6718  6718 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:40:13.804  6718  6718 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 17:40:13.804  6718  6718 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:40:13.804  6718  6718 D AndroidRuntime: readGMSProperty: end
08-30 17:40:13.804  6718  6718 D AndroidRuntime: addProductProperty: start
08-30 17:40:13.814  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.814  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.814  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.814  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.814  6765  6765 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.814  6765  6765 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.814  6663  6713 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:40:13.814  6663  6713 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
08-30 17:40:13.814  6663  6713 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:40:13.814  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.814  6663  6713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:40:13.824  6748  6782 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
08-30 17:40:13.824  6748  6782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
08-30 17:40:13.834  6663  6713 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-30 17:40:13.834  6783  6783 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.844  6783  6783 E Zygote  : v2
08-30 17:40:13.844  6783  6783 I libpersona: KNOX_SDCARD checking this for 10039
08-30 17:40:13.844  6783  6783 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.844  6783  6783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.844  6783  6783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.844  1017  1859 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6783 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-30 17:40:13.844  6783  6783 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:13.844  6697  6762 D Compatibility: enabling receiver ResolveInfo{282b5972 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-30 17:40:13.844  1017  4291 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-30 17:40:13.844  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-30 17:40:13.854  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.854  1017  4291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:13.854  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
08-30 17:40:13.854  6663  6713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.854  6748  6748 D AcmsService: Enter Oncreate
08-30 17:40:13.864  1017  1496 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-30 17:40:13.864  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.864  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.864  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.864  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:13.874  6748  6748 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 17:40:13.874  6748  6748 D AcmsService: creating AcmsCore
08-30 17:40:13.874  6748  6748 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-30 17:40:13.874  6748  6748 D AcmsCore: AcmsCore
08-30 17:40:13.884  6697  6762 D Compatibility: enabling receiver ResolveInfo{2fe201c3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-30 17:40:13.884  6805  6805 E Zygote  : MountEmulatedStorage()
08-30 17:40:13.884  6805  6805 E Zygote  : v2
08-30 17:40:13.884  6805  6805 I libpersona: KNOX_SDCARD checking this for 10117
08-30 17:40:13.884  6805  6805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:13.884  6805  6805 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:13.884  6805  6805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:13.884  6697  6762 D Compatibility: enabling receiver ResolveInfo{1f965a40 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-30 17:40:13.894  1017  1496 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6805 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:40:13.884  6805  6805 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 17:40:13.894  6697  6762 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-30 17:40:13.904  1017  1485 I ActivityManager: Killing 6431:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-30 17:40:13.904  6663  6713 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
08-30 17:40:13.914  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 17:40:13.914  6748  6748 D AcmsCore: init
08-30 17:40:13.914  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.914  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:13.914  6748  6748 D AcmsCore: Looper handler is not null
08-30 17:40:13.914  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:40:13.914  6748  6748 D AcmsCore: Post to AcmsCoreHandler
08-30 17:40:13.914  6748  6748 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 17:40:13.914  6748  6748 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-30 17:40:13.914  6748  6748 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-30 17:40:13.914  6748  6802 D AcmsCertificateMngr: AcmsCertificateMngr
08-30 17:40:13.924  6783  6783 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.924  6805  6805 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:13.924  6783  6783 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.924  6805  6805 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:13.924  6748  6802 D AcmsRevocationMngr: AcmsRevocationMngr
08-30 17:40:13.924  6748  6748 D AcmsService: onStartCommand
08-30 17:40:13.924  6748  6748 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
08-30 17:40:13.924  6748  6748 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-30 17:40:13.924  6748  6748 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-30 17:40:13.924  6748  6748 D AcmsService: Incremented Counter Value : onStartCommand
08-30 17:40:13.924  3768  3768 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 17:40:13.934  1017  3835 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-30 17:40:13.934  3768  3768 I ConfigFetchService: launchTask
08-30 17:40:13.934  6748  6802 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-30 17:40:13.954  6718  6718 E AffinityControl: AffinityControl: registerfunction enter
08-30 17:40:13.954  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:40:13.954  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 17:40:13.964  6783  6783 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:40:13.964  6783  6783 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:13.964  6783  6783 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:13.964  6783  6783 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-30 17:40:13.964  6783  6783 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:40:13.964  6783  6783 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:40:13.964  6783  6783 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:13.964  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:13.964  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:13.964  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:40:13.974  6718  6718 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 17:40:13.984  6805  6805 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:13.984  3768  3768 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 17:40:13.984  3768  3768 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-30 17:40:13.994  3768  6822 I PeopleContactsSync: CP2 sync disabled
08-30 17:40:14.004  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-30 17:40:14.004  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 17:40:14.004  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:14.004  1017  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:14.004  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:40:14.004  3768  6821 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WdMvLXs_fvtDY3VFPJIVXM7RSsSNtWpWuYj3P3TqpmJ7Yo0EJj8mbfwhNOdanYXOqoqS8j-Rf26NkbWDo8lPoAtzu7f9_huUjywJIidqB29jsAfeW2fE_b8Jbst_xo7sZRulk0uDvkDIC85txAB9caoMPuQtGtWQqKEsCUm5PfKd7VOxV3GV76Y2V_JzYPi6CWz32ZUQVnKeaJNTQunQztc8zFzmHx73EzkorOW6akaDVtKVI
08-30 17:40:14.014  1017  1030 I PersonaManagerService: PersonaId don't exist
08-30 17:40:14.014  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 17:40:14.014  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:40:14.024  3768  3768 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
08-30 17:40:14.034  6748  6748 D AcmsService: Inside handle Intent
08-30 17:40:14.034  1017  1030 W ActivityManager: mDVFSHelper.acquire()
08-30 17:40:14.034  6748  6748 D AcmsService: App added - package name: com.test.thalitest
08-30 17:40:14.034  6748  6748 D AcmsCore: Post to AcmsCoreHandler
08-30 17:40:14.034  6748  6748 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 17:40:14.034  6748  6748 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-30 17:40:14.034  6748  6748 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
08-30 17:40:14.034  6748  6748 D AcmsService: Decremented Counter Value : handleStartIntent
08-30 17:40:14.034  6748  6748 D AcmsServiceMonitor: Decrementing - Counter value: 2
08-30 17:40:14.034  1017  1030 D FocusedStackFrame: Set to : 0
08-30 17:40:14.044  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 17:40:14.044  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 17:40:14.044  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.044  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.044  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.044  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.064  6828  6828 E Zygote  : MountEmulatedStorage()
08-30 17:40:14.064  6828  6828 E Zygote  : v2
08-30 17:40:14.064  6828  6828 I libpersona: KNOX_SDCARD checking this for 10170
08-30 17:40:14.064  6828  6828 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:14.064  6828  6828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:14.064  1017  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6828 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:40:14.064  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-30 17:40:14.064  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:40:14.064  1017  1030 D InputDispatcher: Focused application set to: xxxx
08-30 17:40:14.064  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 17:40:14.064  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 17:40:14.064  1017  1030 D InputDispatcher: Focus left window: 1487
08-30 17:40:14.064  6828  6828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:14.064   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-30 17:40:14.064  6828  6828 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 17:40:14.074  6718  6718 D AndroidRuntime: Shutting down VM
08-30 17:40:14.084  3768  6821 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-30 17:40:14.114  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-30 17:40:14.114  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-30 17:40:14.114  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:14.114  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:14.114  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:14.124  6828  6828 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:14.124  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-30 17:40:14.134  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:40:14.134  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:40:14.144  1017  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 17:40:14.144  1017  1458 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4155, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 17:40:14.144  1017  1458 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:40:14.144  1017  1458 D BatteryService: stay LED for charging
08-30 17:40:14.144  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 17:40:14.144  1017  1017 I MotionRecognitionService: Plugged
08-30 17:40:14.144  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-30 17:40:14.154  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:40:14.154  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 17:40:14.154  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 17:40:14.154  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
08-30 17:40:14.164  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
08-30 17:40:14.174  3189  3189 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:40:14.174  3189  3326 D HeadsetStateMachine: Disconnected process message: 10
08-30 17:40:14.184  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
08-30 17:40:14.184  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
08-30 17:40:14.284  1017  1029 I art     : Explicit concurrent mark sweep GC freed 138746(7MB) AllocSpace objects, 2(1824KB) LOS objects, 33% free, 23MB/34MB, paused 2.626ms total 191.156ms
,08-30 17:40:14.284  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 17:40:14.284  6718  6718 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-30 17:40:14.284  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-30 17:40:14.284  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:14.284  1017  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-30 17:40:14.284  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:14.294  1017  1017 V ActivityManager: Display changed displayId=0
08-30 17:40:14.284  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:14.304  6607  6607 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-30 17:40:14.314  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 17:40:14.324  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:40:14.334  1017  1859 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-30 17:40:14.334  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-30 17:40:14.334  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:14.334  1017  1859 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:40:14.334  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-30 17:40:14.344  1017  1224 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-30 17:40:14.344  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,08-30 17:40:14.344  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:14.344  1017  1224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:14.344  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-30 17:40:14.344  1017  4291 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,08-30 17:40:14.344  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.354  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.354  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.354  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.364  1017  4291 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6848 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-30 17:40:14.364  6848  6848 E Zygote  : MountEmulatedStorage()
08-30 17:40:14.364  6848  6848 E Zygote  : v2
08-30 17:40:14.364  6848  6848 I libpersona: KNOX_SDCARD checking this for 10014
08-30 17:40:14.364  6848  6848 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:14.374  6848  6848 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:14.374  6848  6848 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:14.374  6848  6848 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:40:14.384  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-30 17:40:14.394  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:14.394  1017  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:14.394  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-30 17:40:14.414  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,08-30 17:40:14.414  1017  3835 I ActivityManager: Killing 6390:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-30 17:40:14.424   257   453 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
,08-30 17:40:14.424   257  1097 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
,08-30 17:40:14.424  6848  6848 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:14.424  6848  6848 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:14.424  1487  1487 V ActivityThread: updateVisibility : ActivityRecord{ac662a6 token=android.os.BinderProxy@fbb1f62 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 17:40:14.424  1487  1487 D Launcher: onTrimMemory. Level: 20
,08-30 17:40:14.434  6474  6474 I Mms/MmsApp:  start initViewCache mms
08-30 17:40:14.434  6474  6474 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1935.30901
08-30 17:40:14.434  6474  6474 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-30 17:40:14.454  6783  6783 D NearbySource: Nearby Source Create!
,08-30 17:40:14.454  6783  6783 D NearbyContext: Nearby Context Create!
,08-30 17:40:14.464  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-30 17:40:14.464  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.464  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.464  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.464  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.494  1017  1135 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6869 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-30 17:40:14.494  6869  6869 E Zygote  : MountEmulatedStorage(),
08-30 17:40:14.494  6869  6869 E Zygote  : v2
08-30 17:40:14.494  6869  6869 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:14.494  6869  6869 I libpersona: KNOX_SDCARD not a persona,
,08-30 17:40:14.504  6869  6869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:40:14.504  6869  6869 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:40:14.524  6869  6869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:14.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:40:14.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-30 17:40:14.544  6869  6869 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-30 17:40:14.544  6869  6869 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:14.564  1017  1042 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6887 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-30 17:40:14.564  1655  4313 I art     : Explicit concurrent mark sweep GC freed 13047(616KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.148ms total 165.851ms
,08-30 17:40:14.564  6887  6887 E Zygote  : MountEmulatedStorage(),
08-30 17:40:14.564  6887  6887 E Zygote  : v2
08-30 17:40:14.564  6887  6887 I libpersona: KNOX_SDCARD checking this for 1000
,08-30 17:40:14.564  6887  6887 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:14.564  6887  6887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:40:14.574  1017  1496 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup,
08-30 17:40:14.574  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
08-30 17:40:14.574  6887  6887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:14.574  6828  6828 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-30 17:40:14.584  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:14.584  1017  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:14.584  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
08-30 17:40:14.584  6887  6887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:14.584  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup,
08-30 17:40:14.584  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,08-30 17:40:14.594  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:40:14.594  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:14.594  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,08-30 17:40:14.594  1017  1458 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast,
,08-30 17:40:14.594  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:40:14.594  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.594  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.594  1017  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.604   319   319 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.165ms total 43.625ms
,08-30 17:40:14.604  6887  6887 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-30 17:40:14.614  6887  6887 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:14.624   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 18.861ms,
,08-30 17:40:14.644   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.821ms,
,08-30 17:40:14.684  6908  6908 E Zygote  : MountEmulatedStorage(),
08-30 17:40:14.684  6908  6908 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:14.684  6908  6908 E Zygote  : v2
08-30 17:40:14.684  6908  6908 I libpersona: KNOX_SDCARD not a persona,
08-30 17:40:14.684  6908  6908 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:14.684  6908  6908 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:14.684  6908  6908 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:14.694  1017  1458 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6908 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-30 17:40:14.704   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-30 17:40:14.704   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:14.704  6828  6828 I cr.library_loader: Time to load native libraries: 25 ms (timestamps 6481-6506)
08-30 17:40:14.704  6828  6828 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 17:40:14.704  6783  6783 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-30 17:40:14.714  6783  6783 D SLinkSource: Samsung link source created
,08-30 17:40:14.724  1017  1496 I ActivityManager: Killing 6452:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-30 17:40:14.724  6869  6869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,08-30 17:40:14.724  1017  1496 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-30 17:40:14.724  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-30 17:40:14.724  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:14.724  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:14.724  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-30 17:40:14.734  6908  6908 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:14.734  6908  6908 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:14.744  1017  1859 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-30 17:40:14.744  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.744  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.744  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.744  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.754  6887  6887 D AASAservice: onCreate()
08-30 17:40:14.754  6887  6887 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,08-30 17:40:14.764  1017  1859 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6927 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-30 17:40:14.774  6927  6927 E Zygote  : MountEmulatedStorage()
08-30 17:40:14.774  1017  1339 I ActivityManager: Killing 6474:com.android.mms/u0a41 (adj 15): empty #21
08-30 17:40:14.774  6927  6927 E Zygote  : v2
08-30 17:40:14.774  6927  6927 I libpersona: KNOX_SDCARD checking this for 10087
08-30 17:40:14.774  6927  6927 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:14.774  6927  6927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:14.774  6927  6927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:14.774  6927  6927 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:40:14.784  3768  6826 W BaseAppContext: Using Auth Proxy for data requests.
08-30 17:40:14.784  3768  6826 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:40:14.784  6908  6908 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-30 17:40:14.784  6908  6908 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 17:40:14.784  6908  6908 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 17:40:14.794  2749  2749 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
,08-30 17:40:14.824  1017  1485 D CountryDetector: No listener is left
,08-30 17:40:14.834  6828  6828 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10041d79}
,08-30 17:40:14.834  6828  6828 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 17:40:14.834  6828  6828 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:40:14.834  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:14.834  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{29e3b3c2 u0 com.test.thalitest/.MainActivity t163}
,08-30 17:40:14.834  6927  6927 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:14.854  3768  6821 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-30 17:40:14.854  3768  6821 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:40:14.854  3768  6821 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 17:40:14.854  3768  6821 I System.out: (HTTPLog)-Thread-620-246552781: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 17:40:14.854  3768  6821 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:40:14.854   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:40:14.854   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 17:40:14.864  3768  6826 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:40:14.874  6908  6908 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 17:40:14.874  6908  6908 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:40:14.874  6908  6908 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 17:40:14.874  6908  6908 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,08-30 17:40:14.874  1017  4290 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,08-30 17:40:14.884  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.884  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.884  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:14.884  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:14.894  6828  6828 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 17:40:14.904  6947  6947 E Zygote  : MountEmulatedStorage()
08-30 17:40:14.904  6947  6947 I libpersona: KNOX_SDCARD checking this for 10026
08-30 17:40:14.904  6947  6947 E Zygote  : v2
08-30 17:40:14.904  6947  6947 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:14.904  6947  6947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:14.904  6947  6947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:14.904  1017  4290 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6947 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:14.904  6947  6947 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 17:40:14.904  1017  4290 I ActivityManager: Killing 6502:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-30 17:40:14.914  1017  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:40:14.914  6783  6943 D ContactProvider: getAllContactInfoList Start
,08-30 17:40:14.924  1017  1029 D LocationManagerService: getProviders()=[passive, gps]
,08-30 17:40:14.934  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:40:14.934  1017  1224 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:40:14.934  6783  6783 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-30 17:40:14.934  6947  6947 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:14.934  6947  6947 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:14.954  3768  6826 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:40:14.964  3768  6826 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:40:14.974  6828  6828 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 17:40:14.984  6783  6943 D ContactProvider: getAllContactInfoList End
,08-30 17:40:14.984  6783  6943 I syncContacts: thread: 1248, sync time = 157
,08-30 17:40:15.004  1017  1339 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-30 17:40:15.014  1017  1859 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-30 17:40:15.044  6765  6849 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 17:40:15.064  1017  4290 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-30 17:40:15.064  1017  4290 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,08-30 17:40:15.064  1017  4290 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:15.064  1017  4290 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:15.064  1017  4290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-30 17:40:15.074  3768  6826 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 17:40:15.084  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.084  1017  4291 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,08-30 17:40:15.084  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.084  3768  6821 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:40:15.084  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:15.084  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.084  3768  6821 I qtaguid : Tagging socket 96 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3768, getuid(): 10011
08-30 17:40:15.084  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.104  6976  6976 E Zygote  : MountEmulatedStorage(),
08-30 17:40:15.104  6976  6976 E Zygote  : v2
08-30 17:40:15.104  6976  6976 I libpersona: KNOX_SDCARD checking this for 10041
08-30 17:40:15.104  6976  6976 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:15.104  6976  6976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:40:15.104  6976  6976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:15.104  1017  4291 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6976 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
08-30 17:40:15.104  1017  4291 I ActivityManager: Killing 6520:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-30 17:40:15.114  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.114  6976  6976 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 17:40:15.114  1017  1458 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-30 17:40:15.114  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-30 17:40:15.124  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:15.124  1017  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:15.124  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-30 17:40:15.144  6976  6976 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:15.144  6976  6976 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:15.194  6976  6976 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-30 17:40:15.194  6976  6976 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:15.194  6976  6976 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:15.194  6976  6976 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:15.194  6976  6976 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-30 17:40:15.214  6947  6947 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 17:40:15.224  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.234  6976  6976 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-30 17:40:15.264  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-30 17:40:15.264  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:15.264  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:15.264  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:15.264  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.274  1017  1029 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7002 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-30 17:40:15.284  7002  7002 E Zygote  : MountEmulatedStorage()
08-30 17:40:15.284  7002  7002 E Zygote  : v2
08-30 17:40:15.284  7002  7002 I libpersona: KNOX_SDCARD checking this for 10148
08-30 17:40:15.284  7002  7002 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:15.284  7002  7002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:15.284  7002  7002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:15.284  7002  7002 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:15.294  1017  1135 I ActivityManager: Killing 6536:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-30 17:40:15.294  6828  6828 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:40:15.294  6828  6828 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:40:15.294  6828  6828 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:40:15.294  6828  6828 I Adreno-EGL: Local Branch: 
08-30 17:40:15.294  6828  6828 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:40:15.294  6828  6828 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:40:15.294  6828  6828 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:40:15.294  3768  6821 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3768, getuid(): 10011
,08-30 17:40:15.324  1017  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:40:15.324  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:15.324  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:15.324  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-30 17:40:15.334  1017  1469 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:40:15.334  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-30 17:40:15.334  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:15.334  1017  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:40:15.344  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:15.344  7002  7002 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:15.344  7002  7002 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:15.394  1017  1029 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6536, ws=null) (elapsedTime=2676)
,08-30 17:40:15.414  7002  7002 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-30 17:40:15.424  1017  3835 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast,
,08-30 17:40:15.424  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.434  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.434  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:15.434  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.444  7029  7029 E Zygote  : MountEmulatedStorage(),
08-30 17:40:15.444  7029  7029 E Zygote  : v2
08-30 17:40:15.454  7029  7029 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:15.454  7029  7029 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:15.454  7029  7029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:15.454  1017  3835 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7029 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 17:40:15.454  1017  3835 I ActivityManager: Killing 6557:com.wsomacp/u0a23 (adj 15): empty #21
,08-30 17:40:15.454  7029  7029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:15.454  7029  7029 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:15.454  1017  4291 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:40:15.464  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:15.464  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.464  1017  4291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:40:15.464  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:15.484  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.484  1017  1339 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:40:15.494  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:15.494  1017  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:15.494  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-30 17:40:15.494  7029  7029 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:15.494  7029  7029 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:15.504  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.504  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.514  6976  6976 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 217.971ms
,08-30 17:40:15.524  7029  7029 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,08-30 17:40:15.544  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.544  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.554  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.554  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-30 17:40:15.554  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:15.554  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:40:15.554  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:15.554  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.554  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.554  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.564  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.564  6828  6828 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 17:40:15.564  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.574  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.574  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.574  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.574  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.574  6947  6947 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 17:40:15.584  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 17:40:15.584  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 17:40:15.594  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 17:40:15.594  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 17:40:15.604  6947  6947 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 17:40:15.614  6947  6947 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 17:40:15.634  6976  6976 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 110.755ms
,08-30 17:40:15.634  6976  7059 D Mms/ArtClassLoader: init before art
,08-30 17:40:15.654  3768  6826 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 162.926ms
,08-30 17:40:15.654  6976  6976 D Mms/TelephonyPermission: start operation mode monitor
,08-30 17:40:15.654  1017  3835 E EdmStorageProvider: Admin not in database, something went wrong
,08-30 17:40:15.654  1017  1469 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:40:15.654  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-30 17:40:15.664  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:15.664  1017  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-30 17:40:15.664  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:15.674  6976  6976 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 17:40:15.674  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.674  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:15.674  6947  6947 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 17:40:15.684  1017  1224 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-30 17:40:15.684  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.684  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.684  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.684  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.704  7060  7060 E Zygote  : MountEmulatedStorage()
08-30 17:40:15.704  7060  7060 E Zygote  : v2
08-30 17:40:15.704  7060  7060 I libpersona: KNOX_SDCARD checking this for 10152
,08-30 17:40:15.704  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:15.704  1017  1224 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7060 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-30 17:40:15.704  1017  1224 I ActivityManager: Killing 6575:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-30 17:40:15.704  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:40:15.704  6976  6976 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms,
08-30 17:40:15.704  6976  6976 D Mms/TelephonyPermission: isDefault true
,08-30 17:40:15.704  6976  6976 D Mms/MmsApp: onCreate() com.android.mms,
,08-30 17:40:15.714  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:40:15.714  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:15.744  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:15.754  7060  7060 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:15.754  6765  6849 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 712 ms] updated apps [took 712 ms] 
,08-30 17:40:15.764  1017  4291 I ActivityManager: Killing 6264:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-30 17:40:15.784  1017  1496 I ActivityManager: Killing 6283:com.android.calendar/u0a131 (adj 15): empty #21
,08-30 17:40:15.804  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:40:15.814  6828  6828 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 17:40:15.824  6976  6976 D Mms/MmsApp: [start]    initCountryIso consume time = 589.157968
,08-30 17:40:15.834  7060  7060 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-30 17:40:15.834  7060  7060 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,08-30 17:40:15.834  1017  3835 D CountryDetector: The first listener is added
,08-30 17:40:15.844  6828  6828 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-30 17:40:15.844  6828  6828 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 17:40:15.864  6828  6828 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 17:40:15.864  6976  6976 D Mms/MmsApp: [end]    initCountryIso consume time = 41.858333
08-30 17:40:15.864  6976  6976 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.13198
,08-30 17:40:15.864  6947  6947 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 17:40:15.864  1017  1135 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,08-30 17:40:15.864  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-30 17:40:15.864  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:15.864  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:15.864  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-30 17:40:15.874  7060  7060 I TapandpayWidget:Utils: Clear T&P info.
,08-30 17:40:15.874  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:40:15.874  6976  6976 D Mms/MmsConfig: before partial update
,08-30 17:40:15.884  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:40:15.884  7060  7060 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-30 17:40:15.884  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-30 17:40:15.884  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.884  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:15.884  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:15.884  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:15.904  7084  7084 E Zygote  : MountEmulatedStorage()
,08-30 17:40:15.904  7084  7084 E Zygote  : v2
08-30 17:40:15.904  7084  7084 I libpersona: KNOX_SDCARD checking this for 10009
08-30 17:40:15.904  7084  7084 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:15.904  7084  7084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:15.904  1017  1030 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7084 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-30 17:40:15.914  7084  7084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 17:40:15.914  6947  6947 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 17:40:15.914  7084  7084 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 17:40:15.924  1017  4291 I ActivityManager: Killing 6594:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-30 17:40:15.934   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb79fe7c8
08-30 17:40:15.934   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,08-30 17:40:15.934   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 17:40:15.934   272   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1214257864)
,08-30 17:40:15.954  7084  7084 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-30 17:40:15.954  7084  7084 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:15.974  6828  7101 D OpenGLRenderer: Render dirty regions requested: true,
,08-30 17:40:15.984  1017  1480 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
08-30 17:40:15.984  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 17:40:15.984  1017  1480 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-30 17:40:15.984  1017  1480 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 17:40:15.984  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0,
08-30 17:40:15.984  6828  6828 V ActivityThread: updateVisibility : ActivityRecord{57bf8a0 token=android.os.BinderProxy@3d7c78d2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 17:40:15.984  6828  7027 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-30 17:40:15.984  6976  6976 D Mms/MmsConfig: Load Resize quality : 80
,08-30 17:40:15.994  6828  6828 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
08-30 17:40:15.994  6828  6828 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 17:40:16.014   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-30 17:40:16.024   272   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-30 17:40:16.024   272   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 17:40:16.024   272   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1214257864) wakelock released: 1, error no: 0
08-30 17:40:16.024   272   313 I rmt_storage: 
,08-30 17:40:16.024  6976  6976 D EasySignUpManager_1.0.1: serviceId : 1, features : -1,
08-30 17:40:16.024  6976  6976 D EasySignUpManager_1.0.1: isAuth is false
08-30 17:40:16.024  6976  6976 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
08-30 17:40:16.024   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb79fe7c8
,08-30 17:40:16.024  1017  1339 D InputDispatcher: Focus entered window: 6828
,08-30 17:40:16.034  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-30 17:40:16.034  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:40:16.034  6828  6828 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 17:40:16.034  6828  7101 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 17:40:16.034  6828  7101 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-30 17:40:16.034  6828  7101 D OpenGLRenderer: Enabling debug mode 0
,08-30 17:40:16.054  1443  1468 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6976,
,08-30 17:40:16.064  1443  1468 D TP/MmsSmsProvider: match 2117:Elapsed time : 5.994 ms
,08-30 17:40:16.064  1017  1859 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 17:40:16.074  1017  7107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-30 17:40:16.074  1178  1178 D PanelView: There is/are notification(s) 
08-30 17:40:16.084  1017  1047 I ActivityManager: Displayed Component not be shown by security: +1s754ms (total +2s48ms)
08-30 17:40:16.084  1017  1047 W ActivityManager: mDVFSHelper.release()
08-30 17:40:16.084  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29e3b3c2 u0 com.test.thalitest/.MainActivity t163} time:97889
08-30 17:40:16.094  6947  7102 D Ads     : Skipping gmscore version check
,08-30 17:40:16.104  6976  6976 D EasySignUpManager_1.0.1: isAuth is false
08-30 17:40:16.104  6976  6976 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,08-30 17:40:16.104  6976  6976 E CscParser: mps_code.dat does not exist
08-30 17:40:16.104  1017  3351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-30 17:40:16.104  6828  6828 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-30 17:40:16.104  6976  6976 E CscParser: customer_path =/system/csc/customer.xml
08-30 17:40:16.104  6976  6976 E CscParser: fileName + /system/csc/customer.xml
08-30 17:40:16.104  6828  6828 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d7c78d2 time:97902
,08-30 17:40:16.104   257   450 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-30 17:40:16.104   257  1097 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-30 17:40:16.124  6976  6976 E CscParser: mps_code.dat does not exist
08-30 17:40:16.124  6976  6976 E CscParser: customer_path =/system/csc/customer.xml
08-30 17:40:16.124  6976  6976 E CscParser: fileName + /system/csc/customer.xml
,08-30 17:40:16.144  6976  6976 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-30 17:40:16.144  6976  6976 D Mms/MmsConfig:  enable multiwindow = false
08-30 17:40:16.144  1017  1339 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-30 17:40:16.174  6976  6976 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-30 17:40:16.174  6976  6976 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-30 17:40:16.204   290   290 E SMD     : DCD OFF
,08-30 17:40:16.224  1854  1854 I SamsungIME: getCurrentCandidateView
,08-30 17:40:16.234  3768  3785 W art     : Suspending all threads took: 12.906ms
,08-30 17:40:16.254  3768  6821 I qtaguid : Untagging socket 96
,08-30 17:40:16.264  3768  3768 I ConfigFetchService: fetch service done; releasing wakelock
,08-30 17:40:16.264  1017  3835 I art     : Explicit concurrent mark sweep GC freed 20827(1152KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 23MB/34MB, paused 2.738ms total 145.935ms
08-30 17:40:16.264  1017  3835 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:40:16.264  3768  3768 I ConfigFetchService: stopping self
08-30 17:40:16.264  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:16.264  1017  3835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:16.264  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-30 17:40:16.274  1017  4291 I ActivityManager: Killing 6625:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-30 17:40:16.274  6976  6976 D Mms/MmsConfig: [end]    init() consume time = 416.981718
,08-30 17:40:16.284  6976  6976 D Mms/Contact: [start]    init() consume time = 1.82224
,08-30 17:40:16.294  1443  1470 D TP/MmsSmsProvider: query,matched:13, calling pid = 6976
,08-30 17:40:16.294  1443  1470 D TP/MmsSmsProvider: match 13:Elapsed time : 1.128 ms
,08-30 17:40:16.314  6947  6947 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 17:40:16.314  6976  6976 D Mms/Contact: [end]    init consume time = 33.894427
,08-30 17:40:16.344  6976  6976 D Mms/MethodReflector: getSubId is called
08-30 17:40:16.344  6976  6976 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-30 17:40:16.344  6976  7117 D Mms/DraftCache: [start]    rebuildCache consume time = 21.238594
08-30 17:40:16.344  6976  6976 D Mms/MethodReflector: getTelephonyProperty is called
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: auto download without roaming -> true
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-30 17:40:16.344  6976  6976 D Mms/MethodReflector: getSubId is called
08-30 17:40:16.344  6976  6976 D Mms/MethodReflector: getDefaultSmsSubId is called
08-30 17:40:16.344  6976  6976 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-30 17:40:16.344  6976  6976 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-30 17:40:16.344  6976  6976 D Mms/MethodReflector: getTelephonyProperty is called
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: auto download without roaming -> true
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: auto download during roaming secondary -> false
08-30 17:40:16.344  6976  6976 D Mms/DownloadManager: mAutoDownload ------> true
08-30 17:40:16.344  1443  2164 D TP/MmsSmsProvider: query,matched:12, calling pid = 6976
08-30 17:40:16.354  1443  2164 D TP/MmsSmsProvider: match 12:Elapsed time : 4.202 ms
08-30 17:40:16.374  6976  7117 D Mms/DraftCache: [end]    rebuildCache consume time = 34.427604
08-30 17:40:16.384  6927  6968 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-30 17:40:16.384  6927  6968 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:40:16.384  6927  6968 I GAv4    :   adb logcat -s GAv4
08-30 17:40:16.404  6828  6828 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6828
08-30 17:40:16.414  6976  7059 D Mms/ArtClassLoader: init [DONE] art
08-30 17:40:16.414  6976  6976 D ComposerPerformance: 1472571616428 ms / [DONE] Composer constructor
08-30 17:40:16.424  6976  6976 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-30 17:40:16.424  6976  6976 I Mms/ReservationManager: ReservationManager()
08-30 17:40:16.424  6976  6976 I Mms/ReservationManager: resetAfterConnected()
08-30 17:40:16.424  1443  1875 D TP/MmsSmsProvider: query,matched:7, calling pid = 6976
08-30 17:40:16.434  1443  1875 D TP/MmsSmsProvider: match 7:Elapsed time : 1.649 ms
08-30 17:40:16.434  6976  7121 D Mms/Conversation: [start]    init() consume time = 60.194687
08-30 17:40:16.434  6927  6968 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-30 17:40:16.434  1017  1469 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-30 17:40:16.444  1443  1470 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-30 17:40:16.444  6976  6976 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-30 17:40:16.444  1443  1470 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-30 17:40:16.444  1443  1470 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-30 17:40:16.444  1443  1470 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-30 17:40:16.444  6927  6968 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-30 17:40:16.444  6976  6976 D Mms/MmsApp: [end]    onCreate() consume time = 17.328698
08-30 17:40:16.464  1443  1470 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-30 17:40:16.464  1443  1470 D TP/MmsSmsProvider: need read changed broadcast:false
08-30 17:40:16.464  6976  7121 D Mms/Conversation: [end]    init consume time = 14.527083
08-30 17:40:16.464  6976  6976 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-30 17:40:16.474  6976  6976 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-30 17:40:16.474  6976  7121 D Mms/MessagingNotification: [start]    init() consume time = 8.545521
08-30 17:40:16.474  6976  6976 D Mms/MethodReflector: getSubId is called
08-30 17:40:16.474  6976  6976 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-30 17:40:16.484  6976  6976 D Mms/MethodReflector: getTelephonyProperty is called
08-30 17:40:16.484  6976  6976 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-30 17:40:16.484  6976  6976 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 17:40:16.484  6976  6976 D Mms/DownloadManager: auto download without roaming -> true
08-30 17:40:16.484  6976  6976 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-30 17:40:16.484  6976  6976 D Mms/DownloadManager: mAutoDownload ------> true
08-30 17:40:16.484  6976  7121 D Mms/MessagingNotification: [end]    init consume time = 13.859271
08-30 17:40:16.484  6976  6976 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-30 17:40:16.484  1017  1339 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-30 17:40:16.494  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-30 17:40:16.494  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:16.494  1017  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:16.494  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-30 17:40:16.494  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-30 17:40:16.494  6927  7123 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-30 17:40:16.494  1443  2164 D TP/MmsSmsProvider: query,matched:0, calling pid = 6976
08-30 17:40:16.494  1443  2164 V TP/MmsSmsProvider: getSimpleConversations entered.
08-30 17:40:16.504  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.504  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.504  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.504  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.504  1443  2164 D TP/MmsSmsProvider: match 0:Elapsed time : 2.547 ms
08-30 17:40:16.504  6976  7126 D Mms/Synchronizer: [start]    doSync consume time = 14.993177
08-30 17:40:16.504  6976  7125 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 3.435781
08-30 17:40:16.514  7128  7128 E Zygote  : MountEmulatedStorage()
08-30 17:40:16.514  7128  7128 E Zygote  : v2
08-30 17:40:16.514  7128  7128 I libpersona: KNOX_SDCARD checking this for 10042
08-30 17:40:16.514  7128  7128 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:16.514  7128  7128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:16.514  7128  7128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:16.524  1017  1135 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7128 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-30 17:40:16.524  7128  7128 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-30 17:40:16.524  6927  6968 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-30 17:40:16.534  1443  1468 D TP/MmsSmsProvider: update, matched:300, calling pid = 6976
08-30 17:40:16.534  1443  1468 V TP/MmsSmsProvider: syncDBData start
08-30 17:40:16.534  1443  1468 V TP/MmsSmsProvider: syncDBData sms end
08-30 17:40:16.534  1443  1468 V TP/MmsSmsProvider: syncDBData mms end
08-30 17:40:16.534  1443  1468 V TP/MmsSmsProvider: syncDBData end
08-30 17:40:16.534  1017  1496 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-30 17:40:16.534  1443  1875 D TP/MmsSmsProvider: query,matched:400, calling pid = 6976
08-30 17:40:16.534  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.544  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.544  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.544  1017  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.544  6976  7136 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-30 17:40:16.544  6976  7136 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-30 17:40:16.544  1854  1854 D SamsungIME: Dismiss ExpandCandiate
08-30 17:40:16.554  7145  7145 E Zygote  : MountEmulatedStorage()
08-30 17:40:16.554  7128  7128 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:16.554  7145  7145 E Zygote  : v2
08-30 17:40:16.554  7128  7128 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:16.554  7145  7145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:16.554  7145  7145 I libpersona: KNOX_SDCARD checking this for 10068
08-30 17:40:16.554  7145  7145 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:16.564  6976  7126 D Mms/Synchronizer: [end]    doSync consume time = 62.619323
08-30 17:40:16.564  1017  1496 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7145 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-30 17:40:16.574  7145  7145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:16.574  7145  7145 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 17:40:16.574  1017  1339 I ActivityManager: Killing 6641:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-30 17:40:16.574  7128  7128 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:16.574  7128  7128 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:40:16.574  7128  7128 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:40:16.584  6976  7125 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 15.048959
08-30 17:40:16.594  7145  7145 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:16.594  7145  7145 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:16.674  1017  4290 I ActivityManager: Killing 6607:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-30 17:40:16.694  7128  7128 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-30 17:40:16.724  1017  1480 I ActivityManager: Killing 6663:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-30 17:40:16.724  6927  6941 W art     : Suspending all threads took: 8.444ms
08-30 17:40:16.724  1017  1056 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-30 17:40:16.724  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-30 17:40:16.724  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.724  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.724  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.724  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.744  7162  7162 E Zygote  : MountEmulatedStorage()
08-30 17:40:16.754  7162  7162 E Zygote  : v2
08-30 17:40:16.754  7162  7162 I libpersona: KNOX_SDCARD checking this for 10003
08-30 17:40:16.754  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:16.754  7162  7162 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:16.754  7162  7162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:16.754  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7162 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 17:40:16.754  7162  7162 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:16.754  7145  7145 D BadgeProvider: onCreate
08-30 17:40:16.754  7145  7145 D BadgeProvider: DatabaseHelper
08-30 17:40:16.764   319   319 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 21.471ms
08-30 17:40:16.784   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 18.930ms
08-30 17:40:16.784  6976  7121 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-30 17:40:16.794  7162  7162 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:16.794  7162  7162 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:16.794  6828  6828 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 17:40:16.804   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 19.185ms
08-30 17:40:16.804  1443  1470 D TP/SmsProvider: query,matched:26, calling pid = 6976
08-30 17:40:16.814  1443  1470 D TP/SmsProvider: match 26:Elapsed time : 2.759 ms
08-30 17:40:16.814  1443  1875 D TP/MmsSmsProvider: query,matched:6, calling pid = 6976
08-30 17:40:16.824  1443  1875 D TP/MmsSmsProvider: match 6:Elapsed time : 0.869 ms
08-30 17:40:16.834   286   286 E installd: system dir 0 : /system/app/
08-30 17:40:16.834   286   286 E installd: system dir 1 : /system/priv-app/
08-30 17:40:16.834   286   286 E installd: system dir 2 : /vendor/app/
08-30 17:40:16.834   286   286 E installd: system dir 3 : /oem/app/
08-30 17:40:16.834  3768  4301 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-30 17:40:16.874  1017  4291 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-30 17:40:16.874  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.874  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.874  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.874  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.894  1017  4291 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7178 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-30 17:40:16.894  7178  7178 E Zygote  : MountEmulatedStorage()
08-30 17:40:16.894  7178  7178 E Zygote  : v2
08-30 17:40:16.894  7178  7178 I libpersona: KNOX_SDCARD checking this for 10023
08-30 17:40:16.894  7178  7178 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:16.894  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:16.894  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:16.894  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:16.914  1017  1056 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-30 17:40:16.924  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:16.924  7178  7178 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:16.934  6828  7111 D jxcore_app_log: JniHelper::setJavaVM(0xb8e012b0), pthread_self() = -1187451360
08-30 17:40:16.944  6828  7111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:40:16.944  6828  7111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:40:16.944  6828  7111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:40:16.944  6828  7111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:40:16.944  6828  7111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:40:16.944  6828  7111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@111d80f7 added. We now have 1 listener(s)
08-30 17:40:16.944  3768  4301 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-30 17:40:16.954  6828  7111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-30 17:40:16.954  6828  7111 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:16.954  6828  7111 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:16.954  6828  7111 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:40:16.954  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:40:16.964  6828  7111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2430ba82 added. We now have 1 listener(s)
08-30 17:40:16.964  6828  7111 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:16.964  1854  1854 I SamsungIME: getDebugLevel  : 0x4f4c
08-30 17:40:16.964  1017  1224 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-30 17:40:16.964  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.964  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.964  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.964  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:16.974  6828  7111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:40:16.974  6828  7111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:40:16.974  6828  7111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:40:16.974  6828  7111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:40:16.974  6828  7111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 17:40:16.984  7199  7199 E Zygote  : MountEmulatedStorage()
08-30 17:40:16.984  7199  7199 E Zygote  : v2
08-30 17:40:16.984  7199  7199 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:16.984  7199  7199 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:16.984  7199  7199 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:16.984  1017  1224 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7199 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 17:40:16.984  1017  1224 I ActivityManager: Killing 6673:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-30 17:40:16.984  7199  7199 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:16.984  6828  7111 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:16.994  7199  7199 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:16.994  6828  7111 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-30 17:40:17.004  6828  7111 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:17.004  6828  7111 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:17.004  6828  7111 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:40:17.004  6828  7111 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:17.004  6828  7111 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:40:17.004  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:17.024  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:17.024  1017  1859 I ActivityManager: Killing 5047:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-30 17:40:17.034  7199  7199 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:17.034  7199  7199 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:17.044  7178  7178 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-30 17:40:17.084  6976  7121 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-30 17:40:17.084  6828  6828 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:40:17.104  1854  1854 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 17:40:17.114  7199  7199 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-30 17:40:17.114  7199  7199 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-30 17:40:17.114  1017  1485 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,08-30 17:40:17.124  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-30 17:40:17.124  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:17.124  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:17.124  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-30 17:40:17.124  1017  1480 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-30 17:40:17.134  1854  1854 I SamsungIME: KeybaordView init() : load resources
,08-30 17:40:17.134  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-30 17:40:17.134  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:17.134  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:17.134  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:17.134  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:17.144  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false,
08-30 17:40:17.144  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-30 17:40:17.154  7218  7218 E Zygote  : MountEmulatedStorage(),
08-30 17:40:17.154  7218  7218 E Zygote  : v2
08-30 17:40:17.154  7218  7218 I libpersona: KNOX_SDCARD checking this for 10130
08-30 17:40:17.154  7218  7218 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:17.154  7218  7218 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:17.154  7218  7218 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:17.154  7218  7218 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-30 17:40:17.164  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7218 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-30 17:40:17.164  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-30 17:40:17.184  7199  7199 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-30 17:40:17.184  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-30 17:40:17.184  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-30 17:40:17.194  7178  7178 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-30 17:40:17.194  1854  1854 I SamsungIME: getCurrentKeyboard
08-30 17:40:17.194  1854  1854 I SamsungIME: getTextKeyboard
,08-30 17:40:17.204  7218  7218 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:17.204  7218  7218 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:17.204  3768  4301 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-30 17:40:17.234  1854  1854 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 17:40:17.234  7218  7218 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:40:17.234  7218  7218 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-30 17:40:17.234  7199  7217 E FilterInstaller: installFilters
,08-30 17:40:17.244  7199  7217 E FilterInstaller: There is no requred permission
,08-30 17:40:17.254  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-30 17:40:17.254  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:17.254  1017  4291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:17.254  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:17.254  1017  1485 I ActivityManager: Killing 6716:com.samsung.helphub/1000 (adj 15): empty #21
,08-30 17:40:17.254  1017  1485 I ActivityManager: Killing 6733:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-30 17:40:17.274  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-30 17:40:17.274  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:17.274  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:17.274  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:17.274  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:17.284  7233  7233 E Zygote  : MountEmulatedStorage()
08-30 17:40:17.284  7233  7233 E Zygote  : v2
,08-30 17:40:17.294  7233  7233 I libpersona: KNOX_SDCARD checking this for 10131
,08-30 17:40:17.294  7233  7233 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:17.294  7233  7233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:17.294  6927  7194 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 17:40:17.294  6927  7194 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:40:17.294  7233  7233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 17:40:17.294  1017  1029 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7233 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-30 17:40:17.294  7233  7233 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:40:17.304  1017  1029 I ActivityManager: Killing 6697:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-30 17:40:17.324  7233  7233 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:17.324  7233  7233 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:17.344  7233  7233 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 17:40:17.344  7233  7233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:17.344  7233  7233 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:40:17.354  6927  7194 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-30 17:40:17.384  2668  2677 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-30 17:40:17.394  1017  1458 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-30 17:40:17.394  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-30 17:40:17.394  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:17.394  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:17.394  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-30 17:40:17.424  1017  3835 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-30 17:40:17.424  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-30 17:40:17.424  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:17.424  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:17.424  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-30 17:40:17.444  1017  1339 I ActivityManager: Killing 6783:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-30 17:40:17.454  6927  7194 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 17:40:17.454  6927  7194 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e387cb7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-30 17:40:17.454  6927  7194 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 17:40:17.634  6828  7213 W jxcore-log: Initializing JXcore engine
08-30 17:40:17.634  6828  7213 W jxcore-log: JXcore engine is ready
,08-30 17:40:17.694  1959  1959 E audit   : type=1400 msg=audit(1472571617.694:205): avc:  denied  { ioctl } for  pid=7213 comm="Thread-1280" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 17:40:17.694  1959  1959 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:17.694  1959  1959 E audit   : type=1300 msg=audit(1472571617.694:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e4bd8f8 items=0 ppid=319 ppcomm=main pid=7213 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1280" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 17:40:17.694  1959  1959 E audit   : type=1320 msg=audit(1472571617.694:205): 
,08-30 17:40:17.704  6828  7213 W jxcore-log: Starting JXcore engine
,08-30 17:40:17.814  6828  7213 W jxcore-log: Platform android
08-30 17:40:17.814  6828  7213 W jxcore-log: 
08-30 17:40:17.814  6828  7213 W jxcore-log: Process ARCH arm
08-30 17:40:17.814  6828  7213 W jxcore-log: 
,08-30 17:40:18.014  6828  7213 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:40:18.014  6828  7213 I jxcore-log: 
,08-30 17:40:18.014  6828  7213 W jxcore-log: JXcore engine is started
,08-30 17:40:18.024  6828  7111 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:40:18.024  6828  6828 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:40:18.454  6976  6976 I Mms/MmsApp:  start initViewCache mms,
08-30 17:40:18.454  6976  6976 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1868.481093
08-30 17:40:18.454  6976  6976 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-30 17:40:18.524  6748  6802 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-30 17:40:18.534  6748  6802 I AcmsKeyStoreHelper: Key Store exist
,08-30 17:40:18.534  6748  6802 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-30 17:40:18.554  6976  6976 D AbsListView: Get MotionRecognitionManager
,08-30 17:40:18.554  1017  1485 D MotionRecognitionService:  ssp status : false
,08-30 17:40:18.564  6976  6976 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 115.2125
,08-30 17:40:18.594  6748  6802 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-30 17:40:18.594  6748  6802 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-30 17:40:18.594  6748  6802 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-30 17:40:18.594  6748  6802 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 17:40:18.594  6748  6802 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-30 17:40:18.594  6748  6802 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-30 17:40:18.594  6748  6802 D AcmsCore: This is NOT a valid MirrorLink app
08-30 17:40:18.594  6748  6802 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-30 17:40:18.594  6748  6802 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 17:40:18.594  6748  6802 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-30 17:40:18.594  6748  6802 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-30 17:40:18.604  6748  6748 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-30 17:40:18.604  6748  6748 D AcmsService: Enter onDestroy
08-30 17:40:18.604  6748  6748 I AcmsService: cleanUp(): inside service clean up
08-30 17:40:18.604  6748  6748 D AcmsCore: AcmsCore: inside DeInit
08-30 17:40:18.604  6748  6748 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-30 17:40:18.604  6748  6748 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-30 17:40:18.604  6748  6748 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-30 17:40:18.604  6748  6748 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-30 17:40:18.604  6748  6748 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-30 17:40:18.604  6748  6748 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-30 17:40:18.604  6748  6748 D AcmsService: killing acms process
08-30 17:40:18.604  6748  6748 I Process : Sending signal. PID: 6748 SIG: 9
,08-30 17:40:18.654  6976  6976 D Mms/BubbleViewCache: fillCache bubble = 1
,08-30 17:40:18.714  1017  1030 I ActivityManager: Process ACMS.Process (pid 6748)(adj 0) has died(28,756)
,08-30 17:40:19.204   290   290 E SMD     : DCD OFF
,08-30 17:40:20.174  1017  1042 W ProcessCpuTracker: Skipping unknown process pid 7255
,08-30 17:40:21.054  1017  3333 D SSRM:n  : SIOP:: AP = 420
,08-30 17:40:21.104  1017  3351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-30 17:40:21.294  1655  1655 I ConfigService: onDestroy
,08-30 17:40:22.204   290   290 E SMD     : DCD OFF
,08-30 17:40:24.074  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 17:40:24.184  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:40:24.184  1017  1030 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 17:40:24.184  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:40:24.184  1017  1030 D BatteryService: stay LED for charging
08-30 17:40:24.184  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:40:24.184  1017  1017 I MotionRecognitionService: Plugged
,08-30 17:40:24.184  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:40:24.194  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:40:24.194  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:40:24.194  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:40:24.194  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,08-30 17:40:24.204  3189  3189 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 17:40:24.214  3189  3326 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:40:24.224  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:24.224  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:24.224  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:25.214   290   290 E SMD     : DCD OFF
,08-30 17:40:26.164  1017  1319 E Watchdog: !@Sync 3,
,08-30 17:40:26.934  1017  1056 D PackageManager: [MSG] MCS_UNBIND
,08-30 17:40:26.944  1017  1859 I ActivityManager: Killing 6765:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-30 17:40:27.254   329   329 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 17:40:27.254   329   329 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 17:40:28.214   290   290 E SMD     : DCD OFF
,08-30 17:40:30.514  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-30 17:40:30.514  6828  7213 I jxcore-log: 
,08-30 17:40:30.514  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-30 17:40:30.514  6828  7213 I jxcore-log: 
,08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:30.524  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:30.524  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-30 17:40:30.524  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-30 17:40:30.524  6828  7213 I jxcore-log: 
,08-30 17:40:30.524  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-30 17:40:30.524  6828  7213 I jxcore-log: 
,08-30 17:40:30.694  1017  1095 V AlarmManager: waitForAlarm result :4,
08-30 17:40:30.694  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-30 17:40:30.844  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-30 17:40:30.914  6947  7057 D Finsky  : [1304] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-30 17:40:30.924  6947  6947 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 17:40:31.084  1017  3333 D SSRM:n  : SIOP:: AP = 390,
,08-30 17:40:31.214   290   290 E SMD     : DCD OFF
,08-30 17:40:31.224  6828  7213 D executeNativeTests: Running unit tests,
,08-30 17:40:31.314  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:31.314  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 added. We now have 2 listener(s)
,08-30 17:40:31.314  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 17:40:31.314  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:31.314  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:40:31.314  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:31.314  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 added. We now have 2 listener(s)
08-30 17:40:31.314  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:31.314  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:40:31.324  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:31.324  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:31.324  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:31.324  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:40:31.324  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:40:31.334  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:40:31.334  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:40:31.334  6828  7213 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 17:40:31.334  6828  7213 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:40:31.334  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:40:31.334  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 17:40:31.334  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.334  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.334  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.334  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.334  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:31.334  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 removed from the list
08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.334  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 removed from the list
,08-30 17:40:31.334  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.334  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.334  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.334  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.334  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.334  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.334  6828  7213 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 17:40:31.334  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.334  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.334  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.344  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.344  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.344  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.344  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.344  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.344  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.344  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.344  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.344  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:40:31.344  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.344  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.344  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.344  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.344  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.344  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.344  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.344  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.344  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.344  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.344  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 17:40:31.344  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.344  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.344  6828  7213 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:40:31.344  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:31.354  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:31.354  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:31.354  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:31.354  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:31.354  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:40:31.354  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:31.354  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:31.354  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:40:31.354  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:40:31.364  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.364  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.364  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:40:31.364  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:40:31.374  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 17:40:31.374  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 17:40:31.374  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:40:31.374  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:40:31.374  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:40:31.384  3189  3197 D BtGatt.GattService: registerClient() - UUID=b1eb37f5-e6f5-498f-9387-68a76c3bdc2f
,08-30 17:40:31.424  3189  3262 D BtGatt.GattService: onClientRegistered() - UUID=b1eb37f5-e6f5-498f-9387-68a76c3bdc2f, clientIf=6
,08-30 17:40:31.424  6828  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:40:31.424  3189  3337 D BtGatt.GattService: start scan with filters
,08-30 17:40:31.434  3189  3320 D BtGatt.ScanManager: handling starting scan
,08-30 17:40:31.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:40:31.434  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:40:31.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 17:40:31.434  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:31.444  3189  3320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:31.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:31.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:40:31.444  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:31.454  3189  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:40:31.454  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.454  3189  3320 D BtGatt.ScanManager: allow scan with filters
,08-30 17:40:31.454  3189  3320 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:40:31.454  3189  3320 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 17:40:31.454  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:31.454  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:40:31.454  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.464  3189  3320 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:40:31.464  3189  3320 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:40:31.464  6828  7213 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:40:31.464  3189  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 17:40:31.464  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.464  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:31.464  6828  7213 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:40:31.464  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:31.464  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
08-30 17:40:31.464  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.464  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:40:31.464  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:40:31.464  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 17:40:31.464  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:40:31.464  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:31.474  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:40:31.474  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:40:31.474  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:40:31.474  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.474  3189  3202 D BtGatt.GattService: stopScan() - queue size =1,
,08-30 17:40:31.474  3189  3197 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:40:31.474  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:40:31.474  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:40:31.474  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:40:31.474  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:40:31.474  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:31.484  3189  3320 D BtGatt.ScanManager: filter size is 1
,08-30 17:40:31.484  3189  3320 D BtGatt.ScanManager: delete FilterIndex - 3
,08-30 17:40:31.484  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:31.484  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 17:40:31.484  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.484  3189  3320 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:40:31.484  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 17:40:31.484  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 17:40:31.484  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:40:31.484  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:31.494  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.494  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.494  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:31.494  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.494  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.494  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.494  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.494  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.494  6828  7213 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 17:40:31.494  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:40:31.494  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:31.494  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:31.494  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:31.494  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:40:31.494  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.494  3189  3320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:40:31.494  3189  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 17:40:31.494  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:31.504  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:31.504  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:31.504  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:40:31.504  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.504  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.514  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 17:40:31.514  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:40:31.514  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 17:40:31.514  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:31.514  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:40:31.514  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:40:31.524  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:40:31.524  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:40:31.524  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:40:31.524  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 17:40:31.524  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:40:31.524  3189  3197 D BtGatt.GattService: registerClient() - UUID=21dc9b19-ed76-4bfa-aa55-1551721b2e94
,08-30 17:40:31.574  3189  3262 D BtGatt.GattService: onClientRegistered() - UUID=21dc9b19-ed76-4bfa-aa55-1551721b2e94, clientIf=6
,08-30 17:40:31.574  6828  6841 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:40:31.574  3189  3337 D BtGatt.GattService: start scan with filters
,08-30 17:40:31.574  3189  3320 D BtGatt.ScanManager: handling starting scan
08-30 17:40:31.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:40:31.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:40:31.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:40:31.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:31.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:31.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:40:31.574  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:31.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:31.574  3189  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:40:31.574  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.574  3189  3320 D BtGatt.ScanManager: allow scan with filters
08-30 17:40:31.574  3189  3320 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:40:31.574  3189  3320 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 17:40:31.584  6828  7213 I io.jxcore.node.ConnectionHelper: start: OK,
,08-30 17:40:31.584  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.584  6828  7213 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:40:31.584  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.584  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 17:40:31.584  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:40:31.584  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.584  3189  3320 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:40:31.584  3189  3320 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:40:31.584  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.584  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:40:31.584  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:40:31.584  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:31.584  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:40:31.584  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:31.584  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:40:31.584  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:40:31.594  3189  3202 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:40:31.594  3189  3197 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:40:31.594  3189  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:40:31.594  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:40:31.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:40:31.594  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:40:31.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 17:40:31.594  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:31.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:31.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 17:40:31.594  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 17:40:31.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:40:31.594  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:40:31.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:31.594  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.604  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.604  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:31.604  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.604  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.604  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.604  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.604  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:31.604  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:31.604  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:31.604  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.604  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.604  3189  3320 D BtGatt.ScanManager: filter size is 1
,08-30 17:40:31.604  3189  3320 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 17:40:31.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:31.604  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.604  6828  7213 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 17:40:31.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 17:40:31.614  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 17:40:31.614  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.614  3189  3320 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:31.614  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:31.614  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:31.614  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:31.614  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:31.614  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:40:31.614  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:31.614  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:31.614  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:40:31.614  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 17:40:31.614  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.614  3189  3320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:40:31.624  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:40:31.624  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.624  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.624  3189  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 17:40:31.624  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.624  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:40:31.624  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:40:31.634  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:40:31.634  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:40:31.634  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:40:31.634  3189  3337 D BtGatt.GattService: registerClient() - UUID=57d762a0-ef3a-4e97-ab32-676b95ffaa28
,08-30 17:40:31.674  3189  3262 D BtGatt.GattService: onClientRegistered() - UUID=57d762a0-ef3a-4e97-ab32-676b95ffaa28, clientIf=6
,08-30 17:40:31.674  6828  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:40:31.674  3189  3202 D BtGatt.GattService: start scan with filters
,08-30 17:40:31.674  3189  3320 D BtGatt.ScanManager: handling starting scan
,08-30 17:40:31.674  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:40:31.674  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:40:31.674  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:40:31.674  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:31.684  3189  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:40:31.684  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:31.684  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:40:31.684  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:31.684  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.684  3189  3320 D BtGatt.ScanManager: allow scan with filters
08-30 17:40:31.684  3189  3320 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:40:31.684  3189  3320 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 17:40:31.684  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:31.694  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:40:31.694  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.694  3189  3320 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:40:31.694  3189  3320 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:40:31.694  6828  7213 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:40:31.694  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.694  6828  7213 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:40:31.694  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.694  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 17:40:31.694  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.694  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 17:40:31.694  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 17:40:31.704  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:31.704  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:40:31.704  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:31.704  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:40:31.704  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:40:31.704  3189  3337 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:40:31.704  3189  3202 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-30 17:40:31.704  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:40:31.704  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 17:40:31.704  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:40:31.704  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:40:31.704  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:31.704  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 17:40:31.704  3189  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 17:40:31.704  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:31.714  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:40:31.714  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:40:31.714  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:31.714  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.714  6828  7213 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:40:31.714  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.714  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.714  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:31.714  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.714  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.714  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.714  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:40:31.714  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.714  6828  7213 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 17:40:31.714  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.714  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.714  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:31.714  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.714  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
,08-30 17:40:31.714  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.714  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.714  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.714  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.714  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.714  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.714  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 17:40:31.714  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.724  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 17:40:31.724  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.724  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.724  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.724  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.724  6828  7213 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 17:40:31.724  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:31.724  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.724  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.724  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.724  3189  3320 D BtGatt.ScanManager: filter size is 1
08-30 17:40:31.724  3189  3320 D BtGatt.ScanManager: delete FilterIndex - 5
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.724  6828  7213 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 17:40:31.724  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.724  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:31.724  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.724  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:31.724  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.724  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.724  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.724  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.734  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:40:31.734  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 17:40:31.734  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-30 17:40:31.734  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:40:31.734  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:31.734  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.734  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.734  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.734  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.734  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
,08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.734  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.734  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.734  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.734  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.734  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:31.734  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.734  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.734  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.734  6828  7213 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:31.734  6828  7213 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:40:31.734  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:40:31.734  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:40:31.734  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.734  3189  3320 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:40:31.744  6828  7213 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:31.744  6828  7213 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:40:31.744  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:40:31.744  6828  7213 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 17:40:31.744  6828  7213 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:40:31.744  6828  7213 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 17:40:31.744  6828  7213 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:31.744  6828  7213 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:40:31.744  6828  7213 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 17:40:31.744  6828  7213 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:31.744  6828  7213 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:40:31.744  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 17:40:31.744  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:40:31.744  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:31.744  3189  3320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:40:31.744  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 17:40:31.744  3189  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:40:31.744  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:31.744  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 17:40:31.754  6828  7213 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 17:40:31.754  6828  7213 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:40:31.754  6828  7213 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 17:40:31.754  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.754  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.754  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.754  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 17:40:31.754  6828  7264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1344)
,08-30 17:40:31.754  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.754  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.754  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.754  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.754  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.754  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.754  6828  7213 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 17:40:31.754  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.754  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.754  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.754  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.754  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.754  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.754  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.754  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.754  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.754  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.754  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.754  6828  7265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1344
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.764  6828  7213 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 17:40:31.764  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.764  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.764  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 17:40:31.764  6828  7213 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:40:31.764  6828  7213 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:40:31.764  6828  7213 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:40:31.764  6828  7213 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:40:31.764  6828  7213 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:40:31.764  6828  7213 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 17:40:31.764  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.764  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.764  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7264 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:,31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.764  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.764  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.764  6828  7264 D BluetoothSocket: connect(): myUserId = 0
08-30 17:40:31.764  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.764  6828  7264 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
,08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.764  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.764  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.764  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.764  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:31.774  3189  3202 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 17:40:31.774  6828  7264 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-30 17:40:31.774  6828  6828 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 17:40:31.774  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.774  6828  6828 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.774  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:31.774  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.774  6828  7266 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 17:40:31.774  6828  7266 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 17:40:31.774  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:31.774  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.774  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:31.774  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.784  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:31.784  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:31.784  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.784  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.784  6828  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.784  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.784  6828  7213 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 17:40:31.784  6828  7213 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:40:31.784  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:40:31.784  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.784  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.784  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.784  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.784  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.784  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.784  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.784  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.784  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.784  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.784  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.784  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.794  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.794  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.794  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.794  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:31.794  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:31.794  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:31.794  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:31.794  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.794  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.794  6828  7213 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3ac07 not in the list
08-30 17:40:31.794  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.794  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:31.794  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.794  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:31.794  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:31.794  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:31.794  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:31.794  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:31.794  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:31.794  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c49134 not in the list
,08-30 17:40:31.794  6828  7213 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:40:31.794  6828  7213 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:40:31.794  6828  7213 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 17:40:31.794  6828  7213 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:40:31.794  6828  7213 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 17:40:31.794  6828  7213 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 17:40:31.794  6828  7213 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-30 17:40:31.794  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:31.794  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1378f6 added. We now have 2 listener(s)
,08-30 17:40:31.794  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:31.794  6828  7213 D BluetoothAdapter: enable()
,08-30 17:40:31.804  6828  7213 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 17:40:31.804  1017  1859 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 17:40:31.804  1017  1859 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:40:31.804  1017  1859 D SecContentProvider2: mCursor = null
,08-30 17:40:31.804  1017  1859 D WifiService: setWifiEnabled: true pid=6828, uid=10170
,08-30 17:40:31.804  1017  1859 W ActivityManager: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:40:31.814  1017  1859 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:40:31.814  1017  1859 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:40:31.814  1017  1859 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:40:31.814  1017  1859 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:40:31.814  1017  1859 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:40:31.814  1017  1859 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:40:31.814  1017  1859 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:40:31.814  1017  1859 D SettingsProvider: name = wifi_on
,08-30 17:40:31.814  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 17:40:31.814  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d69a4f7 added. We now have 3 listener(s)
08-30 17:40:31.814  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:31.814  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:31.814  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2448af64 added. We now have 4 listener(s)
08-30 17:40:31.814  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:31.814  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:31.824  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23bb55cd added. We now have 5 listener(s)
08-30 17:40:31.824  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:31.824  1017  4291 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:40:31.824  1017  4291 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:40:31.824  1017  4291 D SecContentProvider2: mCursor = null
,08-30 17:40:31.824  1017  4291 D WifiService: setWifiEnabled: false pid=6828, uid=10170
,08-30 17:40:31.824  1017  4291 D SettingsProvider: name = wifi_on
,08-30 17:40:31.834  1017  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 17:40:31.834  6828  7213 D BluetoothAdapter: disable()
08-30 17:40:31.834  1393  1393 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:40:31.834  1393  1393 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-30 17:40:31.834  1393  1393 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:40:31.834  1017  4291 D SettingsProvider: name = bluetooth_on
08-30 17:40:31.834  1393  1393 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 17:40:31.834  3189  3259 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-30 17:40:31.834  3189  3259 D BluetoothAdapterProperties: Setting state to 13
08-30 17:40:31.834  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:40:31.834  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:40:31.834  3189  3259 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 17:40:31.844  1017  4291 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:31.844  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:40:31.844  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:31.844  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:31.844  1017  4291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:31.844  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:31.844  3189  3189 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 17:40:31.844  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:31.844  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23d04700, channel: 19, state: LISTENING
08-30 17:40:31.844  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23d04700, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27a202e8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f506b39mSocket: android.net.LocalSocket@3cff357e impl:android.net.LocalSocketImpl@186a5adf fd:FileDescriptor[80]
08-30 17:40:31.844  3189  3259 D BluetoothAdapterService: Autoconnection is available 
08-30 17:40:31.844  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 17:40:31.844  3189  3259 D BluetoothAdapterService: terminating service from this receiver
08-30 17:40:31.844  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3cff357e impl:android.net.LocalSocketImpl@186a5adf fd:FileDescriptor[80]
,08-30 17:40:31.854  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:40:31.854  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:31.854  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:31.854  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:31.854  3189  3259 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:40:31.854  4765  4765 D BluetoothPbap: Proxy object disconnected
08-30 17:40:31.854  3189  3259 D BluetoothAdapterProperties: mDiscovering is false
08-30 17:40:31.854  4765  4765 D PbapServerProfile: Bluetooth service disconnected
,08-30 17:40:31.854  1017  1469 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:40:31.854  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:31.854  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-30 17:40:31.854  3189  3259 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 17:40:31.854  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:31.854  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:31.864  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:31.864  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:31.864  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:40:31.864  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:40:31.864  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.864  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:31.864  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:40:31.864  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-30 17:40:31.864  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:31.874  1854  1854 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:31.874  1393  1393 I wpa_supplicant: nl80211: Received scan results (13 BSSes)
,08-30 17:40:31.874  1017  1126 E WifiNative-wlan0: do suspend true
,08-30 17:40:31.874  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:31.874  1017  1125 D WifiP2pService: InactiveState{ what=147461 }
08-30 17:40:31.874  1017  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
08-30 17:40:31.874  1017  1125 D WifiP2pService: DefaultState{ what=147461 }
,08-30 17:40:31.874  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:31.874  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:31.874  1017  1224 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:31.874  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 17:40:31.874  1017  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:40:31.874  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:31.884  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:40:31.884  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:31.884  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:31.884  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:31.884  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:31.884  3189  3262 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 17:40:31.884  3189  3262 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:40:31.894  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@114381f5, channel: 5, state: LISTENING
,08-30 17:40:31.894  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@114381f5, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@244e1d01, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23d52b8amSocket: android.net.LocalSocket@2bc3c5fb impl:android.net.LocalSocketImpl@23cff618 fd:FileDescriptor[82]
08-30 17:40:31.894  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2bc3c5fb impl:android.net.LocalSocketImpl@23cff618 fd:FileDescriptor[82]
08-30 17:40:31.894  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:40:31.894  3189  3259 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 17:40:31.894  3189  3189 I BtOppRfcommListener: stopping Accept Thread
,08-30 17:40:31.894  3189  3259 E bt-btif : cmd socket is not created
08-30 17:40:31.894  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@b174871, channel: 12, state: LISTENING
08-30 17:40:31.894  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@b174871, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dd0a983, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9627656mSocket: android.net.LocalSocket@1b7ec6d7 impl:android.net.LocalSocketImpl@36da5bc4 fd:FileDescriptor[87]
08-30 17:40:31.894  3189  3263 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-30 17:40:31.894  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b7ec6d7 impl:android.net.LocalSocketImpl@36da5bc4 fd:FileDescriptor[87]
,08-30 17:40:31.894  3189  5269 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:40:31.894  6828  7264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@13099993, channel: -1, state: INIT
,08-30 17:40:31.894  3189  3259 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:40:31.894  6828  7264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@13099993, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22935dd0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e3481c9mSocket: android.net.LocalSocket@265cb0ce impl:android.net.LocalSocketImpl@20aa3bef fd:FileDescriptor[105]
,08-30 17:40:31.894  6828  7264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@265cb0ce impl:android.net.LocalSocketImpl@20aa3bef fd:FileDescriptor[105]
08-30 17:40:31.894  3189  5269 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 17:40:31.894  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.894  6828  7264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1344)
,08-30 17:40:31.894  4765  4765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:31.904  1017  4291 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:40:31.904  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:40:31.904  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:31.904  1017  4291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:31.904  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:31.904  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:40:31.904  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:31.904  3189  3189 V BluetoothOppManager: cleanUp...
,08-30 17:40:31.904  3189  3263 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,08-30 17:40:31.904  3189  3263 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-30 17:40:31.904  3189  3263 W bt-btif : invalid rfc slot id: 4
,08-30 17:40:31.914  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:31.914  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 17:40:31.914  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:40:31.914  3189  3263 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:40:31.914  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:40:31.914  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:40:31.914  3189  3263 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 17:40:31.914  4765  4765 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:31.924  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:31.924  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:31.924  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 17:40:31.924  1017  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 17:40:31.924  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:31.924  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:31.924  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:31.924  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:31.924  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:40:31.934  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-30 17:40:31.944  7271  7271 E Zygote  : MountEmulatedStorage()
,08-30 17:40:31.944  7271  7271 I libpersona: KNOX_SDCARD checking this for 10055
08-30 17:40:31.944  7271  7271 E Zygote  : v2
08-30 17:40:31.944  7271  7271 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:31.944  7271  7271 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:31.944  1017  1485 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7271 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-30 17:40:31.944  7271  7271 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:31.944  7271  7271 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:31.944   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:31.954  1655  2529 V NativeCrypto: Read error: ssl=0xb931ca60: I/O error during system call, Connection timed out
,08-30 17:40:31.954  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:31.954  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:40:31.954  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:31.954  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-30 17:40:31.964  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:40:31.964  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:40:31.964  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:31.964  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:31.964  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:31.964  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:31.964  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
08-30 17:40:31.964  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 17:40:31.964  1655  2529 V NativeCrypto: SSL shutdown failed: ssl=0xb931ca60: I/O error during system call, Broken pipe
,08-30 17:40:31.964  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:40:31.964  1017  1030 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-30 17:40:31.964  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 17:40:31.964  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:40:31.964  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:31.964  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-30 17:40:31.964  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:31.964  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-30 17:40:31.974  1017  1742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:40:31.974  1017  1742 I qtaguid : Tagging socket 353 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,08-30 17:40:31.974  1017  1742 I qtaguid : Untagging socket 353
08-30 17:40:31.974  1017  1742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:40:31.974  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
,08-30 17:40:31.974  1017  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:40:31.974  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-30 17:40:31.984  1017  1151 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:31.984  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 17:40:31.984  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:31.984  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:31.984  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:31.984  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:31.984  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:31.984  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:31.984  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:31.994  7271  7271 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:31.994  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:40:31.994  7271  7271 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:31.994  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-30 17:40:31.994  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 17:40:31.994  1017  1125 D WifiP2pService: P2pDisablingState
08-30 17:40:31.994  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 17:40:31.994  1017  1125 D WifiP2pService: p2p socket connection lost
08-30 17:40:31.994  1017  1125 D WifiP2pService: P2pDisabledState
,08-30 17:40:31.994  1017  1126 E WifiNative-wlan0: do suspend true
,08-30 17:40:32.004  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:40:32.024  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-30 17:40:32.024  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 17:40:32.024  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 17:40:32.024  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:32.024  1017  1047 D WifiDisplayController: disconnect
08-30 17:40:32.024  1017  1047 D WifiDisplayController: updateConnection
08-30 17:40:32.024  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:32.024  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:40:32.024  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:40:32.024  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:40:32.024  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 17:40:32.024  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:40:32.024  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:40:32.024  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 17:40:32.034  1017  1339 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:40:32.034  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-30 17:40:32.034  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:40:32.034  7271  7271 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 17:40:32.044  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:32.044  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:32.044  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:32.044  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.044  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.044  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.044  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:32.054   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-30 17:40:32.054  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 17:40:32.054   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000,
08-30 17:40:32.054  1017  1128 V NetworkStats: updateIfacesLocked()
08-30 17:40:32.054   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:32.054  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:32.054  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.054  1017  1128 V NetworkStats: performPollLocked() took 5ms
08-30 17:40:32.054  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:32.054  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:40:32.054  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.054  1393  1393 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-30 17:40:32.054  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-30 17:40:32.054  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-30 17:40:32.054  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:40:32.064  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.064  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.064  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-30 17:40:32.064  7271  7271 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 17:40:32.064  1178  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
08-30 17:40:32.064  1017  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:40:32.064  7271  7271 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 17:40:32.064  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 17:40:32.064  7271  7271 D UserAnalysis: Create SecureDbHelper
08-30 17:40:32.064  1017  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-30 17:40:32.064  1017  1742 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:32.064  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:40:32.064  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 17:40:32.064  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 17:40:32.064  1443  1443 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 17:40:32.064  1443  1443 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:40:32.074  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:32.074  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:32.074  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:32.074  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.074  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.074  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:32.074  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.074  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 17:40:32.074  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 17:40:32.074  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:32.074  1017  1126 D SecContentProvider2: mCursor = null
08-30 17:40:32.074  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit(),
08-30 17:40:32.074  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 17:40:32.074  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:40:32.074  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:40:32.084  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:40:32.084  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:32.084  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:32.084  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:40:32.084  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:32.084  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.084  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.084  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:32.084  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:32.084  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-30 17:40:32.084  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:32.084  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:40:32.084  1178  1178 D HotspotTile: onReceive : 0, 0
08-30 17:40:32.084  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:40:32.084  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:32.084  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:32.084  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 17:40:32.084  1017  1130 D Tethering: MasterInitialState.processMessage what=3
,08-30 17:40:32.084  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:32.084  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:32.094  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:32.094  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:32.094  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:32.094  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:32.094  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.094  1017  1123 V NetworkStats: updateIfacesLocked()
08-30 17:40:32.094  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:32.094  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:32.094  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:40:32.094  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 17:40:32.094  3189  3259 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:40:32.094  3189  3259 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 17:40:32.094  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-30 17:40:32.094  3189  3259 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-30 17:40:32.094  1017  1123 V NetworkStats: performPollLocked() took 6ms
08-30 17:40:32.094  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 17:40:32.094  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 17:40:32.094  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:40:32.094  7271  7271 D IntelligenceServiceApplication: onCreate()
,08-30 17:40:32.094  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 17:40:32.094  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.094  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:40:32.094  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:40:32.094  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:40:32.094  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-30 17:40:32.094  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.094  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.094  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.094  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:32.104  1017  1224 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:32.104  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 17:40:32.104  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.104  1017  1224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.104  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-30 17:40:32.104  3189  3189 D HeadsetService: Received stop request...Stopping profile...
08-30 17:40:32.104  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:40:32.104  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 17:40:32.104  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 17:40:32.104  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:32.104  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:32.104  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 17:40:32.104  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:40:32.104  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-30 17:40:32.104  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-30 17:40:32.104  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-30 17:40:32.114  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.114  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:32.114  1017  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:32.114  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:40:32.114  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.114  1017  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.114  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:32.114  7271  7271 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-30 17:40:32.114  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-30 17:40:32.114  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:32.114  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 17:40:32.114  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:32.114  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:32.114  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:40:32.114  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.114  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.114  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.114  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.114  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 17:40:32.114  4765  4765 D HeadsetProfile: Bluetooth service disconnected
,08-30 17:40:32.114  1017  1042 I ActivityManager: Killing 6336:com.samsung.android.sm/1000 (adj 15): empty #21
,08-30 17:40:32.124  1017  1859 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-30 17:40:32.124  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 17:40:32.124  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.124  1017  1859 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.124  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:32.124  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:40:32.124  1017  4290 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:32.124  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:40:32.124  1017  4290 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-30 17:40:32.124  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 17:40:32.124  1017  4290 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.124  1017  4290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.124  1017  4290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-30 17:40:32.124  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 17:40:32.124  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-30 17:40:32.124  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:40:32.124  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:40:32.124  1017  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:32.124  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 17:40:32.124  7271  7271 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-30 17:40:32.124  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.124  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.124  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:32.134  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.134  1393  1393 I wpa_supplicant: Blacklist: Clear (all) 
08-30 17:40:32.134  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.134  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:40:32.134  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:32.134  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:40:32.134  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.134  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.134  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:32.134  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:40:32.134  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:32.134  3189  3259 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:40:32.134  7271  7271 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-30 17:40:32.134  1017  1339 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:32.134  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:40:32.134  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.134  1017  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.134  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:32.144  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:32.144  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:40:32.144  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,08-30 17:40:32.144  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:40:32.144  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:40:32.144  3189  3259 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:40:32.144  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 17:40:32.144  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:32.144  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 17:40:32.144  3189  3189 D A2dpService: Received stop request...Stopping profile...
08-30 17:40:32.144  3189  3328 D A2dpStateMachine: Exit Disconnected: -1
,08-30 17:40:32.144  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:32.154  4765  4765 D BluetoothA2dp: Proxy object disconnected
,08-30 17:40:32.154  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:32.154  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 17:40:32.154  4765  4765 D A2dpProfile: Bluetooth service disconnected
08-30 17:40:32.154  3189  3189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:40:32.154  3189  3189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 17:40:32.154  3189  3189 D HidService: Received stop request...Stopping profile...
08-30 17:40:32.154  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-30 17:40:32.154  3189  3189 D HidService: Stopping Bluetooth HidService
08-30 17:40:32.154  3189  3189 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:40:32.154  3189  3189 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 17:40:32.154  3189  3189 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:40:32.154  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:32.154  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.154  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.154  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.154  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:32.174  7293  7293 E Zygote  : MountEmulatedStorage(),
08-30 17:40:32.174  7293  7293 I libpersona: KNOX_SDCARD checking this for 10105
08-30 17:40:32.174  7293  7293 E Zygote  : v2
08-30 17:40:32.174  7293  7293 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:32.174  7293  7293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:32.174  1017  1480 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7293 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-30 17:40:32.174  7293  7293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:32.174  3189  3189 D HealthService: Received stop request...Stopping profile...
08-30 17:40:32.174  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:32.174  7293  7293 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:40:32.174  4765  4765 D BluetoothInputDevice: Proxy object disconnected
08-30 17:40:32.174  4765  4765 D HidProfile: Bluetooth service disconnected
,08-30 17:40:32.174  3189  3189 D PanService: Received stop request...Stopping profile...
08-30 17:40:32.174  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:32.184  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:40:32.184  3189  3189 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:40:32.184  4765  4765 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:40:32.184  4765  4765 D PanProfile: Bluetooth service disconnected
08-30 17:40:32.184  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:32.184  1393  1393 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 17:40:32.184  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:32.184  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:40:32.184  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:32.184  3189  3189 D SapService: Received stop request...Stopping profile...
08-30 17:40:32.184  3189  3189 D SapService: Stopping Bluetooth SapService
08-30 17:40:32.184  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:32.184  4765  4765 D BluetoothMap: Proxy object disconnected
08-30 17:40:32.184  4765  4765 D MapProfile: Bluetooth service disconnected
,08-30 17:40:32.194  4765  4765 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 17:40:32.194  4765  4765 D SapProfile: Bluetooth service disconnected
,08-30 17:40:32.194  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 17:40:32.194  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 17:40:32.194  3189  3189 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 17:40:32.194  3189  3329 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-30 17:40:32.194  3189  3189 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:40:32.194  3189  3189 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 17:40:32.194  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:32.194  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.194  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:32.194  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.194  3189  3189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:40:32.194  3189  3189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:40:32.194  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:32.194  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:32.194  3189  3189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:40:32.194  3189  3189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 17:40:32.194  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:32.194  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:32.194  3189  3189 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-30 17:40:32.204  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 17:40:32.204  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:32.204  3189  3189 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 17:40:32.204  3189  3189 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-30 17:40:32.204  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:40:32.204  3189  3259 D BluetoothAdapterProperties: Setting state to 10
08-30 17:40:32.204  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:40:32.204  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:40:32.204  3189  3259 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 17:40:32.204  3189  3259 D BluetoothAdapterService: Autoconnection is available 
08-30 17:40:32.204  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 17:40:32.204  4765  4774 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.204  4765  4774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:32.204  3189  3259 I BluetoothAdapterState: Entering OffState
08-30 17:40:32.204  7293  7293 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:32.204  3189  3197 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:40:32.204  1423  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.204  1423  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:32.204  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:40:32.204  7293  7293 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:32.204  1393  1393 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-30 17:40:32.204  1393  1393 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 17:40:32.204  1393  1393 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 17:40:32.204  1393  1393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 17:40:32.204  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:32.204  1393  1393 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 17:40:32.204  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:32.204  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:32.204  1017  1130 D Tethering: InitialState.processMessage what=4
,08-30 17:40:32.214  1017  1130 E Tethering: No numeric data
,08-30 17:40:32.214  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:32.214  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:32.214  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:32.214  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:32.214  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:40:32.214  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:40:32.214  1017  1130 D Tethering: clearTetheredNotification()
08-30 17:40:32.214  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:32.214  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.214  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:32.214  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:32.214  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:32.214  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:40:32.214  1178  1178 D HotspotTile: updateTetherState():false, false
,08-30 17:40:32.224  1017  1123 V NetworkStats: performPollLocked() took 3ms
08-30 17:40:32.224  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:32.224  4765  4773 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 17:40:32.224  1443  1875 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:32.224  1443  1875 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:32.224  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:32.224  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:32.224  1178  1751 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.224  1178  1751 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:32.224  1630  1640 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.224  1630  1640 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:32.234  4765  4773 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 17:40:32.234  3189  3306 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.234  3189  3306 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:32.234  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.234  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:32.234  1430  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:32.234  1430  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:32.234  4765  4773 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:40:32.244  4765  4774 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 17:40:32.244  1655  4319 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.244  1655  4319 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:32.244  4765  4773 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 17:40:32.244  4765  4773 D Bluetoothsap: Unbinding service...
,08-30 17:40:32.244  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.244  6828  6836 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:32.244  6828  6836 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:32.244  6828  6836 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 17:40:32.244  6828  6836 D BluetoothLeAdvertiser: Exit stop advertising
08-30 17:40:32.244  6828  6836 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 17:40:32.244  6828  6836 D BluetoothLeScanner: Exiting stopAllScan
,08-30 17:40:32.244  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.244  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:32.244  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-30 17:40:32.244  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:40:32.254  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.254  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:40:32.254  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:32.254  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:40:32.254   329   329 I ServiceManager: Waiting for service AtCmdFwd...
08-30 17:40:32.254  1178  1178 D BluetoothTile:  getBluetoothState : 10
08-30 17:40:32.254  1854  1854 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:32.254  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.264  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:40:32.264  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.264  1017  1469 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:40:32.264  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:32.264  1017  1135 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:40:32.264  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:40:32.264  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:32.264  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.264  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.264  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:32.264  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.264  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.274  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:40:32.274  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.274  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.274  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.274  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.274  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.274  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.274  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.274  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.274  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:40:32.284  6828  6828 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:40:32.284  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.284  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.284  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.284  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.284  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.284  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.284  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:40:32.284  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:40:32.294  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-30 17:40:32.314  1393  1393 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:40:32.344   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:40:32.344   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:32.344  7293  7327 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:40:32.344   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:40:32.344   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:32.344  7293  7327 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:40:32.384  1393  1393 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 17:40:32.384  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:32.384  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:32.384  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:32.484  1017  4291 I ActivityManager: Killing 6848:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:32.484  7293  7293 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:32.484  7293  7293 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:32.494  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 17:40:32.494  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 17:40:32.504  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:32.504  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:32.504  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:32.504  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:40:32.504  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:32.504  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.504  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.504  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.504  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:32.504  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:32.504  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-30 17:40:32.504  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:40:32.504  1017  1339 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:32.504  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:40:32.504  1178  1178 D HotspotTile: onReceive : 1, 0
08-30 17:40:32.504  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:32.504  1630  2150 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:40:32.504  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:32.504  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.504  1017  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:32.504  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:40:32.504  2183  2183 I Hs20UtilService: Starting #8
08-30 17:40:32.504  2183  2198 I Hs20UtilService: Message received 5007
08-30 17:40:32.514  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:40:32.514  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:40:32.514  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 17:40:32.514  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:40:32.514  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:32.514  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:40:32.514  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:32.534  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:40:32.534  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:40:32.534  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 17:40:32.534  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:40:32.534  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:32.534  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:40:32.534  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 17:40:32.534  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-30 17:40:32.534  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.534  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.544  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.544  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.554  7338  7338 E Zygote  : MountEmulatedStorage()
08-30 17:40:32.554  7338  7338 I libpersona: KNOX_SDCARD checking this for 10064
08-30 17:40:32.554  7338  7338 E Zygote  : v2
08-30 17:40:32.554  7338  7338 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:32.554  7338  7338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:32.554  7338  7338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:32.554  7338  7338 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:32.554  1017  1135 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7338 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:32.554  7293  7331 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 17:40:32.574  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:32.574  7338  7338 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:32.574  7338  7338 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:32.584  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-30 17:40:32.594  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:32.594  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:32.604  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:40:32.604  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:32.604  7338  7338 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:40:32.604  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:32.604  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 17:40:32.614  7338  7338 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:32.624  7338  7338 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:40:32.644  7338  7338 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:40:32.654  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 17:40:32.654  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:32.654  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.654  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.654  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:32.664  7355  7355 E Zygote  : MountEmulatedStorage()
,08-30 17:40:32.664  1017  1135 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7355 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:32.664  7355  7355 E Zygote  : v2
08-30 17:40:32.664  7355  7355 I libpersona: KNOX_SDCARD checking this for 10065
08-30 17:40:32.664  7355  7355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:32.664  7355  7355 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:32.664  1017  1135 I ActivityManager: Killing 6869:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-30 17:40:32.664  7355  7355 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:32.664  7355  7355 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:32.684  7355  7355 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:32.684  7355  7355 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:32.704  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:32.704  7355  7355 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:32.704  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:32.714  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:32.714  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-30 17:40:32.714  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-30 17:40:32.714  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:32.714  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.714  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:32.714  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:32.724  7370  7370 E Zygote  : MountEmulatedStorage(),
,08-30 17:40:32.724  7370  7370 E Zygote  : v2
08-30 17:40:32.724  7370  7370 I libpersona: KNOX_SDCARD checking this for 10102
08-30 17:40:32.724  7370  7370 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:32.724  7370  7370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:32.724  1017  1029 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7370 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 17:40:32.724  1017  1029 I ActivityManager: Killing 6908:com.sec.pcw.device/1000 (adj 15): empty #21
,08-30 17:40:32.724  7370  7370 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:32.734  7370  7370 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:40:32.754  7370  7370 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:32.754  7370  7370 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:32.774  7370  7370 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 17:40:32.964  7370  7390 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-30 17:40:32.964  7370  7390 I Babel_SMS: MmsConfig.loadMmsSettings
08-30 17:40:32.964  7370  7390 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-30 17:40:32.964  7370  7390 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 17:40:32.994  7370  7390 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-30 17:40:32.994  7370  7390 I Babel_SMS: MmsConfig.loadFromResources
,08-30 17:40:32.994  7370  7390 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 17:40:32.994  7370  7390 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-30 17:40:33.024  1017  1458 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-30 17:40:33.034  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-30 17:40:33.034  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.034  1017  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:33.034  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:40:33.054  7370  7370 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:40:33.064  7370  7370 I Babel_Crash: startup - clean
,08-30 17:40:33.084  1017  4290 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:40:33.084  1017  4290 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:33.094  1017  4290 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.094  1017  4290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.094  1017  4290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:33.094  2183  2183 I Hs20UtilService: Starting #9
,08-30 17:40:33.094  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:40:33.094  2183  2198 I Hs20UtilService: Message received 5007
08-30 17:40:33.094  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:40:33.094  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:33.094  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:40:33.094  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:33.104  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:40:33.104  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:33.104  1017  1224 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:40:33.104  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:40:33.104  7370  7370 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:33.104  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.104  1017  1224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.114  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:33.114  2183  2183 I Hs20UtilService: Starting #10
,08-30 17:40:33.114  1017  3835 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-30 17:40:33.114  7370  7370 W AudioCapabilities: Unsupported mime audio/evrc
08-30 17:40:33.114  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.114  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.114  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.114  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.114  7370  7370 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 17:40:33.114  2183  2198 I Hs20UtilService: Message received 5011
,08-30 17:40:33.114  7370  7370 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-30 17:40:33.114  7370  7370 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-30 17:40:33.124  7393  7393 E Zygote  : MountEmulatedStorage()
08-30 17:40:33.124  7393  7393 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:33.124  7393  7393 E Zygote  : v2
08-30 17:40:33.124  7393  7393 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:33.124  7393  7393 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:33.124  7370  7370 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 17:40:33.134  1017  3835 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7393 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 17:40:33.134  7393  7393 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:33.134  7393  7393 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:33.134  1017  1044 D Tethering: interfaceRemoved wlan0
08-30 17:40:33.134  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 17:40:33.134  7370  7370 W AudioCapabilities: Unsupported mime audio/x-ima,
,08-30 17:40:33.134  7370  7370 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 17:40:33.144  7370  7370 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 17:40:33.154  7370  7370 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 17:40:33.154  7393  7393 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:33.154  7370  7370 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 17:40:33.154  7393  7393 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:33.164  7370  7370 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-30 17:40:33.174  7370  7370 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 17:40:33.174  7370  7370 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 17:40:33.174  7370  7370 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-30 17:40:33.174  7370  7370 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-30 17:40:33.174  7370  7370 W VideoCapabilities: Unsupported mime video/mp43
,08-30 17:40:33.184  7370  7370 W VideoCapabilities: Unsupported mime video/sorenson
,08-30 17:40:33.194  7370  7370 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 17:40:33.194  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:40:33.194  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:40:33.194  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:40:33.194  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:40:33.204  1017  1029 I ActivityManager: Killing 6927:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-30 17:40:33.204  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.204  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.204  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.204  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.204  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.204  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.214  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.214  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.214  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.214  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.214  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.214  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.214  7370  7370 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 17:40:33.214  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.214  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.214  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.224  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.224  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.224  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.224  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.224  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.224  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.234  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.234  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.234  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.234  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.234  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.234  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.244  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.244  1017  1044 D Tethering: interfaceRemoved p2p0
08-30 17:40:33.244  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 17:40:33.244  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.244  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.244  7370  7370 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:33.244  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.244  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.254  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.254  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.254  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.254  7370  7370 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:33.254  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.254  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.254  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:40:33.254   329   329 I ServiceManager: Waiting for service AtCmdFwd...
08-30 17:40:33.254  7370  7370 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:33.264  4765  4765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:33.264  1017  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:40:33.264  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:40:33.264  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.264  7370  7370 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:40:33.264  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.264  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:40:33.264  1017  4290 I ActivityManager: Killing 6805:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-30 17:40:33.264  4765  4765 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:33.274  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:33.274  7370  7370 I vclib   : onServiceConnected
,08-30 17:40:33.274  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:33.274  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:33.274  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 17:40:33.294  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:33.294  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:33.294  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.294  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.294  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:33.294  2183  2183 I Hs20UtilService: Starting #11
,08-30 17:40:33.304  2183  2198 I Hs20UtilService: Message received 5011
08-30 17:40:33.304  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:40:33.304  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:40:33.304  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:40:33.304  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:40:33.304  1017  1469 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 17:40:33.304  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.304  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.304  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.304  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.314  7411  7411 E Zygote  : MountEmulatedStorage()
08-30 17:40:33.324  7411  7411 E Zygote  : v2
08-30 17:40:33.324  7411  7411 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:33.324  7411  7411 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:33.324  7411  7411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 17:40:33.324  1017  1469 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:40:33.324  7411  7411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:40:33.334  7411  7411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:33.354   319   319 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 29.160ms
,08-30 17:40:33.354  7411  7411 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:33.354  7411  7411 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:33.364   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.376ms
,08-30 17:40:33.374  7411  7411 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-30 17:40:33.374  7411  7411 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 17:40:33.374  7411  7411 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 17:40:33.384   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 17.499ms
,08-30 17:40:33.394  7411  7411 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 17:40:33.394  7411  7411 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:40:33.394  7411  7411 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 17:40:33.394  7411  7411 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:33.394  7411  7426 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-30 17:40:33.394  1017  1458 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-30 17:40:33.394  1017  1458 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-30 17:40:33.394  1017  1458 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-30 17:40:33.394  1017  1458 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
08-30 17:40:33.394  1017  1458 I ActivityManager: Killing 7002:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-30 17:40:33.404  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 17:40:33.404  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.404  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.404  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.404  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.424  7428  7428 E Zygote  : MountEmulatedStorage()
,08-30 17:40:33.424  7428  7428 E Zygote  : v2
08-30 17:40:33.424  7428  7428 I libpersona: KNOX_SDCARD checking this for 10001
08-30 17:40:33.424  7428  7428 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:33.424  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:33.424  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7428 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:40:33.434  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:33.434  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:33.454  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:33.454  7428  7428 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:33.514  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 17:40:33.524  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.524  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.524  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.524  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.534  1017  1030 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7445 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:40:33.534  7445  7445 E Zygote  : MountEmulatedStorage()
08-30 17:40:33.534  1017  1030 I ActivityManager: Killing 7029:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
08-30 17:40:33.534  7445  7445 E Zygote  : v2
08-30 17:40:33.534  7445  7445 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:33.534  7445  7445 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:33.534  7445  7445 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:33.544  7445  7445 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:33.544  7445  7445 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:33.554  7445  7445 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:33.554  7445  7445 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:33.594  7445  7445 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 17:40:33.704  7445  7445 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-30 17:40:33.714  7445  7445 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-30 17:40:33.714  7445  7445 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:33.714  7445  7445 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 17:40:33.714  7445  7445 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-30 17:40:33.714  7445  7445 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-30 17:40:33.714  1017  1224 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-30 17:40:33.714  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.714  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.714  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.714  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.734  7460  7460 E Zygote  : MountEmulatedStorage(),
08-30 17:40:33.734  7460  7460 E Zygote  : v2
08-30 17:40:33.734  7460  7460 I libpersona: KNOX_SDCARD checking this for 10008
08-30 17:40:33.734  7460  7460 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:33.734  7460  7460 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:33.734  1017  1224 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7460 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-30 17:40:33.734  1017  1224 I ActivityManager: Killing 7060:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
08-30 17:40:33.734  7460  7460 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:33.734  7460  7460 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 17:40:33.754  7460  7460 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:33.754  7460  7460 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:33.834  1017  1224 I ActivityManager: Killing 7084:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-30 17:40:33.844  1017  1458 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-30 17:40:33.844  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 17:40:33.844  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:33.844  1017  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:33.844  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-30 17:40:33.864  3768  7475 I iu.SyncManager: SYNC; picasa accounts
,08-30 17:40:33.874  3768  3768 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-30 17:40:33.884  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:40:33.884  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-30 17:40:33.884  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.884  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:33.884  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:33.904  3768  3768 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:40:33.904  3768  3768 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-30 17:40:33.904  2811  2811 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 17:40:33 GMT+02:00 2016
,08-30 17:40:33.904  1017  1496 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 17:40:33.914  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 17:40:33.914  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:33.914  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:33.914  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 17:40:33.924  2811  2811 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 17:40:33.934  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-30 17:40:33.934  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.934  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.934  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:33.934  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:33.934  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 17:40:33.944  2811  2811 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 17:40:33.944  7478  7478 E Zygote  : MountEmulatedStorage()
,08-30 17:40:33.944  7478  7478 E Zygote  : v2
08-30 17:40:33.944  7478  7478 I libpersona: KNOX_SDCARD checking this for 10031
08-30 17:40:33.944  7478  7478 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:33.944  2811  2811 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 17:40:33.944  7478  7478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:33.944  1017  1135 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7478 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-30 17:40:33.954  7478  7478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:33.954  7478  7478 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:33.954  2811  2811 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 17:40:33.954  2811  7477 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 17:40:33.954  2811  7477 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-30 17:40:33.964  2811  7477 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-30 17:40:33.964  2811  7477 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-30 17:40:33.964  2811  2811 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 17:40:33.964  7478  7478 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:33.974  7478  7478 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:33.994  7478  7478 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-30 17:40:34.014  1017  4291 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 17:40:34.014  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.014  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.014  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.014  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.024  2749  7493 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-30 17:40:34.024  1017  4291 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7494 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:34.034  7494  7494 E Zygote  : MountEmulatedStorage()
08-30 17:40:34.034  7494  7494 I libpersona: KNOX_SDCARD checking this for 10032
08-30 17:40:34.034  7494  7494 E Zygote  : v2
08-30 17:40:34.034  7494  7494 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:34.034  7494  7494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:34.034  2749  7493 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-30 17:40:34.034  2749  7493 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-30 17:40:34.034  7494  7494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:34.034  2749  7493 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-30 17:40:34.034  2749  7493 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 17:40:34.034  7494  7494 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-30 17:40:34.064  7494  7494 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:34.064  7494  7494 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:34.084  1017  1485 I art     : Explicit concurrent mark sweep GC freed 49661(2MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.938ms total 175.945ms
,08-30 17:40:34.094  1017  1030 I ActivityManager: Killing 6976:com.android.mms/u0a41 (adj 15): empty #21
,08-30 17:40:34.114  7494  7509 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-30 17:40:34.114  7494  7509 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-30 17:40:34.124  7494  7509 D SPPClientService: PushLog.txt file is not deleted.
,08-30 17:40:34.124  7494  7509 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:40:34.124  7494  7509 D SPPClientService: ============PushLog. stop!,
,08-30 17:40:34.124  7494  7494 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-30 17:40:34.134  1017  1485 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-30 17:40:34.134  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.134  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.134  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.134  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.144  7511  7511 E Zygote  : MountEmulatedStorage()
08-30 17:40:34.144  1017  1485 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7511 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:34.144  7511  7511 E Zygote  : v2
08-30 17:40:34.144  1017  1485 I ActivityManager: Killing 7128:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-30 17:40:34.144  7511  7511 I libpersona: KNOX_SDCARD checking this for 10036
08-30 17:40:34.144  7511  7511 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:34.144  7511  7511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:34.144  1017  1496 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-30 17:40:34.144  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-30 17:40:34.144  1017  1496 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:40:34.144  1017  1496 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,08-30 17:40:34.144  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-30 17:40:34.154  7511  7511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:34.154  7511  7511 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-30 17:40:34.174  7511  7511 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:34.174  7511  7511 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:34.184  7494  7517 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-30 17:40:34.214   290   290 E SMD     : DCD OFF
,08-30 17:40:34.224  7511  7511 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@355ec741
,08-30 17:40:34.234  1017  1224 D CountryDetector: No listener is left
,08-30 17:40:34.234  7511  7511 I SA      : [SSP] onCreated
08-30 17:40:34.234  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 17:40:34.234  1017  3835 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4197, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 17:40:34.234  1017  3835 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:40:34.234  1017  3835 D BatteryService: stay LED for charging
08-30 17:40:34.234  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:40:34.244  1017  1017 I MotionRecognitionService: Plugged
08-30 17:40:34.244  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
,08-30 17:40:34.244  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:40:34.244  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:40:34.244  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:40:34.244  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,08-30 17:40:34.254   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:40:34.264  7511  7511 I SA      : [TPM] There is no property file
,08-30 17:40:34.274  7511  7511 I SA      : [SCU] isHaveSA() - false
,08-30 17:40:34.274  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:34.274  7511  7511 I SA      : [TPM] getModelProperty : null
08-30 17:40:34.274  7511  7511 I SA      : [TPM] getCSCProperty : null
,08-30 17:40:34.274  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
08-30 17:40:34.274  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:34.274  7511  7511 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-30 17:40:34.274  7511  7511 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,08-30 17:40:34.274  7511  7511 I SA      : [DM] TFT FEATURE: false
,08-30 17:40:34.284  7511  7511 I SA      : [DM] init START
,08-30 17:40:34.284  7511  7511 I SA      : [DM] This device is not a Vodafone
,08-30 17:40:34.294  7511  7511 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-30 17:40:34.294  7511  7511 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-30 17:40:34.294  7511  7511 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-30 17:40:34.294  7511  7511 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-30 17:40:34.294  7511  7511 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75),
08-30 17:40:34.294  7511  7511 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-30 17:40:34.294  7511  7511 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-30 17:40:34.294  7511  7511 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75),
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-30 17:40:34.304  7511  7511 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-30 17:40:34.314  7511  7511 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-30 17:40:34.324  7511  7511 I SA      : [SCU] isHaveSA() - false
,08-30 17:40:34.324  7511  7511 I SA      : support phone number id : false
,08-30 17:40:34.324  7511  7511 I SA      : [DM] Supports Ref Jpn : true
,08-30 17:40:34.324  7511  7511 I SA      : [DM] init END
,08-30 17:40:34.324  7511  7511 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-30 17:40:34.324  1017  1095 V AlarmManager: waitForAlarm result :4
,08-30 17:40:34.324  7511  7511 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-30 17:40:34.324  7511  7511 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 17:40:34.334  7511  7511 I SA      : [SLFUCHKMGR] constructor called
,08-30 17:40:34.334  7511  7511 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-30 17:40:34.334  7511  7511 I SA      : [OR] == isSIMCardReady false ==
,08-30 17:40:34.344  7511  7511 I SA      : [SCU] == networkStateCheck == false
,08-30 17:40:34.344  7511  7511 I SA      : [OR] onReceive END
,08-30 17:40:34.344  1017  4290 I ActivityManager: Killing 7145:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-30 17:40:34.344  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:34.354  1756  1756 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:40:34.354  2668  2676 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-30 17:40:34.364  1756  1756 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1,
08-30 17:40:34.364  1756  1756 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-30 17:40:34.364  1756  1756 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-30 17:40:34.364  1756  1756 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 17:40:34.364  1756  1756 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:40:34.364  1756  1756 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-30 17:40:34.364  1017  1469 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-30 17:40:34.374  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.374  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.374  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.374  1017  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.384  1017  1469 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7533 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:40:34.384  7533  7533 E Zygote  : MountEmulatedStorage()
08-30 17:40:34.384  7533  7533 E Zygote  : v2
08-30 17:40:34.384  7533  7533 I libpersona: KNOX_SDCARD checking this for 10077
08-30 17:40:34.384  7533  7533 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:34.384  7533  7533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:34.394  7533  7533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:40:34.394  7533  7533 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-30 17:40:34.404  7533  7533 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:34.404  7533  7533 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:34.594  1017  3835 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-30 17:40:34.594  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 17:40:34.594  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:34.594  1017  3835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:34.594  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:40:34.604  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-30 17:40:34.604  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.604  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.604  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:34.604  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:34.614  7552  7552 E Zygote  : MountEmulatedStorage(),
08-30 17:40:34.614  1017  1135 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7552 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:34.614  7552  7552 E Zygote  : v2
08-30 17:40:34.614  7552  7552 I libpersona: KNOX_SDCARD checking this for 10110
08-30 17:40:34.614  7552  7552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:34.614  7552  7552 I libpersona: KNOX_SDCARD not a persona,
08-30 17:40:34.614  1017  1496 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-30 17:40:34.614  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 17:40:34.614  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:34.614  1017  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:34.614  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-30 17:40:34.614  7552  7552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:34.624  7370  7551 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 17:40:34.624  7552  7552 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:40:34.624  1017  4290 I ActivityManager: Killing 7178:com.wsomacp/u0a23 (adj 15): empty #21
,08-30 17:40:34.644  7552  7552 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:34.644  7552  7552 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:34.774  1017  1339 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 17:40:34.864  1017  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 17:40:34.864  1017  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:40:34.864  1017  1030 D SecContentProvider2: mCursor = null
,08-30 17:40:34.864  1017  1030 D WifiService: setWifiEnabled: true pid=6828, uid=10170
,08-30 17:40:34.864  1017  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:40:34.864  1017  1030 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:40:34.864  1017  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:40:34.864  1017  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:40:34.864  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:40:34.864  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:40:34.864  1017  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:40:34.864  1017  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:40:34.864  1017  1030 D SettingsProvider: name = wifi_on
,08-30 17:40:34.874  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 17:40:34.944   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 17:40:34.944   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:34.944  7552  7570 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 17:40:34.954  7552  7552 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 17:40:34.954  7552  7552 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 17:40:34.954  7552  7552 I GAv4    :   adb logcat -s GAv4
,08-30 17:40:34.954   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/,
08-30 17:40:34.954   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:34.954  7552  7570 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 17:40:34.974   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 17:40:34.974   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:34.974  7552  7573 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 17:40:34.984   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 17:40:34.984   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:34.984  7552  7573 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,08-30 17:40:34.984  7552  7552 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:40:34.984  1017  4290 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 17:40:35.004  7552  7552 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:40:35.014  7552  7574 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 17:40:35.224  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:40:35.224  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:35.224  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:40:35.224  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 17:40:35.264   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:40:35.264  7552  7552 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-30 17:40:35.264  1017  1044 D Tethering: interfaceAdded wlan0
,08-30 17:40:35.274  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:40:35.274  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:35.274  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:35.274  1017  1130 E Tethering: No numeric data
,08-30 17:40:35.274  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 17:40:35.274  1017  1130 D Tethering: clearTetheredNotification()
08-30 17:40:35.274  1017  1130 D Tethering: InitialState.processMessage what=4
08-30 17:40:35.274  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:35.274  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:35.274  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:35.274  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:35.284  1017  1044 D Tethering: interfaceAdded p2p0
,08-30 17:40:35.284  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:40:35.284  1178  1178 D HotspotTile: updateTetherState():false, false
,08-30 17:40:35.284   277  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
,08-30 17:40:35.284   277  1016 D SoftapController: Softap fwReload - Ok
08-30 17:40:35.284  1017  1123 V NetworkStats: performPollLocked() took 8ms
,08-30 17:40:35.284  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-30 17:40:35.284  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:35.284  1017  1130 E Tethering: No numeric data
08-30 17:40:35.284  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:35.284  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:35.284  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-30 17:40:35.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:35.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:35.294  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:40:35.294  1017  1130 D Tethering: clearTetheredNotification()
08-30 17:40:35.294   277  1016 D CommandListener: Setting iface cfg
08-30 17:40:35.294   277  1016 D CommandListener: Trying to bring down wlan0
,08-30 17:40:35.294  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-30 17:40:35.294  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:40:35.294  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:35.294  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:40:35.294  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:40:35.294  1178  1178 D HotspotTile: updateTetherState():false, false
08-30 17:40:35.294   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:35.294  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-30 17:40:35.294  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:35.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:35.294  7552  7552 I cr.library_loader: Time to load native libraries: 7 ms (timestamps 7082-7089)
08-30 17:40:35.294  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-30 17:40:35.294  7552  7552 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 17:40:35.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:35.314  7552  7552 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23d04700},
08-30 17:40:35.314  7552  7552 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 17:40:35.314  7552  7552 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:40:35.334  7552  7552 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-30 17:40:35.334  7552  7552 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-30 17:40:35.344  7552  7552 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 17:40:35.354  7552  7552 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:40:35.354  7552  7552 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:40:35.354  7552  7552 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:40:35.354  7552  7552 I Adreno-EGL: Local Branch: 
08-30 17:40:35.354  7552  7552 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:40:35.354  7552  7552 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:40:35.354  7552  7552 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:40:35.354  7598  7598 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 17:40:35.354  7598  7598 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 17:40:35.354  7598  7598 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 17:40:35.374  7598  7598 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-30 17:40:35.374   384   384 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7598
08-30 17:40:35.374   384   384 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-30 17:40:35.374  7598  7598 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 17:40:35.374  7598  7598 I wpa_supplicant: ssSupport state is = 1
08-30 17:40:35.374  7598  7598 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 17:40:35.374  7598  7598 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-30 17:40:35.374   384   384 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7598
08-30 17:40:35.374   384   384 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-30 17:40:35.404  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 17:40:35.414  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:35.424  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:35.424  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:35.424  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:35.424  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:40:35.424  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:35.424  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:35.424  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:35.424  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:35.424  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:35.424  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:35.424  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 17:40:35.424  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:40:35.424  1178  1178 D HotspotTile: onReceive : 2, 0
,08-30 17:40:35.424  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:35.434  7552  7612 W cr.media: Requires BLUETOOTH permission
,08-30 17:40:35.444  7552  7552 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 17:40:35.464  7552  7552 I NSApplication: Starting up...
08-30 17:40:35.464  1017  4290 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-30 17:40:35.464  1017  1859 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 17:40:35.474  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-30 17:40:35.474  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:35.474  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:35.474  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:35.474  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:35.484  7617  7617 E Zygote  : MountEmulatedStorage()
,08-30 17:40:35.484  7617  7617 E Zygote  : v2,
08-30 17:40:35.484  7617  7617 I libpersona: KNOX_SDCARD checking this for 10117
08-30 17:40:35.484  7617  7617 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:35.484  7617  7617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:35.494  1017  1135 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7617 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:40:35.494  1017  1135 I ActivityManager: Killing 7199:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-30 17:40:35.494  7617  7617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:35.494  7617  7617 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:40:35.534  7617  7617 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:35.534  7617  7617 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:35.554  7617  7617 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:40:35.574   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-30 17:40:35.574  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-30 17:40:35.624  7598  7598 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 17:40:35.624  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 17:40:35.634  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-30 17:40:35.634   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7598
08-30 17:40:35.634  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:35.634   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 17:40:35.634  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 17:40:35.634  7598  7598 I wpa_supplicant: ssSupport state is = 1
08-30 17:40:35.634  7598  7598 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:35.634  7598  7598 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:35.634  7598  7598 E wpa_supplicant: SIM READ ERROR
08-30 17:40:35.634  7598  7598 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:35.634  7598  7598 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:35.634  7598  7598 E wpa_supplicant: SIM READ ERROR
08-30 17:40:35.634  7598  7598 I wpa_supplicant: Blacklist: Clear (all) 
08-30 17:40:35.634  7598  7598 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:40:35.634  7598  7598 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:40:35.634  7598  7598 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:35.634  7598  7598 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 17:40:35.634  7598  7598 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:35.634  7598  7598 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:35.634  7598  7598 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 17:40:35.634  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:35.634  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:35.714  7598  7598 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 17:40:35.884  7598  7598 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 17:40:35.884  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 17:40:35.884  1017  1224 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 17:40:35.894  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:40:35.894  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:35.894  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:35.894  1017  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:35.904  7640  7640 E Zygote  : MountEmulatedStorage()
08-30 17:40:35.904  7640  7640 E Zygote  : v2
08-30 17:40:35.904  7640  7640 I libpersona: KNOX_SDCARD checking this for 10121
08-30 17:40:35.904  7640  7640 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:35.904  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-30 17:40:35.904   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7598
08-30 17:40:35.904   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 17:40:35.904  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 17:40:35.904  7598  7598 I wpa_supplicant: ssSupport state is = 1,
08-30 17:40:35.904  7640  7640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:35.914  1017  1224 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7640 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,08-30 17:40:35.914  1017  1224 I ActivityManager: Killing 7218:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21,
,08-30 17:40:35.914  7640  7640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:40:35.914  7640  7640 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:35.924  7598  7598 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 17:40:35.924  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 17:40:35.944  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-30 17:40:35.944   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7598
08-30 17:40:35.944   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-30 17:40:35.944  7598  7598 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-30 17:40:35.944  7598  7598 I wpa_supplicant: ssSupport state is = 1
08-30 17:40:35.944  7598  7598 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:35.944  7598  7598 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:35.944  7598  7598 E wpa_supplicant: SIM READ ERROR
08-30 17:40:35.944  7598  7598 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:40:35.944  7598  7598 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:40:35.944  7598  7598 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:40:35.944  7640  7640 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:35.944  7640  7640 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:35.954  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:35.954  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:35.954  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:40:35.954  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:40:35.954  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:35.954  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:40:35.964  7640  7640 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:40:35.964  7640  7640 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:40:35.964  7640  7640 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:40:35.984  7640  7640 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:35.994  7640  7640 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
,08-30 17:40:35.994  7640  7640 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 17:40:35.994  1017  4290 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-30 17:40:35.994  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:35.994  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:35.994  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:35.994  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:36.014  7658  7658 E Zygote  : MountEmulatedStorage()
08-30 17:40:36.014  1017  4290 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7658 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-30 17:40:36.014  7658  7658 E Zygote  : v2
08-30 17:40:36.014  7658  7658 I libpersona: KNOX_SDCARD checking this for 10141
08-30 17:40:36.014  7658  7658 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:36.014  7658  7658 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:36.014  7598  7598 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-30 17:40:36.014  1017  4290 I ActivityManager: Killing 7233:com.android.calendar/u0a131 (adj 15): empty #21
08-30 17:40:36.014  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 17:40:36.014  7658  7658 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:36.014  7658  7658 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:36.034   319   319 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 23.532ms
,08-30 17:40:36.044  7658  7658 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:36.044  7658  7658 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:36.054   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.460ms
,08-30 17:40:36.054  7658  7658 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-30 17:40:36.054  7658  7658 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:36.054  7658  7658 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:36.054  7658  7658 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 17:40:36.064   319   319 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 16.466ms
,08-30 17:40:36.104  1017  1339 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:36.114  7598  7598 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 17:40:36.114  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-30 17:40:36.114  7598  7598 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:40:36.114  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:36.124  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-30 17:40:36.124  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:40:36.124  7598  7598 I wpa_supplicant: HOTSPOT20_ENABLE called
08-30 17:40:36.124  7598  7598 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:36.124  7598  7598 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:36.124  7598  7598 E wpa_supplicant: SIM READ ERROR
08-30 17:40:36.124  7598  7598 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:40:36.144  1017  4290 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:36.144  7598  7598 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-30 17:40:36.154  7598  7598 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:40:36.154  1017  1480 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:36.164  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:36.164  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:40:36.164  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-30 17:40:36.164  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:36.164  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:36.164  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:36.164  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:36.164  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:36.164  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-30 17:40:36.164  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-30 17:40:36.164  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:40:36.164  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:40:36.164  1178  1178 D HotspotTile: onReceive : 3, 0
08-30 17:40:36.164  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:40:36.174  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:36.174  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:36.174  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:36.174  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:36.174  1017  1126 E WifiConfigStore: Not a HS20
,08-30 17:40:36.184  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:36.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:36.184  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:36.184  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:36.184  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 17:40:36.184  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 17:40:36.184  7598  7598 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 17:40:36.184  7598  7598 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 17:40:36.184  7598  7598 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:40:36.184  7598  7598 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:40:36.184  7598  7598 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 17:40:36.184  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 17:40:36.184  7598  7598 I wpa_supplicant: First Scan Start
,08-30 17:40:36.184  7598  7598 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 17:40:36.184  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-30 17:40:36.194  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:40:36.194  1017  1126 I WifiNative-HAL: startHal
08-30 17:40:36.194  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f50888c
08-30 17:40:36.194  1017  1126 I WifiNative-HAL: Could not start hal
,08-30 17:40:36.194  7370  7370 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:40:36.194  1017  1126 E WifiNative-wlan0: do suspend true
,08-30 17:40:36.194  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
08-30 17:40:36.194  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-30 17:40:36.194  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:40:36.194  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:40:36.194  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-30 17:40:36.194  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:40:36.194  1017  1017 D RttService: SCAN_AVAILABLE : 3
,08-30 17:40:36.194  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:36.194  1017  1150 I WifiNative-HAL: startHal
08-30 17:40:36.194  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e3ca9bc
08-30 17:40:36.194  1017  1150 I WifiNative-HAL: Could not start hal
08-30 17:40:36.194  1017  1150 E WifiScanningService: could not start HAL
,08-30 17:40:36.194   277  1016 D CommandListener: Setting iface cfg
08-30 17:40:36.194  1017  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:36.194   277  1016 D CommandListener: Trying to bring up p2p0
,08-30 17:40:36.204  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:40:36.204  7598  7598 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:40:36.204  1017  1125 D WifiP2pService: P2pEnablingState
08-30 17:40:36.204  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 17:40:36.204  1017  1125 D WifiP2pService: P2p socket connection successful
08-30 17:40:36.204  1017  1125 D WifiP2pService: P2pEnabledState
,08-30 17:40:36.204  7598  7598 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:40:36.204  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 17:40:36.204  7598  7598 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-30 17:40:36.204  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:36.204  1017  1126 E WifiStateMachine: Failed to set frequency band 0
08-30 17:40:36.204  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:36.204  1017  1126 D SecContentProvider2: mCursor = null
08-30 17:40:36.204  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-30 17:40:36.204  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:36.204  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:36.204  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-30 17:40:36.204  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:36.204  1017  1047 D WifiDisplayController: disconnect
08-30 17:40:36.204  1017  1047 D WifiDisplayController: updateConnection
08-30 17:40:36.204  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:36.204  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:40:36.214  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-30 17:40:36.214  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-30 17:40:36.214  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:40:36.214  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:40:36.214  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:40:36.214  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:40:36.214  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
,08-30 17:40:36.214  1017  4290 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-30 17:40:36.224  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:36.224  1017  1480 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:36.224  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:36.224  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:36.224  1017  4290 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:36.224  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:36.234  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 17:40:36.234  7684  7684 E Zygote  : MountEmulatedStorage()
08-30 17:40:36.234  7684  7684 E Zygote  : v2
08-30 17:40:36.234  7684  7684 I libpersona: KNOX_SDCARD checking this for 10068
08-30 17:40:36.234  7684  7684 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:36.234  7684  7684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:36.234  7684  7684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:36.244  7684  7684 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 17:40:36.244  1017  4290 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7684 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-30 17:40:36.244  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 17:40:36.244  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  secondary type: null
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  wps: 0
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  grpcapab: 0
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  devcapab: 0
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  status: 3
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  wfdInfo: null
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-30 17:40:36.244  1017  1047 D WifiDisplayController:  SConnectInfo : null
08-30 17:40:36.244  1017  1469 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:40:36.244  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-30 17:40:36.244  1017  1125 D WifiP2pService: InactiveState
08-30 17:40:36.244  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-30 17:40:36.244  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:40:36.244  7598  7598 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:40:36.254  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-30 17:40:36.254  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:40:36.254  7684  7684 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:36.264  7684  7684 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:36.264   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:40:36.274  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:36.274  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 17:40:36.274  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:40:36.274  1017  1458 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:36.274  1017  1339 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-30 17:40:36.284  1017  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:36.284  1017  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:36.284  1017  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:36.284  1017  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:36.284  7684  7684 D BadgeProvider: onCreate,
,08-30 17:40:36.284  7684  7684 D BadgeProvider: DatabaseHelper
,08-30 17:40:36.294  7699  7699 E Zygote  : MountEmulatedStorage()
,08-30 17:40:36.294  7699  7699 E Zygote  : v2
,08-30 17:40:36.294  7699  7699 I libpersona: KNOX_SDCARD checking this for 10009
08-30 17:40:36.294  7699  7699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 17:40:36.294  7699  7699 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:36.294  7699  7699 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:40:36.304  7699  7699 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 17:40:36.304  1017  1339 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7699 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,08-30 17:40:36.304  1017  1339 I ActivityManager: Killing 6947:com.android.vending/u0a26 (adj 15): empty #21,
08-30 17:40:36.304  1017  1339 I ActivityManager: Killing 7162:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-30 17:40:36.324  7684  7693 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-30 17:40:36.324  7699  7699 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:36.334  7699  7699 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:36.354  7684  7693 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-30 17:40:36.354  7684  7693 D BadgeProvider: sendNotify, [notify] : null
08-30 17:40:36.354  7684  7693 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-30 17:40:36.354  7684  7693 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 17:40:36.354  1487  1487 D Launcher.Model: reloadBadges entered.
,08-30 17:40:36.354  7684  7693 D BadgeProvider: update, [UpdateCount] : 1
,08-30 17:40:36.394  5907  5907 D FactoryTest: Not factory mode
08-30 17:40:36.394  5907  5907 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 17:40:36.394  5907  5907 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-30 17:40:36.394  5907  5907 D MTPRx   : still no open session command from host, so toast
,08-30 17:40:36.404  1017  1485 I ActivityManager: Killing 7338:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-30 17:40:36.414  5907  5907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-30 17:40:36.414  5907  5907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 17:40:36.414  5907  5907 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118213
,08-30 17:40:36.414  1017  1135 E PersonaManagerService: inState():  stateMachine is null !!
,08-30 17:40:36.414  1017  1135 I PersonaManagerService: PersonaId don't exist
,08-30 17:40:36.414  1017  1135 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 17:40:36.434   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:40:36.434   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 17:40:36.454  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 17:40:36.454  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:36.454  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:36.454  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 17:40:36.454  1017  1135 W ActivityManager: mDVFSHelper.acquire()
,08-30 17:40:36.474  1017  1135 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:40:36.484  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:40:36.484  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 17:40:36.484  1017  1135 D InputDispatcher: Focused application set to: xxxx
,08-30 17:40:36.484  1017  1135 D InputDispatcher: Focus left window: 6828
,08-30 17:40:36.484  1017  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:36.484  5907  5907 E MTPRx   : started activity for popup
,08-30 17:40:36.484  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:36.484  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:36.484  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:36.484  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:36.494  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 17:40:36.494  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-30 17:40:36.494  1017  3835 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-30 17:40:36.494  2183  2183 I Hs20UtilService: Starting #12
,08-30 17:40:36.494  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-30 17:40:36.494  2183  2198 I Hs20UtilService: Message received 5011
,08-30 17:40:36.494  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:40:36.504  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-30 17:40:36.504  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:40:36.504  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:40:36.504  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:40:36.504  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:40:36.514  1017  3835 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:40:36.514  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:36.514  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:36.514  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:36.514  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:36.514  2183  2183 I Hs20UtilService: Starting #13
,08-30 17:40:36.514  2183  2198 I Hs20UtilService: Message received 5011
,08-30 17:40:36.514  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:40:36.514  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:40:36.514  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-30 17:40:36.514  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:40:36.524  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:40:36.524  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:40:36.524  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:40:36.524  5907  5907 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 17:40:36.524  5907  5907 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:40:36.524  5907  5907 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 17:40:36.524  5907  5907 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:36.524  5907  5907 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:40:36.524  5907  5907 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:40:36.534  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 17:40:36.534  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:40:36.534  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:36.534  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:40:36.534  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 17:40:36.534  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:40:36.534  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:36.534  1017  4291 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-30 17:40:36.534  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:36.534  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:36.534  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:36.534  1017  4291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:36.554  7719  7719 E Zygote  : MountEmulatedStorage()
,08-30 17:40:36.554  7719  7719 I libpersona: KNOX_SDCARD checking this for 10064
08-30 17:40:36.554  7719  7719 E Zygote  : v2
,08-30 17:40:36.554  7719  7719 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:36.554  7719  7719 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:36.554  7719  7719 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:36.554  1017  4291 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7719 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:40:36.554  7719  7719 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:36.564  5907  5907 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true,
,08-30 17:40:36.574  1017  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 17:40:36.574  7719  7719 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:36.574  1017  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:40:36.574  7719  7719 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:36.574  1017  1485 D InputDispatcher: Focused application set to: xxxx
,08-30 17:40:36.574  1017  1485 D InputDispatcher: Focus entered window: 6828
,08-30 17:40:36.584  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:40:36.584  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:40:36.584  1017  3835 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-30 17:40:36.584  1017  3835 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3e7136c8 attribute=null, token = android.os.BinderProxy@fd4b2df
,08-30 17:40:36.594  7719  7719 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:40:36.604  7719  7719 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:36.604  7719  7719 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:40:36.614  5907  5907 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 17:40:36.624  5907  5907 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 17:40:36.624  5907  5907 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 17:40:36.634  7719  7719 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:40:36.644  7355  7355 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:36.654  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:36.654  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:40:36.654  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-30 17:40:36.654  6828  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:40:36.654  6828  6828 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-30 17:40:36.654  1017  1480 I ActivityManager: Killing 7271:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
08-30 17:40:36.654  6828  6828 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 17:40:36.654  6828  6828 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 17:40:36.664  1017  1469 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 17:40:36.664  1017  1469 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 17:40:36.664  1017  1469 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 17:40:36.664  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 17:40:36.664  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 17:40:36.674  6828  6828 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 17:40:36.674  6828  6828 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 17:40:36.674  6828  6828 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21782f6e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@109886fc, 16908290=android.view.AbsSavedState$1@109886fc}, android:focusedViewId=100}]}]
08-30 17:40:36.674  6828  6828 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 17:40:36.674  6828  6828 V ActivityThread: updateVisibility : ActivityRecord{57bf8a0 token=android.os.BinderProxy@3d7c78d2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 17:40:36.674  6828  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 17:40:36.674  6828  6828 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 17:40:36.674  6828  6828 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d7c78d2 time:118475
,08-30 17:40:36.684  1017  3835 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:40:37.214   290   290 E SMD     : DCD OFF,
,08-30 17:40:37.264   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-30 17:40:37.444  7598  7598 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
,08-30 17:40:37.444  7598  7598 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 17:40:37.444  7598  7598 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 17:40:37.444  7598  7598 I wpa_supplicant: Trying to associate with  'G700'
,08-30 17:40:37.444  7598  7598 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-30 17:40:37.444  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-30 17:40:37.444  1017  7674 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 17:40:37.464  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:40:37.464  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:37.564  7598  7598 E wpa_supplicant: Cmd 35605 not handled
,08-30 17:40:37.564  7598  7598 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 17:40:37.564  7598  7598 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-30 17:40:37.564  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:37.564  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:37.564  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:37.564  7598  7598 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-30 17:40:37.564  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 17:40:37.564  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:37.564  7598  7598 I wpa_supplicant: Associated with F4.99.3E
08-30 17:40:37.564  7598  7598 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 17:40:37.564  7598  7598 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 17:40:37.564  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:37.564  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-30 17:40:37.564  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:37.564  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:37.564  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:37.564  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:37.564  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 17:40:37.564  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:40:37.564  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-30 17:40:37.564  1017  1130 E Tethering: No numeric data
,08-30 17:40:37.564  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:40:37.564  1017  1130 D Tethering: clearTetheredNotification()
,08-30 17:40:37.574  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:37.574  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:37.574  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:37.574  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:37.574  7598  7598 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-30 17:40:37.574  7598  7598 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 17:40:37.574  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:37.574  1017  1126 D SecContentProvider2: mCursor = null,
08-30 17:40:37.574  7598  7598 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 17:40:37.574  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 17:40:37.574  7598  7598 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:40:37.574  7598  7598 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-30 17:40:37.574  7598  7598 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 17:40:37.574  7598  7598 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 17:40:37.574  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:40:37.574  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:40:37.574  1178  1178 D HotspotTile: updateTetherState():false, false
,08-30 17:40:37.574  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 17:40:37.574  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:40:37.574  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-30 17:40:37.574  1017  1123 V NetworkStats: performPollLocked() took 6ms
08-30 17:40:37.574  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:37.574  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:37.574  1017  1126 D SecContentProvider2: mCursor = null
08-30 17:40:37.574  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:37.574  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:37.584  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 17:40:37.584  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 17:40:37.594  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:40:37.594  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 17:40:37.594  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 17:40:37.594  1017  1458 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:37.594  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:37.594  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:40:37.594  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:37.594  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:40:37.594  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:37.594  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:37.594  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:37.594  2183  2183 I Hs20UtilService: Starting #14
08-30 17:40:37.594  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:37.594  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:37.594  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.594  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.594  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.594  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.594  2183  2198 I Hs20UtilService: Message received 5007
,08-30 17:40:37.594  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:40:37.594  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:40:37.594  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:37.604  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:40:37.604  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:37.604  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:40:37.604  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:37.604  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:37.614   277  1016 D CommandListener: Setting iface cfg,
,08-30 17:40:37.614  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-30 17:40:37.614  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:40:37.614  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:37.624  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:37.624  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:40:37.624  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:40:37.624  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:37.624  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:37.624  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:37.624  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:37.634  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:40:37.634  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:37.634  1017  1126 E WifiNative-wlan0: do suspend false
,08-30 17:40:37.644  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:40:37.644  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:40:37.854  7738  7738 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 17:40:37.854  7738  7738 I dhcpcd  : version 5.5.6 starting,
,08-30 17:40:37.864  7738  7738 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 17:40:37.884  1017  1480 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-30 17:40:37.884  1017  1480 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:40:37.884  1017  1480 D SecContentProvider2: mCursor = null
,08-30 17:40:37.884  1017  1480 D WifiService: setWifiEnabled: false pid=6828, uid=10170
08-30 17:40:37.884  1017  1480 D SettingsProvider: name = wifi_on
,08-30 17:40:37.894  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-30 17:40:37.914  1017  1126 E WifiNative-wlan0: do suspend true,
,08-30 17:40:37.924  7738  7738 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-30 17:40:37.924  7738  7738 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-30 17:40:37.934  7738  7738 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-30 17:40:37.934  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:40:37.934  7738  7738 I dhcpcd  : bssid match
08-30 17:40:37.934   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:37.934  7738  7738 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
08-30 17:40:37.934  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:40:37.934  1017  1128 E ConnectivityService: updateNetworkInfo(),
,08-30 17:40:37.934  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:40:37.934  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
08-30 17:40:37.944   277  1016 E Netd    : no such netId 503
,08-30 17:40:37.944  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:40:37.944  1017  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)',
08-30 17:40:37.944  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:37.944  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 17:40:37.944  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:40:37.944  1017  1128 V NetworkStats: updateIfacesLocked()
08-30 17:40:37.944  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:37.944  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:37.944  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:37.944  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.944  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:37.944  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.944  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:37.944  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:37.944  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:37.954  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:40:37.954  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
08-30 17:40:37.954  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:40:37.954  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 17:40:37.954  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:37.954  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 17:40:37.954  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-30 17:40:37.954  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:37.954  1017  1128 V NetworkStats: performPollLocked() took 10ms
08-30 17:40:37.954  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:37.954  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:37.954  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:37.954  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:37.954  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.954  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.954  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:37.954  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:37.954  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:40:37.954  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:40:37.954  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:40:37.954  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:40:37.964  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 17:40:37.964  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:40:37.964  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 17:40:37.964  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:37.964  1017  1047 D WifiDisplayController: disconnect
08-30 17:40:37.964  1017  1047 D WifiDisplayController: updateConnection
08-30 17:40:37.964  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:37.964  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:40:37.964  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-30 17:40:37.964  1017  1458 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:37.964  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:40:37.964  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 17:40:37.964  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 17:40:37.964  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 17:40:37.964  1017  1125 D WifiP2pService: P2pDisablingState
08-30 17:40:37.964  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-30 17:40:37.964  1017  1125 D WifiP2pService: p2p socket connection lost
08-30 17:40:37.964  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:37.964  1017  1125 D WifiP2pService: P2pDisabledState
08-30 17:40:37.964  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:37.964  1017  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 17:40:37.964  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:37.964  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:37.964  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:40:37.964  1017  1126 E WifiNative-wlan0: do suspend true
,08-30 17:40:37.964  2183  2183 I Hs20UtilService: Starting #15
,08-30 17:40:37.964  2183  2198 I Hs20UtilService: Message received 5007
,08-30 17:40:37.964  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:40:37.964  1017  4291 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:40:37.964  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:37.964  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:37.964  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:40:37.974  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:40:37.974  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:40:37.974  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:40:37.974  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:40:37.974  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:40:37.974  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:40:37.974  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:37.974  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:40:37.974  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:37.974  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:40:37.974  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:37.984  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 17:40:37.984  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:40:37.984  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:37.984  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:40:37.984  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:37.984  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:40:37.984  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:37.984  7719  7719 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:37.984  7719  7719 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 17:40:37.984  7719  7719 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:40:37.994  7355  7355 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:37.994  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 17:40:38.004  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-30 17:40:38.004  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:38.004  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:40:38.004  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:40:38.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:38.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:38.004   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:38.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:38.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-30 17:40:38.014  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:40:38.014  7598  7598 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:40:38.024  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:38.024  1017  1126 D SecContentProvider2: mCursor = null
08-30 17:40:38.024  7738  7738 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-30 17:40:38.024  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:38.024  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:38.024  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:40:38.024  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:38.024  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:38.024  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:38.024  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:38.024  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:40:38.034  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:38.034  1017  3835 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:38.034  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:38.034  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:38.034  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:40:38.034  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:38.034  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:38.034  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:38.034  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:38.034  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:40:38.034  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:38.034  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:38.034  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-30 17:40:38.034  1178  1178 D HotspotTile: onReceive : 0, 0
08-30 17:40:38.034  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:38.034  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:38.034  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:40:38.034  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:38.034  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:38.034  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:38.034  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:38.034  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:38.034  2183  2183 I Hs20UtilService: Starting #16
08-30 17:40:38.034  2183  2198 I Hs20UtilService: Message received 5007,
08-30 17:40:38.044  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:40:38.044  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:40:38.044  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:40:38.044  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:38.044  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:38.044  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:40:38.044  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:38.044  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:40:38.044  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:38.054  1017  1458 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:40:38.054  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:38.054  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:38.054  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:38.054  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:38.054  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:40:38.054  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:40:38.054  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:40:38.054  2183  2183 I Hs20UtilService: Starting #17
08-30 17:40:38.054  2183  2198 I Hs20UtilService: Message received 5011
,08-30 17:40:38.054  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:40:38.174  7738  7738 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-30 17:40:38.274  7598  7598 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:40:38.394  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 17:40:38.394  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:38.394  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-30 17:40:38.394  7598  7598 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 17:40:38.414  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.414  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.414  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:38.414  1017  1130 D Tethering: InitialState.processMessage what=4
08-30 17:40:38.414  7598  7598 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-30 17:40:38.414  7598  7598 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 17:40:38.414  7598  7598 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-30 17:40:38.424  7598  7598 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 17:40:38.424  7598  7598 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:40:38.424  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:40:38.424  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.424  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:38.424  1017  1130 E Tethering: No numeric data
,08-30 17:40:38.424  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:40:38.424  1017  1130 D Tethering: clearTetheredNotification()
,08-30 17:40:38.424  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-30 17:40:38.424  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:38.424  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:40:38.424  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:40:38.424  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:40:38.424  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.424  1017  1123 V NetworkStats: performPollLocked() took 3ms
08-30 17:40:38.424  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:38.424  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-30 17:40:38.424  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:38.424  1178  1178 D HotspotTile: updateTetherState():false, false
08-30 17:40:38.424  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:38.424  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-30 17:40:38.564  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.564  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.564  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:38.754  7598  7598 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:40:38.874  7598  7598 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 17:40:38.884  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.884  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:38.884  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:38.984  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-30 17:40:38.984  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:40:38.984  7370  7370 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:40:39.004  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:39.004  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:40:39.004  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-30 17:40:39.004  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
,08-30 17:40:39.004  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:40:39.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 17:40:39.004  1178  1178 D HotspotTile: onReceive : 1, 0
,08-30 17:40:39.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 17:40:39.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:39.004  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:39.004  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-30 17:40:39.004  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-30 17:40:39.004  1630  2150 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-30 17:40:39.004  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:40:39.014  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:39.014  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:39.024  1017  3835 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:40:39.024  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:39.024  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:39.024  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:39.024  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:39.034  2183  2183 I Hs20UtilService: Starting #18
,08-30 17:40:39.034  2183  2198 I Hs20UtilService: Message received 5011
,08-30 17:40:39.034  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:40:39.034  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:40:39.034  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:40:39.034  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:40:39.464  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-30 17:40:39.584   277  1010 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-30 17:40:39.584  1017  1044 D Tethering: interfaceRemoved wlan0
,08-30 17:40:39.584  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 17:40:39.754  1017  1044 D Tethering: interfaceRemoved p2p0
,08-30 17:40:39.754  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 17:40:40.214   290   290 E SMD     : DCD OFF
,08-30 17:40:40.474  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-30 17:40:40.894  6828  7213 D BluetoothAdapter: enable()
,08-30 17:40:40.894  1017  4291 W ActivityManager: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,08-30 17:40:40.894  1017  4291 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-30 17:40:40.894  1017  4291 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:40:40.894  1017  4291 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:40:40.894  1017  4291 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 17:40:40.894  1017  4291 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 17:40:40.894  1017  4291 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 17:40:40.894  1017  4291 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:40:40.894  1017  4291 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:40:40.894  1017  4291 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:40:40.904  1017  4291 D SettingsProvider: name = bluetooth_on
,08-30 17:40:40.914  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-30 17:40:40.914  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:40:40.924  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 17:40:40.924  3189  3259 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-30 17:40:40.924  3189  3259 D BluetoothAdapterProperties: Setting state to 11
08-30 17:40:40.924  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 17:40:40.924  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:40:40.924  3189  3259 D BluetoothAdapterService: updateAdapterState state is 11
08-30 17:40:40.924  3189  3259 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:40:40.924  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-30 17:40:40.924  3189  3259 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
,08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10,
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:40.934  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:40.934  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService,
08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-30 17:40:40.924  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:40:40.924  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 17:40:40.934  3189  3259 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-30 17:40:40.934  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService,
08-30 17:40:40.934  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:40:40.934  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-30 17:40:40.954  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
,08-30 17:40:40.954  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:40.954  1178  1178 D BluetoothTile:  getBluetoothState : 11,
,08-30 17:40:40.954  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:40.954  1854  1854 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:40.964  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:40.964  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 17:40:40.964  1017  1859 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:40.964  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:40.974  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:40.974  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:40.974  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:40.974  1017  3835 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 17:40:40.974  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:40.984  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:40.984  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:40:40.984  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:40.984  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:40:40.984  3189  3189 D HeadsetService: Received start request. Starting profile...
08-30 17:40:40.984  3189  3189 D HeadsetService: start()
08-30 17:40:40.984  3189  3189 D HeadsetStateMachine: make
08-30 17:40:40.984  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:40:40.984  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 17:40:40.984  3189  3189 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 17:40:40.994  1017  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:40.994  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:40:40.994  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:40:40.994  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:40.994  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:40.994  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.004  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-30 17:40:41.004  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:41.004  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:40:41.004  1017  4291 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:41.004  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 17:40:41.004  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:40:41.004  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:41.004  1017  4291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.004  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.004  1017  1135 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-30 17:40:41.004  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-30 17:40:41.004  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:40:41.004  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:40:41.004  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 17:40:41.004  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.004  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.004  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:40:41.004  1017  4291 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:41.004  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.014  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:41.014  1017  4291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:41.014  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.014  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-30 17:40:41.014  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:40:41.014  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:40:41.014  1017  1859 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:41.024  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 17:40:41.024  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.024  1017  1859 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.024  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:41.024  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:41.024  1017  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 17:40:41.024  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.024  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 17:40:41.024  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:41.024  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:40:41.024  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.024  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.024  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:40:41.024  3189  3189 I bluedroid: get_profile_interface handsfree
,08-30 17:40:41.024  1017  1859 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:41.024  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.024  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.024  1017  1859 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.024  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.034  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:40:41.034  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:41.034  3189  3259 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:40:41.034  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:41.034  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 17:40:41.034  1017  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:41.034  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.044  3189  3189 E DualScoManager: Dual Sco Manager already instantiated
08-30 17:40:41.044  3189  3189 I DualScoManager: Set HeadsetServiceHelper
08-30 17:40:41.044  3189  3189 D BluetoothAtMessage: createCMTIContentObservers
,08-30 17:40:41.044  1017  1339 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 17:40:41.044  1017  1339 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:40:41.044  1017  1339 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:40:41.044  1017  1339 D SettingsProvider: selectionArgs: false
08-30 17:40:41.044  1017  1339 D SettingsProvider: selectionArgs: 1002
08-30 17:40:41.044  1017  1339 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:40:41.044  1017  1339 D SettingsProvider: ret = -1
,08-30 17:40:41.044  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:41.044  3189  7771 D HeadsetStateMachine: Enter Disconnected: -2
08-30 17:40:41.044  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.044  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:40:41.044  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-30 17:40:41.044  3189  3189 D HeadsetService: mStartError = false
08-30 17:40:41.044  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:41.044  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:40:41.044  3189  3189 D A2dpService: Received start request. Starting profile...
08-30 17:40:41.044  3189  3189 D A2dpService: start()
08-30 17:40:41.044  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:40:41.044  3189  3189 I bluedroid: get_profile_interface avrcp
08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:40:41.044  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:40:41.044  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:40:41.044  3189  3259 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 17:40:41.044  3189  7771 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 17:40:41.044  3189  7771 D HeadsetStateMachine: map size, before remove : 0
08-30 17:40:41.044  1017  3835 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-30 17:40:41.044  3189  7771 D HeadsetStateMachine: map size, after remove: 0
,08-30 17:40:41.054  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:41.054  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:41.054  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:41.054  1017  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:41.054  3189  3189 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 17:40:41.054  3189  3189 D Avrcp   : Initialize Media Controller
08-30 17:40:41.054  3189  3189 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-30 17:40:41.054  3189  3189 E Avrcp   : getActiveSessions
08-30 17:40:41.054  3189  3189 D Avrcp   : pick active media Controller
08-30 17:40:41.054  3189  3189 D Avrcp   : Get the active Media Controller 
,08-30 17:40:41.074  7773  7773 E Zygote  : MountEmulatedStorage()
08-30 17:40:41.074  7773  7773 E Zygote  : v2
08-30 17:40:41.074  7773  7773 I libpersona: KNOX_SDCARD checking this for 10055
08-30 17:40:41.074  7773  7773 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:41.074  7773  7773 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:41.074  7773  7773 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:41.074  7773  7773 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:41.084  1017  3835 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7773 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-30 17:40:41.084  3189  3189 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 17:40:41.094  3189  7772 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 17:40:41.094  3189  3189 D A2dpStateMachine: make
,08-30 17:40:41.094  3189  3189 I bluedroid: get_profile_interface a2dp
,08-30 17:40:41.094  3189  7787 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 17:40:41.094  3189  3189 E bt-btif : warning : media task started media_task_refcnt 1 
08-30 17:40:41.094  3189  3189 D A2dpService: mStartError = false
08-30 17:40:41.094  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40,
,08-30 17:40:41.104  3189  3189 D HidService: Received start request. Starting profile...
08-30 17:40:41.104  3189  3189 D HidService: start()
08-30 17:40:41.104  3189  3189 I bluedroid: get_profile_interface hidhost
08-30 17:40:41.104  3189  7781 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:40:41.104  3189  3189 D HidService: setHidService(): set to: null
08-30 17:40:41.104  3189  3189 D HidService: mStartError = false
08-30 17:40:41.104  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:41.104  1423  3324 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 17:40:41.104  3189  3189 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 17:40:41.104  1017  3351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:40:41.104  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-30 17:40:41.104  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 17:40:41.104  1423  3324 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 17:40:41.104  3189  3189 D HealthService: Received start request. Starting profile...
,08-30 17:40:41.104  3189  3189 D HealthService: start()
,08-30 17:40:41.104  7773  7773 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:41.114  7773  7773 D ActivityThread: Added TimaKeyStore provider
08-30 17:40:41.114  3189  7772 D BluetoothMediaBrowser: no now playing list
08-30 17:40:41.114  3189  7772 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-30 17:40:41.114  3189  3189 I bluedroid: get_profile_interface health
08-30 17:40:41.114  1017  3333 D SSRM:n  : SIOP:: AP = 380
08-30 17:40:41.114  3189  3189 D HealthService: mStartError = false
08-30 17:40:41.114  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:41.114  3189  3189 D PanService: Received start request. Starting profile...
08-30 17:40:41.114  3189  3189 D PanService: start()
08-30 17:40:41.114  3189  3189 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:40:41.114  3189  3189 I bluedroid: get_profile_interface pan
08-30 17:40:41.114  3189  3189 D PanService: mStartError = false
08-30 17:40:41.114  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:41.114  3189  3189 D HeadsetStateMachine: Proxy object connected
08-30 17:40:41.114  3189  3189 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 17:40:41.114  3189  7771 D HeadsetStateMachine: Disconnected process message: 11
,08-30 17:40:41.114  3189  3189 D BluetoothMapService: Received start request. Starting profile...
08-30 17:40:41.114  3189  3189 D BluetoothMapService: start()
,08-30 17:40:41.124  3189  3189 D BluetoothMapService: mStartError = false
,08-30 17:40:41.124  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:41.124  3189  3189 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 17:40:41.124  3189  3189 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-30 17:40:41.124  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-30 17:40:41.124  3189  7771 D HeadsetStateMachine: Disconnected process message: 18
,08-30 17:40:41.124  3189  3189 D SapService: Received start request. Starting profile...
,08-30 17:40:41.124  3189  3189 D SapService: start()
08-30 17:40:41.124  3189  3189 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 17:40:41.124  3189  3189 I bluedroid: get_profile_interface sap
08-30 17:40:41.124  3189  3189 D SapService: mStartError = false
08-30 17:40:41.124  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:41.124  3189  3189 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 17:40:41.124  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 17:40:41.124  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 17:40:41.124  3189  7771 D HeadsetStateMachine: Disconnected process message: 10
08-30 17:40:41.124  3189  7771 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:40:41.124  3189  7771 D HeadsetStateMachine: Disconnected process message: 11
,08-30 17:40:41.124  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-30 17:40:41.124  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 17:40:41.144  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 17:40:41.144  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 17:40:41.144  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-30 17:40:41.144  3189  3259 I bluedroid: enable
,08-30 17:40:41.154  7773  7773 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 17:40:41.154  3189  3262 E bt-btif : Calling BTA_HhEnable
,08-30 17:40:41.154  3189  3262 E bt-btif : BTA got event 0x1f16
,08-30 17:40:41.154  3189  3262 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 17:40:41.154  3189  3262 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 17:40:41.154  3189  3262 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-30 17:40:41.154  3189  3262 E BluetoothServiceJni: populateRssiValuesNative
08-30 17:40:41.154  3189  3262 I bluedroid: getModelRssiValues
,08-30 17:40:41.154  3189  3262 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 17:40:41.154  3189  3262 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:40:41.154  1017  1095 V AlarmManager: waitForAlarm result :4
,08-30 17:40:41.154  1017  1017 D SettingsProvider: name = bluetooth_name
,08-30 17:40:41.154  3189  3262 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-30 17:40:41.164  3189  3262 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 17:40:41.164  3189  3262 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:40:41.164  3189  3262 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:40:41.164  3189  3262 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-30 17:40:41.164  3189  3262 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-30 17:40:41.164  3189  3262 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-30 17:40:41.164  3189  3262 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 17:40:41.164  3189  3262 E bt-btif : JVenable fails
,08-30 17:40:41.164  3189  3262 D bte_conf: Device ID record 1 : primary
08-30 17:40:41.164  3189  3262 D bte_conf:   vendorId            = 0075
08-30 17:40:41.164  3189  3262 D bte_conf:   vendorIdSource      = 0001
08-30 17:40:41.164  3189  3262 D bte_conf:   product             = 0100
08-30 17:40:41.164  3189  3262 D bte_conf:   version             = 0200
08-30 17:40:41.164  3189  3262 D bte_conf:   clientExecutableURL = 
08-30 17:40:41.164  3189  3262 D bte_conf:   serviceDescription  = 
08-30 17:40:41.164  3189  3262 D bte_conf:   documentationURL    = 
08-30 17:40:41.164  3189  3262 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 17:40:41.164  3189  3262 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 17:40:41.164  3189  3262 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:40:41.164  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 17:40:41.164  3189  3259 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:40:41.164  3189  3259 D BluetoothAdapterProperties: State =  11
,08-30 17:40:41.164  1017  1480 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:40:41.164  3189  3259 D BluetoothAdapterProperties: Setting state to 12
08-30 17:40:41.164  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 17:40:41.164  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:41.174  3189  3262 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:40:41.174  3189  3262 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:40:41.174  3189  3262 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:40:41.174  1017  4290 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 17:40:41.174  1017  4290 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:40:41.174  1017  4290 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:40:41.174  1017  4290 D SettingsProvider: selectionArgs: false
,08-30 17:40:41.174  1017  4290 D SettingsProvider: selectionArgs: 1002
,08-30 17:40:41.174  1017  4290 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:40:41.174  1017  4290 D SettingsProvider: ret = -1
,08-30 17:40:41.174  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 17:40:41.174  3189  3259 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 17:40:41.174  1017  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:41.174  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.174  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.174  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.174  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.184  3189  3259 D BluetoothAdapterService: Autoconnection is available 
08-30 17:40:41.184  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 17:40:41.184  3189  3259 D BluetoothAdapterService: starting service from this receiver
,08-30 17:40:41.184  4765  4774 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:40:41.184  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:41.184  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.184  3189  3189 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-30 17:40:41.184  3189  3189 I BluetoothPbapService: Handler(): got msg=1
08-30 17:40:41.184  4765  4774 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:41.184  1017  1859 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:40:41.184  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.184  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.184  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.184  3189  3259 I BluetoothAdapterState: Entering On State from state = 11
,08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:41.184  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:41.184  7773  7773 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 17:40:41.194  3189  3197 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:41.194  7773  7773 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-30 17:40:41.194  7773  7773 D UserAnalysis: Create SecureDbHelper
,08-30 17:40:41.194  3189  3197 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.194  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:40:41.194  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 17:40:41.194  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:41.194  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.194  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.194  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.204  7773  7773 D IntelligenceServiceApplication: onCreate()
,08-30 17:40:41.204  1423  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:41.204  1423  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:41.204  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:40:41.204  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.204  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:40:41.204  3189  7795 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 17:40:41.204  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:41.204  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:41.204  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:41.214  1017  1030 I ActivityManager: Killing 7293:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-30 17:40:41.214  7773  7773 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-30 17:40:41.214  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:41.214  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 17:40:41.214  1423  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.214  1017  1017 D BluetoothA2dp: Proxy object connected
08-30 17:40:41.214  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:41.214  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:41.214  7773  7773 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-30 17:40:41.214  3189  3189 D BluetoothA2dp: Proxy object connected
08-30 17:40:41.214  3189  3189 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-30 17:40:41.214  3189  7795 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:40:41.214  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.214  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.214  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.214  3189  7795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:41.224  1423  1451 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:41.224  1443  2164 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.224  3189  7795 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-30 17:40:41.224  3189  7795 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:40:41.224  3189  7795 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:40:41.224  3189  7795 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7e46745
,08-30 17:40:41.224  3189  7795 D BluetoothSocket: channel: 19
08-30 17:40:41.224  3189  7795 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 17:40:41.224  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:41.224  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:41.224  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.224  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.224  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.224  1443  2164 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:41.224  7773  7773 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 17:40:41.224  4765  4773 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:40:41.234  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 17:40:41.234  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.234  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.234  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.234  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.234  1017  1046 D BluetoothPan: Binding service...
,08-30 17:40:41.234  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:40:41.234  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.234  1443  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:41.234  1443  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:41.234  4765  4773 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.234  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 17:40:41.234  4765  4765 D BluetoothPbap: Proxy object connected
08-30 17:40:41.234  4765  4765 D PbapServerProfile: Bluetooth service connected
08-30 17:40:41.234  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:41.234  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:41.234  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.234  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.234  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.234  4765  4773 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:41.234  1178  5924 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:41.234  1178  5924 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:41.234  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.234  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:41.234  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 17:40:41.234  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:41.244  4765  4765 D HeadsetProfile: Bluetooth service connected
,08-30 17:40:41.254   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-30 17:40:41.254   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 17:40:41.254  1017  1046 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #12
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: android.os.DeadObjectException
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:40:41.254  1017  1046 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 17:40:41.254  1630  1640 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:41.254  1630  1640 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:41.254  4765  4774 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:40:41.264  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:41.264  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:41.264  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-30 17:40:41.264  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-30 17:40:41.264  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:41.264  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-30 17:40:41.264  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.264  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.274  1423  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 17:40:41.274  4765  4765 D BluetoothMap: Proxy object connected
08-30 17:40:41.274  4765  4765 D MapProfile: Bluetooth service connected
08-30 17:40:41.274  4765  4765 D BluetoothMap: getConnectedDevices()
,08-30 17:40:41.274  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:41.274  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:41.274  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.274  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.274  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.274  1423  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:41.274  3189  3306 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:41.274  3189  3306 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:41.274  4765  7797 D BluetoothPan: Binding service...
,08-30 17:40:41.274  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:40:41.274  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.274  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.274  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.274  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.274  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:41.274  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:41.274  4765  4765 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:40:41.274  4765  4765 D PanProfile: Bluetooth service connected
,08-30 17:40:41.284  1430  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:40:41.284  1430  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:41.284  4765  4773 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:41.284  4765  4773 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.284  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:40:41.284  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.284  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.284  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.284  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.284  4765  7797 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:40:41.284  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-30 17:40:41.284  4765  4765 D BluetoothA2dp: Proxy object connected
08-30 17:40:41.284  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.284  4765  4765 D A2dpProfile: Bluetooth service connected
08-30 17:40:41.294  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.294  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.294  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.294  1423  3324 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:41.294  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:40:41.294  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:41.294  4765  4765 D BluetoothInputDevice: Proxy object connected
08-30 17:40:41.294  4765  4765 D HidProfile: Bluetooth service connected
,08-30 17:40:41.294  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.294  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.294  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.294  1423  3324 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:41.294  1655  4320 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:40:41.294  1655  4320 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:41.294  4765  4774 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 17:40:41.294  4765  4774 D Bluetoothsap: Binding service...
,08-30 17:40:41.304  4765  4774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 17:40:41.304  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-30 17:40:41.304  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.304  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:41.304  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.304  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.304  4765  4774 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 17:40:41.304  6828  6841 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:40:41.304  6828  6841 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:41.304  4765  4765 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-30 17:40:41.304  4765  4765 D SapProfile: Bluetooth service connected
08-30 17:40:41.304  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 17:40:41.304  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-30 17:40:41.304  4765  4765 D Bluetoothsap: getConnectedDevices()
,08-30 17:40:41.304  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:41.304  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
,08-30 17:40:41.304  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:40:41.314  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:40:41.314  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@111d80f7, true
,08-30 17:40:41.314  1423  1423 D BluetoothHeadset: registerMessageListener
,08-30 17:40:41.314  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:40:41.314  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:41.314  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-30 17:40:41.314  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:41.314  1854  1854 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:41.324  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:41.324  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:41.334  3189  7770 D HeadsetService: registerMessageListener
,08-30 17:40:41.334  3189  7770 D HeadsetService: registerMessageListener
08-30 17:40:41.334  3189  7771 D HeadsetStateMachine: Disconnected process message: 70
,08-30 17:40:41.334  3189  7771 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@18152e9a
,08-30 17:40:41.334  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:41.334  4765  4765 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-30 17:40:41.334  4765  4765 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-30 17:40:41.334  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 17:40:41.334  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 17:40:41.334  1017  1458 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-30 17:40:41.334  3189  7800 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 17:40:41.334  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:41.334  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:41.334  4765  4765 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-30 17:40:41.334  4765  4765 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 17:40:41.334  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 17:40:41.334  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 17:40:41.344  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
08-30 17:40:41.344  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 17:40:41.344  3189  7800 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 17:40:41.344  3189  7800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:41.344  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:41.344  3189  7771 D HeadsetStateMachine: Disconnected process message: 9
08-30 17:40:41.344  3189  7800 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-30 17:40:41.344  3189  7800 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:40:41.344  3189  7800 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:40:41.344  3189  7800 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a53f3cb
,08-30 17:40:41.344  3189  7800 D BluetoothSocket: channel: 5
08-30 17:40:41.344  3189  7771 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 17:40:41.344   285   690 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 17:40:41.344   285   690 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 17:40:41.344   285   690 V voice   : voice_set_parameters: exit with code(-2)
08-30 17:40:41.344   285   690 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 17:40:41.344   285   690 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 17:40:41.344   285   690 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 17:40:41.344   285   690 V audio_hw_primary: adev_set_parameters: exit
,08-30 17:40:41.344  3189  7771 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 17:40:41.354  4765  4765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:41.354  1017  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings,
08-30 17:40:41.354  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.354  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-30 17:40:41.354  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.354  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:40:41.364  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:41.364  4765  4765 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:41.364  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:41.374  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:41.374  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 17:40:41.374  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:41.374  3189  3189 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 17:40:41.374  1017  3835 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:41.374  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 17:40:41.374  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:41.374  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:41.374  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:41.384  1017  1859 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-30 17:40:41.384  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:41.384  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:41.384  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:41.384  1017  1859 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:41.404  7803  7803 E Zygote  : MountEmulatedStorage(),
08-30 17:40:41.404  7803  7803 I libpersona: KNOX_SDCARD checking this for 10105
08-30 17:40:41.404  7803  7803 E Zygote  : v2
,08-30 17:40:41.404  7803  7803 I libpersona: KNOX_SDCARD not a persona
08-30 17:40:41.404  7803  7803 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:41.404  7803  7803 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 17:40:41.404  1017  1859 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7803 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-30 17:40:41.404  1017  1458 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-30 17:40:41.404  7803  7803 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:40:41.414  3189  7813 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:40:41.414  3189  7813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:41.414  3189  7813 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
08-30 17:40:41.414  3189  7813 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:40:41.414  3189  7813 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:40:41.414  3189  7813 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cac01a7
,08-30 17:40:41.414  3189  7813 D BluetoothSocket: channel: 12
08-30 17:40:41.414  3189  7813 I BtOppRfcommListener: Accept thread started.
,08-30 17:40:41.444  7803  7803 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:41.444  7803  7803 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:41.574   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:40:41.574   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:41.584  7803  7823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:40:41.584   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 17:40:41.584   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:40:41.584  7803  7823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:40:41.744  1017  1480 I ActivityManager: Killing 7411:com.sec.pcw.device/1000 (adj 15): empty #21
08-30 17:40:41.744  7803  7803 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:40:41.744  7803  7803 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 17:40:41.794  7803  7834 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 17:40:41.964  1017  1859 I art     : Explicit concurrent mark sweep GC freed 69953(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/34MB, paused 2.359ms total 142.585ms
,08-30 17:40:41.964  1017  1859 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:40:41.964  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:41.964  1017  1859 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:41.964  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 17:40:42.264   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:40:43.224   290   290 E SMD     : DCD OFF,
,08-30 17:40:43.264   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:40:43.914  6828  7213 D BluetoothAdapter: disable(),
08-30 17:40:43.914  1017  3835 D SettingsProvider: name = bluetooth_on
,08-30 17:40:43.924  3189  3259 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-30 17:40:43.924  3189  3259 D BluetoothAdapterProperties: Setting state to 13
,08-30 17:40:43.924  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 17:40:43.924  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 17:40:43.924  3189  3259 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 17:40:43.934  1017  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:43.934  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:40:43.934  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:43.934  1017  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:43.934  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:43.934  3189  3189 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 17:40:43.934  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1be7c654, channel: 19, state: LISTENING
,08-30 17:40:43.934  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1be7c654, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7e46745, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@391539fdmSocket: android.net.LocalSocket@1c62f6f2 impl:android.net.LocalSocketImpl@2e8d1143 fd:FileDescriptor[80]
,08-30 17:40:43.934  3189  3259 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:40:43.934  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 17:40:43.934  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c62f6f2 impl:android.net.LocalSocketImpl@2e8d1143 fd:FileDescriptor[80]
,08-30 17:40:43.934  3189  3259 D BluetoothAdapterService: terminating service from this receiver
,08-30 17:40:43.944  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:40:43.944  4765  4765 D BluetoothPbap: Proxy object disconnected
08-30 17:40:43.944  4765  4765 D PbapServerProfile: Bluetooth service disconnected
08-30 17:40:43.944  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:43.944  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:43.944  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:43.944  3189  3259 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:40:43.944  3189  3259 D BluetoothAdapterProperties: mDiscovering is false
,08-30 17:40:43.944  1017  1480 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-30 17:40:43.944  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:43.944  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-30 17:40:43.944  3189  3259 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 17:40:43.954  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:40:43.954  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:40:43.954  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:43.954  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:43.954  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-30 17:40:43.964  1854  1854 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:43.964  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:43.964  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:43.964  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:40:43.974  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:43.974  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:43.974  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:43.974  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:43.984  1017  1339 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:43.984  1017  1469 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:40:43.984  3189  3262 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 17:40:43.984  3189  3262 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:40:43.984  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:40:43.994  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-30 17:40:43.994  3189  3259 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 17:40:43.994  3189  3259 E bt-btif : cmd socket is not created
,08-30 17:40:43.994  3189  3259 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 17:40:43.994  3189  3263 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-30 17:40:43.994  3189  7813 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:40:43.994  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:43.994  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:43.994  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:40:43.994  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:44.004  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:40:44.004  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:40:44.004  3189  3263 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:40:44.004  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:40:44.004  3189  3263 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:40:44.004  3189  3263 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 17:40:44.004  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:44.004  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a8078f9, channel: 5, state: LISTENING
08-30 17:40:44.004  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a8078f9, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a53f3cb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1725903emSocket: android.net.LocalSocket@1ae57e9f impl:android.net.LocalSocketImpl@2e458bec fd:FileDescriptor[82]
08-30 17:40:44.004  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ae57e9f impl:android.net.LocalSocketImpl@2e458bec fd:FileDescriptor[82]
,08-30 17:40:44.004  3189  3189 I BtOppRfcommListener: stopping Accept Thread
08-30 17:40:44.004  3189  3189 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8c6abb5, channel: 12, state: LISTENING
08-30 17:40:44.004  3189  3189 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8c6abb5, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cac01a7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7e6724amSocket: android.net.LocalSocket@32d65bb impl:android.net.LocalSocketImpl@18f57ad8 fd:FileDescriptor[87]
08-30 17:40:44.004  3189  3189 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32d65bb impl:android.net.LocalSocketImpl@18f57ad8 fd:FileDescriptor[87]
,08-30 17:40:44.004  3189  7813 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 17:40:44.004  4765  4765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:44.004  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:40:44.004  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.014  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:44.014  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:44.014  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:40:44.014  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:44.014  3189  3189 V BluetoothOppManager: cleanUp...
,08-30 17:40:44.024  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:44.024  4765  4765 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:44.034  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:44.034  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:44.034  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 17:40:44.194  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 17:40:44.194  3189  3259 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:40:44.194  3189  3259 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 17:40:44.194  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-30 17:40:44.194  3189  3259 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-30 17:40:44.194  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 17:40:44.194  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:40:44.194  1017  3835 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:44.194  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 17:40:44.194  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.194  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:44.194  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:44.194  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:44.194  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:40:44.194  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:40:44.194  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 17:40:44.194  1017  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:44.194  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.204  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:44.204  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:44.204  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:44.204  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-30 17:40:44.204  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:40:44.204  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:40:44.204  3189  3189 D HeadsetService: Received stop request...Stopping profile...
,08-30 17:40:44.204  1017  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:44.204  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.204  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:44.214  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:44.214  1017  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:44.214  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:44.214  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-30 17:40:44.214  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 17:40:44.214  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:40:44.214  1017  1859 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:44.214  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.214  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:44.214  1017  1859 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:44.214  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:44.214  4765  4765 D HeadsetProfile: Bluetooth service disconnected
,08-30 17:40:44.214  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 17:40:44.224  3189  3189 D A2dpService: Received stop request...Stopping profile...,
08-30 17:40:44.224  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-30 17:40:44.224  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:40:44.224  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 17:40:44.224  3189  7781 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:40:44.224  1017  1224 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:44.224  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.224  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:44.224  1017  1224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-30 17:40:44.224  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-30 17:40:44.224  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:44.234  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:44.234  1017  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:44.234  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 17:40:44.234  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.234  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.234  4765  4765 D BluetoothA2dp: Proxy object disconnected
08-30 17:40:44.234  4765  4765 D A2dpProfile: Bluetooth service disconnected
08-30 17:40:44.234  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:44.234  1017  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:44.234  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:40:44.234  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-30 17:40:44.234  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:44.234  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.234  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:44.234  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:44.234  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:40:44.234  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:44.234  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:40:44.234  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:40:44.234  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:40:44.234  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:40:44.234  3189  3259 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:40:44.234  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 17:40:44.234  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:44.234  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 17:40:44.234  3189  3189 D HidService: Received stop request...Stopping profile...
,08-30 17:40:44.234  3189  3189 D HidService: Stopping Bluetooth HidService
08-30 17:40:44.234  3189  3189 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:40:44.234  3189  3189 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 17:40:44.234  3189  3189 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:40:44.234  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:44.244  4765  4765 D BluetoothInputDevice: Proxy object disconnected
,08-30 17:40:44.244  4765  4765 D HidProfile: Bluetooth service disconnected
,08-30 17:40:44.244  3189  3189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 17:40:44.244  3189  3189 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 17:40:44.244  3189  3189 D HealthService: Received stop request...Stopping profile...
08-30 17:40:44.244  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:44.254  3189  3189 D PanService: Received stop request...Stopping profile...
,08-30 17:40:44.254  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:44.254  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 17:40:44.254  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-30 17:40:44.254  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:40:44.254  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 17:40:44.254  3189  3189 D BluetoothA2dp: Proxy object disconnected
,08-30 17:40:44.254  3189  3189 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 17:40:44.254  3189  7787 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 17:40:44.254  3189  3189 I GKI_LINUX: GKI_exit_task 2 done
,08-30 17:40:44.254  3189  3189 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 17:40:44.254  3189  3189 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 17:40:44.254  4765  4765 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:40:44.254  4765  4765 D PanProfile: Bluetooth service disconnected
,08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:44.264  4765  4765 D BluetoothMap: Proxy object disconnected
08-30 17:40:44.264  4765  4765 D MapProfile: Bluetooth service disconnected
08-30 17:40:44.264  3189  3189 D SapService: Received stop request...Stopping profile...
08-30 17:40:44.264  3189  3189 D SapService: Stopping Bluetooth SapService
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:44.264  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:44.264  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.264  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:44.264  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.264  3189  3189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:40:44.264  3189  3189 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:40:44.264  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:44.264  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:44.264  3189  3189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:40:44.264  3189  3189 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 17:40:44.264   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:40:44.264  4765  4765 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 17:40:44.264  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 17:40:44.264  3189  3189 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-30 17:40:44.264  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 17:40:44.264  4765  4765 D SapProfile: Bluetooth service disconnected
08-30 17:40:44.264  3189  3189 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-30 17:40:44.264  3189  3189 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 17:40:44.264  3189  3189 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 17:40:44.274  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:40:44.274  3189  3259 D BluetoothAdapterProperties: Setting state to 10
08-30 17:40:44.274  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:40:44.274  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:40:44.274  3189  3259 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 17:40:44.274  3189  3259 D BluetoothAdapterService: Autoconnection is available 
08-30 17:40:44.274  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 17:40:44.274  3189  3259 I BluetoothAdapterState: Entering OffState
,08-30 17:40:44.274  4765  4773 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:44.274  4765  4773 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.274  3189  3337 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:40:44.274  1423  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.274  1423  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:44.274  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:40:44.274  7803  7814 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.274  7803  7814 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.274  4765  7797 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 17:40:44.274  1443  2164 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.274  1443  2164 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.274  1178  2330 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.274  1178  2330 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.284  1630  1640 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:44.284  1630  1640 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.284  4765  4773 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 17:40:44.284  3189  3202 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:40:44.284  3189  3202 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.284  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.284  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:44.284  1430  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.284  1430  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:40:44.284  4765  4774 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:40:44.284  4765  4773 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 17:40:44.284  1655  4320 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.284  1655  4320 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.284  4765  7797 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 17:40:44.284  4765  7797 D Bluetoothsap: Unbinding service...
,08-30 17:40:44.294  6828  6841 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:40:44.294  6828  6841 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:40:44.294  6828  6841 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 17:40:44.294  6828  6841 D BluetoothLeAdvertiser: Exit stop advertising
,08-30 17:40:44.294  6828  6841 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 17:40:44.294  6828  6841 D BluetoothLeScanner: Exiting stopAllScan
,08-30 17:40:44.294  1017  1224 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:40:44.294  1017  1224 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4221, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 17:40:44.294  1017  1224 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:40:44.294  1017  1224 D BatteryService: stay LED for charging
08-30 17:40:44.294  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:40:44.294  1017  1017 I MotionRecognitionService: Plugged
,08-30 17:40:44.294  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:40:44.304  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:40:44.304  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:40:44.304  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:40:44.304  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,08-30 17:40:44.314  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:44.314  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-30 17:40:44.314  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:40:44.324  1854  1854 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:44.324  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:44.324  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
08-30 17:40:44.324  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:44.324  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:44.324  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:44.324  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:40:44.324  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:44.334  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-30 17:40:44.334  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:44.334  1017  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:44.334  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:40:44.334  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:44.334  4765  4765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:44.334  1017  4291 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:40:44.334  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:40:44.334  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:44.334  1017  4291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:44.334  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:40:44.344  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:44.354  4765  4765 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:44.354  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:40:44.354  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:44.374  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:44.374  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 17:40:45.264   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:40:46.224   290   290 E SMD     : DCD OFF
,08-30 17:40:46.264   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:40:46.924  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:46.924  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:47.264   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 17:40:49.224   290   290 E SMD     : DCD OFF,
,08-30 17:40:49.934  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:49.934  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cfa7185 added. We now have 6 listener(s)
08-30 17:40:49.934  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:49.934  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:49.934  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7170bda added. We now have 7 listener(s)
,08-30 17:40:49.934  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:49.934  6828  7213 I System.out: IsBluetoothEnabled
,08-30 17:40:49.934  6828  7213 D BluetoothAdapter: disable()
,08-30 17:40:49.944  1017  1224 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-30 17:40:49.944  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:49.944  6828  7213 D BluetoothAdapter: enable()
,08-30 17:40:49.944  1017  1859 W ActivityManager: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:40:49.944  1017  1859 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 17:40:49.944  1017  1859 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:40:49.944  1017  1859 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:40:49.944  1017  1859 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 17:40:49.944  1017  1859 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 17:40:49.944  1017  1859 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 17:40:49.944  1017  1859 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:40:49.944  1017  1859 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:40:49.944  1017  1859 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:40:49.954  1017  1859 D SettingsProvider: name = bluetooth_on
,08-30 17:40:49.964  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:40:49.964  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:40:49.974  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 17:40:49.974  3189  3259 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
08-30 17:40:49.974  3189  3259 D BluetoothAdapterProperties: Setting state to 11
08-30 17:40:49.974  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 17:40:49.974  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-30 17:40:49.974  3189  3259 D BluetoothAdapterService: updateAdapterState state is 11
08-30 17:40:49.974  1017  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:49.974  3189  3259 D BluetoothAdapterService: Autoconnection is available 
08-30 17:40:49.974  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 17:40:49.974  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-30 17:40:49.974  3189  3259 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
,08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 17:40:49.974  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:40:49.974  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 17:40:49.974  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:49.974  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:49.974  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:49.984  3189  3189 D HeadsetService: Received start request. Starting profile...,
08-30 17:40:49.984  3189  3189 D HeadsetService: start()
08-30 17:40:49.984  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:49.984  3189  3189 D HeadsetStateMachine: make
08-30 17:40:49.984  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
08-30 17:40:49.984  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:40:49.984  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:40:49.984  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 17:40:49.984  3189  3189 E HeadsetStateMachine: # of Max HF connection is 2,
,08-30 17:40:49.994  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:40:49.994  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:49.994  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-30 17:40:49.994  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
08-30 17:40:49.994  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:40:50.004  1854  1854 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:50.004  1017  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:50.004  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:40:50.004  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:50.004  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-30 17:40:50.004  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:50.004  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:50.004  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 17:40:50.004  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.004  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.004  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.014  1017  4291 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 17:40:50.014  1017  4291 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.014  1017  4291 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.014  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-30 17:40:50.014  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:40:50.014  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:40:50.014  1017  4291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.014  1017  4291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:40:50.014  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:50.024  1017  1859 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:50.024  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.024  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.024  1017  1859 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:50.024  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.024  1017  3835 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-30 17:40:50.024  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.024  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService,
08-30 17:40:50.024  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:40:50.024  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:40:50.024  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.024  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.024  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:40:50.024  1017  1339 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:50.024  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.024  3189  3189 I bluedroid: get_profile_interface handsfree,
08-30 17:40:50.024  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.024  1017  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:50.024  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.034  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-30 17:40:50.034  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:40:50.034  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:40:50.034  1017  1339 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:50.034  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.034  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.034  1017  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:50.034  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.034  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-30 17:40:50.034  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:40:50.034  3189  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-30 17:40:50.044  1017  1224 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:50.044  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.044  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.044  1017  1224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.044  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:50.044  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:50.044  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-30 17:40:50.044  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:40:50.044  3189  3259 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:40:50.044  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:50.044  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.044  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:50.044  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-30 17:40:50.044  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.054  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:50.054  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.054  3189  3189 E DualScoManager: Dual Sco Manager already instantiated,
08-30 17:40:50.054  3189  3189 I DualScoManager: Set HeadsetServiceHelper
08-30 17:40:50.054  3189  3189 D BluetoothAtMessage: createCMTIContentObservers
08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:50.054  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:50.054  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService,
08-30 17:40:50.054  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:40:50.054  3189  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
08-30 17:40:50.054  3189  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:40:50.054  3189  3259 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
08-30 17:40:50.054  1017  1030 D SettingsProvider: name = bluetooth_hfp_allowed_bvra,
,08-30 17:40:50.054  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:40:50.054  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:40:50.054  1017  1030 D SettingsProvider: selectionArgs: false
08-30 17:40:50.054  1017  1030 D SettingsProvider: selectionArgs: 1002
08-30 17:40:50.054  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:40:50.054  1017  1030 D SettingsProvider: ret = -1
08-30 17:40:50.054  3189  7848 D HeadsetStateMachine: Enter Disconnected: -2,
08-30 17:40:50.054  3189  3189 D HeadsetService: mStartError = false
08-30 17:40:50.054  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:50.054  3189  3189 D A2dpService: Received start request. Starting profile...
,08-30 17:40:50.054  3189  3189 D A2dpService: start()
08-30 17:40:50.054  3189  3189 I bluedroid: get_profile_interface avrcp
08-30 17:40:50.064  3189  7848 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 17:40:50.064  3189  7848 D HeadsetStateMachine: map size, before remove : 0
08-30 17:40:50.064  3189  7848 D HeadsetStateMachine: map size, after remove: 0
,08-30 17:40:50.064  3189  3189 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:40:50.064  3189  3189 D Avrcp   : Initialize Media Controller
08-30 17:40:50.064  3189  3189 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-30 17:40:50.064  3189  3189 E Avrcp   : getActiveSessions
,08-30 17:40:50.064  3189  3189 D Avrcp   : pick active media Controller
08-30 17:40:50.064  3189  3189 D Avrcp   : Get the active Media Controller 
,08-30 17:40:50.074  3189  3189 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 17:40:50.074  3189  7849 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 17:40:50.074  3189  3189 D A2dpStateMachine: make
,08-30 17:40:50.074  3189  3189 I bluedroid: get_profile_interface a2dp
,08-30 17:40:50.074  3189  7851 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 17:40:50.074  3189  3189 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 17:40:50.074  3189  3189 D A2dpService: mStartError = false
08-30 17:40:50.074  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:50.074  3189  3189 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 17:40:50.074  1423  1465 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 17:40:50.074  3189  7850 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:40:50.074  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-30 17:40:50.074  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 17:40:50.074  1423  1465 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 17:40:50.084  3189  3189 D HidService: Received start request. Starting profile...
,08-30 17:40:50.084  3189  3189 D HidService: start()
,08-30 17:40:50.084  3189  3189 I bluedroid: get_profile_interface hidhost
,08-30 17:40:50.084  3189  3189 D HidService: setHidService(): set to: null
08-30 17:40:50.084  3189  3189 D HidService: mStartError = false
08-30 17:40:50.084  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:50.084  3189  3189 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 17:40:50.084  3189  3189 D HeadsetStateMachine: Proxy object connected
08-30 17:40:50.084  3189  7848 D HeadsetStateMachine: Disconnected process message: 11
08-30 17:40:50.084  3189  3189 D HealthService: Received start request. Starting profile...
08-30 17:40:50.084  3189  3189 D HealthService: start()
,08-30 17:40:50.084  3189  7849 D BluetoothMediaBrowser: no now playing list
,08-30 17:40:50.084  3189  7849 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 17:40:50.094  3189  3189 I bluedroid: get_profile_interface health
,08-30 17:40:50.094  3189  3189 D HealthService: mStartError = false
08-30 17:40:50.094  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:50.094  3189  3189 D PanService: Received start request. Starting profile...
08-30 17:40:50.094  3189  3189 D PanService: start()
08-30 17:40:50.094  3189  3189 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:40:50.094  3189  3189 I bluedroid: get_profile_interface pan
08-30 17:40:50.094  3189  3189 D PanService: mStartError = false
08-30 17:40:50.094  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:50.094  3189  3189 D BluetoothMapService: Received start request. Starting profile...
08-30 17:40:50.094  3189  3189 D BluetoothMapService: start()
,08-30 17:40:50.094  3189  3189 D BluetoothMapService: mStartError = false
,08-30 17:40:50.094  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:50.094  3189  3189 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 17:40:50.094  3189  3189 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-30 17:40:50.094  3189  3189 D SapService: Received start request. Starting profile...,
08-30 17:40:50.094  3189  3189 D SapService: start()
08-30 17:40:50.094  3189  3189 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 17:40:50.094  3189  3189 I bluedroid: get_profile_interface sap
08-30 17:40:50.094  3189  3189 D SapService: mStartError = false
,08-30 17:40:50.094  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
08-30 17:40:50.094  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true,
08-30 17:40:50.094  3189  3189 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:40:50.094  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 17:40:50.094  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true,
08-30 17:40:50.094  3189  7848 D HeadsetStateMachine: Disconnected process message: 18
08-30 17:40:50.094  3189  7848 D HeadsetStateMachine: Disconnected process message: 10
08-30 17:40:50.094  3189  7848 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:40:50.094  3189  7848 D HeadsetStateMachine: Disconnected process message: 11
08-30 17:40:50.104  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 17:40:50.104  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 17:40:50.114  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 17:40:50.114  3189  3189 E BluetoothAdapterService(529947200): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 17:40:50.114  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 17:40:50.114  3189  3259 I bluedroid: enable,
,08-30 17:40:50.124  3189  3262 E bt-btif : Calling BTA_HhEnable
,08-30 17:40:50.124  3189  3262 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-30 17:40:50.124  3189  3262 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-30 17:40:50.124  3189  3262 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 17:40:50.124  3189  3262 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-30 17:40:50.124  3189  3262 E BluetoothServiceJni: populateRssiValuesNative
08-30 17:40:50.124  3189  3262 I bluedroid: getModelRssiValues
,08-30 17:40:50.124  3189  3262 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 17:40:50.124  3189  3262 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:40:50.124  1017  1017 D SettingsProvider: name = bluetooth_name
,08-30 17:40:50.124  3189  3262 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-30 17:40:50.134  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:50.134  3189  3262 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 17:40:50.134  3189  3262 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:40:50.134  3189  3262 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:40:50.134  3189  3262 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-30 17:40:50.134  3189  3262 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-30 17:40:50.134  3189  3262 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-30 17:40:50.134  3189  3262 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 17:40:50.134  3189  3262 E bt-btif : JVenable fails
,08-30 17:40:50.134  3189  3262 D bte_conf: Device ID record 1 : primary
,08-30 17:40:50.134  3189  3262 D bte_conf:   vendorId            = 0075
08-30 17:40:50.134  3189  3262 D bte_conf:   vendorIdSource      = 0001
08-30 17:40:50.134  3189  3262 D bte_conf:   product             = 0100
,08-30 17:40:50.144  3189  3262 D bte_conf:   version             = 0200
,08-30 17:40:50.144  3189  3262 D bte_conf:   clientExecutableURL = 
08-30 17:40:50.144  3189  3262 D bte_conf:   serviceDescription  = 
08-30 17:40:50.144  3189  3262 D bte_conf:   documentationURL    = 
,08-30 17:40:50.144  3189  3262 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 17:40:50.144  3189  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 17:40:50.144  3189  3259 D BluetoothAdapterProperties: ScanMode =  20
,08-30 17:40:50.144  3189  3259 D BluetoothAdapterProperties: State =  11
08-30 17:40:50.144  3189  3262 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 17:40:50.144  3189  3262 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:40:50.144  1017  1496 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:40:50.144  3189  3259 D BluetoothAdapterProperties: Setting state to 12
08-30 17:40:50.144  3189  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 17:40:50.144  3189  3262 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:40:50.144  3189  3262 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:40:50.144  3189  3262 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:40:50.154  1017  1135 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 17:40:50.154  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:40:50.154  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:40:50.154  1017  1135 D SettingsProvider: selectionArgs: false
08-30 17:40:50.154  1017  1135 D SettingsProvider: selectionArgs: 1002
08-30 17:40:50.154  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:40:50.154  1017  1135 D SettingsProvider: ret = -1
08-30 17:40:50.154  3189  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 17:40:50.154  3189  3259 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 17:40:50.154  1017  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:50.154  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:50.154  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.154  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:50.154  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:50.154  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:50.164  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.164  4765  4774 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.164  3189  3259 D BluetoothAdapterService: Autoconnection is available 
08-30 17:40:50.164  3189  3259 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 17:40:50.164  3189  3259 D BluetoothAdapterService: starting service from this receiver
,08-30 17:40:50.164  1017  4290 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:40:50.164  1017  4290 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.164  4765  4774 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:50.164  1017  4290 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.164  1017  4290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.164  1017  4290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:40:50.164  3189  3306 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:50.164  3189  3259 I BluetoothAdapterState: Entering On State from state = 11
,08-30 17:40:50.164  3189  3306 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.164  3189  3189 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 17:40:50.164  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 17:40:50.164  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.164  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 17:40:50.164  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.164  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.174  1423  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.174  1423  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:50.174  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:50.174  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 17:40:50.174  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 17:40:50.174  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.174  7803  7819 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.174  7803  7819 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:50.174  3189  3189 I BluetoothPbapService: Handler(): got msg=1
,08-30 17:40:50.174  1017  1480 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:40:50.184  1423  3324 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.184  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:50.184  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 17:40:50.184  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:50.184  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.184  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.184  1017  1017 D BluetoothA2dp: Proxy object connected
,08-30 17:40:50.184  1423  3324 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 17:40:50.184  3189  7856 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 17:40:50.184  3189  3189 D BluetoothA2dp: Proxy object connected
,08-30 17:40:50.184  3189  3189 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-30 17:40:50.184  1443  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.184  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:40:50.184  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:50.184  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.184  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.184  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-30 17:40:50.184  1443  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:50.184  4765  4773 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:40:50.194  3189  7856 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:40:50.194  3189  7856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:50.194  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 17:40:50.194  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.194  3189  7856 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-30 17:40:50.194  3189  7856 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:40:50.194  3189  7856 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:40:50.194  3189  7856 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34f18350
08-30 17:40:50.194  3189  7856 D BluetoothSocket: channel: 19
08-30 17:40:50.194  3189  7856 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 17:40:50.194  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.194  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.194  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.194  1017  1046 D BluetoothPan: Binding service...
,08-30 17:40:50.194  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:40:50.194  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.194  1443  1875 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.194  1443  1875 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:50.194  4765  4765 D BluetoothPbap: Proxy object connected
08-30 17:40:50.194  4765  4773 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.194  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:40:50.194  4765  4765 D PbapServerProfile: Bluetooth service connected
,08-30 17:40:50.194  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:50.194  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 17:40:50.194  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.194  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.194  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.194  4765  4773 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:50.194  1178  1193 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.194  1178  1193 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:50.194  4765  4765 D HeadsetProfile: Bluetooth service connected
,08-30 17:40:50.194  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.194  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:50.204  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 17:40:50.204  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:50.204  1630  1640 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.204  1630  1640 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:50.204  4765  4774 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:40:50.204  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 17:40:50.204  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.204  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.204  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.204  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.204  1423  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.204  4765  4765 D BluetoothMap: Proxy object connected
08-30 17:40:50.204  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:40:50.204  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:50.204  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.204  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.204  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.204  1423  1451 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 17:40:50.204  4765  4765 D MapProfile: Bluetooth service connected
08-30 17:40:50.204  4765  4765 D BluetoothMap: getConnectedDevices()
08-30 17:40:50.204  3189  3306 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:40:50.204  3189  3306 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:50.204  4765  4773 D BluetoothPan: Binding service...
,08-30 17:40:50.214  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:40:50.214  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.214  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.214  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.214  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.214  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.214  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:50.214  1430  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.214  1430  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:50.214  4765  4765 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:40:50.214  4765  4765 D PanProfile: Bluetooth service connected
08-30 17:40:50.214  4765  4773 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:40:50.214  4765  4773 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.214  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
08-30 17:40:50.214  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.214  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.214  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.214  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.214  4765  4773 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:40:50.214  4765  4765 D BluetoothA2dp: Proxy object connected
08-30 17:40:50.214  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 17:40:50.214  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.214  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.214  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.214  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 17:40:50.214  4765  4765 D A2dpProfile: Bluetooth service connected
,08-30 17:40:50.224  1423  3324 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:40:50.224  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:40:50.224  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:40:50.224  4765  4765 D BluetoothInputDevice: Proxy object connected
,08-30 17:40:50.224  4765  4765 D HidProfile: Bluetooth service connected
08-30 17:40:50.224  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:50.224  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.224  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.224  1423  3324 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:40:50.224  1655  4323 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:40:50.224  1655  4323 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:40:50.224  4765  4774 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 17:40:50.224  4765  4774 D Bluetoothsap: Binding service...
,08-30 17:40:50.224  4765  4774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 17:40:50.224  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 17:40:50.224  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 17:40:50.224  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:50.224  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.224  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 17:40:50.224  4765  4774 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 17:40:50.234  6828  6836 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:40:50.234  6828  6836 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:40:50.234  4765  4765 D Bluetoothsap: BluetoothSAP Proxy object connected,
08-30 17:40:50.234  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 17:40:50.234  4765  4765 D SapProfile: Bluetooth service connected
08-30 17:40:50.234  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:40:50.234  4765  4765 D Bluetoothsap: getConnectedDevices()
,08-30 17:40:50.234  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:50.234  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-30 17:40:50.234  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:40:50.234  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3ce55b64, true
,08-30 17:40:50.234  1423  1423 D BluetoothHeadset: registerMessageListener
,08-30 17:40:50.234  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:40:50.244  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:40:50.244  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:50.244  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-30 17:40:50.244  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null,
08-30 17:40:50.244  1854  1854 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:40:50.244  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:50.244  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:50.244  1017  1339 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 17:40:50.254  4765  4765 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:40:50.254  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:40:50.254  1178  1705 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:40:50.254  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:50.254  3189  3306 D HeadsetService: registerMessageListener
,08-30 17:40:50.254  3189  3306 D HeadsetService: registerMessageListener
,08-30 17:40:50.254  3189  7848 D HeadsetStateMachine: Disconnected process message: 70
08-30 17:40:50.254  3189  7848 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@b77949
,08-30 17:40:50.254  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-30 17:40:50.254  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 17:40:50.264  3189  7857 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 17:40:50.264  4765  4765 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 17:40:50.264  4765  4765 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 17:40:50.264  4765  4765 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 17:40:50.264  4765  4765 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 17:40:50.264  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-30 17:40:50.264  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 17:40:50.264  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 17:40:50.264  3189  7848 D HeadsetStateMachine: Disconnected process message: 9
08-30 17:40:50.264  3189  7848 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 17:40:50.264  3189  7857 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:40:50.264  3189  7857 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:50.264  3189  7857 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-30 17:40:50.264  3189  7857 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:40:50.264  3189  7857 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:40:50.264  3189  7857 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c89124e
,08-30 17:40:50.264   285   285 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 17:40:50.264  3189  7857 D BluetoothSocket: channel: 5
08-30 17:40:50.264   285   285 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 17:40:50.264   285   285 V voice   : voice_set_parameters: exit with code(-2)
08-30 17:40:50.264   285   285 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 17:40:50.264   285   285 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 17:40:50.264   285   285 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 17:40:50.264   285   285 V audio_hw_primary: adev_set_parameters: exit
,08-30 17:40:50.274  3189  7848 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 17:40:50.274  4765  4765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:40:50.274  1017  1859 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:40:50.274  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.274  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:50.274  1017  1859 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.274  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:40:50.284  1655  1655 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:40:50.284  4765  4765 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:40:50.284  4765  4765 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:40:50.294  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:40:50.294  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 17:40:50.294  3189  3189 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f965a40
,08-30 17:40:50.294  3189  3189 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 17:40:50.294  1017  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:40:50.294  1017  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 17:40:50.294  1017  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:50.304  1017  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:50.304  1017  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:40:50.314  1017  1859 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:40:50.314  3189  7862 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 17:40:50.314  3189  7862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:40:50.324  3189  7862 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
,08-30 17:40:50.324  3189  7862 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:40:50.324  3189  7862 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-30 17:40:50.324  3189  7862 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d68055a
08-30 17:40:50.324  3189  7862 D BluetoothSocket: channel: 12
08-30 17:40:50.324  3189  7862 I BtOppRfcommListener: Accept thread started.
,08-30 17:40:50.694  1017  1095 V AlarmManager: waitForAlarm result :4
,08-30 17:40:50.694   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:40:50.694   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 17:40:50.704  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:50.714  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:40:50.714  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:50.974  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:50.974  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-30 17:40:50.984  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:40:50.984  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f08a80b added. We now have 8 listener(s)
08-30 17:40:50.984  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-30 17:40:50.984  1017  1339 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:40:50.984  1017  1339 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 17:40:50.984  1017  1339 D SecContentProvider2: mCursor = null
,08-30 17:40:50.984  1017  1339 D SettingsProvider: name = wifi_on
08-30 17:40:50.984  1017  1339 D WifiService: setWifiEnabled: false pid=6828, uid=10170
,08-30 17:40:50.994  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:50.994  1017  4290 D WifiService: setWifiEnabled: true pid=6828, uid=10170
08-30 17:40:50.994  1017  4290 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 17:40:50.994  1017  4290 W ActivityManager: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:40:50.994  1017  4290 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:40:50.994  1017  4290 D SecContentProvider2: mCursor = null
08-30 17:40:50.994  1017  4290 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:40:50.994  1017  4290 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6828, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:40:50.994  1017  4290 W WifiService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 17:40:50.994  1017  4290 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:40:50.994  1017  4290 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:40:50.994  1017  4290 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:40:50.994  1017  4290 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:40:50.994  1017  4290 D SettingsProvider: name = wifi_on
,08-30 17:40:51.004  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 17:40:51.134  1017  3333 D SSRM:n  : SIOP:: AP = 340
,08-30 17:40:51.324  1017  1044 D Tethering: interfaceAdded wlan0
,08-30 17:40:51.334  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:40:51.334  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:51.334  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:51.344  1017  1130 E Tethering: No numeric data
,08-30 17:40:51.344  1017  1044 D Tethering: interfaceAdded p2p0
,08-30 17:40:51.344  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 17:40:51.354  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:40:51.354  1017  1130 D Tethering: clearTetheredNotification()
08-30 17:40:51.354  1017  1130 D Tethering: InitialState.processMessage what=4
08-30 17:40:51.354   277  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-30 17:40:51.354  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:51.354  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:51.354  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-30 17:40:51.354   277  1016 D SoftapController: Softap fwReload - Ok
08-30 17:40:51.354  1017  1130 E Tethering: No numeric data
,08-30 17:40:51.354  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:51.354  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:51.364   277  1016 D CommandListener: Setting iface cfg
08-30 17:40:51.364   277  1016 D CommandListener: Trying to bring down wlan0
,08-30 17:40:51.364   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:40:51.364  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:51.364  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:51.364  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:40:51.364  1178  1178 D HotspotTile: updateTetherState():false, false
,08-30 17:40:51.364  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-30 17:40:51.374  1017  1123 V NetworkStats: performPollLocked() took 11ms
,08-30 17:40:51.374  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:51.374  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 17:40:51.374  1017  1130 D Tethering: clearTetheredNotification()
,08-30 17:40:51.384  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:40:51.384  1178  1178 D HotspotTile: updateTetherState():false, false
,08-30 17:40:51.384  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:51.384  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:51.384  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:51.384  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:40:51.384  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:40:51.384  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:51.384  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 17:40:51.384  1017  1123 V NetworkStats: performPollLocked() took 6ms
08-30 17:40:51.384  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:51.404  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:51.404  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:51.404  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:51.404  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:40:51.404  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:40:51.404  1178  1178 D HotspotTile: onReceive : 2, 0
08-30 17:40:51.404  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:51.404  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:51.404  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:51.404  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:51.404  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:51.404  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 17:40:51.404  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:40:51.414  1017  1135 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:51.414  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:51.414  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:51.414  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:51.414  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:51.414  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:51.414  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:51.414  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:51.414  2183  2183 I Hs20UtilService: Starting #19
,08-30 17:40:51.414  2183  2198 I Hs20UtilService: Message received 5011
,08-30 17:40:51.414  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:40:51.414  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:40:51.414  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:40:51.414  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:40:51.434  7877  7877 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 17:40:51.434  7877  7877 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 17:40:51.434  7877  7877 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 17:40:51.444  7877  7877 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-30 17:40:51.444   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7877,
08-30 17:40:51.444   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-30 17:40:51.444  7877  7877 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 17:40:51.444  7877  7877 I wpa_supplicant: ssSupport state is = 1
,08-30 17:40:51.444  7877  7877 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 17:40:51.444  7877  7877 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 17:40:51.444   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7877
08-30 17:40:51.444   384   384 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106,
,08-30 17:40:51.614   384   384 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-30 17:40:51.624  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-30 17:40:51.664  7877  7877 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 17:40:51.664  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:40:51.674  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-30 17:40:51.674   384   384 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7877
08-30 17:40:51.674   384   384 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:40:51.674  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-30 17:40:51.674  7877  7877 I wpa_supplicant: ssSupport state is = 1
08-30 17:40:51.674  7877  7877 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:51.674  7877  7877 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:51.674  7877  7877 E wpa_supplicant: SIM READ ERROR
08-30 17:40:51.674  7877  7877 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:51.674  7877  7877 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 17:40:51.674  7877  7877 E wpa_supplicant: SIM READ ERROR
08-30 17:40:51.674  7877  7877 I wpa_supplicant: Blacklist: Clear (all) 
08-30 17:40:51.674  7877  7877 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:40:51.674  7877  7877 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:40:51.674  7877  7877 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:51.674  7877  7877 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-30 17:40:51.674  7877  7877 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:51.674  7877  7877 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 17:40:51.684  7877  7877 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-30 17:40:51.684  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 17:40:51.684  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:51.684  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:51.734  7877  7877 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-30 17:40:51.884  7877  7877 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 17:40:51.884  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:40:51.894  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 17:40:51.894   384   384 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7877
08-30 17:40:51.894   384   384 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-30 17:40:51.894  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 17:40:51.894  7877  7877 I wpa_supplicant: ssSupport state is = 1
08-30 17:40:51.904  7877  7877 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 17:40:51.904  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:40:51.914  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 17:40:51.914   384   384 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7877
08-30 17:40:51.914   384   384 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:40:51.914  7877  7877 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 17:40:51.914  7877  7877 I wpa_supplicant: ssSupport state is = 1
08-30 17:40:51.914  7877  7877 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:40:51.914  7877  7877 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:51.914  7877  7877 E wpa_supplicant: SIM READ ERROR
08-30 17:40:51.914  7877  7877 I wpa_supplicant: wpa_default_ap_write_once
,08-30 17:40:51.914  7877  7877 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:40:51.914  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:51.914  7877  7877 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 17:40:51.914  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:51.914  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:40:51.924  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:51.924  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:40:51.924  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:40:51.964  7877  7877 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 17:40:51.964  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 17:40:52.054  7877  7877 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 17:40:52.054  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-30 17:40:52.054  7877  7877 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:40:52.064  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-30 17:40:52.064  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:40:52.064  7877  7877 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-30 17:40:52.064  7877  7877 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 17:40:52.064  7877  7877 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:40:52.074  7877  7877 E wpa_supplicant: SIM READ ERROR,
08-30 17:40:52.074  7877  7877 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:40:52.084  7877  7877 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 17:40:52.094  7877  7877 I wpa_supplicant: Skip scan - bUseNetwork false,
08-30 17:40:52.094  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:40:52.104  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:52.104  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:52.104  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:52.104  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:52.104  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:52.104  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:52.104  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:52.104  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:52.104  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:40:52.104  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-30 17:40:52.104  1178  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:40:52.104  1178  1178 D HotspotTile: onReceive : 3, 0
,08-30 17:40:52.104  4765  4765 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:40:52.104  1017  1126 E WifiConfigStore: Not a HS20
,08-30 17:40:52.114  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:52.114  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:52.114  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 17:40:52.114  7877  7877 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 17:40:52.114  7877  7877 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 17:40:52.114  7877  7877 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:40:52.114  7877  7877 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:40:52.114  7877  7877 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 17:40:52.114  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 17:40:52.114  7877  7877 I wpa_supplicant: First Scan Start
,08-30 17:40:52.114  7877  7877 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 17:40:52.114  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:52.114  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-30 17:40:52.114  1017  1458 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:52.114  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:52.124  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:52.124  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:40:52.124  1017  1126 I WifiNative-HAL: startHal
08-30 17:40:52.124  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f50888c
08-30 17:40:52.124  1017  1126 I WifiNative-HAL: Could not start hal
,08-30 17:40:52.124  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:40:52.124  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:52.124  7370  7370 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:40:52.124  1017  1126 E WifiNative-wlan0: do suspend true
,08-30 17:40:52.124  2183  2183 I Hs20UtilService: Starting #20
,08-30 17:40:52.124  2183  2198 I Hs20UtilService: Message received 5011
08-30 17:40:52.124  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 17:40:52.124   277  1016 D CommandListener: Setting iface cfg
08-30 17:40:52.124   277  1016 D CommandListener: Trying to bring up p2p0
,08-30 17:40:52.124  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:40:52.134  1017  1125 D WifiP2pService: P2pEnablingState
,08-30 17:40:52.134  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:40:52.134  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 17:40:52.134  7393  7393 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:40:52.134  7393  7393 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:40:52.134  7393  7393 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-30 17:40:52.134  1017  1125 D WifiP2pService: P2p socket connection successful
08-30 17:40:52.134  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 17:40:52.134  1017  1125 D WifiP2pService: P2pEnabledState
,08-30 17:40:52.134  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:40:52.134  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:40:52.134  1017  1150 I WifiNative-HAL: startHal
08-30 17:40:52.134  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e3ca9bc
08-30 17:40:52.134  1017  1150 I WifiNative-HAL: Could not start hal
08-30 17:40:52.134  1017  1150 E WifiScanningService: could not start HAL
08-30 17:40:52.134  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:40:52.134  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:40:52.134  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-30 17:40:52.134  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-30 17:40:52.134  1017  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:40:52.134  7877  7877 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:40:52.134  7877  7877 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:40:52.144  7877  7877 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
08-30 17:40:52.144  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,08-30 17:40:52.144  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:40:52.144  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:40:52.144  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-30 17:40:52.144  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:52.144  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 17:40:52.144  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:52.144  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:52.144  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:40:52.144  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
08-30 17:40:52.144  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:52.144  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:52.144  1017  1126 D SecContentProvider2: mCursor = null
08-30 17:40:52.144  1017  1047 D WifiDisplayController: disconnect
08-30 17:40:52.144  1017  1047 D WifiDisplayController: updateConnection
08-30 17:40:52.144  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:40:52.144  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:40:52.144  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:40:52.144  1017  4291 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:40:52.154  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:40:52.154  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-30 17:40:52.154  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-30 17:40:52.154  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 17:40:52.154  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:40:52.154  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:40:52.154  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:40:52.154  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 17:40:52.154  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:40:52.154  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
,08-30 17:40:52.164  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:52.164  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  secondary type: null
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  wps: 0
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  grpcapab: 0
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  devcapab: 0
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  status: 3
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  wfdInfo: null
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-30 17:40:52.164  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-30 17:40:52.164  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:40:52.164  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:52.164  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:40:52.164  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:52.164  7719  7719 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:52.164  7719  7719 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:40:52.164  7719  7719 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:40:52.174  7355  7355 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:40:52.184  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 17:40:52.184  1017  1125 D WifiP2pService: InactiveState
,08-30 17:40:52.184  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-30 17:40:52.184  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:40:52.184  7877  7877 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:40:52.184  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-30 17:40:52.184  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:40:52.224   290   290 E SMD     : DCD OFF
,08-30 17:40:52.334  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:40:52.334  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:40:52.334  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:53.014  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:53.014  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:40:53.024  6828  7213 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 17:40:53.024  6828  7213 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 17:40:53.024  6828  7213 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21782f6e Bundle[{}]
,08-30 17:40:53.024  6828  7213 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:40:53.024  6828  7213 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 17:40:53.024  6828  7213 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:40:53.024  6828  7213 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 17:40:53.034  6828  7213 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 17:40:53.034  6828  7213 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 17:40:53.034  6828  7213 I System.out: Running OutgoingSocketThread
08-30 17:40:53.034  6828  7885 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1374)
08-30 17:40:53.034  6828  7885 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 34519
08-30 17:40:53.034  6828  7885 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 17:40:53.324  7877  7877 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
08-30 17:40:53.324  7877  7877 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 17:40:53.324  7877  7877 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 17:40:53.324  7877  7877 I wpa_supplicant: Trying to associate with  'G700'
,08-30 17:40:53.324  7877  7877 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-30 17:40:53.324  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-30 17:40:53.324  1017  7882 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 17:40:53.344  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-30 17:40:53.344  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:53.444  7877  7877 E wpa_supplicant: Cmd 35605 not handled
08-30 17:40:53.444  7877  7877 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:40:53.444  7877  7877 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-30 17:40:53.444  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:53.444  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:53.444  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:53.444  7877  7877 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 17:40:53.444  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 17:40:53.444  7877  7877 I wpa_supplicant: Associated with F4.99.3E
08-30 17:40:53.444  7877  7877 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:40:53.444  7877  7877 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 17:40:53.444  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:40:53.444  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:53.444  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:53.444  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:40:53.444  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:40:53.444  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:40:53.444  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:40:53.444  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-30 17:40:53.444  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 17:40:53.444  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-30 17:40:53.444  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:40:53.444  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:53.454  7877  7877 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 17:40:53.454  7877  7877 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 17:40:53.454  1017  1130 E Tethering: No numeric data
,08-30 17:40:53.454  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:40:53.454  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:53.454  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:40:53.454  1017  1130 D Tethering: clearTetheredNotification()
08-30 17:40:53.454  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:40:53.454  7877  7877 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 17:40:53.454  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:53.454  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:53.454  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 17:40:53.454  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:40:53.454  1178  1178 D HotspotTile: updateTetherState():false, false,
08-30 17:40:53.454  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:40:53.454  1017  1123 V NetworkStats: performPollLocked() took 3ms
08-30 17:40:53.454  7877  7877 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:40:53.454  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:40:53.454  7877  7877 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 17:40:53.454  7877  7877 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 17:40:53.454  7877  7877 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 17:40:53.454  7877  7877 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:40:53.454  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 17:40:53.454  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-30 17:40:53.454  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:53.464  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:53.464  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:53.464  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-30 17:40:53.464  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 17:40:53.474  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 17:40:53.474  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 17:40:53.474  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:53.474  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:40:53.474  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:53.474  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-30 17:40:53.474  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:53.474  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:53.474  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:53.474  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:53.474  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:53.474  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:53.474  1017  1339 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:53.474  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:53.474  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:53.474  1017  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:53.484  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:53.484  2183  2183 I Hs20UtilService: Starting #21
,08-30 17:40:53.484  2183  2198 I Hs20UtilService: Message received 5007
,08-30 17:40:53.484  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:40:53.484  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:40:53.484  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:40:53.484  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:40:53.484  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:40:53.484  4765  4765 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:40:53.494  4765  4824 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:40:53.494  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:40:53.504   277  1016 D CommandListener: Setting iface cfg
,08-30 17:40:53.504  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-30 17:40:53.504  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:40:53.504  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:53.514  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:53.514  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:40:53.514  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:40:53.514  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:53.524  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:53.524  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:53.524  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:53.524  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:40:53.524  1017  1126 D SecContentProvider2: mCursor = null
,08-30 17:40:53.534  1017  1126 E WifiNative-wlan0: do suspend false
,08-30 17:40:53.534  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:40:53.534  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:40:53.744  7888  7888 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 17:40:53.754  7888  7888 I dhcpcd  : version 5.5.6 starting
,08-30 17:40:53.754  7888  7888 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 17:40:53.804  7888  7888 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-30 17:40:53.804  7888  7888 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 17:40:53.804  7888  7888 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-30 17:40:53.804  7888  7888 I dhcpcd  : bssid match
08-30 17:40:53.804  7888  7888 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-30 17:40:53.884  7888  7888 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-30 17:40:53.934  7888  7888 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-30 17:40:54.034  6828  7213 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1375)
08-30 17:40:54.034  6828  7213 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1375)
08-30 17:40:54.034  6828  7213 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1380)
08-30 17:40:54.034  6828  7213 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 17:40:54.034  6828  7213 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1381)
,08-30 17:40:54.044  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.044  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6516e8 added. We now have 2 listener(s)
,08-30 17:40:54.044  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-30 17:40:54.044  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.044  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.044  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.044  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2075a101 added. We now have 9 listener(s)
08-30 17:40:54.044  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-30 17:40:54.044  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:40:54.054  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:54.054  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:54.054  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:54.064  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b97b9e7 added. We now have 3 listener(s)
,08-30 17:40:54.064  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.064  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e8b994 added. We now have 10 listener(s)
08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-30 17:40:54.064  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:54.064  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:54.064  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:54.064  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6516e8 removed from the list
08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2075a101 removed from the list
08-30 17:40:54.064  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:54.064  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.064  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2075a101 not in the list
,08-30 17:40:54.064  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e8b994 removed from the list
08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:54.064  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:54.064  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:54.064  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b97b9e7 removed from the list
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.064  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a4c3d added. We now have 2 listener(s)
,08-30 17:40:54.074  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 17:40:54.074  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.074  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.074  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.074  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9b3c32 added. We now have 9 listener(s)
08-30 17:40:54.074  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:54.074  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-30 17:40:54.074  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:54.084  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:40:54.084  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:54.084  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-30 17:40:54.084  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.084  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3461db00 added. We now have 3 listener(s),
08-30 17:40:54.084  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:54.084  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:40:54.084  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:54.084  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.084  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.084  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.084  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646f39 added. We now have 10 listener(s)
,08-30 17:40:54.084  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:54.084  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:54.084  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:40:54.084  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:54.084  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:54.084  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:40:54.094  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:40:54.094  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:40:54.094  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 17:40:54.104  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:40:54.104  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:40:54.104  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:40:54.114  3189  3306 D BtGatt.GattService: registerClient() - UUID=c5b86bd4-de5c-41c5-b4ac-dff1d6c15148,
,08-30 17:40:54.144  1017  1126 E WifiNative-wlan0: do suspend true,
,08-30 17:40:54.154  3189  3262 D BtGatt.GattService: onClientRegistered() - UUID=c5b86bd4-de5c-41c5-b4ac-dff1d6c15148, clientIf=6,
,08-30 17:40:54.154  6828  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 17:40:54.154  3189  7770 D BtGatt.GattService: start scan with filters
08-30 17:40:54.154  3189  3320 D BtGatt.ScanManager: handling starting scan
08-30 17:40:54.154  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-30 17:40:54.154  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:40:54.154  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:40:54.154  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:54.164  3189  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 17:40:54.164  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.164  3189  3320 D BtGatt.ScanManager: allow scan with filters
08-30 17:40:54.164  3189  3320 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:40:54.164  3189  3320 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-30 17:40:54.164  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:54.164  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:40:54.164  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:54.164  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:40:54.164  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.164  3189  3320 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:40:54.164  3189  3320 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-30 17:40:54.164  3189  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 17:40:54.164  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.164  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:54.164  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:40:54.164  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.174  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:40:54.174  6828  7213 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:40:54.174  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:54.174  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:40:54.174  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.174  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:40:54.174  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:40:54.174  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:54.174  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:40:54.174  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:54.174  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:40:54.174  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:40:54.174  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:40:54.174  3189  3197 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:40:54.174  3189  3202 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:40:54.174  1017  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 17:40:54.174  1017  1126 E WifiStateMachine: VerifyingLinkState enter
,08-30 17:40:54.174  3189  3320 D BtGatt.ScanManager: filter size is 1
08-30 17:40:54.174  3189  3320 D BtGatt.ScanManager: delete FilterIndex - 6
,08-30 17:40:54.174  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:40:54.174  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.184  3189  3320 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:40:54.184  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:40:54.184  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:40:54.184  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:40:54.184  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:40:54.184  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:54.184  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:54.184  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 17:40:54.184  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.184  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:54.184  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:40:54.184  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:54.184  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.184  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.184  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.184  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.184  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:40:54.184  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:40:54.184  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:40:54.184  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:40:54.184  3189  3320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:40:54.184  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-30 17:40:54.184  1017  1128 D ConnectivityService: Adding iface wlan0 to network 504
,08-30 17:40:54.184  3189  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:40:54.184  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.194  1017  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-30 17:40:54.194  1017  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 17:40:54.194  1017  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 17:40:54.194  1017  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 17:40:54.194  1017  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 17:40:54.204  1017  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-30 17:40:54.204  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:54.204  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:54.204  1017  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-30 17:40:54.204  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:54.204  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:54.204  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:54.204  1017  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-30 17:40:54.204  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:54.214  1017  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:40:54.214  1017  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-30 17:40:54.214  1017  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-30 17:40:54.214  2183  2183 I Hs20UtilService: Starting #22
,08-30 17:40:54.214  1017  1128 D ConnectivityService: LTETest block dns file not exists
,08-30 17:40:54.214  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:54.214  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:54.214  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:54.214  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.214  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.214  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.214  1017  1128 V NetworkStats: updateIfacesLocked()
08-30 17:40:54.214  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.214  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:40:54.214  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:54.214  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:54.214  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:54.214  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:54.214  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:54.214  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:54.214  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:40:54.214  1017  1128 V NetworkStats: performPollLocked() took 4ms
08-30 17:40:54.214  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:54.224  2183  2198 I Hs20UtilService: Message received 5007
,08-30 17:40:54.224  4765  4765 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 17:40:54.234  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-30 17:40:54.234  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-30 17:40:54.234  1017  1128 E ConnectivityService: updateNetworkInfo()
08-30 17:40:54.234  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:40:54.234  1017  1128 V NetworkStats: updateIfacesLocked()
,08-30 17:40:54.234  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.234  1017  1128 V NetworkStats: performPollLocked(flags=0x1),
08-30 17:40:54.234  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:54.234  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-30 17:40:54.234  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:54.234  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:54.234  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.234  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-30 17:40:54.234  1017  1128 V NetworkStats: performPollLocked() took 3ms
08-30 17:40:54.234  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:54.234  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.234  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1a4c3d removed from the list
,08-30 17:40:54.234  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.234  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:40:54.234  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9b3c32 removed from the list
08-30 17:40:54.234  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 17:40:54.234  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:54.234  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.234  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:54.234  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 17:40:54.234  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 17:40:54.234  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:40:54.234  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:54.244  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 17:40:54.244  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:40:54.244  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:40:54.244  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:54.244  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:54.244  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.244  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:54.244  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:40:54.244  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-30 17:40:54.244  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-30 17:40:54.254  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:54.254  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-30 17:40:54.254  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.254  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.254  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.254  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:54.254  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:54.254  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.254  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:54.254  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.264  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9b3c32 not in the list
08-30 17:40:54.264  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.264  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.264  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646f39 removed from the list
08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:54.264  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.264  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.264  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3461db00 removed from the list
,08-30 17:40:54.264  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.264  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@993c5f5 added. We now have 2 listener(s)
08-30 17:40:54.264  1017  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,08-30 17:40:54.264  1017  7886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:54.264  1017  7886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-30 17:40:54.264  1017  7886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:40:54.264  1017  7886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-30 17:40:54.264  1017  7886 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:40:54.264  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:54.264  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.264  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.264  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.264  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aba1f8a added. We now have 9 listener(s)
08-30 17:40:54.264  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 17:40:54.264  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:54.264   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:40:54.264   277  1012 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:40:54.264  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:54.274  1017  1128 D ConnectivityService:    accepting network in place of null
,08-30 17:40:54.274  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 17:40:54.274  1443  1443 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 17:40:54.274  1443  1443 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:40:54.274  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-30 17:40:54.274  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 17:40:54.274  1017  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-30 17:40:54.274  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 17:40:54.284  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-30 17:40:54.284  1017  1130 D Tethering: MasterInitialState.processMessage what=3
08-30 17:40:54.284  1017  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-30 17:40:54.284  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.284  1017  1123 V NetworkStats: updateIfacesLocked()
08-30 17:40:54.284  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:40:54.284  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:40:54.284  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:54.284  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:40:54.284  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:40:54.284  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-30 17:40:54.284  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-30 17:40:54.294  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-30 17:40:54.294  1017  3835 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:54.294  1017  3835 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:54.294  1178  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:40:54.294  1017  1123 V NetworkStats: performPollLocked() took 5ms
08-30 17:40:54.294  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.294  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 17:40:54.294  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:54.294  1017  3835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:54.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.294  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:40:54.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.294  2183  2183 I Hs20UtilService: Starting #23
08-30 17:40:54.294  2183  2198 I Hs20UtilService: Message received 5007
,08-30 17:40:54.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:54.294  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:54.294  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:54.294  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 17:40:54.294  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:40:54.294  4765  4765 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:40:54.294  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-30 17:40:54.294  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:40:54.294  4765  4765 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false,
,08-30 17:40:54.294  4765  4765 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:40:54.304  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:54.304  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:54.304  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:54.304  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:40:54.304  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:54.304  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-30 17:40:54.304  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a800a18 added. We now have 3 listener(s)
,08-30 17:40:54.304  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:54.304  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.304  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:40:54.314  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.314  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3227cc71 added. We now have 10 listener(s)
08-30 17:40:54.314  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:54.314  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:54.314  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:54.314  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:40:54.314  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:40:54.314  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:54.314  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:40:54.314  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:54.314  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:54.314  1017  1458 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:40:54.314  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:40:54.314  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:54.314  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:54.314  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:40:54.314  2183  2183 I Hs20UtilService: Starting #24
,08-30 17:40:54.324  2183  2198 I Hs20UtilService: Message received 5007
,08-30 17:40:54.324  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:40:54.324  4765  4765 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:40:54.324  4765  4765 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 17:40:54.324  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-30 17:40:54.324  1017  4291 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-30 17:40:54.324  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:40:54.334  1017  1859 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-30 17:40:54.334  1017  1859 D SecContentProvider2: mCursor = null
08-30 17:40:54.334  1017  1469 D SecContentProvider2: uri = 15 selection = getToastGravity
08-30 17:40:54.334  1017  1469 D SecContentProvider2: mCursor = null,
08-30 17:40:54.334  1017  3835 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-30 17:40:54.334  1017  3835 D SecContentProvider2: mCursor = null
,08-30 17:40:54.334  1017  4291 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-30 17:40:54.334  1017  4291 D SecContentProvider2: mCursor = null
08-30 17:40:54.334  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:40:54.334  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:40:54.334  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:40:54.334  3189  3197 D BtGatt.GattService: registerClient() - UUID=885a5673-0506-48e1-ab00-6e9a3d6f6025
,08-30 17:40:54.344  1017  1859 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
08-30 17:40:54.344  1017  1224 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 17:40:54.344  1017  1859 D SecContentProvider2: mCursor = null
08-30 17:40:54.344  1017  1224 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4226, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 17:40:54.344  1017  1469 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-30 17:40:54.344  1017  1224 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 17:40:54.344  1017  1469 D SecContentProvider2: mCursor = null
08-30 17:40:54.344  1017  1224 D BatteryService: stay LED for charging
,08-30 17:40:54.344  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:40:54.344  1017  1017 I MotionRecognitionService: Plugged,
08-30 17:40:54.344  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:40:54.344  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:40:54.344  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,08-30 17:40:54.354  3189  3189 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:40:54.354  3189  7848 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:40:54.354  1017  7886 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:40:54.364   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-30 17:40:54.374  3189  3262 D BtGatt.GattService: onClientRegistered() - UUID=885a5673-0506-48e1-ab00-6e9a3d6f6025, clientIf=6
,08-30 17:40:54.384  6828  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:40:54.384  3189  3202 D BtGatt.GattService: start scan with filters
,08-30 17:40:54.384  1017  1859 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
08-30 17:40:54.384  3189  3320 D BtGatt.ScanManager: handling starting scan
,08-30 17:40:54.384  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:40:54.384  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:40:54.384  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:40:54.384  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:54.394  3189  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 17:40:54.394  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:54.394  3189  3320 D BtGatt.ScanManager: allow scan with filters
08-30 17:40:54.394  3189  3320 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:40:54.394  3189  3320 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-30 17:40:54.394  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:40:54.394  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.394  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:54.394  3189  3320 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:40:54.394  3189  3320 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-30 17:40:54.394  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:54.394  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:40:54.394  3189  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:40:54.394  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.404  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 17:40:54.404  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.404  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 17:40:54.404  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:54.414  1017  7886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:40:54 GMT], X-Android-Received-Millis=[1472571654420], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472571654389]},
08-30 17:40:54.414  1017  7886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 17:40:54.414  1017  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-30 17:40:54.414  1017  7886 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-30 17:40:54.414  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
,08-30 17:40:54.414  1178  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:40:54.414  1017  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.,
08-30 17:40:54.414  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-30 17:40:54.414  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 17:40:54.414  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:54.414  6828  7213 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 17:40:54.424  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:54.424  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:54.424  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-30 17:40:54.424  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.424  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
,08-30 17:40:54.424  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@993c5f5 removed from the list
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:54.424  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aba1f8a removed from the list
08-30 17:40:54.424  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 17:40:54.424  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:54.424  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.424  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:40:54.424  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.424  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.424  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aba1f8a not in the list
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:54.424  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:40:54.424  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:40:54.424  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:40:54.424  3189  3197 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:40:54.424  3189  3320 D BtGatt.ScanManager: filter size is 1
08-30 17:40:54.424  3189  3320 D BtGatt.ScanManager: delete FilterIndex - 7
,08-30 17:40:54.424  3189  3202 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:40:54.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:40:54.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:40:54.434  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:40:54.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:40:54.434  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:54.434  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:40:54.434  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
08-30 17:40:54.434  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,08-30 17:40:54.434  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
08-30 17:40:54.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:54.434  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-30 17:40:54.434  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:54.434  3189  3320 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:40:54.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:40:54.434  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:40:54.434  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:40:54.434  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-30 17:40:54.434  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:40:54.434  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:40:54.434  1178  1178 D StatusBar.NetworkController: updateDataNetType(),
08-30 17:40:54.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.444  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:40:54.444  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.444  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:54.444  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.444  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.444  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3227cc71 removed from the list
08-30 17:40:54.444  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:54.444  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.444  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:54.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:54.444  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:40:54.444  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a800a18 removed from the list
,08-30 17:40:54.444  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:54.444  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:54.444  3189  3320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-30 17:40:54.444  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.444  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21bbead added. We now have 2 listener(s)
08-30 17:40:54.444  3189  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:40:54.444  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:54.444  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 17:40:54.444  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-30 17:40:54.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:54.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.444  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 17:40:54.444  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b715e2 added. We now have 9 listener(s)
08-30 17:40:54.444  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:54.444  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:40:54.444  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-30 17:40:54.444  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-30 17:40:54.444  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-30 17:40:54.444  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-30 17:40:54.444  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:40:54.454  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:40:54.454  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.454  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.454  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:40:54.454  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:40:54.454  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:54.454  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:54.464  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:40:54.464  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:54.464  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:40:54.464  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:40:54.464  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f220430 added. We now have 3 listener(s)
,08-30 17:40:54.464  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:54.464  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:54.464  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.464  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.464  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.464  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be298a9 added. We now have 10 listener(s)
08-30 17:40:54.464  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:40:54.464  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:40:54.464  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:40:54.464  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:40:54.464  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:40:54.464  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:40:54.474  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:54.474  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:40:54.474  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:40:54.484  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:40:54.484  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:40:54.484  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:40:54.484  6828  7213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:40:54.484  3189  3337 D BtGatt.GattService: registerClient() - UUID=e759c7de-0fed-4a1b-bff0-c0d7f972d3f7
,08-30 17:40:54.524  3189  3262 D BtGatt.GattService: onClientRegistered() - UUID=e759c7de-0fed-4a1b-bff0-c0d7f972d3f7, clientIf=6
,08-30 17:40:54.534  6828  6841 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:40:54.534  3189  7770 D BtGatt.GattService: start scan with filters
,08-30 17:40:54.534  3189  3320 D BtGatt.ScanManager: handling starting scan
,08-30 17:40:54.534  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:40:54.534  3189  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:40:54.534  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.534  3189  3320 D BtGatt.ScanManager: allow scan with filters
,08-30 17:40:54.534  3189  3320 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:40:54.534  3189  3320 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-30 17:40:54.534  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:40:54.544  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:40:54.544  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:40:54.544  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:40:54.544  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:54.544  3189  3320 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:40:54.544  3189  3320 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:40:54.544  3189  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:40:54.544  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.544  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:40:54.544  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.554  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:40:54.554  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:40:54.554  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:40:54.554  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:40:54.564  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:40:54.564  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:54.564  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:54.564  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.564  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21bbead removed from the list
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.564  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b715e2 removed from the list
08-30 17:40:54.564  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:54.564  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:40:54.564  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.564  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b715e2 not in the list
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:40:54.564  3189  3306 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:40:54.564  3189  3320 D BtGatt.ScanManager: filter size is 1
08-30 17:40:54.564  3189  3197 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:40:54.564  3189  3320 D BtGatt.ScanManager: delete FilterIndex - 8,
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:40:54.564  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:40:54.564  3189  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:40:54.564  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:40:54.564  3189  3320 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:40:54.564  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:40:54.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:40:54.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 17:40:54.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:40:54.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:54.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.574  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be298a9 removed from the list
08-30 17:40:54.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:54.574  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.574  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:40:54.574  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.574  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f220430 removed from the list
,08-30 17:40:54.574  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:40:54.574  3189  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:40:54.574  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.574  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:40:54.574  3189  3320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:40:54.574  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.574  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c231665 added. We now have 2 listener(s)
08-30 17:40:54.574  6828  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:40:54.574  3189  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 17:40:54.574  3189  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:40:54.584  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 17:40:54.584  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.584  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.584  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.584  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e17f3a added. We now have 9 listener(s)
08-30 17:40:54.584  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:54.584  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:40:54.584  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:54.594  6828  7213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:54.594  6828  7213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:54.594  6828  7213 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:40:54.594  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:40:54.594  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f962948 added. We now have 3 listener(s)
,08-30 17:40:54.594  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:54.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 17:40:54.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:40:54.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:40:54.594  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:40:54.594  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2933b3e1 added. We now have 10 listener(s)
08-30 17:40:54.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:40:54.594  6828  7213 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:40:54.594  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:40:54.594  6828  7213 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:40:54.594  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:40:54.594  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.594  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:40:54.594  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.594  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c231665 removed from the list
08-30 17:40:54.594  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:40:54.594  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e17f3a removed from the list
,08-30 17:40:54.594  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:40:54.604  6828  7213 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:40:54.604  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.604  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:54.604  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:54.604  6828  7213 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e17f3a not in the list
08-30 17:40:54.604  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:40:54.604  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:40:54.604  6828  7213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2933b3e1 removed from the list
08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:40:54.604  6828  7213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:40:54.604  6828  7213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:40:54.604  6828  7213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:40:54.604  6828  7213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f962948 removed from the list
,08-30 17:40:54.614  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-30 17:40:54.614  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 17:40:54.614  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 17:40:54.614  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 17:40:54.614  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-30 17:40:54.614  6828  7213 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:40:54.624  6828  7926 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1388, name: My test thread name)
,08-30 17:40:54.624  6828  7926 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1388, thread name: My test thread name)
,08-30 17:40:54.624  6828  7926 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1388, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:40:54.624  6828  7927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1390, name: My test thread name)
,08-30 17:40:54.624  6828  7927 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1390, thread name: My test thread name)
,08-30 17:40:54.624  6828  7927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1390, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:40:54.624  6828  7213 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-30 17:40:54.624  6828  7213 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 17:40:54.624  6828  7213 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-30 17:40:54.624  6828  7213 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 17:40:54.624  6828  7213 D com.test.thalitest.ThaliTestRunner: Total duration: 23318 ms
,08-30 17:40:54.634  6828  7213 I jxcore-log: *Native tests were executed*
08-30 17:40:54.634  6828  7213 I jxcore-log: 
,08-30 17:40:54.634  6828  7213 I jxcore-log: Total number of executed tests:  80
08-30 17:40:54.634  6828  7213 I jxcore-log: 
,08-30 17:40:54.634  6828  7213 I jxcore-log: Number of passed tests:  80
08-30 17:40:54.634  6828  7213 I jxcore-log: 
,08-30 17:40:54.634  6828  7213 I jxcore-log: Number of failed tests:  0
08-30 17:40:54.634  6828  7213 I jxcore-log: 
,08-30 17:40:54.634  6828  7213 I jxcore-log: Number of ignored tests:  0
08-30 17:40:54.634  6828  7213 I jxcore-log: 
,08-30 17:40:54.634  6828  7213 I jxcore-log: Total duration:  23318
08-30 17:40:54.634  6828  7213 I jxcore-log: 
,08-30 17:40:54.634  6828  7213 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 17:40:54.634  6828  7213 I jxcore-log: 
,08-30 17:40:54.644  6828  6828 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:40:54.644  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.644  6828  7213 I jxcore-log: 
08-30 17:40:54.654  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.654  6828  7213 I jxcore-log: 
08-30 17:40:54.654  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.654  6828  7213 I jxcore-log: 
08-30 17:40:54.654  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.654  6828  7213 I jxcore-log: 
08-30 17:40:54.654  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.654  6828  7213 I jxcore-log: 
08-30 17:40:54.654  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.654  6828  7213 I jxcore-log: 
08-30 17:40:54.654  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.654  6828  7213 I jxcore-log: 
08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.664  6828  7213 I jxcore-log: 
08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.664  6828  7213 I jxcore-log: 
08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:40:54.664  6828  7213 I jxcore-log: 
,08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:40:54.664  6828  7213 I jxcore-log: 
,08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:40:54.664  6828  7213 I jxcore-log: 
,08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.664  6828  7213 I jxcore-log: 
,08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 17:40:54.664  6828  7213 I jxcore-log: 
08-30 17:40:54.664  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.664  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 17:40:54.674  6828  7213 I jxcore-log: 
08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.674  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.674  6828  7213 I jxcore-log: 
,08-30 17:40:54.684  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.684  6828  7213 I jxcore-log: 
,08-30 17:40:54.714  6828  6828 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-30 17:40:54.714  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:40:54.714  6828  7213 I jxcore-log: 
,08-30 17:40:54.784  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:54.804  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:54.804  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 17:40:54.804  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:54.804  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:54.804  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:40:54.804  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:40:54.824  6828  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:40:54.824  6828  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:40:54.824  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:40:54.824  6828  7213 I jxcore-log: 
,08-30 17:40:54.824  1017  1042 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7930 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 17:40:54.834  7930  7930 E Zygote  : MountEmulatedStorage()
08-30 17:40:54.834  7930  7930 E Zygote  : v2
,08-30 17:40:54.834  7930  7930 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:40:54.834  7930  7930 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:54.834  7930  7930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:54.834  7930  7930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 17:40:54.834  7930  7930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:40:54.864  7930  7930 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:40:54.864  7930  7930 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:54.884  7930  7930 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-30 17:40:54.884  7930  7930 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 17:40:54.884  7930  7930 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 17:40:54.894  7930  7930 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 17:40:54.894  7930  7930 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:40:54.894  7930  7930 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 17:40:54.894  7930  7930 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:54.894  1017  1485 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-30 17:40:54.894  1017  1485 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,08-30 17:40:54.894  1017  1485 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-30 17:40:54.894  1017  1485 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-30 17:40:54.904  1017  1485 I ActivityManager: Killing 7428:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-30 17:40:54.944  6828  6828 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:40:54.944  7928  7928 D AndroidRuntime: 
08-30 17:40:54.944  7928  7928 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 17:40:54.944  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:40:54.944  6828  7213 I jxcore-log: 
,08-30 17:40:54.944  7928  7928 D AndroidRuntime: CheckJNI is OFF
,08-30 17:40:54.944  7928  7928 D AndroidRuntime: readGMSProperty: start
08-30 17:40:54.944  7928  7928 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:40:54.944  7928  7928 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 17:40:54.944  7928  7928 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:40:54.944  7928  7928 D AndroidRuntime: readGMSProperty: end
08-30 17:40:54.944  7928  7928 D AndroidRuntime: addProductProperty: start
,08-30 17:40:54.984  7445  7445 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:54.984  7445  7445 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 17:40:54.984  7445  7445 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-30 17:40:54.984  7445  7445 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-30 17:40:55.074  6828  6828 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:40:55.074  6828  7213 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:40:55.074  6828  7213 I jxcore-log: 
,08-30 17:40:55.084  7928  7928 E AffinityControl: AffinityControl: registerfunction enter
,08-30 17:40:55.094  7460  7460 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-30 17:40:55.104  7928  7928 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 17:40:55.114  7460  7460 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-30 17:40:55.114  7460  7460 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-30 17:40:55.124  7460  7460 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-30 17:40:55.134  1017  1339 D PackageManager: START PACKAGE DELETE: observer{342600605}
08-30 17:40:55.134  1017  1339 D PackageManager: pkg{<packageName>}
08-30 17:40:55.134  1017  1339 D PackageManager: user{0}
08-30 17:40:55.134  1017  1339 D PackageManager: caller{2000}
08-30 17:40:55.134  1017  1339 D PackageManager: flags{2}
08-30 17:40:55.134  1017  1339 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-30 17:40:55.134  1017  1339 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 17:40:55.134  1017  1339 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-30 17:40:55.134  1017  1339 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 17:40:55.134  1017  1339 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 17:40:55.144  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-30 17:40:55.144  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 17:40:55.144  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-30 17:40:55.144  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-30 17:40:55.144  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 17:40:55.154  1017  1056 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-30 17:40:55.164  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-30 17:40:55.164  1017  1042 I ActivityManager: Killing 6828:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 17:40:55.224   290   290 E SMD     : DCD OFF
,08-30 17:40:55.274  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{29e3b3c2 u0 com.test.thalitest/.MainActivity t163}
,08-30 17:40:55.274  1017  1042 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 17:40:55.284  1017  1042 D InputDispatcher: Focus left window: 6828
,08-30 17:40:55.284   257   450 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-30 17:40:55.284   257   453 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-30 17:40:55.294  1017  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-30 17:40:55.324  1017  1042 D InputDispatcher: Focused application released
,08-30 17:40:55.324  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 17:40:55.324  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:40:55.324  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-30 17:40:55.344  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 17:40:55.374  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:40:55.374  2827  2827 I art     : Explicit concurrent mark sweep GC freed 16602(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 795us total 41.529ms
,08-30 17:40:55.384  1854  1854 E SamsungIME: mOCRHelper is null
,08-30 17:40:55.384  1630  1878 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:40:55.394  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-30 17:40:55.394  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:40:55.394  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-30 17:40:55.404  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:40:55.404  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:40:55.404  1017  1123 V NetworkStats: performPollLocked() took 8ms
08-30 17:40:55.404  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:55.414  1430  1430 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:40:55.424  1430  1430 D RegisteredServicesCache: empty dynamic service
,08-30 17:40:55.424  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:55.424  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:40:55.434  1017  1339 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-30 17:40:55.444  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.444  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:55.444  1017  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:55.444  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-30 17:40:55.454   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:40:55.454   277  1012 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-30 17:40:55.454  1430  1430 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 17:40:55.454  1430  1430 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:40:55.484  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 17:40:55.484  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-30 17:40:55.484  1017  1041 W TextServicesManagerService: no available spell checker services found
,08-30 17:40:55.504  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-30 17:40:55.504  1017  1030 D SecContentProvider2: mCursor = null
,08-30 17:40:55.504  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.514  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.514  3768  3768 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,08-30 17:40:55.524  1017  1017 I art     : Explicit concurrent mark sweep GC freed 74714(4MB) AllocSpace objects, 12(193KB) LOS objects, 33% free, 23MB/35MB, paused 4.159ms total 181.301ms
,08-30 17:40:55.524  1017  1056 I art     : WaitForGcToComplete blocked for 172.179ms for cause Explicit
,08-30 17:40:55.574  3768  3768 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 17:40:55.574  1017  1224 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:40:55.574  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.584  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:55.584  1017  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:55.584  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:40:55.584  3768  7475 I iu.UploadsManager: num queued entries: 0
,08-30 17:40:55.584  3768  7475 I iu.UploadsManager: num updated entries: 0
,08-30 17:40:55.584  3768  7475 I iu.SyncManager: NEXT; no task
,08-30 17:40:55.594  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.594  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.604  3768  3768 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 17:40:55.604  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-30 17:40:55.604  3768  3768 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-30 17:40:55.604  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 17:40:55.614  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-30 17:40:55.614  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-30 17:40:55.614  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-30 17:40:55.614  2811  2811 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 17:40:55 GMT+02:00 2016
,08-30 17:40:55.614  1017  1339 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 17:40:55.614  1017  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.624  1017  1339 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:55.624  1017  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:55.624  1017  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 17:40:55.624  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 17:40:55.624  2811  2811 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 17:40:55.634  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 17:40:55.634  2811  2811 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 17:40:55.644  1017  1458 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-30 17:40:55.644  1017  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.644  1017  1458 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:55.644  1017  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:55.644  1017  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-30 17:40:55.644  2811  2811 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 17:40:55.654  2811  2811 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 17:40:55.654  2811  7967 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 17:40:55.654  2811  7967 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-30 17:40:55.674  2811  7967 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-30 17:40:55.674  2811  7967 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-30 17:40:55.674  2811  7967 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-30 17:40:55.704  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-30 17:40:55.704  2811  7967 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-30 17:40:55.714  2811  7967 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-30 17:40:55.714  2749  7969 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-30 17:40:55.714  2749  7969 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-30 17:40:55.714  7494  7494 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-30 17:40:55.714  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.724  7511  7511 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-30 17:40:55.724  7511  7511 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-30 17:40:55.724  7511  7511 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 17:40:55.724  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.724  1017  1056 I art     : Explicit concurrent mark sweep GC freed 9136(465KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 15.025ms total 198.918ms,
08-30 17:40:55.724  2749  7969 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 17:40:55.734  2811  2811 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 17:40:55.734  7511  7511 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-30 17:40:55.734  7511  7511 I SA      : [OR] == isSIMCardReady false ==
,08-30 17:40:55.744  7511  7511 I SA      : [SCU] == networkStateCheck == true
,08-30 17:40:55.744  7511  7511 I SA      : [DM] getCountryCodeFromCSC : PL
08-30 17:40:55.744  7511  7511 I SA      : isChinaCountryCode : false
08-30 17:40:55.744  7511  7511 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-30 17:40:55.744  7511  7511 I SA      : [OR] == networkStateCheck true ==
,08-30 17:40:55.764  7511  7511 I SA      : [OR] GetMyCountryZoneTask
,08-30 17:40:55.764  7511  7511 I SA      : [OR] onReceive END
,08-30 17:40:55.764  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-30 17:40:55.764  2749  7969 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-30 17:40:55.774  1017  1029 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-30 17:40:55.774  2749  7969 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-30 17:40:55.774  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.774  2749  7969 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-30 17:40:55.774  2749  7969 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-30 17:40:55.774  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:55.774  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:40:55.774  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-30 17:40:55.774  2749  7969 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-30 17:40:55.784  1756  1756 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:40:55.784  1017  1056 D PackageManager: delete codoeFile: 
,08-30 17:40:55.794  7511  7970 I SA      : [SRS] prepareGetMyCountryZone
,08-30 17:40:55.794  2749  7969 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-30 17:40:55.804  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.804  2668  2676 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-30 17:40:55.804  1756  1756 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-30 17:40:55.804  1756  1756 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-30 17:40:55.804  1756  1756 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-30 17:40:55.804  1756  1756 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 17:40:55.814  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-30 17:40:55.814  1017  3835 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-30 17:40:55.814  1017  3835 D SecContentProvider2: mCursor = null
,08-30 17:40:55.814  1756  1756 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:40:55.814  2749  7969 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-30 17:40:55.814  1756  1756 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-30 17:40:55.814  7511  7970 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-30 17:40:55.814  7511  7970 I SA      : [SSP] query invoked
,08-30 17:40:55.814  2749  7969 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-30 17:40:55.824  1017  1056 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-30 17:40:55.824  1017  1056 D PackageManager: result of delete: 1{342600605}
,08-30 17:40:55.824  7511  7970 I SA      : [TPMU] GetMccFromDB : null
,08-30 17:40:55.824  7511  7970 I SA      : [SCU] getMccFromPreferece mcc = 260
08-30 17:40:55.824  7511  7970 I SA      : [LBE] isSupportCheckDomainRegion : false
08-30 17:40:55.824  7511  7970 I SA      : [TPM] isNoProxy(default) : true
,08-30 17:40:55.834  2749  7969 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-30 17:40:55.844  1017  1859 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-30 17:40:55.844  1017  1859 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.844  7511  7970 E File    : fail readDirectory() errno=2
08-30 17:40:55.844  7928  7928 D AndroidRuntime: Shutting down VM
,08-30 17:40:55.844  1017  1859 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:40:55.844  1017  1859 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:55.844  1017  1859 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-30 17:40:55.844  2749  7969 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-30 17:40:55.844  1017  1049 I PowerManagerService: [PWL] Off : 75s ago
,08-30 17:40:55.854  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:40:55.854  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:40:55.854  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:40:55.854  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.854  1017  1224 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-30 17:40:55.854  1017  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.854  1017  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:40:55.854  1017  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:40:55.854  1017  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:40:55.864  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 17:40:55.864  1017  1056 D PackageManager: userId{-1}
08-30 17:40:55.864  1017  1056 D PackageManager: andCode{true}
,08-30 17:40:55.874  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 17:40:55.874  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 17:40:55.874  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 17:40:55.884  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 17:40:55.884  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.884  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:55.884  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:55.884  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:55.884  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:40:55.884  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.884  7370  7974 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-30 17:40:55.894  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:40:55.894  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:40:55.894  7370  7974 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:40:55.894  7370  7974 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 17:40:55.894  7370  7974 I System.out: (HTTPLog)-Thread-1380-69154195: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 17:40:55.894  7370  7974 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:40:55.894  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.894   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 17:40:55.894   277  1012 D Netd    : getNetworkForDns: using netid 504 for uid 10102
08-30 17:40:55.894  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:40:55.894  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:40:55.904  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.904  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-30 17:40:55.904  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:40:55.904  7978  7978 E Zygote  : MountEmulatedStorage(),
08-30 17:40:55.904  7978  7978 E Zygote  : v2
08-30 17:40:55.904  7978  7978 I libpersona: KNOX_SDCARD checking this for 10003
08-30 17:40:55.904  7978  7978 I libpersona: KNOX_SDCARD not a persona
,08-30 17:40:55.904  7978  7978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 17:40:55.914  7978  7978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 17:40:55.914  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7978 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 17:40:55.914  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:40:55.914  1017  3333 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 17:40:55.914  7978  7978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:40:55.914  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 17:40:55.914  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 17:40:55.914  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-30 17:40:55.914  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-30 17:40:55.914  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 17:40:55.934  7370  7974 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:40:55.944  7978  7978 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:40:55.944  7640  7640 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:40:55.944  7640  7640 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-30 17:40:55.944  7978  7978 D ActivityThread: Added TimaKeyStore provider
,08-30 17:40:55.944  7640  7640 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 17:40:55.954  1017  1458 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:40:55.984  7370  7974 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 17:40:56.004  7699  7699 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-30 17:40:56.054  7928  7928 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 17:40:56.144  3189  3260 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 17:40:56.164  1017  1319 E Watchdog: !@Sync 4

```
