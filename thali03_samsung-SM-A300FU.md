#### Test 82203060198550b_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-24 14:03:37.819  6758  6758 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:37.819  6758  6758 D ActivityThread: Added TimaKeyStore provider
--------- beginning of system
08-24 14:03:37.839  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-24 14:03:37.849  6742  6775 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
08-24 14:03:37.849  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:37.849  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:37.849  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:37.849  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:37.849  6742  6775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
08-24 14:03:37.849  6758  6758 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 14:03:37.849  6758  6758 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:37.849  6758  6758 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:37.849  6758  6758 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-24 14:03:37.849  6758  6758 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 14:03:37.849  6758  6758 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-24 14:03:37.849  6758  6758 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-24 14:03:37.859  6776  6776 E Zygote  : MountEmulatedStorage()
08-24 14:03:37.859  6776  6776 E Zygote  : v2
08-24 14:03:37.859  6776  6776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:37.859  6776  6776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:37.859  6776  6776 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:03:37.859  6776  6776 I libpersona: KNOX_SDCARD checking this for 10117
08-24 14:03:37.859  6776  6776 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:37.859  1018  1495 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6776 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:03:37.859  1018  1495 I ActivityManager: Killing 6431:com.osp.app.signin/u0a36 (adj 15): empty #21
08-24 14:03:37.859  1018  1503 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-24 14:03:37.869  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:37.869  1018  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:37.869  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:03:37.879  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:37.879  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:37.879  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
08-24 14:03:37.879  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-24 14:03:37.879  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-24 14:03:37.889  6776  6776 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:37.889  6776  6776 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:37.889  6742  6742 D AcmsService: Enter Oncreate
08-24 14:03:37.889  6742  6742 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:37.889  6742  6742 D AcmsService: creating AcmsCore
08-24 14:03:37.889  6742  6742 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-24 14:03:37.889  6742  6742 D AcmsCore: AcmsCore
08-24 14:03:37.899  1811  1811 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 14:03:37.899  6742  6742 D AcmsCore: init
08-24 14:03:37.899  6742  6742 D AcmsCore: Looper handler is not null
08-24 14:03:37.899  6742  6742 D AcmsCore: Post to AcmsCoreHandler
08-24 14:03:37.899  6742  6742 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:37.899  6742  6742 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-24 14:03:37.899  6742  6742 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-24 14:03:37.899  6742  6742 D AcmsService: onStartCommand
08-24 14:03:37.899  6742  6742 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
08-24 14:03:37.899  6742  6742 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-24 14:03:37.899  6742  6742 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-24 14:03:37.899  6742  6742 D AcmsService: Incremented Counter Value : onStartCommand
08-24 14:03:37.899  1811  1811 I ConfigFetchService: launchTask
08-24 14:03:37.899  6742  6793 D AcmsCertificateMngr: AcmsCertificateMngr
08-24 14:03:37.899  1018  1519 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-24 14:03:37.899  6742  6742 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-24 14:03:37.909  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:37.909  1018  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:03:37.909  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-24 14:03:37.909  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:37.909  1018  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:37.909  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-24 14:03:37.909  6742  6793 D AcmsRevocationMngr: AcmsRevocationMngr
08-24 14:03:37.909  1018  1329 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-24 14:03:37.909  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-24 14:03:37.909  1018  1503 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-24 14:03:37.909  1018  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-24 14:03:37.919  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:03:37.919  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 14:03:37.919  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:37.919  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:37.919  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:03:37.919  6776  6776 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:37.959  6742  6742 D AcmsService: Inside handle Intent
08-24 14:03:37.959  6742  6742 D AcmsService: App added - package name: com.test.thalitest
08-24 14:03:37.959  6742  6742 D AcmsCore: Post to AcmsCoreHandler
08-24 14:03:37.959  6742  6742 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:37.959  6742  6742 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-24 14:03:37.959  6742  6742 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
08-24 14:03:37.959  6742  6742 D AcmsService: Decremented Counter Value : handleStartIntent
08-24 14:03:37.959  6742  6742 D AcmsServiceMonitor: Decrementing - Counter value: 2
08-24 14:03:37.969  1018  4247 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-24 14:03:37.969  1018  4247 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
08-24 14:03:37.969  1018  4247 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:37.969  1018  4247 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:37.969  1018  4247 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
08-24 14:03:37.989  1018  1519 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-24 14:03:38.019  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.019  1811  1811 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-24 14:03:38.019  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.019  1811  1811 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-24 14:03:38.019  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.019  1811  6795 I PeopleContactsSync: CP2 sync disabled
08-24 14:03:38.019  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.029  1811  6794 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Umja4hR2vPmr2HjzygovF1CCF3nkf_qgRwZ9MpA8xB4n76e7WVqfizrA0iY4MZKcBGxrZRiH1V18NGNOzZQ1nEnYc6scgcdaIJzdl2c4noI1GoIgP0vfxOrT9LIomKTuKfvBOAS44-qF7TN5YF0l9S9Wc1xJQA6tkhN3jiYbHRQN_x56kmRqJvti1XfECPXH8c-dJVHc9R8w6fvmqOCg3P92JLLRQrwPDZ84m0vTyLAYCN2MY
08-24 14:03:38.029  1018  1519 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:38.039  6806  6806 E Zygote  : MountEmulatedStorage()
08-24 14:03:38.039  6806  6806 E Zygote  : v2
08-24 14:03:38.039  6806  6806 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:38.039  6806  6806 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:38.039  6806  6806 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:38.039  6806  6806 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:38.039  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 14:03:38.039  6806  6806 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:38.039  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.039  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:38.039  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:03:38.049  1811  1811 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
08-24 14:03:38.079  6806  6806 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:38.079  6806  6806 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:38.129  1018  4251 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
08-24 14:03:38.129  1811  6794 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-24 14:03:38.149  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.149  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.149  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.149  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.149  6758  6758 D NearbySource: Nearby Source Create!
08-24 14:03:38.149  6758  6758 D NearbyContext: Nearby Context Create!
08-24 14:03:38.179  6830  6830 E Zygote  : MountEmulatedStorage()
08-24 14:03:38.179  6830  6830 E Zygote  : v2
08-24 14:03:38.179  6830  6830 I libpersona: KNOX_SDCARD checking this for 10014
08-24 14:03:38.179  6830  6830 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:38.179  6830  6830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:38.189  6830  6830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:38.189  1018  4251 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6830 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
08-24 14:03:38.189  1018  1329 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-24 14:03:38.189  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-24 14:03:38.189  6830  6830 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:03:38.199  6806  6806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
08-24 14:03:38.209  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.209  1018  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:38.209  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:03:38.219  1018  1495 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-24 14:03:38.219  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-24 14:03:38.219  6799  6799 D AndroidRuntime: 
08-24 14:03:38.219  6799  6799 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:03:38.229  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.229  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:38.229  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-24 14:03:38.229  6799  6799 D AndroidRuntime: CheckJNI is OFF
08-24 14:03:38.229  6799  6799 D AndroidRuntime: readGMSProperty: start
08-24 14:03:38.229  6799  6799 D AndroidRuntime: readGMSProperty: already setted!!
08-24 14:03:38.229  6799  6799 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 14:03:38.229  6799  6799 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:03:38.229  6799  6799 D AndroidRuntime: readGMSProperty: end
08-24 14:03:38.229  6799  6799 D AndroidRuntime: addProductProperty: start
08-24 14:03:38.239  6830  6830 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:38.239  6579  6579 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
08-24 14:03:38.239  1018  4260 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-24 14:03:38.239  6830  6830 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:38.239  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.239  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.239  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.239  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.259  1018  4260 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6846 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-24 14:03:38.269  6846  6846 E Zygote  : MountEmulatedStorage()
08-24 14:03:38.269  6846  6846 E Zygote  : v2
08-24 14:03:38.269  6846  6846 I libpersona: KNOX_SDCARD checking this for 10087
08-24 14:03:38.269  6846  6846 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:38.269  6846  6846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:38.279  1018  4260 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-24 14:03:38.279  6846  6846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:38.279  1018  4260 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.279  1018  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:38.279  1018  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
08-24 14:03:38.279  6846  6846 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:03:38.279  1018  1503 I ActivityManager: Killing 6450:com.android.mms/u0a41 (adj 15): empty #21
08-24 14:03:38.289   313   313 I art     : Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 35.182ms
08-24 14:03:38.299  6846  6846 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:38.299  6846  6846 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:38.319   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 22.963ms
08-24 14:03:38.339   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 17.286ms
08-24 14:03:38.369   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-24 14:03:38.369   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 14:03:38.369  6758  6758 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-24 14:03:38.369  6758  6758 D SLinkSource: Samsung link source created
08-24 14:03:38.389  1018  4252 D CountryDetector: No listener is left
08-24 14:03:38.399  6799  6799 E AffinityControl: AffinityControl: registerfunction enter
08-24 14:03:38.419  6799  6799 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 14:03:38.459  1018  1495 E PersonaManagerService: inState():  stateMachine is null !!
08-24 14:03:38.469  1018  1495 I PersonaManagerService: PersonaId don't exist
08-24 14:03:38.469  1018  1495 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-24 14:03:38.469  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.469  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.469  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.469  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.489  6874  6874 E Zygote  : MountEmulatedStorage()
08-24 14:03:38.489  6874  6874 E Zygote  : v2
08-24 14:03:38.489  6874  6874 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:38.489  6874  6874 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:38.489  6874  6874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:38.489  1018  1043 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6874 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:38.499  6874  6874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:38.499  6874  6874 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:38.509  1018  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:03:38.539  6874  6874 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:38.539  6874  6874 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:38.599  1018  4251 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-24 14:03:38.619  1018  4247 I art     : Explicit concurrent mark sweep GC freed 141350(7MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 22MB/34MB, paused 2.757ms total 203.180ms
08-24 14:03:38.619  1018  1495 W ActivityManager: mDVFSHelper.acquire()
08-24 14:03:38.619  1018  1502 E EdmStorageProvider: Admin not in database, something went wrong
08-24 14:03:38.629  1018  1495 D FocusedStackFrame: Set to : 0
08-24 14:03:38.639  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 14:03:38.639  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-24 14:03:38.639  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-24 14:03:38.649  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.649  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.649  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.649  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.659  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 14:03:38.659  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 14:03:38.659  6895  6895 E Zygote  : MountEmulatedStorage()
08-24 14:03:38.659  6895  6895 E Zygote  : v2
08-24 14:03:38.659  6895  6895 I libpersona: KNOX_SDCARD checking this for 10170
08-24 14:03:38.659  6895  6895 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:38.659  6895  6895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:38.659   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-24 14:03:38.669  6895  6895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:38.669  6895  6895 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 14:03:38.669  1018  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 14:03:38.669  1018  1495 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6895 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:03:38.669  1018  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:03:38.669  1018  1495 D InputDispatcher: Focused application set to: xxxx
08-24 14:03:38.679  1018  1495 D InputDispatcher: Focus left window: 1504
08-24 14:03:38.679  6799  6799 D AndroidRuntime: Shutting down VM
08-24 14:03:38.679  1018  1461 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
08-24 14:03:38.679  1018  1461 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.679  1018  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
08-24 14:03:38.679  1018  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:38.679  1018  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
08-24 14:03:38.679  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:03:38.679  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:38.709  6895  6895 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:38.709  1018  1495 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
08-24 14:03:38.709  6895  6895 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:38.709  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
08-24 14:03:38.709  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.709  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:38.709  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
08-24 14:03:38.709  1018  4247 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-24 14:03:38.719  1018  1329 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-24 14:03:38.719  1018  1018 V ActivityManager: Display changed displayId=0
08-24 14:03:38.729  1018  4260 D LocationManagerService: getProviders()=[passive, gps]
08-24 14:03:38.729  1018  1457 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-24 14:03:38.729  6758  6758 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-24 14:03:38.739  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 14:03:38.759  6874  6874 D AASAservice: onCreate()
08-24 14:03:38.759  6874  6874 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
08-24 14:03:38.759  1018  1329 D PersonaManager: isKioskContainerExistOnDevice
08-24 14:03:38.769   258   447 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-24 14:03:38.769   258   442 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-24 14:03:38.769  1811  6794 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-24 14:03:38.769  1811  6794 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 14:03:38.769  1811  6794 I System.out: (HTTPLog)-Static: isShipBuild true
08-24 14:03:38.769  1811  6794 I System.out: (HTTPLog)-Thread-229-356230181: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-24 14:03:38.769  1811  6794 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 14:03:38.779  1018  1461 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-24 14:03:38.779   278  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 14:03:38.779   278  1013 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-24 14:03:38.779  1504  1504 V ActivityThread: updateVisibility : ActivityRecord{2316e523 token=android.os.BinderProxy@30afad93 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 14:03:38.779  1504  1504 D Launcher: onTrimMemory. Level: 20
08-24 14:03:38.779  1018  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.779  1018  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.779  1018  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.779  1018  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.799  6920  6920 E Zygote  : MountEmulatedStorage()
08-24 14:03:38.799  6920  6920 E Zygote  : v2
08-24 14:03:38.799  6920  6920 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:38.799  6920  6920 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:38.799  6920  6920 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:38.799  6920  6920 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:38.799  1018  6893 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 14:03:38.799  6920  6920 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:38.799  1018  6893 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4200, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:03:38.799  1018  6893 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 14:03:38.799  1018  6893 D BatteryService: stay LED for charging
08-24 14:03:38.799  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 14:03:38.799  1018  1461 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6920 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:38.809  2761  2761 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
08-24 14:03:38.809  1018  1503 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
08-24 14:03:38.809  6758  6872 D ContactProvider: getAllContactInfoList Start
08-24 14:03:38.819  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.819  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.819  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.819  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.839  6937  6937 E Zygote  : MountEmulatedStorage()
08-24 14:03:38.839  6937  6937 I libpersona: KNOX_SDCARD checking this for 10041
08-24 14:03:38.839  6937  6937 E Zygote  : v2
08-24 14:03:38.839  6937  6937 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:38.839  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:38.839  1018  1503 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6937 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
08-24 14:03:38.839  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:38.839  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-24 14:03:38.839  1018  1503 I ActivityManager: Killing 6372:com.android.defcontainer/u0a3 (adj 15): empty #21
08-24 14:03:38.849  6920  6920 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:38.849  6920  6920 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:38.879  1018  1018 I MotionRecognitionService: Plugged
08-24 14:03:38.879  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-24 14:03:38.879  6799  6799 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-24 14:03:38.889  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 14:03:38.889  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 14:03:38.889  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-24 14:03:38.889  1811  6794 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-24 14:03:38.889  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:03:38.889  1811  6794 I qtaguid : Tagging socket 100 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1811, getuid(): 10011
,08-24 14:03:38.899  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:38.899  6937  6937 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:38.909  3203  3203 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:03:38.909  3203  3344 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:03:38.909  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,08-24 14:03:38.909  1018  1329 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-24 14:03:38.909  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,08-24 14:03:38.909  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.909  1018  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:38.909  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-24 14:03:38.929  6937  6937 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-24 14:03:38.929  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:03:38.929  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:03:38.929  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:03:38.929  6937  6937 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:38.929  6937  6937 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:38.929  6937  6937 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-24 14:03:38.929  6721  6796 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 14:03:38.929  6937  6937 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-24 14:03:38.939  6920  6920 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-24 14:03:38.939  6920  6920 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 14:03:38.939  6920  6920 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-24 14:03:38.949  1018  1461 I ActivityManager: Killing 6478:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-24 14:03:38.959  1811  6794 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1811, getuid(): 10011
,08-24 14:03:38.969  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-24 14:03:38.969  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-24 14:03:38.969  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:38.969  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:38.969  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-24 14:03:38.969  1811  6812 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:03:38.969  1811  6812 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:03:38.969  6920  6920 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-24 14:03:38.969  6920  6920 I PCWCLIENTTRACE_PushUtil: sales region : global
08-24 14:03:38.969  6920  6920 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 14:03:38.979  6920  6920 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,08-24 14:03:38.979  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,08-24 14:03:38.979  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:38.979  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:38.979  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:38.979  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:38.999  6955  6955 E Zygote  : MountEmulatedStorage(),
08-24 14:03:38.999  6955  6955 E Zygote  : v2
08-24 14:03:38.999  6955  6955 I libpersona: KNOX_SDCARD checking this for 10026
08-24 14:03:38.999  6955  6955 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:38.999  6955  6955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:38.999  1018  1031 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6955 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:03:38.999  6955  6955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:03:38.999  6955  6955 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-24 14:03:39.009  1018  1031 I ActivityManager: Killing 6495:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-24 14:03:39.009  6895  6895 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-24 14:03:39.049  6937  6937 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-24 14:03:39.049  6955  6955 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:39.049  6955  6955 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:39.069  6758  6872 D ContactProvider: getAllContactInfoList End
,08-24 14:03:39.069  6758  6872 I syncContacts: thread: 1253, sync time = 601
,08-24 14:03:39.089  6895  6895 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6203-6206)
08-24 14:03:39.089  6895  6895 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 14:03:39.099  1018  4260 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-24 14:03:39.099  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.099  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:39.099  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:39.099  1018  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.109  1018  4260 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6972 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-24 14:03:39.119  6972  6972 E Zygote  : MountEmulatedStorage()
,08-24 14:03:39.119  6972  6972 E Zygote  : v2
08-24 14:03:39.119  6972  6972 I libpersona: KNOX_SDCARD checking this for 10148
08-24 14:03:39.119  6972  6972 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:39.119  6972  6972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:39.119  6972  6972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:03:39.119  6972  6972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:39.129  1018  6893 I ActivityManager: Killing 6511:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-24 14:03:39.139  6972  6972 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:39.149  6972  6972 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:39.159  1811  6812 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:03:39.159  6895  6895 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e7673ea}
,08-24 14:03:39.159  6895  6895 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 14:03:39.169  6895  6895 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 14:03:39.199  1811  6812 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:03:39.199  1811  6812 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:03:39.199  6972  6972 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-24 14:03:39.209  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.209  1018  4247 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,08-24 14:03:39.219  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.219  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.219  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:39.219  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:39.219  1018  1461 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6511, ws=null) (elapsedTime=2587)
,08-24 14:03:39.229  6990  6990 E Zygote  : MountEmulatedStorage(),
08-24 14:03:39.229  6990  6990 E Zygote  : v2
,08-24 14:03:39.229  1018  4247 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6990 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:39.229  6990  6990 I libpersona: KNOX_SDCARD checking this for 1000
,08-24 14:03:39.229  6990  6990 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:39.229  1018  4247 I ActivityManager: Killing 6526:com.wsomacp/u0a23 (adj 15): empty #21
,08-24 14:03:39.229  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:03:39.239  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:03:39.239  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:39.239  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.269  6895  6895 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 14:03:39.269  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{26562864 u0 com.test.thalitest/.MainActivity t163}
,08-24 14:03:39.269  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:39.269  6895  6895 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:03:39.279  6990  6990 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:39.289  6895  6895 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 14:03:39.289  6990  6990 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,08-24 14:03:39.319  6955  6955 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-24 14:03:39.339  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.349  1018  1503 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:39.349  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:39.349  1018  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.349  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.349  1018  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-24 14:03:39.349  6937  6937 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 199.582ms
,08-24 14:03:39.359  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:39.359  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:39.359  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:39.359  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.369  1018  1503 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7013 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-24 14:03:39.369  1811  6812 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:03:39.369  1018  1503 I ActivityManager: Killing 6545:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-24 14:03:39.379  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:03:39.379  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-24 14:03:39.379  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:39.379  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.379  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.379  7013  7013 E Zygote  : MountEmulatedStorage()
08-24 14:03:39.379  7013  7013 E Zygote  : v2
08-24 14:03:39.379  7013  7013 I libpersona: KNOX_SDCARD checking this for 10152
,08-24 14:03:39.379  7013  7013 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:39.389  7013  7013 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:39.389  7013  7013 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:39.389  7013  7013 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:39.399  7013  7013 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:39.399  7013  7013 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:39.419  6895  6895 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 14:03:39.419  6895  6895 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 14:03:39.419  6895  6895 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 14:03:39.419  6895  6895 I Adreno-EGL: Local Branch: 
08-24 14:03:39.419  6895  6895 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 14:03:39.419  6895  6895 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 14:03:39.419  6895  6895 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 14:03:39.429  7013  7013 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-24 14:03:39.429  7013  7013 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,08-24 14:03:39.439  1811  1844 W art     : Suspending all threads took: 6.284ms
,08-24 14:03:39.439  7013  7013 I TapandpayWidget:Utils: Clear T&P info.
,08-24 14:03:39.459  1018  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-24 14:03:39.459  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:39.469  1018  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.469  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.469  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:03:39.469  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-24 14:03:39.469  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:39.469  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.469  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.479  7013  7013 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-24 14:03:39.479  1018  1329 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-24 14:03:39.489  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.489  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.489  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.489  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:39.499  7034  7034 E Zygote  : MountEmulatedStorage()
08-24 14:03:39.499  7034  7034 I libpersona: KNOX_SDCARD checking this for 10009
08-24 14:03:39.499  7034  7034 E Zygote  : v2
08-24 14:03:39.499  7034  7034 I libpersona: KNOX_SDCARD not a persona,
08-24 14:03:39.499  7034  7034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:39.499  7034  7034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:39.509  7034  7034 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
08-24 14:03:39.509  1018  1329 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7034 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-24 14:03:39.509  1018  1461 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:39.509  1018  1329 I ActivityManager: Killing 6269:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21,
08-24 14:03:39.509  1018  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.509  1018  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-24 14:03:39.509  1018  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:03:39.509  6937  6937 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 159.951ms
,08-24 14:03:39.519  6937  7042 D Mms/ArtClassLoader: init before art
,08-24 14:03:39.519  6937  6937 D Mms/TelephonyPermission: start operation mode monitor
,08-24 14:03:39.529  1018  4260 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:39.539  1018  4260 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:39.539  1018  4260 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.539  1018  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.539  7034  7034 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:39.549  7034  7034 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:39.549  1018  4260 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-24 14:03:39.549  1018  4260 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:39.549  1018  4260 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.549  1018  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.549  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.559  6937  6937 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 14:03:39.559  6742  6793 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-24 14:03:39.559  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.569  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.569  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.569  6937  6937 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-24 14:03:39.569  6937  6937 D Mms/TelephonyPermission: isDefault true
,08-24 14:03:39.569  6937  6937 D Mms/MmsApp: onCreate() com.android.mms
,08-24 14:03:39.589  6895  6895 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 14:03:39.599  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.609  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:03:39.609  6895  6895 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 14:03:39.609  6895  6895 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 14:03:39.609  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.609  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.609  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.609  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.609  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.609  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.619  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.619  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.619  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.619  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.619  6895  6895 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 14:03:39.619  6895  6895 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 14:03:39.619  6955  6955 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-24 14:03:39.659  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:03:39.659  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-24 14:03:39.659  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:39.659  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.659  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.679  6937  6937 D Mms/MmsApp: [start]    initCountryIso consume time = 634.39625
,08-24 14:03:39.689  6955  6955 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 14:03:39.689  6955  6955 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 14:03:39.689  1018  1519 D CountryDetector: The first listener is added
,08-24 14:03:39.689  6742  6793 I AcmsKeyStoreHelper: Key Store exist
08-24 14:03:39.689  6742  6793 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-24 14:03:39.699  6721  6796 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 762 ms] updated apps [took 761 ms] 
,08-24 14:03:39.699  6937  6937 D Mms/MmsApp: [end]    initCountryIso consume time = 15.261719
,08-24 14:03:39.699  6937  6937 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 1.020833
,08-24 14:03:39.699  1018  4247 I ActivityManager: Killing 6286:com.android.calendar/u0a131 (adj 15): empty #21
,08-24 14:03:39.709  6937  6937 D Mms/MmsConfig: before partial update
,08-24 14:03:39.729  6937  6937 D Mms/MmsConfig: Load Resize quality : 80
,08-24 14:03:39.729  6937  6937 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,08-24 14:03:39.729  6937  6937 D EasySignUpManager_1.0.1: isAuth is false
,08-24 14:03:39.729  6937  6937 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,08-24 14:03:39.739  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.739  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.739  1480  1494 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6937
,08-24 14:03:39.739  6955  6955 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-24 14:03:39.739  1480  1494 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.716 ms
,08-24 14:03:39.749  6937  6937 D EasySignUpManager_1.0.1: isAuth is false
,08-24 14:03:39.749  6937  6937 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,08-24 14:03:39.749  6937  6937 E CscParser: mps_code.dat does not exist
,08-24 14:03:39.749  6937  6937 E CscParser: customer_path =/system/csc/customer.xml
08-24 14:03:39.749  6937  6937 E CscParser: fileName + /system/csc/customer.xml
,08-24 14:03:39.769  6937  6937 E CscParser: mps_code.dat does not exist
,08-24 14:03:39.769  6937  6937 E CscParser: customer_path =/system/csc/customer.xml
,08-24 14:03:39.769  6937  6937 E CscParser: fileName + /system/csc/customer.xml
,08-24 14:03:39.769  1018  1137 I ActivityManager: Killing 6564:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-24 14:03:39.779  6955  6955 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-24 14:03:39.779  6937  6937 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-24 14:03:39.789  6937  6937 D Mms/MmsConfig:  enable multiwindow = false
,08-24 14:03:39.789  1018  1030 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,08-24 14:03:39.789  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-24 14:03:39.809  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:39.809  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:03:39.809  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-24 14:03:39.819  6955  7077 D Ads     : Skipping gmscore version check
,08-24 14:03:39.819  6937  6937 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-24 14:03:39.819  6937  6937 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-24 14:03:39.829  6937  6937 D Mms/MmsConfig: [end]    init() consume time = 127.593958
,08-24 14:03:39.829  6937  6937 D Mms/Contact: [start]    init() consume time = 2.207448
,08-24 14:03:39.839  1811  6794 I qtaguid : Untagging socket 100
,08-24 14:03:39.839  1480  1726 D TP/MmsSmsProvider: query,matched:13, calling pid = 6937
,08-24 14:03:39.839  1480  1726 D TP/MmsSmsProvider: match 13:Elapsed time : 1.053 ms
,08-24 14:03:39.859  6955  6955 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-24 14:03:39.859  1018  6893 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:39.859  1018  6893 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:39.869  1018  6893 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:39.869  1018  6893 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-24 14:03:39.869  6937  6937 D Mms/Contact: [end]    init consume time = 41.026406
,08-24 14:03:39.899  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:03:39.909  6937  6937 D Mms/MethodReflector: getSubId is called
,08-24 14:03:39.909  6937  6937 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-24 14:03:39.909  6937  7087 D Mms/DraftCache: [start]    rebuildCache consume time = 35.251615
,08-24 14:03:39.909  1480  1497 D TP/MmsSmsProvider: query,matched:12, calling pid = 6937
,08-24 14:03:39.909  1480  1497 D TP/MmsSmsProvider: match 12:Elapsed time : 1.962 ms
,08-24 14:03:39.919  6937  7087 D Mms/DraftCache: [end]    rebuildCache consume time = 8.957344
,08-24 14:03:39.919  6937  6937 D Mms/MethodReflector: getTelephonyProperty is called
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: auto download without roaming -> true
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-24 14:03:39.919  6937  6937 D Mms/MethodReflector: getSubId is called
,08-24 14:03:39.919  6937  6937 D Mms/MethodReflector: getDefaultSmsSubId is called
08-24 14:03:39.919  6937  6937 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-24 14:03:39.919  6937  6937 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-24 14:03:39.919  6937  6937 D Mms/MethodReflector: getTelephonyProperty is called
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: auto download without roaming -> true
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: auto download during roaming secondary -> false
08-24 14:03:39.919  6937  6937 D Mms/DownloadManager: mAutoDownload ------> true
,08-24 14:03:39.939  1018  4247 I ActivityManager: Killing 6601:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-24 14:03:39.939  1018  1519 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-24 14:03:39.969  6895  6895 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:03:39.979  1811  1811 I ConfigFetchService: fetch service done; releasing wakelock
,08-24 14:03:39.979  1811  1811 I ConfigFetchService: stopping self
,08-24 14:03:39.989  6895  6895 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 14:03:39.999  6937  6937 D ComposerPerformance: 1472040220013 ms / [DONE] Composer constructor
,08-24 14:03:39.999  6937  6937 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,08-24 14:03:39.999  6895  6895 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 14:03:39.999  6895  6895 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-24 14:03:39.999  6937  6937 I Mms/ReservationManager: ReservationManager()
08-24 14:03:39.999  6937  6937 I Mms/ReservationManager: resetAfterConnected()
,08-24 14:03:40.009  1480  1497 D TP/MmsSmsProvider: query,matched:7, calling pid = 6937
,08-24 14:03:40.009  1480  1497 D TP/MmsSmsProvider: match 7:Elapsed time : 2.182 ms
,08-24 14:03:40.009  6895  6895 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-24 14:03:40.009  6937  7090 D Mms/Conversation: [start]    init() consume time = 96.774843
,08-24 14:03:40.019  1480  1726 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,08-24 14:03:40.019  1480  1726 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,08-24 14:03:40.019  1480  1726 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-24 14:03:40.019  1480  1726 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,08-24 14:03:40.019  6895  6895 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:03:40.019  6895  6895 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:03:40.029  6937  6937 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-24 14:03:40.029  1480  1726 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-24 14:03:40.029  1480  1726 D TP/MmsSmsProvider: need read changed broadcast:false
,08-24 14:03:40.029  6937  7090 D Mms/Conversation: [end]    init consume time = 18.62224
,08-24 14:03:40.029  6937  7090 D Mms/MessagingNotification: [start]    init() consume time = 2.721875
,08-24 14:03:40.029  6742  6793 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-24 14:03:40.029  6742  6793 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-24 14:03:40.029  6742  6793 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-24 14:03:40.029  6742  6793 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:40.029  6742  6793 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-24 14:03:40.029  6742  6793 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-24 14:03:40.039  6937  6937 D Mms/MmsApp: [end]    onCreate() consume time = 1.768229
,08-24 14:03:40.039  6937  7090 D Mms/MessagingNotification: [end]    init consume time = 5.048229
,08-24 14:03:40.039  6937  6937 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,08-24 14:03:40.039  6937  6937 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-24 14:03:40.039  6742  6793 D AcmsCore: This is NOT a valid MirrorLink app
08-24 14:03:40.039  6742  6793 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-24 14:03:40.039  6742  6793 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:40.039  6742  6793 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-24 14:03:40.039  6742  6793 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-24 14:03:40.049  1480  1494 D TP/MmsSmsProvider: query,matched:0, calling pid = 6937
08-24 14:03:40.049  1480  1494 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-24 14:03:40.049  1480  1494 D TP/MmsSmsProvider: match 0:Elapsed time : 1.042 ms
,08-24 14:03:40.049  6937  6937 D Mms/MethodReflector: getSubId is called
08-24 14:03:40.049  6937  6937 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-24 14:03:40.049  6937  6937 D Mms/MethodReflector: getTelephonyProperty is called
08-24 14:03:40.049  6937  6937 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-24 14:03:40.049  6937  6937 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 14:03:40.049  6937  6937 D Mms/DownloadManager: auto download without roaming -> true
08-24 14:03:40.049  6937  6937 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-24 14:03:40.049  6937  6937 D Mms/DownloadManager: mAutoDownload ------> true
,08-24 14:03:40.059  6742  6742 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-24 14:03:40.059  6742  6742 D AcmsService: Enter onDestroy
08-24 14:03:40.059  6742  6742 I AcmsService: cleanUp(): inside service clean up
08-24 14:03:40.059  6742  6742 D AcmsCore: AcmsCore: inside DeInit
08-24 14:03:40.059  6742  6742 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-24 14:03:40.059  6742  6742 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-24 14:03:40.059  6742  6742 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-24 14:03:40.059  6742  6742 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-24 14:03:40.059  6742  6742 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-24 14:03:40.059  6742  6742 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-24 14:03:40.059  6742  6742 D AcmsService: killing acms process
08-24 14:03:40.059  6742  6742 I Process : Sending signal. PID: 6742 SIG: 9
,08-24 14:03:40.069  6937  7093 D Mms/Synchronizer: [start]    doSync consume time = 25.151563
,08-24 14:03:40.069  1480  1726 D TP/MmsSmsProvider: update, matched:300, calling pid = 6937
08-24 14:03:40.069  1480  1726 V TP/MmsSmsProvider: syncDBData start
,08-24 14:03:40.069  1480  1726 V TP/MmsSmsProvider: syncDBData sms end
,08-24 14:03:40.069  1480  1726 V TP/MmsSmsProvider: syncDBData mms end
,08-24 14:03:40.069  1480  1726 V TP/MmsSmsProvider: syncDBData end
08-24 14:03:40.069  6937  7093 D Mms/Synchronizer: [end]    doSync consume time = 5.28151
,08-24 14:03:40.079  6937  7092 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 6.903177
,08-24 14:03:40.079  1018  1502 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,08-24 14:03:40.089  1480  1494 D TP/MmsSmsProvider: query,matched:400, calling pid = 6937
,08-24 14:03:40.089  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:40.089   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7f467c8
08-24 14:03:40.089   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-24 14:03:40.089  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.089   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-24 14:03:40.099  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.089   273   320 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1208719224)
08-24 14:03:40.099  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:40.109  6937  6937 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,08-24 14:03:40.119  7097  7097 E Zygote  : MountEmulatedStorage()
08-24 14:03:40.119  7097  7097 I libpersona: KNOX_SDCARD checking this for 10068
08-24 14:03:40.119  7097  7097 E Zygote  : v2
08-24 14:03:40.119  7097  7097 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:40.119  7097  7097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:40.129  7097  7097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:40.129  7097  7097 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 14:03:40.129  1018  1502 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7097 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-24 14:03:40.129  1018  4251 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-24 14:03:40.129  1018  4251 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-24 14:03:40.129  1018  4251 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:40.129  1018  4251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:40.129  1018  4251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-24 14:03:40.139  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,08-24 14:03:40.139  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.139  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.139  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.139  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:40.159   273   320 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-24 14:03:40.159   273   320 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-24 14:03:40.159   273   320 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1208719224) wakelock released: 1, error no: 0
08-24 14:03:40.159   273   320 I rmt_storage: 
,08-24 14:03:40.159   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7f467c8
,08-24 14:03:40.159  7097  7097 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:40.159  7097  7097 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:40.169  6937  7042 D Mms/ArtClassLoader: init [DONE] art
08-24 14:03:40.169  7112  7112 E Zygote  : MountEmulatedStorage()
08-24 14:03:40.169  7112  7112 I libpersona: KNOX_SDCARD checking this for 10042
08-24 14:03:40.169  7112  7112 E Zygote  : v2
08-24 14:03:40.169  7112  7112 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:40.169  7112  7112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:03:40.179  1018  1495 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7112 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a,
,08-24 14:03:40.179  1018  4247 I ActivityManager: Process ACMS.Process (pid 6742)(adj 0) has died(43,757)
,08-24 14:03:40.179  7112  7112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:40.179  7112  7112 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL,
,08-24 14:03:40.189  6937  7092 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 107.894219
,08-24 14:03:40.189   313   313 I art     : Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 19.853ms
,08-24 14:03:40.199  7112  7112 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:40.199  7112  7112 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:40.209  6895  7121 D OpenGLRenderer: Render dirty regions requested: true,
,08-24 14:03:40.209   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.792ms,
,08-24 14:03:40.219  1018  4251 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 14:03:40.219  1018  4251 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 14:03:40.219  1018  4251 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 14:03:40.219  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 14:03:40.219  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 14:03:40.219  6895  7058 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-24 14:03:40.219  6895  6895 V ActivityThread: updateVisibility : ActivityRecord{337b3cb5 token=android.os.BinderProxy@1259679f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 14:03:40.229  6895  6895 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 14:03:40.229  6895  6895 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-24 14:03:40.229  7112  7112 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:40.229   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.777ms
08-24 14:03:40.229  7112  7112 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-24 14:03:40.229  7112  7112 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 14:03:40.239  7097  7097 D BadgeProvider: onCreate
08-24 14:03:40.239  7097  7097 D BadgeProvider: DatabaseHelper
,08-24 14:03:40.249   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-24 14:03:40.309  6937  7130 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-24 14:03:40.309  6937  7130 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,08-24 14:03:40.329  1018  4247 I ActivityManager: Killing 6579:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-24 14:03:40.329  1018  4247 I ActivityManager: Killing 6617:com.qualcomm.timeservice/1000 (adj 15): empty #22
,08-24 14:03:40.339  1018  4260 D InputDispatcher: Focus entered window: 6895
,08-24 14:03:40.339  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:03:40.339  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:40.349  6937  7090 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-24 14:03:40.349  6895  6895 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-24 14:03:40.349  6895  7121 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:03:40.349  1480  1726 D TP/SmsProvider: query,matched:26, calling pid = 6937
08-24 14:03:40.349  6895  7121 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-24 14:03:40.349  6895  7121 D OpenGLRenderer: Enabling debug mode 0
08-24 14:03:40.359  1480  1726 D TP/SmsProvider: match 26:Elapsed time : 1.705 ms
08-24 14:03:40.359  1480  1494 D TP/MmsSmsProvider: query,matched:6, calling pid = 6937
08-24 14:03:40.369  1480  1494 D TP/MmsSmsProvider: match 6:Elapsed time : 2.126 ms
,08-24 14:03:40.379  1018  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 14:03:40.379  6846  6928 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-24 14:03:40.379  6846  6928 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 14:03:40.379  6846  6928 I GAv4    :   adb logcat -s GAv4
,08-24 14:03:40.379  1179  1179 D PanelView: There is/are notification(s) 
,08-24 14:03:40.389  1018  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-24 14:03:40.389  1018  6893 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-24 14:03:40.399  1018  6893 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.399  1018  6893 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.399  1018  6893 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.399  1018  6893 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.399  6895  6895 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 14:03:40.409  6895  6895 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1259679f time:97522
08-24 14:03:40.419  7138  7138 E Zygote  : MountEmulatedStorage()
08-24 14:03:40.419  7138  7138 E Zygote  : v2
08-24 14:03:40.419  7138  7138 I libpersona: KNOX_SDCARD checking this for 10023
08-24 14:03:40.419  7138  7138 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:40.419  1018  6893 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7138 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-24 14:03:40.429  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:40.429  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s659ms (total +1s782ms)
08-24 14:03:40.429  1018  1048 W ActivityManager: mDVFSHelper.release()
08-24 14:03:40.429  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26562864 u0 com.test.thalitest/.MainActivity t163} time:97542
08-24 14:03:40.429  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:40.429  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:40.439   258  1932 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-24 14:03:40.439   258   447 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-24 14:03:40.439  6846  6928 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-24 14:03:40.439  1018  1519 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-24 14:03:40.459  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:40.459  7138  7138 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:40.459  1018  1457 I ActivityManager: Killing 6641:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-24 14:03:40.469  7112  7112 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-24 14:03:40.479  1018  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-24 14:03:40.479  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-24 14:03:40.479  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.479  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.479  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.479  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.489  1018  1495 I art     : Explicit concurrent mark sweep GC freed 18979(1027KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.908ms total 236.506ms
08-24 14:03:40.489  7153  7153 E Zygote  : MountEmulatedStorage()
08-24 14:03:40.489  7153  7153 E Zygote  : v2
08-24 14:03:40.489  7153  7153 I libpersona: KNOX_SDCARD checking this for 10003
08-24 14:03:40.489  7153  7153 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:40.499  7153  7153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:40.499  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7153 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-24 14:03:40.499  1880  1880 I SamsungIME: getCurrentCandidateView
08-24 14:03:40.499  1018  1519 I ActivityManager: Killing 6656:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-24 14:03:40.499  7153  7153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:40.499  7153  7153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:40.519  7138  7138 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-24 14:03:40.519  7153  7153 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:40.529  7153  7153 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:40.549  6937  7090 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-24 14:03:40.569   284   284 E installd: system dir 0 : /system/app/
08-24 14:03:40.569   284   284 E installd: system dir 1 : /system/priv-app/
08-24 14:03:40.569   284   284 E installd: system dir 2 : /vendor/app/
08-24 14:03:40.569   284   284 E installd: system dir 3 : /oem/app/
08-24 14:03:40.569  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-24 14:03:40.569  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-24 14:03:40.569  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-24 14:03:40.569  6846  6928 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-24 14:03:40.569  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-24 14:03:40.569  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-24 14:03:40.569  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-24 14:03:40.579  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-24 14:03:40.579  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-24 14:03:40.579  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-24 14:03:40.579  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-24 14:03:40.579  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-24 14:03:40.579  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-24 14:03:40.579  7138  7138 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-24 14:03:40.599  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-24 14:03:40.609  6846  7173 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-24 14:03:40.619  6846  6928 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-24 14:03:40.659  6895  6895 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6895
08-24 14:03:40.689   292   292 E SMD     : DCD OFF
08-24 14:03:40.719  1811  4400 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-24 14:03:40.779  1811  4400 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-24 14:03:40.779  1880  1880 D SamsungIME: Dismiss ExpandCandiate
08-24 14:03:40.839  1811  4400 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-24 14:03:40.859  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-24 14:03:40.859  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.859  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.859  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.859  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.869  7183  7183 E Zygote  : MountEmulatedStorage()
08-24 14:03:40.869  7183  7183 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:40.869  7183  7183 E Zygote  : v2
08-24 14:03:40.869  7183  7183 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:40.869  7183  7183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:40.879  7183  7183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:40.879  7183  7183 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:40.889  1018  1495 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:40.889  1018  1495 I ActivityManager: Killing 5070:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-24 14:03:40.899  7183  7183 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:40.899  7183  7183 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:40.909  6895  6895 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-24 14:03:40.919  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 14:03:40.919  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:40.919  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:40.919  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:03:40.939  7183  7183 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-24 14:03:40.949  7183  7183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-24 14:03:40.949  1018  1329 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-24 14:03:40.949  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-24 14:03:40.949  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:40.949  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:40.949  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-24 14:03:40.949  6846  7181 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 14:03:40.949  6846  7181 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-24 14:03:40.959  1018  1031 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-24 14:03:40.959  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
08-24 14:03:40.959  7183  7183 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-24 14:03:40.959  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.959  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.959  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.959  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:40.969  7200  7200 E Zygote  : MountEmulatedStorage()
08-24 14:03:40.969  7200  7200 E Zygote  : v2
08-24 14:03:40.969  7200  7200 I libpersona: KNOX_SDCARD checking this for 10130
08-24 14:03:40.969  7200  7200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:40.969  7200  7200 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:40.979  7200  7200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:40.979  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7200 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-24 14:03:40.979  7200  7200 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-24 14:03:40.979  7183  7199 E FilterInstaller: installFilters
08-24 14:03:40.989  7183  7199 E FilterInstaller: There is no requred permission
08-24 14:03:40.989  1018  1030 I ActivityManager: Killing 6690:com.sec.spp.push/u0a32 (adj 15): empty #21
08-24 14:03:40.989  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
08-24 14:03:40.999  1018  3402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-24 14:03:40.999  7200  7200 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:41.009  7200  7200 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:41.019  6895  7136 D jxcore_app_log: JniHelper::setJavaVM(0xb836c2b0), pthread_self() = -1198595600
08-24 14:03:41.029  7200  7200 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:41.029  7200  7200 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
08-24 14:03:41.029  6895  7136 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:03:41.029  6895  7136 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:03:41.029  6895  7136 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:03:41.029  6895  7136 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:03:41.029  6895  7136 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 14:03:41.029  6895  7136 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0ef1f0 added. We now have 1 listener(s)
08-24 14:03:41.029  6846  7181 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-24 14:03:41.039  6895  7136 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-24 14:03:41.039  6895  7136 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 14:03:41.039  6895  7136 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:03:41.039  6895  7136 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:03:41.049  6895  7136 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2971768f added. We now have 1 listener(s)
08-24 14:03:41.049  6895  7136 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:03:41.049  6895  7136 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:03:41.049  6895  7136 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:03:41.049  6895  7136 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:03:41.049  6895  7136 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:03:41.049  6895  7136 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 14:03:41.059  6895  7136 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:03:41.059  1018  1457 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
08-24 14:03:41.059  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
08-24 14:03:41.059  1018  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:41.059  1018  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:41.059  1018  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:41.059  1018  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:41.069  1880  1880 I SamsungIME: KeybaordView init() : load resources
08-24 14:03:41.079  7217  7217 E Zygote  : MountEmulatedStorage()
08-24 14:03:41.079  7217  7217 I libpersona: KNOX_SDCARD checking this for 10131
08-24 14:03:41.079  7217  7217 E Zygote  : v2
08-24 14:03:41.079  7217  7217 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:41.079  7217  7217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:41.079  1018  1457 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7217 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-24 14:03:41.079  7217  7217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:41.079  7217  7217 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:41.079  1018  1457 I ActivityManager: Killing 6703:com.samsung.helphub/1000 (adj 15): empty #21
08-24 14:03:41.089  6895  7136 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-24 14:03:41.099  6895  7136 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-24 14:03:41.099  6846  7181 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-24 14:03:41.099  6846  7181 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6800eb0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-24 14:03:41.099  6846  7181 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:03:41.099  6895  7136 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:03:41.099  6895  7136 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:03:41.099  6895  7136 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:03:41.099  6895  7136 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 14:03:41.109  7217  7217 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:41.109  6895  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:03:41.109  7217  7217 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:41.109  6895  6895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:03:41.119  1880  1880 I SamsungIME: getCurrentKeyboard
08-24 14:03:41.119  1880  1880 I SamsungIME: getTextKeyboard
08-24 14:03:41.129  7217  7217 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 14:03:41.129  7217  7217 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:41.129  7217  7217 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:41.139  6895  6895 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:03:41.149  1880  1880 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-24 14:03:41.169  2666  2676 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 14:03:41.199  1018  4252 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-24 14:03:41.199  1018  4252 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-24 14:03:41.199  1018  4252 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:41.199  1018  4252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:41.199  1018  4252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-24 14:03:41.219  1018  4247 I ActivityManager: Killing 6671:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-24 14:03:41.249  1018  1503 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-24 14:03:41.249  1018  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-24 14:03:41.249  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:41.249  1018  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:41.249  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-24 14:03:41.259  1018  6892 I ActivityManager: Killing 6758:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-24 14:03:41.789  6895  7232 W jxcore-log: Initializing JXcore engine
08-24 14:03:41.789  6895  7232 W jxcore-log: JXcore engine is ready
,08-24 14:03:41.849  1953  1953 E audit   : type=1400 msg=audit(1472040221.849:205): avc:  denied  { ioctl } for  pid=7232 comm="Thread-1305" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 14:03:41.849  1953  1953 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:41.849  1953  1953 E audit   : type=1300 msg=audit(1472040221.849:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f1fb8f8 items=0 ppid=313 ppcomm=main pid=7232 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1305" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-24 14:03:41.849  1953  1953 E audit   : type=1320 msg=audit(1472040221.849:205): 
,08-24 14:03:41.859  6895  7232 W jxcore-log: Starting JXcore engine
,08-24 14:03:41.969  6895  7232 W jxcore-log: Platform android
08-24 14:03:41.969  6895  7232 W jxcore-log: 
08-24 14:03:41.969  6895  7232 W jxcore-log: Process ARCH arm
08-24 14:03:41.969  6895  7232 W jxcore-log: 
,08-24 14:03:42.029  6937  6937 I Mms/MmsApp:  start initViewCache mms
,08-24 14:03:42.029  6937  6937 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1846.018385
08-24 14:03:42.029  6937  6937 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-24 14:03:42.129  6937  6937 D AbsListView: Get MotionRecognitionManager
,08-24 14:03:42.139  1018  1461 D MotionRecognitionService:  ssp status : false
,08-24 14:03:42.139  6937  6937 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 109.407135
,08-24 14:03:42.179  6895  7232 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:03:42.179  6895  7232 I jxcore-log: 
,08-24 14:03:42.179  6895  7232 W jxcore-log: JXcore engine is started
,08-24 14:03:42.189  6895  7136 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:03:42.189  6895  6895 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 14:03:42.229  6937  6937 D Mms/BubbleViewCache: fillCache bubble = 1
,08-24 14:03:43.699   292   292 E SMD     : DCD OFF
,08-24 14:03:44.989  1659  1659 I ConfigService: onDestroy
,08-24 14:03:45.029  1018  3372 D SSRM:n  : SIOP:: AP = 400
,08-24 14:03:45.999  1018  3402 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:03:46.699   292   292 E SMD     : DCD OFF,
,08-24 14:03:48.679  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 14:03:48.849  1018  4247 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 14:03:48.849  1018  4247 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4266, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 14:03:48.849  1018  4247 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 14:03:48.849  1018  4247 D BatteryService: stay LED for charging
,08-24 14:03:48.849  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 14:03:48.849  1018  1018 I MotionRecognitionService: Plugged
,08-24 14:03:48.849  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:03:48.859  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 14:03:48.859  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:03:48.859  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 14:03:48.859  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:03:48.879  3203  3203 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:03:48.879  3203  3344 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:03:48.889  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:03:48.889  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:03:48.889  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:03:49.699   292   292 E SMD     : DCD OFF
,08-24 14:03:50.049  6895  7232 E jxcore  : Error!: syntax error
08-24 14:03:50.049  6895  7232 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"14","_columnNumber":"19","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"}]
,08-24 14:03:50.059  6895  6895 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-24 14:03:50.059  6895  6895 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-24 14:03:50.069  1018  1461 D FocusedStackFrame: Set to : 0
08-24 14:03:50.069  1018  1461 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:03:50.069  1018  1461 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 14:03:50.069  1018  1461 D InputDispatcher: Focused application set to: xxxx
08-24 14:03:50.069  1018  1461 D InputDispatcher: Focus left window: 6895
08-24 14:03:50.079  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:03:50.079  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:50.079  1018  1461 I ActivityManager: Killing 6721:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-24 14:03:50.079  6895  6895 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 14:03:50.089  6895  6895 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-24 14:03:50.089  6895  6895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:03:50.089  6895  6895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:03:50.089  6895  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:03:50.089  6895  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:03:50.089  6895  6895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0ef1f0 removed from the list
08-24 14:03:50.089  6895  6895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:03:50.089  6895  6895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2971768f removed from the list
08-24 14:03:50.089  6895  6895 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:03:50.089  6895  6895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-24 14:03:50.089  6895  7136 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,08-24 14:03:50.099  6895  6895 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 14:03:50.109   258   442 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
08-24 14:03:50.109   258   447 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-24 14:03:50.129  1018  1031 W ActivityManager: mDVFSHelper.acquire()
,08-24 14:03:50.149  1018  1031 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-24 14:03:50.159  1504  1504 D Launcher: onRestart, Launcher: 119927889
,08-24 14:03:50.159  1504  1504 D Launcher: onStart, Launcher: 119927889
,08-24 14:03:50.159  1504  1504 D Launcher.HomeView: onStart
08-24 14:03:50.159  1504  1504 D Launcher: onResume, Launcher: 119927889
,08-24 14:03:50.159  1018  1137 D SettingsProvider: name = kids_home_mode
,08-24 14:03:50.159  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 14:03:50.169  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 14:03:50.169  1018  1137 D SettingsProvider: selectionArgs: false
,08-24 14:03:50.169  1018  1137 D SettingsProvider: selectionArgs: 10006
08-24 14:03:50.169  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 14:03:50.169  1018  1137 D SettingsProvider: ret = -1
,08-24 14:03:50.169  1504  1504 D Launcher.HomeView: onResume
,08-24 14:03:50.169  1504  1504 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-24 14:03:50.179  1504  1504 D MenuAppsGridFragment: onResume
,08-24 14:03:50.179  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.179  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.179  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-24 14:03:50.179  1504  1504 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-24 14:03:50.179  1504  1504 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-24 14:03:50.179  1018  1137 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-24 14:03:50.179  1018  1137 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-24 14:03:50.179  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:50.179  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.189  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-24 14:03:50.189  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-24 14:03:50.189  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.189  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.189  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.189  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.199  7247  7247 E Zygote  : MountEmulatedStorage()
08-24 14:03:50.199  1018  1137 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7247 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-24 14:03:50.199  7247  7247 E Zygote  : v2
08-24 14:03:50.199  7247  7247 I libpersona: KNOX_SDCARD checking this for 10039
08-24 14:03:50.199  7247  7247 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:50.209  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:50.209  1018  1461 D ActivityManager: handle home activity for 0
08-24 14:03:50.209  1018  1461 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-24 14:03:50.209  1018  1461 D KnoxTimeoutHandler: post home show event for user 0
08-24 14:03:50.209  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-24 14:03:50.209  1018  1461 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 14:03:50.209  1018  1461 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 14:03:50.209  1018  1461 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 14:03:50.209  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-24 14:03:50.209  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-24 14:03:50.209  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 14:03:50.209  1504  1504 D Launcher.HomeView: onPause
08-24 14:03:50.209  1504  1504 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-24 14:03:50.209  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:50.209  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-24 14:03:50.209  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.209  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.209  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-24 14:03:50.219  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-24 14:03:50.219  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.219  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.219  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-24 14:03:50.219  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.219  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.219  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.219  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.229  7260  7260 E Zygote  : MountEmulatedStorage()
08-24 14:03:50.229  7260  7260 I libpersona: KNOX_SDCARD checking this for 10089
08-24 14:03:50.229  7260  7260 E Zygote  : v2
08-24 14:03:50.229  7260  7260 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:50.239  7260  7260 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:50.239  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7260 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-24 14:03:50.239  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.239  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.239  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-24 14:03:50.239  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,08-24 14:03:50.239  7260  7260 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:50.239  7260  7260 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
08-24 14:03:50.239  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.239  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.239  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.239  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.239  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-24 14:03:50.249  7247  7247 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:50.259  7272  7272 E Zygote  : MountEmulatedStorage(),
08-24 14:03:50.259  7272  7272 E Zygote  : v2
08-24 14:03:50.259  7272  7272 I libpersona: KNOX_SDCARD checking this for 10139
08-24 14:03:50.259  7272  7272 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:50.259  7272  7272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:03:50.259  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7272 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
08-24 14:03:50.259  7272  7272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:50.259  7272  7272 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:50.279   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-24 14:03:50.279  1018  6893 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.279  1018  6893 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1504, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-24 14:03:50.279  1018  6893 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.279  1018  6893 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-24 14:03:50.279  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-24 14:03:50.289  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.289  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.289  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-24 14:03:50.289  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-24 14:03:50.289  2609  2609 D Recents_RecreateReceiver: onReceive by home
,08-24 14:03:50.289  7272  7272 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:50.289  1018  1502 D InputDispatcher: Focus entered window: 1504
08-24 14:03:50.289  7272  7272 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:50.289  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.289  1018  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-24 14:03:50.289  1018  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.289  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-24 14:03:50.289  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:03:50.289  7260  7260 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:50.289  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:50.299  7260  7260 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:50.299  1504  1504 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 14:03:50.299  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.299  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.299  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.299  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.299  1504  1504 D Launcher.HomeView: onStop
08-24 14:03:50.299  1504  1504 V ActivityThread: updateVisibility : ActivityRecord{2316e523 token=android.os.BinderProxy@30afad93 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-24 14:03:50.299  1018  1457 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-24 14:03:50.299  7247  7247 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 14:03:50.299  7247  7247 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:50.299  7247  7247 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:50.299  7247  7247 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-24 14:03:50.299  7247  7247 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 14:03:50.299  7247  7247 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-24 14:03:50.299  1018  7293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-24 14:03:50.299  7247  7247 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 14:03:50.309  6895  6895 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-24 14:03:50.309  1880  1880 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,08-24 14:03:50.319  7295  7295 E Zygote  : MountEmulatedStorage()
08-24 14:03:50.319  7295  7295 E Zygote  : v2
08-24 14:03:50.319  7295  7295 I libpersona: KNOX_SDCARD checking this for 10084
08-24 14:03:50.319  7295  7295 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:50.319  7295  7295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:50.319  1179  1179 D PanelView: There is/are notification(s) ,
,08-24 14:03:50.319  7295  7295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:03:50.329  7295  7295 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,08-24 14:03:50.329  1018  1503 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7295 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-24 14:03:50.349  1504  1504 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30afad93 time:107465
,08-24 14:03:50.359  7260  7260 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:50.359  7260  7260 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-24 14:03:50.369  7295  7295 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:50.369  7244  7244 D AndroidRuntime: 
08-24 14:03:50.369  7244  7244 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:03:50.369  7295  7295 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:50.379  7244  7244 D AndroidRuntime: CheckJNI is OFF
08-24 14:03:50.379  7244  7244 D AndroidRuntime: readGMSProperty: start
08-24 14:03:50.379  7244  7244 D AndroidRuntime: readGMSProperty: already setted!!
08-24 14:03:50.379  7244  7244 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 14:03:50.379  7244  7244 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:03:50.379  7244  7244 D AndroidRuntime: readGMSProperty: end
08-24 14:03:50.379  7244  7244 D AndroidRuntime: addProductProperty: start
,08-24 14:03:50.379  1018  1048 W ActivityManager: mDVFSHelper.release()
08-24 14:03:50.389  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3cde217b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t162} time:107500
,08-24 14:03:50.389  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-24 14:03:50.399  7295  7295 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:50.419  7272  7272 V TaskCloserActivity: TaskCloserActivity enter()
,08-24 14:03:50.429  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.429  1018  1519 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-24 14:03:50.429  1018  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.429  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,08-24 14:03:50.429  7272  7272 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-24 14:03:50.429  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.429  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.429  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.429  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.439  7320  7320 E Zygote  : MountEmulatedStorage(),
08-24 14:03:50.439  7320  7320 E Zygote  : v2
08-24 14:03:50.439  7320  7320 I libpersona: KNOX_SDCARD checking this for 10135
08-24 14:03:50.439  7320  7320 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:50.439  7320  7320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:50.439  1018  1519 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7320 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,08-24 14:03:50.439  1018  1519 I ActivityManager: Killing 6193:com.samsung.android.sm/1000 (adj 15): empty #21
,08-24 14:03:50.449  1018  1519 I ActivityManager: Killing 6806:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-24 14:03:50.449  7320  7320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:50.449  7320  7320 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:50.449  1018  1519 W ActivityManager: userId = 0, bbcId = -10000,
08-24 14:03:50.449  1018  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.449  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone,
08-24 14:03:50.449  1018  1519 I ActivityManager: Killing 6846:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-24 14:03:50.469  7320  7320 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:50.469  7320  7320 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:50.489  7320  7320 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-24 14:03:50.489  7320  7320 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 14:03:50.489  7320  7320 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-24 14:03:50.489  7320  7320 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-24 14:03:50.489  7320  7320 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 14:03:50.519  7247  7247 D NearbySource: Nearby Source Create!
,08-24 14:03:50.519  7247  7247 D NearbyContext: Nearby Context Create!
,08-24 14:03:50.519  7244  7244 E AffinityControl: AffinityControl: registerfunction enter
,08-24 14:03:50.529  1018  1031 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:50.539  1018  1503 I ActivityManager: Killing 6830:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-24 14:03:50.549  7244  7244 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:03:50.559   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-24 14:03:50.559   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:03:50.559  1018  6892 D PackageManager: START PACKAGE DELETE: observer{490842962}
08-24 14:03:50.559  1018  6892 D PackageManager: pkg{<packageName>}
08-24 14:03:50.559  1018  6892 D PackageManager: user{0}
08-24 14:03:50.559  1018  6892 D PackageManager: caller{2000}
08-24 14:03:50.559  1018  6892 D PackageManager: flags{2}
08-24 14:03:50.559  1018  6892 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-24 14:03:50.559  1018  6892 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-24 14:03:50.559  1018  6892 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-24 14:03:50.559  1018  6892 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 14:03:50.559  1018  6892 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 14:03:50.559  7247  7247 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-24 14:03:50.559  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-24 14:03:50.559  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 14:03:50.559  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-24 14:03:50.559  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-24 14:03:50.559  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-24 14:03:50.559  7247  7247 D SLinkSource: Samsung link source created
,08-24 14:03:50.569  1018  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-24 14:03:50.569  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-24 14:03:50.569  1018  1043 I ActivityManager: Killing 6895:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-24 14:03:50.649  1018  1316 E Watchdog: !@Sync 3
,08-24 14:03:50.689  1018  4252 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:03:50.699  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-24 14:03:50.699  1018  1461 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:03:50.709  7247  7247 D GalleryCacheReady: Receive : home resume
,08-24 14:03:50.719  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-24 14:03:50.739  7183  7183 I art     : Explicit concurrent mark sweep GC freed 3764(196KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 1.090ms total 32.106ms
,08-24 14:03:50.749  2840  2840 I art     : Explicit concurrent mark sweep GC freed 17288(1019KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 778us total 33.041ms
,08-24 14:03:50.749  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:03:50.759  1880  1880 E SamsungIME: mOCRHelper is null
,08-24 14:03:50.769  1622  1857 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 14:03:50.769  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:50.769  1018  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.769  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-24 14:03:50.779  6937  6937 D Mms/UIEventReceiver: ui event
,08-24 14:03:50.779  1018  1031 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-24 14:03:50.779  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:50.779  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.779  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-24 14:03:50.789  7272  7272 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-24 14:03:50.799  1467  1467 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:50.799  1467  1467 D RegisteredServicesCache: empty dynamic service
,08-24 14:03:50.809  7247  7337 D ContactProvider: getAllContactInfoList Start
,08-24 14:03:50.819  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-24 14:03:50.819  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:03:50.819  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-24 14:03:50.819  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:03:50.819  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:03:50.819  2823  2823 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 24 14:03:50 GMT+02:00 2016
,08-24 14:03:50.829  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-24 14:03:50.829  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-24 14:03:50.829  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-24 14:03:50.829  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-24 14:03:50.829  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:03:50.829  1018  4247 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-24 14:03:50.829  1018  4247 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-24 14:03:50.829  1018  4247 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:50.829  1018  4247 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:50.829  1018  4247 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-24 14:03:50.839  2823  2823 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-24 14:03:50.839  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:50.839  1018  4252 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-24 14:03:50.839  1018  4252 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-24 14:03:50.849  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:50.849  1018  4252 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-24 14:03:50.849  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.849  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.849  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.849  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.859  2823  2823 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-24 14:03:50.859  2823  2823 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 14:03:50.869  2823  2823 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
08-24 14:03:50.869  7340  7340 E Zygote  : MountEmulatedStorage()
08-24 14:03:50.869  7340  7340 I libpersona: KNOX_SDCARD checking this for 10090
08-24 14:03:50.869  7340  7340 E Zygote  : v2
08-24 14:03:50.869  7340  7340 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:50.869  7340  7340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:50.869  7340  7340 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:50.869  1018  4252 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7340 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-24 14:03:50.869  7340  7340 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:50.879  2823  7339 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-24 14:03:50.889   313   313 I art     : Explicit concurrent mark sweep GC freed 8675(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 644us total 21.960ms
08-24 14:03:50.889  1467  1467 D RegisteredComponentCache: Collect Tech packages for Knox
08-24 14:03:50.889  1467  1467 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:50.899  2823  7339 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-24 14:03:50.899  2823  7339 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-24 14:03:50.899  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:03:50.899  1018  4251 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-24 14:03:50.899  1018  4251 D SecContentProvider2: mCursor = null
,08-24 14:03:50.899  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:03:50.909   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 17.856ms
,08-24 14:03:50.909  7340  7340 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:50.919  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-24 14:03:50.919  7340  7340 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:50.919  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.919  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.919  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.919  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.919  1018  1018 I art     : Explicit concurrent mark sweep GC freed 30539(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/34MB, paused 4.391ms total 203.757ms
08-24 14:03:50.919  2823  7339 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-24 14:03:50.929  1018  1058 I art     : WaitForGcToComplete blocked for 113.468ms for cause Explicit
,08-24 14:03:50.929  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:50.929   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 17.128ms
,08-24 14:03:50.939  7355  7355 E Zygote  : MountEmulatedStorage(),
08-24 14:03:50.939  7355  7355 E Zygote  : v2
08-24 14:03:50.939  7355  7355 I libpersona: KNOX_SDCARD checking this for 10032
08-24 14:03:50.939  7355  7355 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:50.939  7355  7355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:50.949  1018  1043 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7355 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-24 14:03:50.949  7355  7355 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:50.949  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-24 14:03:50.949  7355  7355 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 14:03:50.949  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:50.949  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.949  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:50.949  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.969  7364  7364 E Zygote  : MountEmulatedStorage()
08-24 14:03:50.969  7364  7364 E Zygote  : v2,
,08-24 14:03:50.969  1018  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7364 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-24 14:03:50.969  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
08-24 14:03:50.969  7364  7364 I libpersona: KNOX_SDCARD checking this for 10052
08-24 14:03:50.969  7364  7364 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:50.969  7364  7364 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:50.969  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.969  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.969  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:50.969  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:50.979  7364  7364 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:50.979  7364  7364 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:03:50.989  7377  7377 E Zygote  : MountEmulatedStorage()
,08-24 14:03:50.989  7377  7377 E Zygote  : v2
08-24 14:03:50.989  7377  7377 I libpersona: KNOX_SDCARD checking this for 10098
08-24 14:03:50.989  7377  7377 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:50.989  7377  7377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:50.999  7377  7377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 14:03:50.999  7377  7377 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:50.999  1018  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7377 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-24 14:03:50.999  7355  7355 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.009  7355  7355 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.019  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-24 14:03:51.019  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-24 14:03:51.019  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-24 14:03:51.019  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-24 14:03:51.019  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-24 14:03:51.019  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:51.029  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-24 14:03:51.039  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-24 14:03:51.039  7364  7364 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.039  7364  7364 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.039  7377  7377 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.049  7377  7377 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.049  2823  7339 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-24 14:03:51.059  2823  7339 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-24 14:03:51.069  2823  7339 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-24 14:03:51.069  2823  2823 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-24 14:03:51.079  7247  7337 D ContactProvider: getAllContactInfoList End
,08-24 14:03:51.079  7247  7337 I syncContacts: thread: 1358, sync time = 465
,08-24 14:03:51.099  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-24 14:03:51.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.109  7340  7340 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) },
08-24 14:03:51.109  1018  1031 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7400 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:51.109  7340  7340 D elm:15121: ELMEngine.ELMEngine( context ).
08-24 14:03:51.119  1018  1031 I ActivityManager: Killing 6920:com.sec.pcw.device/1000 (adj 15): empty #21
,08-24 14:03:51.119  7340  7340 D elm:15121: MDMBridge.setEnterpriseBridge(),
,08-24 14:03:51.119  7400  7400 E Zygote  : MountEmulatedStorage(),
08-24 14:03:51.119  1018  1502 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-24 14:03:51.119  1018  1502 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-24 14:03:51.129  1018  1502 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.129  1018  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:51.129  1018  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-24 14:03:51.129  7400  7400 E Zygote  : v2
,08-24 14:03:51.129  7400  7400 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:51.129  7400  7400 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.129  7400  7400 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 14:03:51.129  7340  7340 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-24 14:03:51.129  7400  7400 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:03:51.139  7400  7400 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:51.139  7340  7340 D elm:15121: ElmAgentService : onCreate(),
08-24 14:03:51.139  7340  7406 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-24 14:03:51.139  7340  7406 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-24 14:03:51.139  7340  7406 D elm:15121: MDMBridge.getInstance()
08-24 14:03:51.139  7340  7406 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-24 14:03:51.139  7340  7406 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-24 14:03:51.189  7400  7400 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.189  7400  7400 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.189  1018  1058 I art     : Explicit concurrent mark sweep GC freed 10271(725KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.992ms total 263.266ms
08-24 14:03:51.189  7340  7340 D elm:15121: ElmAgentService : onDestroy().
,08-24 14:03:51.209  1018  1030 I ActivityManager: Killing 6776:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-24 14:03:51.209  1018  1461 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-24 14:03:51.209  1018  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-24 14:03:51.219  1018  1461 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:51.219  1018  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:03:51.219  1018  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-24 14:03:51.219  1018  1502 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-24 14:03:51.219  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.219  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.219  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.219  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.229  7355  7417 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-24 14:03:51.229  7355  7417 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-24 14:03:51.239  7419  7419 E Zygote  : MountEmulatedStorage(),
08-24 14:03:51.239  7355  7417 D SPPClientService: PushLog.txt file is not deleted.
08-24 14:03:51.239  7355  7417 D SPPClientService: PushLog.txt file is not deleted.
08-24 14:03:51.239  7355  7417 D SPPClientService: ============PushLog. stop!
08-24 14:03:51.239  7419  7419 E Zygote  : v2
08-24 14:03:51.239  7419  7419 I libpersona: KNOX_SDCARD checking this for 10032,
08-24 14:03:51.249  7419  7419 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.249  7419  7419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:51.249  1018  1502 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7419 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:03:51.249  1018  1502 I ActivityManager: Killing 6972:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-24 14:03:51.249  7419  7419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:51.249  7419  7419 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
08-24 14:03:51.259  1018  1503 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-24 14:03:51.259  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.259  1018  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-24 14:03:51.259  1018  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.259  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-24 14:03:51.269  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-24 14:03:51.279  1018  1502 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-24 14:03:51.279  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.279  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.279  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.279  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.289  7419  7419 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.289  7419  7419 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.289  7435  7435 E Zygote  : MountEmulatedStorage()
08-24 14:03:51.289  7435  7435 E Zygote  : v2
08-24 14:03:51.289  7435  7435 I libpersona: KNOX_SDCARD checking this for 10055
08-24 14:03:51.289  7435  7435 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.299  7435  7435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:51.299  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:51.299  7435  7435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:51.299  7435  7435 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:51.299  1018  1502 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7435 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-24 14:03:51.299  1018  1502 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
08-24 14:03:51.299  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.299  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.309  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.309  1018  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.319  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-24 14:03:51.329  1018  1502 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-24 14:03:51.329  7444  7444 E Zygote  : MountEmulatedStorage()
,08-24 14:03:51.329  7444  7444 E Zygote  : v2
08-24 14:03:51.329  7444  7444 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:51.329  7444  7444 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.329  7444  7444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:03:51.329  7444  7444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:51.329  7444  7444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:51.339  1018  1502 I ActivityManager: Killing 6990:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21,
,08-24 14:03:51.339  7435  7435 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.339  7435  7435 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.349  1018  1058 D PackageManager: delete codoeFile: 
,08-24 14:03:51.359  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-24 14:03:51.359  1018  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-24 14:03:51.359  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:51.359  1018  1058 D PackageManager: result of delete: 1{490842962}
,08-24 14:03:51.369  7444  7444 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.369  7444  7444 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.379  7244  7244 D AndroidRuntime: Shutting down VM
,08-24 14:03:51.409  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-24 14:03:51.419  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 14:03:51.419  7435  7435 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-24 14:03:51.419  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 14:03:51.419  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-24 14:03:51.419  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 14:03:51.419  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-24 14:03:51.429  1018  3372 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-24 14:03:51.429  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 14:03:51.429  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:51.429  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:51.429  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:51.439  7419  7466 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-24 14:03:51.439  7419  7466 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-24 14:03:51.439  7419  7466 D SPPClientService: PushLog.txt file is not deleted.
,08-24 14:03:51.439  7419  7466 D SPPClientService: PushLog.txt file is not deleted.
,08-24 14:03:51.439  7419  7466 D SPPClientService: ============PushLog. stop!
,08-24 14:03:51.439  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:51.449  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:51.449  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:51.449  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 14:03:51.449  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:51.449  7444  7444 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
08-24 14:03:51.449  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:51.449  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 14:03:51.459  1018  6892 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,08-24 14:03:51.459  1018  6892 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-24 14:03:51.459  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:51.459  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 14:03:51.459  1018  6892 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.459  1018  6892 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:03:51.459  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:51.459  1018  6892 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-24 14:03:51.459  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-24 14:03:51.459  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-24 14:03:51.459  1018  4251 I ActivityManager: Killing 7013:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-24 14:03:51.469  7435  7435 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-24 14:03:51.469  7435  7435 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-24 14:03:51.469  7435  7435 D UserAnalysis: Create SecureDbHelper
,08-24 14:03:51.469  1018  4251 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-24 14:03:51.469  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.469  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.469  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.469  1018  4251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.489  7470  7470 E Zygote  : MountEmulatedStorage()
08-24 14:03:51.489  7470  7470 E Zygote  : v2
08-24 14:03:51.489  7470  7470 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:51.489  7470  7470 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.489  7470  7470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:51.489  7470  7470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:51.489  1018  4251 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7470 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-24 14:03:51.489  7470  7470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-24 14:03:51.489  1018  6893 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-24 14:03:51.489  1018  6893 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-24 14:03:51.499  7435  7435 D IntelligenceServiceApplication: onCreate()
,08-24 14:03:51.499  1018  6893 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.499  1018  6893 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-24 14:03:51.499  1018  6893 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
08-24 14:03:51.499  1018  1519 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
08-24 14:03:51.499  7435  7435 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-24 14:03:51.509  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.509  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.509  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.509  1018  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.509  7435  7435 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-24 14:03:51.509  7470  7470 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.509  7470  7470 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.519  7484  7484 E Zygote  : MountEmulatedStorage()
08-24 14:03:51.519  7484  7484 E Zygote  : v2
08-24 14:03:51.519  7484  7484 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:51.519  7484  7484 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.519  7484  7484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:51.529  1018  1519 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:51.529  1018  1519 I ActivityManager: Killing 7034:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-24 14:03:51.529  7484  7484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:51.529  7484  7484 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:51.529  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-24 14:03:51.529  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-24 14:03:51.539  7247  7247 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-24 14:03:51.549  1018  4247 D LocationManagerService: getProviders()=[passive, gps]
,08-24 14:03:51.559  7484  7484 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.559  7484  7484 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.569  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-24 14:03:51.569  7484  7484 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:51.569  1018  4247 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,08-24 14:03:51.579  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:51.579  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.579  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.579  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.579  7470  7507 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,08-24 14:03:51.579  7470  7507 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-24 14:03:51.589  7244  7244 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-24 14:03:51.599  7508  7508 E Zygote  : MountEmulatedStorage()
08-24 14:03:51.599  7508  7508 I libpersona: KNOX_SDCARD checking this for 10014
08-24 14:03:51.599  7508  7508 E Zygote  : v2
08-24 14:03:51.599  7508  7508 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:51.599  7508  7508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:51.599  7508  7508 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:51.599  1018  4247 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7508 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-24 14:03:51.599  7508  7508 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:03:51.599  1018  4252 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-24 14:03:51.609  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:51.609  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.609  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.609  1018  4252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.609  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
08-24 14:03:51.609  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-24 14:03:51.609  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-24 14:03:51.609  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-24 14:03:51.619  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-24 14:03:51.629  7520  7520 E Zygote  : MountEmulatedStorage()
08-24 14:03:51.629  7520  7520 E Zygote  : v2
08-24 14:03:51.629  7520  7520 I libpersona: KNOX_SDCARD checking this for 10117
08-24 14:03:51.629  7520  7520 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.629  7520  7520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:51.629  7520  7520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:51.629  7520  7520 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:03:51.629  7508  7508 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.639  7508  7508 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:51.639  1018  4252 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7520 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-24 14:03:51.649  1018  4252 I ActivityManager: Killing 6955:com.android.vending/u0a26 (adj 15): empty #21
,08-24 14:03:51.649  7435  7435 D BluetoothAdapter: cancelDiscovery
,08-24 14:03:51.659  1018  1329 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-24 14:03:51.659  1018  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-24 14:03:51.659   313   313 I art     : Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 22.535ms
,08-24 14:03:51.659  1018  1329 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.659  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 14:03:51.659  1018  1058 D PackageManager: userId{-1}
08-24 14:03:51.659  1018  1058 D PackageManager: andCode{true}
08-24 14:03:51.659  1018  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:51.659  1018  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-24 14:03:51.669  7520  7520 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:51.669  7520  7520 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.669  1659  1659 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-24 14:03:51.669  1659  1659 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-24 14:03:51.679  7470  7470 D AcmsService: Enter Oncreate
08-24 14:03:51.679  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-24 14:03:51.679  7470  7470 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:51.679  1018  1058 D PackageManager: [MSG] MCS_UNBIND
08-24 14:03:51.679  7470  7470 D AcmsService: creating AcmsCore
08-24 14:03:51.679  7470  7470 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-24 14:03:51.679  7470  7470 D AcmsCore: AcmsCore
,08-24 14:03:51.679   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 678us total 21.082ms
,08-24 14:03:51.679  6937  6937 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
08-24 14:03:51.679  3203  3236 D BluetoothAdapterProperties: mDiscovering is false
08-24 14:03:51.679  3203  3236 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-24 14:03:51.689  7435  7435 D BluetoothAdapter: cancelDiscovery = true
,08-24 14:03:51.689  7435  7435 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-24 14:03:51.689  7470  7470 D AcmsCore: init
08-24 14:03:51.689  7470  7470 D AcmsCore: Looper handler is not null
08-24 14:03:51.689  7470  7470 D AcmsCore: Post to AcmsCoreHandler
08-24 14:03:51.689  7470  7470 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:51.689  7470  7470 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-24 14:03:51.689  7470  7470 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-24 14:03:51.689  7470  7470 D AcmsService: onStartCommand
08-24 14:03:51.689  7470  7470 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-24 14:03:51.689  7470  7470 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-24 14:03:51.689  7470  7470 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-24 14:03:51.689  7470  7470 D AcmsService: Incremented Counter Value : onStartCommand
,08-24 14:03:51.689  7364  7426 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 14:03:51.689  7470  7540 D AcmsCertificateMngr: AcmsCertificateMngr
,08-24 14:03:51.699  7470  7540 D AcmsRevocationMngr: AcmsRevocationMngr
08-24 14:03:51.699  1018  1137 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-24 14:03:51.699  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.699  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-24 14:03:51.699  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:51.699  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-24 14:03:51.699  1018  1519 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-24 14:03:51.699  7520  7520 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 14:03:51.699   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 799us total 18.806ms
,08-24 14:03:51.699  1018  4260 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink,
08-24 14:03:51.709   329   329 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 14:03:51.699  7470  7470 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-24 14:03:51.709  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-24 14:03:51.709   329   329 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
08-24 14:03:51.709  7435  7435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-24 14:03:51.719  1018  1519 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-24 14:03:51.719  1018  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-24 14:03:51.719  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.719  1018  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.719  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.729  1018  1461 I TactileAssist: enable value -1
08-24 14:03:51.729  1018  1461 I TactileAssist: internal enable value -1
08-24 14:03:51.729  1018  1461 I TactileAssist: intensity value -1
08-24 14:03:51.729  1018  1461 I TactileAssist: saveAppList value true
,08-24 14:03:51.729  6937  7542 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
08-24 14:03:51.729  6937  7542 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,08-24 14:03:51.729  1018  1461 I TactileAssist: List of disabled apps :
,08-24 14:03:51.739  1811  7543 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 14:03:51.739  1811  7543 D AccountUtils: Clearing selected account for com.test.thalitest
,08-24 14:03:51.769  1018  1519 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:51.769  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.769  1018  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.769  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.769  1018  1329 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-24 14:03:51.769  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.769  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.769  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.769  1018  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:51.799  7549  7549 E Zygote  : MountEmulatedStorage()
,08-24 14:03:51.799  7549  7549 E Zygote  : v2
,08-24 14:03:51.799  7549  7549 I libpersona: KNOX_SDCARD checking this for 10048
08-24 14:03:51.799  7549  7549 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.799  7549  7549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 14:03:51.799  1018  1329 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7549 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-24 14:03:51.799  7549  7549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:51.809  7549  7549 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 14:03:51.809  1018  1502 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:51.809  1018  1502 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.809  1018  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.809  1018  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.829  7470  7470 D AcmsService: Inside handle Intent
08-24 14:03:51.829  7470  7470 D AcmsService: App removed - package name: com.test.thalitest
08-24 14:03:51.829  7470  7470 D AcmsCore: Post to AcmsCoreHandler
08-24 14:03:51.829  7470  7470 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:03:51.829  7470  7470 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-24 14:03:51.829  7470  7470 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
08-24 14:03:51.829  7470  7470 D AcmsService: Decremented Counter Value : handleStartIntent
08-24 14:03:51.829  7470  7470 D AcmsServiceMonitor: Decrementing - Counter value: 2
,08-24 14:03:51.829  1018  4247 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:03:51.829  1018  4247 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-24 14:03:51.829  1018  4247 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.829  1018  4247 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.829  1018  4247 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.839  7549  7549 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:51.839  7549  7549 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:51.849  1018  1519 I ActivityManager: Killing 7097:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-24 14:03:51.879  1811  7543 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-24 14:03:51.879  1811  1811 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-24 14:03:51.879  1811  1811 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-24 14:03:51.889  7364  7426 E SQLiteLog: (10) unixWrite() File Descriptor : 30 gets errno : 9
,08-24 14:03:51.899  1018  1457 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-24 14:03:51.899  1018  1457 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-24 14:03:51.899  7549  7549 D Compatibility: onReceive() it will make start service
,08-24 14:03:51.899  1811  7568 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,08-24 14:03:51.909  1018  1457 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.909  1018  1457 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.909  1018  1457 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.909  7484  7484 I art     : Explicit concurrent mark sweep GC freed 8589(403KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 724us total 150.539ms
,08-24 14:03:51.919  7484  7484 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
,08-24 14:03:51.919  1811  7568 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:03:51.919  1811  7568 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:03:51.919  1811  7568 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:03:51.919  1018  4260 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:51.919  1018  4260 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.919  1018  4260 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.919  1018  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.919  1018  1503 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-24 14:03:51.919  1018  1503 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-24 14:03:51.929  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:51.929  1018  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:51.929  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-24 14:03:51.929  1811  7568 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-24 14:03:51.929  1811  7568 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
08-24 14:03:51.929  1811  7568 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-24 14:03:51.929  1018  4247 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-24 14:03:51.929  1811  7568 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,08-24 14:03:51.929  1811  7568 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
08-24 14:03:51.929  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.929  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:51.929  1811  7568 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-24 14:03:51.929  1811  7568 E AndroidRuntime: Process: com.google.android.gms, PID: 1811
,08-24 14:03:51.929  1811  7568 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754),
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:03:51.929  1811  7568 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:03:51.929  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:51.929  1018  4247 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:51.939  1811  1811 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-24 14:03:51.939  1811  1811 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-24 14:03:51.939  7484  7484 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/seatbelt.db'.
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:43)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:31)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.b.<init>(ApkManager.java:52)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.b.a(ApkManager.java:36)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:174)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:03:51.939  7484  7484 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-24 14:03:51.939  7484  7484 D AndroidRuntime: Shutting down VM
,08-24 14:03:51.949  7484  7484 E AndroidRuntime: FATAL EXCEPTION: main
08-24 14:03:51.949  7484  7484 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7484
08-24 14:03:51.949  7484  7484 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:43)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:31)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at com.samsung.android.sm.common.security.b.<init>(ApkManager.java:52)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at com.samsung.android.sm.common.security.b.a(ApkManager.java:36)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:174)
08-24 14:03:51,.949  7484  7484 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-24 14:03:51.949  7484  7484 E AndroidRuntime: 	... 9 more
08-24 14:03:51.949  1018  4247 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:51.949  7571  7571 E Zygote  : MountEmulatedStorage()
08-24 14:03:51.949  7571  7571 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:51.949  7571  7571 E Zygote  : v2
08-24 14:03:51.949  7571  7571 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:51.949  7549  7569 D Compatibility: onHandleIntent()
,08-24 14:03:51.949  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:51.959  1018  4247 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm,
08-24 14:03:51.959  7484  7541 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
08-24 14:03:51.959  1018  1031 W ActivityManager: userId = 0, bbcId = -10000,
08-24 14:03:51.959  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.959  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.959  7571  7571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:51.959  7549  7569 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-24 14:03:51.959  7549  7569 D Compatibility: found: 2
08-24 14:03:51.959  7571  7571 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:51.959  7571  7571 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:51.969  7484  7541 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
08-24 14:03:51.969  1018  1503 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/seatbelt.db'.
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:43)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:31)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at com.samsung.android.sm.common.r.n(Utils.java:2240)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at com.samsung.android.sm.common.o.run(SmartManagerReceiver.java:125)
08-24 14:03:51.969  7484  7541 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 14:03:51.969  1018  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
08-24 14:03:51.969  7484  7541 I Process : Sending signal. PID: 7484 SIG: 9
08-24 14:03:51.969  1018  1503 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:51.969  1018  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:51.969  1018  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:51.969  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.969  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.969  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:51.969  1018  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
