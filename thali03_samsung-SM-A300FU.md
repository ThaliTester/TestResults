#### Test 82203060884b823_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
08-23 12:38:35.435  1019  1452 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6762 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-23 12:38:35.435  1019  1452 I ActivityManager: Killing 6425:com.osp.app.signin/u0a36 (adj 15): empty #21
--------- beginning of main
08-23 12:38:35.445  6762  6762 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:35.445  6762  6762 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:35.445  1019  1269 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.445  1019  1269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:35.445  1019  1269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
08-23 12:38:35.445  1019  1045 W ProcessCpuTracker: Skipping unknown process pid 6406
08-23 12:38:35.445  1019  1269 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-23 12:38:35.445  1019  1269 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-23 12:38:35.455  6731  6731 D AcmsService: Enter Oncreate
08-23 12:38:35.455  6731  6731 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 12:38:35.455  6731  6731 D AcmsService: creating AcmsCore
08-23 12:38:35.455  6731  6731 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-23 12:38:35.455  6731  6731 D AcmsCore: AcmsCore
08-23 12:38:35.455  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.455  1019  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.455  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 12:38:35.455  6731  6731 D AcmsCore: init
08-23 12:38:35.455  6731  6731 D AcmsCore: Looper handler is not null
08-23 12:38:35.455  6731  6731 D AcmsCore: Post to AcmsCoreHandler
08-23 12:38:35.455  6731  6731 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 12:38:35.455  6731  6731 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-23 12:38:35.455  6731  6731 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-23 12:38:35.455  6731  6731 D AcmsService: onStartCommand
08-23 12:38:35.455  6731  6731 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
08-23 12:38:35.455  6731  6731 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-23 12:38:35.455  6731  6731 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-23 12:38:35.455  6731  6731 D AcmsService: Incremented Counter Value : onStartCommand
08-23 12:38:35.455  1019  1081 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 12:38:35.455  6635  6697 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-23 12:38:35.455  6635  6697 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
08-23 12:38:35.455  6635  6697 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 12:38:35.455  6635  6697 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:38:35.455  6635  6697 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 12:38:35.465  1884  1884 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 12:38:35.465  6731  6782 D AcmsCertificateMngr: AcmsCertificateMngr
08-23 12:38:35.465  6635  6697 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-23 12:38:35.465  6635  6697 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:38:35.475  1884  1884 I ConfigFetchService: launchTask
08-23 12:38:35.475  6731  6782 D AcmsRevocationMngr: AcmsRevocationMngr
08-23 12:38:35.475  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.475  1019  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.475  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-23 12:38:35.475  1019  1508 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-23 12:38:35.475  6731  6731 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-23 12:38:35.475  6748  6748 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 12:38:35.475  1019  1081 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 12:38:35.475  6748  6748 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:38:35.475  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-23 12:38:35.475  6748  6748 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:38:35.475  6748  6748 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 12:38:35.475  6748  6748 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 12:38:35.475  6748  6748 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 12:38:35.475  6748  6748 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 12:38:35.485  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.485  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.485  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-23 12:38:35.485  6635  6697 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
08-23 12:38:35.485  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 12:38:35.485  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-23 12:38:35.485  6762  6762 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:38:35.485  1019  1269 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 12:38:35.485  1019  1269 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-23 12:38:35.495  1019  1269 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.495  1019  1269 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.495  1019  1269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 12:38:35.515  1884  1884 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-23 12:38:35.515  1884  1884 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 12:38:35.515  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-23 12:38:35.515  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.515  1019  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.515  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:38:35.535  1884  6784 I PeopleContactsSync: CP2 sync disabled
08-23 12:38:35.535  6731  6731 D AcmsService: Inside handle Intent
08-23 12:38:35.535  6731  6731 D AcmsService: App added - package name: com.test.thalitest
08-23 12:38:35.535  6731  6731 D AcmsCore: Post to AcmsCoreHandler
08-23 12:38:35.535  6731  6731 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 12:38:35.535  6731  6731 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-23 12:38:35.535  6731  6731 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
08-23 12:38:35.535  6731  6731 D AcmsService: Decremented Counter Value : handleStartIntent
08-23 12:38:35.535  6731  6731 D AcmsServiceMonitor: Decrementing - Counter value: 2
08-23 12:38:35.545  1019  1512 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-23 12:38:35.555  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.555  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.555  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.555  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.565  6791  6791 E Zygote  : MountEmulatedStorage()
08-23 12:38:35.565  6791  6791 E Zygote  : v2
08-23 12:38:35.565  6791  6791 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:35.565  6791  6791 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:35.565  6791  6791 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:35.575  1019  1512 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 12:38:35.575  6791  6791 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:35.575  6791  6791 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:38:35.575  1884  1884 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
08-23 12:38:35.605  1884  6783 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Umja4hR2vPmr2HjzygovF1CCF3nkf_qgRwZ9MpA8xB4n76e7WVqfizrA0iY4MZKcBGxrZRiH1V18NGNOzZQ1nEnYc6scgcdaIJzdl2c4noI1GoIgP0vfxOrT9LIomKTuKfvBOAS44-qF7TN5YF0l9S9Wc1xJQA6tkhN3jiYbHRQN_x56kmRqJvti1XfECPXH8c-dJVHc9R8w6fvmqOCg3P92JLLRQrwPDZ84m0vTyLAYCN2MY
08-23 12:38:35.625  1019  1508 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
08-23 12:38:35.625  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.625  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.625  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.625  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.645  1019  1508 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6810 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
08-23 12:38:35.645  6810  6810 E Zygote  : MountEmulatedStorage()
08-23 12:38:35.645  6810  6810 I libpersona: KNOX_SDCARD checking this for 10014
08-23 12:38:35.645  6810  6810 E Zygote  : v2
08-23 12:38:35.645  6810  6810 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:35.645  6810  6810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:35.655  6810  6810 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:35.655  6810  6810 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-23 12:38:35.675  6791  6791 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:35.685  6791  6791 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:35.685  6810  6810 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:35.685  6810  6810 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:35.695  1884  6783 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-23 12:38:35.745  6558  6558 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
08-23 12:38:35.745  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-23 12:38:35.745  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.745  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:35.745  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
08-23 12:38:35.755  6791  6791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
08-23 12:38:35.765  1019  1452 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-23 12:38:35.765  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
08-23 12:38:35.765  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.765  1019  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:35.765  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
08-23 12:38:35.785  1019  1508 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-23 12:38:35.785  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-23 12:38:35.785  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.785  1019  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.785  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 12:38:35.795  6444  6444 I Mms/MmsApp:  start initViewCache mms
08-23 12:38:35.795  6444  6444 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1890.306197
08-23 12:38:35.795  6444  6444 D Mms/ComposeMessageFragment: fillCache, easy = false
08-23 12:38:35.795  1019  1490 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-23 12:38:35.795  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-23 12:38:35.795  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.795  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:35.795  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-23 12:38:35.805  1019  1567 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-23 12:38:35.805  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.805  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.805  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.805  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.815  6801  6801 D AndroidRuntime: 
08-23 12:38:35.815  6801  6801 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 12:38:35.815  6801  6801 D AndroidRuntime: CheckJNI is OFF
08-23 12:38:35.815  6801  6801 D AndroidRuntime: readGMSProperty: start
08-23 12:38:35.815  6801  6801 D AndroidRuntime: readGMSProperty: already setted!!
08-23 12:38:35.815  6801  6801 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 12:38:35.815  6801  6801 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 12:38:35.815  6801  6801 D AndroidRuntime: readGMSProperty: end
08-23 12:38:35.815  6801  6801 D AndroidRuntime: addProductProperty: start
08-23 12:38:35.835  6833  6833 E Zygote  : MountEmulatedStorage()
08-23 12:38:35.835  6833  6833 E Zygote  : v2
08-23 12:38:35.835  6833  6833 I libpersona: KNOX_SDCARD checking this for 10087
08-23 12:38:35.835  1019  1567 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6833 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-23 12:38:35.845  6833  6833 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:35.845  6833  6833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:35.845  6833  6833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:35.845  6833  6833 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-23 12:38:35.865  1019  1081 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
08-23 12:38:35.865  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
08-23 12:38:35.865  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.865  1019  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.865  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
08-23 12:38:35.875  1019  1559 I ActivityManager: Killing 6444:com.android.mms/u0a41 (adj 15): empty #21
08-23 12:38:35.885  6833  6833 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:35.885  6833  6833 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:35.915  1019  1566 D CountryDetector: No listener is left
08-23 12:38:35.925  1019  1490 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
08-23 12:38:35.925  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
08-23 12:38:35.925  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:35.925  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:35.925  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
08-23 12:38:35.925  1019  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-23 12:38:35.945  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.945  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.945  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.945  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:35.965  6864  6864 E Zygote  : MountEmulatedStorage()
08-23 12:38:35.965  6864  6864 E Zygote  : v2
08-23 12:38:35.965  6864  6864 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:35.975  6864  6864 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:35.975  6864  6864 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:35.985  6864  6864 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:35.985  6801  6801 E AffinityControl: AffinityControl: registerfunction enter
08-23 12:38:35.985  6864  6864 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:38:36.005  1019  1508 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6864 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 12:38:36.015   315   315 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 904us total 33.744ms
08-23 12:38:36.015  6801  6801 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 12:38:36.025  1019  1032 E PersonaManagerService: inState():  stateMachine is null !!
08-23 12:38:36.035  1019  1032 I PersonaManagerService: PersonaId don't exist
08-23 12:38:36.035  1019  1032 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 12:38:36.035  6864  6864 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:36.035  6864  6864 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:36.035   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 22.482ms
08-23 12:38:36.035  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 12:38:36.055   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 17.076ms
08-23 12:38:36.065  1884  6783 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-23 12:38:36.065  1884  6783 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 12:38:36.065  1884  6783 I System.out: (HTTPLog)-Static: isShipBuild true
08-23 12:38:36.065  1884  6783 I System.out: (HTTPLog)-Thread-243-994567709: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 12:38:36.065  1884  6783 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 12:38:36.065   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 12:38:36.065   279   966 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-23 12:38:36.145  1019  1567 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 12:38:36.165  1884  6783 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 12:38:36.165  1884  6783 I qtaguid : Tagging socket 103 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1884, getuid(): 10011
08-23 12:38:36.185  1019  1512 E EdmStorageProvider: Admin not in database, something went wrong
08-23 12:38:36.195  1884  6783 I qtaguid : Tagging socket 107 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1884, getuid(): 10011
08-23 12:38:36.235  1019  1559 I art     : Explicit concurrent mark sweep GC freed 141487(7MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 22MB/34MB, paused 6.246ms total 282.858ms
08-23 12:38:36.235  1019  1032 W ActivityManager: mDVFSHelper.acquire()
08-23 12:38:36.235  1019  1032 D FocusedStackFrame: Set to : 0
08-23 12:38:36.245  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.245  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.245  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.245  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.245  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 12:38:36.245  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 12:38:36.265  6892  6892 E Zygote  : MountEmulatedStorage()
08-23 12:38:36.265  6892  6892 E Zygote  : v2
08-23 12:38:36.265  6892  6892 I libpersona: KNOX_SDCARD checking this for 10170
08-23 12:38:36.265  6892  6892 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:36.265  6892  6892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:36.265  1019  1032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6892 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 12:38:36.265  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 12:38:36.265  6892  6892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:36.265  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 12:38:36.265  1019  1032 D InputDispatcher: Focused application set to: xxxx
08-23 12:38:36.265  1019  1032 D InputDispatcher: Focus left window: 1495
08-23 12:38:36.265  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 12:38:36.265  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 12:38:36.265  6892  6892 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 12:38:36.265   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-23 12:38:36.265  6801  6801 D AndroidRuntime: Shutting down VM
08-23 12:38:36.275  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.275  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.275  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.275  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.285  6900  6900 E Zygote  : MountEmulatedStorage()
08-23 12:38:36.285  6900  6900 E Zygote  : v2
08-23 12:38:36.285  6900  6900 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:36.285  6900  6900 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:36.285  6900  6900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:36.285  1019  1045 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6900 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 12:38:36.295  6900  6900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:36.295  6900  6900 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:38:36.305  6892  6892 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:36.305  6892  6892 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:36.315  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 12:38:36.315  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:38:36.315  1019  1486 I ActivityManager: Killing 6365:com.android.defcontainer/u0a3 (adj 15): empty #21
08-23 12:38:36.325  1019  1031 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 12:38:36.325  1019  6888 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 12:38:36.325  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 12:38:36.335  6900  6900 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:36.335  6900  6900 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:36.345  1019  1019 V ActivityManager: Display changed displayId=0
08-23 12:38:36.345  1019  1453 D LocationManagerService: getProviders()=[passive, gps]
08-23 12:38:36.355  1019  6888 D PersonaManager: isKioskContainerExistOnDevice
08-23 12:38:36.395  6748  6748 D NearbySource: Nearby Source Create!
08-23 12:38:36.395  6748  6748 D NearbyContext: Nearby Context Create!
08-23 12:38:36.395  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 12:38:36.395   259  1101 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-23 12:38:36.415  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{3b47e61d token=android.os.BinderProxy@1ad7db36 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 12:38:36.415  1495  1495 D Launcher: onTrimMemory. Level: 20
08-23 12:38:36.435  1884  6790 W BaseAppContext: Using Auth Proxy for data requests.
08-23 12:38:36.435  1884  6790 W BaseAppContext: Using Auth Proxy for data requests.
08-23 12:38:36.445  1884  6783 I qtaguid : Untagging socket 103
08-23 12:38:36.445  1884  1884 I ConfigFetchService: fetch service done; releasing wakelock
08-23 12:38:36.445  1884  1884 I ConfigFetchService: stopping self
08-23 12:38:36.455  6900  6900 D AASAservice: onCreate()
08-23 12:38:36.455  6900  6900 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
08-23 12:38:36.455  6864  6864 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 12:38:36.455  6864  6864 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 12:38:36.455  6864  6864 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-23 12:38:36.465  2769  2769 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
08-23 12:38:36.475  6801  6801 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 12:38:36.475  1019  6889 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,08-23 12:38:36.485  1019  6889 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
08-23 12:38:36.485  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:36.485  1019  6889 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:36.485  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-23 12:38:36.505  6864  6864 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-23 12:38:36.505  6864  6864 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-23 12:38:36.505  6864  6864 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-23 12:38:36.505  6864  6864 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,08-23 12:38:36.505  1019  6889 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,08-23 12:38:36.515  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:36.515  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.515  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.515  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:36.525  6930  6930 E Zygote  : MountEmulatedStorage()
08-23 12:38:36.525  6930  6930 E Zygote  : v2
08-23 12:38:36.525  6930  6930 I libpersona: KNOX_SDCARD checking this for 10026
08-23 12:38:36.525  6930  6930 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:36.525  6930  6930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:36.525  6930  6930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:36.535  6930  6930 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 12:38:36.535  1019  6889 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6930 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-23 12:38:36.545  1019  6889 I ActivityManager: Killing 6474:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-23 12:38:36.545   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-23 12:38:36.545   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:38:36.555  6714  6788 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-23 12:38:36.555  6748  6748 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-23 12:38:36.555  6748  6748 D SLinkSource: Samsung link source created
,08-23 12:38:36.555  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:36.555  6930  6930 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:36.575  6892  6892 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-23 12:38:36.575  1019  1566 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-23 12:38:36.575  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-23 12:38:36.575  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:36.575  1019  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:36.575  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-23 12:38:36.615   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8f367c8
08-23 12:38:36.615   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-23 12:38:36.615   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-23 12:38:36.615   273   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1192007544)
,08-23 12:38:36.655  1884  6790 W BaseAppContext: Using Auth Proxy for data requests.,
,08-23 12:38:36.675  1884  6790 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 12:38:36.675  1884  6790 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 12:38:36.675  6892  6892 I cr.library_loader: Time to load native libraries: 38 ms (timestamps 7325-7363)
08-23 12:38:36.675   273   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-23 12:38:36.675   273   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-23 12:38:36.675  6892  6892 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 12:38:36.675   273   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1192007544) wakelock released: 1, error no: 0
08-23 12:38:36.675   273   341 I rmt_storage: 
,08-23 12:38:36.675   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8f367c8
,08-23 12:38:36.695  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-23 12:38:36.705  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.705  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.705  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.705  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:36.715  6892  6892 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e36f6ff}
08-23 12:38:36.715  6892  6892 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 12:38:36.715  6892  6892 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 12:38:36.725  6951  6951 E Zygote  : MountEmulatedStorage()
08-23 12:38:36.725  1019  1490 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6951 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-23 12:38:36.725  6951  6951 E Zygote  : v2
08-23 12:38:36.725  6951  6951 I libpersona: KNOX_SDCARD checking this for 10148
08-23 12:38:36.725  6951  6951 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:36.725  6951  6951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:36.735  6951  6951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 12:38:36.735  6951  6951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:38:36.745  1019  1452 I ActivityManager: Killing 6489:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-23 12:38:36.745  6748  6948 D ContactProvider: getAllContactInfoList Start
08-23 12:38:36.745  1019  1508 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:38:36.765  6951  6951 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:36.765  6951  6951 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:36.775  1019  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 12:38:36.775  6892  6892 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 12:38:36.775  6892  6892 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:38:36.775  6748  6748 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-23 12:38:36.785  6892  6892 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 12:38:36.785  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:36.795  6748  6948 D ContactProvider: getAllContactInfoList End
08-23 12:38:36.795  6748  6948 I syncContacts: thread: 1248, sync time = 102
08-23 12:38:36.795  1884  6790 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 12:38:36.805  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:36.815  6951  6951 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-23 12:38:36.815  1019  1486 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,08-23 12:38:36.815  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.815  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.815  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.815  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:36.835  6971  6971 E Zygote  : MountEmulatedStorage()
08-23 12:38:36.835  6971  6971 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:36.835  6971  6971 E Zygote  : v2
08-23 12:38:36.835  6971  6971 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:36.835  6971  6971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:36.835  1019  1486 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 12:38:36.835  6971  6971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:36.835  1019  1486 I ActivityManager: Killing 6505:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-23 12:38:36.835  6971  6971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:36.855  6930  6930 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-23 12:38:36.855  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:36.865  1019  1045 W ActivityManager: Activity pause timeout for ActivityRecord{1b39dc1b u0 com.test.thalitest/.MainActivity t163}
,08-23 12:38:36.865  6971  6971 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:36.865  6971  6971 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:36.885  1019  1566 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,08-23 12:38:36.885  6971  6971 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,08-23 12:38:36.885  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.885  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.885  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.885  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:36.905  1019  1559 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6505, ws=null) (elapsedTime=2708)
,08-23 12:38:36.905  1019  1566 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6990 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
08-23 12:38:36.905  1019  1566 I ActivityManager: Killing 6520:com.wsomacp/u0a23 (adj 15): empty #21
,08-23 12:38:36.905  6990  6990 E Zygote  : MountEmulatedStorage()
08-23 12:38:36.905  6990  6990 E Zygote  : v2
08-23 12:38:36.905  6990  6990 I libpersona: KNOX_SDCARD checking this for 10041
08-23 12:38:36.905  6990  6990 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:36.915  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:36.915  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 12:38:36.915  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-23 12:38:36.935  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:36.935  6990  6990 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:36.955  6990  6990 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-23 12:38:36.955  6990  6990 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 12:38:36.955  6990  6990 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 12:38:36.955  6990  6990 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 12:38:36.965  6990  6990 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-23 12:38:36.995  1019  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-23 12:38:36.995  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:36.995  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.995  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:36.995  1019  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:37.005  6892  6892 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-23 12:38:37.005  6892  6892 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 12:38:37.005  6892  6892 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 12:38:37.005  6892  6892 I Adreno-EGL: Local Branch: 
08-23 12:38:37.005  6892  6892 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 12:38:37.005  6892  6892 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 12:38:37.005  6892  6892 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 12:38:37.005  7012  7012 I libpersona: KNOX_SDCARD checking this for 10152
08-23 12:38:37.005  7012  7012 E Zygote  : MountEmulatedStorage()
08-23 12:38:37.005  7012  7012 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:37.005  7012  7012 E Zygote  : v2
08-23 12:38:37.015  7012  7012 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:38:37.015  7012  7012 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:38:37.015  7012  7012 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-23 12:38:37.015  1019  1486 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7012 uid=10152 gids={50152, 9997} abi=armeabi-v7a,
08-23 12:38:37.015  1019  1486 I ActivityManager: Killing 6539:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-23 12:38:37.025  6990  6990 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-23 12:38:37.025  1019  6889 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 12:38:37.035  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:37.035  1019  6889 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:37.035  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-23 12:38:37.035  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.035  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 12:38:37.035  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-23 12:38:37.035  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.035  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:37.035  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:37.035  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:38:37.055  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.055  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.055  7012  7012 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:37.055  7012  7012 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:37.075  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.075  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.075  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.075  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.075  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 12:38:37.085  6930  6930 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-23 12:38:37.095  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-23 12:38:37.095  1019  1031 W ActivityManager: userId = 0, bbcId = -10000,
08-23 12:38:37.095  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:37.095  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:38:37.105  1019  1452 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 12:38:37.105  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-23 12:38:37.105  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:37.105  1019  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:37.105  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:38:37.115  1019  6889 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 12:38:37.115  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:37.115  1019  6889 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 12:38:37.115  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:38:37.135  1019  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 12:38:37.135  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:37.135  6930  6930 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 12:38:37.135  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 12:38:37.145  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 12:38:37.145  7012  7012 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-23 12:38:37.145  7012  7012 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,08-23 12:38:37.145  6930  6930 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 12:38:37.165  7012  7012 I TapandpayWidget:Utils: Clear T&P info.
,08-23 12:38:37.185  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.185  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.185  6930  6930 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-23 12:38:37.195  6892  6892 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 12:38:37.215  6714  6788 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 659 ms] updated apps [took 659 ms] 
,08-23 12:38:37.215  7012  7012 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-23 12:38:37.225  1019  6888 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-23 12:38:37.225  6892  6892 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 12:38:37.225  6892  6892 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 12:38:37.225  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:37.225  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:37.225  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:37.235  6892  6892 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 12:38:37.235  6892  6892 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-23 12:38:37.235  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:37.235  6990  6990 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 138.799ms
,08-23 12:38:37.245  7051  7051 E Zygote  : MountEmulatedStorage()
,08-23 12:38:37.245  7051  7051 E Zygote  : v2
08-23 12:38:37.245  7051  7051 I libpersona: KNOX_SDCARD checking this for 10009
08-23 12:38:37.245  7051  7051 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:37.255  7051  7051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:37.255  7051  7051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:37.265  1019  6888 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7051 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-23 12:38:37.265  7051  7051 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 12:38:37.275  1019  6888 I ActivityManager: Killing 6265:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-23 12:38:37.275  1019  1081 I ActivityManager: Killing 6281:com.android.calendar/u0a131 (adj 15): empty #21
,08-23 12:38:37.285  1019  1081 I ActivityManager: Killing 6567:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-23 12:38:37.325  7051  7051 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:37.325  7051  7051 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:37.325   289   289 E SMD     : DCD OFF
,08-23 12:38:37.355  1884  6790 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 109.735ms
,08-23 12:38:37.375  6930  6930 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-23 12:38:37.375  1019  1566 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,08-23 12:38:37.375  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-23 12:38:37.375  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:37.375  1019  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:37.375  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-23 12:38:37.415  6930  6930 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-23 12:38:37.415  6990  6990 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 175.898ms
,08-23 12:38:37.415  6990  7071 D Mms/ArtClassLoader: init before art
,08-23 12:38:37.425  6990  6990 D Mms/TelephonyPermission: start operation mode monitor
,08-23 12:38:37.445  6990  6990 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 12:38:37.445  6930  7070 D Ads     : Skipping gmscore version check
,08-23 12:38:37.455  6892  6892 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:38:37.465  6990  6990 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-23 12:38:37.465  6990  6990 D Mms/TelephonyPermission: isDefault true
,08-23 12:38:37.465  6990  6990 D Mms/MmsApp: onCreate() com.android.mms
,08-23 12:38:37.495  1019  1508 I ActivityManager: Killing 6595:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-23 12:38:37.495  1687  1782 I art     : Explicit concurrent mark sweep GC freed 10719(491KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.073ms total 57.177ms
,08-23 12:38:37.505  6892  6892 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 12:38:37.515  6892  6892 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-23 12:38:37.515  6892  6892 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-23 12:38:37.525  1019  1508 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-23 12:38:37.525  6892  6892 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 12:38:37.535  6892  6892 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:38:37.535  6892  6892 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:38:37.555  1019  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 12:38:37.555  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:37.555  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:37.555  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-23 12:38:37.565  6990  6990 D Mms/MmsApp: [start]    initCountryIso consume time = 539.106146
,08-23 12:38:37.575  1019  6888 D CountryDetector: The first listener is added
,08-23 12:38:37.585  6990  6990 D Mms/MmsApp: [end]    initCountryIso consume time = 19.150468
,08-23 12:38:37.585  6990  6990 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.730365
,08-23 12:38:37.585  6930  6930 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-23 12:38:37.605  6990  6990 D Mms/MmsConfig: before partial update
,08-23 12:38:37.655  6990  6990 D Mms/MmsConfig: Load Resize quality : 80
,08-23 12:38:37.665  6990  6990 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,08-23 12:38:37.665  6990  6990 D EasySignUpManager_1.0.1: isAuth is false
08-23 12:38:37.665  6990  6990 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,08-23 12:38:37.675  1471  1969 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6990,
,08-23 12:38:37.675  1471  1969 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.993 ms
,08-23 12:38:37.685  6892  7082 D OpenGLRenderer: Render dirty regions requested: true
,08-23 12:38:37.685  6990  6990 D EasySignUpManager_1.0.1: isAuth is false
08-23 12:38:37.685  6990  6990 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,08-23 12:38:37.695  6990  6990 E CscParser: mps_code.dat does not exist
,08-23 12:38:37.695  6990  6990 E CscParser: customer_path =/system/csc/customer.xml
08-23 12:38:37.695  6990  6990 E CscParser: fileName + /system/csc/customer.xml
,08-23 12:38:37.695  1019  6889 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 12:38:37.695  1019  6889 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 12:38:37.695  1019  6889 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 12:38:37.695  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 12:38:37.695  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 12:38:37.695  6892  6892 V ActivityThread: updateVisibility : ActivityRecord{56b137e token=android.os.BinderProxy@37757500 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 12:38:37.695  6892  7045 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-23 12:38:37.695  1019  3416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 12:38:37.705  6892  6892 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 12:38:37.705  6892  6892 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-23 12:38:37.715   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-23 12:38:37.735  6990  6990 E CscParser: mps_code.dat does not exist
08-23 12:38:37.735  6990  6990 E CscParser: customer_path =/system/csc/customer.xml
08-23 12:38:37.735  6990  6990 E CscParser: fileName + /system/csc/customer.xml
08-23 12:38:37.735  1019  1453 D InputDispatcher: Focus entered window: 6892
08-23 12:38:37.745  6990  6990 D CscParser: getInstance fileName =/system/csc/customer.xml
08-23 12:38:37.745  6990  6990 D Mms/MmsConfig:  enable multiwindow = false
08-23 12:38:37.745  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 12:38:37.745  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:38:37.745  6892  6892 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 12:38:37.745  6892  7082 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 12:38:37.765  6990  6990 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-23 12:38:37.765  6990  6990 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-23 12:38:37.765  6833  6924 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-23 12:38:37.765  6833  6924 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 12:38:37.765  6833  6924 I GAv4    :   adb logcat -s GAv4
08-23 12:38:37.765  6892  7082 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-23 12:38:37.765  6892  7082 D OpenGLRenderer: Enabling debug mode 0
08-23 12:38:37.775  6990  6990 D Mms/MmsConfig: [end]    init() consume time = 194.831042
08-23 12:38:37.785  6990  6990 D Mms/Contact: [start]    init() consume time = 3.393906
08-23 12:38:37.795  1019  1486 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 12:38:37.805  1019  7090 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 12:38:37.815  1182  1182 D PanelView: There is/are notification(s) 
08-23 12:38:37.815  6833  6924 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-23 12:38:37.815  1019  1032 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 12:38:37.815  6990  6990 D Mms/Contact: [end]    init consume time = 34.440208
08-23 12:38:37.825  1471  1969 D TP/MmsSmsProvider: query,matched:13, calling pid = 6990
08-23 12:38:37.825  1019  1050 I ActivityManager: Displayed Component not be shown by security: +1s467ms (total +1s585ms)
08-23 12:38:37.835  6892  6892 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 12:38:37.835  6892  6892 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37757500 time:98520
08-23 12:38:37.835  1471  1969 D TP/MmsSmsProvider: match 13:Elapsed time : 9.304 ms
08-23 12:38:37.835  6990  7092 D Mms/DraftCache: [start]    rebuildCache consume time = 18.384323
08-23 12:38:37.835  1019  1050 W ActivityManager: mDVFSHelper.release()
08-23 12:38:37.835  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b39dc1b u0 com.test.thalitest/.MainActivity t163} time:98526
08-23 12:38:37.845   259  1101 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-23 12:38:37.845   259  1102 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-23 12:38:37.845  1901  1901 I SamsungIME: getCurrentCandidateView
08-23 12:38:37.845  1471  1875 D TP/MmsSmsProvider: query,matched:12, calling pid = 6990
08-23 12:38:37.845  1471  1875 D TP/MmsSmsProvider: match 12:Elapsed time : 1.968 ms
08-23 12:38:37.855  6990  6990 D Mms/MethodReflector: getSubId is called
08-23 12:38:37.855  6990  6990 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-23 12:38:37.855  6990  6990 D Mms/MethodReflector: getTelephonyProperty is called
08-23 12:38:37.855  6990  6990 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-23 12:38:37.855  6990  6990 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 12:38:37.855  6990  6990 D Mms/DownloadManager: auto download without roaming -> true
08-23 12:38:37.855  6990  6990 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-23 12:38:37.855  6990  6990 D Mms/MethodReflector: getSubId is called
08-23 12:38:37.855  6990  7092 D Mms/DraftCache: [end]    rebuildCache consume time = 26.257604
08-23 12:38:37.865  6892  6892 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6892
08-23 12:38:37.865  6990  6990 D Mms/MethodReflector: getDefaultSmsSubId is called
08-23 12:38:37.865  6990  6990 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-23 12:38:37.865  6990  6990 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-23 12:38:37.865  6990  6990 D Mms/MethodReflector: getTelephonyProperty is called
08-23 12:38:37.865  6990  6990 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-23 12:38:37.865  6990  6990 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-23 12:38:37.865  6990  6990 D Mms/DownloadManager: auto download without roaming -> true
08-23 12:38:37.865  6990  6990 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-23 12:38:37.865  6990  6990 D Mms/DownloadManager: auto download during roaming secondary -> false
08-23 12:38:37.865  6990  6990 D Mms/DownloadManager: mAutoDownload ------> true
08-23 12:38:37.875  6833  6924 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-23 12:38:37.915  6833  6924 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-23 12:38:37.935  6990  7071 W art     : Verification of int com.android.mms.util.HandleComposerAttachment.getAvailableSlideCount(int) took 108.546ms
08-23 12:38:37.965  6990  6990 D ComposerPerformance: 1471948717982 ms / [DONE] Composer constructor
08-23 12:38:37.965  6990  6990 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-23 12:38:37.975  6990  7101 D Mms/Conversation: [start]    init() consume time = 110.109844
08-23 12:38:37.975  6990  6990 I Mms/ReservationManager: ReservationManager()
08-23 12:38:37.975  6990  6990 I Mms/ReservationManager: resetAfterConnected()
08-23 12:38:37.975  1884  1898 W art     : Suspending all threads took: 7.627ms
08-23 12:38:37.975  1471  1484 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-23 12:38:37.975  1471  1969 D TP/MmsSmsProvider: query,matched:7, calling pid = 6990
08-23 12:38:37.975  1471  1969 D TP/MmsSmsProvider: match 7:Elapsed time : 3.098 ms
08-23 12:38:37.975  1471  1484 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-23 12:38:37.985  1471  1484 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-23 12:38:37.985  1471  1484 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-23 12:38:37.985  6990  6990 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-23 12:38:37.995  6990  6990 D Mms/MmsApp: [end]    onCreate() consume time = 23.132552
08-23 12:38:37.995  1471  1484 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-23 12:38:37.995  1471  1484 D TP/MmsSmsProvider: need read changed broadcast:false
08-23 12:38:37.995  6990  7101 D Mms/Conversation: [end]    init consume time = 1.282396
08-23 12:38:37.995  6990  7101 D Mms/MessagingNotification: [start]    init() consume time = 3.809323
08-23 12:38:38.005  6990  6990 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-23 12:38:38.005  6990  7101 D Mms/MessagingNotification: [end]    init consume time = 10.734427
08-23 12:38:38.015  6990  6990 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-23 12:38:38.015  1471  1488 D TP/MmsSmsProvider: query,matched:0, calling pid = 6990
08-23 12:38:38.015  1471  1488 V TP/MmsSmsProvider: getSimpleConversations entered.
08-23 12:38:38.015  1471  1488 D TP/MmsSmsProvider: match 0:Elapsed time : 3.006 ms
08-23 12:38:38.015  6990  6990 D Mms/MethodReflector: getSubId is called
08-23 12:38:38.015  6990  6990 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-23 12:38:38.015  6990  6990 D Mms/MethodReflector: getTelephonyProperty is called
08-23 12:38:38.025  6833  6854 W art     : Suspending all threads took: 56.926ms
08-23 12:38:38.025  6990  6990 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-23 12:38:38.025  6990  6990 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 12:38:38.025  6990  6990 D Mms/DownloadManager: auto download without roaming -> true
08-23 12:38:38.025  6990  6990 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-23 12:38:38.035  6990  6990 D Mms/DownloadManager: mAutoDownload ------> true
08-23 12:38:38.045  1019  1490 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-23 12:38:38.045  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.045  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.045  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.045  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.055  6833  7098 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-23 12:38:38.055  7107  7107 I libpersona: KNOX_SDCARD checking this for 10068
08-23 12:38:38.055  7107  7107 E Zygote  : MountEmulatedStorage()
08-23 12:38:38.055  7107  7107 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:38.055  7107  7107 E Zygote  : v2
08-23 12:38:38.065  1019  1490 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7107 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-23 12:38:38.055  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:38.065  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:38.065  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-23 12:38:38.065  6990  7105 D Mms/Synchronizer: [start]    doSync consume time = 55.560573
08-23 12:38:38.075  6990  6990 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-23 12:38:38.075  6990  7104 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 8.244375
08-23 12:38:38.075  1019  1566 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-23 12:38:38.075  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-23 12:38:38.075  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:38.075  1019  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:38.075  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-23 12:38:38.085  1019  6889 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-23 12:38:38.085  6990  7071 D Mms/ArtClassLoader: init [DONE] art
08-23 12:38:38.085  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.085  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.085  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.085  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.085  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:38.085  1471  1488 D TP/MmsSmsProvider: update, matched:300, calling pid = 6990
08-23 12:38:38.085  7107  7107 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:38.085  1471  1488 V TP/MmsSmsProvider: syncDBData start
08-23 12:38:38.085  1471  1488 V TP/MmsSmsProvider: syncDBData sms end
08-23 12:38:38.085  1471  1488 V TP/MmsSmsProvider: syncDBData mms end
08-23 12:38:38.085  1471  1488 V TP/MmsSmsProvider: syncDBData end
08-23 12:38:38.095  7122  7122 E Zygote  : MountEmulatedStorage()
08-23 12:38:38.095  7122  7122 E Zygote  : v2
08-23 12:38:38.095  7122  7122 I libpersona: KNOX_SDCARD checking this for 10042
08-23 12:38:38.095  7122  7122 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:38.095  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:38.105  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:38.105  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-23 12:38:38.105  6990  7128 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-23 12:38:38.115  1019  6889 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7122 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-23 12:38:38.115  6990  7128 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-23 12:38:38.125  1019  1453 I ActivityManager: Killing 6611:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-23 12:38:38.125  1019  1453 I ActivityManager: Killing 6558:com.android.providers.calendar/u0a37 (adj 15): empty #22
08-23 12:38:38.135  1471  1969 D TP/MmsSmsProvider: query,matched:400, calling pid = 6990
08-23 12:38:38.135  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:38.135  7122  7122 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:38.165  6990  7105 D Mms/Synchronizer: [end]    doSync consume time = 87.489166
08-23 12:38:38.165  6892  6892 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-23 12:38:38.185  6990  7104 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 20.826875
08-23 12:38:38.215  1901  1901 D SamsungIME: Dismiss ExpandCandiate
08-23 12:38:38.225  1884  4392 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-23 12:38:38.265  6892  7088 D jxcore_app_log: JniHelper::setJavaVM(0xb808a2b0), pthread_self() = -1201585248
08-23 12:38:38.265  6892  7088 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:38:38.265  6892  7088 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:38:38.265  6892  7088 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:38:38.265  6892  7088 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:38:38.265  6892  7088 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 12:38:38.265  6892  7088 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@249bb0ad added. We now have 1 listener(s)
08-23 12:38:38.275  6892  7088 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-23 12:38:38.275  6892  7088 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:38:38.285  6892  7088 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:38:38.285  6892  7088 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 12:38:38.285  6892  7088 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23501e30 added. We now have 1 listener(s)
08-23 12:38:38.285  6892  7088 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:38.295  6892  7088 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:38:38.295  6892  7088 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 12:38:38.295  6892  7088 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 12:38:38.305  6892  7088 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:38:38.305  6892  7088 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 12:38:38.305  1019  6888 I art     : Explicit concurrent mark sweep GC freed 18208(975KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.810ms total 159.430ms
08-23 12:38:38.305  6892  7088 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:38.315  6892  7088 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-23 12:38:38.315  7122  7122 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:38:38.315  7122  7122 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 12:38:38.315  7122  7122 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 12:38:38.325  6892  7088 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:38.325  6892  7088 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:38:38.325  6892  7088 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 12:38:38.325  6892  7088 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:38:38.325  6892  7088 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 12:38:38.325  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:38.335  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:38.345  7107  7107 D BadgeProvider: onCreate
08-23 12:38:38.345  7107  7107 D BadgeProvider: DatabaseHelper
08-23 12:38:38.365  6731  6782 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-23 12:38:38.385  6892  6892 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-23 12:38:38.395  6731  6782 I AcmsKeyStoreHelper: Key Store exist
08-23 12:38:38.395  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-23 12:38:38.395  6731  6782 I AcmsKeyStoreHelper: Hence loading the keystore file
08-23 12:38:38.395  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.395  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.395  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.395  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.425  7145  7145 E Zygote  : MountEmulatedStorage()
08-23 12:38:38.425  7145  7145 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:38.425  7145  7145 E Zygote  : v2
08-23 12:38:38.425  7145  7145 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:38.425  7145  7145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:38.425  7145  7145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:38.425  7145  7145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:38.425  1019  1490 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-23 12:38:38.435  6990  7101 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-23 12:38:38.455  1471  1488 D TP/SmsProvider: query,matched:26, calling pid = 6990
,08-23 12:38:38.455   315   315 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 40.022ms
08-23 12:38:38.455  1471  1488 D TP/SmsProvider: match 26:Elapsed time : 2.047 ms
,08-23 12:38:38.475   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.904ms
,08-23 12:38:38.485  7145  7145 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:38.485  7145  7145 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:38.495   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.486ms
,08-23 12:38:38.505  1901  1901 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 12:38:38.515  1471  1875 D TP/MmsSmsProvider: query,matched:6, calling pid = 6990
,08-23 12:38:38.515  1471  1875 D TP/MmsSmsProvider: match 6:Elapsed time : 1.130 ms
,08-23 12:38:38.525  1884  4392 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-23 12:38:38.525  7145  7145 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-23 12:38:38.525  7145  7145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-23 12:38:38.535  1019  1490 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-23 12:38:38.535  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-23 12:38:38.535  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:38.535  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:38.535  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-23 12:38:38.545  1019  1032 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,08-23 12:38:38.545  7145  7145 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-23 12:38:38.545  6731  6782 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-23 12:38:38.545  6731  6782 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-23 12:38:38.545  6731  6782 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-23 12:38:38.545  6731  6782 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 12:38:38.545  6731  6782 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-23 12:38:38.545  6731  6782 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-23 12:38:38.545  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:38.545  6731  6782 D AcmsCore: This is NOT a valid MirrorLink app
08-23 12:38:38.545  6731  6782 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-23 12:38:38.545  6731  6782 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 12:38:38.545  6731  6782 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-23 12:38:38.545  6731  6782 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-23 12:38:38.545  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.545  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.545  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:38.555  7162  7162 E Zygote  : MountEmulatedStorage()
08-23 12:38:38.555  7162  7162 E Zygote  : v2
08-23 12:38:38.555  7162  7162 I libpersona: KNOX_SDCARD checking this for 10023
08-23 12:38:38.555  7162  7162 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:38.565  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:38.565  7162  7162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:38.565  1019  1032 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7162 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,08-23 12:38:38.565  7162  7162 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:38.565  6731  6731 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-23 12:38:38.565  1019  1567 I ActivityManager: Killing 6635:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-23 12:38:38.565  6731  6731 D AcmsService: Enter onDestroy
08-23 12:38:38.565  6731  6731 I AcmsService: cleanUp(): inside service clean up
08-23 12:38:38.565  6731  6731 D AcmsCore: AcmsCore: inside DeInit
08-23 12:38:38.565  6731  6731 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-23 12:38:38.575  6731  6731 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-23 12:38:38.575  6731  6731 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-23 12:38:38.575  6731  6731 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-23 12:38:38.575  6731  6731 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-23 12:38:38.575  6731  6731 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-23 12:38:38.575  6731  6731 D AcmsService: killing acms process
08-23 12:38:38.575  6731  6731 I Process : Sending signal. PID: 6731 SIG: 9
,08-23 12:38:38.595  7122  7122 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-23 12:38:38.595  7162  7162 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:38.595  7162  7162 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:38.605  1019  1512 I ActivityManager: Killing 6645:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,08-23 12:38:38.605  1019  1081 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-23 12:38:38.605  1019  1081 I ActivityManager: Killing 5087:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-23 12:38:38.605  1019  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-23 12:38:38.605  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 12:38:38.615  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:38.615  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.615  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.615  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:38.625  7177  7177 E Zygote  : MountEmulatedStorage()
08-23 12:38:38.625  7177  7177 I libpersona: KNOX_SDCARD checking this for 10003
08-23 12:38:38.625  7177  7177 E Zygote  : v2
08-23 12:38:38.625  7177  7177 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:38.625  7177  7177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:38.625  7177  7177 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:38.625  7177  7177 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:38.635  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7177 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 12:38:38.635  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-23 12:38:38.635  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.635  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.635  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.635  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:38.655  7186  7186 E Zygote  : MountEmulatedStorage()
08-23 12:38:38.655  7186  7186 E Zygote  : v2
08-23 12:38:38.655  7186  7186 I libpersona: KNOX_SDCARD checking this for 10130
08-23 12:38:38.655  7186  7186 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:38.655  7186  7186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:38.655  1019  1045 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7186 uid=10130 gids={50130, 9997} abi=armeabi-v7a,
08-23 12:38:38.655  7186  7186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:38.665  7186  7186 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-23 12:38:38.675  7177  7177 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:38.675  7177  7177 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:38.675  7162  7162 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,08-23 12:38:38.685  7186  7186 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:38.685  7186  7186 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:38.695  1901  1901 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 12:38:38.715  6990  7101 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-23 12:38:38.715  7145  7160 E FilterInstaller: installFilters
,08-23 12:38:38.715  7145  7160 E FilterInstaller: There is no requred permission
,08-23 12:38:38.715  1901  1901 I SamsungIME: KeybaordView init() : load resources
,08-23 12:38:38.715  6833  7143 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 12:38:38.715  6833  7143 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 12:38:38.725   285   285 E installd: system dir 0 : /system/app/
08-23 12:38:38.725   285   285 E installd: system dir 1 : /system/priv-app/
08-23 12:38:38.725   285   285 E installd: system dir 2 : /vendor/app/
08-23 12:38:38.725   285   285 E installd: system dir 3 : /oem/app/
,08-23 12:38:38.735  7186  7186 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:38:38.735  7186  7186 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-23 12:38:38.745  1884  4392 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-23 12:38:38.745  1019  1452 I ActivityManager: Killing 6681:com.samsung.helphub/1000 (adj 15): empty #21
,08-23 12:38:38.745  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-23 12:38:38.755  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:38.755  1019  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 12:38:38.755  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-23 12:38:38.755  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-23 12:38:38.755  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-23 12:38:38.755  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-23 12:38:38.755  1901  1901 I SamsungIME: getCurrentKeyboard
08-23 12:38:38.755  1901  1901 I SamsungIME: getTextKeyboard
,08-23 12:38:38.755  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:38:38.755  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-23 12:38:38.755  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-23 12:38:38.765  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-23 12:38:38.765  1019  1486 I ActivityManager: Killing 6665:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-23 12:38:38.765  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-23 12:38:38.765  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-23 12:38:38.765  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-23 12:38:38.775  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-23 12:38:38.775  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-23 12:38:38.775  1019  6889 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
08-23 12:38:38.775  7162  7162 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-23 12:38:38.775  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.775  1901  1901 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-23 12:38:38.775  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.775  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.775  1019  6889 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:38.785  1019  1044 E libprocessgroup: failed to kill 1 processes for processgroup 6635
08-23 12:38:38.795  7208  7208 E Zygote  : MountEmulatedStorage()
08-23 12:38:38.795  7208  7208 E Zygote  : v2
08-23 12:38:38.795  7208  7208 I libpersona: KNOX_SDCARD checking this for 10131
08-23 12:38:38.795  7208  7208 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:38.795  7208  7208 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:38.795  1019  6889 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7208 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-23 12:38:38.795  1019  6889 I ActivityManager: Killing 6699:com.sec.spp.push/u0a32 (adj 15): empty #21
08-23 12:38:38.805  7208  7208 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:38.805  7208  7208 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:38:38.815  1019  1059 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 12:38:38.815  1019  1031 I ActivityManager: Process ACMS.Process (pid 6731)(adj 0) has died(26,762)
,08-23 12:38:38.825  7208  7208 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:38.825  7208  7208 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:38.865  6833  7143 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-23 12:38:38.865  7208  7208 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 12:38:38.865  7208  7208 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:38:38.865  7208  7208 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 12:38:38.895  1019  1486 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-23 12:38:38.895  1019  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-23 12:38:38.905  2683  2692 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 12:38:38.905  1019  1486 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:38.905  1019  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:38.905  1019  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-23 12:38:38.925  1019  1486 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-23 12:38:38.925  1019  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-23 12:38:38.925  1019  1486 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:38.925  1019  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:38.925  1019  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-23 12:38:38.935  6833  7143 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 12:38:38.935  6833  7143 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1748526d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 12:38:38.935  6833  7143 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 12:38:38.945  1019  1032 I ActivityManager: Killing 6748:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-23 12:38:39.115  6892  7141 W jxcore-log: Initializing JXcore engine
08-23 12:38:39.115  6892  7141 W jxcore-log: JXcore engine is ready
,08-23 12:38:39.175  2021  2021 E audit   : type=1400 msg=audit(1471948719.175:205): avc:  denied  { ioctl } for  pid=7141 comm="Thread-1300" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 12:38:39.175  2021  2021 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:39.175  2021  2021 E audit   : type=1300 msg=audit(1471948719.175:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f5268f8 items=0 ppid=315 ppcomm=main pid=7141 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1300" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 12:38:39.175  2021  2021 E audit   : type=1320 msg=audit(1471948719.175:205): 
,08-23 12:38:39.185  6892  7141 W jxcore-log: Starting JXcore engine
,08-23 12:38:39.295  6892  7141 W jxcore-log: Platform android
08-23 12:38:39.295  6892  7141 W jxcore-log: 
08-23 12:38:39.295  6892  7141 W jxcore-log: Process ARCH arm
08-23 12:38:39.295  6892  7141 W jxcore-log: 
,08-23 12:38:39.505  6892  7141 I jxcore-log: JXcore Cordova bridge is ready!
08-23 12:38:39.505  6892  7141 I jxcore-log: 
,08-23 12:38:39.505  6892  7141 W jxcore-log: JXcore engine is started
,08-23 12:38:39.505  6892  7088 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 12:38:39.515  6892  6892 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:38:39.995  6990  6990 I Mms/MmsApp:  start initViewCache mms,
08-23 12:38:39.995  6990  6990 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1811.919739
,08-23 12:38:39.995  6990  6990 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-23 12:38:40.095  6990  6990 D AbsListView: Get MotionRecognitionManager
,08-23 12:38:40.095  1019  1081 D MotionRecognitionService:  ssp status : false
,08-23 12:38:40.105  6990  6990 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 110.760573
,08-23 12:38:40.185  6990  6990 D Mms/BubbleViewCache: fillCache bubble = 1
,08-23 12:38:40.325   289   289 E SMD     : DCD OFF
,08-23 12:38:41.475  1687  1687 I ConfigService: onDestroy,
,08-23 12:38:42.145  1019  3384 D SSRM:n  : SIOP:: AP = 400
,08-23 12:38:42.705  1019  3416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 12:38:43.325   289   289 E SMD     : DCD OFF,
,08-23 12:38:45.265  1019  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 12:38:45.265  1019  1032 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4252, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-23 12:38:45.265  1019  1032 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 12:38:45.265  1019  1032 D BatteryService: stay LED for charging
,08-23 12:38:45.265  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 12:38:45.275  1019  1019 I MotionRecognitionService: Plugged
08-23 12:38:45.275  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 12:38:45.275  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 12:38:45.275  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 12:38:45.275  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 12:38:45.285  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-23 12:38:45.285  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 12:38:45.285  3219  3372 D HeadsetStateMachine: Disconnected process message: 10
,08-23 12:38:45.285  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 12:38:45.285  1182  1182 D SViewCoverView: level :99 plugged : 2
,08-23 12:38:45.295  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:38:45.295  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:38:45.295  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:38:46.285  1019  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-23 12:38:46.325   289   289 E SMD     : DCD OFF
,08-23 12:38:47.545  1019  1329 E Watchdog: !@Sync 3
,08-23 12:38:48.335   330   330 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 12:38:48.335   330   330 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 12:38:48.825  1019  1059 D PackageManager: [MSG] MCS_UNBIND
,08-23 12:38:48.835  1019  6889 I ActivityManager: Killing 6714:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-23 12:38:49.335   289   289 E SMD     : DCD OFF,
,08-23 12:38:51.735  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-23 12:38:51.735  6892  7141 I jxcore-log: 
,08-23 12:38:51.735  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-23 12:38:51.735  6892  7141 I jxcore-log: 
,08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:51.745  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:51.745  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:51.755  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 12:38:51.755  6892  7141 I jxcore-log: 
,08-23 12:38:51.755  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 12:38:51.755  6892  7141 I jxcore-log: 
,08-23 12:38:51.965  1019  1052 I PowerManagerService: [PWL] Off : 50s ago
,08-23 12:38:52.185  1019  3384 D SSRM:n  : SIOP:: AP = 360,
,08-23 12:38:52.195  1019  1099 V AlarmManager: waitForAlarm result :4
08-23 12:38:52.195  1019  1099 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-23 12:38:52.335   289   289 E SMD     : DCD OFF
,08-23 12:38:52.415  6930  7036 D Finsky  : [1304] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-23 12:38:52.425  6930  6930 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-23 12:38:52.465  6892  7141 D ExecuteNativeTests: Running unit tests
,08-23 12:38:52.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 12:38:52.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d added. We now have 2 listener(s)
,08-23 12:38:52.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-23 12:38:52.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:38:52.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:38:52.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:52.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 added. We now have 2 listener(s)
08-23 12:38:52.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:52.555  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:38:52.555  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:52.565  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:52.565  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:52.565  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:52.565  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.565  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:38:52.565  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 12:38:52.565  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 12:38:52.565  6892  7141 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-23 12:38:52.565  6892  7141 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 12:38:52.565  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:38:52.565  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:38:52.565  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 12:38:52.565  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.565  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.565  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.565  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.565  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.565  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:52.565  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:38:52.565  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d removed from the list
08-23 12:38:52.565  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.565  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 removed from the list
,08-23 12:38:52.575  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.575  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:38:52.575  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.575  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.575  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.575  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:38:52.575  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.575  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.575  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:52.575  6892  7141 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-23 12:38:52.575  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.575  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.575  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.575  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.575  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.575  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.575  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.575  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.575  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.575  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.575  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.575  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.575  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.575  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.585  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.585  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.585  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.585  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 12:38:52.585  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.585  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.585  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.585  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.585  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.585  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.585  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list,
08-23 12:38:52.585  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.585  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.585  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.585  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.585  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.585  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.585  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.595  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.595  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.595  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-23 12:38:52.595  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.595  6892  7141 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 12:38:52.595  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:52.595  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:52.595  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:52.595  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:52.605  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:38:52.605  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:38:52.605  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:38:52.605  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:52.605  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 12:38:52.605  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:38:52.605  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.605  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.615  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:38:52.615  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:38:52.625  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-23 12:38:52.625  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-23 12:38:52.625  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 12:38:52.625  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 12:38:52.625  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 12:38:52.635  3219  3381 D BtGatt.GattService: registerClient() - UUID=b38311ce-1275-4232-9de5-3efdb5a1e272
,08-23 12:38:52.685  3219  3293 D BtGatt.GattService: onClientRegistered() - UUID=b38311ce-1275-4232-9de5-3efdb5a1e272, clientIf=6
,08-23 12:38:52.685  6892  6907 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 12:38:52.685  3219  3368 D BtGatt.GattService: start scan with filters
,08-23 12:38:52.685  3219  3371 D BtGatt.ScanManager: handling starting scan
,08-23 12:38:52.685  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:38:52.685  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 12:38:52.685  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 12:38:52.685  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:38:52.685  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:38:52.685  3219  3371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:38:52.685  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:38:52.695  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 12:38:52.695  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:38:52.695  3219  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-23 12:38:52.695  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.695  3219  3371 D BtGatt.ScanManager: allow scan with filters
08-23 12:38:52.695  3219  3371 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-23 12:38:52.695  3219  3371 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-23 12:38:52.705  6892  7141 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 12:38:52.705  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 12:38:52.705  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.705  3219  3371 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 12:38:52.705  3219  3371 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 12:38:52.705  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:38:52.705  6892  7141 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 12:38:52.705  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:38:52.705  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 12:38:52.705  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.705  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 12:38:52.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:38:52.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:38:52.705  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:38:52.705  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 12:38:52.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 12:38:52.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:38:52.715  3219  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 12:38:52.715  3219  3229 D BtGatt.GattService: stopScan() - queue size =1
,08-23 12:38:52.715  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.715  3219  3381 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 12:38:52.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:38:52.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:38:52.715  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:38:52.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:38:52.715  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:38:52.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:38:52.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 12:38:52.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:38:52.715  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 12:38:52.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:38:52.715  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 12:38:52.715  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.725  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.725  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.725  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:52.725  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.725  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.725  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.725  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.725  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.725  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:52.725  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:52.725  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:52.725  6892  7141 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 12:38:52.725  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:38:52.725  3219  3371 D BtGatt.ScanManager: filter size is 1
08-23 12:38:52.725  3219  3371 D BtGatt.ScanManager: delete FilterIndex - 3
,08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:52.725  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:52.725  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:52.735  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 12:38:52.735  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:38:52.735  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:38:52.735  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:38:52.735  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:38:52.735  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:38:52.735  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:52.735  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:38:52.735  3219  3371 D BtGatt.ScanManager: stopping BLe Batch
,08-23 12:38:52.735  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.735  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-23 12:38:52.735  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.735  3219  3371 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 12:38:52.735  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:38:52.735  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.735  3219  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 12:38:52.735  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:38:52.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:38:52.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 12:38:52.745  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:38:52.745  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 12:38:52.745  3219  3381 D BtGatt.GattService: registerClient() - UUID=77557f09-110b-437a-894d-43e4161d3190
,08-23 12:38:52.785  3219  3293 D BtGatt.GattService: onClientRegistered() - UUID=77557f09-110b-437a-894d-43e4161d3190, clientIf=6
,08-23 12:38:52.785  6892  6907 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 12:38:52.785  3219  3231 D BtGatt.GattService: start scan with filters
,08-23 12:38:52.795  3219  3371 D BtGatt.ScanManager: handling starting scan
,08-23 12:38:52.795  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:38:52.795  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 12:38:52.795  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 12:38:52.795  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:38:52.795  3219  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-23 12:38:52.795  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.805  3219  3371 D BtGatt.ScanManager: allow scan with filters
,08-23 12:38:52.805  3219  3371 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 12:38:52.805  3219  3371 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-23 12:38:52.805  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:38:52.805  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:38:52.805  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 12:38:52.805  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 12:38:52.805  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.805  3219  3371 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 12:38:52.805  3219  3371 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 12:38:52.815  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-23 12:38:52.815  3219  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 12:38:52.815  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.815  6892  7141 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 12:38:52.825  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:38:52.825  6892  7141 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 12:38:52.825  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:38:52.825  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 12:38:52.825  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 12:38:52.825  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.825  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:52.835  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 12:38:52.835  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 12:38:52.835  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:38:52.835  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-23 12:38:52.835  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 12:38:52.835  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 12:38:52.835  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:38:52.835  3219  3368 D BtGatt.GattService: stopScan() - queue size =1
,08-23 12:38:52.835  3219  3371 D BtGatt.ScanManager: filter size is 1
,08-23 12:38:52.835  3219  3371 D BtGatt.ScanManager: delete FilterIndex - 4
,08-23 12:38:52.835  3219  3381 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:38:52.845  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 12:38:52.845  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:38:52.845  3219  3371 D BtGatt.ScanManager: stopping BLe Batch
,08-23 12:38:52.845  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 12:38:52.845  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 12:38:52.845  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.845  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:52.845  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.845  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.845  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.845  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.845  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:38:52.845  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:52.855  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:52.855  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 12:38:52.855  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:38:52.855  3219  3371 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 12:38:52.855  6892  7141 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 12:38:52.855  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:38:52.865  3219  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 12:38:52.865  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:52.865  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:52.865  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:52.865  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:52.875  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:38:52.875  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:38:52.875  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:38:52.875  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:52.875  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 12:38:52.875  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.875  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:52.875  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:38:52.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:38:52.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:38:52.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 12:38:52.885  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 12:38:52.885  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 12:38:52.885  3219  3231 D BtGatt.GattService: registerClient() - UUID=1480040a-a074-44e4-9684-37e00d887da3
,08-23 12:38:52.935  3219  3293 D BtGatt.GattService: onClientRegistered() - UUID=1480040a-a074-44e4-9684-37e00d887da3, clientIf=6
,08-23 12:38:52.935  6892  6904 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 12:38:52.935  3219  3368 D BtGatt.GattService: start scan with filters
,08-23 12:38:52.935  3219  3371 D BtGatt.ScanManager: handling starting scan
,08-23 12:38:52.935  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:38:52.935  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 12:38:52.935  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 12:38:52.935  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:38:52.935  3219  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-23 12:38:52.935  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:38:52.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 12:38:52.945  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:38:52.945  3219  3371 D BtGatt.ScanManager: allow scan with filters
08-23 12:38:52.945  3219  3371 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 12:38:52.945  3219  3371 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-23 12:38:52.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:38:52.945  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 12:38:52.945  6892  7141 I io.jxcore.node.ConnectionHelper: start: OK
08-23 12:38:52.945  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.945  6892  7141 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 12:38:52.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.945  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 12:38:52.945  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 12:38:52.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:38:52.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:38:52.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:38:52.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:38:52.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:38:52.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:38:52.945  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:38:52.945  3219  3371 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:38:52.945  3219  3371 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 12:38:52.955  3219  3231 D BtGatt.GattService: stopScan() - queue size =1
,08-23 12:38:52.955  3219  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 12:38:52.955  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:38:52.955  3219  3368 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 12:38:52.955  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 12:38:52.955  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:38:52.955  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 12:38:52.955  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:38:52.955  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:38:52.955  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 12:38:52.955  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:38:52.955  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:38:52.965  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 12:38:52.965  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.965  6892  7141 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 12:38:52.965  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.965  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.965  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:52.965  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.965  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.965  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.965  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:52.965  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:52.965  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.965  3219  3371 D BtGatt.ScanManager: filter size is 1
,08-23 12:38:52.965  3219  3371 D BtGatt.ScanManager: delete FilterIndex - 5
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.965  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:52.965  6892  7141 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-23 12:38:52.965  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.965  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.965  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.965  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.965  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.965  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.965  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.965  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.965  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.965  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.965  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.975  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-23 12:38:52.975  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.975  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.975  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.975  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:52.975  6892  7141 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-23 12:38:52.975  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.975  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.975  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.975  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop,
08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.975  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 12:38:52.975  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-23 12:38:52.975  3219  3371 D BtGatt.ScanManager: stopping BLe Batch
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.975  6892  7141 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-23 12:38:52.975  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.975  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.975  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.975  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.975  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:52.975  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.975  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.975  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.985  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-23 12:38:52.985  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:38:52.985  3219  3371 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.985  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:38:52.985  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:38:52.985  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:38:52.985  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 12:38:52.985  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.985  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.985  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.985  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:52.985  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.985  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
,08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.985  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.985  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.985  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.985  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.985  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.985  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.985  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:52.985  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.985  6892  7141 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:52.985  6892  7141 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 12:38:52.985  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-23 12:38:52.995  3219  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 12:38:52.995  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:38:52.995  6892  7141 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:52.995  6892  7141 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-23 12:38:52.995  6892  7141 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 12:38:52.995  6892  7141 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:38:52.995  6892  7141 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 12:38:52.995  6892  7141 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:52.995  6892  7141 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:38:52.995  6892  7141 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 12:38:52.995  6892  7141 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:52.995  6892  7141 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 12:38:52.995  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 12:38:52.995  6892  7141 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 12:38:52.995  6892  7141 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:52.995  6892  7141 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 12:38:52.995  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:52.995  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:52.995  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:52.995  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.995  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.995  6892  7240 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1364)
,08-23 12:38:52.995  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-23 12:38:52.995  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:52.995  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:52.995  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:52.995  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.995  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:52.995  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:52.995  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:52.995  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:52.995  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:53.005  6892  7141 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 12:38:53.005  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 12:38:53.005  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:53.005  6892  7241 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1364
,08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
,08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 12:38:53.005  6892  7141 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:38:53.005  6892  7141 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 12:38:53.005  6892  7141 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:38:53.005  6892  7141 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 12:38:53.005  6892  7141 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:38:53.005  6892  7141 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 12:38:53.005  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.005  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.005  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings,: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.005  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.005  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.005  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.005  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-23 12:38:53.015  6892  7240 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 12:38:53.015  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:38:53.015  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.015  6892  6892 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 12:38:53.015  6892  6892 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 12:38:53.015  6892  7240 D BluetoothSocket: connect(): myUserId = 0
08-23 12:38:53.015  6892  7240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:53.015  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.015  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:53.015  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.015  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:53.015  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:53.015  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.015  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.015  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.015  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.015  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.015  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.015  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.015  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.015  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.015  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.015  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.015  6892  7242 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 12:38:53.015  6892  7242 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 12:38:53.015  3219  3381 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:38:53.025  6892  6892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 12:38:53.025  6892  7141 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 12:38:53.025  6892  7141 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:38:53.025  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:38:53.025  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.025  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.025  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.025  6892  7240 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.025  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.025  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.025  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.025  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.025  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.025  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.025  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.025  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.025  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.025  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.025  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.025  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.025  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.025  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.025  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.025  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.025  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.025  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.025  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.025  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.025  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.025  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.025  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.025  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.035  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:53.035  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:53.035  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:53.035  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:53.035  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.035  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.035  6892  7141 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195823d not in the list
08-23 12:38:53.035  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.035  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:53.035  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.035  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.035  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:53.035  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:53.035  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:53.035  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:53.035  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:53.035  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32853a32 not in the list
08-23 12:38:53.035  6892  7141 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:38:53.035  6892  7141 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:38:53.035  6892  7141 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-23 12:38:53.035  6892  7141 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 12:38:53.035  6892  7141 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 12:38:53.035  6892  7141 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 12:38:53.035  6892  7141 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-23 12:38:53.035  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:53.035  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26d57dc4 added. We now have 2 listener(s)
08-23 12:38:53.035  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:53.035  6892  7141 D BluetoothAdapter: enable()
08-23 12:38:53.045  6892  7141 D BluetoothAdapter: enable(): BT is already enabled..!
08-23 12:38:53.045  1019  1566 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 12:38:53.045  1019  1566 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 12:38:53.045  1019  1566 D SecContentProvider2: mCursor = null
,08-23 12:38:53.045  1019  1566 D WifiService: setWifiEnabled: true pid=6892, uid=10170
08-23 12:38:53.045  1019  1566 W ActivityManager: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-23 12:38:53.045  1019  1566 W WifiService: Failed getting userId using ActivityManagerNative
08-23 12:38:53.045  1019  1566 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-23 12:38:53.045  1019  1566 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 12:38:53.045  1019  1566 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 12:38:53.045  1019  1566 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 12:38:53.045  1019  1566 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 12:38:53.045  1019  1566 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-23 12:38:53.055  1019  1566 D SettingsProvider: name = wifi_on
08-23 12:38:53.055  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:53.055  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed074ad added. We now have 3 listener(s)
08-23 12:38:53.055  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:53.055  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:53.055  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d1c93e2 added. We now have 4 listener(s)
08-23 12:38:53.055  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:53.055  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:53.065  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d060373 added. We now have 5 listener(s)
08-23 12:38:53.065  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:53.065  1019  1486 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 12:38:53.065  1019  1486 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 12:38:53.065  1019  1486 D SecContentProvider2: mCursor = null
08-23 12:38:53.065  1019  1486 D WifiService: setWifiEnabled: false pid=6892, uid=10170
08-23 12:38:53.065  1019  1486 D SettingsProvider: name = wifi_on
08-23 12:38:53.075  1019  1132 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 12:38:53.075  1358  1358 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 12:38:53.075  1358  1358 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-23 12:38:53.075  1358  1358 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 12:38:53.075  1358  1358 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-23 12:38:53.075  6892  7141 D BluetoothAdapter: disable()
08-23 12:38:53.075  1019  1452 D SettingsProvider: name = bluetooth_on
08-23 12:38:53.085  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:38:53.085  3219  3290 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-23 12:38:53.085  3219  3290 D BluetoothAdapterProperties: Setting state to 13
08-23 12:38:53.085  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-23 12:38:53.085  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:38:53.085  3219  3290 D BluetoothAdapterService: updateAdapterState state is 13
,08-23 12:38:53.095  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:38:53.095  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 12:38:53.095  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.095  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.095  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:38:53.095  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-23 12:38:53.095  3219  3290 D BluetoothAdapterService: Autoconnection is available 
08-23 12:38:53.095  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-23 12:38:53.095  3219  3290 D BluetoothAdapterService: terminating service from this receiver
,08-23 12:38:53.095  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-23 12:38:53.095  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@274a28de, channel: 19, state: LISTENING
,08-23 12:38:53.095  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@274a28de, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f103f06, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@cbb3abfmSocket: android.net.LocalSocket@2658658c impl:android.net.LocalSocketImpl@18dc14d5 fd:FileDescriptor[80]
08-23 12:38:53.095  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2658658c impl:android.net.LocalSocketImpl@18dc14d5 fd:FileDescriptor[80]
08-23 12:38:53.095  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.095  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.095  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:38:53.095  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:38:53.095  3219  3290 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 12:38:53.095  3219  3290 D BluetoothAdapterProperties: mDiscovering is false
,08-23 12:38:53.095  1019  1566 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 12:38:53.095  3219  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-23 12:38:53.105  1358  1358 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-23 12:38:53.105  1358  1358 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-23 12:38:53.105  1358  1358 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,08-23 12:38:53.105  1019  1132 E WifiNative-wlan0: do suspend true
,08-23 12:38:53.105  4715  4715 D BluetoothPbap: Proxy object disconnected
,08-23 12:38:53.105  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 12:38:53.105  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
08-23 12:38:53.105  4715  4715 D PbapServerProfile: Bluetooth service disconnected
,08-23 12:38:53.115  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:53.115  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:53.115  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-23 12:38:53.115  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.115  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:53.115  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:53.115  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 12:38:53.115  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:38:53.115  1182  1182 D BluetoothTile:  getBluetoothState : 13
,08-23 12:38:53.115  1901  1901 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 12:38:53.115  1019  1081 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:38:53.125  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:53.125  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:38:53.125  1019  1567 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 12:38:53.125  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:53.125  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 12:38:53.125  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:38:53.135  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:53.135  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:53.135  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.135  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:53.135  3219  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
,08-23 12:38:53.135  3219  3293 D BluetoothAdapterProperties: Scan Mode:20
,08-23 12:38:53.145  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 12:38:53.145  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
08-23 12:38:53.145  3219  3290 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-23 12:38:53.145  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:53.145  3219  3290 E bt-btif : cmd socket is not created
08-23 12:38:53.145  3219  5258 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:38:53.145  6892  7240 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e2caea9, channel: -1, state: INIT
08-23 12:38:53.145  6892  7240 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e2caea9, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35f40c2e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e3363cfmSocket: android.net.LocalSocket@1564c15c impl:android.net.LocalSocketImpl@37f88c65 fd:FileDescriptor[105]
08-23 12:38:53.145  6892  7240 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1564c15c impl:android.net.LocalSocketImpl@37f88c65 fd:FileDescriptor[105]
08-23 12:38:53.145  6892  7240 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1364)
08-23 12:38:53.145  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-23 12:38:53.145  3219  3290 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 12:38:53.145  3219  3294 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-23 12:38:53.145  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@372c3db, channel: 5, state: LISTENING
08-23 12:38:53.145  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@372c3db, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21c2d9c7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5ec4e78mSocket: android.net.LocalSocket@2e562951 impl:android.net.LocalSocketImpl@ec75b6 fd:FileDescriptor[82]
08-23 12:38:53.145  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e562951 impl:android.net.LocalSocketImpl@ec75b6 fd:FileDescriptor[82]
,08-23 12:38:53.145  3219  3219 I BtOppRfcommListener: stopping Accept Thread
08-23 12:38:53.145  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@314fc2b7, channel: 12, state: LISTENING
08-23 12:38:53.145  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@314fc2b7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3cab9019, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1cd3da24mSocket: android.net.LocalSocket@2e83098d impl:android.net.LocalSocketImpl@2ac23742 fd:FileDescriptor[85]
08-23 12:38:53.145  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e83098d impl:android.net.LocalSocketImpl@2ac23742 fd:FileDescriptor[85]
08-23 12:38:53.145  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:53.145  3219  5258 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 12:38:53.155  4715  4715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:38:53.155  1019  1452 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 12:38:53.155  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 12:38:53.155  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.155  1019  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:38:53.155  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:53.155  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 12:38:53.155  3219  3219 V BluetoothOppManager: cleanUp...
,08-23 12:38:53.155  3219  3294 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,08-23 12:38:53.155  3219  3294 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-23 12:38:53.155  3219  3294 W bt-btif : invalid rfc slot id: 4
,08-23 12:38:53.165  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:38:53.165  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-23 12:38:53.165  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:38:53.165  3219  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:38:53.165  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:38:53.165  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:38:53.165  3219  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 12:38:53.165  4715  4715 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:38:53.165  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:38:53.175  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:38:53.175  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-23 12:38:53.175  1019  1508 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 12:38:53.175  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.175  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.175  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.175  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 12:38:53.175  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
08-23 12:38:53.175  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 12:38:53.185  7247  7247 E Zygote  : MountEmulatedStorage()
,08-23 12:38:53.195  7247  7247 E Zygote  : v2
08-23 12:38:53.195  7247  7247 I libpersona: KNOX_SDCARD checking this for 10055
08-23 12:38:53.195  7247  7247 I libpersona: KNOX_SDCARD not a persona,
,08-23 12:38:53.195  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 12:38:53.195  1019  1508 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7247 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 12:38:53.195  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:53.195   279   970 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:38:53.195  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:53.205  1687  2540 V NativeCrypto: Read error: ssl=0xb85c04f0: I/O error during system call, Connection timed out,
,08-23 12:38:53.205  1687  2540 V NativeCrypto: SSL shutdown failed: ssl=0xb85c04f0: I/O error during system call, Broken pipe
08-23 12:38:53.205  1019  1134 E ConnectivityService: updateNetworkInfo()
08-23 12:38:53.205  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:38:53.205  1019  1134 E ConnectivityService: updateNetworkInfo(),
08-23 12:38:53.205  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-23 12:38:53.205  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:53.205  1019  1131 D WifiP2pService: InactiveState{ what=131204 }
08-23 12:38:53.205  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 12:38:53.205  1019  1131 D WifiP2pService: P2pEnabledState{ what=131204 }
08-23 12:38:53.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.205  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-23 12:38:53.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.205  1019  1512 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-23 12:38:53.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.205  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:38:53.205  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 12:38:53.205  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-23 12:38:53.205  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:38:53.205  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-23 12:38:53.205  1019  1132 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 12:38:53.205  1019  1745 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 12:38:53.215  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 12:38:53.215  1019  1745 I qtaguid : Tagging socket 326 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,08-23 12:38:53.225  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 12:38:53.225  1019  1155 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:38:53.225  1019  1019 D RttService: SCAN_AVAILABLE : 1
,08-23 12:38:53.225  1019  1156 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler },
08-23 12:38:53.225  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-23 12:38:53.225  1019  1745 I qtaguid : Untagging socket 326
08-23 12:38:53.225  1019  1131 D WifiP2pService: P2pDisablingState
08-23 12:38:53.225  1019  1745 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 12:38:53.225  1019  1131 D WifiP2pService: P2pDisablingState{ what=147458 }
08-23 12:38:53.235  1019  1132 E WifiNative-wlan0: do suspend true
08-23 12:38:53.225  1019  1131 D WifiP2pService: p2p socket connection lost
,08-23 12:38:53.235  1019  1131 D WifiP2pService: P2pDisabledState
,08-23 12:38:53.235  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:38:53.235  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 12:38:53.235  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 12:38:53.235  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-23 12:38:53.235  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:53.235  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:38:53.235  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:53.235  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:53.235  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.235  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:53.235  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 12:38:53.235  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-23 12:38:53.235  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-23 12:38:53.235  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 12:38:53.235  1019  1050 D WifiDisplayController: disconnect
08-23 12:38:53.235  1019  1050 D WifiDisplayController: updateConnection
08-23 12:38:53.235  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 12:38:53.235  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:38:53.245  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:53.245  7247  7247 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:53.255  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 12:38:53.265  1019  1131 D WifiP2pService: P2pDisabledState{ what=143375 }
08-23 12:38:53.265  1019  1131 D WifiP2pService: DefaultState{ what=143375 }
,08-23 12:38:53.275  7247  7247 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
,08-23 12:38:53.285  1019  6888 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-23 12:38:53.285  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 12:38:53.285  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-23 12:38:53.285  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:53.285  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 12:38:53.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-23 12:38:53.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:53.305   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-23 12:38:53.305   279   966 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-23 12:38:53.305  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.305  1019  1134 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-23 12:38:53.305  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:38:53.305  1019  1134 V NetworkStats: updateIfacesLocked(),
08-23 12:38:53.305  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:38:53.305  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
,08-23 12:38:53.305   279   970 D CommandListener: Clearing all IP addresses on wlan0
,08-23 12:38:53.305  7247  7247 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-23 12:38:53.305  1019  1134 V NetworkStats: performPollLocked() took 6ms
08-23 12:38:53.305  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.305  7247  7247 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-23 12:38:53.315  1019  1134 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502],
08-23 12:38:53.305  7247  7247 D UserAnalysis: Create SecureDbHelper
,08-23 12:38:53.315  1019  1134 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:38:53.315  1358  1358 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-23 12:38:53.315  1182  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-23 12:38:53.315  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-23 12:38:53.315  1019  1134 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-23 12:38:53.315  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-23 12:38:53.315  1019  1134 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-23 12:38:53.315  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 12:38:53.315  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 12:38:53.315  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:38:53.315  1471  1471 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 12:38:53.315  1019  1131 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 12:38:53.315  1471  1471 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:38:53.315  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-23 12:38:53.325  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.325  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:53.325  1019  1132 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 12:38:53.325  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 12:38:53.325  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:38:53.325  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:53.325  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:53.325  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:38:53.325  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.325  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.325  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.325  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:53.325  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:53.335  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:53.335  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:53.335  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 12:38:53.335  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.335  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.335  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.335  7247  7247 D IntelligenceServiceApplication: onCreate()
08-23 12:38:53.335  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:53.335  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:38:53.335  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:53.335  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-23 12:38:53.335  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 12:38:53.335   330   330 I ServiceManager: Waiting for service AtCmdFwd...
08-23 12:38:53.335  1182  1182 D HotspotTile: onReceive : 0, 0
08-23 12:38:53.335  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-23 12:38:53.335  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:38:53.335  1019  1135 D Tethering: MasterInitialState.processMessage what=3
08-23 12:38:53.335  1019  1134 D ConnectivityService: nai.networkMonitor.doQuit()
08-23 12:38:53.335  1019  1134 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-23 12:38:53.335  1019  1134 E ConnectivityService: updateNetworkInfo()
08-23 12:38:53.335  1019  1134 E ConnectivityService: updateNetworkInfo()
,08-23 12:38:53.345  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.345  1019  1129 V NetworkStats: updateIfacesLocked()
,08-23 12:38:53.345  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:38:53.345  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:38:53.345  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:38:53.345  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:38:53.345  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-23 12:38:53.345  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.345  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:38:53.345  7247  7247 D IntelligenceServiceApplication: no applications having user consent for prediction
08-23 12:38:53.345  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-23 12:38:53.345  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 12:38:53.345  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 12:38:53.345  1182  1182 D StatusBar.NetworkController: updateDataNetType()
08-23 12:38:53.345  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.345  1019  1490 I ActivityManager: Killing 6157:com.samsung.android.sm/1000 (adj 15): empty #21
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:53.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:38:53.345  1019  1130 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-23 12:38:53.345  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.345  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.345  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.345  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.345  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal,.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.345  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:38:53.345  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 12:38:53.345  3219  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-23 12:38:53.345  3219  3290 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-23 12:38:53.345  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-23 12:38:53.345  3219  3290 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-23 12:38:53.345  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 12:38:53.345  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 12:38:53.355  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:38:53.355  1019  1129 V NetworkStats: performPollLocked() took 10ms
08-23 12:38:53.355  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-23 12:38:53.355  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 12:38:53.355  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-23 12:38:53.355  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-23 12:38:53.355  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-23 12:38:53.355  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.355  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:53.355  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.355  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:53.365  7268  7268 E Zygote  : MountEmulatedStorage()
08-23 12:38:53.365  7268  7268 E Zygote  : v2
08-23 12:38:53.365  7268  7268 I libpersona: KNOX_SDCARD checking this for 10105
08-23 12:38:53.365  7268  7268 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:53.365  1019  1032 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7268 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-23 12:38:53.365  7268  7268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:53.365  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-23 12:38:53.365  1019  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:38:53.365  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 12:38:53.375  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.375  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.375  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:38:53.375  7247  7247 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-23 12:38:53.375  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 12:38:53.375  7268  7268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:53.375  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-23 12:38:53.375  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-23 12:38:53.375  3219  3219 D HeadsetService: Received stop request...Stopping profile...
08-23 12:38:53.375  1019  1559 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:38:53.375  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 12:38:53.375  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.375  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.375  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:38:53.375  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-23 12:38:53.375  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:38:53.375  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:38:53.375  7268  7268 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-23 12:38:53.375  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-23 12:38:53.375  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-23 12:38:53.375  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.375  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.375  4715  4715 D HeadsetProfile: Bluetooth service disconnected
08-23 12:38:53.375  3219  3219 D A2dpService: Received stop request...Stopping profile...
,08-23 12:38:53.385  3219  3374 D A2dpStateMachine: Exit Disconnected: -1
,08-23 12:38:53.385  1019  1567 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:38:53.385  1019  1567 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 12:38:53.385  1019  1567 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.385  1019  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.385  1019  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:38:53.385  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-23 12:38:53.385  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-23 12:38:53.385  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-23 12:38:53.385  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:38:53.385  1019  1269 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:38:53.385  1019  1269 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-23 12:38:53.385  1019  1269 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.385  1019  1269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.385  1019  1269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:38:53.385  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-23 12:38:53.385  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-23 12:38:53.385  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 12:38:53.395  7247  7247 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-23 12:38:53.395  1019  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:38:53.395  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 12:38:53.395  1019  1019 D BluetoothA2dp: Proxy object disconnected
08-23 12:38:53.395  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 12:38:53.395  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.395  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.395  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:38:53.395  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 12:38:53.395  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 12:38:53.395  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 12:38:53.395  4715  4715 D BluetoothA2dp: Proxy object disconnected
08-23 12:38:53.395  4715  4715 D A2dpProfile: Bluetooth service disconnected
08-23 12:38:53.395  1019  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:38:53.395  1019  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 12:38:53.405  1019  1486 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.405  1019  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:38:53.405  1019  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-23 12:38:53.405  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 12:38:53.405  1019  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:38:53.405  1019  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 12:38:53.405  1019  1512 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.405  1019  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.405  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:38:53.405  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:38:53.405  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 12:38:53.405  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 12:38:53.405  7268  7268 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-23 12:38:53.405  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 12:38:53.405  7268  7268 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:53.405  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 12:38:53.405  3219  3290 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 12:38:53.405  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-23 12:38:53.405  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:38:53.405  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 12:38:53.415  1358  1358 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 12:38:53.415  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 12:38:53.415  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-23 12:38:53.415  3219  3219 D HidService: Received stop request...Stopping profile...
08-23 12:38:53.415  3219  3219 D HidService: Stopping Bluetooth HidService
08-23 12:38:53.415  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 12:38:53.415  3219  3219 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-23 12:38:53.415  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 12:38:53.415  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:38:53.425  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-23 12:38:53.425  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:38:53.425  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 12:38:53.425  3219  3219 D HealthService: Received stop request...Stopping profile...
08-23 12:38:53.425  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:38:53.425  4715  4715 D BluetoothInputDevice: Proxy object disconnected
08-23 12:38:53.425  4715  4715 D HidProfile: Bluetooth service disconnected
,08-23 12:38:53.435  3219  3219 D BluetoothA2dp: Proxy object disconnected
08-23 12:38:53.435  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-23 12:38:53.435  3219  3375 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 12:38:53.435  3219  3219 I GKI_LINUX: GKI_exit_task 2 done
08-23 12:38:53.435  3219  3219 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-23 12:38:53.435  3219  3219 D PanService: Received stop request...Stopping profile...
08-23 12:38:53.435  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:38:53.435  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 12:38:53.435  4715  4715 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 12:38:53.435  4715  4715 D PanProfile: Bluetooth service disconnected
,08-23 12:38:53.435  3219  3219 D BluetoothMapService: Received stop request...Stopping profile...
,08-23 12:38:53.435  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:38:53.445  4715  4715 D BluetoothMap: Proxy object disconnected
,08-23 12:38:53.445  4715  4715 D MapProfile: Bluetooth service disconnected
08-23 12:38:53.445  3219  3219 D SapService: Received stop request...Stopping profile...
08-23 12:38:53.445  3219  3219 D SapService: Stopping Bluetooth SapService
08-23 12:38:53.445  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:38:53.445  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-23 12:38:53.445  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:38:53.445  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:38:53.445  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-23 12:38:53.445  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-23 12:38:53.445  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:38:53.445  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:38:53.445  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 12:38:53.445  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 12:38:53.445  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 12:38:53.445  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-23 12:38:53.445  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:38:53.445  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:38:53.445  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 12:38:53.445  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 12:38:53.445  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 12:38:53.445  4715  4715 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-23 12:38:53.445  4715  4715 D SapProfile: Bluetooth service disconnected
,08-23 12:38:53.455  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-23 12:38:53.455  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:38:53.455  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 12:38:53.455  3219  3219 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-23 12:38:53.455  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-23 12:38:53.455  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:38:53.455  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-23 12:38:53.455  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-23 12:38:53.455  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-23 12:38:53.455  3219  3290 D BluetoothAdapterProperties: Setting state to 10
08-23 12:38:53.455  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 12:38:53.455  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:38:53.455  3219  3290 D BluetoothAdapterService: updateAdapterState state is 10
,08-23 12:38:53.455  1687  2189 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.455  1687  2189 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 12:38:53.455  3219  3290 D BluetoothAdapterService: Autoconnection is available 
08-23 12:38:53.455  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-23 12:38:53.455  3219  3290 I BluetoothAdapterState: Entering OffState
08-23 12:38:53.455  4715  4723 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.455  4715  4723 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.455  4715  4729 D BluetoothPbap: onBluetoothStateChange: up=false
,08-23 12:38:53.465  6892  6907 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.465  6892  6907 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 12:38:53.465  6892  6907 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-23 12:38:53.465  6892  6907 D BluetoothLeAdvertiser: Exit stop advertising
08-23 12:38:53.465  6892  6907 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-23 12:38:53.465  6892  6907 D BluetoothLeScanner: Exiting stopAllScan
,08-23 12:38:53.465  3219  3368 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 12:38:53.465  1457  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.465  1457  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.465  4715  4729 D Bluetoothsap: onBluetoothStateChange: up=false
,08-23 12:38:53.465  4715  4729 D Bluetoothsap: Unbinding service...
,08-23 12:38:53.475  4715  4723 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-23 12:38:53.475  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.475  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.475  1182  1198 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.475  1182  1198 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.475  1718  3976 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:38:53.475  1718  3976 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.485  1358  1358 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 12:38:53.485  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:38:53.485  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:38:53.485  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 12:38:53.485  1440  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:38:53.485  1440  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.485  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.495  1471  1969 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.495  1471  1969 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.495  4715  4729 D BluetoothMap: onBluetoothStateChange: up=false
08-23 12:38:53.495  3219  3229 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:38:53.495  3219  3229 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:38:53.495  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.495  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:38:53.495  4715  4729 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:38:53.495  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 12:38:53.495  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 12:38:53.495  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
08-23 12:38:53.495  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-23 12:38:53.495  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.495  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.505  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 12:38:53.505  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:38:53.505  1182  1182 D BluetoothTile:  getBluetoothState : 10
,08-23 12:38:53.505  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.505  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.505  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.505  1358  1358 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-23 12:38:53.505  1358  1358 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-23 12:38:53.505  1358  1358 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-23 12:38:53.505  1358  1358 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-23 12:38:53.505  1358  1358 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-23 12:38:53.505  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:53.505  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:38:53.505  1019  1135 D Tethering: InitialState.processMessage what=4
08-23 12:38:53.505  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:38:53.515  1019  1453 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 12:38:53.515  1901  1901 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 12:38:53.515  1019  1032 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 12:38:53.515  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-23 12:38:53.515  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:53.515  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:38:53.515  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 12:38:53.515  1019  1135 E Tethering: No numeric data
,08-23 12:38:53.515  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:38:53.515  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 12:38:53.515  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:53.515  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:38:53.515  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 12:38:53.515  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 12:38:53.515  6892  6892 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-23 12:38:53.515  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:38:53.515  1019  1135 D Tethering: clearTetheredNotification()
08-23 12:38:53.515  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.515  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-23 12:38:53.515  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:38:53.515  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:38:53.525  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:38:53.525  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.525  1019  1129 V NetworkStats: performPollLocked() took 3ms
08-23 12:38:53.525  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 12:38:53.525  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:38:53.525  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 12:38:53.525  1182  1182 D HotspotTile: updateTetherState():false, false
,08-23 12:38:53.525  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:53.525  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:53.525  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:53.525  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.525  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 12:38:53.525  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:53.525  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 12:38:53.525  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.535  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-23 12:38:53.535  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 12:38:53.535  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 12:38:53.535  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.535  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 12:38:53.535  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 12:38:53.535  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.535  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.535  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.535  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.545  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 12:38:53.545  1471  1471 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 12:38:53.545  1471  1471 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 12:38:53.565   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 12:38:53.565   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:38:53.565  7268  7305 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 12:38:53.565   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 12:38:53.565   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:38:53.565  7268  7305 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 12:38:53.655  1358  1358 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.k.d(PG:583)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:38:53.715  1019  1566 I ActivityManager: Killing 6791:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
08-23 12:38:53.705  7268  7268 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:38:53.705  7268  7268 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:38:53.715  1019  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:38:53.715  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.715  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 12:38:53.715  1019  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:53.715  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 12:38:53.715  1628  1628 I Hs20UtilService: Starting #8
08-23 12:38:53.715  1628  1655 I Hs20UtilService: Message received 5007
08-23 12:38:53.715  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 12:38:53.725  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 12:38:53.725  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 12:38:53.725  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:38:53.725  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 12:38:53.725  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:38:53.725  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-23 12:38:53.725  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-23 12:38:53.735  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 12:38:53.735  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 12:38:53.735  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:38:53.735  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 12:38:53.735  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:38:53.735  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-23 12:38:53.735  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-23 12:38:53.735  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.735  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.735  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.735  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.745  7315  7315 E Zygote  : MountEmulatedStorage()
08-23 12:38:53.755  7315  7315 E Zygote  : v2
08-23 12:38:53.755  7315  7315 I libpersona: KNOX_SDCARD checking this for 10064
08-23 12:38:53.755  7315  7315 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:53.755  7315  7315 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:53.755  7315  7315 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:53.755  7315  7315 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:38:53.755  1019  1032 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7315 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 12:38:53.765  7268  7303 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-23 12:38:53.775  1358  1358 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-23 12:38:53.775  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:53.775  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:38:53.775  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:38:53.785  7315  7315 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 12:38:53.785  7315  7315 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:53.805  1019  1566 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 12:38:53.805  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:53.805  1019  1566 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:53.805  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-23 12:38:53.805  7315  7315 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 12:38:53.825  7315  7315 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:53.825  7315  7315 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 12:38:53.835  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:53.845  1019  1019 I ApplicationPolicy: updateDataUsageMap
,08-23 12:38:53.855  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:53.855  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:53.855  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:53.865  7315  7315 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 12:38:53.865  1019  1453 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-23 12:38:53.865  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.865  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.865  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.865  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.875  7332  7332 E Zygote  : MountEmulatedStorage(),
08-23 12:38:53.875  7332  7332 E Zygote  : v2
08-23 12:38:53.875  7332  7332 I libpersona: KNOX_SDCARD checking this for 10065
,08-23 12:38:53.875  7332  7332 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:53.885  7332  7332 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:53.885  7332  7332 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:53.885  7332  7332 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-23 12:38:53.885  1019  1453 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7332 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:38:53.885  1019  1453 I ActivityManager: Killing 6833:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-23 12:38:53.895  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-23 12:38:53.905  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 12:38:53.905  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:53.905  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:38:53.915  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 12:38:53.915  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.915  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.915  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.915  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:53.915  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:38:53.915  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-23 12:38:53.915  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:53.915  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 12:38:53.915  1182  1182 D HotspotTile: onReceive : 1, 0
,08-23 12:38:53.915  1718  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:38:53.915  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:53.915  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:53.925  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:53.925  7332  7332 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:53.925  7332  7332 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:53.945  7332  7332 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:53.945  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:53.945  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:53.945  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-23 12:38:53.945  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-23 12:38:53.945  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.945  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.945  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:53.945  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:53.965  7347  7347 E Zygote  : MountEmulatedStorage()
08-23 12:38:53.965  7347  7347 I libpersona: KNOX_SDCARD checking this for 10102
08-23 12:38:53.965  7347  7347 E Zygote  : v2
08-23 12:38:53.965  7347  7347 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:53.965  1019  1490 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7347 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-23 12:38:53.965  7347  7347 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:53.965  1019  1490 I ActivityManager: Killing 6810:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-23 12:38:53.965  7347  7347 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:53.965  7347  7347 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 12:38:53.975  7347  7347 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:53.985  7347  7347 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:53.995  7347  7347 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 12:38:54.195  7347  7367 I Babel_SMS: MmsConfig: mnc/mcc: 0/0,
08-23 12:38:54.195  7347  7367 I Babel_SMS: MmsConfig.loadMmsSettings
08-23 12:38:54.195  7347  7367 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-23 12:38:54.195  7347  7367 I Babel_SMS: MmsConfig.loadFromDatabase
,08-23 12:38:54.205  7347  7367 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-23 12:38:54.205  7347  7367 I Babel_SMS: MmsConfig.loadFromResources
,08-23 12:38:54.215  7347  7367 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-23 12:38:54.215  7347  7367 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-23 12:38:54.235  1019  1512 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-23 12:38:54.235  1019  1512 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-23 12:38:54.235  1019  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:54.235  1019  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:54.235  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 12:38:54.255  7347  7347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:38:54.255  7347  7347 I Babel_Crash: startup - clean
,08-23 12:38:54.285  1019  1566 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:38:54.285  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:38:54.285  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.285  1019  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.285  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:54.295  1628  1628 I Hs20UtilService: Starting #9
,08-23 12:38:54.295  1628  1655 I Hs20UtilService: Message received 5007
,08-23 12:38:54.295  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 12:38:54.295  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 12:38:54.295  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:38:54.295  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 12:38:54.295  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 12:38:54.295  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:38:54.295  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:38:54.305  1019  1559 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:38:54.305  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:38:54.305  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.305  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.305  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:54.305  1628  1628 I Hs20UtilService: Starting #10
,08-23 12:38:54.305  1019  6888 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-23 12:38:54.305  7347  7347 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:54.305  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:38:54.305  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.305  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.305  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.305  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.315  7347  7347 W AudioCapabilities: Unsupported mime audio/evrc
,08-23 12:38:54.315  7347  7347 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 12:38:54.315  7347  7347 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-23 12:38:54.315  7347  7347 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-23 12:38:54.325  7347  7347 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-23 12:38:54.325  7347  7347 W AudioCapabilities: Unsupported mime audio/x-ima,
,08-23 12:38:54.325  7347  7347 W AudioCapabilities: Unsupported mime audio/qcelp
,08-23 12:38:54.325  1019  6888 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 12:38:54.335  7370  7370 E Zygote  : MountEmulatedStorage()
08-23 12:38:54.335  7370  7370 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:54.335  7370  7370 E Zygote  : v2
08-23 12:38:54.335  7370  7370 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:54.335  7347  7347 W AudioCapabilities: Unsupported mime audio/evrc
08-23 12:38:54.335  7370  7370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:54.335  7370  7370 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:38:54.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 12:38:54.345  7370  7370 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:54.345  7347  7347 W VideoCapabilities: Unsupported mime video/wvc1
,08-23 12:38:54.345  7347  7347 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-23 12:38:54.355  7347  7347 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-23 12:38:54.365  7347  7347 W VideoCapabilities: Unsupported mime video/wvc1
08-23 12:38:54.365  7370  7370 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:54.375  7370  7370 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:54.375  7347  7347 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-23 12:38:54.375  7347  7347 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-23 12:38:54.375  7347  7347 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-23 12:38:54.375  7347  7347 W VideoCapabilities: Unsupported mime video/mp43
,08-23 12:38:54.385  7347  7347 W VideoCapabilities: Unsupported mime video/sorenson
,08-23 12:38:54.385  7347  7347 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-23 12:38:54.405  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 12:38:54.405  7347  7347 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-23 12:38:54.405  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-23 12:38:54.405  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 12:38:54.415  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:38:54.415  1019  1269 I ActivityManager: Killing 6864:com.sec.pcw.device/1000 (adj 15): empty #21
,08-23 12:38:54.425  1019  1047 D Tethering: interfaceRemoved wlan0
08-23 12:38:54.425  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-23 12:38:54.425  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.425  1019  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.425  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.425  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.425  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.425  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.425  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.425  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.425  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.435  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:54.435  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.435  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.435  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.435  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.435  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.445  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:54.445  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.445  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.445  7347  7347 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:54.445  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:54.445  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.445  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.445  7347  7347 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:54.445  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:54.445  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.445  7347  7347 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 12:38:54.445  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.455  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:54.455  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.455  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.455  7347  7347 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:54.455  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.455  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.455  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.455  1019  1031 I ActivityManager: Killing 6762:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-23 12:38:54.455  7347  7347 I vclib   : onServiceConnected
,08-23 12:38:54.465  1019  1019 W ActivityManager: userId = 0, bbcId = -10000,
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.465  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.465  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.465  1019  1019 W ActivityManager: userId = 0, bbcId = -10000,
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.465  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.475  1019  1019 W ActivityManager: userId = 0, bbcId = -10000,
08-23 12:38:54.475  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.475  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 12:38:54.475  4715  4715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:38:54.475  1019  1508 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 12:38:54.475  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 12:38:54.475  1019  1508 W ActivityManager: userId = 0, bbcId = -10000,
,08-23 12:38:54.475  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:54.475  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-23 12:38:54.485  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:38:54.485  4715  4715 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:38:54.485  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:38:54.485  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:38:54.495  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-23 12:38:54.505  1019  1508 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 12:38:54.505  1019  1508 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.pcw.device/com.sec.pcw.device.receiver.SYSTEMReceiver}
08-23 12:38:54.505  1019  1508 W BroadcastQueue: android.os.TransactionTooLargeException
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-23 12:38:54.505  1019  1508 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 12:38:54.505  1019  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 12:38:54.505  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.505  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.505  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.505  1019  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.515  7388  7388 E Zygote  : MountEmulatedStorage(),
08-23 12:38:54.515  7388  7388 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:54.515  7388  7388 E Zygote  : v2
08-23 12:38:54.515  7388  7388 I libpersona: KNOX_SDCARD not a persona,
08-23 12:38:54.525  7388  7388 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:54.525  1019  1508 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 12:38:54.525  7388  7388 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:38:54.525  7388  7388 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:54.545  7388  7388 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:54.545  7388  7388 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:54.545   315   315 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 23.810ms
,08-23 12:38:54.565   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.649ms
,08-23 12:38:54.565  7388  7388 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-23 12:38:54.565  7388  7388 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-23 12:38:54.565  7388  7388 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-23 12:38:54.575   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.294ms
,08-23 12:38:54.585  7388  7388 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-23 12:38:54.585  7388  7388 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-23 12:38:54.585  7388  7388 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-23 12:38:54.585  7388  7388 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:54.585  1019  1453 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-23 12:38:54.585  1019  1453 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,08-23 12:38:54.585  7388  7404 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-23 12:38:54.585  1019  1453 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-23 12:38:54.585  1019  1453 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-23 12:38:54.585  1019  1453 I ActivityManager: Killing 6951:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-23 12:38:54.595  1019  1047 D Tethering: interfaceRemoved p2p0
,08-23 12:38:54.595  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-23 12:38:54.595  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-23 12:38:54.605  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.605  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.605  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.605  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.615  7406  7406 E Zygote  : MountEmulatedStorage(),
08-23 12:38:54.615  7406  7406 I libpersona: KNOX_SDCARD checking this for 10001
,08-23 12:38:54.615  7406  7406 E Zygote  : v2
08-23 12:38:54.615  7406  7406 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:54.615  7406  7406 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:54.615  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7406 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:38:54.615  7406  7406 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:54.615  7406  7406 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 12:38:54.635  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_6864/cgroup.procs: No such file or directory
,08-23 12:38:54.635  7406  7406 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:54.635  7406  7406 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:54.705  1019  1567 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-23 12:38:54.705  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.705  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.705  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.705  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-23 12:38:54.725  7423  7423 E Zygote  : MountEmulatedStorage()
08-23 12:38:54.725  1019  1567 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7423 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 12:38:54.725  7423  7423 E Zygote  : v2
08-23 12:38:54.725  7423  7423 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:38:54.725  7423  7423 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:54.725  7423  7423 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:54.725  1019  1567 I ActivityManager: Killing 6971:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-23 12:38:54.725  7423  7423 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:54.735  7423  7423 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:54.755  7423  7423 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:54.755  7423  7423 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:54.795  7423  7423 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-23 12:38:54.935  7423  7423 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-23 12:38:54.945  7423  7423 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-23 12:38:54.955  7423  7423 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:54.955  7423  7423 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-23 12:38:54.955  7423  7423 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-23 12:38:54.955  7423  7423 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-23 12:38:54.955  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-23 12:38:54.955  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.965  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.965  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:54.965  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:54.975  1019  1032 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7438 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-23 12:38:54.985  7438  7438 E Zygote  : MountEmulatedStorage()
08-23 12:38:54.985  7438  7438 E Zygote  : v2
08-23 12:38:54.985  7438  7438 I libpersona: KNOX_SDCARD checking this for 10008
08-23 12:38:54.985  7438  7438 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:54.985  1019  1032 I ActivityManager: Killing 7012:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
08-23 12:38:54.985  7438  7438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:54.985  7438  7438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 12:38:54.995  7438  7438 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-23 12:38:55.005  7438  7438 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:55.015  7438  7438 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:55.085  1019  1081 I ActivityManager: Killing 7051:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-23 12:38:55.085  1019  6889 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-23 12:38:55.085  1019  6889 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 12:38:55.085  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:55.085  1019  6889 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 12:38:55.085  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 12:38:55.105  1884  1884 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-23 12:38:55.115  1884  2828 I iu.UploadsManager: num queued entries: 0
,08-23 12:38:55.115  1884  2828 I iu.UploadsManager: num updated entries: 0
08-23 12:38:55.115  1019  1453 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 12:38:55.115  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
08-23 12:38:55.115  1884  2828 I iu.SyncManager: NEXT; no task
,08-23 12:38:55.115  1019  1453 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:55.115  1019  1453 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 12:38:55.115  1019  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:38:55.125  1884  1884 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 12:38:55.125  1884  1884 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-23 12:38:55.125  2832  2832 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 12:38:55 GMT+02:00 2016
,08-23 12:38:55.125  1019  6888 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 12:38:55.125  1019  6888 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 12:38:55.125  1019  6888 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:55.125  1019  6888 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:38:55.135  1019  6888 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 12:38:55.135  2832  2832 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 12:38:55.145  1019  1453 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-23 12:38:55.145  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.145  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.145  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 12:38:55.145  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 12:38:55.145  2832  2832 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 12:38:55.155  2832  2832 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 12:38:55.155  2832  2832 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 12:38:55.155  2832  7454 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 12:38:55.155  2832  7454 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-23 12:38:55.165  7455  7455 E Zygote  : MountEmulatedStorage()
08-23 12:38:55.165  7455  7455 E Zygote  : v2
08-23 12:38:55.165  7455  7455 I libpersona: KNOX_SDCARD checking this for 10031
08-23 12:38:55.165  7455  7455 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:55.165  7455  7455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:38:55.165  1019  1453 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7455 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-23 12:38:55.165  2832  7454 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-23 12:38:55.165  7455  7455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:55.165  2832  7454 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-23 12:38:55.165  7455  7455 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:55.175  2832  2832 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 12:38:55.195  7455  7455 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:55.195  7455  7455 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:55.225  7455  7455 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-23 12:38:55.225  1019  1490 I ActivityManager: Killing 6990:com.android.mms/u0a41 (adj 15): empty #21
,08-23 12:38:55.245  1019  1453 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-23 12:38:55.245  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.245  2769  7470 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-23 12:38:55.245  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.245  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.245  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.245  2769  7470 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
,08-23 12:38:55.255  2769  7470 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-23 12:38:55.255  2769  7470 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-23 12:38:55.255  2769  7470 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-23 12:38:55.265  7471  7471 E Zygote  : MountEmulatedStorage()
08-23 12:38:55.265  7471  7471 E Zygote  : v2
08-23 12:38:55.265  7471  7471 I libpersona: KNOX_SDCARD checking this for 10032
08-23 12:38:55.265  7471  7471 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:55.265  7471  7471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:38:55.275  1019  1453 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7471 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:38:55.275  7471  7471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:55.275  7471  7471 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 12:38:55.305  7471  7471 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:55.305  7471  7471 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:55.325  1019  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 12:38:55.325  1019  1490 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4226, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-23 12:38:55.325  1019  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 12:38:55.325  1019  1490 D BatteryService: stay LED for charging
08-23 12:38:55.325  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 12:38:55.325  1019  1019 I MotionRecognitionService: Plugged
,08-23 12:38:55.325  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 12:38:55.335  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 12:38:55.335  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 12:38:55.335   289   289 E SMD     : DCD OFF,
,08-23 12:38:55.335  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 12:38:55.335  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-23 12:38:55.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 12:38:55.365  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-23 12:38:55.365  1182  1182 D SViewCoverView: level :99 plugged : 2
,08-23 12:38:55.365  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:38:55.365  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
08-23 12:38:55.365  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:38:55.375  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-23 12:38:55.375  7471  7486 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-23 12:38:55.375  7471  7486 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-23 12:38:55.385  7471  7486 D SPPClientService: PushLog.txt file is not deleted.
08-23 12:38:55.385  7471  7486 D SPPClientService: PushLog.txt file is not deleted.
08-23 12:38:55.385  7471  7486 D SPPClientService: ============PushLog. stop!
,08-23 12:38:55.385  7471  7471 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-23 12:38:55.385  1019  1031 D CountryDetector: No listener is left
,08-23 12:38:55.385  1019  6888 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-23 12:38:55.385  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.385  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.385  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.385  1019  6888 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.405  7488  7488 E Zygote  : MountEmulatedStorage()
,08-23 12:38:55.405  7488  7488 I libpersona: KNOX_SDCARD checking this for 10036
08-23 12:38:55.405  7488  7488 E Zygote  : v2
08-23 12:38:55.405  7488  7488 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:55.405  7488  7488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:55.405  7488  7488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:38:55.405  1019  6888 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7488 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 12:38:55.405  7488  7488 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 12:38:55.405  1019  6888 I ActivityManager: Killing 7107:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-23 12:38:55.405  1019  1566 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-23 12:38:55.405  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-23 12:38:55.415  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:55.415  1019  1566 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-23 12:38:55.415  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-23 12:38:55.435  7488  7488 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:55.435  7488  7488 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:55.455  7471  7497 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-23 12:38:55.475  7488  7488 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@28c4e07
,08-23 12:38:55.485  7488  7488 I SA      : [SSP] onCreated
,08-23 12:38:55.495  7488  7488 I SA      : [TPM] There is no property file
,08-23 12:38:55.495  7488  7488 I SA      : [SCU] isHaveSA() - false
,08-23 12:38:55.495  7488  7488 I SA      : [TPM] getModelProperty : null
,08-23 12:38:55.495  7488  7488 I SA      : [TPM] getCSCProperty : null
,08-23 12:38:55.505  7488  7488 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-23 12:38:55.505  7488  7488 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-23 12:38:55.505  7488  7488 I SA      : [DM] TFT FEATURE: false
,08-23 12:38:55.505  7488  7488 I SA      : [DM] init START
,08-23 12:38:55.505  7488  7488 I SA      : [DM] This device is not a Vodafone
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-23 12:38:55.515  7488  7488 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-23 12:38:55.525  7488  7488 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-23 12:38:55.525  7488  7488 I SA      : [SCU] isHaveSA() - false,
08-23 12:38:55.525  7488  7488 I SA      : support phone number id : false
08-23 12:38:55.525  7488  7488 I SA      : [DM] Supports Ref Jpn : true
08-23 12:38:55.525  7488  7488 I SA      : [DM] init END
08-23 12:38:55.525  7488  7488 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-23 12:38:55.535  7488  7488 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
08-23 12:38:55.535  7488  7488 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-23 12:38:55.535  7488  7488 I SA      : [SLFUCHKMGR] constructor called
,08-23 12:38:55.545  7488  7488 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-23 12:38:55.545  7488  7488 I SA      : [OR] == isSIMCardReady false ==
,08-23 12:38:55.545  7488  7488 I SA      : [SCU] == networkStateCheck == false
08-23 12:38:55.545  7488  7488 I SA      : [OR] onReceive END
,08-23 12:38:55.545  1019  1269 I ActivityManager: Killing 7122:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-23 12:38:55.555  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:55.555  1817  1817 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 12:38:55.565  2683  2692 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2,
,08-23 12:38:55.565  1817  1817 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-23 12:38:55.565  1817  1817 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-23 12:38:55.565  1817  1817 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-23 12:38:55.565  1817  1817 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-23 12:38:55.575  1817  1817 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 12:38:55.575  1817  1817 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-23 12:38:55.575  1019  1512 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-23 12:38:55.575  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.575  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.575  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.575  1019  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.595  7510  7510 E Zygote  : MountEmulatedStorage(),
08-23 12:38:55.595  7510  7510 E Zygote  : v2
08-23 12:38:55.595  7510  7510 I libpersona: KNOX_SDCARD checking this for 10077
08-23 12:38:55.595  7510  7510 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:55.595  7510  7510 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:55.595  1019  1512 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7510 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-23 12:38:55.595  7510  7510 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:38:55.605  7510  7510 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-23 12:38:55.615  7510  7510 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:55.615  7510  7510 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:55.795  1019  1452 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-23 12:38:55.805  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-23 12:38:55.805  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:55.805  1019  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:55.805  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 12:38:55.805  1019  1453 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-23 12:38:55.805  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.805  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.805  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:55.805  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:55.825  7529  7529 E Zygote  : MountEmulatedStorage(),
08-23 12:38:55.825  7529  7529 E Zygote  : v2
08-23 12:38:55.825  7529  7529 I libpersona: KNOX_SDCARD checking this for 10110,
08-23 12:38:55.825  7529  7529 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:55.825  7529  7529 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:38:55.825  1019  1453 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7529 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:38:55.825  1019  1559 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-23 12:38:55.825  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-23 12:38:55.825  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:55.825  1019  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:55.825  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-23 12:38:55.825  7529  7529 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:55.835  7347  7528 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-23 12:38:55.835  7529  7529 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 12:38:55.835  1019  1490 I ActivityManager: Killing 7145:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-23 12:38:55.855  7529  7529 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:55.855  7529  7529 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:55.995  1019  1269 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 12:38:56.105   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-23 12:38:56.105   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:38:56.105  7529  7548 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-23 12:38:56.115   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-23 12:38:56.115   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:38:56.115  7529  7548 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-23 12:38:56.115  1019  6889 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 12:38:56.115  1019  6889 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-23 12:38:56.115  1019  6889 D SecContentProvider2: mCursor = null
,08-23 12:38:56.115  1019  6889 D WifiService: setWifiEnabled: true pid=6892, uid=10170
,08-23 12:38:56.115  1019  6889 W ActivityManager: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-23 12:38:56.115  1019  6889 W WifiService: Failed getting userId using ActivityManagerNative
08-23 12:38:56.115  1019  6889 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-23 12:38:56.115  1019  6889 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 12:38:56.115  1019  6889 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 12:38:56.115  1019  6889 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 12:38:56.115  1019  6889 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 12:38:56.115  1019  6889 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 12:38:56.125  1019  6889 D SettingsProvider: name = wifi_on
,08-23 12:38:56.125   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-23 12:38:56.125   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:38:56.125  7529  7529 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 12:38:56.125  7529  7529 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 12:38:56.125  7529  7529 I GAv4    :   adb logcat -s GAv4
,08-23 12:38:56.125  7529  7549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-23 12:38:56.125   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-23 12:38:56.125   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:38:56.135  7529  7549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-23 12:38:56.135  1019  1132 E WifiHW  : ##################### set firmware type 0 #####################
,08-23 12:38:56.155  7529  7529 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:38:56.155  1019  1486 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 12:38:56.185  7529  7529 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:38:56.195  7529  7552 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:38:56.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 12:38:56.435  1019  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 12:38:56.435  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:56.435  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:38:56.435  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-23 12:38:56.455  7529  7529 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-23 12:38:56.505  7529  7529 I cr.library_loader: Time to load native libraries: 30 ms (timestamps 7164-7194)
,08-23 12:38:56.505  7529  7529 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-23 12:38:56.515  1019  1047 D Tethering: interfaceAdded wlan0
,08-23 12:38:56.515  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:56.525  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:38:56.525  1019  1135 E Tethering: No numeric data
,08-23 12:38:56.525  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:38:56.525  7529  7529 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {274a28de}
,08-23 12:38:56.525  7529  7529 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 12:38:56.525  7529  7529 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0,
08-23 12:38:56.525  1019  1047 D Tethering: interfaceAdded p2p0,
08-23 12:38:56.525  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-23 12:38:56.525  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 12:38:56.525  1019  1135 D Tethering: clearTetheredNotification()
08-23 12:38:56.525  1019  1135 D Tethering: InitialState.processMessage what=4
08-23 12:38:56.535  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:38:56.535  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:38:56.535   279   970 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
,08-23 12:38:56.535  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:38:56.535   279   970 D SoftapController: Softap fwReload - Ok
08-23 12:38:56.535  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 12:38:56.535  1019  1135 E Tethering: No numeric data
08-23 12:38:56.535  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:38:56.535  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:56.535  1182  1182 D HotspotTile: updateTetherState():false, false
,08-23 12:38:56.545  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:38:56.545  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:38:56.545   279   970 D CommandListener: Setting iface cfg
,08-23 12:38:56.545   279   970 D CommandListener: Trying to bring down wlan0
08-23 12:38:56.545  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 12:38:56.545  1019  1135 D Tethering: clearTetheredNotification()
08-23 12:38:56.545   279   970 D CommandListener: Clearing all IP addresses on wlan0
,08-23 12:38:56.545  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:56.545  1019  1129 V NetworkStats: performPollLocked() took 7ms
,08-23 12:38:56.545  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:38:56.545  1182  1182 D HotspotTile: updateTetherState():false, false
,08-23 12:38:56.545  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:56.545  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:56.545  1019  1132 E WifiHW  : supplicant_name : p2p_supplicant
,08-23 12:38:56.545  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:56.545  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:38:56.545  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-23 12:38:56.555  1019  1132 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-23 12:38:56.555  1019  1132 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-23 12:38:56.555  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:38:56.555  7529  7529 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-23 12:38:56.555  1019  1129 V NetworkStats: performPollLocked() took 7ms
08-23 12:38:56.555  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:56.555  7529  7529 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:38:56.565  7529  7529 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 12:38:56.565  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:56.575  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-23 12:38:56.575  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:38:56.575  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:56.575  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 12:38:56.575  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 12:38:56.575  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:56.575  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:56.575  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:56.575  1182  1182 D HotspotTile: onReceive : 2, 0
08-23 12:38:56.575  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:56.575  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:38:56.575  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-23 12:38:56.575  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:56.575  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:56.575  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:56.575  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:56.585  7529  7529 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-23 12:38:56.585  7529  7529 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 12:38:56.585  7529  7529 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 12:38:56.585  7529  7529 I Adreno-EGL: Local Branch: 
08-23 12:38:56.585  7529  7529 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 12:38:56.585  7529  7529 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 12:38:56.585  7529  7529 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 12:38:56.615  7577  7577 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-23 12:38:56.615  7577  7577 I wpa_supplicant: Successfully initialized wpa_supplicant
08-23 12:38:56.615  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-23 12:38:56.635  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-23 12:38:56.635   385   385 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7577,
08-23 12:38:56.635   385   385 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-23 12:38:56.635  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-23 12:38:56.635  7577  7577 I wpa_supplicant: ssSupport state is = 1
08-23 12:38:56.635  7577  7577 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-23 12:38:56.635  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-23 12:38:56.635   385   385 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7577
08-23 12:38:56.635   385   385 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-23 12:38:56.645  7529  7590 W cr.media: Requires BLUETOOTH permission
,08-23 12:38:56.665  7529  7529 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 12:38:56.685  7529  7529 I NSApplication: Starting up...
,08-23 12:38:56.685  1019  1453 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 12:38:56.685  1019  1032 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 12:38:56.695  1019  1452 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-23 12:38:56.695  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 12:38:56.695  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:56.695  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:56.695  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:56.705  7595  7595 E Zygote  : MountEmulatedStorage(),
,08-23 12:38:56.715  7595  7595 E Zygote  : v2
,08-23 12:38:56.715  7595  7595 I libpersona: KNOX_SDCARD checking this for 10117
08-23 12:38:56.715  7595  7595 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:56.715  1019  1452 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7595 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-23 12:38:56.715  1019  1452 I ActivityManager: Killing 7162:com.wsomacp/u0a23 (adj 15): empty #21,
08-23 12:38:56.715  7595  7595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:56.725  7595  7595 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:56.725  7595  7595 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 12:38:56.735  7595  7595 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:56.735  7595  7595 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:56.755  7595  7595 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 12:38:56.825   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-23 12:38:56.835  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-23 12:38:56.875  7577  7577 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 12:38:56.875  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-23 12:38:56.885  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-23 12:38:56.895   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7577
08-23 12:38:56.895   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-23 12:38:56.895  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 12:38:56.895  7577  7577 I wpa_supplicant: ssSupport state is = 1
08-23 12:38:56.895  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-23 12:38:56.895  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-23 12:38:56.895  7577  7577 E wpa_supplicant: SIM READ ERROR
08-23 12:38:56.895  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-23 12:38:56.895  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 12:38:56.895  7577  7577 E wpa_supplicant: SIM READ ERROR
,08-23 12:38:56.895  7577  7577 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 12:38:56.895  7577  7577 I wpa_supplicant: wpa_default_ap_write_once,
08-23 12:38:56.895  7577  7577 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-23 12:38:56.895  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 12:38:56.895  7577  7577 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-23 12:38:56.895  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 12:38:56.895  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-23 12:38:56.905  7577  7577 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-23 12:38:56.905  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 12:38:56.905  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:38:56.905  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:38:57.055  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-23 12:38:57.125  1019  1453 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-23 12:38:57.125  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.125  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.125  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.125  1019  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.135  7617  7617 E Zygote  : MountEmulatedStorage(),
08-23 12:38:57.135  7617  7617 I libpersona: KNOX_SDCARD checking this for 10121
08-23 12:38:57.135  7617  7617 E Zygote  : v2,
08-23 12:38:57.135  7617  7617 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:57.135  7617  7617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:38:57.145  1019  1453 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7617 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-23 12:38:57.145  1019  1453 I ActivityManager: Killing 7186:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-23 12:38:57.145  7617  7617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:57.145  7617  7617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:57.165  7617  7617 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:57.165  7617  7617 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:57.185  7617  7617 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 12:38:57.185  7617  7617 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 12:38:57.185  7617  7617 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 12:38:57.195  7617  7617 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:57.215  7617  7617 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-23 12:38:57.215  7617  7617 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-23 12:38:57.215  1019  1081 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-23 12:38:57.215  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.215  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.215  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.215  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.235  7577  7577 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-23 12:38:57.235  1019  1081 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7634 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-23 12:38:57.235  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
08-23 12:38:57.235  1019  1081 I ActivityManager: Killing 7208:com.android.calendar/u0a131 (adj 15): empty #21
,08-23 12:38:57.245  7634  7634 E Zygote  : MountEmulatedStorage()
08-23 12:38:57.245  7634  7634 I libpersona: KNOX_SDCARD checking this for 10141
08-23 12:38:57.245  7634  7634 E Zygote  : v2,
08-23 12:38:57.245  7634  7634 I libpersona: KNOX_SDCARD not a persona
08-23 12:38:57.245  7634  7634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:57.245  7634  7634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:38:57.245  7634  7634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:38:57.255   315   315 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 645us total 21.261ms,
,08-23 12:38:57.265  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-23 12:38:57.265   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7577
08-23 12:38:57.265   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 12:38:57.265  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 12:38:57.265  7577  7577 I wpa_supplicant: ssSupport state is = 1
,08-23 12:38:57.265  7577  7577 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-23 12:38:57.265  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-23 12:38:57.275  7634  7634 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 12:38:57.275  7634  7634 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:57.275   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 18.315ms
,08-23 12:38:57.285  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-23 12:38:57.285   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7577
08-23 12:38:57.285   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 12:38:57.285  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 12:38:57.285  7577  7577 I wpa_supplicant: ssSupport state is = 1
08-23 12:38:57.285  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 12:38:57.285  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 12:38:57.285  7577  7577 E wpa_supplicant: SIM READ ERROR
08-23 12:38:57.285  7577  7577 I wpa_supplicant: wpa_default_ap_write_once
08-23 12:38:57.285  7577  7577 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 12:38:57.285  7577  7577 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 12:38:57.285  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-23 12:38:57.285  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
08-23 12:38:57.285  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 12:38:57.295  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:38:57.295  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 12:38:57.295  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:38:57.295   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.759ms
,08-23 12:38:57.295  7634  7634 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-23 12:38:57.295  7634  7634 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:38:57.295  7634  7634 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:38:57.295  7634  7634 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
,08-23 12:38:57.325  7577  7577 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-23 12:38:57.325  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-23 12:38:57.335  1019  1486 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:38:57.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 12:38:57.355  1019  1269 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:38:57.375  1019  1453 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:38:57.385  1019  1081 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:38:57.435  5892  5892 D FactoryTest: Not factory mode
,08-23 12:38:57.435  5892  5892 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-23 12:38:57.435  7577  7577 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-23 12:38:57.435  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-23 12:38:57.435  7577  7577 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 12:38:57.445  5892  5892 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-23 12:38:57.445  5892  5892 D MTPRx   : still no open session command from host, so toast
,08-23 12:38:57.445  5892  5892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-23 12:38:57.445  5892  5892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-23 12:38:57.445  5892  5892 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118135
,08-23 12:38:57.445  1019  1512 E PersonaManagerService: inState():  stateMachine is null !!
,08-23 12:38:57.445  1019  1512 I PersonaManagerService: PersonaId don't exist
,08-23 12:38:57.445  1019  1512 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-23 12:38:57.455  1019  1512 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 12:38:57.455  1019  1512 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:57.455  1019  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:57.455  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-23 12:38:57.465  1019  1512 W ActivityManager: mDVFSHelper.acquire()
,08-23 12:38:57.465  1019  1269 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:38:57.475  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:38:57.475  1019  1512 D PersonaManager: isKioskContainerExistOnDevice
,08-23 12:38:57.485  1019  1512 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 12:38:57.485  1019  1512 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 12:38:57.485  1019  1512 D InputDispatcher: Focused application set to: xxxx
08-23 12:38:57.485  1019  1512 D InputDispatcher: Focus left window: 6892
,08-23 12:38:57.485  5892  5892 E MTPRx   : started activity for popup
08-23 12:38:57.485  1019  1567 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-23 12:38:57.495  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 12:38:57.495  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 12:38:57.495  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.495  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.495  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.495  1019  1567 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.515  7660  7660 E Zygote  : MountEmulatedStorage()
,08-23 12:38:57.515  7660  7660 E Zygote  : v2,
08-23 12:38:57.515  7660  7660 I libpersona: KNOX_SDCARD checking this for 10068,
,08-23 12:38:57.515  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:38:57.515  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 12:38:57.515  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
08-23 12:38:57.515  1019  1567 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7660 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-23 12:38:57.515  7660  7660 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:57.515  7660  7660 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:57.515  7660  7660 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:57.515  7660  7660 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-23 12:38:57.535  5892  5892 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-23 12:38:57.535  5892  5892 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-23 12:38:57.535  5892  5892 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 12:38:57.535  5892  5892 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:38:57.535  5892  5892 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:38:57.535  5892  5892 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 12:38:57.545  7660  7660 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:57.545  7660  7660 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:57.555  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-23 12:38:57.565  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-23 12:38:57.565  7577  7577 I wpa_supplicant: HOTSPOT20_ENABLE called
08-23 12:38:57.565  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 12:38:57.565  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 12:38:57.565  7577  7577 E wpa_supplicant: SIM READ ERROR
08-23 12:38:57.565  7577  7577 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 12:38:57.565  1019  1559 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:38:57.565  1019  1452 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-23 12:38:57.565  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.565  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.565  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.565  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.575  7660  7660 D BadgeProvider: onCreate
08-23 12:38:57.575  5892  5892 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
08-23 12:38:57.575  7660  7660 D BadgeProvider: DatabaseHelper
,08-23 12:38:57.585  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-23 12:38:57.595  7577  7577 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-23 12:38:57.595  7677  7677 E Zygote  : MountEmulatedStorage()
08-23 12:38:57.595  1019  1452 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7677 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-23 12:38:57.595  7677  7677 E Zygote  : v2
08-23 12:38:57.595  1019  1452 I ActivityManager: Killing 6930:com.android.vending/u0a26 (adj 15): empty #21
08-23 12:38:57.595  7677  7677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:38:57.595  1019  1452 I ActivityManager: Killing 7177:com.android.defcontainer/u0a3 (adj 15): empty #22
08-23 12:38:57.595  7677  7677 I libpersona: KNOX_SDCARD checking this for 10009
08-23 12:38:57.595  7677  7677 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:57.605  1019  1132 D WifiConfigStore: Loading config and enabling all networks 
,08-23 12:38:57.605  7677  7677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:57.615  7677  7677 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 12:38:57.615  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:38:57.615  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:38:57.615  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:38:57.615  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:57.615  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:57.615  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:57.615  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:57.615  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:38:57.615  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:38:57.615  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-23 12:38:57.625  1182  1182 D HotspotTile: onReceive : 3, 0
,08-23 12:38:57.635  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:57.635  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 12:38:57.645  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 12:38:57.655  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 12:38:57.655  1019  1132 E WifiConfigStore: Not a HS20
,08-23 12:38:57.655  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:57.655  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:57.655  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:57.655  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:38:57.655  1019  1031 D InputDispatcher: Focused application set to: xxxx
,08-23 12:38:57.655  1019  1031 D InputDispatcher: Focus entered window: 6892
,08-23 12:38:57.665  7677  7677 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:38:57.665  7677  7677 D ActivityThread: Added TimaKeyStore provider
08-23 12:38:57.665  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:57.665  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:57.665  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:57.665  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:38:57.665  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 12:38:57.665  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 12:38:57.665  1019  1081 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 12:38:57.675  1019  1081 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1e243727 attribute=null, token = android.os.BinderProxy@391d6f42
,08-23 12:38:57.675  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-23 12:38:57.675  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-23 12:38:57.685  7577  7577 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-23 12:38:57.685  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-23 12:38:57.685  7577  7577 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 12:38:57.685  7577  7577 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 12:38:57.685  7577  7577 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-23 12:38:57.685  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-23 12:38:57.685  7577  7577 I wpa_supplicant: First Scan Start
,08-23 12:38:57.685  7577  7577 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 12:38:57.685  1019  1132 D WifiNative-wlan0: Setting external_sim to 1
,08-23 12:38:57.685  1019  1132 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 12:38:57.685  1019  1132 I WifiNative-HAL: startHal
,08-23 12:38:57.685  1019  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9f3f588c
08-23 12:38:57.685  7347  7347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:38:57.685  1019  1132 I WifiNative-HAL: Could not start hal
,08-23 12:38:57.695  1019  1132 E WifiNative-wlan0: do suspend true
,08-23 12:38:57.695  1019  1131 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-23 12:38:57.695   279   970 D CommandListener: Setting iface cfg
08-23 12:38:57.695   279   970 D CommandListener: Trying to bring up p2p0
,08-23 12:38:57.695  1019  1131 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 12:38:57.705  1019  1131 D WifiP2pService: P2pEnablingState
,08-23 12:38:57.705  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-23 12:38:57.705  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,08-23 12:38:57.705  1019  1155 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 12:38:57.705  1019  1155 I WifiNative-HAL: startHal
,08-23 12:38:57.705  1019  1155 E wifi    : getStaticLongField sWifiHalHandle 0x9e3b59bc
08-23 12:38:57.705  1019  1155 I WifiNative-HAL: Could not start hal
,08-23 12:38:57.705  1019  1155 E WifiScanningService: could not start HAL
,08-23 12:38:57.705  1019  1019 D RttService: SCAN_AVAILABLE : 3
,08-23 12:38:57.705  1019  1156 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 12:38:57.705  1019  1131 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-23 12:38:57.705  1019  1131 D WifiP2pService: P2p socket connection successful
,08-23 12:38:57.715  1019  1131 D WifiP2pService: P2pEnabledState,
08-23 12:38:57.715  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-23 12:38:57.715  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-23 12:38:57.715  1019  1132 E WifiNative-wlan0: invaild command id : 215
,08-23 12:38:57.715  7577  7577 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-23 12:38:57.715  7577  7577 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 12:38:57.715  7577  7577 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-23 12:38:57.715  1019  1132 E WifiStateMachine: Failed to set frequency band 0
08-23 12:38:57.715  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:38:57.725  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:38:57.725  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-23 12:38:57.725  1019  1134 E ConnectivityService: updateNetworkInfo()
,08-23 12:38:57.725  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 12:38:57.725  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-23 12:38:57.725  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 12:38:57.725  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:38:57.725  1019  1132 D SecContentProvider2: mCursor = null
08-23 12:38:57.725  1019  1050 D WifiDisplayController: disconnect
08-23 12:38:57.725  1019  1050 D WifiDisplayController: updateConnection
08-23 12:38:57.725  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-23 12:38:57.725  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:38:57.725  5892  5892 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-23 12:38:57.735  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress
,08-23 12:38:57.735  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-23 12:38:57.735  5892  5892 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-23 12:38:57.735  5892  5892 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-23 12:38:57.745  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 12:38:57.745  1019  1131 D WifiP2pService: DeviceAddress: 0a:75:42
,08-23 12:38:57.745  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-23 12:38:57.745  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 12:38:57.745  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 12:38:57.745  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 12:38:57.745  1019  1486 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:38:57.745  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 12:38:57.755  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  secondary type: null
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  wps: 0
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  grpcapab: 0
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  devcapab: 0
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  status: 3
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  wfdInfo: null
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  groupownerAddress: null
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  GOdeviceName: null
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  interfaceAddress: 
08-23 12:38:57.755  1019  1050 D WifiDisplayController:  SConnectInfo : null
,08-23 12:38:57.765  6892  6892 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 12:38:57.765  6892  6892 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-23 12:38:57.765  6892  6892 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 12:38:57.765  6892  6892 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-23 12:38:57.775  1019  1131 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-23 12:38:57.775  1019  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 12:38:57.775  1019  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 12:38:57.775  1019  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 12:38:57.775  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 12:38:57.775  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 12:38:57.775  1019  1131 D WifiP2pService: InactiveState
,08-23 12:38:57.775  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,08-23 12:38:57.785  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 12:38:57.785  7577  7577 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 12:38:57.785  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
08-23 12:38:57.785  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 12:38:57.795  6892  6892 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 12:38:57.795  6892  6892 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 12:38:57.795  6892  6892 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fa940fc Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ab8bd3a, 16908290=android.view.AbsSavedState$1@ab8bd3a}, android:focusedViewId=100}]}]
08-23 12:38:57.795  6892  6892 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 12:38:57.795  6892  6892 V ActivityThread: updateVisibility : ActivityRecord{56b137e token=android.os.BinderProxy@37757500 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 12:38:57.795  6892  6892 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 12:38:57.795  6892  6892 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 12:38:57.795  6892  6892 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37757500 time:118488
,08-23 12:38:57.805  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-23 12:38:57.805  1019  1453 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-23 12:38:57.805  1019  6888 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-23 12:38:57.815  1019  1567 I art     : Explicit concurrent mark sweep GC freed 70729(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 4.505ms total 212.888ms
,08-23 12:38:57.815  1019  1031 D PersonaManager: isKioskContainerExistOnDevice
,08-23 12:38:57.825  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-23 12:38:57.825  7660  7668 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-23 12:38:57.845  7660  7668 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-23 12:38:57.845  7660  7668 D BadgeProvider: sendNotify, [notify] : null
08-23 12:38:57.845  7660  7668 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-23 12:38:57.845  7660  7668 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-23 12:38:57.845  7660  7668 D BadgeProvider: update, [UpdateCount] : 1
,08-23 12:38:57.845  1495  1495 D Launcher.Model: reloadBadges entered.
,08-23 12:38:57.845  1019  6889 I ActivityManager: Killing 7315:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-23 12:38:57.855  1019  1453 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:38:57.855  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:38:57.855  1019  1453 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:57.855  1019  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:38:57.855  1019  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:57.855  1628  1628 I Hs20UtilService: Starting #11
,08-23 12:38:57.855  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:38:57.865  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 12:38:57.865  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 12:38:57.865  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
08-23 12:38:57.865  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:38:57.875  1019  6889 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:38:57.875  1019  6889 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:38:57.875  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:57.875  1019  6889 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:57.875  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:57.875  1628  1628 I Hs20UtilService: Starting #12
,08-23 12:38:57.875  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:38:57.885  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 12:38:57.885  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 12:38:57.885  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
08-23 12:38:57.885  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:38:57.885  1019  1081 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:38:57.895  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:38:57.895  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:57.895  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:57.895  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:57.895  1628  1628 I Hs20UtilService: Starting #13
,08-23 12:38:57.895  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:38:57.895  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 12:38:57.895  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 12:38:57.895  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
08-23 12:38:57.895  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:38:57.895  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-23 12:38:57.895  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 12:38:57.895  1019  1132 E WifiNative-wlan0: invaild command id : 215
,08-23 12:38:57.905  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 12:38:57.905  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 12:38:57.905  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:38:57.905  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:38:57.905  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 12:38:57.905  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 12:38:57.905  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:38:57.915  1019  1566 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 12:38:57.915  1019  1566 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
08-23 12:38:57.915  1019  1566 W BroadcastQueue: android.os.TransactionTooLargeException
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-23 12:38:57.915  1019  1566 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 12:38:57.925  1019  1566 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-23 12:38:57.925  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.925  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:38:57.925  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.925  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:38:57.935  7697  7697 E Zygote  : MountEmulatedStorage(),
08-23 12:38:57.945  7697  7697 E Zygote  : v2
08-23 12:38:57.945  7697  7697 I libpersona: KNOX_SDCARD checking this for 10064
08-23 12:38:57.945  7697  7697 I libpersona: KNOX_SDCARD not a persona
,08-23 12:38:57.945  7697  7697 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:38:57.945  1019  1566 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7697 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:38:57.945  7697  7697 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:38:57.945  7697  7697 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 12:38:57.955  1019  1044 W libprocessgroup: failed to open /acct/uid_10064/pid_7315/cgroup.procs: No such file or directory
,08-23 12:38:57.965  7697  7697 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:38:57.965  7697  7697 D ActivityThread: Added TimaKeyStore provider
,08-23 12:38:57.975  7697  7697 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 12:38:57.985  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:57.985  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 12:38:58.005  7697  7697 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 12:38:58.015  7332  7332 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:58.015  1019  1269 I ActivityManager: Killing 7247:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-23 12:38:58.345   289   289 E SMD     : DCD OFF,
,08-23 12:38:58.345   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-23 12:38:58.905  7577  7577 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
08-23 12:38:58.905  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-23 12:38:58.905  7577  7577 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-23 12:38:58.905  7577  7577 I wpa_supplicant: Trying to associate with  'G700'
08-23 12:38:58.905  7577  7577 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-23 12:38:58.905  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-23 12:38:58.905  1019  7675 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-23 12:38:58.915  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 12:38:58.915  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:38:59.005  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 12:38:59.005  7577  7577 E wpa_supplicant: Cmd 35605 not handled
08-23 12:38:59.005  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:38:59.005  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:38:59.005  7577  7577 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-23 12:38:59.005  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-23 12:38:59.005  7577  7577 I wpa_supplicant: Associated with F4.99.3E
08-23 12:38:59.005  7577  7577 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-23 12:38:59.015  7577  7577 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-23 12:38:59.015  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:59.015  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:38:59.015  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:38:59.015  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-23 12:38:59.015  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
,08-23 12:38:59.015  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
,08-23 12:38:59.015  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-23 12:38:59.015  1019  1135 E Tethering: No numeric data,
,08-23 12:38:59.015  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 12:38:59.015  1019  1135 D Tethering: clearTetheredNotification()
,08-23 12:38:59.015  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:38:59.015  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:59.015  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:38:59.015  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:38:59.015  1182  1182 D HotspotTile: updateTetherState():false, false
,08-23 12:38:59.015  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:38:59.015  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:59.015  1019  1129 V NetworkStats: performPollLocked() took 3ms,
,08-23 12:38:59.025  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:59.025  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:59.025  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 12:38:59.025  1019  1132 D SecContentProvider2: mCursor = null
08-23 12:38:59.025  7577  7577 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-23 12:38:59.025  7577  7577 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-23 12:38:59.025  7577  7577 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-23 12:38:59.025  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-23 12:38:59.025  7577  7577 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 12:38:59.025  7577  7577 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
08-23 12:38:59.025  7577  7577 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-23 12:38:59.025  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 12:38:59.025  7577  7577 I wpa_supplicant: Blacklist: Clear (temp) 
,08-23 12:38:59.025  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-23 12:38:59.025  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 12:38:59.025  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-23 12:38:59.025  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:38:59.025  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:38:59.035  1019  1132 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-23 12:38:59.035  1019  1132 E WifiConfigStore: setLastSelectedConfiguration -1
,08-23 12:38:59.035  1019  1132 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-23 12:38:59.035  1019  1134 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-23 12:38:59.035  1019  1134 E ConnectivityService: updateNetworkInfo()
,08-23 12:38:59.035  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 12:38:59.045  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:59.045  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:59.045  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:38:59.045  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.045  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.045  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.045  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.045  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:38:59.045  1019  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:38:59.045  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:59.045  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 12:38:59.045  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:59.045  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:59.045  1628  1628 I Hs20UtilService: Starting #14
,08-23 12:38:59.055  1628  1655 I Hs20UtilService: Message received 5007
,08-23 12:38:59.055  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 12:38:59.055  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 12:38:59.055  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:38:59.055  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 12:38:59.055  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 12:38:59.055  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:38:59.055  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:38:59.065  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:38:59.075   279   970 D CommandListener: Setting iface cfg,
,08-23 12:38:59.075  1019  1132 E WifiStateMachine: Start Dhcp Watchdog 2
,08-23 12:38:59.075  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-23 12:38:59.075  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:38:59.085  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:59.085  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:38:59.085  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 12:38:59.085  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.085  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.095  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.095  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.095  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 12:38:59.095  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:38:59.095  1019  1132 E WifiNative-wlan0: do suspend false
,08-23 12:38:59.105  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,08-23 12:38:59.105  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 12:38:59.145  1019  1486 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-23 12:38:59.145  1019  1486 D WifiService: setWifiEnabled: false pid=6892, uid=10170
08-23 12:38:59.145  1019  1486 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 12:38:59.145  1019  1486 D SecContentProvider2: mCursor = null
08-23 12:38:59.145  1019  1486 D SettingsProvider: name = wifi_on
,08-23 12:38:59.145  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:38:59.155  1019  1132 E WifiNative-wlan0: do suspend true
,08-23 12:38:59.185  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,08-23 12:38:59.185  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 12:38:59.185  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:59.185  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:38:59.185  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:38:59.185  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.185  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.185  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.185  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.185   279   970 D CommandListener: Clearing all IP addresses on wlan0
,08-23 12:38:59.185  1019  1134 E ConnectivityService: updateNetworkInfo(),
08-23 12:38:59.185  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 12:38:59.185  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 12:38:59.185  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
08-23 12:38:59.185   279   970 E Netd    : no such netId 503
08-23 12:38:59.195  1019  1134 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
,08-23 12:38:59.195  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:59.195  1019  1134 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-23 12:38:59.195  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:38:59.195  1019  1134 V NetworkStats: updateIfacesLocked()
08-23 12:38:59.195  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:38:59.195  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
,08-23 12:38:59.195  1019  6889 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:38:59.195  1019  6889 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:38:59.195  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:59.195  1019  6889 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:59.195  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:59.195  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:59.205  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:59.205  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:38:59.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.205  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.205  1628  1628 I Hs20UtilService: Starting #15
08-23 12:38:59.205  1628  1655 I Hs20UtilService: Message received 5007
,08-23 12:38:59.205  1019  1134 V NetworkStats: performPollLocked() took 9ms
08-23 12:38:59.205  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:59.205  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 12:38:59.205  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 12:38:59.205  1019  1134 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-23 12:38:59.205  1019  7712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:38:59.205  1019  1134 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-23 12:38:59.205  1019  1134 D ConnectivityService: nai.networkMonitor.doQuit()
08-23 12:38:59.205  1019  1134 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-23 12:38:59.205  1019  1131 D WifiP2pService: InactiveState{ what=131204 }
08-23 12:38:59.205  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:59.205  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:59.205  1019  1134 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 12:38:59.205  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 12:38:59.205  1019  1132 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 12:38:59.205  1019  1155 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:38:59.205  1019  7712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-23 12:38:59.205  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:38:59.205  1019  1019 D RttService: SCAN_AVAILABLE : 1
08-23 12:38:59.205  1019  1156 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 12:38:59.205  1019  1131 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-23 12:38:59.215  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:38:59.215  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-23 12:38:59.215  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 12:38:59.215  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:38:59.215  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:38:59.215  1019  1134 E ConnectivityService: updateNetworkInfo()
,08-23 12:38:59.215  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 12:38:59.215  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-23 12:38:59.215  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 12:38:59.215  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 12:38:59.215  1019  1134 E ConnectivityService: updateNetworkInfo()
,08-23 12:38:59.215  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-23 12:38:59.225  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 12:38:59.225  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-23 12:38:59.225  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 12:38:59.225  1019  1050 D WifiDisplayController: disconnect
08-23 12:38:59.225  1019  1050 D WifiDisplayController: updateConnection
08-23 12:38:59.225  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 12:38:59.225  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:38:59.225  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 12:38:59.225  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 12:38:59.225  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:38:59.225  1019  1131 D WifiP2pService: P2pDisablingState
,08-23 12:38:59.225  1019  1131 D WifiP2pService: P2pDisablingState{ what=147458 }
08-23 12:38:59.225  1019  1131 D WifiP2pService: p2p socket connection lost
08-23 12:38:59.225  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:38:59.225  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 12:38:59.225  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:38:59.225  1019  1131 D WifiP2pService: P2pDisabledState
08-23 12:38:59.225  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:38:59.225  1019  1132 E WifiNative-wlan0: do suspend true
,08-23 12:38:59.225  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-23 12:38:59.225  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-23 12:38:59.235  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-23 12:38:59.235  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 12:38:59.235  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 12:38:59.235  1019  6888 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:38:59.235  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 12:38:59.235  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:59.235  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-23 12:38:59.235  7697  7697 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 12:38:59.245  7332  7332 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:59.245  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 12:38:59.245  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
08-23 12:38:59.245  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 12:38:59.245  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 12:38:59.245  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 12:38:59.245  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 12:38:59.255  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:38:59.255  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:59.255  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
08-23 12:38:59.255  7697  7697 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 12:38:59.255  1019  1131 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-23 12:38:59.255  1019  1131 D WifiP2pService: DefaultState{ what=143375 }
,08-23 12:38:59.265   279   970 D CommandListener: Clearing all IP addresses on wlan0
,08-23 12:38:59.265  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 12:38:59.265  7577  7577 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-23 12:38:59.265  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:59.265  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:38:59.275  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 12:38:59.275  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.275  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.275  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.275  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-23 12:38:59.275  7332  7332 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:38:59.275  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:38:59.275  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:38:59.285  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:59.285  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:38:59.285  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:38:59.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.285  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.285  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:59.295  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:59.295  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:38:59.295  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:38:59.295  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 12:38:59.295  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.295  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:38:59.295  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:38:59.295  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:38:59.295  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:38:59.295  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 12:38:59.295  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:38:59.295  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-23 12:38:59.295  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:59.295  1182  1182 D HotspotTile: onReceive : 0, 0
08-23 12:38:59.295  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:38:59.295  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:59.295  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:59.295  1019  1559 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:38:59.295  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:59.295  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:38:59.295  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:38:59.295  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:38:59.305  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:38:59.305  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:59.305  1628  1628 I Hs20UtilService: Starting #16
,08-23 12:38:59.305  1628  1655 I Hs20UtilService: Message received 5007
08-23 12:38:59.305  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 12:38:59.305  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 12:38:59.305  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:38:59.305  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:38:59.305  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 12:38:59.305  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:38:59.305  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:38:59.315  7715  7715 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 12:38:59.315  7715  7715 I dhcpcd  : version 5.5.6 starting
,08-23 12:38:59.315  1019  1453 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:38:59.325  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 12:38:59.325  7715  7715 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 12:38:59.325  1019  1453 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:38:59.325  1019  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:38:59.325  1019  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:38:59.325  1628  1628 I Hs20UtilService: Starting #17,
08-23 12:38:59.325  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:38:59.325  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 12:38:59.335  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 12:38:59.335  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
08-23 12:38:59.335  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:38:59.365  7715  7715 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-23 12:38:59.365  7715  7715 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-23 12:38:59.365  7715  7715 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-23 12:38:59.365  7715  7715 I dhcpcd  : bssid match,
,08-23 12:38:59.375  7715  7715 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-23 12:38:59.425  7577  7577 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 12:38:59.525  7715  7715 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-23 12:38:59.525  7577  7577 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-23 12:38:59.525  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:38:59.525  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:38:59.525  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 12:38:59.555  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 12:38:59.555  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:38:59.555  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:38:59.555  1019  1135 D Tethering: InitialState.processMessage what=4
08-23 12:38:59.555  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 12:38:59.555  1019  1047 D Tethering: interfaceStatusChanged wlan0, false,
08-23 12:38:59.555  7577  7577 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
,08-23 12:38:59.555  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:38:59.555  1019  1135 E Tethering: No numeric data
08-23 12:38:59.555  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:38:59.555  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 12:38:59.555  1182  1182 D HotspotTile: updateTetherState():false, false
08-23 12:38:59.555  1019  1135 D Tethering: clearTetheredNotification()
08-23 12:38:59.555  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:38:59.555  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:59.565  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:38:59.565  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 12:38:59.565  7577  7577 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-23 12:38:59.565  7577  7577 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-23 12:38:59.565  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:59.565  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:38:59.565  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-23 12:38:59.565  7577  7577 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-23 12:38:59.565  1019  1129 V NetworkStats: performPollLocked() took 11ms
,08-23 12:38:59.565  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:38:59.575  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:38:59.575  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:59.575  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:38:59.665  7715  7715 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-23 12:38:59.835  7577  7577 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 12:38:59.925  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 12:38:59.925  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:38:59.925  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-23 12:38:59.925  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:38:59.925  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:38:59.925  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:38:59.935  7577  7577 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-23 12:38:59.985  1019  1099 V AlarmManager: waitForAlarm result :8
,08-23 12:39:00.035  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-23 12:39:00.035  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 12:39:00.035  7347  7347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:39:00.055  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:39:00.055  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:39:00.055  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 12:39:00.055  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:00.055  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:00.055  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:00.055  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:39:00.055  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:00.055  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:39:00.055  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-23 12:39:00.055  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 12:39:00.055  1718  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:39:00.055  1182  1182 D HotspotTile: onReceive : 1, 0
,08-23 12:39:00.055  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:39:00.065  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:00.065  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:00.065  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:39:00.065  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:39:00.065  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:00.065  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:00.065  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:39:00.075  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 12:39:00.075  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-23 12:39:00.075  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 12:39:00.085  1628  1628 I Hs20UtilService: Starting #18
,08-23 12:39:00.085  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:39:00.085  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:39:00.465  1019  1045 W ActivityManager: mDVFSHelper.release()
,08-23 12:39:00.625   279   964 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-23 12:39:00.625  1019  1047 D Tethering: interfaceRemoved wlan0
,08-23 12:39:00.625  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-23 12:39:00.745  1019  1047 D Tethering: interfaceRemoved p2p0
,08-23 12:39:00.745  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-23 12:39:01.145  1019  1099 V AlarmManager: waitForAlarm result :4
,08-23 12:39:01.155  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___,
,08-23 12:39:01.155   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-23 12:39:01.155   279   966 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-23 12:39:01.155  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
08-23 12:39:01.155  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
08-23 12:39:01.155  1182  1182 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 12:39:01.155  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-23 12:39:01.165  1182  1182 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 12:39:01.165  1182  1182 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 12:39:01.175  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:01.175  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:39:01.175  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk,
,08-23 12:39:01.175  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 12:39:01.175  1182  1182 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-23 12:39:01.185  1182  1182 I KeyguardEffectViewController: *** don't update sliding image ***
,08-23 12:39:01.185  1182  1182 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-23 12:39:01.195  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 12:39:01.205  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,08-23 12:39:01.225  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 12:39:01.235  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 12:39:01.345   289   289 E SMD     : DCD OFF,
,08-23 12:39:01.505  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-23 12:39:02.155  6892  7141 D BluetoothAdapter: enable(),
,08-23 12:39:02.155  1019  1512 W ActivityManager: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,08-23 12:39:02.155  1019  1512 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
,08-23 12:39:02.155  1019  1512 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-23 12:39:02.155  1019  1512 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 12:39:02.155  1019  1512 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-23 12:39:02.155  1019  1512 W BluetoothManagerService: ,	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-23 12:39:02.155  1019  1512 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-23 12:39:02.155  1019  1512 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-23 12:39:02.155  1019  1512 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 12:39:02.155  1019  1512 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 12:39:02.155  1019  1512 D SettingsProvider: name = bluetooth_on,
,08-23 12:39:02.165  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-23 12:39:02.165  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
08-23 12:39:02.165  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 12:39:02.175  3219  3290 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-23 12:39:02.175  3219  3290 D BluetoothAdapterProperties: Setting state to 11
08-23 12:39:02.175  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-23 12:39:02.175  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:39:02.175  3219  3290 D BluetoothAdapterService: updateAdapterState state is 11
,08-23 12:39:02.175  3219  3290 D BluetoothAdapterService: Autoconnection is available 
08-23 12:39:02.175  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-23 12:39:02.175  3219  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService,
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-23 12:39:02.175  1019  1566 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:02.175  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 12:39:02.175  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
08-23 12:39:02.175  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-23 12:39:02.175  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.175  1019  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:02.175  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:39:02.185  1019  1453 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:02.185  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-23 12:39:02.185  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 12:39:02.185  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 12:39:02.185  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-23 12:39:02.185  1019  1453 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.185  1019  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.185  1019  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.185  3219  3219 D HeadsetService: Received start request. Starting profile...
,08-23 12:39:02.185  3219  3219 D HeadsetService: start()
08-23 12:39:02.185  3219  3219 D HeadsetStateMachine: make
,08-23 12:39:02.195  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-23 12:39:02.195  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:39:02.195  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-23 12:39:02.195  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:02.195  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-23 12:39:02.195  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.195  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.195  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.195  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-23 12:39:02.195  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 12:39:02.195  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-23 12:39:02.195  3219  3219 E HeadsetStateMachine: # of Max HF connection is 2
,08-23 12:39:02.195  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:02.195  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,08-23 12:39:02.215  1019  3384 D SSRM:n  : SIOP:: AP = 340
,08-23 12:39:02.215  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 12:39:02.215  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
,08-23 12:39:02.215  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:02.215  1182  1182 D BluetoothTile:  getBluetoothState : 11
,08-23 12:39:02.215  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:02.215  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
08-23 12:39:02.215  1901  1901 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 12:39:02.215  1019  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:02.215  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.215  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-23 12:39:02.215  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:02.215  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-23 12:39:02.215  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.225  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:02.225  1019  6889 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 12:39:02.225  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-23 12:39:02.225  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 12:39:02.225  1019  6888 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-23 12:39:02.225  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-23 12:39:02.225  1019  6888 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.225  1019  6888 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:02.225  1019  1032 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
08-23 12:39:02.225  1019  6888 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.225  1019  1559 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-23 12:39:02.225  1019  6888 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-23 12:39:02.225  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-23 12:39:02.225  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-23 12:39:02.225  1019  1081 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-23 12:39:02.225  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.225  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-23 12:39:02.225  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.225  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:39:02.225  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-23 12:39:02.225  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:02.225  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-23 12:39:02.235  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.235  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.235  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 12:39:02.235  3219  3219 I bluedroid: get_profile_interface handsfree
,08-23 12:39:02.235  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:02.235  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:02.235  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.235  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:02.235  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.245  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService,
08-23 12:39:02.245  1019  1567 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:02.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 12:39:02.245  1019  1567 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 12:39:02.245  1019  1567 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.245  1019  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.245  1019  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:02.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:02.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 12:39:02.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-23 12:39:02.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 12:39:02.245  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 12:39:02.245  3219  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 12:39:02.255  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:39:02.255  3219  3219 E DualScoManager: Dual Sco Manager already instantiated,
08-23 12:39:02.255  3219  3219 I DualScoManager: Set HeadsetServiceHelper
08-23 12:39:02.255  3219  3219 D BluetoothAtMessage: createCMTIContentObservers
,08-23 12:39:02.255  1019  1512 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-23 12:39:02.255  1019  1512 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 12:39:02.255  1019  1512 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 12:39:02.255  1019  1512 D SettingsProvider: selectionArgs: false
,08-23 12:39:02.255  1019  1512 D SettingsProvider: selectionArgs: 1002
08-23 12:39:02.255  1019  1512 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 12:39:02.255  1019  1512 D SettingsProvider: ret = -1
,08-23 12:39:02.255  3219  7749 D HeadsetStateMachine: Enter Disconnected: -2
,08-23 12:39:02.265  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:02.265  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11,
,08-23 12:39:02.265  3219  3219 D HeadsetService: mStartError = false
08-23 12:39:02.265  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:02.265  3219  3219 D A2dpService: Received start request. Starting profile...
,08-23 12:39:02.265  3219  3219 D A2dpService: start()
,08-23 12:39:02.265  3219  3219 I bluedroid: get_profile_interface avrcp,
08-23 12:39:02.265  1019  1566 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 12:39:02.275  3219  7749 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-23 12:39:02.275  3219  7749 D HeadsetStateMachine: map size, before remove : 0
08-23 12:39:02.275  3219  7749 D HeadsetStateMachine: map size, after remove: 0
08-23 12:39:02.275  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:02.275  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:02.275  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:02.275  1019  1566 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:02.275  3219  3219 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 12:39:02.275  3219  3219 D Avrcp   : Initialize Media Controller
,08-23 12:39:02.275  3219  3219 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-23 12:39:02.275  3219  3219 E Avrcp   : getActiveSessions
08-23 12:39:02.275  3219  3219 D Avrcp   : pick active media Controller
08-23 12:39:02.275  3219  3219 D Avrcp   : Get the active Media Controller 
,08-23 12:39:02.285  7751  7751 E Zygote  : MountEmulatedStorage(),
08-23 12:39:02.285  7751  7751 E Zygote  : v2
,08-23 12:39:02.285  7751  7751 I libpersona: KNOX_SDCARD checking this for 10055
08-23 12:39:02.285  7751  7751 I libpersona: KNOX_SDCARD not a persona
,08-23 12:39:02.285  7751  7751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:39:02.295  1019  1566 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7751 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 12:39:02.295  7751  7751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:39:02.295  7751  7751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:39:02.305  3219  3219 I Avrcp   :  Updating now playing list upon AVRCP Start
08-23 12:39:02.305  3219  7750 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-23 12:39:02.305  3219  3219 D A2dpStateMachine: make
,08-23 12:39:02.315  3219  7750 D BluetoothMediaBrowser: no now playing list
08-23 12:39:02.315  3219  7750 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-23 12:39:02.315  7751  7751 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:39:02.315  7751  7751 D ActivityThread: Added TimaKeyStore provider
,08-23 12:39:02.315  3219  3219 I bluedroid: get_profile_interface a2dp
08-23 12:39:02.315  3219  7765 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 12:39:02.315  3219  3219 E bt-btif : warning : media task started media_task_refcnt 1 
,08-23 12:39:02.315  3219  3219 D A2dpService: mStartError = false
08-23 12:39:02.315  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:02.315  3219  7760 D A2dpStateMachine: Enter Disconnected: -2
,08-23 12:39:02.315  3219  3219 D HidService: Received start request. Starting profile...
08-23 12:39:02.315  3219  3219 D HidService: start()
08-23 12:39:02.315  3219  3219 I bluedroid: get_profile_interface hidhost
08-23 12:39:02.315  3219  3219 D HidService: setHidService(): set to: null
08-23 12:39:02.315  3219  3219 D HidService: mStartError = false
08-23 12:39:02.315  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:02.325  3219  3219 D HealthService: Received start request. Starting profile...
08-23 12:39:02.325  3219  3219 D HealthService: start()
,08-23 12:39:02.325  3219  3219 I bluedroid: get_profile_interface health
08-23 12:39:02.325  3219  3219 D HealthService: mStartError = false
08-23 12:39:02.325  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:02.325  3219  3219 D HeadsetStateMachine: Try to query the phonestate on bind
08-23 12:39:02.325  1440  2473 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 12:39:02.325  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-23 12:39:02.325  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-23 12:39:02.325  1440  2473 I Telecom : BluetoothPhoneService: Result of Message : true
,08-23 12:39:02.335  3219  3219 D PanService: Received start request. Starting profile...
08-23 12:39:02.335  3219  3219 D PanService: start()
08-23 12:39:02.335  3219  3219 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 12:39:02.335  3219  3219 I bluedroid: get_profile_interface pan
08-23 12:39:02.335  3219  3219 D PanService: mStartError = false
08-23 12:39:02.335  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:02.335  3219  3219 D HeadsetStateMachine: Proxy object connected
08-23 12:39:02.335  3219  3219 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-23 12:39:02.335  3219  7749 D HeadsetStateMachine: Disconnected process message: 11
08-23 12:39:02.335  3219  3219 D BluetoothMapService: Received start request. Starting profile...
08-23 12:39:02.335  3219  3219 D BluetoothMapService: start()
,08-23 12:39:02.335  3219  3219 D BluetoothMapService: mStartError = false
08-23 12:39:02.335  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:02.335  3219  3219 D SapService: Received start request. Starting profile...
08-23 12:39:02.335  3219  3219 D SapService: start()
08-23 12:39:02.335  3219  3219 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-23 12:39:02.335  3219  3219 I bluedroid: get_profile_interface sap
08-23 12:39:02.335  3219  3219 D SapService: mStartError = false
08-23 12:39:02.335  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:02.335  3219  3219 D HeadsetPhoneState: sendDeviceDataStateChanged
08-23 12:39:02.335  3219  3219 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-23 12:39:02.335  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-23 12:39:02.335  3219  7749 D HeadsetStateMachine: Disconnected process message: 18
08-23 12:39:02.335  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 12:39:02.335  3219  7749 D HeadsetStateMachine: Disconnected process message: 10
,08-23 12:39:02.335  3219  7749 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 12:39:02.335  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-23 12:39:02.335  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-23 12:39:02.335  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-23 12:39:02.335  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-23 12:39:02.335  3219  7749 D HeadsetStateMachine: Disconnected process message: 11
,08-23 12:39:02.355  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-23 12:39:02.355  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-23 12:39:02.355  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-23 12:39:02.355  3219  3290 I bluedroid: enable
,08-23 12:39:02.365  7751  7751 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-23 12:39:02.365  3219  3293 E bt-btif : Calling BTA_HhEnable
,08-23 12:39:02.365  3219  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-23 12:39:02.365  3219  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-23 12:39:02.365  3219  3293 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-23 12:39:02.365  3219  3293 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-23 12:39:02.365  3219  3293 E BluetoothServiceJni: populateRssiValuesNative
08-23 12:39:02.365  3219  3293 I bluedroid: getModelRssiValues
08-23 12:39:02.365  3219  3293 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-23 12:39:02.365  3219  3293 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 12:39:02.365  1019  1019 D SettingsProvider: name = bluetooth_name
,08-23 12:39:02.365  3219  3293 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-23 12:39:02.375  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:02.375  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:02.375  3219  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 12:39:02.375  3219  3293 D BluetoothAdapterProperties: Scan Mode:20
08-23 12:39:02.375  3219  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 12:39:02.375  3219  3293 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-23 12:39:02.375  3219  3293 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-23 12:39:02.375  3219  3293 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-23 12:39:02.375  3219  3293 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-23 12:39:02.375  3219  3293 E bt-btif : JVenable fails
,08-23 12:39:02.375  3219  3293 D bte_conf: Device ID record 1 : primary
,08-23 12:39:02.375  3219  3293 D bte_conf:   vendorId            = 0075
08-23 12:39:02.375  3219  3293 D bte_conf:   vendorIdSource      = 0001
08-23 12:39:02.375  3219  3293 D bte_conf:   product             = 0100
,08-23 12:39:02.375  3219  3293 D bte_conf:   version             = 0200
,08-23 12:39:02.385  3219  3293 D bte_conf:   clientExecutableURL = 
08-23 12:39:02.385  3219  3293 D bte_conf:   serviceDescription  = 
08-23 12:39:02.385  3219  3293 D bte_conf:   documentationURL    = 
,08-23 12:39:02.385  3219  3293 D bte_conf: bte_load_did_conf no section named DID2.
,08-23 12:39:02.385  3219  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-23 12:39:02.385  3219  3293 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 12:39:02.385  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-23 12:39:02.385  3219  3290 D BluetoothAdapterProperties: ScanMode =  20
,08-23 12:39:02.385  3219  3290 D BluetoothAdapterProperties: State =  11
,08-23 12:39:02.385  1019  1559 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 12:39:02.385  3219  3290 D BluetoothAdapterProperties: Setting state to 12
,08-23 12:39:02.385  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 12:39:02.395  3219  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 12:39:02.395  3219  3293 D BluetoothAdapterProperties: Scan Mode:21
08-23 12:39:02.395  3219  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 12:39:02.395  1019  1490 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-23 12:39:02.395  1019  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 12:39:02.395  1019  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 12:39:02.395  1019  1490 D SettingsProvider: selectionArgs: false
08-23 12:39:02.395  1019  1490 D SettingsProvider: selectionArgs: 1002
08-23 12:39:02.395  1019  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 12:39:02.395  1019  1490 D SettingsProvider: ret = -1
,08-23 12:39:02.395  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:39:02.395  3219  3290 D BluetoothAdapterService: updateAdapterState state is 12
,08-23 12:39:02.395  1019  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:02.395  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.395  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.395  1019  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.395  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.395  7751  7751 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-23 12:39:02.395  7751  7751 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-23 12:39:02.395  7751  7751 D UserAnalysis: Create SecureDbHelper
,08-23 12:39:02.405  3219  3290 D BluetoothAdapterService: Autoconnection is available 
08-23 12:39:02.405  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-23 12:39:02.405  3219  3290 D BluetoothAdapterService: starting service from this receiver
,08-23 12:39:02.405  1019  1453 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:02.405  1687  1695 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:02.405  1687  1695 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:02.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:39:02.405  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-23 12:39:02.405  1019  1453 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.405  4715  4729 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:02.405  4715  4729 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 12:39:02.405  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-23 12:39:02.405  1019  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.405  3219  3219 I BluetoothPbapService: Handler(): got msg=1
08-23 12:39:02.405  1019  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:39:02.405  1019  1032 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-23 12:39:02.405  4715  4723 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 12:39:02.405  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:02.405  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-23 12:39:02.405  3219  3290 I BluetoothAdapterState: Entering On State from state = 11
08-23 12:39:02.405  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-23 12:39:02.405  7751  7751 D IntelligenceServiceApplication: onCreate()
08-23 12:39:02.405  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.405  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.405  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.405  4715  4729 D BluetoothPan: Binding service...
,08-23 12:39:02.415  1019  6889 I ActivityManager: Killing 7268:com.google.android.apps.maps/u0a105 (adj 15): empty #21
08-23 12:39:02.415  3219  7772 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:02.415  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:02.415  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 12:39:02.415  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.415  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:02.415  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.415  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.415  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.415  6892  6904 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:02.415  6892  6904 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.425  4715  4715 D BluetoothPbap: Proxy object connected
08-23 12:39:02.425  4715  4715 D PbapServerProfile: Bluetooth service connected
08-23 12:39:02.425  3219  7772 D BluetoothSocket: bindListen(): myUserId = 0
08-23 12:39:02.425  3219  7772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:39:02.425  3219  3381 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 12:39:02.425  3219  3381 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.435  4715  4715 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 12:39:02.435  4715  4715 D PanProfile: Bluetooth service connected
08-23 12:39:02.435  3219  7772 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-23 12:39:02.435  3219  7772 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 12:39:02.435  3219  7772 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 12:39:02.435  3219  7772 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bbe99ab
,08-23 12:39:02.435  3219  7772 D BluetoothSocket: channel: 19
08-23 12:39:02.435  3219  7772 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-23 12:39:02.435  7751  7751 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-23 12:39:02.435  1019  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 12:39:02.435  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 12:39:02.435  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.435  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.435  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.435  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-23 12:39:02.435  3219  3219 D BluetoothA2dp: Proxy object connected
08-23 12:39:02.435  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-23 12:39:02.435  1457  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:02.435  7751  7751 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-23 12:39:02.435  1457  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.435  1019  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 12:39:02.445  7751  7751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-23 12:39:02.445  1019  1049 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #7
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: android.os.TransactionTooLargeException
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:39:02.445  1019  1049 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-23 12:39:02.445  4715  4723 D Bluetoothsap: onBluetoothStateChange: up=true
,08-23 12:39:02.445  4715  4723 D Bluetoothsap: Binding service...
,08-23 12:39:02.455  4715  4723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-23 12:39:02.455  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-23 12:39:02.455  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.455  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:02.455  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.455  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.455  4715  4723 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-23 12:39:02.455  1471  1488 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.465  4715  4715 D Bluetoothsap: BluetoothSAP Proxy object connected
08-23 12:39:02.465  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:02.465  4715  4715 D SapProfile: Bluetooth service connected
08-23 12:39:02.465  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 12:39:02.465  4715  4715 D Bluetoothsap: getConnectedDevices()
08-23 12:39:02.465  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.465  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.465  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-23 12:39:02.465  1471  1488 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:02.465  4715  7774 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 12:39:02.465  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-23 12:39:02.465  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.475  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.475  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.475  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 12:39:02.475  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:02.475  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.475  1440  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.475  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:02.475  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:02.475  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.475  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.475  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.475  4715  4715 D BluetoothInputDevice: Proxy object connected
08-23 12:39:02.475  1440  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:02.475  4715  4715 D HidProfile: Bluetooth service connected
08-23 12:39:02.475  1182  2368 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:02.475  1182  2368 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.475  1718  3976 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:02.475  1718  3976 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.485  1440  2473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.485  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:02.485  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:02.485  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.485  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.485  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.485  1440  2473 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:02.485  1440  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:02.485  1440  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.485  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-23 12:39:02.485  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:02.485  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 12:39:02.485  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:02.485  1471  1484 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:02.485  1471  1484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.485  4715  4723 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 12:39:02.485  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-23 12:39:02.485  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.495  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.495  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.495  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.495  3219  3229 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:02.495  3219  3229 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:02.495  4715  4715 D BluetoothMap: Proxy object connected
,08-23 12:39:02.495  4715  7774 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.495  4715  4715 D MapProfile: Bluetooth service connected
08-23 12:39:02.495  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:02.495  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:02.495  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.495  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.495  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 12:39:02.495  4715  4715 D BluetoothMap: getConnectedDevices()
,08-23 12:39:02.495  4715  7774 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:02.495  1440  1455 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.495  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:02.495  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:02.495  4715  4715 D HeadsetProfile: Bluetooth service connected
,08-23 12:39:02.495  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.495  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.495  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.495  1440  1455 E BluetoothHeadset: BluetoothHeadset service is binded
08-23 12:39:02.495  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:39:02.495  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.495  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 12:39:02.495  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.495  1019  1019 D BluetoothA2dp: Proxy object connected
08-23 12:39:02.495  4715  4729 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 12:39:02.505  4715  4729 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:02.505  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 12:39:02.505  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.505  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.505  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.505  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.505  1019  1049 D BluetoothPan: Binding service...
08-23 12:39:02.505  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 12:39:02.505  4715  4715 D BluetoothA2dp: Proxy object connected
08-23 12:39:02.505  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-23 12:39:02.505  4715  4715 D A2dpProfile: Bluetooth service connected
08-23 12:39:02.505  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-23 12:39:02.505  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 12:39:02.505  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 12:39:02.505  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:02.505  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,08-23 12:39:02.505  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 12:39:02.515  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-23 12:39:02.515  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 12:39:02.515  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:39:02.515  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:39:02.515  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:02.515  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-23 12:39:02.525  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:39:02.525  1019  6889 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:39:02.525  1440  1440 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@249bb0ad, true
,08-23 12:39:02.525  1019  1512 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true,
,08-23 12:39:02.525  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 12:39:02.525  1440  1440 D BluetoothHeadset: registerMessageListener
,08-23 12:39:02.525  1901  1901 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 12:39:02.535  3219  3229 D HeadsetService: registerMessageListener
,08-23 12:39:02.535  3219  3229 D HeadsetService: registerMessageListener
,08-23 12:39:02.535  3219  7749 D HeadsetStateMachine: Disconnected process message: 70
08-23 12:39:02.535  3219  7749 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@383bb808
08-23 12:39:02.535  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-23 12:39:02.535  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-23 12:39:02.535  3219  7777 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-23 12:39:02.535  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:02.535  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:02.535  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-23 12:39:02.535  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-23 12:39:02.535  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-23 12:39:02.535  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:02.535  4715  4715 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-23 12:39:02.535  4715  4715 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-23 12:39:02.535  4715  4715 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-23 12:39:02.535  4715  4715 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-23 12:39:02.545  3219  7749 D HeadsetStateMachine: Disconnected process message: 9
08-23 12:39:02.545  3219  7749 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-23 12:39:02.545  3219  7777 D BluetoothSocket: bindListen(): myUserId = 0
,08-23 12:39:02.545  3219  7777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:02.545   284   284 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-23 12:39:02.545   284   284 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-23 12:39:02.545   284   284 V voice   : voice_set_parameters: exit with code(-2)
08-23 12:39:02.545   284   284 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-23 12:39:02.545   284   284 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-23 12:39:02.545   284   284 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-23 12:39:02.545   284   284 V audio_hw_primary: adev_set_parameters: exit
,08-23 12:39:02.545  3219  7749 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-23 12:39:02.545  3219  7777 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-23 12:39:02.545  3219  7777 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 12:39:02.545  3219  7777 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 12:39:02.545  3219  7777 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1affba1
,08-23 12:39:02.545  3219  7777 D BluetoothSocket: channel: 5
,08-23 12:39:02.545  4715  4715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:39:02.555  1019  1508 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 12:39:02.555  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.555  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:02.555  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.555  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 12:39:02.555  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:02.565  4715  4715 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:39:02.565  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:39:02.575  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:02.575  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-23 12:39:02.575  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:02.575  3219  3219 D BtConfig.SecureMode: isSecureModeOn:false
,08-23 12:39:02.575  1019  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:02.575  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-23 12:39:02.585  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:02.585  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:02.585  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:02.585  1019  1269 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-23 12:39:02.595  1019  1269 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:02.595  1019  1269 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:02.595  1019  1269 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:02.595  1019  1269 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:02.605  7780  7780 E Zygote  : MountEmulatedStorage()
,08-23 12:39:02.605  7780  7780 E Zygote  : v2
08-23 12:39:02.605  7780  7780 I libpersona: KNOX_SDCARD checking this for 10105
08-23 12:39:02.605  7780  7780 I libpersona: KNOX_SDCARD not a persona
,08-23 12:39:02.605  1019  1269 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7780 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-23 12:39:02.605  7780  7780 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:39:02.605  1019  1269 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 12:39:02.615  7780  7780 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:39:02.615  7780  7780 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-23 12:39:02.625  3219  7790 D BluetoothSocket: bindListen(): myUserId = 0
08-23 12:39:02.625  3219  7790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:02.625  3219  7790 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-23 12:39:02.625  3219  7790 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 12:39:02.625  3219  7790 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 12:39:02.625  3219  7790 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14afb0dd
,08-23 12:39:02.625  3219  7790 D BluetoothSocket: channel: 12
08-23 12:39:02.625  3219  7790 I BtOppRfcommListener: Accept thread started.
,08-23 12:39:02.635  7780  7780 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:39:02.635  7780  7780 D ActivityThread: Added TimaKeyStore provider
,08-23 12:39:02.705  1019  3416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 12:39:02.745   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 12:39:02.745   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:39:02.745  7780  7801 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 12:39:02.755   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 12:39:02.755   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:39:02.755  7780  7801 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.v.a(PG,:1161)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.k.d(PG:583)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a,(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:39:02.915  7780  7780 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:02.915  7780  7780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 12:39:02.925  1019  1269 I ActivityManager: Killing 7388:com.sec.pcw.device/1000 (adj 15): empty #21
,08-23 12:39:02.985  7780  7811 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 12:39:03.005  1019  1452 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 12:39:03.005  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:03.005  1019  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:39:03.005  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-23 12:39:03.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 12:39:04.345   289   289 E SMD     : DCD OFF,
,08-23 12:39:04.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 12:39:05.175  6892  7141 D BluetoothAdapter: disable()
,08-23 12:39:05.175  1019  1031 D SettingsProvider: name = bluetooth_on
,08-23 12:39:05.175  3219  3290 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-23 12:39:05.175  3219  3290 D BluetoothAdapterProperties: Setting state to 13
,08-23 12:39:05.175  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-23 12:39:05.175  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:39:05.175  3219  3290 D BluetoothAdapterService: updateAdapterState state is 13
,08-23 12:39:05.185  1019  1453 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-23 12:39:05.185  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
,08-23 12:39:05.185  1019  1453 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:05.185  1019  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:05.185  1019  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.185  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-23 12:39:05.185  3219  3290 D BluetoothAdapterService: Autoconnection is available 
08-23 12:39:05.185  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-23 12:39:05.185  3219  3290 D BluetoothAdapterService: terminating service from this receiver
,08-23 12:39:05.185  1019  1269 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.185  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e9fd452, channel: 19, state: LISTENING
08-23 12:39:05.185  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e9fd452, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bbe99ab, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@262a9323mSocket: android.net.LocalSocket@29078020 impl:android.net.LocalSocketImpl@39fb7dd9 fd:FileDescriptor[80]
08-23 12:39:05.185  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29078020 impl:android.net.LocalSocketImpl@39fb7dd9 fd:FileDescriptor[80]
,08-23 12:39:05.185  1019  1269 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:05.185  1019  1269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:05.185  1019  1269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.195  3219  3290 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 12:39:05.195  3219  3290 D BluetoothAdapterProperties: mDiscovering is false
,08-23 12:39:05.195  4715  4715 D BluetoothPbap: Proxy object disconnected
08-23 12:39:05.195  4715  4715 D PbapServerProfile: Bluetooth service disconnected
08-23 12:39:05.195  1019  1032 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 12:39:05.195  3219  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-23 12:39:05.205  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:05.205  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-23 12:39:05.205  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,08-23 12:39:05.205  3219  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 12:39:05.215  3219  3293 D BluetoothAdapterProperties: Scan Mode:20
,08-23 12:39:05.215  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 12:39:05.215  1901  1901 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 12:39:05.215  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:05.215  1182  1182 D BluetoothTile:  getBluetoothState : 13
,08-23 12:39:05.215  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:39:05.215  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:05.225  1019  1452 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:39:05.225  1019  6889 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 12:39:05.225  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:39:05.225  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-23 12:39:05.225  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:39:05.225  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 12:39:05.225  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-23 12:39:05.225  3219  3290 E bt-btif : HAL bt_hal_cbacks->log_collector_cb
,08-23 12:39:05.235  3219  3290 E bt-btif : cmd socket is not created
08-23 12:39:05.235  3219  7790 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-23 12:39:05.235  4715  4715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:39:05.235  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b093e7f, channel: 5, state: LISTENING
08-23 12:39:05.235  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b093e7f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1affba1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9347e4cmSocket: android.net.LocalSocket@249d1e95 impl:android.net.LocalSocketImpl@32759baa fd:FileDescriptor[82]
08-23 12:39:05.235  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@249d1e95 impl:android.net.LocalSocketImpl@32759baa fd:FileDescriptor[82]
08-23 12:39:05.235  3219  3219 I BtOppRfcommListener: stopping Accept Thread
08-23 12:39:05.235  3219  3219 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20fd439b, channel: 12, state: LISTENING
08-23 12:39:05.235  3219  3290 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 12:39:05.235  3219  3219 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20fd439b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14afb0dd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b513338mSocket: android.net.LocalSocket@347e0f11 impl:android.net.LocalSocketImpl@3a69c876 fd:FileDescriptor[85]
08-23 12:39:05.235  3219  3219 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@347e0f11 impl:android.net.LocalSocketImpl@3a69c876 fd:FileDescriptor[85]
,08-23 12:39:05.235  3219  7790 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 12:39:05.235  1019  1032 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 12:39:05.235  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.235  3219  3294 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-23 12:39:05.235  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:05.235  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:05.235  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:05.235  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:39:05.245  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:05.245  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:05.245  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 12:39:05.245  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:39:05.245  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:39:05.245  3219  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 12:39:05.245  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:39:05.245  3219  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:39:05.245  3219  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 12:39:05.245  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:39:05.245  3219  3219 V BluetoothOppManager: cleanUp...
,08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:05.245  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:05.245  6892  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:39:05.255  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:05.255  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:05.255  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:05.255  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:05.255  4715  4715 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:39:05.265  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:39:05.265  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:05.265  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-23 12:39:05.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 12:39:05.375  1019  1559 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 12:39:05.375  1019  1559 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-23 12:39:05.375  1019  1559 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 12:39:05.375  1019  1559 D BatteryService: stay LED for charging
08-23 12:39:05.375  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 12:39:05.385  1019  1019 I MotionRecognitionService: Plugged
,08-23 12:39:05.385  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 12:39:05.385  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 12:39:05.385  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 12:39:05.385  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 12:39:05.385  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-23 12:39:05.395  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 12:39:05.395  3219  7749 D HeadsetStateMachine: Disconnected process message: 10
,08-23 12:39:05.405  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-23 12:39:05.415  1182  1182 D SViewCoverView: level :99 plugged : 2
,08-23 12:39:05.415  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:39:05.415  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2,
,08-23 12:39:05.415  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:39:05.435  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-23 12:39:05.435  3219  3290 D BtConfig.SecureMode: isSecureModeOn:false
,08-23 12:39:05.445  3219  3290 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
,08-23 12:39:05.445  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-23 12:39:05.445  3219  3290 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-23 12:39:05.445  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 12:39:05.445  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
08-23 12:39:05.445  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 12:39:05.445  1019  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:05.445  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.445  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:05.445  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-23 12:39:05.445  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 12:39:05.445  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 12:39:05.445  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 12:39:05.455  1019  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:05.445  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-23 12:39:05.455  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.455  1019  1452 W ActivityManager: userId = 0, bbcId = -10000,
,08-23 12:39:05.455  1019  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-23 12:39:05.455  1019  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:05.455  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.455  1019  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-23 12:39:05.455  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-23 12:39:05.455  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:39:05.455  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-23 12:39:05.455  3219  3219 D HeadsetService: Received stop request...Stopping profile...
08-23 12:39:05.455  1019  1512 W ActivityManager: userId = 0, bbcId = -10000,
08-23 12:39:05.455  1019  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:05.455  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.455  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-23 12:39:05.455  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-23 12:39:05.455  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-23 12:39:05.455  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:05.465  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-23 12:39:05.465  1019  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:05.465  1019  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.465  4715  4715 D HeadsetProfile: Bluetooth service disconnected
,08-23 12:39:05.465  3219  3219 D A2dpService: Received stop request...Stopping profile...
08-23 12:39:05.465  1019  1512 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:05.465  1019  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:05.465  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.465  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-23 12:39:05.465  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 12:39:05.465  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 12:39:05.465  3219  7760 D A2dpStateMachine: Exit Disconnected: -1
,08-23 12:39:05.465  1019  6888 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:05.465  1019  6888 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.465  1019  6888 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:05.465  1019  6888 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:05.465  1019  6888 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.475  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 12:39:05.475  1019  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:05.475  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.475  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:05.475  1019  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:05.475  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-23 12:39:05.475  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-23 12:39:05.475  1019  1269 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:05.475  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:05.475  1019  1269 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.475  1019  1269 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:05.475  1019  1269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:05.475  1019  1269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 12:39:05.475  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:05.475  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 12:39:05.475  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-23 12:39:05.475  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 12:39:05.475  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 12:39:05.475  3219  3290 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-23 12:39:05.485  1019  1019 D BluetoothA2dp: Proxy object disconnected
,08-23 12:39:05.485  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-23 12:39:05.485  4715  4715 D BluetoothA2dp: Proxy object disconnected
08-23 12:39:05.485  3219  3219 D HidService: Received stop request...Stopping profile...
08-23 12:39:05.485  3219  3219 D HidService: Stopping Bluetooth HidService
08-23 12:39:05.485  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 12:39:05.485  3219  3219 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-23 12:39:05.485  3219  3219 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 12:39:05.485  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:05.485  4715  4715 D A2dpProfile: Bluetooth service disconnected
,08-23 12:39:05.485  4715  4715 D BluetoothInputDevice: Proxy object disconnected
,08-23 12:39:05.485  4715  4715 D HidProfile: Bluetooth service disconnected
08-23 12:39:05.485  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-23 12:39:05.485  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:39:05.485  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 12:39:05.485  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 12:39:05.485  3219  3219 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-23 12:39:05.485  3219  3219 D HealthService: Received stop request...Stopping profile...
,08-23 12:39:05.485  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:05.495  3219  3219 D PanService: Received stop request...Stopping profile...
,08-23 12:39:05.495  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:05.495  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-23 12:39:05.495  3219  3219 D BluetoothMapService: Received stop request...Stopping profile...
,08-23 12:39:05.495  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:05.495  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-23 12:39:05.495  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:39:05.495  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 12:39:05.495  3219  3219 D SapService: Received stop request...Stopping profile...
,08-23 12:39:05.495  4715  4715 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 12:39:05.495  3219  3219 D SapService: Stopping Bluetooth SapService
08-23 12:39:05.495  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:05.505  4715  4715 D PanProfile: Bluetooth service disconnected
08-23 12:39:05.505  4715  4715 D BluetoothMap: Proxy object disconnected
08-23 12:39:05.505  4715  4715 D MapProfile: Bluetooth service disconnected
,08-23 12:39:05.505  4715  4715 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-23 12:39:05.505  3219  3219 D BluetoothA2dp: Proxy object disconnected
08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-23 12:39:05.505  3219  7765 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-23 12:39:05.505  3219  3219 I GKI_LINUX: GKI_exit_task 2 done
08-23 12:39:05.505  3219  3219 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 12:39:05.505  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:39:05.505  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.505  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:39:05.505  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.505  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 12:39:05.505  3219  3219 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 12:39:05.505  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-23 12:39:05.505  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:05.505  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 12:39:05.505  3219  3219 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-23 12:39:05.505  4715  4715 D SapProfile: Bluetooth service disconnected
,08-23 12:39:05.505  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-23 12:39:05.505  3219  3219 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-23 12:39:05.505  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-23 12:39:05.505  3219  3219 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-23 12:39:05.515  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-23 12:39:05.515  3219  3219 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-23 12:39:05.515  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-23 12:39:05.515  3219  3290 D BluetoothAdapterProperties: Setting state to 10
08-23 12:39:05.515  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 12:39:05.515  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:39:05.515  3219  3290 D BluetoothAdapterService: updateAdapterState state is 10
,08-23 12:39:05.515  3219  3290 D BluetoothAdapterService: Autoconnection is available 
,08-23 12:39:05.515  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-23 12:39:05.515  3219  3290 I BluetoothAdapterState: Entering OffState
,08-23 12:39:05.515  1687  1710 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:39:05.515  1687  1710 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 12:39:05.515  4715  4723 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-23 12:39:05.515  4715  4723 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:39:05.515  4715  7774 D BluetoothPbap: onBluetoothStateChange: up=false
,08-23 12:39:05.515  6892  7696 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:39:05.515  6892  7696 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:39:05.515  6892  7696 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-23 12:39:05.515  6892  7696 D BluetoothLeAdvertiser: Exit stop advertising
,08-23 12:39:05.515  6892  7696 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-23 12:39:05.515  6892  7696 D BluetoothLeScanner: Exiting stopAllScan
,08-23 12:39:05.515  3219  7776 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:39:05.515  1457  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:39:05.515  1457  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 12:39:05.525  4715  4723 D Bluetoothsap: onBluetoothStateChange: up=false
08-23 12:39:05.525  4715  4723 D Bluetoothsap: Unbinding service...
,08-23 12:39:05.525  4715  7774 D BluetoothInputDevice: onBluetoothStateChange: up=false,
,08-23 12:39:05.525  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:39:05.525  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:39:05.525  1182  1198 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:39:05.525  1182  1198 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 12:39:05.525  1718  3976 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:39:05.525  1718  3976 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:39:05.525  1440  7775 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 12:39:05.525  1440  7775 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:39:05.525  1471  1484 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:39:05.525  1471  1484 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 12:39:05.525  4715  4729 D BluetoothMap: onBluetoothStateChange: up=false
08-23 12:39:05.525  3219  3229 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:39:05.525  3219  3229 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 12:39:05.525  7780  7793 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 12:39:05.525  7780  7793 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 12:39:05.535  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 12:39:05.535  4715  7774 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:39:05.535  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:05.535  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
08-23 12:39:05.535  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 12:39:05.545  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 12:39:05.545  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:05.545  1182  1182 D BluetoothTile:  getBluetoothState : 10
,08-23 12:39:05.545  1901  1901 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 12:39:05.545  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:05.545  1019  1081 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:39:05.555  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:05.555  1019  6888 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 12:39:05.555  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 12:39:05.555  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:05.555  4715  4715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:39:05.555  1019  1567 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 12:39:05.555  1019  1567 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 12:39:05.555  1019  1567 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:05.555  1019  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:05.555  1019  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 12:39:05.565  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:05.565  4715  4715 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:39:05.565  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:39:05.575  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:05.575  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-23 12:39:06.355   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 12:39:07.345   289   289 E SMD     : DCD OFF
,08-23 12:39:07.345   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 12:39:08.195  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:39:08.195  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:08.355   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 12:39:10.355   289   289 E SMD     : DCD OFF
,08-23 12:39:11.205  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:11.205  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f2c6deb added. We now have 6 listener(s)
08-23 12:39:11.205  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:11.205  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:11.205  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e2a9748 added. We now have 7 listener(s)
,08-23 12:39:11.205  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:11.205  6892  7141 I System.out: IsBluetoothEnabled
,08-23 12:39:11.205  6892  7141 D BluetoothAdapter: disable()
,08-23 12:39:11.205  1019  1032 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-23 12:39:11.205  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:11.205  6892  7141 D BluetoothAdapter: enable()
,08-23 12:39:11.215  1019  1512 W ActivityManager: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-23 12:39:11.215  1019  1512 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-23 12:39:11.215  1019  1512 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-23 12:39:11.215  1019  1512 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 12:39:11.215  1019  1512 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-23 12:39:11.215  1019  1512 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-23 12:39:11.215  1019  1512 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-23 12:39:11.215  1019  1512 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 12:39:11.215  1019  1512 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 12:39:11.215  1019  1512 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 12:39:11.225  1019  1512 D SettingsProvider: name = bluetooth_on,
,08-23 12:39:11.235  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 12:39:11.235  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 12:39:11.235  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-23 12:39:11.245  3219  3290 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
08-23 12:39:11.245  3219  3290 D BluetoothAdapterProperties: Setting state to 11
08-23 12:39:11.245  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11,
08-23 12:39:11.245  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:39:11.245  3219  3290 D BluetoothAdapterService: updateAdapterState state is 11
08-23 12:39:11.245  3219  3290 D BluetoothAdapterService: Autoconnection is available 
,08-23 12:39:11.245  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11,
08-23 12:39:11.245  3219  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-23 12:39:11.245  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 12:39:11.245  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10,
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService,
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService,
08-23 12:39:11.245  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 12:39:11.245  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 12:39:11.255  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 12:39:11.255  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:11.255  1182  1182 D BluetoothTile:  getBluetoothState : 11
,08-23 12:39:11.265  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
08-23 12:39:11.265  1901  1901 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 12:39:11.265  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 12:39:11.265  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:11.265  1019  1490 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:39:11.265  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:11.265  1019  6889 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 12:39:11.265  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 12:39:11.275  1019  1566 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:11.275  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.275  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.275  1019  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.275  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.275  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-23 12:39:11.275  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-23 12:39:11.275  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-23 12:39:11.285  3219  3219 D HeadsetService: Received start request. Starting profile...
08-23 12:39:11.285  3219  3219 D HeadsetService: start()
08-23 12:39:11.285  3219  3219 D HeadsetStateMachine: make
,08-23 12:39:11.285  3219  3219 E HeadsetStateMachine: # of Max HF connection is 2
,08-23 12:39:11.285  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:11.285  1019  1453 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-23 12:39:11.285  1019  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.295  1019  1453 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.295  1019  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.295  1019  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
,08-23 12:39:11.295  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-23 12:39:11.295  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.295  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.295  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:11.295  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.305  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-23 12:39:11.305  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 12:39:11.305  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-23 12:39:11.305  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:39:11.305  1019  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:11.305  1019  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.305  1019  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.305  1019  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.305  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.315  1019  1486 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-23 12:39:11.315  1019  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-23 12:39:11.315  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-23 12:39:11.315  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 12:39:11.315  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-23 12:39:11.315  1019  1486 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.315  1019  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.315  1019  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 12:39:11.315  3219  3219 I bluedroid: get_profile_interface handsfree
,08-23 12:39:11.315  1019  6889 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 12:39:11.315  1019  6889 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.315  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.315  1019  6889 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.315  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.325  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-23 12:39:11.325  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 12:39:11.325  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 12:39:11.325  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:11.325  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.325  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.325  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.325  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.325  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 12:39:11.325  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 12:39:11.325  3219  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 12:39:11.335  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:11.335  1019  1566 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:11.335  1019  1566 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.335  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-23 12:39:11.335  1019  1566 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.335  1019  1566 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.335  1019  1566 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.335  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-23 12:39:11.335  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 12:39:11.335  3219  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-23 12:39:11.345  3219  3219 E DualScoManager: Dual Sco Manager already instantiated
08-23 12:39:11.345  1019  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:11.345  3219  3219 I DualScoManager: Set HeadsetServiceHelper
08-23 12:39:11.345  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-23 12:39:11.345  3219  3219 D BluetoothAtMessage: createCMTIContentObservers
,08-23 12:39:11.345  1019  1490 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-23 12:39:11.345  1019  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 12:39:11.345  1019  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 12:39:11.345  1019  1490 D SettingsProvider: selectionArgs: false
08-23 12:39:11.345  1019  1490 D SettingsProvider: selectionArgs: 1002
08-23 12:39:11.345  1019  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 12:39:11.345  1019  1490 D SettingsProvider: ret = -1
08-23 12:39:11.345  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.345  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.345  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-23 12:39:11.345  3219  7825 D HeadsetStateMachine: Enter Disconnected: -2
08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:11.345  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:11.345  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 12:39:11.345  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-23 12:39:11.345  3219  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 12:39:11.345  1440  1454 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 12:39:11.345  3219  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 12:39:11.345  3219  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 12:39:11.345  3219  3219 D HeadsetService: mStartError = false
08-23 12:39:11.345  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:11.345  3219  3219 D HeadsetStateMachine: Try to query the phonestate on bind
,08-23 12:39:11.345  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-23 12:39:11.345  3219  7825 D HeadsetStateMachine: Clear mHeadsetBrsf
08-23 12:39:11.345  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-23 12:39:11.345  3219  7825 D HeadsetStateMachine: map size, before remove : 0
08-23 12:39:11.355  1440  1454 I Telecom : BluetoothPhoneService: Result of Message : true
08-23 12:39:11.345  3219  7825 D HeadsetStateMachine: map size, after remove: 0
,08-23 12:39:11.355  3219  3219 D A2dpService: Received start request. Starting profile...
08-23 12:39:11.355  3219  3219 D A2dpService: start()
,08-23 12:39:11.355  3219  3219 I bluedroid: get_profile_interface avrcp
,08-23 12:39:11.355  3219  3219 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 12:39:11.355  3219  3219 D Avrcp   : Initialize Media Controller
08-23 12:39:11.355  3219  3219 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-23 12:39:11.355  3219  3219 E Avrcp   : getActiveSessions
,08-23 12:39:11.355  3219  3219 D Avrcp   : pick active media Controller
08-23 12:39:11.355  3219  3219 D Avrcp   : Get the active Media Controller 
,08-23 12:39:11.365  3219  3219 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-23 12:39:11.365  3219  3219 D A2dpStateMachine: make
,08-23 12:39:11.365  3219  7826 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-23 12:39:11.365  3219  3219 I bluedroid: get_profile_interface a2dp
08-23 12:39:11.365  3219  7828 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 12:39:11.365  3219  3219 E bt-btif : warning : media task started media_task_refcnt 1 
,08-23 12:39:11.375  3219  3219 D A2dpService: mStartError = false
08-23 12:39:11.375  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:11.375  3219  7827 D A2dpStateMachine: Enter Disconnected: -2
,08-23 12:39:11.375  3219  3219 D HidService: Received start request. Starting profile...
,08-23 12:39:11.375  3219  3219 D HidService: start()
08-23 12:39:11.375  3219  3219 I bluedroid: get_profile_interface hidhost
08-23 12:39:11.375  3219  3219 D HidService: setHidService(): set to: null
,08-23 12:39:11.375  3219  3219 D HidService: mStartError = false
08-23 12:39:11.375  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:11.375  3219  3219 D HeadsetStateMachine: Proxy object connected
08-23 12:39:11.375  3219  3219 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-23 12:39:11.375  3219  7825 D HeadsetStateMachine: Disconnected process message: 11
08-23 12:39:11.375  3219  3219 D HealthService: Received start request. Starting profile...
08-23 12:39:11.375  3219  3219 D HealthService: start()
,08-23 12:39:11.375  3219  3219 I bluedroid: get_profile_interface health
08-23 12:39:11.375  3219  3219 D HealthService: mStartError = false
08-23 12:39:11.375  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:11.375  3219  3219 D PanService: Received start request. Starting profile...,
08-23 12:39:11.375  3219  3219 D PanService: start()
08-23 12:39:11.375  3219  3219 D BluetoothPanServiceJni: initializeNative(L110): pan,
08-23 12:39:11.375  3219  3219 I bluedroid: get_profile_interface pan
08-23 12:39:11.375  3219  3219 D PanService: mStartError = false
08-23 12:39:11.375  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:11.375  3219  3219 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-23 12:39:11.375  3219  3219 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-23 12:39:11.375  3219  7825 D HeadsetStateMachine: Disconnected process message: 18
,08-23 12:39:11.385  3219  3219 D BluetoothMapService: Received start request. Starting profile...
08-23 12:39:11.385  3219  3219 D BluetoothMapService: start()
,08-23 12:39:11.385  3219  7826 D BluetoothMediaBrowser: no now playing list
,08-23 12:39:11.385  3219  7826 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-23 12:39:11.385  3219  3219 D BluetoothMapService: mStartError = false
,08-23 12:39:11.385  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:11.385  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-23 12:39:11.385  3219  3219 D SapService: Received start request. Starting profile...
,08-23 12:39:11.385  3219  3219 D SapService: start()
08-23 12:39:11.385  3219  3219 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-23 12:39:11.385  3219  3219 I bluedroid: get_profile_interface sap
08-23 12:39:11.385  3219  3219 D SapService: mStartError = false
08-23 12:39:11.385  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
08-23 12:39:11.385  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 12:39:11.385  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-23 12:39:11.385  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-23 12:39:11.385  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-23 12:39:11.385  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-23 12:39:11.385  3219  7825 D HeadsetStateMachine: Disconnected process message: 10
,08-23 12:39:11.385  3219  7825 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 12:39:11.385  3219  7825 D HeadsetStateMachine: Disconnected process message: 11
,08-23 12:39:11.405  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-23 12:39:11.405  3219  3219 E BluetoothAdapterService(757739038): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-23 12:39:11.405  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-23 12:39:11.405  3219  3290 I bluedroid: enable
,08-23 12:39:11.415  3219  3293 E bt-btif : Calling BTA_HhEnable
,08-23 12:39:11.415  3219  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-23 12:39:11.415  3219  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-23 12:39:11.415  3219  3293 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-23 12:39:11.415  3219  3293 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-23 12:39:11.415  3219  3293 E BluetoothServiceJni: populateRssiValuesNative
08-23 12:39:11.415  3219  3293 I bluedroid: getModelRssiValues
,08-23 12:39:11.415  3219  3293 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-23 12:39:11.415  3219  3293 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 12:39:11.415  3219  3293 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-23 12:39:11.415  1019  1019 D SettingsProvider: name = bluetooth_name
,08-23 12:39:11.425  3219  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 12:39:11.425  3219  3293 D BluetoothAdapterProperties: Scan Mode:20
,08-23 12:39:11.425  3219  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 12:39:11.425  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:11.425  3219  3293 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-23 12:39:11.425  3219  3293 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-23 12:39:11.425  3219  3293 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-23 12:39:11.425  3219  3293 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-23 12:39:11.425  3219  3293 E bt-btif : JVenable fails
,08-23 12:39:11.425  3219  3293 D bte_conf: Device ID record 1 : primary
,08-23 12:39:11.425  3219  3293 D bte_conf:   vendorId            = 0075
08-23 12:39:11.435  3219  3293 D bte_conf:   vendorIdSource      = 0001
,08-23 12:39:11.435  3219  3293 D bte_conf:   product             = 0100
08-23 12:39:11.435  3219  3293 D bte_conf:   version             = 0200
08-23 12:39:11.435  3219  3293 D bte_conf:   clientExecutableURL = 
,08-23 12:39:11.435  3219  3293 D bte_conf:   serviceDescription  = 
,08-23 12:39:11.435  3219  3293 D bte_conf:   documentationURL    = 
,08-23 12:39:11.435  3219  3293 D bte_conf: bte_load_did_conf no section named DID2.
,08-23 12:39:11.435  3219  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-23 12:39:11.435  3219  3290 D BluetoothAdapterProperties: ScanMode =  20
08-23 12:39:11.435  3219  3290 D BluetoothAdapterProperties: State =  11
,08-23 12:39:11.435  1019  6889 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 12:39:11.435  3219  3293 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-23 12:39:11.435  3219  3293 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 12:39:11.435  3219  3290 D BluetoothAdapterProperties: Setting state to 12
,08-23 12:39:11.435  3219  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 12:39:11.435  3219  3293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 12:39:11.435  3219  3293 D BluetoothAdapterProperties: Scan Mode:21
08-23 12:39:11.435  3219  3293 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 12:39:11.435  1019  1486 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-23 12:39:11.435  1019  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 12:39:11.435  1019  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 12:39:11.435  1019  1486 D SettingsProvider: selectionArgs: false
08-23 12:39:11.435  1019  1486 D SettingsProvider: selectionArgs: 1002,
08-23 12:39:11.445  1019  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:11.435  1019  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 12:39:11.445  1019  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.445  1019  1486 D SettingsProvider: ret = -1
08-23 12:39:11.445  3219  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 12:39:11.445  3219  3290 D BluetoothAdapterService: updateAdapterState state is 12
,08-23 12:39:11.445  1019  1512 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.445  1019  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:11.445  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.445  3219  3290 D BluetoothAdapterService: Autoconnection is available 
08-23 12:39:11.445  3219  3290 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-23 12:39:11.445  3219  3290 D BluetoothAdapterService: starting service from this receiver
,08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:11.445  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:11.445  1687  2189 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:11.445  1687  2189 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.445  1019  6888 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:11.445  4715  4729 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:11.445  4715  4729 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 12:39:11.445  1019  6888 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0,
08-23 12:39:11.445  4715  4723 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 12:39:11.445  1019  6888 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.445  1019  6888 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.445  1019  6888 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.455  3219  3219 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-23 12:39:11.455  3219  3219 I BluetoothPbapService: Handler(): got msg=1
,08-23 12:39:11.455  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:11.455  3219  3290 I BluetoothAdapterState: Entering On State from state = 11
,08-23 12:39:11.595  1019  1049 I art     : Explicit concurrent mark sweep GC freed 55160(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.330ms total 138.659ms
08-23 12:39:11.595  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-23 12:39:11.595  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-23 12:39:11.595  1019  1269 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 12:39:11.595  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.595  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.595  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.595  4715  4723 D BluetoothPan: Binding service...
,08-23 12:39:11.595  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 12:39:11.595  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.605  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.605  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.605  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.605  3219  7833 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-23 12:39:11.605  6892  6904 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:11.605  6892  6904 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.605  3219  7776 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 12:39:11.605  4715  4715 D BluetoothPbap: Proxy object connected
08-23 12:39:11.605  3219  7776 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:11.605  4715  4715 D PbapServerProfile: Bluetooth service connected
,08-23 12:39:11.605  4715  4715 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 12:39:11.605  1019  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 12:39:11.605  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.605  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.605  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.605  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.615  4715  4715 D PanProfile: Bluetooth service connected
,08-23 12:39:11.615  1457  1478 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:11.615  1457  1478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.615  3219  7833 D BluetoothSocket: bindListen(): myUserId = 0
08-23 12:39:11.615  3219  7833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:11.615  3219  3219 D BluetoothA2dp: Proxy object connected
08-23 12:39:11.615  3219  3219 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-23 12:39:11.615  4715  4729 D Bluetoothsap: onBluetoothStateChange: up=true
08-23 12:39:11.615  4715  4729 D Bluetoothsap: Binding service...
,08-23 12:39:11.615  3219  7833 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-23 12:39:11.615  3219  7833 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 12:39:11.615  3219  7833 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 12:39:11.615  3219  7833 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9eb2dae
08-23 12:39:11.615  3219  7833 D BluetoothSocket: channel: 19
08-23 12:39:11.615  3219  7833 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-23 12:39:11.615  4715  4729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-23 12:39:11.615  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-23 12:39:11.615  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.625  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.625  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.625  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.625  4715  4729 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-23 12:39:11.625  4715  4715 D Bluetoothsap: BluetoothSAP Proxy object connected
08-23 12:39:11.625  4715  4715 D SapProfile: Bluetooth service connected
08-23 12:39:11.625  4715  4715 D Bluetoothsap: getConnectedDevices()
,08-23 12:39:11.625  1471  1488 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:11.625  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:11.625  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:11.625  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.625  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.625  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.625  1471  1488 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:11.625  4715  7774 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 12:39:11.635  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-23 12:39:11.635  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.635  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.635  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.635  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.635  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:11.635  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.635  1440  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:11.635  4715  4715 D BluetoothInputDevice: Proxy object connected
08-23 12:39:11.635  4715  4715 D HidProfile: Bluetooth service connected
,08-23 12:39:11.635  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-23 12:39:11.635  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 12:39:11.635  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.635  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.635  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-23 12:39:11.635  1440  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:11.635  1182  1201 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:11.635  1182  1201 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.635  1718  2825 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:11.635  1718  2825 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.645  1440  7775 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,08-23 12:39:11.645  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:11.645  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:11.645  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.645  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.645  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.645  1440  7775 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:11.645  1440  2473 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:11.645  1440  2473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 12:39:11.645  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:11.645  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:11.645  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:11.645  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded,
08-23 12:39:11.645  1471  1969 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:11.645  1471  1969 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 12:39:11.645  4715  4729 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 12:39:11.645  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-23 12:39:11.645  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.645  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.645  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.645  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.655  3219  7776 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 12:39:11.655  3219  7776 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.655  4715  4715 D BluetoothMap: Proxy object connected
08-23 12:39:11.655  4715  4715 D MapProfile: Bluetooth service connected
08-23 12:39:11.655  4715  4715 D BluetoothMap: getConnectedDevices()
,08-23 12:39:11.655  4715  4723 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-23 12:39:11.655  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:11.655  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 12:39:11.655  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.655  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.655  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.655  4715  4723 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 12:39:11.655  7780  7791 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 12:39:11.655  7780  7791 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 12:39:11.655  4715  4715 D HeadsetProfile: Bluetooth service connected
,08-23 12:39:11.655  1440  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:11.655  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 12:39:11.655  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.655  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 12:39:11.655  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.655  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.655  1440  1454 E BluetoothHeadset: BluetoothHeadset service is binded
08-23 12:39:11.655  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:39:11.655  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 12:39:11.655  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 12:39:11.655  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.655  4715  7774 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:39:11.655  1019  1019 D BluetoothA2dp: Proxy object connected
,08-23 12:39:11.665  4715  7774 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-23 12:39:11.665  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 12:39:11.665  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.665  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:11.665  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.665  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 12:39:11.665  1019  1049 D BluetoothPan: Binding service...
,08-23 12:39:11.665  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 12:39:11.665  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-23 12:39:11.665  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-23 12:39:11.665  4715  4715 D BluetoothA2dp: Proxy object connected
08-23 12:39:11.665  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 12:39:11.665  4715  4715 D A2dpProfile: Bluetooth service connected
08-23 12:39:11.665  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 12:39:11.665  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:11.665  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,08-23 12:39:11.665  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 12:39:11.675  1440  1440 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@18ed1fe2, true
,08-23 12:39:11.675  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-23 12:39:11.675  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 12:39:11.675  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:11.675  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-23 12:39:11.675  1440  1440 D BluetoothHeadset: registerMessageListener
08-23 12:39:11.675  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
08-23 12:39:11.675  1901  1901 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 12:39:11.685  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:39:11.685  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:39:11.685  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:11.685  1019  1453 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-23 12:39:11.685  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 12:39:11.685  1182  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 12:39:11.695  3219  3231 D HeadsetService: registerMessageListener
,08-23 12:39:11.695  3219  3231 D HeadsetService: registerMessageListener
,08-23 12:39:11.695  4715  4715 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:11.695  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-23 12:39:11.695  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-23 12:39:11.695  3219  7825 D HeadsetStateMachine: Disconnected process message: 70
,08-23 12:39:11.695  3219  7825 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@23a1a74f
,08-23 12:39:11.695  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-23 12:39:11.695  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-23 12:39:11.695  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-23 12:39:11.695  4715  4715 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-23 12:39:11.695  4715  4715 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-23 12:39:11.695  4715  4715 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-23 12:39:11.695  4715  4715 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-23 12:39:11.695  3219  7834 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-23 12:39:11.695  3219  7825 D HeadsetStateMachine: Disconnected process message: 9
,08-23 12:39:11.705  3219  7825 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-23 12:39:11.705  3219  7834 D BluetoothSocket: bindListen(): myUserId = 0
,08-23 12:39:11.705  3219  7834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:11.705   284  1017 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-23 12:39:11.705   284  1017 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-23 12:39:11.705   284  1017 V voice   : voice_set_parameters: exit with code(-2)
,08-23 12:39:11.705   284  1017 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-23 12:39:11.705   284  1017 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-23 12:39:11.705   284  1017 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-23 12:39:11.705   284  1017 V audio_hw_primary: adev_set_parameters: exit
,08-23 12:39:11.705  3219  7825 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-23 12:39:11.705  3219  7834 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-23 12:39:11.705  3219  7834 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 12:39:11.705  3219  7834 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 12:39:11.705  3219  7834 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22e87edc
,08-23 12:39:11.705  3219  7834 D BluetoothSocket: channel: 5
,08-23 12:39:11.715  4715  4715 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:39:11.715  1019  1452 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 12:39:11.715  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.715  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.715  1019  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.715  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 12:39:11.715  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:11.725  4715  4715 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:39:11.725  4715  4715 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 12:39:11.725  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 12:39:11.725  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-23 12:39:11.735  3219  3219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d2a2e1e
,08-23 12:39:11.735  3219  3219 D BtConfig.SecureMode: isSecureModeOn:false
,08-23 12:39:11.735  1019  6889 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 12:39:11.735  1019  6889 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-23 12:39:11.735  1019  6889 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:11.735  1019  6889 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:11.735  1019  6889 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 12:39:11.745  1019  1567 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 12:39:11.755  3219  7839 D BluetoothSocket: bindListen(): myUserId = 0
08-23 12:39:11.755  3219  7839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:11.765  3219  7839 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,08-23 12:39:11.765  3219  7839 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 12:39:11.765  3219  7839 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 12:39:11.765  3219  7839 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fecacc8
08-23 12:39:11.765  3219  7839 D BluetoothSocket: channel: 12
08-23 12:39:11.765  3219  7839 I BtOppRfcommListener: Accept thread started.
,08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:12.245  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:12.245  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:12.245  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:12.245  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bea89e1 added. We now have 8 listener(s)
08-23 12:39:12.245  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:12.245  1019  6888 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 12:39:12.245  1019  6888 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 12:39:12.245  1019  6888 D SecContentProvider2: mCursor = null
,08-23 12:39:12.245  1019  6888 D SettingsProvider: name = wifi_on,
08-23 12:39:12.245  1019  6888 D WifiService: setWifiEnabled: false pid=6892, uid=10170
,08-23 12:39:12.255  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-23 12:39:12.255  1019  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 12:39:12.255  1019  1031 D WifiService: setWifiEnabled: true pid=6892, uid=10170
,08-23 12:39:12.255  1019  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 12:39:12.255  1019  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-23 12:39:12.255  1019  1031 D SecContentProvider2: mCursor = null
,08-23 12:39:12.255  1019  1031 W WifiService: Failed getting userId using ActivityManagerNative
08-23 12:39:12.255  1019  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6892, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-23 12:39:12.255  1019  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 12:39:12.255  1019  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 12:39:12.255  1019  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 12:39:12.255  1019  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 12:39:12.255  1019  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 12:39:12.255  1019  1031 D SettingsProvider: name = wifi_on
,08-23 12:39:12.265  1019  1132 E WifiHW  : ##################### set firmware type 0 #####################
,08-23 12:39:12.285  1019  3384 D SSRM:n  : SIOP:: AP = 320,
,08-23 12:39:12.585  1019  1047 D Tethering: interfaceAdded wlan0
,08-23 12:39:12.595  1019  1135 E Tethering: No numeric data
,08-23 12:39:12.595  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:12.595  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:39:12.605  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:12.605  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:39:12.605  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:39:12.605  1182  1182 D HotspotTile: updateTetherState():false, false
,08-23 12:39:12.605  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 12:39:12.605  1019  1135 D Tethering: clearTetheredNotification()
,08-23 12:39:12.605  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 12:39:12.605  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:39:12.605  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:39:12.605  1019  1129 V NetworkStats: performPollLocked() took 9ms
,08-23 12:39:12.605  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:12.615  1019  1135 D Tethering: InitialState.processMessage what=4
,08-23 12:39:12.615  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:12.615  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
08-23 12:39:12.615  1019  1135 E Tethering: No numeric data
,08-23 12:39:12.615  1019  1047 D Tethering: interfaceAdded p2p0
08-23 12:39:12.615  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-23 12:39:12.615  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:39:12.615  1019  1135 D Tethering: clearTetheredNotification(),
08-23 12:39:12.615  1182  1182 D HotspotTile: updateTetherState():false, false
08-23 12:39:12.615  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-23 12:39:12.625  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:39:12.625  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:12.625   279   970 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-23 12:39:12.625   279   970 D SoftapController: Softap fwReload - Ok
08-23 12:39:12.625  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:12.625  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 12:39:12.625  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:39:12.625  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:39:12.625  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 12:39:12.625   279   970 D CommandListener: Setting iface cfg
08-23 12:39:12.625   279   970 D CommandListener: Trying to bring down wlan0
,08-23 12:39:12.635   279   970 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:39:12.635  1019  1129 V NetworkStats: performPollLocked() took 11ms
08-23 12:39:12.635  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:12.635  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:12.635  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:12.635  1019  1132 E WifiHW  : supplicant_name : p2p_supplicant
,08-23 12:39:12.685  7851  7851 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-23 12:39:12.685  7851  7851 I wpa_supplicant: Successfully initialized wpa_supplicant
08-23 12:39:12.685  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-23 12:39:12.695  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-23 12:39:12.695   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7851
08-23 12:39:12.695   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 12:39:12.695  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-23 12:39:12.695  7851  7851 I wpa_supplicant: ssSupport state is = 1,
08-23 12:39:12.695  7851  7851 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-23 12:39:12.695  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-23 12:39:12.695   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7851
08-23 12:39:12.695   385   385 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-23 12:39:12.745  1019  1132 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-23 12:39:12.755  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:39:12.755  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:39:12.755  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 12:39:12.755  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:12.755  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:12.755  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:12.755  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:12.755  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:39:12.755  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-23 12:39:12.755  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 12:39:12.755  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:39:12.755  1182  1182 D HotspotTile: onReceive : 2, 0
,08-23 12:39:12.755  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:39:12.765  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:12.765  1019  1567 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:39:12.765  1019  1567 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:39:12.765  1019  1567 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:12.765  1019  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:12.765  1019  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:39:12.765  1628  1628 I Hs20UtilService: Starting #19
08-23 12:39:12.765  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:39:12.775  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 12:39:12.775  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 12:39:12.775  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
08-23 12:39:12.775  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:39:12.865   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-23 12:39:12.865  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-23 12:39:12.905  7851  7851 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 12:39:12.905  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 12:39:12.915  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-23 12:39:12.915   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7851
08-23 12:39:12.915   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-23 12:39:12.915  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-23 12:39:12.915  7851  7851 I wpa_supplicant: ssSupport state is = 1
08-23 12:39:12.915  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-23 12:39:12.915  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 12:39:12.915  7851  7851 E wpa_supplicant: SIM READ ERROR
08-23 12:39:12.915  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-23 12:39:12.925  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 12:39:12.925  7851  7851 E wpa_supplicant: SIM READ ERROR
08-23 12:39:12.925  7851  7851 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 12:39:12.925  7851  7851 I wpa_supplicant: wpa_default_ap_write_once
08-23 12:39:12.925  7851  7851 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-23 12:39:12.925  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 12:39:12.925  7851  7851 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-23 12:39:12.925  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-23 12:39:12.925  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-23 12:39:12.925  7851  7851 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-23 12:39:12.925  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 12:39:12.925  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:39:12.925  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:39:13.015  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-23 12:39:13.155  7851  7851 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-23 12:39:13.155  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-23 12:39:13.165  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-23 12:39:13.165   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7851,
08-23 12:39:13.165   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-23 12:39:13.175  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-23 12:39:13.175  7851  7851 I wpa_supplicant: ssSupport state is = 1
,08-23 12:39:13.175  7851  7851 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 12:39:13.175  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 12:39:13.185  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-23 12:39:13.185   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7851,
08-23 12:39:13.185   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-23 12:39:13.185  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-23 12:39:13.185  7851  7851 I wpa_supplicant: ssSupport state is = 1
08-23 12:39:13.185  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 12:39:13.195  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 12:39:13.185  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 12:39:13.185  7851  7851 E wpa_supplicant: SIM READ ERROR
08-23 12:39:13.185  7851  7851 I wpa_supplicant: wpa_default_ap_write_once
08-23 12:39:13.185  7851  7851 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 12:39:13.185  7851  7851 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 12:39:13.185  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:39:13.185  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:39:13.195  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 12:39:13.195  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:39:13.195  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 12:39:13.235  7851  7851 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-23 12:39:13.235  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-23 12:39:13.335  7851  7851 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-23 12:39:13.335  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-23 12:39:13.335  7851  7851 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 12:39:13.345   289   289 E SMD     : DCD OFF,
08-23 12:39:13.345  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-23 12:39:13.345  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-23 12:39:13.345  7851  7851 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-23 12:39:13.345  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-23 12:39:13.345  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 12:39:13.345  7851  7851 E wpa_supplicant: SIM READ ERROR,
08-23 12:39:13.355  7851  7851 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 12:39:13.375  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-23 12:39:13.385  7851  7851 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-23 12:39:13.395  1019  1132 D WifiConfigStore: Loading config and enabling all networks 
,08-23 12:39:13.395  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-23 12:39:13.395  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 12:39:13.395  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:39:13.395  1182  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 12:39:13.395  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:39:13.405  1182  1182 D HotspotTile: onReceive : 3, 0
08-23 12:39:13.395  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:13.405  1019  1567 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:39:13.395  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:13.405  1019  1567 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 12:39:13.395  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:13.395  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:13.395  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 12:39:13.395  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-23 12:39:13.405  4715  4715 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-23 12:39:13.405  1019  1567 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:13.405  1019  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:13.405  1019  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:13.405  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:13.405  1628  1628 I Hs20UtilService: Starting #20
08-23 12:39:13.405  1628  1655 I Hs20UtilService: Message received 5011
,08-23 12:39:13.405  1019  1132 E WifiConfigStore: Not a HS20
,08-23 12:39:13.405  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:13.415  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 12:39:13.415  7370  7370 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 12:39:13.415  7370  7370 D SecurityLogAgent: StateMachine : Current State = 1
08-23 12:39:13.415  7370  7370 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 12:39:13.415  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-23 12:39:13.415  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-23 12:39:13.415  7851  7851 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-23 12:39:13.415  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-23 12:39:13.415  7851  7851 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 12:39:13.415  7851  7851 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 12:39:13.415  7851  7851 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-23 12:39:13.415  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-23 12:39:13.415  7851  7851 I wpa_supplicant: First Scan Start
08-23 12:39:13.415  7851  7851 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 12:39:13.425  1019  1132 D WifiNative-wlan0: Setting external_sim to 1,
08-23 12:39:13.425  1019  1132 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 12:39:13.425  1019  1132 I WifiNative-HAL: startHal
08-23 12:39:13.425  1019  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9f3f588c
08-23 12:39:13.425  1019  1132 I WifiNative-HAL: Could not start hal
08-23 12:39:13.425  7347  7347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:39:13.425  1019  1132 E WifiNative-wlan0: do suspend true
,08-23 12:39:13.435  1019  1131 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-23 12:39:13.435  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-23 12:39:13.435  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 12:39:13.435  1019  1155 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:39:13.435  1019  1155 I WifiNative-HAL: startHal
08-23 12:39:13.435  1019  1155 E wifi    : getStaticLongField sWifiHalHandle 0x9e3b59bc
08-23 12:39:13.435  1019  1155 I WifiNative-HAL: Could not start hal
08-23 12:39:13.435  1019  1155 E WifiScanningService: could not start HAL
,08-23 12:39:13.435  1019  1019 D RttService: SCAN_AVAILABLE : 3
08-23 12:39:13.435   279   970 D CommandListener: Setting iface cfg
08-23 12:39:13.435   279   970 D CommandListener: Trying to bring up p2p0
,08-23 12:39:13.435  1019  1156 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:39:13.435  1019  1131 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 12:39:13.435  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-23 12:39:13.435  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 12:39:13.435  1019  1132 E WifiNative-wlan0: invaild command id : 215
08-23 12:39:13.435  1019  1131 D WifiP2pService: P2pEnablingState
08-23 12:39:13.435  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
08-23 12:39:13.435  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 12:39:13.435  1019  1131 D WifiP2pService: P2pEnablingState{ what=147457 }
08-23 12:39:13.435  1019  1132 E WifiNative-wlan0: invaild command id : 215
,08-23 12:39:13.435  1019  1131 D WifiP2pService: P2p socket connection successful
08-23 12:39:13.435  1019  1131 D WifiP2pService: P2pEnabledState
,08-23 12:39:13.435  7851  7851 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-23 12:39:13.435  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-23 12:39:13.435  1019  1134 E ConnectivityService: updateNetworkInfo(),
08-23 12:39:13.435  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 12:39:13.435  7851  7851 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-23 12:39:13.445  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-23 12:39:13.445  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 12:39:13.445  1019  1050 D WifiDisplayController: disconnect
08-23 12:39:13.445  1019  1050 D WifiDisplayController: updateConnection
08-23 12:39:13.445  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 12:39:13.445  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 12:39:13.445  7851  7851 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-23 12:39:13.445  1019  1132 E WifiStateMachine: Failed to set frequency band 0
,08-23 12:39:13.445  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:39:13.445  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:39:13.445  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress
,08-23 12:39:13.445  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-23 12:39:13.445  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 12:39:13.445  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-23 12:39:13.445  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 12:39:13.445  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 12:39:13.445  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 12:39:13.445  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 12:39:13.445  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:39:13.445  1019  1132 D SecContentProvider2: mCursor = null
08-23 12:39:13.445  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 12:39:13.445  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:39:13.455  1019  1452 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:39:13.455  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:39:13.455  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-23 12:39:13.455  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 12:39:13.455  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 12:39:13.455  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-23 12:39:13.455  1019  1131 D WifiP2pService: DeviceAddress: 0a:75:42
,08-23 12:39:13.455  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  secondary type: null
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  wps: 0
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  grpcapab: 0
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  devcapab: 0
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  status: 3
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  wfdInfo: null
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  groupownerAddress: null
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  GOdeviceName: null
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  interfaceAddress: 
08-23 12:39:13.455  1019  1050 D WifiDisplayController:  SConnectInfo : null
,08-23 12:39:13.455  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:39:13.455  7697  7697 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 12:39:13.455  7697  7697 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 12:39:13.465  7332  7332 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 12:39:13.475  1019  1131 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-23 12:39:13.475  1019  1131 D WifiP2pService: InactiveState
,08-23 12:39:13.475  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,08-23 12:39:13.475  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 12:39:13.475  7851  7851 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 12:39:13.475  1019  1131 D WifiP2pService: InactiveState{ what=143376 },
08-23 12:39:13.475  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 12:39:13.605  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-23 12:39:13.605  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-23 12:39:13.605  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:14.275  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:14.275  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:14.275  6892  7141 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-23 12:39:14.275  6892  7141 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 12:39:14.285  6892  7141 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fa940fc Bundle[{}]
,08-23 12:39:14.285  6892  7141 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 12:39:14.285  6892  7141 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 12:39:14.285  6892  7141 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 12:39:14.285  6892  7141 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 12:39:14.285  6892  7141 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 12:39:14.285  6892  7141 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 12:39:14.295  6892  7141 I System.out: Running OutgoingSocketThread
,08-23 12:39:14.295  6892  7860 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1395)
,08-23 12:39:14.295  6892  7860 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56029
,08-23 12:39:14.295  6892  7860 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 12:39:14.615  7851  7851 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
08-23 12:39:14.615  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-23 12:39:14.615  7851  7851 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-23 12:39:14.615  7851  7851 I wpa_supplicant: Trying to associate with  'G700'
08-23 12:39:14.615  7851  7851 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-23 12:39:14.615  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-23 12:39:14.615  1019  7857 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-23 12:39:14.625  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 12:39:14.635  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:39:14.725  7851  7851 E wpa_supplicant: Cmd 35605 not handled
,08-23 12:39:14.725  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 12:39:14.725  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-23 12:39:14.725  7851  7851 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-23 12:39:14.725  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:39:14.725  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:39:14.725  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 12:39:14.725  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:39:14.725  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 12:39:14.725  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-23 12:39:14.725  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-23 12:39:14.725  7851  7851 I wpa_supplicant: Associated with F4.99.3E
08-23 12:39:14.725  7851  7851 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 12:39:14.725  7851  7851 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-23 12:39:14.725  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-23 12:39:14.725  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 12:39:14.725  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-23 12:39:14.725  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 12:39:14.725  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-23 12:39:14.725  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:39:14.725  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:39:14.735  7851  7851 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-23 12:39:14.735  1019  1135 E Tethering: No numeric data
08-23 12:39:14.735  7851  7851 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-23 12:39:14.735  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 12:39:14.735  1019  1135 D Tethering: clearTetheredNotification()
08-23 12:39:14.735  7851  7851 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-23 12:39:14.735  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-23 12:39:14.735  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:14.735  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:39:14.735  7851  7851 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 12:39:14.735  7851  7851 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-23 12:39:14.735  7851  7851 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-23 12:39:14.735  7851  7851 I wpa_supplicant: Blacklist: Clear (temp) 
08-23 12:39:14.735  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-23 12:39:14.735  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:14.735  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 12:39:14.735  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:39:14.735  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 12:39:14.735  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 12:39:14.735  1182  1182 D HotspotTile: updateTetherState():false, false
08-23 12:39:14.735  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
,08-23 12:39:14.735  1019  1129 V NetworkStats: performPollLocked() took 5ms
08-23 12:39:14.735  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:14.735  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:14.735  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:14.735  1019  1132 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-23 12:39:14.745  1019  1132 E WifiConfigStore: setLastSelectedConfiguration -1
,08-23 12:39:14.745  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:39:14.745  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:39:14.745  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:39:14.745  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:14.745  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:14.755  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:14.755  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:14.755  1019  1132 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-23 12:39:14.755  1019  1134 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-23 12:39:14.755  1019  1134 E ConnectivityService: updateNetworkInfo()
08-23 12:39:14.755  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 12:39:14.755  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:39:14.755  1019  1512 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 12:39:14.755  1019  1512 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:39:14.755  1019  1512 W ActivityManager: userId = 0, bbcId = -10000,
08-23 12:39:14.755  1019  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:14.755  1019  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:39:14.765  1628  1628 I Hs20UtilService: Starting #21
,08-23 12:39:14.765  1628  1655 I Hs20UtilService: Message received 5007
,08-23 12:39:14.765  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:39:14.765  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 12:39:14.765  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 12:39:14.765  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 12:39:14.765  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 12:39:14.775  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 12:39:14.775   279   970 D CommandListener: Setting iface cfg
,08-23 12:39:14.775  4715  4715 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 12:39:14.775  1019  1132 E WifiStateMachine: Start Dhcp Watchdog 3
,08-23 12:39:14.775  4715  4804 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 12:39:14.775  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:39:14.775  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:39:14.785  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 12:39:14.785  1019  1132 D SecContentProvider2: mCursor = null
,08-23 12:39:14.795  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:39:14.795  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:39:14.795  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 12:39:14.795  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:14.795  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:14.795  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:14.795  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:14.805  1019  1132 E WifiNative-wlan0: do suspend false
,08-23 12:39:14.805  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,08-23 12:39:14.805  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 12:39:14.805  1019  1132 D SecContentProvider2: mCursor = null
08-23 12:39:14.805  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 12:39:15.025  7863  7863 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 12:39:15.025  7863  7863 I dhcpcd  : version 5.5.6 starting,
,08-23 12:39:15.035  7863  7863 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-23 12:39:15.085  7863  7863 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-23 12:39:15.085  7863  7863 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-23 12:39:15.085  7863  7863 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-23 12:39:15.085  7863  7863 I dhcpcd  : bssid match
08-23 12:39:15.085  7863  7863 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-23 12:39:15.185  7863  7863 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-23 12:39:15.305  6892  7141 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1396),
08-23 12:39:15.305  6892  7141 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1396)
08-23 12:39:15.305  6892  7141 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1401)
08-23 12:39:15.305  6892  7141 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-23 12:39:15.305  6892  7141 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1402)
,08-23 12:39:15.305  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-23 12:39:15.305  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de57306 added. We now have 2 listener(s),
,08-23 12:39:15.305  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-23 12:39:15.305  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:39:15.305  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:15.315  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:15.315  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1061fdc7 added. We now have 9 listener(s)
,08-23 12:39:15.315  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:15.315  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:15.315  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:15.325  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:15.325  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:15.325  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:39:15.325  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:15.325  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:15.335  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.335  7863  7863 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-23 12:39:15.335  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24a4e31d added. We now have 3 listener(s)
,08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.335  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.335  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd5b992 added. We now have 10 listener(s)
08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.335  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:39:15.335  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:39:15.335  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:39:15.335  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.335  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:39:15.335  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:15.335  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de57306 removed from the list
08-23 12:39:15.335  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.335  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1061fdc7 removed from the list
08-23 12:39:15.335  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.335  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.335  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.335  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.335  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.335  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1061fdc7 not in the list
08-23 12:39:15.335  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.335  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:15.345  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.345  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.345  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.345  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd5b992 removed from the list
08-23 12:39:15.345  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-23 12:39:15.345  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:39:15.345  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.345  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-23 12:39:15.345  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24a4e31d removed from the list
,08-23 12:39:15.345  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.345  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e76af63 added. We now have 2 listener(s)
08-23 12:39:15.345  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.345  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.345  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.345  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.345  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8b0760 added. We now have 9 listener(s)
,08-23 12:39:15.345  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:15.345  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:15.355  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:15.365  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:15.365  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:15.365  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:39:15.365  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.365  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d11dcde added. We now have 3 listener(s)
08-23 12:39:15.365  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:15.365  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:15.365  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.365  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.365  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.365  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.375  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39adebf added. We now have 10 listener(s)
08-23 12:39:15.375  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.375  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:15.375  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 12:39:15.375  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:39:15.375  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:15.375  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 12:39:15.395  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:39:15.405  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:39:15.405  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:39:15.405  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-23 12:39:15.405  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:39:15.405  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 12:39:15.415  3219  3381 D BtGatt.GattService: registerClient() - UUID=f2203c94-7204-43d5-87fb-b601306a9d95
,08-23 12:39:15.425  1019  1567 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 12:39:15.425  1019  1567 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 12:39:15.425  1019  1567 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 12:39:15.425  1019  1567 D BatteryService: stay LED for charging
08-23 12:39:15.425  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 12:39:15.435  1019  1019 I MotionRecognitionService: Plugged
08-23 12:39:15.435  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 12:39:15.435  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 12:39:15.435  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 12:39:15.435  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 12:39:15.435  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-23 12:39:15.445  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 12:39:15.445  3219  7825 D HeadsetStateMachine: Disconnected process message: 10
,08-23 12:39:15.455  3219  3293 D BtGatt.GattService: onClientRegistered() - UUID=f2203c94-7204-43d5-87fb-b601306a9d95, clientIf=6,
,08-23 12:39:15.455  6892  7696 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 12:39:15.455  3219  3368 D BtGatt.GattService: start scan with filters,
,08-23 12:39:15.465  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 12:39:15.465  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 12:39:15.465  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:39:15.465  1182  1182 D SViewCoverView: level :99 plugged : 2
08-23 12:39:15.465  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 12:39:15.465  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 12:39:15.465  3219  3371 D BtGatt.ScanManager: handling starting scan
,08-23 12:39:15.465  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
08-23 12:39:15.465  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
08-23 12:39:15.465  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-23 12:39:15.465  3219  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 12:39:15.465  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.465  3219  3371 D BtGatt.ScanManager: allow scan with filters
08-23 12:39:15.465  3219  3371 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 12:39:15.465  3219  3371 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-23 12:39:15.475  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 12:39:15.475  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.475  3219  3371 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:39:15.475  3219  3371 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 12:39:15.475  3219  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-23 12:39:15.475  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.485  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:15.485  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 12:39:15.485  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.485  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 12:39:15.485  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:15.485  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:39:15.495  6892  7141 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 12:39:15.495  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:15.495  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 12:39:15.495  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.495  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 12:39:15.495  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:39:15.495  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:39:15.495  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:39:15.495  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:39:15.495  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:39:15.495  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:39:15.495  3219  7776 D BtGatt.GattService: stopScan() - queue size =1
,08-23 12:39:15.495  3219  3371 D BtGatt.ScanManager: filter size is 1
08-23 12:39:15.495  3219  3371 D BtGatt.ScanManager: delete FilterIndex - 6
,08-23 12:39:15.495  3219  3229 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-23 12:39:15.495  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-23 12:39:15.495  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.495  3219  3371 D BtGatt.ScanManager: stopping BLe Batch
,08-23 12:39:15.505  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-23 12:39:15.505  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:39:15.505  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:39:15.505  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:39:15.505  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 12:39:15.505  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-23 12:39:15.505  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.505  3219  3371 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 12:39:15.505  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:15.505  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 12:39:15.505  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:39:15.505  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:39:15.505  3219  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 12:39:15.505  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.505  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:39:15.515  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:15.515  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:15.515  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:15.525  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:39:15.525  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:15.525  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 12:39:15.525  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.525  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.525  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:39:15.525  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:15.525  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e76af63 removed from the list
08-23 12:39:15.525  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.525  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8b0760 removed from the list
08-23 12:39:15.525  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:39:15.525  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:15.525  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-23 12:39:15.525  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.535  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8b0760 not in the list
,08-23 12:39:15.535  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.535  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.535  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39adebf removed from the list
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.535  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.535  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:15.535  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d11dcde removed from the list
08-23 12:39:15.535  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 12:39:15.535  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a8a7db added. We now have 2 listener(s)
,08-23 12:39:15.535  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.535  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.535  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.535  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.535  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23566278 added. We now have 9 listener(s)
08-23 12:39:15.535  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.535  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:15.545  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:15.545  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:15.545  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:15.545  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:39:15.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@976a9b6 added. We now have 3 listener(s)
,08-23 12:39:15.555  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:15.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.555  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27ffe6b7 added. We now have 10 listener(s)
08-23 12:39:15.555  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.555  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:15.555  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:15.555  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:39:15.555  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:39:15.555  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:15.555  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 12:39:15.555  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:15.565  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:39:15.565  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:39:15.575  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:39:15.575  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 12:39:15.575  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-23 12:39:15.575  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-23 12:39:15.585  3219  3368 D BtGatt.GattService: registerClient() - UUID=16bafec0-e063-43b0-bb07-79239f41b43b
,08-23 12:39:15.625  1019  1132 E WifiNative-wlan0: do suspend true,
,08-23 12:39:15.625  3219  3293 D BtGatt.GattService: onClientRegistered() - UUID=16bafec0-e063-43b0-bb07-79239f41b43b, clientIf=6,
08-23 12:39:15.625  6892  7696 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-23 12:39:15.625  3219  7776 D BtGatt.GattService: start scan with filters
08-23 12:39:15.635  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 12:39:15.635  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:39:15.635  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-23 12:39:15.635  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:39:15.635  3219  3371 D BtGatt.ScanManager: handling starting scan
,08-23 12:39:15.635  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:15.635  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:15.635  3219  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,08-23 12:39:15.645  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 12:39:15.645  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.645  3219  3371 D BtGatt.ScanManager: allow scan with filters,
08-23 12:39:15.645  3219  3371 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
08-23 12:39:15.645  3219  3371 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
08-23 12:39:15.645  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 12:39:15.645  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.645  3219  3371 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:39:15.645  3219  3371 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 12:39:15.645  3219  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 12:39:15.645  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.645  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 12:39:15.645  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.655  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,08-23 12:39:15.655  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 12:39:15.655  1019  1132 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 12:39:15.655  1019  1132 E WifiStateMachine: VerifyingLinkState enter
,08-23 12:39:15.655  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:39:15.665  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:39:15.665  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 12:39:15.665  1019  1134 E ConnectivityService: updateNetworkInfo()
,08-23 12:39:15.665  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:39:15.665  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:15.665  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:15.665  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.665  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:15.675  1019  1134 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-23 12:39:15.675  1019  1134 D ConnectivityService: Adding iface wlan0 to network 504
08-23 12:39:15.675  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:15.675  6892  7141 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-23 12:39:15.675  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:39:15.675  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:15.675  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:39:15.675  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.675  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.675  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 12:39:15.675  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:15.675  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a8a7db removed from the list
08-23 12:39:15.675  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.675  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23566278 removed from the list
08-23 12:39:15.675  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:39:15.675  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:39:15.685  1019  1149 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-23 12:39:15.685  1019  1149 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-23 12:39:15.685  1019  1149 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-23 12:39:15.685  1019  1149 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-23 12:39:15.685  1019  1149 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-23 12:39:15.695  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-23 12:39:15.695  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 12:39:15.695  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:39:15.695  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.695  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.695  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:15.695  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.695  1019  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:39:15.695  1019  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:39:15.695  1019  1132 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-23 12:39:15.695  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.695  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 12:39:15.695  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.705  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:39:15.705  1019  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:15.705  1019  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:39:15.705  1019  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 12:39:15.705  1628  1628 I Hs20UtilService: Starting #22,
,08-23 12:39:15.705  1628  1655 I Hs20UtilService: Message received 5007
08-23 12:39:15.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.705  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23566278 not in the list
08-23 12:39:15.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:39:15.705  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:39:15.705  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:39:15.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:39:15.705  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 12:39:15.705  3219  7776 D BtGatt.GattService: stopScan() - queue size =1
08-23 12:39:15.705  3219  3371 D BtGatt.ScanManager: filter size is 1
08-23 12:39:15.705  3219  3371 D BtGatt.ScanManager: delete FilterIndex - 7
08-23 12:39:15.705  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 12:39:15.705  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.705  3219  3231 D BtGatt.GattService: unregisterClient() - clientIf=6
08-23 12:39:15.705  3219  3371 D BtGatt.ScanManager: stopping BLe Batch
08-23 12:39:15.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:39:15.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:39:15.715  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:39:15.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:39:15.715  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:39:15.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:15.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 12:39:15.715  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:39:15.715  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:39:15.715  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 12:39:15.725  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 12:39:15.725  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.725  3219  3371 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 12:39:15.725  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 12:39:15.725  3219  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 12:39:15.725  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.725  4715  4715 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-23 12:39:15.725  1019  1132 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 12:39:15.725  1019  1134 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-23 12:39:15.725  1019  1132 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 12:39:15.725  1019  1134 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-23 12:39:15.725  1019  1134 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-23 12:39:15.725  1019  1134 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 12:39:15.725  1019  1134 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-23 12:39:15.725  1019  1134 D ConnectivityService: LTETest block dns file not exists
,08-23 12:39:15.735  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 12:39:15.735  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
08-23 12:39:15.735  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
,08-23 12:39:15.735  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:39:15.735  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:39:15.735  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 12:39:15.735  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.735  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.735  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.735  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:15.745  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:39:15.745  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-23 12:39:15.745  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.745  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.745  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.745  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.745  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 12:39:15.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.745  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27ffe6b7 removed from the list
08-23 12:39:15.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.745  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.745  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.745  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 12:39:15.745  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@976a9b6 removed from the list
08-23 12:39:15.745  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.745  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c223753 added. We now have 2 listener(s)
08-23 12:39:15.745  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:15.745  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:15.745  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:15.745  1019  1134 V NetworkStats: updateIfacesLocked()
08-23 12:39:15.745  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.745  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
,08-23 12:39:15.745  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:15.745  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 12:39:15.755  1019  1134 V NetworkStats: performPollLocked() took 6ms,
08-23 12:39:15.755  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit,
08-23 12:39:15.755  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.755  1019  1134 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-23 12:39:15.755  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.755  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 12:39:15.755  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.755  1019  1134 V NetworkStats: updateIfacesLocked()
08-23 12:39:15.755  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.755  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:39:15.755  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249f0890 added. We now have 9 listener(s)
08-23 12:39:15.755  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.755  1019  1134 E ConnectivityService: updateNetworkInfo()
08-23 12:39:15.755  1019  1134 E ConnectivityService: updateNetworkInfo()
08-23 12:39:15.755  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:15.755  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.755  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:15.765  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:15.765  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-23 12:39:15.765  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:15.765  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:15.765  1019  1134 V NetworkStats: performPollLocked() took 8ms
08-23 12:39:15.765  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:15.765  1019  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:39:15.765  1019  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:39:15.765  1019  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:39:15.765  1019  1134 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-23 12:39:15.765  1019  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-23 12:39:15.765  1019  1134 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-23 12:39:15.765  1019  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 12:39:15.765  1019  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-23 12:39:15.765  1019  7861 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:15.775  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:39:15.775  1019  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:15.775  1019  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:15.775  1019  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 12:39:15.775  1019  1134 D ConnectivityService:    accepting network in place of null
08-23 12:39:15.775   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 12:39:15.775   279   966 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-23 12:39:15.775  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.775  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.775  1019  1131 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 12:39:15.775  1019  1132 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-23 12:39:15.775  1471  1471 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-23 12:39:15.775  1471  1471 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:39:15.775  1628  1628 I Hs20UtilService: Starting #23
08-23 12:39:15.775  1019  1134 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-23 12:39:15.775  1019  1134 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-23 12:39:15.775  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 12:39:15.775  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:15.775  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:39:15.775  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.775  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5d398e added. We now have 3 listener(s)
,08-23 12:39:15.775  1628  1655 I Hs20UtilService: Message received 5007
,08-23 12:39:15.775  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 12:39:15.775  4715  4715 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 12:39:15.785  1019  1134 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-23 12:39:15.785  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-23 12:39:15.785  1019  1135 D Tethering: MasterInitialState.processMessage what=3
,08-23 12:39:15.785  1019  1134 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:15.785  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:39:15.785  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:15.785  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED,
08-23 12:39:15.785  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-23 12:39:15.785  1182  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 12:39:15.785  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.785  1019  1129 V NetworkStats: updateIfacesLocked()
08-23 12:39:15.785  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.785  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:39:15.785  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.785  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.785  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.785  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40ef5af added. We now have 10 listener(s)
08-23 12:39:15.785  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.785  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:15.785  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:39:15.785  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:39:15.785  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:15.785  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:39:15.785  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:15.785  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 12:39:15.795  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:15.795  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 12:39:15.795  4715  4715 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-23 12:39:15.795  1019  1129 V NetworkStats: performPollLocked() took 3ms
08-23 12:39:15.795  4715  4715 I NearbySettings: MountReceiver.onReceive - Keep current state
08-23 12:39:15.795  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:15.795  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.795  1019  1130 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-23 12:39:15.795  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.795  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.795  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:15.795  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-23 12:39:15.795  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 12:39:15.795  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 12:39:15.795  1182  1182 D StatusBar.NetworkController: updateDataNetType()
,08-23 12:39:15.795  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:39:15.795  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:39:15.805  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.805  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.805  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:39:15.805  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:15.805  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:15.815  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 12:39:15.815  1019  1567 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 12:39:15.815  1019  1567 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 12:39:15.815  1019  1567 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:15.815  1019  1567 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:15.815  1019  1567 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 12:39:15.815  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:39:15.815  1628  1628 I Hs20UtilService: Starting #24
,08-23 12:39:15.815  1628  1655 I Hs20UtilService: Message received 5007
,08-23 12:39:15.815  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-23 12:39:15.815  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:39:15.815  6892  7141 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 12:39:15.815  4715  4715 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 12:39:15.815  4715  4715 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-23 12:39:15.825  3219  3231 D BtGatt.GattService: registerClient() - UUID=a2ce4f9e-10b1-4e25-b3f1-929fd899110b
,08-23 12:39:15.825  1019  1031 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-23 12:39:15.825  1019  1566 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-23 12:39:15.825  1019  1566 D SecContentProvider2: mCursor = null
,08-23 12:39:15.825  1019  1032 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-23 12:39:15.825  1019  1032 D SecContentProvider2: mCursor = null
,08-23 12:39:15.835  1019  1486 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-23 12:39:15.835  1019  1486 D SecContentProvider2: mCursor = null
,08-23 12:39:15.835  1019  1559 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-23 12:39:15.835  1019  1559 D SecContentProvider2: mCursor = null
,08-23 12:39:15.835  1019  6889 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-23 12:39:15.835  1019  6889 D SecContentProvider2: mCursor = null
,08-23 12:39:15.835  1019  6888 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-23 12:39:15.835  1019  6888 D SecContentProvider2: mCursor = null
,08-23 12:39:15.865  1019  7861 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 12:39:15.865  3219  3293 D BtGatt.GattService: onClientRegistered() - UUID=a2ce4f9e-10b1-4e25-b3f1-929fd899110b, clientIf=6,
08-23 12:39:15.865  6892  6904 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 12:39:15.865  3219  3229 D BtGatt.GattService: start scan with filters
,08-23 12:39:15.865   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-23 12:39:15.865  3219  3371 D BtGatt.ScanManager: handling starting scan
,08-23 12:39:15.865  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:39:15.865  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 12:39:15.865  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 12:39:15.865  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:39:15.875  3219  3293 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 12:39:15.875  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.875  3219  3371 D BtGatt.ScanManager: allow scan with filters
,08-23 12:39:15.875  3219  3371 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 12:39:15.875  3219  3371 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-23 12:39:15.875  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:39:15.875  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 12:39:15.875  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:15.875  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-23 12:39:15.875  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.875  3219  3371 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:39:15.875  3219  3371 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 12:39:15.875  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:39:15.875  3219  3293 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 12:39:15.875  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.885  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 12:39:15.885  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 12:39:15.885  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:39:15.885  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:15.885  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:39:15.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.885  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.885  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 12:39:15.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:15.885  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c223753 removed from the list
08-23 12:39:15.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.885  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249f0890 removed from the list
08-23 12:39:15.885  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:39:15.885  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:15.885  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.885  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 12:39:15.885  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.885  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:39:15.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:39:15.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:39:15.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.885  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249f0890 not in the list
,08-23 12:39:15.885  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 12:39:15.895  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:39:15.895  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:39:15.895  1019  1508 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,08-23 12:39:15.895  3219  7776 D BtGatt.GattService: stopScan() - queue size =1
,08-23 12:39:15.895  3219  3371 D BtGatt.ScanManager: filter size is 1,
08-23 12:39:15.895  3219  3371 D BtGatt.ScanManager: delete FilterIndex - 8,
08-23 12:39:15.895  3219  3231 D BtGatt.GattService: unregisterClient() - clientIf=6
08-23 12:39:15.895  3219  3293 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-23 12:39:15.895  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:39:15.895  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 12:39:15.895  3219  3371 D BtGatt.ScanManager: stopping BLe Batch
08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:39:15.895  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:39:15.895  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 12:39:15.895  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:15.895  3219  3293 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-23 12:39:15.895  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.905  3219  3371 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 12:39:15.905  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-23 12:39:15.905  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.905  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:15.905  6892  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-23 12:39:15.905  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.905  6892  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:15.905  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40ef5af removed from the list
08-23 12:39:15.905  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.905  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.905  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.905  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 12:39:15.905  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5d398e removed from the list
08-23 12:39:15.905  3219  3293 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 12:39:15.905  3219  3293 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 12:39:15.905  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.905  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5f3dcb added. We now have 2 listener(s)
,08-23 12:39:15.905  1182  1182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 12:39:15.905  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.905  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.905  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.905  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:15.905  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@226359a8 added. We now have 9 listener(s)
08-23 12:39:15.905  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.905  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:39:15.905  1019  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 10:39:16 GMT], X-Android-Received-Millis=[1471948755925], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471948755897]}
08-23 12:39:15.905  1019  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 12:39:15.905  1019  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-23 12:39:15.915  1019  1134 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-23 12:39:15.915  1019  1134 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-23 12:39:15.915  1019  1134 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-23 12:39:15.915  1019  1134 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-23 12:39:15.915  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 12:39:15.915  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:15.915  1182  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:15.925  6892  7141 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:39:15.925  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-23 12:39:15.925  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 12:39:15.925  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 12:39:15.925  1182  1182 D StatusBar.NetworkController: updateDataNetType()
08-23 12:39:15.925  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-23 12:39:15.935  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-23 12:39:15.935  6892  7141 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-23 12:39:15.935  6892  7141 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:39:15.935  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:15.935  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edaec66 added. We now have 3 listener(s)
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 12:39:15.935  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.935  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 12:39:15.935  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:15.945  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:15.945  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:15.945  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3421eba7 added. We now have 10 listener(s)
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:15.945  6892  7141 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.945  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:15.945  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b5f3dcb removed from the list
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.945  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@226359a8 removed from the list
08-23 12:39:15.945  6892  7141 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.945  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.945  6892  7141 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@226359a8 not in the list
08-23 12:39:15.945  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:15.945  6892  7141 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3421eba7 removed from the list
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:15.945  6892  7141 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:15.945  6892  7141 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:15.945  6892  7141 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:15.945  6892  7141 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3edaec66 removed from the list
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 12:39:15.945  6892  7141 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:15.955  6892  7901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1409, name: My test thread name)
08-23 12:39:15.955  6892  7901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1409, thread name: My test thread name)
08-23 12:39:15.955  6892  7901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1409, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 12:39:15.965  6892  7902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1411, name: My test thread name)
08-23 12:39:15.965  6892  7902 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1411, thread name: My test thread name)
08-23 12:39:15.965  6892  7902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1411, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 12:39:15.965  6892  7141 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-23 12:39:15.965  6892  7141 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 12:39:15.965  6892  7141 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-23 12:39:15.965  6892  7141 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-23 12:39:15.965  6892  7141 D com.test.thalitest.ThaliTestRunner: Total duration: 23416 ms
08-23 12:39:15.965  6892  7141 I jxcore-log: Total number of executed tests:  80
08-23 12:39:15.965  6892  7141 I jxcore-log: 
08-23 12:39:15.965  6892  7141 I jxcore-log: Number of passed tests:  80
08-23 12:39:15.965  6892  7141 I jxcore-log: 
08-23 12:39:15.965  6892  7141 I jxcore-log: Number of failed tests:  0
08-23 12:39:15.965  6892  7141 I jxcore-log: 
08-23 12:39:15.965  6892  7141 I jxcore-log: Number of ignored tests:  0
08-23 12:39:15.965  6892  7141 I jxcore-log: 
08-23 12:39:15.965  6892  7141 I jxcore-log: Total duration:  23416
08-23 12:39:15.965  6892  7141 I jxcore-log: 
08-23 12:39:15.965  6892  7141 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 12:39:15.965  6892  7141 I jxcore-log: 
08-23 12:39:15.975  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:15.975  6892  7141 I jxcore-log: 
08-23 12:39:15.985  6892  6892 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 12:39:15.985  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:15.985  6892  7141 I jxcore-log: 
,08-23 12:39:15.985  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:15.985  6892  7141 I jxcore-log: 
08-23 12:39:15.985  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:15.985  6892  7141 I jxcore-log: 
08-23 12:39:15.985  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:15.985  6892  7141 I jxcore-log: 
08-23 12:39:15.985  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:15.985  6892  7141 I jxcore-log: 
08-23 12:39:15.995  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:15.995  6892  7141 I jxcore-log: 
08-23 12:39:15.995  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:15.995  6892  7141 I jxcore-log: 
08-23 12:39:15.995  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:15.995  6892  7141 I jxcore-log: 
08-23 12:39:15.995  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:15.995  6892  7141 I jxcore-log: 
08-23 12:39:15.995  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:39:15.995  6892  7141 I jxcore-log: 
08-23 12:39:15.995  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:39:15.995  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.005  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:39:16.005  6892  7141 I jxcore-log: 
08-23 12:39:16.015  6892  6892 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-23 12:39:16.015  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:16.015  6892  7141 I jxcore-log: 
08-23 12:39:16.015  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:16.015  6892  7141 I jxcore-log: 
08-23 12:39:16.015  6892  6912 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e2caea9, channel: -1, state: CLOSED
,08-23 12:39:16.245  6892  6892 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 12:39:16.245  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:16.245  6892  7141 I jxcore-log: 
,08-23 12:39:16.255  7903  7903 D AndroidRuntime: 
08-23 12:39:16.255  7903  7903 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 12:39:16.265  7903  7903 D AndroidRuntime: CheckJNI is OFF,
08-23 12:39:16.265  7903  7903 D AndroidRuntime: readGMSProperty: start,
08-23 12:39:16.265  7903  7903 D AndroidRuntime: readGMSProperty: already setted!!
08-23 12:39:16.265  7903  7903 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 12:39:16.265  7903  7903 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 12:39:16.265  7903  7903 D AndroidRuntime: readGMSProperty: end,
08-23 12:39:16.265  7903  7903 D AndroidRuntime: addProductProperty: start
,08-23 12:39:16.285  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:39:16.325  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,08-23 12:39:16.335  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 12:39:16.335  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 12:39:16.335  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:16.335  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 12:39:16.335  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:16.345   289   289 E SMD     : DCD OFF
08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:16.345  6892  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:16.355  6892  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:16.355  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:16.355  6892  7141 I jxcore-log: 
,08-23 12:39:16.365  7911  7911 E Zygote  : MountEmulatedStorage()
,08-23 12:39:16.365  7911  7911 E Zygote  : v2
08-23 12:39:16.365  7911  7911 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:39:16.365  7911  7911 I libpersona: KNOX_SDCARD not a persona
,08-23 12:39:16.365  1019  1045 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7911 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 12:39:16.365  7911  7911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:39:16.375  7911  7911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:39:16.375  7911  7911 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:39:16.395  7903  7903 E AffinityControl: AffinityControl: registerfunction enter
,08-23 12:39:16.405  6892  6892 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-23 12:39:16.405  6892  7141 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:16.405  6892  7141 I jxcore-log: 
,08-23 12:39:16.415  7911  7911 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:39:16.415  7911  7911 D ActivityThread: Added TimaKeyStore provider
,08-23 12:39:16.425  7903  7903 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 12:39:16.455  7911  7911 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 12:39:16.455  1019  1512 D PackageManager: START PACKAGE DELETE: observer{363922802}
08-23 12:39:16.455  1019  1512 D PackageManager: pkg{<packageName>}
08-23 12:39:16.455  1019  1512 D PackageManager: user{0}
08-23 12:39:16.455  1019  1512 D PackageManager: caller{2000}
08-23 12:39:16.455  1019  1512 D PackageManager: flags{2}
08-23 12:39:16.455  7911  7911 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 12:39:16.455  7911  7911 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-23 12:39:16.455  1019  1512 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 12:39:16.455  1019  1512 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 12:39:16.455  1019  1512 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 12:39:16.465  1019  1512 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 12:39:16.465  1019  1512 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 12:39:16.465  1019  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
08-23 12:39:16.465  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 12:39:16.465  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 12:39:16.465  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 12:39:16.465  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 12:39:16.475  1019  1059 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-23 12:39:16.475  7911  7911 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-23 12:39:16.475  7911  7911 I PCWCLIENTTRACE_PushUtil: sales region : global
08-23 12:39:16.475  7911  7911 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-23 12:39:16.475  7911  7911 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:39:16.475  1019  1045 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-23 12:39:16.485  1019  1045 I ActivityManager: Killing 6892:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-23 12:39:16.485  1019  1045 I ActivityManager:   Force finishing activity ActivityRecord{1b39dc1b u0 com.test.thalitest/.MainActivity t163}
,08-23 12:39:16.485  1019  1566 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-23 12:39:16.485  1019  1566 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-23 12:39:16.485  1019  1566 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-23 12:39:16.485  1019  1566 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-23 12:39:16.605  1019  1566 I ActivityManager: Killing 7406:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-23 12:39:16.605  1019  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 12:39:16.615  1019  1045 D InputDispatcher: Focus left window: 6892
,08-23 12:39:16.615   259  1041 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-23 12:39:16.615   259   445 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-23 12:39:16.645  1019  1045 D InputDispatcher: Focused application released
08-23 12:39:16.645  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 12:39:16.645  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 12:39:16.645  1019  1019 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 12:39:16.655  1019  1019 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.cloudagent/com.sec.android.cloudagent.detector.DetectorReceiver}
08-23 12:39:16.655  1019  1019 W BroadcastQueue: android.os.TransactionTooLargeException
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.sendFinished(BroadcastReceiver.java:424)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.finish(BroadcastReceiver.java:389)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3141)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at com.android.server.SystemServer.run(SystemServer.java:445)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at com.android.server.SystemServer.main(SystemServer.java:329)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 12:39:16.655  1019  1019 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 12:39:16.655  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-23 12:39:16.655  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:16.655  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:16.655  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:16.655  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:16.665  7929  7929 E Zygote  : MountEmulatedStorage(),
08-23 12:39:16.665  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7929 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 12:39:16.665  7929  7929 E Zygote  : v2
08-23 12:39:16.665  7929  7929 I libpersona: KNOX_SDCARD checking this for 10001
08-23 12:39:16.665  7929  7929 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:39:16.665  7929  7929 I libpersona: KNOX_SDCARD not a persona,
,08-23 12:39:16.675  1019  1059 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
08-23 12:39:16.675  7929  7929 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:39:16.675  7929  7929 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:39:16.695  1019  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also,
,08-23 12:39:16.705  1019  1044 W libprocessgroup: failed to open /acct/uid_10001/pid_7406/cgroup.procs: No such file or directory
,08-23 12:39:16.705  7929  7929 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:39:16.705  7929  7929 D ActivityThread: Added TimaKeyStore provider
,08-23 12:39:16.715  2848  2848 I art     : Explicit concurrent mark sweep GC freed 17388(1024KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 807us total 36.701ms
,08-23 12:39:16.735  1019  1104 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 12:39:16.745  1901  1901 E SamsungIME: mOCRHelper is null
,08-23 12:39:16.755  1718  1965 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 12:39:16.785  1019  1129 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-23 12:39:16.785  1019  1134 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-23 12:39:16.785  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:16.785  1019  1129 V NetworkStats: performPollLocked(flags=0x3)
08-23 12:39:16.785  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:16.785  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-23 12:39:16.785  1019  1129 V NetworkStats: performPollLocked() took 5ms,
08-23 12:39:16.785  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:16.795  1019  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 12:39:16.795  1019  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-23 12:39:16.795  1019  1044 W TextServicesManagerService: no available spell checker services found
,08-23 12:39:16.815  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-23 12:39:16.815  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,08-23 12:39:16.815  1457  1457 D RegisteredServicesCache: empty dynamic service
,08-23 12:39:16.825  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:16.845  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:16.845  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:16.855  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:16.855  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:16.865  7423  7423 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:39:16.865  7423  7423 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-23 12:39:16.865  7423  7423 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-23 12:39:16.865  7423  7423 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-23 12:39:16.875  1457  1457 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 12:39:16.875  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,08-23 12:39:16.885  1019  1031 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-23 12:39:16.885  1019  1031 D SecContentProvider2: mCursor = null
,08-23 12:39:16.895  1019  1019 I art     : Explicit concurrent mark sweep GC freed 67871(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 3.144ms total 208.317ms
,08-23 12:39:16.905  1019  1059 I art     : WaitForGcToComplete blocked for 133.611ms for cause Explicit
,08-23 12:39:16.965  1019  1052 I PowerManagerService: [PWL] Off : 75s ago
,08-23 12:39:17.015  1019  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-23 12:39:17.015  1019  1099 V AlarmManager: waitForAlarm result :4
,08-23 12:39:17.015  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.025  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.025  7438  7438 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-23 12:39:17.035  7438  7438 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-23 12:39:17.035  7438  7438 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-23 12:39:17.035  7438  7438 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-23 12:39:17.055  1019  1566 I ActivityManager: Killing 7455:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-23 12:39:17.055  1019  1452 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-23 12:39:17.055  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.055  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:17.055  1019  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:39:17.055  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:39:17.055  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 12:39:17.065   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 12:39:17.065   279   966 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-23 12:39:17.075  1884  1884 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,08-23 12:39:17.085  1019  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 12:39:17.085  1019  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:39:17.085  1019  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 12:39:17.085  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.085  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,08-23 12:39:17.105  1019  1059 I art     : Explicit concurrent mark sweep GC freed 9486(449KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 7.837ms total 204.991ms
,08-23 12:39:17.115  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 12:39:17.115  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 12:39:17.115  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 12:39:17.115  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-23 12:39:17.125  1884  1884 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 12:39:17.125  1884  2828 I iu.UploadsManager: num queued entries: 0
,08-23 12:39:17.125  1884  2828 I iu.UploadsManager: num updated entries: 0
,08-23 12:39:17.125  1019  1452 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 12:39:17.125  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.125  1884  2828 I iu.SyncManager: NEXT; no task
,08-23 12:39:17.125  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:17.125  1019  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:39:17.125  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 12:39:17.135  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,08-23 12:39:17.135  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-23 12:39:17.145  1884  1884 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 12:39:17.145  1884  1884 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-23 12:39:17.155  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.165  1019  1059 D PackageManager: delete codoeFile: 
,08-23 12:39:17.165  2832  2832 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 12:39:17 GMT+02:00 2016
08-23 12:39:17.165  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.165  1019  1559 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-23 12:39:17.165  1019  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.165  1019  1559 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:17.165  1019  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:17.165  1019  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 12:39:17.175  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.175  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 12:39:17.175  1019  1059 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-23 12:39:17.175  1019  1059 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-23 12:39:17.175  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.175  1019  1059 D PackageManager: result of delete: 1{363922802}
,08-23 12:39:17.185  2832  2832 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 12:39:17.185  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:39:17.185  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 12:39:17.185  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:39:17.185  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 12:39:17.185  7903  7903 D AndroidRuntime: Shutting down VM
,08-23 12:39:17.185  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-23 12:39:17.185  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.185  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:17.185  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:17.185  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-23 12:39:17.195  1019  1452 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-23 12:39:17.195  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:17.195  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:17.195  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:17.195  1019  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:17.195  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:39:17.195  2832  2832 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 12:39:17.205  7955  7955 E Zygote  : MountEmulatedStorage(),
08-23 12:39:17.205  7955  7955 I libpersona: KNOX_SDCARD checking this for 10031
08-23 12:39:17.205  7955  7955 E Zygote  : v2
08-23 12:39:17.205  7955  7955 I libpersona: KNOX_SDCARD not a persona
08-23 12:39:17.205  7955  7955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:39:17.205  7955  7955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:39:17.215  7955  7955 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:39:17.215  1019  1452 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7955 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-23 12:39:17.215  2832  2832 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 12:39:17.225  1019  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-23 12:39:17.225  1019  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-23 12:39:17.225  2832  2832 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 12:39:17.235  2832  7954 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 12:39:17.235  2832  7954 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-23 12:39:17.235  7955  7955 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:39:17.235  7955  7955 D ActivityThread: Added TimaKeyStore provider
,08-23 12:39:17.235  2832  7954 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-23 12:39:17.235  2832  7954 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-23 12:39:17.245  2832  7954 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-23 12:39:17.255  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 12:39:17.255  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 12:39:17.255  2832  7954 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-23 12:39:17.255  2832  7954 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 12:39:17.265  2832  2832 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 12:39:17.265  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 12:39:17.265  1019  3384 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 12:39:17.265  1019  1166 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-23 12:39:17.265  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 12:39:17.275  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-23 12:39:17.295  1019  1508 I ActivityManager: Killing 7471:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-23 12:39:17.315  2769  7972 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-23 12:39:17.315  2769  7972 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-23 12:39:17.315  2769  7972 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-23 12:39:17.345  2769  7972 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-23 12:39:17.355  2769  7972 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-23 12:39:17.355  2769  7972 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-23 12:39:17.355  2769  7972 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-23 12:39:17.355  2769  7972 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-23 12:39:17.355  2769  7972 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-23 12:39:17.365  2769  7972 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-23 12:39:17.365  2769  7972 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-23 12:39:17.375  7488  7488 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-23 12:39:17.375  7488  7488 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-23 12:39:17.375  7488  7488 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-23 12:39:17.375  2769  7972 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-23 12:39:17.385  2769  7972 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-23 12:39:17.395  7488  7488 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-23 12:39:17.395  7488  7488 I SA      : [OR] == isSIMCardReady false ==
08-23 12:39:17.395  7488  7488 I SA      : [SCU] == networkStateCheck == true
,08-23 12:39:17.395  7903  7903 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 12:39:17.395  7488  7488 I SA      : [DM] getCountryCodeFromCSC : PL
08-23 12:39:17.395  7488  7488 I SA      : isChinaCountryCode : false
08-23 12:39:17.395  7488  7488 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-23 12:39:17.395  7488  7488 I SA      : [OR] == networkStateCheck true ==
,08-23 12:39:17.415  7488  7488 I SA      : [OR] GetMyCountryZoneTask
,08-23 12:39:17.415  7488  7488 I SA      : [OR] onReceive END
,08-23 12:39:17.415  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:39:17.415  1019  1031 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-23 12:39:17.415  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.415  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:39:17.415  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:39:17.415  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-23 12:39:17.425  1817  1817 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 12:39:17.435  1019  6889 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,08-23 12:39:17.435  1019  6889 D SecContentProvider2: mCursor = null
,08-23 12:39:17.435  7488  7973 I SA      : [SRS] prepareGetMyCountryZone
,08-23 12:39:17.435  3219  3291 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-23 12:39:17.445  1019  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 12:39:17.445  1019  1059 D PackageManager: userId{-1}
08-23 12:39:17.445  1019  1059 D PackageManager: andCode{true}
,08-23 12:39:17.445  2683  3016 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 12
,08-23 12:39:17.445  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.445  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:17.445  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:17.445  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:39:17.445  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:39:17.445  7488  7973 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-23 12:39:17.445  7488  7973 I SA      : [SSP] query invoked
,08-23 12:39:17.455  7488  7973 I SA      : [TPMU] GetMccFromDB : null
,08-23 12:39:17.455  7488  7973 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-23 12:39:17.455  7488  7973 I SA      : [LBE] isSupportCheckDomainRegion : false,
08-23 12:39:17.455  7488  7973 I SA      : [TPM] isNoProxy(default) : true
,08-23 12:39:17.465  7977  7977 E Zygote  : MountEmulatedStorage(),
08-23 12:39:17.465  7977  7977 E Zygote  : v2
08-23 12:39:17.465  7977  7977 I libpersona: KNOX_SDCARD checking this for 10003
,08-23 12:39:17.465  7977  7977 I libpersona: KNOX_SDCARD not a persona
,08-23 12:39:17.465  7977  7977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:39:17.465  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7977 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 12:39:17.465  1817  1817 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-23 12:39:17.465  1817  1817 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-23 12:39:17.465  1817  1817 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-23 12:39:17.465  1019  1134 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-23 12:39:17.465  1817  1817 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
08-23 12:39:17.465  7977  7977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:39:17.465  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:17.465  1019  1134 V NetworkStats: updateIfacesLocked()
08-23 12:39:17.465  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:39:17.465  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
08-23 12:39:17.465  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 12:39:17.475  7977  7977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:39:17.475  1019  1134 V NetworkStats: performPollLocked() took 4ms
08-23 12:39:17.475  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:17.475  1817  1817 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-23 12:39:17.475  1019  1134 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-23 12:39:17.475  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:39:17.475  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:39:17.475  1019  1134 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-23 12:39:17.475  1182  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-23 12:39:17.475  1817  1817 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-23 12:39:17.475  1182  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-23 12:39:17.495  1019  1032 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-23 12:39:17.495  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.495  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:17.495  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-23 12:39:17.495  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
08-23 12:39:17.495  7977  7977 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-23 12:39:17.495  7977  7977 D ActivityThread: Added TimaKeyStore provider
,08-23 12:39:17.505  7488  7973 E File    : fail readDirectory() errno=2
,08-23 12:39:17.505  1019  1452 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-23 12:39:17.505  1019  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-23 12:39:17.505  1019  1452 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:39:17.505  1019  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:39:17.505  1019  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 12:39:17.535  7617  7617 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:39:17.535  7617  7617 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-23 12:39:17.535  7617  7617 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-23 12:39:17.545  7595  7616 E SQLiteLog: (28) failed to open "/data/data/com.google.android.apps.plus/databases/iu.upload.db" with flag (131138) and mode_t (0) due to error (30)
,08-23 12:39:17.545  1019  1329 E Watchdog: !@Sync 4
,08-23 12:39:17.545  1019  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 12:39:17.545  7595  7616 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.plus/databases/iu.upload.db'.
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at gqg.getReadableDatabase(PG:61)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at gpk.b(PG:394)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at gos.a(PG:305)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at gos.a(PG:4414)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at gou.handleMessage(PG:1230)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:17.545  7595  7616 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: Couldn't open iu.upload.db for writing (will try read-only):
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228),
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at gqg.getReadableDatabase(PG:61)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at gpk.b(PG:394)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at gos.a(PG:305)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: ,	at gos.a(PG:4414)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at gou.handleMessage(PG:1230)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-23 12:39:17.545  7595  7616 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:39:17.555  7595  7616 W SQLiteOpenHelper: Opened iu.upload.db in read-only mode
,08-23 12:39:17.555  7595  7616 E SQLiteLog: (28) failed to open "/data/data/com.google.android.apps.plus/databases/iu.upload.db" with flag (131074) and mode_t (0) due to error (30)
,08-23 12:39:17.555  7595  7616 E SQLiteLog: (28) failed to open "/data/data/com.google.android.apps.plus/databases/iu.upload.db" with flag (131074) and mode_t (0) due to error (30)
,08-23 12:39:17.585  7677  7677 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-23 12:39:17.605  7347  7994 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-23 12:39:17.605  7347  7994 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 12:39:17.605  7347  7994 I System.out: (HTTPLog)-Static: isShipBuild true
08-23 12:39:17.605  7347  7994 I System.out: (HTTPLog)-Thread-1380-997173929: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 12:39:17.605  7347  7994 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 12:39:17.615   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 12:39:17.615   279   966 D Netd    : getNetworkForDns: using netid 504 for uid 10102

```
