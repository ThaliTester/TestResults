#### Test 503880190437b9b_thali07_samsung-SM-A500FU Logs


```--------- beginning of main
11-17 18:00:55.338  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.338  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.338  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
--------- beginning of system
11-17 18:00:55.338  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.338  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.338  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.338  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.358  4451  4451 E Zygote  : MountEmulatedStorage()
11-17 18:00:55.358  4451  4451 E Zygote  : v2
11-17 18:00:55.358  4451  4451 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:55.358  4451  4451 I libpersona: KNOX_SDCARD checking this for 10044
11-17 18:00:55.358  4451  4451 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:55.358  1017  1029 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=4451 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
11-17 18:00:55.368  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
11-17 18:00:55.368  1017  1029 I ActivityManager: Killing 3154:com.sec.pcw.device/1000 (adj 15): empty #31
11-17 18:00:55.378  4451  4451 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:55.378  4451  4451 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:00:55.388  4400  4400 E SystemInfo: [SIOP LEVEL] : 0
11-17 18:00:55.398  4451  4451 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:55.398  4451  4451 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:55.398  4400  4465 I DocumentService: [BEGIN SYNC] DocumentService beginIndexing :16
11-17 18:00:55.408  4400  4465 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
11-17 18:00:55.408   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
11-17 18:00:55.408   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.418  4451  4451 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:00:55.418  4451  4451 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:00:55.418  4451  4451 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
11-17 18:00:55.418  4451  4451 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:55.418  4451  4451 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
11-17 18:00:55.418  4451  4451 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:00:55.418  4451  4451 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
11-17 18:00:55.428  4451  4451 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
11-17 18:00:55.438  4400  4465 E File    : fail readDirectory() errno=13
11-17 18:00:55.438  4400  4465 E File    : fail readDirectory() errno=13
11-17 18:00:55.438  4400  4465 I SystemInfo: [SYSTEM STATUS] Battery and Storage levels are OK:
11-17 18:00:55.438  4400  4465 I DocumentService: [STOP DOCUMENTSERVICE] Attempting to stop the Service
11-17 18:00:55.438  4400  4465 E DocumentService: [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :51
11-17 18:00:55.438  4400  4465 E DocumentService: [THUMBNAIL] Total Time taken for each file :0
11-17 18:00:55.438  4400  4465 E         : [INDEX] Total time taken for each file :0
11-17 18:00:55.448  4400  4400 I DocumentService: DocumentService onDestroy start
11-17 18:00:55.448  4400  4400 I DocumentService: DocumentService onDestroy end
11-17 18:00:55.448  4400  4471 I DocumentService: DocumentService cleanupEverything start
11-17 18:00:55.448  1017  1493 I ActivityManager: Killing 3708:com.vlingo.midas/u0a31 (adj 15): empty #31
11-17 18:00:55.458  4400  4462 I IndexParserThreadsManager: InterruptedException: null
11-17 18:00:55.468  4400  4471 I SystemInfo: [SYSTEM STATUS] Battery and Storage levels are OK:
11-17 18:00:55.468  4400  4471 I DocumentService: DocumentService cleanupEverything end
11-17 18:00:55.468  4400  4471 I Process : Sending signal. PID: 4400 SIG: 9
,11-17 18:00:55.538  1017  1291 I ActivityManager: Process com.samsung.indexservice (pid 4400)(adj 9) has died(55,1161)
11-17 18:00:55.568  4451  4451 D NearbySource: Nearby Source Create!
11-17 18:00:55.568  4451  4451 D NearbyContext: Nearby Context Create!
11-17 18:00:55.588   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
11-17 18:00:55.588   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.588  4451  4451 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
11-17 18:00:55.588  4451  4451 D SLinkSource: Samsung link source created
11-17 18:00:55.588  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3154/cgroup.procs: No such file or directory
11-17 18:00:55.588  1017  1041 W libprocessgroup: failed to open /acct/uid_10031/pid_3708/cgroup.procs: No such file or directory
11-17 18:00:55.608  4451  4476 D ContactProvider: getAllContactInfoList Start
11-17 18:00:55.618  1017  1706 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
11-17 18:00:55.618  1017  1706 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
11-17 18:00:55.618  4451  4451 D GalleryCacheReady: Receive action.ACTION_MEDIA_SCANNER_FINISHED
11-17 18:00:55.618  4451  4477 D GalleryCacheReady: handleMeidaScanFinish()
11-17 18:00:55.618  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.618  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
11-17 18:00:55.618  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
11-17 18:00:55.628  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.628  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
11-17 18:00:55.628  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
11-17 18:00:55.628  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
11-17 18:00:55.628  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.638  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:55.638  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
11-17 18:00:55.638  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.638  1017  1291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.638  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
11-17 18:00:55.648  1017  3532 D SettingsProvider: name = icc_lock_enable
11-17 18:00:55.648  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.648  1017  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.648  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
11-17 18:00:55.658  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
11-17 18:00:55.658  1286  1286 I SettingSearch/SearchIntentReceiver: action : com.samsung.settings.CHANGED_ICC_LOCK_ENABLE
11-17 18:00:55.658   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
11-17 18:00:55.658   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.658  4451  4476 D ContactProvider: getAllContactInfoList End
11-17 18:00:55.658  4451  4476 I syncContacts: thread: 718, sync time = 61
11-17 18:00:55.658  4451  4477 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
11-17 18:00:55.668  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.668  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.668  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.sec.smartcard.manager
11-17 18:00:55.668  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.668  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.668  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.668  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.678  4480  4480 E Zygote  : MountEmulatedStorage()
11-17 18:00:55.678  4480  4480 I libpersona: KNOX_SDCARD checking this for 10153
11-17 18:00:55.678  4480  4480 E Zygote  : v2
11-17 18:00:55.678  4480  4480 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:55.678  4480  4480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:55.688  1017  1030 I ActivityManager: Start proc com.sec.smartcard.manager for broadcast com.sec.smartcard.manager/com.sec.smartcard.pinservice.SmartCardBroadcastReceiver: pid=4480 uid=10153 gids={50153, 9997, 3001, 3002} abi=armeabi-v7a
11-17 18:00:55.688  4480  4480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:55.688  4480  4480 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:00:55.688  1017  2619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:00:55.688   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
11-17 18:00:55.688   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.688  4451  4477 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
11-17 18:00:55.698   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
11-17 18:00:55.698   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.698  4451  4477 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
11-17 18:00:55.698   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
11-17 18:00:55.698   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.698  4451  4477 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
11-17 18:00:55.708   305   305 I art     : Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.368ms total 24.142ms
11-17 18:00:55.708  4480  4480 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:55.708  4480  4480 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:55.708  4451  4477 D FaceInterface: requestFaceScan() is called.
11-17 18:00:55.708  4451  4477 W LocalSuggestAlbumData: query fail: 
11-17 18:00:55.718  4451  4477 W LocalSuggestAlbumData: query fail: 
11-17 18:00:55.718  4451  4495 I FaceInterface: startFaceScan() : waiting 5 sec
11-17 18:00:55.718  4480  4480 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
11-17 18:00:55.728   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.083ms
11-17 18:00:55.738   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.589ms
11-17 18:00:55.748  4480  4480 E SmartCardContentProvider: onCreate
11-17 18:00:55.748  4480  4480 I SmartCardBroadcastReceiver: SmartCardBroadcastReceiver - onReceive() 
11-17 18:00:55.748  4480  4480 I SmartCardBroadcastReceiver: Broadcast received for locktype changed 
11-17 18:00:55.748  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.748  1017  3532 I ActivityManager: Killing 3825:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
11-17 18:00:55.748  1017  3532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.748  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
11-17 18:00:55.758  1467  1467 E CscFactoryReceiver: onReceive android.intent.action.MEDIA_SCANNER_FINISHED
11-17 18:00:55.758  1467  1467 D CscFactoryReceiver: Media DB Scanner finished.
11-17 18:00:55.758  1467  1467 D CscFactoryReceiver: start service to Set Ringtone
11-17 18:00:55.758  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
11-17 18:00:55.758  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.758  1017  3531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.758  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
11-17 18:00:55.758  1467  1467 D CscFactoryReceiver: start service to Set Notification
11-17 18:00:55.758  1017  1280 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
11-17 18:00:55.758  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.758  1017  1280 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.758  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
11-17 18:00:55.758  1467  1467 D CscFactoryReceiver: start service to Set Alarmtone
11-17 18:00:55.758  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
11-17 18:00:55.758  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.758  1017  1291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.758  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
11-17 18:00:55.758  4473  4473 D AndroidRuntime: 
11-17 18:00:55.758  4473  4473 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:00:55.768  1467  1467 D CscUpdateService: onStart
11-17 18:00:55.768  1467  1467 E CscUpdateService: costomer file is exists : it has been preconfiged.
11-17 18:00:55.768  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.768  1467  1467 D CscUpdateService: only ringtone update
11-17 18:00:55.768  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.768  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.768  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.768  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.768  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.768  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
11-17 18:00:55.768  1467  1467 D CscUpdateService: onStart
11-17 18:00:55.768  1467  1467 E CscUpdateService: costomer file is exists : it has been preconfiged.
11-17 18:00:55.768  1467  1467 D CscUpdateService: only notification update
11-17 18:00:55.768  4473  4473 D AndroidRuntime: CheckJNI is OFF
11-17 18:00:55.768  1467  4497 E CscParser: update(): xml file exist
11-17 18:00:55.768  1467  1467 D CscUpdateService: onStart
11-17 18:00:55.768  1467  1467 E CscUpdateService: costomer file is exists : it has been preconfiged.
11-17 18:00:55.768  1467  1467 D CscUpdateService: only alarmtone update
11-17 18:00:55.768  4473  4473 D AndroidRuntime: readGMSProperty: start
11-17 18:00:55.768  4473  4473 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:00:55.768  4473  4473 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-17 18:00:55.768  4473  4473 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:00:55.768  4473  4473 D AndroidRuntime: readGMSProperty: end
11-17 18:00:55.768  4473  4473 D AndroidRuntime: addProductProperty: start
11-17 18:00:55.768  1467  4498 E CscParser: update(): xml file exist
11-17 18:00:55.768  1467  4499 E CscParser: update(): xml file exist
11-17 18:00:55.778  1467  4497 W CSCSettings: Setting Ringtones (type) : 1
11-17 18:00:55.778  1467  4497 D CscParser: RingTone: null
11-17 18:00:55.778  1467  4497 W CSCSettings: 1. Tag_Str: null
11-17 18:00:55.778  1467  4498 W CSCSettings: Setting Ringtones (type) : 2
11-17 18:00:55.778  1467  4498 D CscParser: MessageTone: null
11-17 18:00:55.778  1467  4498 W CSCSettings: 1. Tag_Str: null
11-17 18:00:55.778  4500  4500 E Zygote  : MountEmulatedStorage()
11-17 18:00:55.778  4500  4500 I libpersona: KNOX_SDCARD checking this for 10006
11-17 18:00:55.778  4500  4500 E Zygote  : v2
11-17 18:00:55.778  4500  4500 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:55.778  1467  4499 W CSCSettings: Setting Ringtones (type) : 4
11-17 18:00:55.778  1467  4499 D CscParser: AlarmTone: null
11-17 18:00:55.778  1467  4499 W CSCSettings: 1. Tag_Str: null
11-17 18:00:55.778  4500  4500 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:55.788  4500  4500 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:55.788  4500  4500 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:00:55.788  1017  1216 I ActivityManager: Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=4500 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
11-17 18:00:55.798  4500  4500 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:55.798  4500  4500 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:55.868  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3825/cgroup.procs: No such file or directory
11-17 18:00:55.868  4500  4500 I ThumbnailProvider: ThumbnailProvider onCreate()
11-17 18:00:55.878  4500  4500 I DocumentBroadcastReceiver: DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
11-17 18:00:55.878  4500  4500 I BroadcastProcessorService: [START] processBroadcastIntent ...
11-17 18:00:55.878  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
11-17 18:00:55.878  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.878  1017  3531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.878  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
11-17 18:00:55.878  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.878  1017  1280 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.878  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
11-17 18:00:55.888  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.888  1017  1291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.888  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
11-17 18:00:55.898  4500  4522 I BroadcastProcessorService: DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
11-17 18:00:55.898  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.898  1017  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.898  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
11-17 18:00:55.908  4451  4451 D GalleryCacheReady: Receive action.ACTION_MEDIA_SCANNER_FINISHED
11-17 18:00:55.908  4500  4522 I SystemInfo: [SYSTEM STATUS] Battery and Storage levels are OK:
11-17 18:00:55.908  4500  4522 I BroadcastProcessorService: [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
11-17 18:00:55.908  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
11-17 18:00:55.908  4500  4522 I BroadcastProcessorService: [START] DocumentService startDocumentService
11-17 18:00:55.908  4451  4524 D GalleryCacheReady: handleMeidaScanFinish()
11-17 18:00:55.908  4451  4524 D FaceInterface: requestFaceScan() is called.
11-17 18:00:55.908  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.908  1017  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:55.908  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
11-17 18:00:55.908  4451  4524 W LocalSuggestAlbumData: query fail: 
11-17 18:00:55.908  4451  4524 W LocalSuggestAlbumData: query fail: 
11-17 18:00:55.908  4500  4500 I DocumentService: DocumentService onCreate ... service
11-17 18:00:55.918  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.918  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
11-17 18:00:55.918  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
11-17 18:00:55.918  4451  4525 I FaceInterface: startFaceScan() : waiting 5 sec
11-17 18:00:55.918  1017  1280 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
11-17 18:00:55.918   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
11-17 18:00:55.918   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.928  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.928  1017  1280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:55.928  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
11-17 18:00:55.928  4500  4500 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
11-17 18:00:55.928   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
11-17 18:00:55.928   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.928  4500  4500 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
11-17 18:00:55.928  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
11-17 18:00:55.928  4473  4473 E AffinityControl: AffinityControl: registerfunction enter
11-17 18:00:55.928  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.928  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:55.928  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
11-17 18:00:55.948  4500  4500 E SystemInfo: [SIOP LEVEL] : 0
11-17 18:00:55.958  4473  4473 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:00:55.958  1017  3532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
11-17 18:00:55.958  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:55.958  1017  3532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:55.958  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
11-17 18:00:55.958  1649  2491 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
11-17 18:00:55.958  1017  1291 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
11-17 18:00:55.958  1017  1291 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
11-17 18:00:55.958  1017  1291 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
11-17 18:00:55.958  1017  1291 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
11-17 18:00:55.968  1017  1493 E PersonaManagerService: inState():  stateMachine is null !!
11-17 18:00:55.968  1017  1493 I PersonaManagerService: PersonaId don't exist
11-17 18:00:55.968  1017  1493 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
11-17 18:00:55.968  1649  1649 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
11-17 18:00:55.978  4500  4531 I DocumentService: [BEGIN SYNC] DocumentService beginIndexing :16
11-17 18:00:55.978  1017  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:00:55.978  4500  4531 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
11-17 18:00:55.978  1017  1493 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
11-17 18:00:55.978   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
11-17 18:00:55.978   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:00:55.978  1017  1493 W ActivityManager: mDVFSHelper.acquire()
11-17 18:00:55.978  1017  1493 D FocusedStackFrame: Set to : 0
11-17 18:00:55.988  1494  1494 D Launcher.HomeView: onPause
11-17 18:00:55.988  1017  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
11-17 18:00:55.988  1017  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:00:55.988  1017  1493 D InputDispatcher: Focused application set to: xxxx
11-17 18:00:55.988  1017  1493 D InputDispatcher: Focus left window: 1494
11-17 18:00:55.988  1494  1494 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
11-17 18:00:55.988  4473  4473 D AndroidRuntime: Shutting down VM
11-17 18:00:55.988  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
11-17 18:00:55.988  1017  1047 D PhoneWindow: *FMB* installDecor flags : 25362712
11-17 18:00:55.998  1933  1933 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
11-17 18:00:55.998  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:00:55.998  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:00:55.998  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
11-17 18:00:55.998  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
11-17 18:00:55.998   256   256 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, iello
11-17 18:00:55.998  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.998  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.998  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:55.998  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.018  1017  1777 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4533 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:00:56.018  4533  4533 E Zygote  : MountEmulatedStorage()
11-17 18:00:56.018  4533  4533 I libpersona: KNOX_SDCARD checking this for 10174
11-17 18:00:56.018  4533  4533 E Zygote  : v2
11-17 18:00:56.018  4533  4533 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:56.018  4533  4533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:56.018  4533  4533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:56.018  4533  4533 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
11-17 18:00:56.018  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
11-17 18:00:56.018  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.018  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:56.018  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:00:56.028  1494  1494 V ActivityThread: updateVisibility : ActivityRecord{a6cb1b7 token=android.os.BinderProxy@3335c6c3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
11-17 18:00:56.058  4533  4533 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:56.058  4533  4533 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:56.068  1017  1438 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
11-17 18:00:56.068  1017  1438 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
11-17 18:00:56.068  1017  1438 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
11-17 18:00:56.068  4500  4531 E File    : fail readDirectory() errno=13
11-17 18:00:56.068  4500  4531 E File    : fail readDirectory() errno=13
11-17 18:00:56.068  1494  1494 D Launcher.HomeView: onStop
11-17 18:00:56.068  1494  1494 V ActivityThread: updateVisibility : ActivityRecord{a6cb1b7 token=android.os.BinderProxy@3335c6c3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
11-17 18:00:56.068  1744  4545 E MDM     : [194] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
11-17 18:00:56.078  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:00:56.078  1017  1438 D PersonaManager: isKioskContainerExistOnDevice
11-17 18:00:56.098  4500  4531 I SystemInfo: [SYSTEM STATUS] Battery and Storage levels are OK:
11-17 18:00:56.098  4500  4531 I DocumentService: [STOP DOCUMENTSERVICE] Attempting to stop the Service
11-17 18:00:56.098  4500  4531 E DocumentService: [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :131
11-17 18:00:56.098  4500  4531 E DocumentService: [THUMBNAIL] Total Time taken for each file :0
11-17 18:00:56.098  4500  4531 E         : [INDEX] Total time taken for each file :0
11-17 18:00:56.098  1017  1777 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
11-17 18:00:56.108  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.108  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:56.108  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:00:56.118  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
11-17 18:00:56.118  1017  1017 D SensorService: [SO] activate (ident=0xb966b8d0, enabled=0)
11-17 18:00:56.118  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
11-17 18:00:56.128  1494  1494 D Launcher: onTrimMemory. Level: 20
11-17 18:00:56.128  1017  1017 D SensorManager: unregisterListener ::   
11-17 18:00:56.128  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
11-17 18:00:56.128  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
11-17 18:00:56.128  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.128  1017  1017 D SensorService: [SO] changed settle time [1]
11-17 18:00:56.128  1017  1017 D SensorService: [SO] setDelay [66000000]
11-17 18:00:56.128  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:56.128  1017  1017 D SensorService: [SO] activate (ident=0xb966b8d0, enabled=1)
11-17 18:00:56.128  1017  1017 D SensorService: [SO] AR_init
11-17 18:00:56.128  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:00:56.128  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
11-17 18:00:56.138  1933  4550 D LocationInitializer: Restart initialization of location
11-17 18:00:56.138  4500  4500 I DocumentService: DocumentService onDestroy start
11-17 18:00:56.138  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.138  1017  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:56.138  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.samsung.android.app.assistantmenu
11-17 18:00:56.138  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.138  4500  4500 I DocumentService: DocumentService onDestroy end
11-17 18:00:56.138  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.138  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.138  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.138  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
11-17 18:00:56.138  4500  4552 I DocumentService: DocumentService cleanupEverything start
11-17 18:00:56.148  4500  4527 I IndexParserThreadsManager: InterruptedException: null
11-17 18:00:56.158  1017  1438 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=4553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
11-17 18:00:56.158  4553  4553 E Zygote  : MountEmulatedStorage()
11-17 18:00:56.158  4553  4553 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:00:56.158  4553  4553 E Zygote  : v2
11-17 18:00:56.158  4553  4553 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:56.158  4553  4553 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:56.168  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
11-17 18:00:56.168  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.168  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:56.168  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:00:56.168  4553  4553 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:56.168  4553  4553 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:00:56.168  4500  4552 I SystemInfo: [SYSTEM STATUS] Battery and Storage levels are OK:
11-17 18:00:56.168  4500  4552 I DocumentService: DocumentService cleanupEverything end
11-17 18:00:56.168  4500  4552 I Process : Sending signal. PID: 4500 SIG: 9
11-17 18:00:56.198  4473  4473 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
11-17 18:00:56.208  1017  1039 D SensorService: [SO] Reset Rotation Old [100], Init [1]
11-17 18:00:56.208  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
11-17 18:00:56.208  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.208  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:56.208  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
11-17 18:00:56.208  1017  1049 D PowerManagerService: [s] UserActivityState : 1 -> 2
11-17 18:00:56.208  1017  1049 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-17 18:00:56.208  1017  1049 D DisplayPowerController: animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
11-17 18:00:56.208  1017  1049 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
11-17 18:00:56.208  1017  1049 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-17 18:00:56.208  1017  1049 D DisplayPowerController: animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
11-17 18:00:56.208  1017  1159 D lights  : lcd : 1 +
,11-17 18:00:56.228  4158  4181 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
11-17 18:00:56.228  4533  4533 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
11-17 18:00:56.228  1017  1159 D lights  : lcd : 1 -
11-17 18:00:56.228  1017  1049 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-17 18:00:56.228  1017  1049 D DisplayPowerController: animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
11-17 18:00:56.238  4553  4553 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:56.238  1933  1933 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
11-17 18:00:56.238  4553  4553 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:56.248  1017  1706 I ActivityManager: Process com.samsung.indexservice (pid 4500)(adj 9) has died(57,1151)
11-17 18:00:56.258  4533  4533 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5261-5263)
11-17 18:00:56.258  4533  4533 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:00:56.278  1017  1039 D SensorService: [SO] 0.192 0.077 10.190
11-17 18:00:56.278  1017  1039 D SensorService: [SO] [100 -> 255]
11-17 18:00:56.278  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{20ca57c6 u0 com.samsung.android.providers.context/.ContextService}
11-17 18:00:56.278  4533  4533 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a5c13c9}
11-17 18:00:56.278  4533  4533 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:00:56.278  4533  4533 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:00:56.288  4553  4553 D AssistantMenuSettingSearch: onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
11-17 18:00:56.288  4553  4553 D AssistantMenuSettingSearch: Make Setting DB
11-17 18:00:56.288  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.288  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.288  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.288  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.298  4342  4526 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
11-17 18:00:56.308  4575  4575 E Zygote  : MountEmulatedStorage()
11-17 18:00:56.308  4575  4575 I libpersona: KNOX_SDCARD checking this for 10150
11-17 18:00:56.308  4575  4575 E Zygote  : v2
11-17 18:00:56.308  4575  4575 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:56.308  4575  4575 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:56.308  1017  1216 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=4575 uid=10150 gids={50150, 9997} abi=armeabi-v7a
11-17 18:00:56.308  4575  4575 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:56.308  4575  4575 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
11-17 18:00:56.318  4533  4533 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-17 18:00:56.318  4533  4533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:00:56.318  4533  4533 E SysUtils: ApplicationContext is null in ApplicationStatus
11-17 18:00:56.328  4533  4588 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
11-17 18:00:56.328  4575  4575 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:56.338  4575  4575 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:56.338  4533  4533 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-17 18:00:56.348  4533  4533 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:00:56.348  4533  4533 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:00:56.348  4533  4533 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
11-17 18:00:56.348  4533  4533 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
11-17 18:00:56.348  4533  4533 I Adreno-EGL: Build Date: 04/06/15 Mon
11-17 18:00:56.348  4533  4533 I Adreno-EGL: Local Branch: 
11-17 18:00:56.348  4533  4533 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
11-17 18:00:56.348  4533  4533 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
11-17 18:00:56.348  4533  4533 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
11-17 18:00:56.378  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
11-17 18:00:56.418  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{609e387 u0 com.android.settings/.wifi.WifiCredService}
11-17 18:00:56.428  4533  4602 D BluetoothAdapter: 1066718682: getState() :  mService = null. Returning STATE_OFF
11-17 18:00:56.518  1017  1056 D PackageManager: [MSG] SEND_PENDING_BROADCAST
11-17 18:00:56.528   256  1161 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
11-17 18:00:56.528   256   445 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
11-17 18:00:56.548  3281  3281 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
11-17 18:00:56.558  4553  4553 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
11-17 18:00:56.558  1017  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-17 18:00:56.568  1448  1448 D RegisteredComponentCache: Collect Tech packages for Knox
11-17 18:00:56.568  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
11-17 18:00:56.578  4533  4533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:00:56.578  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.578  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.578  1017  1777 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:56.578  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.phone
11-17 18:00:56.578  1017  1777 I ActivityManager: Killing 3859:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
11-17 18:00:56.578  1017  1777 I ActivityManager: Killing 3842:com.android.email/u0a145 (adj 15): empty #32
11-17 18:00:56.618  1467  1467 I SettingSearchManagerReceiver: onReceive : com.samsung.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
11-17 18:00:56.618  1467  1467 I SettingSearchManagerReceiver: addSearchInfoDB
11-17 18:00:56.618  4533  4533 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:00:56.618  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.628  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
11-17 18:00:56.628  1448  1448 D RegisteredServicesCache: empty dynamic service
11-17 18:00:56.628  4533  4533 D PhoneWindow: *FMB* installDecor mIsFloating : false
11-17 18:00:56.628  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.628  4533  4533 D PhoneWindow: *FMB* installDecor flags : 8456448
11-17 18:00:56.648  4533  4533 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
11-17 18:00:56.658  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.658  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
11-17 18:00:56.658  1017  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4167, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
11-17 18:00:56.658  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
11-17 18:00:56.668  4533  4533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:00:56.668  4533  4533 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:00:56.678  1017  1706 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
11-17 18:00:56.678  1017  1706 D SecContentProvider2: mCursor = null
11-17 18:00:56.738  4533  4615 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:00:56.748  1017  1487 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
11-17 18:00:56.748  1017  1487 D KnoxTimeoutHandler: postActiveUserChange for user 0
11-17 18:00:56.748  1017  1487 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
11-17 18:00:56.748  4533  4600 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-17 18:00:56.748  4533  4533 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
11-17 18:00:56.758  4533  4533 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
11-17 18:00:56.758  1467  1467 I SettingSearchManagerReceiver: endInsert
11-17 18:00:56.768   256   256 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
11-17 18:00:56.778  4368  4368 I Mms/MmsApp:  start initViewCache mms
11-17 18:00:56.778  4368  4368 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1793.027082
11-17 18:00:56.778  4368  4368 D Mms/ComposeMessageFragment: fillCache, easy = false
11-17 18:00:56.778  1448  1448 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
11-17 18:00:56.778  1017  1029 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
11-17 18:00:56.778  1017  1029 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
11-17 18:00:56.788  4451  4451 I PackagesMonitor: PackagesMonitor onReceive :com.example.hello
11-17 18:00:56.788  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
11-17 18:00:56.788  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.788  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.788  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.788  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.788  1017  1017 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
11-17 18:00:56.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.798  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
11-17 18:00:56.798  1017  1017 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
11-17 18:00:56.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.798  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:00:56.798  1017  1449 D InputDispatcher: Focus entered window: 4533
11-17 18:00:56.798  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:00:56.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.798  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:56.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.798  4617  4617 I libpersona: KNOX_SDCARD checking this for 10100
11-17 18:00:56.798  4617  4617 E Zygote  : MountEmulatedStorage()
11-17 18:00:56.798  4617  4617 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:56.798  4617  4617 E Zygote  : v2
11-17 18:00:56.808  4617  4617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:56.808  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:00:56.808  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:00:56.808  4533  4533 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
11-17 18:00:56.808  4533  4615 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:00:56.808  4617  4617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:56.808  4617  4617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:00:56.808  4533  4615 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
11-17 18:00:56.808  4533  4615 D OpenGLRenderer: Enabling debug mode 0
11-17 18:00:56.818  1017  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4617 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
11-17 18:00:56.818  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.818  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.818  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.818  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:00:56.818  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.828  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.828  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:00:56.828  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.828  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:00:56.828  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:00:56.838  1017  1017 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
11-17 18:00:56.838  1017  1017 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
11-17 18:00:56.848  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
11-17 18:00:56.858  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.858  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:56.858  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
11-17 18:00:56.858  1017  3532 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
11-17 18:00:56.868  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.868  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.868  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.868  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.868  1017  4634 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:00:56.868  4617  4617 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:56.868  4617  4617 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:56.878  4368  4368 D AbsListView: Get MotionRecognitionManager
11-17 18:00:56.878  1017  1030 D MotionRecognitionService:  ssp status : false
11-17 18:00:56.878  4533  4533 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@27b2f7f5 time:45887
11-17 18:00:56.888  4636  4636 E Zygote  : MountEmulatedStorage()
11-17 18:00:56.888  4636  4636 E Zygote  : v2
11-17 18:00:56.888  4636  4636 I libpersona: KNOX_SDCARD checking this for 10035
11-17 18:00:56.888  4636  4636 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:56.888  4636  4636 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:56.888  4636  4636 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:56.888  4636  4636 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
11-17 18:00:56.888  1017  1029 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageChangeEventReceiver: pid=4636 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:00:56.888  1778  1778 I SamsungIME: getCurrentCandidateView
11-17 18:00:56.888  4368  4368 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 117.827969
,11-17 18:00:56.908  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,11-17 18:00:56.918  1017  1047 I ActivityManager: Displayed Component not be shown by security: +919ms
,11-17 18:00:56.918  4636  4636 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:56.918  1017  1047 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
11-17 18:00:56.918  4636  4636 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:56.918  1017  1047 W ActivityManager: mDVFSHelper.release()
11-17 18:00:56.918  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c2d33ad u0 com.example.hello/.MainActivity t228} time:45927
11-17 18:00:56.918  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
11-17 18:00:56.918  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
11-17 18:00:56.918  1178  1178 D PanelView: There is/are notification(s) 
11-17 18:00:56.918  1017  1041 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,11-17 18:00:56.928  1017  1042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,11-17 18:00:56.938  1017  1017 I MotionRecognitionService: Plugged
,11-17 18:00:56.938  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,11-17 18:00:56.948  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,11-17 18:00:56.948  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,11-17 18:00:56.948  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
11-17 18:00:56.948  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,11-17 18:00:56.948  4617  4617 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
11-17 18:00:56.948  4617  4617 D PackageIntentReceiver: Not GearManger package! 
,11-17 18:00:56.958  4368  4368 D Mms/BubbleViewCache: fillCache bubble = 1
,11-17 18:00:56.958  1017  1777 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,11-17 18:00:56.958  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:56.958  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:56.958  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,11-17 18:00:56.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,11-17 18:00:56.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
11-17 18:00:56.968  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
11-17 18:00:56.968  1017  1041 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,11-17 18:00:56.978  1017  1017 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,11-17 18:00:56.978  1017  1017 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@748011a
,11-17 18:00:56.978  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.978  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.978  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:56.978  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:56.988  1778  1778 D SamsungIME: Dismiss ExpandCandiate
,11-17 18:00:56.998  4654  4654 E Zygote  : MountEmulatedStorage()
11-17 18:00:56.998  4654  4654 E Zygote  : v2
11-17 18:00:56.998  4654  4654 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:00:56.998  4654  4654 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:56.998  4654  4654 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:56.998  1017  1029 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4654 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
11-17 18:00:56.998  1778  1778 I SamsungIME: getDebugLevel  : 0x4f4c
11-17 18:00:57.008  4654  4654 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:57.008  4654  4654 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.018  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.018  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.018  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.018  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.028  4368  4368 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,11-17 18:00:57.038  4636  4667 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,11-17 18:00:57.038  4671  4671 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.038  4671  4671 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:00:57.038  4671  4671 E Zygote  : v2
11-17 18:00:57.038  4671  4671 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:57.038  4671  4671 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:00:57.038  4636  4667 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,11-17 18:00:57.038  4671  4671 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:57.048  4671  4671 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:00:57.048  1017  1029 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4671 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,11-17 18:00:57.048  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,11-17 18:00:57.048  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:57.048  1017  3531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:57.048  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,11-17 18:00:57.048  4654  4654 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:57.048  1017  1041 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
11-17 18:00:57.048  4654  4654 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.058  4636  4667 D SPPClientService: PushLog.txt file is not deleted.
11-17 18:00:57.058  4636  4667 D SPPClientService: PushLog.txt file is not deleted.
11-17 18:00:57.058  4636  4667 D SPPClientService: ============PushLog. stop!
,11-17 18:00:57.068  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3859/cgroup.procs: No such file or directory
11-17 18:00:57.068  1017  1041 D LocationProviderProxy: applying state to connected service
11-17 18:00:57.068  1017  1041 W libprocessgroup: failed to open /acct/uid_10145/pid_3842/cgroup.procs: No such file or directory
,11-17 18:00:57.078  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.078  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.078  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.078  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.088  4686  4686 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.088  4686  4686 I libpersona: KNOX_SDCARD checking this for 10091
11-17 18:00:57.088  4686  4686 E Zygote  : v2
11-17 18:00:57.088  4686  4686 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:57.088  4671  4671 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:57.088  4671  4671 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.098  4686  4686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:57.098  1017  1029 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4686 uid=10091 gids={50091, 9997, 1028, 3003, 1015} abi=armeabi-v7a
11-17 18:00:57.098  1017  1029 I ActivityManager: Killing 3879:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,11-17 18:00:57.098  4686  4686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:57.098   287   287 E SMD     : DCD OFF
11-17 18:00:57.098  4686  4686 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.108  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.108  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.108  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.108  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.118  4368  4696 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
11-17 18:00:57.118  4368  4696 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,11-17 18:00:57.128  4701  4701 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.128  4701  4701 E Zygote  : v2
11-17 18:00:57.128  4701  4701 I libpersona: KNOX_SDCARD checking this for 10047
11-17 18:00:57.128  4701  4701 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:57.128  4701  4701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:00:57.128   256  1098 I SurfaceFlinger: id=10 Removed iello (7/8)
,11-17 18:00:57.128   256   445 I SurfaceFlinger: id=10 Removed iello (-2/8)
11-17 18:00:57.128  4701  4701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:57.128  4701  4701 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
11-17 18:00:57.128  1778  1778 I SamsungIME: getDebugLevel  : 0x4f4c
,11-17 18:00:57.128  1017  1029 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4701 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,11-17 18:00:57.138  4533  4533 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4533
,11-17 18:00:57.148  1017  3532 I ActivityManager: Killing 3907:com.sec.modem.settings/1000 (adj 15): empty #31
,11-17 18:00:57.158  4686  4686 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:57.158  4686  4686 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.168  1017  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.168  1017  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.168  1017  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.168  1017  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.168  4701  4701 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:57.178  4701  4701 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.178  1778  1778 I SamsungIME: KeybaordView init() : load resources
,11-17 18:00:57.188  4721  4721 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.188  4721  4721 E Zygote  : v2
11-17 18:00:57.188  4721  4721 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:00:57.188  4721  4721 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:57.188  4721  4721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:00:57.188  1017  1449 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4721 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
11-17 18:00:57.188  1017  1449 I ActivityManager: Killing 3925:com.sec.android.soagent/u0a34 (adj 15): empty #31
11-17 18:00:57.188  4533  4533 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,11-17 18:00:57.198  4721  4721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:57.198  4721  4721 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.218   305   305 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 709us total 31.828ms
,11-17 18:00:57.218  4721  4721 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:57.228  4671  4671 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
11-17 18:00:57.228  4671  4671 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
11-17 18:00:57.228  4671  4671 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,11-17 18:00:57.238  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,11-17 18:00:57.238  4721  4721 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.238   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.791ms
,11-17 18:00:57.248  1017  1096 V AlarmManager: waitForAlarm result :4
,11-17 18:00:57.248  1778  1778 I SamsungIME: getCurrentKeyboard
11-17 18:00:57.248  4701  4701 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.248  1778  1778 I SamsungIME: getTextKeyboard
11-17 18:00:57.248  4701  4701 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
11-17 18:00:57.248  4701  4701 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,11-17 18:00:57.258   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 17.369ms
,11-17 18:00:57.258  4671  4671 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
11-17 18:00:57.258  4671  4671 I PCWCLIENTTRACE_PushUtil: sales region : global
11-17 18:00:57.258  4671  4671 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
11-17 18:00:57.258  4671  4671 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,11-17 18:00:57.268  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.268  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.268  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.268  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.288  1778  1778 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,11-17 18:00:57.288  4737  4737 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.298  4737  4737 I libpersona: KNOX_SDCARD checking this for 10032
11-17 18:00:57.288  4737  4737 E Zygote  : v2
11-17 18:00:57.298  4737  4737 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:57.298  4737  4737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:00:57.298  4737  4737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:57.298  4737  4737 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.298  1017  1030 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4737 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,11-17 18:00:57.298  1017  1030 I ActivityManager: Killing 3780:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,11-17 18:00:57.308  4721  4744 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
,11-17 18:00:57.318  1017  3531 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.318  1017  3531 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.318  1017  3531 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.318  1017  3531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.328  1017  1041 W libprocessgroup: failed to kill pid 3925: No such process
,11-17 18:00:57.328  1017  1041 W libprocessgroup: failed to open /acct/uid_10152/pid_3879/cgroup.procs: No such file or directory
,11-17 18:00:57.338  4753  4753 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.338  1017  3531 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4753 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
11-17 18:00:57.338  4753  4753 E Zygote  : v2
11-17 18:00:57.338  4753  4753 I libpersona: KNOX_SDCARD checking this for 10152
11-17 18:00:57.338  4753  4753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:57.338  4753  4753 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:57.338  1017  3531 I ActivityManager: Killing 3942:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,11-17 18:00:57.338  4753  4753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:57.348  4737  4737 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:57.348  4737  4737 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.358  4753  4753 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.388  4753  4753 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:57.388  4753  4753 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.398  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,11-17 18:00:57.408  4533  4533 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,11-17 18:00:57.418  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3907/cgroup.procs: No such file or directory
,11-17 18:00:57.418  4721  4744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,11-17 18:00:57.428  4533  4606 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:00:57.488  1017  1017 I art     : Explicit concurrent mark sweep GC freed 36276(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.273ms total 179.687ms
,11-17 18:00:57.508  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,11-17 18:00:57.508  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:57.508  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:57.508  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,11-17 18:00:57.508  4721  4721 D AcmsService: Enter Oncreate
,11-17 18:00:57.508  4721  4721 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:00:57.508  4721  4721 D AcmsService: creating AcmsCore
11-17 18:00:57.508  4721  4721 D AcmsCore: AcmsCore.getAcmsCore() - Enter
11-17 18:00:57.508  4721  4721 D AcmsCore: AcmsCore
,11-17 18:00:57.518  4721  4721 D AcmsCore: init
,11-17 18:00:57.518  4721  4721 D AcmsCore: Looper handler is not null
11-17 18:00:57.518  4721  4721 D AcmsCore: Post to AcmsCoreHandler
11-17 18:00:57.518  4721  4721 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:00:57.518  4721  4721 D AcmsServiceMonitor: Incrementing - Counter value: 1
11-17 18:00:57.518  4721  4721 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
11-17 18:00:57.518  4721  4721 D AcmsService: onStartCommand
11-17 18:00:57.518  4721  4721 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
11-17 18:00:57.518  4721  4721 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
11-17 18:00:57.518  4721  4721 D AcmsServiceMonitor: Incrementing - Counter value: 2
11-17 18:00:57.518  4721  4721 D AcmsService: Incremented Counter Value : onStartCommand
,11-17 18:00:57.518  4721  4721 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,11-17 18:00:57.518  4721  4768 D AcmsCertificateMngr: AcmsCertificateMngr
,11-17 18:00:57.528  4721  4768 D AcmsRevocationMngr: AcmsRevocationMngr
,11-17 18:00:57.538  4701  4701 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,11-17 18:00:57.538  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,11-17 18:00:57.548  4753  4753 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,11-17 18:00:57.548   283   283 E installd: system dir 0 : /system/app/
11-17 18:00:57.548   283   283 E installd: system dir 1 : /system/priv-app/
11-17 18:00:57.548   283   283 E installd: system dir 2 : /vendor/app/
11-17 18:00:57.548   283   283 E installd: system dir 3 : /oem/app/
,11-17 18:00:57.558  1017  3532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.558  1017  3532 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.558  1017  3532 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.558  1017  3532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.558  1017  1706 I TactileAssist: enable value -1
11-17 18:00:57.558  1017  1706 I TactileAssist: internal enable value -1
11-17 18:00:57.558  1017  1706 I TactileAssist: intensity value -1
11-17 18:00:57.558  1017  1706 I TactileAssist: saveAppList value true
11-17 18:00:57.558  4721  4721 D AcmsService: Inside handle Intent
11-17 18:00:57.558  4721  4721 D AcmsService: App added - package name: com.example.hello
11-17 18:00:57.558  4721  4721 D AcmsCore: Post to AcmsCoreHandler
11-17 18:00:57.558  4721  4721 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:00:57.558  4721  4721 D AcmsServiceMonitor: Incrementing - Counter value: 3
11-17 18:00:57.558  4721  4721 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
11-17 18:00:57.558  4721  4721 D AcmsService: Decremented Counter Value : handleStartIntent
11-17 18:00:57.558  4721  4721 D AcmsServiceMonitor: Decrementing - Counter value: 2
11-17 18:00:57.558  1017  1706 I TactileAssist: List of disabled apps :
,11-17 18:00:57.568  4770  4770 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.568  4770  4770 I libpersona: KNOX_SDCARD checking this for 10156
11-17 18:00:57.568  4770  4770 E Zygote  : v2
11-17 18:00:57.568  4770  4770 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:57.578  4770  4770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:00:57.578  1017  1056 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,11-17 18:00:57.578  4770  4770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:57.578  4770  4770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.588  1017  3532 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4770 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,11-17 18:00:57.598  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.598  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.598  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.598  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.598  4737  4786 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,11-17 18:00:57.608  4788  4788 E Zygote  : MountEmulatedStorage()
,11-17 18:00:57.608  4788  4788 E Zygote  : v2
11-17 18:00:57.608  4788  4788 I libpersona: KNOX_SDCARD checking this for 10053
11-17 18:00:57.608  4788  4788 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:57.608  4788  4788 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:57.608  1017  1030 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4788 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,11-17 18:00:57.608  4770  4770 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:57.608  4770  4770 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:57.608  4788  4788 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:57.608  4788  4788 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.628  4788  4788 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:57.628  4788  4788 D ActivityThread: Added TimaKeyStore provider
11-17 18:00:57.628  3974  3974 I DBG_POLICYDM: [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
,11-17 18:00:57.628  1017  1041 W libprocessgroup: failed to open /acct/uid_10034/pid_3925/cgroup.procs: No such file or directory
,11-17 18:00:57.628  1017  1041 W libprocessgroup: failed to open /acct/uid_10072/pid_3780/cgroup.procs: No such file or directory
11-17 18:00:57.628  1017  1041 W libprocessgroup: failed to open /acct/uid_1101/pid_3942/cgroup.procs: No such file or directory
,11-17 18:00:57.638  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.638  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.638  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.638  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.648  4788  4788 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,11-17 18:00:57.648  4737  4786 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,11-17 18:00:57.648  4770  4770 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
11-17 18:00:57.648  4770  4770 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
11-17 18:00:57.648  4804  4804 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.658  4804  4804 E Zygote  : v2
11-17 18:00:57.658  4804  4804 I libpersona: KNOX_SDCARD checking this for 10038
11-17 18:00:57.658  4804  4804 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,11-17 18:00:57.658  1017  1291 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4804 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,11-17 18:00:57.658  1017  1291 I ActivityManager: Killing 3982:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.658  4737  4786 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,11-17 18:00:57.668  4770  4770 I TapandpayWidget:Utils: Clear T&P info.
,11-17 18:00:57.678  4737  4786 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:00:57.678  4737  4786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:00:57.678  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:00:57.678  4804  4804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:57.678  4804  4804 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:57.678  4804  4804 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.698  4737  4786 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
11-17 18:00:57.698  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.698  4737  4786 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,11-17 18:00:57.708  4788  4788 D Compatibility: onReceive() it will make start service
,11-17 18:00:57.708  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,11-17 18:00:57.708  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:57.708  1017  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:57.708  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,11-17 18:00:57.718  4804  4804 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:57.718  4804  4804 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.718  4737  4786 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:00:57.718  4737  4786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:00:57.718  4737  4786 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
11-17 18:00:57.718  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.738  4770  4770 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
11-17 18:00:57.738  4737  4786 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
11-17 18:00:57.738  4737  4786 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:00:57.738  4737  4786 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
11-17 18:00:57.738  4737  4786 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
11-17 18:00:57.748  4788  4821 D Compatibility: onHandleIntent()
11-17 18:00:57.748  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.748  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.748  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.748  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.748  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.748  4737  4786 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
11-17 18:00:57.748  4737  4786 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
11-17 18:00:57.758  4804  4804 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.758  4804  4804 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,11-17 18:00:57.758  4788  4821 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
,11-17 18:00:57.758  4788  4821 D Compatibility: found: 2
,11-17 18:00:57.758  4823  4823 E Zygote  : MountEmulatedStorage(),
11-17 18:00:57.758  4823  4823 E Zygote  : v2
11-17 18:00:57.758  4823  4823 I libpersona: KNOX_SDCARD checking this for 10028
11-17 18:00:57.758  4823  4823 I libpersona: KNOX_SDCARD not a persona,
,11-17 18:00:57.768  4823  4823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:57.768  1017  1492 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4823 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:00:57.768  4823  4823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:57.768  4823  4823 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.778  1017  1041 W libprocessgroup: failed to open /acct/uid_10157/pid_3982/cgroup.procs: No such file or directory
,11-17 18:00:57.788  4737  4786 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
11-17 18:00:57.788  4737  4786 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:00:57.788  4737  4786 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
11-17 18:00:57.788  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.788  4737  4786 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
11-17 18:00:57.788  4553  4553 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,11-17 18:00:57.788  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,11-17 18:00:57.798  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:57.798  1017  1291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,11-17 18:00:57.798  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,11-17 18:00:57.798  4788  4821 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,11-17 18:00:57.798  4788  4821 D Compatibility: skipping ResolveInfo{362dc7cd com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
11-17 18:00:57.798  4788  4821 D Compatibility: considering ResolveInfo{19ecb882 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,11-17 18:00:57.808  4788  4821 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,11-17 18:00:57.818  4788  4821 D Compatibility: enabling receiver ResolveInfo{208e5b93 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:00:57.818  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.818  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.818  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.818  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.828  4788  4821 D Compatibility: enabling receiver ResolveInfo{2335f7d0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:00:57.828  4737  4786 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,11-17 18:00:57.838  4788  4821 D Compatibility: enabling receiver ResolveInfo{2a5c13c9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:00:57.838  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.838  4788  4821 D Compatibility: enabling receiver ResolveInfo{2db1dace com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
11-17 18:00:57.848  4839  4839 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:00:57.848  4839  4839 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.848  4839  4839 I libpersona: KNOX_SDCARD not a persona
11-17 18:00:57.848  4839  4839 E Zygote  : v2
,11-17 18:00:57.848  4839  4839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:00:57.848  4839  4839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:57.848  4839  4839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:00:57.848  1017  1493 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=4839 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
11-17 18:00:57.848  4788  4821 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,11-17 18:00:57.858  4737  4786 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
11-17 18:00:57.858  4737  4786 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,11-17 18:00:57.858  1017  1438 I ActivityManager: Killing 4006:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,11-17 18:00:57.858  4823  4823 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:57.858  4823  4823 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.878  4533  4652 D jxcore_app_log: JniHelper::setJavaVM(0xb8d77450), pthread_self() = -1188163360,
11-17 18:00:57.878  4533  4652 D JX-Cordova: jxcore cordova android initializing
11-17 18:00:57.878  1017  1438 I ActivityManager: Killing 4063:com.osp.app.signin/u0a41 (adj 15): empty #31
11-17 18:00:57.878  4839  4839 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:57.878  4839  4839 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:57.918  4839  4839 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,11-17 18:00:57.948  4737  4786 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
11-17 18:00:57.948  4737  4786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:00:57.948  4737  4786 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
11-17 18:00:57.948  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:57.948  4737  4786 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,11-17 18:00:57.948  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.958  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:57.958  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.958  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:57.968  4533  4533 W jxcore-log: Initializing JXcore engine
11-17 18:00:57.968  4533  4533 W jxcore-log: JXcore engine is ready
,11-17 18:00:57.968  4533  4533 W jxcore-log: Starting JXcore engine,
,11-17 18:00:57.978  1017  1029 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
11-17 18:00:57.978  1017  1029 I ActivityManager: Killing 3476:com.android.providers.calendar/u0a42 (adj 15): empty #31,
11-17 18:00:57.978  4737  4786 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
11-17 18:00:57.978  4737  4786 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
11-17 18:00:57.978  4855  4855 E Zygote  : MountEmulatedStorage()
11-17 18:00:57.978  4855  4855 E Zygote  : v2,
11-17 18:00:57.978  4855  4855 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:00:57.978  4855  4855 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:57.978  4855  4855 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,11-17 18:00:57.988  4855  4855 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:57.988  4855  4855 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:00:58.018  4855  4855 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:58.018  4855  4855 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:58.048  4855  4855 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,11-17 18:00:58.058  1845  1845 E audit   : type=1400 msg=audit(1447779658.048:203): avc:  denied  { ioctl } for  pid=4533 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3088 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-17 18:00:58.058  4737  4786 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
11-17 18:00:58.058  1845  1845 E audit   :  SEPF_SM-A500FU_5.0.2_0027
11-17 18:00:58.058  4737  4786 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
11-17 18:00:58.058  1845  1845 E audit   : type=1300 msg=audit(1447779658.048:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=befa6d58 items=0 ppid=305 ppcomm=main pid=4533 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
11-17 18:00:58.058  4737  4786 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:00:58.058  1845  1845 E audit   : type=1320 msg=audit(1447779658.048:203): 
11-17 18:00:58.058  4737  4786 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,11-17 18:00:58.058  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:00:58.058  4737  4786 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,11-17 18:00:58.068  4737  4786 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
11-17 18:00:58.078  4737  4786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:00:58.088  1017  1029 I ActivityManager: Killing 4113:com.google.android.gms:car/u0a12 (adj 15): empty #31
,11-17 18:00:58.088  4737  4786 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,11-17 18:00:58.088  1017  1041 W libprocessgroup: failed to open /acct/uid_10159/pid_4006/cgroup.procs: No such file or directory
11-17 18:00:58.088  1017  1041 W libprocessgroup: failed to open /acct/uid_10041/pid_4063/cgroup.procs: No such file or directory
11-17 18:00:58.088  1017  1041 W libprocessgroup: failed to open /acct/uid_10042/pid_3476/cgroup.procs: No such file or directory
,11-17 18:00:58.168  1017  1280 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,11-17 18:00:58.198  4533  4533 W jxcore-log: Platform android
11-17 18:00:58.198  4533  4533 W jxcore-log: 
11-17 18:00:58.198  4533  4533 W jxcore-log: Process ARCH arm
11-17 18:00:58.198  4533  4533 W jxcore-log: 
,11-17 18:00:58.208  4823  4823 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,11-17 18:00:58.208  1017  1041 W libprocessgroup: failed to open /acct/uid_10012/pid_4113/cgroup.procs: No such file or directory
,11-17 18:00:58.248  4533  4533 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:00:58.248  4533  4533 I jxcore-log: 
,11-17 18:00:58.248  4533  4533 W jxcore-log: JXcore engine is started
,11-17 18:00:58.258  4804  4804 I SL_DEBUG: isLoggable:: isProductShip = 1
,11-17 18:00:58.258  4804  4804 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,11-17 18:00:58.268  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,11-17 18:00:58.278  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.278  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:00:58.278  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,11-17 18:00:58.308  4533  4533 E jxcore-log: >> samsung-SM-A500FU
11-17 18:00:58.308  4533  4533 E jxcore-log: 
,11-17 18:00:58.308  4533  4533 I jxcore-log: Total memory 1983787008
11-17 18:00:58.308  4533  4533 I jxcore-log: 
,11-17 18:00:58.308  4533  4533 I jxcore-log: Free memory 39534592
11-17 18:00:58.308  4533  4533 I jxcore-log: 
11-17 18:00:58.308  4533  4533 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:00:58.308  4533  4533 I jxcore-log: 
11-17 18:00:58.308  4533  4533 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:00:58.308  4533  4533 I jxcore-log: 
,11-17 18:00:58.318  4533  4533 I jxcore-log: userPath [ 'rList-com.example.hello.MainActivity', 'www' ],
11-17 18:00:58.318  4533  4533 I jxcore-log: 
,11-17 18:00:58.318  4533  4533 I jxcore-log: Size 720 1280,
11-17 18:00:58.318  4533  4533 I jxcore-log: 
,11-17 18:00:58.318  4533  4533 I jxcore-log: Screen Brightness 5,
11-17 18:00:58.318  4533  4533 I jxcore-log: 
11-17 18:00:58.318  4533  4533 E jxcore-log: Dummy Error Log.
11-17 18:00:58.318  4533  4533 E jxcore-log: 
,11-17 18:00:58.398  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,11-17 18:00:58.458   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
11-17 18:00:58.458   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
,11-17 18:00:58.458  4804  4804 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,11-17 18:00:58.488  4823  4823 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,11-17 18:00:58.488  1017  1280 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,11-17 18:00:58.488  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.488  1017  1280 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
11-17 18:00:58.488  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,11-17 18:00:58.518   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
11-17 18:00:58.518   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
,11-17 18:00:58.518  4804  4804 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,11-17 18:00:58.528  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:00:58.538  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.538  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.538  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,11-17 18:00:58.538  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:58.538  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:58.538  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:58.538  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:58.558  4904  4904 E Zygote  : MountEmulatedStorage(),
11-17 18:00:58.558  4904  4904 E Zygote  : v2
,11-17 18:00:58.558  4904  4904 I libpersona: KNOX_SDCARD checking this for 10012
11-17 18:00:58.558  4904  4904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:00:58.558  4904  4904 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:58.568  4904  4904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,11-17 18:00:58.568  4904  4904 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,11-17 18:00:58.568  1017  1029 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4904 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,11-17 18:00:58.578  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,11-17 18:00:58.578  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:58.578  1017  1216 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
11-17 18:00:58.578  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,11-17 18:00:58.588  4904  4904 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:58.598  4904  4904 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:58.608  4823  4823 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:00:58.608  4823  4823 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:00:58.608  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:58.618  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:58.618  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:58.618  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:58.628  4904  4904 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:00:58.628  4904  4904 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:00:58.628  4925  4925 E Zygote  : MountEmulatedStorage()
11-17 18:00:58.628  4925  4925 E Zygote  : v2
11-17 18:00:58.628  4925  4925 I libpersona: KNOX_SDCARD checking this for 10041
11-17 18:00:58.628  4925  4925 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:58.638  4925  4925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,11-17 18:00:58.638  1017  1493 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=4925 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:00:58.638  4925  4925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:58.638  4925  4925 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,11-17 18:00:58.658  4925  4925 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:00:58.668  4925  4925 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:58.718  4904  4904 I MultiDex: VM with version 2.1.0 has multidex support
11-17 18:00:58.718  4904  4904 I MultiDex: install
11-17 18:00:58.718  4904  4904 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,11-17 18:00:58.758  1017  1761 I ActivityManager: Killing 4043:com.google.android.youtube/u0a166 (adj 15): empty #31
,11-17 18:00:58.768  4823  4823 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,11-17 18:00:58.768  4925  4925 I SA      : [SSP] onCreated
11-17 18:00:58.768  4823  4823 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,11-17 18:00:58.778  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,11-17 18:00:58.778  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:58.778  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.778  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:00:58.788  1933  1933 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 18:00:58.788  1933  1933 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
11-17 18:00:58.788  4904  4904 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,11-17 18:00:58.788  1933  4946 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,11-17 18:00:58.798  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,11-17 18:00:58.808  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.808  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.808  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:58.808  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,11-17 18:00:58.808  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:58.808  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.808  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:58.808  4686  4686 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
11-17 18:00:58.808  4686  4686 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-17 18:00:58.808  4686  4686 I GAv4    :   adb logcat -s GAv4
,11-17 18:00:58.818  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,11-17 18:00:58.818  4823  4823 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,11-17 18:00:58.818  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.818  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.818  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:58.818  4925  4925 I SA      : [TPM] There is no property file
,11-17 18:00:58.828  4925  4925 I SA      : [SCU] isHaveSA() - false
,11-17 18:00:58.828  4925  4925 I SA      : [TPM] getModelProperty : null
11-17 18:00:58.828  4925  4925 I SA      : [TPM] getCSCProperty : null
,11-17 18:00:58.828  4925  4925 I SA      : [DM] FLOATING AMOLED FEATURE: true
11-17 18:00:58.828  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
11-17 18:00:58.828  4925  4925 I SA      : [DM] PRODUCT AMOLED FEATURE: false
11-17 18:00:58.828  4925  4925 I SA      : [DM] TFT FEATURE: false
,11-17 18:00:58.828  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.828  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.828  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,11-17 18:00:58.828  1017  1777 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:00:58.838  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.838  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.838  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:58.848  4823  4823 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,11-17 18:00:58.858  4533  4533 I jxcore-log: getBuffer is called!!!!
11-17 18:00:58.858  4533  4533 I jxcore-log: 
11-17 18:00:58.858  4686  4686 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:00:58.858  1017  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:00:58.858  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:58.858  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:58.868  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,11-17 18:00:58.878  4904  4904 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-17 18:00:58.878  4904  4904 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f0ff490: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
11-17 18:00:58.878  4904  4904 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 18:00:58.878  4925  4925 I SA      : [PMR] Received action : android.intent.action.PACKAGE_ADDED
,11-17 18:00:58.888  4925  4925 I SA      : [DM] init START
,11-17 18:00:58.898  1017  1041 W libprocessgroup: failed to open /acct/uid_10166/pid_4043/cgroup.procs: No such file or directory
,11-17 18:00:58.898  4686  4686 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:00:58.908  4925  4925 I SA      : [DM] This device is not a Vodafone
,11-17 18:00:58.918  4925  4925 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,11-17 18:00:58.918  4925  4925 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,11-17 18:00:58.918  4925  4925 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,11-17 18:00:58.918  4925  4925 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
11-17 18:00:58.918  4925  4925 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
11-17 18:00:58.918  4925  4925 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
11-17 18:00:58.918  4925  4925 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
11-17 18:00:58.918  4925  4925 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,11-17 18:00:58.928  4925  4925 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,11-17 18:00:58.938  4925  4925 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,11-17 18:00:58.958  4925  4925 I SA      : [SCU] isHaveSA() - false
11-17 18:00:58.958  4925  4925 I SA      : support phone number id : false
11-17 18:00:58.958  4925  4925 I SA      : [DM] Supports Ref Jpn : true
,11-17 18:00:58.958  4925  4925 I SA      : [DM] init END
11-17 18:00:58.958  4925  4925 I SA      : [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,11-17 18:00:58.958  4925  4925 I SA      : [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
,11-17 18:00:58.958  1017  1438 I ActivityManager: Killing 4158:com.google.android.gm/u0a101 (adj 15): empty #31
,11-17 18:00:58.978  1017  1096 V AlarmManager: waitForAlarm result :8
,11-17 18:00:58.978  1017  1096 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:00:58.998  4686  4686 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,11-17 18:00:59.008  4686  4956 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:00:59.038  1017  3527 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:00:59.038  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:59.038  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:59.038  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.038  1933  1933 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-17 18:00:59.048  1933  1933 I ConfigFetchService: launchTask
,11-17 18:00:59.058  1017  3527 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:00:59.058  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:59.058  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:00:59.058  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.058  1017  1334 E Watchdog: !@Sync 1
,11-17 18:00:59.068  1933  1933 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 18:00:59.068  1933  1933 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:00:59.088  1017  1041 W libprocessgroup: failed to open /acct/uid_10101/pid_4158/cgroup.procs: No such file or directory
,11-17 18:00:59.088  1017  1139 D SettingsProvider: name = audio_safe_volume_state
,11-17 18:00:59.088  1933  4962 I PeopleContactsSync: CP2 sync disabled
,11-17 18:00:59.098  1933  1933 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
,11-17 18:00:59.098  1933  1933 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,11-17 18:00:59.108  1933  1933 D Vision  : Failed to find package metadata for com.example.hello
,11-17 18:00:59.108  1933  1933 D Vision  : No vision deps
,11-17 18:00:59.118  4686  4714 W art     : Suspending all threads took: 21.225ms
,11-17 18:00:59.148  1933  4961 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WUsrCmRxY3H0u1ZoLY64NpoSN3jIK__tEulmaAY1Utn02YXfa7iqypmZytcKxLBl458NXJehGFdBkjFS-n_7jx-n_frojI2IKccmIiqygvFBUsAjozO6zNrVlReFWfM_kLHWJA28-2GlpaWPxZmtZNOM_bJiWT84frXtCxP2iM2diMsmqe-ypedKD6m6fxtC2DDL_1puZ-QcrIlkwSuE0S8_IsTXe1-KIL6JRjHYEJs2lw7IM
,11-17 18:00:59.198  1933  3679 I Icing   : Storage manager: low false usage 2.00MB avail 7.89GB capacity 9.93GB
,11-17 18:00:59.218  1933  4961 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-17 18:00:59.218  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,11-17 18:00:59.218  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:59.218  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:59.218  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.238  1933  3679 W Icing   : Received bad json for section weights override -- ignoring.
,11-17 18:00:59.238  1933  3679 W Icing   : Received bad json for corpus context scoring override -- ignoring.
11-17 18:00:59.238  1933  3679 W Icing   : Received bad json for section weights override -- ignoring.
,11-17 18:00:59.238  1933  3679 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,11-17 18:00:59.278  1017  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:00:59.278  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:00:59.278  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:59.278  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.288  1933  4961 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,11-17 18:00:59.288  1933  4961 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,11-17 18:00:59.288  1933  4961 I System.out: (HTTPLog)-Static: isShipBuild true
,11-17 18:00:59.288  1933  4961 I System.out: (HTTPLog)-Thread-235-591694469: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,11-17 18:00:59.288  1933  4961 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,11-17 18:00:59.298   277   974 D EnterpriseController: uids 10012
11-17 18:00:59.298   277   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
11-17 18:00:59.298   277   974 D Netd    : getNetworkForDns: using netid 0 for uid 10012
,11-17 18:00:59.308  1933  4961 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,11-17 18:00:59.308  1933  1933 I ConfigFetchService: fetch service done; releasing wakelock
,11-17 18:00:59.308  1933  1933 I ConfigFetchService: stopping self
,11-17 18:00:59.328  1933  4964 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:00:59.338  1933  4964 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:00:59.338  4721  4768 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,11-17 18:00:59.348  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:59.348  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:00:59.348  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:59.348  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:00:59.358   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/,
11-17 18:00:59.358   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
,11-17 18:00:59.368  4721  4768 I AcmsKeyStoreHelper: Key Store exist
,11-17 18:00:59.368  4721  4768 I AcmsKeyStoreHelper: Hence loading the keystore file
,11-17 18:00:59.368  4980  4980 E Zygote  : MountEmulatedStorage()
11-17 18:00:59.368  4980  4980 E Zygote  : v2
11-17 18:00:59.368  4980  4980 I libpersona: KNOX_SDCARD checking this for 10120
11-17 18:00:59.368  4980  4980 I libpersona: KNOX_SDCARD not a persona
,11-17 18:00:59.368  1017  1030 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4980 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,11-17 18:00:59.368  1017  1030 I ActivityManager: Killing 4216:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,11-17 18:00:59.378  4686  4978 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
,11-17 18:00:59.378  4980  4980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:00:59.378  4980  4980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:00:59.378  4980  4980 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,11-17 18:00:59.388  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{2d41b0d0 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,11-17 18:00:59.398   305   305 I art     : Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 27.364ms
,11-17 18:00:59.408  4980  4980 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:00:59.408   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.326ms
,11-17 18:00:59.418  4980  4980 D ActivityThread: Added TimaKeyStore provider
,11-17 18:00:59.418  1933  4964 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:00:59.428  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 15 sec
,11-17 18:00:59.428   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.972ms
,11-17 18:00:59.438  4686  4979 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:00:59.438  4686  4979 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:00:59.438  1933  4964 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:00:59.448  1933  4964 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:00:59.458  1017  3527 I ActivityManager: Killing 4193:com.dropbox.android/u0a92 (adj 15): empty #31
,11-17 18:00:59.468  4721  4768 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
11-17 18:00:59.468  4721  4768 I AcmsCertificateMngr: getKeyStoreForApplication success 
11-17 18:00:59.468  4721  4768 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
11-17 18:00:59.468  4721  4768 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:00:59.468  4721  4768 D AcmsServiceMonitor: Decrementing - Counter value: 1
11-17 18:00:59.468  4721  4768 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,11-17 18:00:59.468  4980  4980 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:00:59.468  4721  4768 D AcmsCore: This is NOT a valid MirrorLink app
11-17 18:00:59.468  4721  4768 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
11-17 18:00:59.468  4721  4768 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:00:59.468  4721  4768 D AcmsServiceMonitor: Decrementing - Counter value: 0
11-17 18:00:59.468  4721  4768 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,11-17 18:00:59.468  4721  4721 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,11-17 18:00:59.468  4721  4721 D AcmsService: Enter onDestroy
11-17 18:00:59.468  4721  4721 I AcmsService: cleanUp(): inside service clean up
11-17 18:00:59.468  4721  4721 D AcmsCore: AcmsCore: inside DeInit
11-17 18:00:59.468  4721  4721 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
11-17 18:00:59.478  4721  4721 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
11-17 18:00:59.478  4721  4721 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
11-17 18:00:59.478  4721  4721 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
11-17 18:00:59.478  4721  4721 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
11-17 18:00:59.478  4721  4721 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
11-17 18:00:59.478  4721  4721 D AcmsService: killing acms process
11-17 18:00:59.478  4721  4721 I Process : Sending signal. PID: 4721 SIG: 9
,11-17 18:00:59.488  1017  1096 V AlarmManager: waitForAlarm result :4
,11-17 18:00:59.488  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,11-17 18:00:59.488  1933  4964 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:00:59.498  4686  4979 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,11-17 18:00:59.498  1017  1041 W libprocessgroup: failed to open /acct/uid_10092/pid_4216/cgroup.procs: No such file or directory
,11-17 18:00:59.528  1017  3531 I ActivityManager: Process ACMS.Process (pid 4721)(adj 0) has died(48,1107)
,11-17 18:00:59.548  4823  4823 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,11-17 18:00:59.558  4686  4979 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-17 18:00:59.558  4686  4979 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f26fdd9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
11-17 18:00:59.558  4686  4979 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-17 18:00:59.568  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:00:59.568  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:00:59.578  4823  4823 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,11-17 18:00:59.578  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,11-17 18:00:59.578  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:59.578  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:59.578  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.608  1017  1777 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:00:59.608  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:59.608  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:59.608  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.618  1017  1706 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:00:59.628  1649  1658 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,11-17 18:00:59.628  1649  1658 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
11-17 18:00:59.628  1649  1658 I GLSUser : [GLSUser] Extracting token using key: Auth
,11-17 18:00:59.628  1649  1658 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,11-17 18:00:59.638  1649  1658 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:00:59.638  1017  3532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,11-17 18:00:59.638  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:59.648  1017  3532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:00:59.648  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.648  1017  1041 W libprocessgroup: failed to open /acct/uid_10092/pid_4193/cgroup.procs: No such file or directory
,11-17 18:00:59.648  1649  3729 I art     : Explicit concurrent mark sweep GC freed 9349(465KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 1.092ms total 57.517ms
,11-17 18:00:59.698  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:00:59.708  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:00:59.718  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:00:59.718  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:59.718  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:00:59.718  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.728  1649  1738 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,11-17 18:00:59.728  1649  1738 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,11-17 18:00:59.738  1649  1738 I GLSUser : [GLSUser] Extracting token using key: Auth
11-17 18:00:59.738  1649  1738 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,11-17 18:00:59.738  1649  1738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:00:59.738  1017  1706 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,11-17 18:00:59.738  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:00:59.738  1017  1706 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:00:59.738  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:00:59.768  4823  4823 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,11-17 18:00:59.938  1933  3679 I Icing   : updateResources: need to parse f{com.google.android.gms}
,11-17 18:00:59.998  1017  1096 V AlarmManager: waitForAlarm result :8
,11-17 18:00:59.998  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,11-17 18:00:59.998  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,11-17 18:01:00.008  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,11-17 18:01:00.008  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,11-17 18:01:00.018  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,11-17 18:01:00.018  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
11-17 18:01:00.018  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,11-17 18:01:00.018  1596  1596 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,11-17 18:01:00.018  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,11-17 18:01:00.018  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,11-17 18:01:00.028  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,11-17 18:01:00.028  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
11-17 18:01:00.028  1596  1596 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,11-17 18:01:00.028  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,11-17 18:01:00.028  1596  1596 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
11-17 18:01:00.028  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,11-17 18:01:00.028  1596  1596 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 18 01
,11-17 18:01:00.068  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,11-17 18:01:00.068  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,11-17 18:01:00.078  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,11-17 18:01:00.098  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
11-17 18:01:00.098   287   287 E SMD     : DCD OFF
,11-17 18:01:00.198  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.208  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.208  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.208  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,11-17 18:01:00.208  1933  3679 I Icing   : Internal init done: storage state 0
,11-17 18:01:00.238  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.238  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:00.238  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.238  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,11-17 18:01:00.248  1933  4964 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:01:00.248  1933  4964 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:01:00.258  1933  3679 I Icing   : Post-init done
,11-17 18:01:00.258  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.258  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:00.258  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:00.258  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.428  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 16 sec
,11-17 18:01:00.438  1017  1291 I art     : Explicit concurrent mark sweep GC freed 28452(1572KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.328ms total 153.779ms
,11-17 18:01:00.448  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.448  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:00.448  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.448  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,11-17 18:01:00.458  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.458  1017  3527 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.458  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:00.458  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.458  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,11-17 18:01:00.458  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:00.468  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.468  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:00.468  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:00.468  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.478  5014  5014 E Zygote  : MountEmulatedStorage()
11-17 18:01:00.478  5014  5014 I libpersona: KNOX_SDCARD checking this for 10010
11-17 18:01:00.478  5014  5014 E Zygote  : v2
11-17 18:01:00.478  5014  5014 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:00.478  5014  5014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:00.478  5014  5014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:01:00.488  1017  1493 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5014 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,11-17 18:01:00.488  5014  5014 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,11-17 18:01:00.498  1017  1291 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:00.498  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.498  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.498  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.498  4250  5012 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:01:00.518  1649  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,11-17 18:01:00.518  1649  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,11-17 18:01:00.518  1649  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
,11-17 18:01:00.528  1649  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,11-17 18:01:00.528  5014  5014 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:00.528  1649  2076 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:00.538  5014  5014 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:00.538  1017  3527 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.548  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.548  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.548  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.558  4823  4823 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,11-17 18:01:00.568  4823  4823 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,11-17 18:01:00.578  1017  1706 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:00.578  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.578  1017  1706 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.578  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.578  4823  4823 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,11-17 18:01:00.588  4823  4823 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 81 minutes (failures=3)
,11-17 18:01:00.598  1017  2603 D SSRM:n  : SIOP:: AP = 410
,11-17 18:01:00.628  1744  3121 D DeviceConnectionService: client connected with version: 7571000
,11-17 18:01:00.648  1017  3531 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:00.648  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.648  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.648  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.688  1017  2619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:01:00.708  1017  1492 I splitIntent: Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,11-17 18:01:00.708  1017  1492 I ActivityManager: Killing 3691:com.google.android.talk/u0a104 (adj 15): empty #31
,11-17 18:01:00.708  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:00.708  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.708  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.718  4451  4495 I FaceInterface: startFaceScan() : going on
11-17 18:01:00.718  4451  4495 D FaceInterface: startFaceScan() is called.
,11-17 18:01:00.718  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.718  1225  1235 D ContentApp: startScan() is called.
,11-17 18:01:00.718  1017  1706 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.718  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.728  1225  1235 D FaceValue: mSleepTime: 800
11-17 18:01:00.728  1225  1235 D FaceValue: mMaxThreadNum: 2
,11-17 18:01:00.728  1225  1235 W FaceValue: com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
11-17 18:01:00.728  1225  1235 D ContentApp: startScan() is end.
,11-17 18:01:00.728  1225  5031 D ContentApp: face_restore FINISHED_TYPE: 3
,11-17 18:01:00.738  1225  5031 D FaceScanner: isNeedToRestore : start
,11-17 18:01:00.738  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.738  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:00.738  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:00.738  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.758  5032  5032 E Zygote  : MountEmulatedStorage()
11-17 18:01:00.758  5032  5032 E Zygote  : v2
11-17 18:01:00.758  5032  5032 I libpersona: KNOX_SDCARD checking this for 10165
11-17 18:01:00.758  5032  5032 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:00.758  5032  5032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:00.758  5032  5032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:00.758  1017  3527 I ActivityManager: Start proc com.sec.android.app.wluc for broadcast com.sec.android.app.wluc/.PolicyManagerBroadcastReceiver: pid=5032 uid=10165 gids={50165, 9997} abi=armeabi-v7a
,11-17 18:01:00.758  5032  5032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:01:00.758  1017  1280 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:00.768  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.768  1017  1280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:00.768  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.778  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.778  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.778  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.778  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.788  5032  5032 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:00.788  5032  5032 D ActivityThread: Added TimaKeyStore provider,
,11-17 18:01:00.798  1017  1706 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.798  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:00.798  1017  1706 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.798  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.808  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:01:00.808  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.808  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.808  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.818  5032  5032 I PolicyManagerBroadcastReceiver: onReceive: action = com.sec.intent.ACTION.SSRM_HGL_UPDATE
,11-17 18:01:00.818  5032  5032 I PolicyManagerBroadcastReceiver: onReceive: width = 720, height = 1280
,11-17 18:01:00.818  1017  1449 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:00.828  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.828  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.828  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.828  1017  1041 W libprocessgroup: failed to open /acct/uid_10104/pid_3691/cgroup.procs: No such file or directory
,11-17 18:01:00.838  1017  3531 I ActivityManager: Killing 4324:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,11-17 18:01:00.838  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.838  1017  1706 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:00.848  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
,11-17 18:01:00.848  1017  1706 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.848  1017  1706 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.848  1017  1706 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:00.848  1017  1706 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.848   277   974 D EnterpriseController: uids 10012
11-17 18:01:00.848   277   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
11-17 18:01:00.848   277   974 D Netd    : getNetworkForDns: using netid 0 for uid 10012
,11-17 18:01:00.868  5051  5051 E Zygote  : MountEmulatedStorage()
,11-17 18:01:00.868  5051  5051 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:01:00.868  5051  5051 E Zygote  : v2
11-17 18:01:00.868  5051  5051 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:00.868  5051  5051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:00.868  5051  5051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
11-17 18:01:00.868  1017  1706 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
11-17 18:01:00.868  5051  5051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:00.878  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{1fa1668b u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,11-17 18:01:00.878  1017  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:00.888  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.888  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:00.888  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:00.888  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4324/cgroup.procs: No such file or directory
,11-17 18:01:00.888  5051  5051 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:00.898  5051  5051 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:00.908  4250  5012 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 400 ms] updated apps [took 400 ms] 
,11-17 18:01:00.908  1017  1029 I ActivityManager: Killing 4417:com.wsomacp/u0a25 (adj 15): empty #31
,11-17 18:01:00.918  4451  4525 I FaceInterface: startFaceScan() : going on
,11-17 18:01:00.918  4451  4525 D FaceInterface: startFaceScan() is called.
,11-17 18:01:00.928  1225  4541 D ContentApp: startScan() is called.
,11-17 18:01:00.928  1225  4541 D ContentApp: startScan() is end.
,11-17 18:01:00.928  5051  5051 D PopupuiReceiver: onReceive() getAction : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
,11-17 18:01:00.928  1017  1706 D SecContentProvider2: uri = -1 selection = getSealedState
11-17 18:01:00.928  1017  1706 D SecContentProvider2: mCursor = null
,11-17 18:01:00.928  1225  5067 D ContentApp: face_restore FINISHED_TYPE: 3
11-17 18:01:00.928  5051  5051 I PopupuiReceiver_KNOX: getSealedState : true
11-17 18:01:00.928  1225  5067 D FaceScanner: isNeedToRestore : start
,11-17 18:01:00.928  1017  1487 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
11-17 18:01:00.928  1017  1487 D SecContentProvider2: mCursor = null
,11-17 18:01:00.928  5051  5051 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,11-17 18:01:00.928  1017  3527 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,11-17 18:01:00.928  1017  3527 D SecContentProvider2: mCursor = null
,11-17 18:01:00.928  5051  5051 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,11-17 18:01:00.938  5051  5051 D PopupuiReceiver: Action cable connected ! on - 
,11-17 18:01:00.938  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:00.938  1017  1777 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:00.938  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
,11-17 18:01:00.938  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.938  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:00.938  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.938  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:00.948  5068  5068 E Zygote  : MountEmulatedStorage()
11-17 18:01:00.948  5068  5068 I libpersona: KNOX_SDCARD checking this for 10122
11-17 18:01:00.948  5068  5068 E Zygote  : v2
11-17 18:01:00.948  5068  5068 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:00.958  5068  5068 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:01:00.958  1017  1777 I ActivityManager: Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=5068 uid=10122 gids={50122, 9997} abi=armeabi-v7a
11-17 18:01:00.958  5068  5068 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:01:00.958  1017  1777 I ActivityManager: Killing 4480:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,11-17 18:01:00.958  5068  5068 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,11-17 18:01:00.978  5068  5068 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:00.978  5068  5068 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:01.018  5068  5068 I PowerSharing.BatteryReceiver: onReceive : com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED
,11-17 18:01:01.018  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:01.018  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.018  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.028  1017  1761 I ActivityManager: Killing 4433:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,11-17 18:01:01.028  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.028  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:01.028  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.028  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.028  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.038  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.038  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.038  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.038  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:01.038  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.038  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.038  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.038  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.038  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.048  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.058  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:01.058  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.058  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.058  1017  1280 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.058  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:01.058  1017  1280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.058  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.068  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.068  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.068  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,11-17 18:01:01.078  1017  1438 I ActivityManager: Killing 4342:com.google.android.music:main/u0a111 (adj 15): empty #31
,11-17 18:01:01.078  1017  1041 W libprocessgroup: failed to open /acct/uid_10025/pid_4417/cgroup.procs: No such file or directory
,11-17 18:01:01.148  1017  1041 W libprocessgroup: failed to open /acct/uid_10153/pid_4480/cgroup.procs: No such file or directory
,11-17 18:01:01.158  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{400eae u0 com.sec.bcservice/.BroadcastService}
,11-17 18:01:01.158  1017  1041 W libprocessgroup: failed to open /acct/uid_10040/pid_4433/cgroup.procs: No such file or directory
11-17 18:01:01.158  1017  1041 W libprocessgroup: failed to open /acct/uid_10111/pid_4342/cgroup.procs: No such file or directory
,11-17 18:01:01.168  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.168  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:01.168  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.178  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.178  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.178  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.178  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.178  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.178  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.178  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.178  1649  3526 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,11-17 18:01:01.188  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.188  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.188  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.198  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.198  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.198  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.198  1933  1933 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 18:01:01.198  1017  1777 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:01.198  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.198  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.198  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.208  1933  1933 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 18:01:01.208  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.208  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.208  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.218  1933  5088 I Kids    : [KidAccountFixer] No network connection
,11-17 18:01:01.238  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.238  1017  1706 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.238  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.258  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.258  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.258  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.258  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.268  5089  5089 E Zygote  : MountEmulatedStorage()
11-17 18:01:01.268  5089  5089 E Zygote  : v2
11-17 18:01:01.268  5089  5089 I libpersona: KNOX_SDCARD checking this for 10134
11-17 18:01:01.268  5089  5089 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:01.268  5089  5089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,11-17 18:01:01.278  5089  5089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:01.278  1017  1777 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5089 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,11-17 18:01:01.278  5089  5089 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,11-17 18:01:01.298  5089  5089 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:01.298  5089  5089 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:01.308  5089  5089 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:01:01.308  5089  5089 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,11-17 18:01:01.328  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.328  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.328  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.328  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.348  5104  5104 E Zygote  : MountEmulatedStorage()
,11-17 18:01:01.348  5104  5104 E Zygote  : v2
11-17 18:01:01.348  5104  5104 I libpersona: KNOX_SDCARD checking this for 10135
11-17 18:01:01.348  5104  5104 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:01.348  5104  5104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:01.348  5104  5104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
11-17 18:01:01.348  1017  1777 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5104 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,11-17 18:01:01.348  5104  5104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:01.348  1017  1777 I ActivityManager: Killing 4575:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,11-17 18:01:01.368  5104  5104 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:01.368  5104  5104 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:01.378  5104  5104 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,11-17 18:01:01.378  5104  5104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:01.378  5104  5104 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:01:01.428  1298  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,11-17 18:01:01.428  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 17 sec
,11-17 18:01:01.438  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.438  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
11-17 18:01:01.438  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,11-17 18:01:01.438  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,11-17 18:01:01.458  1017  3532 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.458  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.458  1017  3532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:01.458  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,11-17 18:01:01.458  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.458  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.458  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.458  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.478  5124  5124 E Zygote  : MountEmulatedStorage(),
11-17 18:01:01.478  5124  5124 E Zygote  : v2
11-17 18:01:01.478  5124  5124 I libpersona: KNOX_SDCARD checking this for 10033
,11-17 18:01:01.478  5124  5124 I libpersona: KNOX_SDCARD not a persona,
11-17 18:01:01.478  5124  5124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:01.478  5124  5124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
11-17 18:01:01.478  1017  1216 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5124 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
11-17 18:01:01.478  5124  5124 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,11-17 18:01:01.498  1017  1487 I ActivityManager: Killing 4451:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,11-17 18:01:01.498  5124  5124 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:01.508  5124  5124 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:01.528  1017  1041 W libprocessgroup: failed to open /acct/uid_10150/pid_4575/cgroup.procs: No such file or directory
,11-17 18:01:01.568  5124  5124 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,11-17 18:01:01.568  5124  5124 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:01:01.568  5124  5124 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,11-17 18:01:01.598  5124  5124 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,11-17 18:01:01.598  5124  5124 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:01:01.598  5124  5124 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:01:01.618  5124  5124 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.,
11-17 18:01:01.618  5124  5124 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
11-17 18:01:01.618  5124  5124 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,11-17 18:01:01.628  1017  1041 W libprocessgroup: failed to open /acct/uid_10044/pid_4451/cgroup.procs: No such file or directory
,11-17 18:01:01.808  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.808  1017  1777 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
11-17 18:01:01.808  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,11-17 18:01:01.818  4025  4025 E SPPClientService: [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,11-17 18:01:01.818  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.828  1017  1029 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
11-17 18:01:01.828  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,11-17 18:01:01.828  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.828  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.828  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:01.828  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:01.838  5155  5155 E Zygote  : MountEmulatedStorage()
,11-17 18:01:01.838  5155  5155 E Zygote  : v2
11-17 18:01:01.838  5155  5155 I libpersona: KNOX_SDCARD checking this for 10035,
11-17 18:01:01.838  5155  5155 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:01.838  5155  5155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:01.838  1017  1029 I ActivityManager: Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5155 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:01:01.838  1017  1029 I ActivityManager: Killing 4617:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,11-17 18:01:01.848  5155  5155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:01.848  5155  5155 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,11-17 18:01:01.868  5155  5155 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:01.868  5155  5155 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:01.898  5155  5170 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,11-17 18:01:01.898  5155  5170 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,11-17 18:01:01.908  1933  3679 I Icing   : Indexing 13A41D57DAFE2A1AC75C4231EB152071BBE04BC1 from com.google.android.googlequicksearchbox
,11-17 18:01:01.908  5155  5170 D SPPClientService: PushLog.txt file is not deleted.
,11-17 18:01:01.908  5155  5170 D SPPClientService: PushLog.txt file is not deleted.
,11-17 18:01:01.908  5155  5170 D SPPClientService: ============PushLog. stop!
,11-17 18:01:01.938  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:01.938  1017  1777 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
11-17 18:01:01.938  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,11-17 18:01:01.938  1017  1777 I ActivityManager: Killing 3409:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,11-17 18:01:01.948  1017  1041 W libprocessgroup: failed to open /acct/uid_10100/pid_4617/cgroup.procs: No such file or directory
,11-17 18:01:01.958  1933  3679 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,11-17 18:01:01.958  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.958  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:01.958  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.958  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.958  1017  1438 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,11-17 18:01:01.958  1017  1438 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,11-17 18:01:01.958  1017  1438 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
11-17 18:01:01.958  1649  4287 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
11-17 18:01:01.958  1017  1438 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,11-17 18:01:01.968  1649  1649 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,11-17 18:01:01.978  1933  1933 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,11-17 18:01:01.978  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,11-17 18:01:01.978  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.978  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.978  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.998  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:01.998  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:01.998  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:01.998  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:01.998  4289  4289 D WearableService: callingUid 10012, callindPid: 4289
,11-17 18:01:02.018  1744  2496 E MDM     : [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,11-17 18:01:02.018  1017  1041 W libprocessgroup: failed to open /acct/uid_10015/pid_3409/cgroup.procs: No such file or directory
,11-17 18:01:02.028  1017  1777 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:02.028  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:02.028  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.028  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.038  1933  3679 I Icing   : Indexing done 13A41D57DAFE2A1AC75C4231EB152071BBE04BC1
,11-17 18:01:02.048  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,11-17 18:01:02.048  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.048  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.048  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.048  1933  5176 D LocationInitializer: Restart initialization of location
,11-17 18:01:02.048  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.048  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.048  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.048  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.068  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.068  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.068  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.068  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.078  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:02.078  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:02.078  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:02.078  1017  3527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:02.098  5178  5178 E Zygote  : MountEmulatedStorage()
11-17 18:01:02.098  5178  5178 E Zygote  : v2
,11-17 18:01:02.098  5178  5178 I libpersona: KNOX_SDCARD checking this for 10101
11-17 18:01:02.098  5178  5178 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:02.098  5178  5178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:01:02.098  1017  3527 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5178 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:01:02.098  5178  5178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
11-17 18:01:02.098  5178  5178 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,11-17 18:01:02.118  5178  5178 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:02.118  5178  5178 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:02.198  3959  4967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,11-17 18:01:02.208  2807  2807 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,11-17 18:01:02.208  1017  1049 D PowerManagerService: [s] UserActivityState : 2 -> 4
,11-17 18:01:02.208  1017  1049 I PowerManagerService: Nap time (uid 1000)...
,11-17 18:01:02.208  2807  2807 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
11-17 18:01:02.208  3959  3959 I Process : Sending signal. PID: 3959 SIG: 9
,11-17 18:01:02.208  1017  1049 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,11-17 18:01:02.208  1017  1049 I PowerManagerService: !@[ps] Screen__Off - 0 :  dream(timeout) (2)
11-17 18:01:02.208  1017  1049 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
11-17 18:01:02.208  1017  1049 D DisplayPowerController: getFinalBrightness : Summary is 1 -> 1
11-17 18:01:02.208  1017  1049 D DisplayPowerController: animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
11-17 18:01:02.208  1017  1049 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,11-17 18:01:02.208  1017  1049 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,11-17 18:01:02.208  1017  1049 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
11-17 18:01:02.208  1017  1155 V WindowOrientationListener: WindowOrientationListener disabled
,11-17 18:01:02.218  1017  1155 D SensorService: [SO] activate (ident=0xb966b8d0, enabled=0)
11-17 18:01:02.218  1017  1155 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,11-17 18:01:02.218  1017  1049 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
11-17 18:01:02.218  2807  2807 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
11-17 18:01:02.218  1017  1049 D PowerManagerService: handleSandman : startDream(true)
,11-17 18:01:02.218  1017  1049 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
11-17 18:01:02.218  1017  1049 I PowerManagerService: Sleeping (uid 1000)...
11-17 18:01:02.218  1017  1049 D PowerManagerService: [s] UserActivityState : 4 -> 0
,11-17 18:01:02.218   256   256 I SurfaceFlinger: id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,11-17 18:01:02.218  2807  2807 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,11-17 18:01:02.228  1017  1155 D SensorManager: unregisterListener ::   
,11-17 18:01:02.238  1017  1049 D PowerManagerService: Excessive delay in ColorFade : createSurface: 20ms
,11-17 18:01:02.238  1017  1049 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
11-17 18:01:02.238  1017  1049 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
11-17 18:01:02.238  1017  1049 I Adreno-EGL: Build Date: 04/06/15 Mon
11-17 18:01:02.238  1017  1049 I Adreno-EGL: Local Branch: 
11-17 18:01:02.238  1017  1049 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
11-17 18:01:02.238  1017  1049 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
11-17 18:01:02.238  1017  1049 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,11-17 18:01:02.248  1178  1190 D KeyguardViewMediator: onScreenTurnedOff(3)
11-17 18:01:02.248  1178  1190 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
11-17 18:01:02.248  1178  1190 D KeyguardEffectViewController: changeWallpaperByScreenOff()
,11-17 18:01:02.248  4533  4533 V ActivityThread: updateVisibility : ActivityRecord{1eb2ddd0 token=android.os.BinderProxy@27b2f7f5 {com.example.hello/com.example.hello.MainActivity}} show : true
,11-17 18:01:02.258  1178  1190 D KeyguardViewMediator: notifyScreenOffLocked
,11-17 18:01:02.258  1178  1190 D KeyguardViewMediator: timeout : 5000
,11-17 18:01:02.268  1017  1438 I ActivityManager: Process com.sec.android.app.sysscope (pid 3959)(adj 0) has died(58,1122)
,11-17 18:01:02.278  1178  1190 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1
11-17 18:01:02.278  1017  1092 E SmartFaceService: onReceive: android.intent.action.SCREEN_ON
,11-17 18:01:02.288  1178  1178 D KeyguardViewMediator: handleNotifyScreenOff
,11-17 18:01:02.288  1178  1178 D VolumePanel: onScreenTurnedOff()
11-17 18:01:02.288  1178  1178 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,11-17 18:01:02.288  1178  1178 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
,11-17 18:01:02.288  1017  1092 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,11-17 18:01:02.288  1178  1178 D SecKeyguardClockSingleView: onScreenTurnedOff
,11-17 18:01:02.288  1017  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,11-17 18:01:02.288  1017  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:02.288  1017  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:02.288  1017  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
11-17 18:01:02.288  1017  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
11-17 18:01:02.288  1017  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
11-17 18:01:02.288  1017  1092 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
11-17 18:01:02.288  1017  1092 E SmartFaceService: fail to set sysfs 1
11-17 18:01:02.288  1017  1092 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:01:02.288  1017  1092 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:01:02.288  1017  1092 W System.err: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:02.288  1017  1092 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:02.288  1017  1092 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
11-17 18:01:02.288  1017  1092 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:02.288  1017  1092 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:02.288  1017  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:02.288  1017  1092 W System.err: 	... 10 more
,11-17 18:01:02.298  1017  3531 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:02.298  1017  3531 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,11-17 18:01:02.298  1017  1049 D PowerManagerService: Excessive delay in ColorFade : createEglContext: 65ms
,11-17 18:01:02.318  1017  1049 D PowerManagerService: Excessive delay in ColorFade : createEglSurface: 13ms
,11-17 18:01:02.318   256  1098 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (214 us)
,11-17 18:01:02.318  1017  1017 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,11-17 18:01:02.328  1178  1178 D PanelView: There is/are notification(s) 
,11-17 18:01:02.328  1017  1017 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,11-17 18:01:02.328  1017  1104 E MotionRecognitionService:  handler : SCREEN_ON end
,11-17 18:01:02.328  1017  1017 D NotificationService: ACTION_SCREEN_ON
11-17 18:01:02.328  1017  1017 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,11-17 18:01:02.328  1017  1017 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,11-17 18:01:02.338  1017  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
11-17 18:01:02.338  1017  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
11-17 18:01:02.338  1017  1132 I WifiNative-HAL: startHal
,11-17 18:01:02.338  1017  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9cec37fc
11-17 18:01:02.338  1017  1132 I WifiNative-HAL: Could not start hal
,11-17 18:01:02.338  1017  1049 D PowerManagerService: Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 24ms
,11-17 18:01:02.348   282   282 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
11-17 18:01:02.348   282   282 V voice   : voice_set_parameters: enter: screen_state=on
11-17 18:01:02.348   282   282 V voice   : voice_set_parameters: exit with code(-2)
11-17 18:01:02.348   282   282 V msm8974_platform: platform_set_parameters: enter: screen_state=on
11-17 18:01:02.348   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
11-17 18:01:02.348   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
11-17 18:01:02.348   282   282 V audio_hw_primary: adev_set_parameters: exit
,11-17 18:01:02.358  1017  1047 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,11-17 18:01:02.358  1017  1047 D IpRemoteDisplayController: Bridge Server is not available
,11-17 18:01:02.358  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,11-17 18:01:02.358  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,11-17 18:01:02.368  1017  1017 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,11-17 18:01:02.368  1017  1061 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,11-17 18:01:02.368  1017  3532 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,11-17 18:01:02.368  1448  1448 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,11-17 18:01:02.388  1017  1049 D PowerManagerService: Excessive delay in ColorFade : initGLShaders: 39ms
,11-17 18:01:02.388  1017  1049 D PowerManagerService: Excessive delay in ColorFade prepare: 171ms
11-17 18:01:02.388  1596  1596 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
11-17 18:01:02.388  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,11-17 18:01:02.388  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
11-17 18:01:02.388  1017  1049 D DisplayPowerController: ColorFade: onAnimationStart
11-17 18:01:02.388  1017  1049 D DisplayPowerController: getFinalBrightness : Summary is 5 -> 5
11-17 18:01:02.388  1017  1049 D DisplayPowerController: performScreenOffTransition : no brightness animation
,11-17 18:01:02.388  1448  5200 D NfcService: call the applyRouting
11-17 18:01:02.388  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,11-17 18:01:02.388  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.388  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:02.388  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:02.388  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,11-17 18:01:02.418  5178  5201 I Gmail   : getAccountsCursor
,11-17 18:01:02.418  1017  1291 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:02.418  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.418  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.418  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.418  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.428  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:02.438  2807  2880 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 18 sec
,11-17 18:01:02.438  2807  2880 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,11-17 18:01:02.448  2807  2880 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,11-17 18:01:02.458  2807  2880 E DBG_DM  : [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,11-17 18:01:02.458  1778  1778 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,11-17 18:01:02.458  2807  2880 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,11-17 18:01:02.458  1017  1017 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1017) 
,11-17 18:01:02.458  1017  1017 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
11-17 18:01:02.458  1017  1017 D BatteryService: turn on LED for charging
11-17 18:01:02.458  1017  1077 E lights  : write_int failed to open -1
11-17 18:01:02.458  1017  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
11-17 18:01:02.458  1017  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,11-17 18:01:02.468  1017  1092 E SmartFaceService: onReceive: android.intent.action.SCREEN_OFF
,11-17 18:01:02.468  1017  1092 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
11-17 18:01:02.468  1017  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:02.468  1017  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:02.468  1017  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:02.468  1017  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
11-17 18:01:02.468  1017  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
11-17 18:01:02.468  1017  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
11-17 18:01:02.468  1017  1092 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
11-17 18:01:02.468  1017  1092 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:01:02.468  1017  1092 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:01:02.468  1017  1092 W System.err: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:02.468  1017  1092 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:02.468  1017  1092 E SmartFaceService: fail to set sysfs 0
11-17 18:01:02.468  1017  1092 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
11-17 18:01:02.468  1017  1092 W System.err: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:02.468  1017  1092 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:02.468  1017  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:02.468  1017  1092 W System.err: 	... 10 more
,11-17 18:01:02.468  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
11-17 18:01:02.468  1017  1216 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,11-17 18:01:02.468  5178  5178 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,11-17 18:01:02.468  1017  2603 D SSRM:n  : SIOP:: AP = 410
,11-17 18:01:02.488  1178  1178 D PanelView: There is/are notification(s) 
,11-17 18:01:02.488  1017  1017 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,11-17 18:01:02.498  5178  5209 I Gmail   : Observing account changes for notifications
,11-17 18:01:02.498  1017  1132 I WifiNative-HAL: startHal
11-17 18:01:02.498  1017  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9cec37fc
11-17 18:01:02.498  1017  1132 I WifiNative-HAL: Could not start hal
,11-17 18:01:02.498  1017  1017 D NotificationService: ACTION_SCREEN_OFF
11-17 18:01:02.498  1017  1017 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
,11-17 18:01:02.498  1017  1104 E MotionRecognitionService:  handler : SCREEN_OFF end 
11-17 18:01:02.498  1017  1017 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
11-17 18:01:02.508  1017  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
11-17 18:01:02.508  1017  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,11-17 18:01:02.508  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.508   282   778 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-17 18:01:02.508   282   778 V voice   : voice_set_parameters: enter: screen_state=off
11-17 18:01:02.508  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.508  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.508  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,11-17 18:01:02.508   282   778 V voice   : voice_set_parameters: exit with code(-2)
11-17 18:01:02.508   282   778 V msm8974_platform: platform_set_parameters: enter: screen_state=off
11-17 18:01:02.508   282   778 V msm8974_platform: platform_set_parameters: exit with code(-2)
11-17 18:01:02.508   282   778 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,11-17 18:01:02.508   282   778 V audio_hw_primary: adev_set_parameters: exit
11-17 18:01:02.508  1017  1761 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:02.508  1017  1761 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,11-17 18:01:02.528  1017  1047 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,11-17 18:01:02.528  1017  1047 D IpRemoteDisplayController: Bridge Server is not available
,11-17 18:01:02.528  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,11-17 18:01:02.538  1017  1280 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
11-17 18:01:02.538  1017  1280 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,11-17 18:01:02.538  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,11-17 18:01:02.538  1017  1706 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.538  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.538  1017  1706 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.538  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,11-17 18:01:02.538  1423  1423 V EmergencyMode: [EmergencyStateReceiver] binteractive [false] why[3]
,11-17 18:01:02.538  1017  1017 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
,11-17 18:01:02.548  1017  1061 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,11-17 18:01:02.558  1448  5214 D NfcService: call the applyRouting
,11-17 18:01:02.558  5178  5215 E Gmail   : Error finding the version of the Email provider.....
11-17 18:01:02.558  5178  5215 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
11-17 18:01:02.558  5178  5215 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
11-17 18:01:02.558  5178  5215 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
11-17 18:01:02.558  5178  5215 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
11-17 18:01:02.558  5178  5215 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:02.558  5178  5215 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:02.558  5178  5215 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:02.558  5178  5215 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:02.558  5178  5215 W EmailMigration: We do not support migrating this version of the Email provider.
,11-17 18:01:02.558  1596  1596 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,11-17 18:01:02.558  1596  1596 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,11-17 18:01:02.568  5178  5217 I Gmail   : getAccountsCursor
,11-17 18:01:02.568  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.568  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:02.568  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:02.568  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,11-17 18:01:02.568  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.578  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.578  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:02.578  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,11-17 18:01:02.578  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.578  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:02.588  1596  1596 D accuweather: [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,11-17 18:01:02.598  1017  1049 D DisplayPowerState: !@ ColorFade entry
,11-17 18:01:02.598  1017  1049 D DisplayPowerController: ColorFade: onAnimationEnd
,11-17 18:01:02.608  1017  1159 D lights  : lcd : 0 +
,11-17 18:01:02.608  1017  1049 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
11-17 18:01:02.608  1017  1049 D DisplayPowerController: performScreenOffTransition : no brightness animation
,11-17 18:01:02.608  1017  1159 D lights  : lcd : 0 -
,11-17 18:01:02.618  1017  1049 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,11-17 18:01:02.618  1017  1049 D DisplayPowerController: performScreenOffTransition : no brightness animation
11-17 18:01:02.618  1017  1049 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,11-17 18:01:02.618  1017  1049 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,11-17 18:01:02.618  1017  5222 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
11-17 18:01:02.618  1017  5222 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
11-17 18:01:02.618  1017  5221 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 0
,11-17 18:01:02.618  1017  5221 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,11-17 18:01:02.618  1017  1054 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,11-17 18:01:02.618  1017  1054 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
11-17 18:01:02.618  1017  1054 I QCOM PowerHAL: Got set_interactive hint
,11-17 18:01:02.628  1017  1054 D DisplayManagerService: !@display_state: ON -> OFF
,11-17 18:01:02.628  1017  1047 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,11-17 18:01:02.628  1017  1017 V ActivityManager: Display changed displayId=0
,11-17 18:01:02.628   256   256 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb828d690
,11-17 18:01:02.628   256   256 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-17 18:01:02.628   256   256 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
11-17 18:01:02.628   256   256 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,11-17 18:01:02.748  1017  1493 I art     : Explicit concurrent mark sweep GC freed 29976(1717KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 26MB/40MB, paused 2.140ms total 152.752ms
,11-17 18:01:02.748  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:02.748  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:02.748  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:02.748  1017  1777 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:02.768  5225  5225 E Zygote  : MountEmulatedStorage()
,11-17 18:01:02.768  5225  5225 E Zygote  : v2
11-17 18:01:02.768  5225  5225 I libpersona: KNOX_SDCARD checking this for 10104
11-17 18:01:02.768  5225  5225 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:02.768  5225  5225 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:02.768  5225  5225 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:02.768  1017  1777 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5225 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
11-17 18:01:02.768  1178  1178 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
11-17 18:01:02.768  1017  1777 I ActivityManager: Killing 4368:com.android.mms/u0a46 (adj 15): empty #31
11-17 18:01:02.768  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
11-17 18:01:02.768  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
11-17 18:01:02.768  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,11-17 18:01:02.768  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
11-17 18:01:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
11-17 18:01:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
11-17 18:01:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
11-17 18:01:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
11-17 18:01:02.778  5225  5225 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,11-17 18:01:02.788  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.798  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:02.798  1017  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:02.798  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.798  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.798  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.808  5225  5225 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:02.808  5225  5225 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:02.828  5225  5225 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,11-17 18:01:02.828  1852  1852 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,11-17 18:01:02.828  1017  1155 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,11-17 18:01:02.838  5178  5240 E SQLiteLog: (283) recovered 96 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,11-17 18:01:02.838  1017  2603 D SSRM:n  : SIOP:: AP = 410
,11-17 18:01:02.878   256   526 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-17 18:01:02.878   256   526 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
,11-17 18:01:02.878   256   526 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
11-17 18:01:02.878   256   256 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-17 18:01:02.878  1017  1054 D SurfaceControl: Excessive delay in setPowerMode(): 258ms
11-17 18:01:02.878  1017  1054 I libsuspend: !@autosuspend_wakeup_count_enable
11-17 18:01:02.878  1017  1054 D PowerManagerService: Excessive delay in !@display_state: OFF: 258ms
11-17 18:01:02.878  1017  1054 I libsuspend: !@autosuspend_wakeup_count_enable done
,11-17 18:01:02.878  1017  1054 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 268ms
11-17 18:01:02.878  1017  1049 I PowerManagerService: [PWL] Off : 0s ago
,11-17 18:01:02.878  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
11-17 18:01:02.888  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,11-17 18:01:02.888  5178  5240 E File    : fail readDirectory() errno=2
11-17 18:01:02.888  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1017, ws=WorkSource{10104}) (elapsedTime=24348)
,11-17 18:01:02.888  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1933, ws=null) (elapsedTime=17089)
,11-17 18:01:02.898  5178  5241 I Gmail   : notifyAccountChanged
,11-17 18:01:02.898  5178  5201 I Gmail   : getAccountsCursor
,11-17 18:01:02.898  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:01:02.898  5178  5241 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,11-17 18:01:02.908  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:02.908  5178  5241 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,11-17 18:01:02.918  1017  3532 D CountryDetector: No listener is left
,11-17 18:01:02.918  5178  5241 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,11-17 18:01:02.918  5178  5241 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,11-17 18:01:02.918  1017  1280 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,11-17 18:01:02.928  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:02.928  1017  1280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.928  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.928  1017  1777 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:02.938  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:02.938  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.938  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.958  1017  3532 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:02.968  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:02.968  1017  3532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:02.968  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:02.988  1017  1041 W libprocessgroup: failed to open /acct/uid_10046/pid_4368/cgroup.procs: No such file or directory
,11-17 18:01:03.008  5178  5202 I Gmail   : getAccountsCursor
,11-17 18:01:03.008  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.008  1649  1649 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:01:03.018  5225  5249 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
11-17 18:01:03.018  5225  5249 I Babel_SMS: MmsConfig.loadMmsSettings
11-17 18:01:03.018  5225  5249 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
11-17 18:01:03.018  5225  5249 I Babel_SMS: MmsConfig.loadFromDatabase
,11-17 18:01:03.048  5225  5249 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
11-17 18:01:03.048  5225  5249 I Babel_SMS: MmsConfig.loadFromResources
,11-17 18:01:03.048  5225  5249 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,11-17 18:01:03.048  5225  5249 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,11-17 18:01:03.078   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 0
11-17 18:01:03.078   282   282 W QCamera2Factory: getCameraInfo: X
,11-17 18:01:03.078   282   778 W QCamera2Factory: getCameraInfo: E, camera_id = 1
11-17 18:01:03.078   282   778 W QCamera2Factory: getCameraInfo: X
,11-17 18:01:03.078  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.088  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.088  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.088  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,11-17 18:01:03.098   287   287 E SMD     : DCD OFF
,11-17 18:01:03.108  5225  5225 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:01:03.108  5225  5225 I Babel_Crash: startup - clean
,11-17 18:01:03.118  5225  5252 I Babel   : deleted: false for 0
,11-17 18:01:03.128  1017  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:03.128  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.128  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.128  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.158  1017  1777 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.158  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.158  1017  1777 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.158  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,11-17 18:01:03.168  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.168  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.168  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.168  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,11-17 18:01:03.178  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.178  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.178  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.178  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,11-17 18:01:03.188  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.188  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.188  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.188  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,11-17 18:01:03.198  5225  5225 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:03.198   277   974 D EnterpriseController: uids 10012
11-17 18:01:03.198   277   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
11-17 18:01:03.198   277   974 D Netd    : getNetworkForDns: using netid 0 for uid 10012
,11-17 18:01:03.198  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.198  5225  5225 W AudioCapabilities: Unsupported mime audio/evrc
,11-17 18:01:03.198  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.208  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.208  5225  5225 W AudioCapabilities: Unsupported mime audio/qcelp
11-17 18:01:03.208  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.208  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.208  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.208  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.208  1017  1030 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,11-17 18:01:03.208  1017  1030 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
11-17 18:01:03.208  1649  4299 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,11-17 18:01:03.208  1017  1030 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
11-17 18:01:03.208  1017  1030 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,11-17 18:01:03.208  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.208  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.208  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.218  5225  5225 W AudioCapabilities: Unsupported mime audio/mpeg-L1
11-17 18:01:03.218  5225  5225 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,11-17 18:01:03.218  5225  5225 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,11-17 18:01:03.218  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.218  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.218  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:01:03.218  5225  5225 W AudioCapabilities: Unsupported mime audio/x-ima
,11-17 18:01:03.228  1649  1649 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,11-17 18:01:03.228  5225  5225 W AudioCapabilities: Unsupported mime audio/qcelp
,11-17 18:01:03.228  5225  5225 W AudioCapabilities: Unsupported mime audio/evrc
,11-17 18:01:03.228  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.228  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.228  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.228  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.238  1017  3527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.238  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.238  1933  1933 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,11-17 18:01:03.238  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.238  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.238  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.238  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.238  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.238  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.238  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.248  5225  5225 W VideoCapabilities: Unsupported mime video/wvc1
,11-17 18:01:03.248  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.248  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.248  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.248  5225  5225 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,11-17 18:01:03.248  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.248  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.248  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.258  1017  2603 D SSRM:a  : DeviceInfo:: 000000000000
,11-17 18:01:03.258  1017  2603 D SSRM:a  : SettingsAirViewInfo:: 000000000
,11-17 18:01:03.258  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.258  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.258  5178  5254 I NotifUtils: Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,11-17 18:01:03.268  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.268  1744  4288 E MDM     : [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,11-17 18:01:03.268  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.268  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:03.268  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.278  5225  5225 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,11-17 18:01:03.278  5225  5225 W VideoCapabilities: Unsupported mime video/wvc1
,11-17 18:01:03.278  5225  5225 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,11-17 18:01:03.278  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.278  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:03.278  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.278  5225  5225 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,11-17 18:01:03.288  1017  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:03.288  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.288  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:03.288  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.288  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.288  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.288  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.298  5225  5225 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,11-17 18:01:03.298  5225  5225 W VideoCapabilities: Unsupported mime video/mp43
,11-17 18:01:03.298  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.298  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.298  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.298  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,11-17 18:01:03.298  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.298  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.298  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.298  5225  5225 W VideoCapabilities: Unsupported mime video/sorenson
,11-17 18:01:03.308  1933  5261 D LocationInitializer: Restart initialization of location
,11-17 18:01:03.308  1017  3532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.308  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.308  1017  3532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.308  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.308  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.308  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.308  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,11-17 18:01:03.318  5225  5225 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,11-17 18:01:03.328  5225  5225 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,11-17 18:01:03.338  4533  4533 D BluetoothAdapter: disable()
,11-17 18:01:03.338  1017  3532 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,11-17 18:01:03.338  5178  5254 I NotifUtils: validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,11-17 18:01:03.348  1017  1761 D SecContentProvider: uri = 18 selection = isWifiEnabled
,11-17 18:01:03.348  1017  1761 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,11-17 18:01:03.348  1017  1761 D SecContentProvider2: mCursor = null
,11-17 18:01:03.348  1017  1761 D WifiService: setWifiEnabled: false pid=4533, uid=10174
,11-17 18:01:03.348  1017  1761 D SettingsProvider: name = wifi_on
,11-17 18:01:03.358  4533  4533 I jxcore-log: ****TEST TOOK:  5053  ms ****,
11-17 18:01:03.358  4533  4533 I jxcore-log: 
11-17 18:01:03.358  4533  4533 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:01:03.358  4533  4533 I jxcore-log: 
,11-17 18:01:03.368  5225  5225 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:03.368  5225  5225 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:03.368  5225  5225 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:03.368  5225  5225 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:03.428  1017  3532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,11-17 18:01:03.428  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.428  1017  3532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.428  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,11-17 18:01:03.428  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,11-17 18:01:03.428  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:03.428  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.428  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,11-17 18:01:03.438  5225  5225 I vclib   : onServiceConnected
,11-17 18:01:03.438  5225  5225 W Babel   : Attempted to change video mute state without an active call.
,11-17 18:01:03.448  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.448  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.448  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.448  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:03.468  5270  5270 E Zygote  : MountEmulatedStorage()
,11-17 18:01:03.468  5270  5270 E Zygote  : v2
11-17 18:01:03.468  5270  5270 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:01:03.468  5270  5270 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:03.478  5270  5270 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,11-17 18:01:03.478  5270  5270 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:01:03.478  1017  1216 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5270 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
11-17 18:01:03.478  5270  5270 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:03.478  5225  5225 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:01:03.478  5225  5225 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
11-17 18:01:03.488  1017  3532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.488  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.488  1017  3532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.488  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,11-17 18:01:03.508   305   305 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 781us total 29.390ms
,11-17 18:01:03.528  5225  5225 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
11-17 18:01:03.528   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 19.952ms,
,11-17 18:01:03.538  5270  5270 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:01:03.538  5270  5270 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:03.548   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 17.499ms
,11-17 18:01:03.568  5270  5270 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,11-17 18:01:03.568  1017  1492 D SecContentProvider2: uri = 14 selection = getSealedState
11-17 18:01:03.568  1017  1492 D SecContentProvider2: mCursor = null
,11-17 18:01:03.578  1017  1029 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,11-17 18:01:03.578  1017  1029 D SecContentProvider2: mCursor = null
,11-17 18:01:03.578  5270  5270 V MTPRx   : sealedState: false
11-17 18:01:03.578  5270  5270 V MTPRx   : sealedUsbMassStorageState: false,
11-17 18:01:03.578  5270  5270 E MTPRx   : check value of boot_completed is1
11-17 18:01:03.578  5270  5270 E MTPRx   : check booting is completed_sys.boot_completed,
11-17 18:01:03.578  5270  5270 E MTPRx   : Sd-Card path/storage/extSdCard
11-17 18:01:03.578  5270  5270 E MTPRx   : Status for mount/Unmount :removed
11-17 18:01:03.578  5270  5270 E MTPRx   : SDcard is not available
,11-17 18:01:03.578  5270  5270 W MTPRx   : value of connected istrue
11-17 18:01:03.578  5270  5270 W MTPRx   : value of configured istrue
11-17 18:01:03.578  5270  5270 W MTPRx   : value of mtpEnabled istrue
11-17 18:01:03.578  5270  5270 W MTPRx   : value of ptpEnabled isfalse
,11-17 18:01:03.578  5270  5270 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,11-17 18:01:03.578  5270  5270 E MTPRx   : mFirstTime: false
,11-17 18:01:03.588  5225  5225 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
11-17 18:01:03.588  5225  5225 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14cf4d0d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
11-17 18:01:03.588  5225  5225 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-17 18:01:03.598  1017  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
11-17 18:01:03.598  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.598  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.598  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.658  5270  5270 D         : MTP: reading debug level property
,11-17 18:01:03.658  5270  5270 E MTPJNIInterface: Getting CryptionKey from JAVA
11-17 18:01:03.658  5270  5270 E MTPRx   : currentUserId is 0
,11-17 18:01:03.658  5270  5270 E MTPRx   : Start observing USB_STATE_MATCH ,
11-17 18:01:03.658  5270  5270 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
11-17 18:01:03.658  5270  5270 E MTPRx   : is_Privatemode is NOT 1
11-17 18:01:03.658  5225  5264 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:03.658  5225  5264 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:01:03.668  1017  1706 D SettingsProvider: name = mtp_usb_conditions_met
,11-17 18:01:03.668  1017  1030 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,11-17 18:01:03.668  5270  5270 E MTPRx   : sending MTP_ICON_ENABLED to stack
,11-17 18:01:03.668  1017  1777 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
11-17 18:01:03.668  5225  5264 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:01:03.668  1017  1777 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.668  1017  1777 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:03.668  1017  1777 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,11-17 18:01:03.668  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.678  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.678  1017  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.678  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
11-17 18:01:03.678  1017  1216 D SettingsProvider: name = mtp_running_status
,11-17 18:01:03.678  1017  1280 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:03.678  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.678  1017  1280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:03.678  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:03.688  1017  3532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.688  1017  3532 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.688  1017  3532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,11-17 18:01:03.688  1017  3532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
11-17 18:01:03.688  5225  5289 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,11-17 18:01:03.728  1017  1030 D SettingsProvider: name = mtp_usb_conditions_met
,11-17 18:01:03.738  5270  5270 E MTPRx   : else part ... so first time!!!
,11-17 18:01:03.738  5270  5270 E MTPPlaObsrvr: inside setContext()
11-17 18:01:03.738  5270  5270 E MTPPlaObsrvr:  inside createplafiles
,11-17 18:01:03.738  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,11-17 18:01:03.738  5270  5270 E MTPPlaObsrvr: playlist count is0
11-17 18:01:03.738  5270  5270 E MTPPlaObsrvr:  inside try branch createplafiles
,11-17 18:01:03.738  5270  5270 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,11-17 18:01:03.748  5270  5270 E MTPPlaObsrvr: Inside registerContentObserver
,11-17 18:01:03.748  5270  5270 E MtpAdbObserver: inside setContext()
,11-17 18:01:03.748  5270  5270 E MtpAdbObserver: Inside registerContentObserver
,11-17 18:01:03.748  5270  5270 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,11-17 18:01:03.748  5270  5291 V MtpMediaDBManager: inside deleteAllDB
11-17 18:01:03.748  1017  3527 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.748  1017  3527 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.748  1017  3527 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:03.748  1017  3527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
11-17 18:01:03.748  1017  1449 D SettingsProvider: name = mtp_running_status
11-17 18:01:03.748  1017  1492 D SettingsProvider: name = mtp_usb_conditions_met
11-17 18:01:03.758  5270  5270 E MtpService: onCreate.
,11-17 18:01:03.758  5270  5270 E MtpService: < MTP > Registering BroadCast receiver :::::
,11-17 18:01:03.758  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.758  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.758  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:03.758  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
11-17 18:01:03.758  5270  5270 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,11-17 18:01:03.768  5270  5270 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,11-17 18:01:03.768  5270  5270 E MtpService: onStartCommand.
11-17 18:01:03.768  5270  5270 W MTPRx   : calling native method
11-17 18:01:03.768  5270  5270 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
11-17 18:01:03.768  5270  5292 E MtpService: handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
11-17 18:01:03.768  1225  1225 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
11-17 18:01:03.768  1017  1280 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.768  1017  1280 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.768  1017  1280 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.768  1017  1280 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:03.778  5293  5293 E Zygote  : MountEmulatedStorage()
,11-17 18:01:03.778  5293  5293 E Zygote  : v2
11-17 18:01:03.778  5293  5293 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:01:03.778  5293  5293 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:03.778  5270  5291 V MtpMediaDBManager: inside Thread updateDB
,11-17 18:01:03.778  1017  1280 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5293 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,11-17 18:01:03.788  5293  5293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:01:03.788  5270  5270 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
11-17 18:01:03.788  5270  5270 E MTPJNIInterface: noti = 10
11-17 18:01:03.788  5270  5270 E MtpService: onStartCommand.
11-17 18:01:03.788  5270  5292 E MtpService: handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
11-17 18:01:03.788  5270  5291 E MtpMediaDBManager: count : 27
,11-17 18:01:03.788  5270  5270 W MTPRx   : calling native method
11-17 18:01:03.788  5270  5270 E MTPRx   : Checking the driver time out
11-17 18:01:03.788  5270  5270 E MTPJNIInterface: noti = 2
11-17 18:01:03.788  5270  5270 D         : deleting sockets before message queue initialization
11-17 18:01:03.788  5293  5293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:03.798  5270  5270 D         : event handler thread is created, so set the flag
11-17 18:01:03.798  5293  5293 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:03.798  5270  5270 E MTPRx   : called native method
11-17 18:01:03.798  5270  5270 E MTPJNIInterface: setting Media scanner status0
11-17 18:01:03.798  5270  5270 E MTPJNIInterface: After setting Media scanner status0
11-17 18:01:03.798  5270  5270 W MTPRx   : notification from stack 1
11-17 18:01:03.798  5270  5299 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
11-17 18:01:03.798  5270  5299 E MTPJNIInterface: Getting media scanner status0
,11-17 18:01:03.798  5270  5299 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A5)
,11-17 18:01:03.808  5270  5291 W MtpMediaDBManager: sending db update complete noti to stack
11-17 18:01:03.808  5270  5291 E MTPJNIInterface: noti = 29
,11-17 18:01:03.808  5270  5299 E SQLiteLog: (5) database is locked
,11-17 18:01:03.818  5293  5293 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:03.818  5293  5293 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:03.828  5032  5032 I PolicyManagerBroadcastReceiver: This process will be killed soon.
11-17 18:01:03.828  5032  5032 I Process : Sending signal. PID: 5032 SIG: 9
,11-17 18:01:03.828  5270  5299 E MTPJNIInterface: Status for mount/Unmount :removed
11-17 18:01:03.828  5270  5299 E MTPJNIInterface: SDcard is not available
,11-17 18:01:03.838  5270  5299 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
11-17 18:01:03.838  5267  5267 D AndroidRuntime: 
11-17 18:01:03.838  5267  5267 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:01:03.848  5270  5299 E MTPJNIInterface: Status for mount/Unmount :removed
11-17 18:01:03.848  5270  5299 E MTPJNIInterface: SDcard is not available
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) API call with NULL database connection pointer
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) API call with NULL database connection pointer
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) API call with NULL database connection pointer
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) API call with NULL database connection pointer
11-17 18:01:03.848  5270  5299 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
11-17 18:01:03.848  5270  5309 D         : [mtp_init_device] Library open with 32 bits.
11-17 18:01:03.848  5270  5309 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,11-17 18:01:03.848  5270  5270 W MTPRx   : notification from stack 2
11-17 18:01:03.848  5270  5309 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,11-17 18:01:03.848  5270  5309 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
11-17 18:01:03.848  5270  5309 E         :  [sua_support_present:1287] returning false 
11-17 18:01:03.848  5270  5309 D         : *****Starting mtp_io()
11-17 18:01:03.848  5267  5267 D AndroidRuntime: CheckJNI is OFF
11-17 18:01:03.848  5267  5267 D AndroidRuntime: readGMSProperty: start
11-17 18:01:03.848  5267  5267 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:01:03.848  5267  5267 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-17 18:01:03.848  5267  5267 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:01:03.848  5267  5267 D AndroidRuntime: readGMSProperty: end
11-17 18:01:03.848  5267  5267 D AndroidRuntime: addProductProperty: start
,11-17 18:01:03.848  5270  5270 W MTPRx   : notification from stack 3,
11-17 18:01:03.848  5270  5309 D         : [mtp_start_io] source_thread Creation 
11-17 18:01:03.848  5270  5309 D         : [mtp_start_io] sink_thread Creation 
11-17 18:01:03.848  5270  5309 D         : [mtp_start_io:376] sink thread created so set th_sink
,11-17 18:01:03.878  5293  5293 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main,
11-17 18:01:03.878  5293  5293 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter
,11-17 18:01:03.878  5293  5293 D TMNetworkReceiver: MirrorLink feauture level: using UEvent
,11-17 18:01:03.888  1017  1487 I ActivityManager: Killing 4654:com.samsung.helphub/1000 (adj 15): empty #31
,11-17 18:01:03.888  1225  1225 D MediaScannerReceiver: action: com.samsung.intent.action.MTP_FILE_SCAN
,11-17 18:01:03.888  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,11-17 18:01:03.888  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:03.888  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:03.888  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
11-17 18:01:03.898  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.898  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.898  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:03.898  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:03.908  5315  5315 E Zygote  : MountEmulatedStorage()
,11-17 18:01:03.908  5315  5315 I libpersona: KNOX_SDCARD checking this for 10042
11-17 18:01:03.908  5315  5315 E Zygote  : v2
11-17 18:01:03.908  5315  5315 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:03.908  5315  5315 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:03.918  5315  5315 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:03.918  5315  5315 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
11-17 18:01:03.918  1017  1030 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5315 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:01:03.918  1017  1291 I ActivityManager: Process com.sec.android.app.wluc (pid 5032)(adj 15) has died(50,1128)
,11-17 18:01:03.938  5315  5315 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:03.938  5315  5315 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:03.948  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4654/cgroup.procs: No such file or directory
,11-17 18:01:03.958  5315  5315 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:01:03.978  5315  5315 I CalendarProvider2: CalendarProvider2.onCreate() called
,11-17 18:01:03.998  1225  5314 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,11-17 18:01:04.008  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter started
,11-17 18:01:04.008  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,11-17 18:01:04.018  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:04.018  1017  3531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:04.018  1017  3531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:01:04.018  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
11-17 18:01:04.018  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
11-17 18:01:04.018  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter finished
11-17 18:01:04.018  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter started
,11-17 18:01:04.018  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,11-17 18:01:04.018  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,11-17 18:01:04.018  1225  5314 D MediaProvider: savePlaylistTableInBulkDeleter finished
,11-17 18:01:04.028  1225  5314 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,11-17 18:01:04.038  1225  5314 V MediaScanner: processDirectory :  /storage/emulated/0
,11-17 18:01:04.038  1225  5314 D MediaScanner: Skipping:
11-17 18:01:04.038  1225  5314 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
11-17 18:01:04.048  1225  5314 D MediaScanner: Skipping:
11-17 18:01:04.048  1225  5314 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,11-17 18:01:04.058  1225  5314 V MediaScanner: processDirectory :  /storage/extSdCard
11-17 18:01:04.058  1225  5314 W MediaScanner: Error opening directory, reason : Permission denied.
11-17 18:01:04.058  1225  5314 W MediaScanner: 7klwibgf7fxlKdCbid7
,11-17 18:01:04.058  1017  1706 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,11-17 18:01:04.058  1225  5314 V MediaScanner:  prescan time: 19ms (DB items: 27)
11-17 18:01:04.058  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:04.058  1225  5314 V MediaScanner:     scan time: 18ms (Caching mode: true), (makeEntry time: 10ms ~55%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
11-17 18:01:04.058  1017  1706 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:04.058  1225  5314 V MediaScanner: postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
11-17 18:01:04.058  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
11-17 18:01:04.058  1225  5314 V MediaScanner:    total time: 40ms
11-17 18:01:04.058  1225  5314 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,11-17 18:01:04.068  5270  5270 E MTPJNIInterface: In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,11-17 18:01:04.068  1225  5314 D MediaScannerService: !@done scanning volume external
,11-17 18:01:04.068  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:04.068  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:04.068  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,11-17 18:01:04.068  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.068  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:04.068  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:04.068  1017  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.078  5341  5341 E Zygote  : MountEmulatedStorage()
,11-17 18:01:04.078  5341  5341 E Zygote  : v2
11-17 18:01:04.078  5341  5341 I libpersona: KNOX_SDCARD checking this for 10142
11-17 18:01:04.078  5341  5341 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:04.078  5341  5341 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,11-17 18:01:04.088  1017  1216 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5341 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,11-17 18:01:04.088  5341  5341 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,11-17 18:01:04.088  5341  5341 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,11-17 18:01:04.108  5315  5340 E SQLiteLog: (284) automatic index on view_events(_id)
,11-17 18:01:04.128  5341  5341 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:04.128  5341  5341 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:04.138  5267  5267 E AffinityControl: AffinityControl: registerfunction enter
,11-17 18:01:04.148  5315  5340 D CalendarAlarmManager: sys current time:1447779664111
,11-17 18:01:04.148  5315  5340 D CalendarAlarmManager: reminder amount:0
,11-17 18:01:04.168  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,11-17 18:01:04.168   329   329 I ServiceManager: Waiting for service AtCmdFwd...
11-17 18:01:04.168  5341  5341 V TaskCloserActivity: TaskCloserActivity enter()
11-17 18:01:04.168  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:04.168  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:04.168  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,11-17 18:01:04.168  5267  5267 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:01:04.168  5341  5341 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,11-17 18:01:04.178  1933  5338 I art     : Explicit concurrent mark sweep GC freed 32281(2MB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 12MB/20MB, paused 1.280ms total 79.861ms,
,11-17 18:01:04.188  1017  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,11-17 18:01:04.188  1017  3532 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
11-17 18:01:04.188  1017  3532 D PackageManager: START PACKAGE DELETE: observer{244309339},
11-17 18:01:04.188  1017  3532 D PackageManager: pkg{<packageName>}
11-17 18:01:04.188  1017  3532 D PackageManager: user{0}
11-17 18:01:04.188  1017  3532 D PackageManager: caller{2000}
11-17 18:01:04.188  1017  3532 D PackageManager: flags{3}
11-17 18:01:04.188  1017  3532 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
11-17 18:01:04.188  1017  1493 I splitIntent: intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
11-17 18:01:04.188  1017  3532 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
11-17 18:01:04.188  1017  1493 I splitIntent: base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GmsPackageWatcher
11-17 18:01:04.188  1017  1449 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:04.188  1017  1493 I splitIntent: other index=14, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
11-17 18:01:04.188  1017  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:04.188  1017  1493 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
11-17 18:01:04.188  1017  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
11-17 18:01:04.188  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
11-17 18:01:04.188  1017  3532 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
11-17 18:01:04.188  1017  1056 D PackageManager: !@killApplicatoin: 10174, uninstall pkg
11-17 18:01:04.188  1017  3532 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
11-17 18:01:04.188  1017  1056 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:0
11-17 18:01:04.188  1017  1056 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:-1
11-17 18:01:04.188  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
11-17 18:01:04.188  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
11-17 18:01:04.188  1933  5338 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 164 ms
,11-17 18:01:04.198  1649  1649 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
11-17 18:01:04.198  1017  1042 I ActivityManager: Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
11-17 18:01:04.198  1017  1042 I ActivityManager: Killing 4533:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,11-17 18:01:04.268  1017  1056 W PackageSettings: Skipping PackageSetting{16a01f7d com.test.thalitest/10175} due to missing metadata
,11-17 18:01:04.298  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{c2d33ad u0 com.example.hello/.MainActivity t228}
,11-17 18:01:04.308  1017  1280 I WindowState: WIN DEATH: Window{2a71bcf1 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:01:04.308   256  1161 I SurfaceFlinger: id=11 Removed NainActivit (6/8)
,11-17 18:01:04.308  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,11-17 18:01:04.308   256   449 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
11-17 18:01:04.308  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:04.308  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:04.308  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,11-17 18:01:04.308  1017  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.requestwriter.RequestWriter; callingUser = 0; userId(target) = 0
,11-17 18:01:04.308  1017  1438 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:04.308  1017  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:04.308  1017  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,11-17 18:01:04.318  1017  1280 D InputDispatcher: Focus left window: 4533
,11-17 18:01:04.318  1017  1056 I ActivityManager: Force stopping com.example.hello appid=10174 user=0: pkg removed
,11-17 18:01:04.318  1017  1056 I ActivityManager:   Force finishing activity ActivityRecord{c2d33ad u0 com.example.hello/.MainActivity t228 f}
11-17 18:01:04.318  1017  1056 W ActivityManager: Duplicate finish request for ActivityRecord{c2d33ad u0 com.example.hello/.MainActivity t228 f}
,11-17 18:01:04.318  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:01:04.318  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,11-17 18:01:04.328  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,11-17 18:01:04.358  1017  1042 D InputDispatcher: Focused application released
,11-17 18:01:04.368  3745  3745 I art     : Explicit concurrent mark sweep GC freed 2178(132KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 717us total 25.900ms
,11-17 18:01:04.368  4250  4250 I art     : Explicit concurrent mark sweep GC freed 15467(1303KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 1.003ms total 41.919ms
,11-17 18:01:04.378  1017  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:01:04.388  1778  1778 E SamsungIME: mOCRHelper is null,
,11-17 18:01:04.388  1744  2016 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:01:04.428  1448  1448 D RegisteredComponentCache: Collect Tech packages for Knox
,11-17 18:01:04.428  1649  1649 I ConfigService: onDestroy
,11-17 18:01:04.438  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.438  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.438  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:04.438  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.448  5362  5362 E Zygote  : MountEmulatedStorage()
,11-17 18:01:04.448  5362  5362 I libpersona: KNOX_SDCARD checking this for 10044
11-17 18:01:04.448  5362  5362 E Zygote  : v2
11-17 18:01:04.448  5362  5362 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:04.448  5362  5362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:04.448  5362  5362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:04.458  5362  5362 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,11-17 18:01:04.458  1017  1029 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=5362 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,11-17 18:01:04.468  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,11-17 18:01:04.488  5362  5362 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:04.488  5362  5362 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:04.508  1017  1487 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,11-17 18:01:04.508  1017  1487 D SecContentProvider2: mCursor = null
,11-17 18:01:04.518  1017  1056 I art     : Explicit concurrent mark sweep GC freed 27431(1974KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 26MB/40MB, paused 3.140ms total 185.002ms
,11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
11-17 18:01:04.528  5362  5362 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,11-17 18:01:04.538  1017  1056 D PackageManager: delete codoeFile: 
,11-17 18:01:04.548  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,11-17 18:01:04.548  1017  1056 I AASA_removePackage: UID=10174 Target=com.example.hello
,11-17 18:01:04.558  1017  1056 D PackageManager: result of delete: 1{244309339}
,11-17 18:01:04.558  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,11-17 18:01:04.568  1448  1448 D RegisteredServicesCache: empty dynamic service
,11-17 18:01:04.568  5267  5267 D AndroidRuntime: Shutting down VM
,11-17 18:01:04.588  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,11-17 18:01:04.588  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,11-17 18:01:04.588  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,11-17 18:01:04.588  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,11-17 18:01:04.588  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,11-17 18:01:04.588  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,11-17 18:01:04.598  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,11-17 18:01:04.598  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,11-17 18:01:04.598  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,11-17 18:01:04.598  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:01:04.608  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: uID is 10174
,11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
,11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:01:04.608  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
,11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: uID is 10174
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:01:04.608  1017  2603 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
,11-17 18:01:04.608  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:01:04.608  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=228_task.xml
,11-17 18:01:04.628  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
11-17 18:01:04.628  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
11-17 18:01:04.628  1017  1041 W TextServicesManagerService: no available spell checker services found
,11-17 18:01:04.638  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.638  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.638  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.648  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.698  1017  1438 I art     : Explicit concurrent mark sweep GC freed 10802(607KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 2.728ms total 166.563ms
,11-17 18:01:04.698  5362  5362 D NearbySource: Nearby Source Create!
,11-17 18:01:04.698  5362  5362 D NearbyContext: Nearby Context Create!
,11-17 18:01:04.718  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,11-17 18:01:04.718  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:04.718  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:04.718  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:04.728   255   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
11-17 18:01:04.728   255   521 W Vold    : Returning OperationFailed - no handler for errno 0
,11-17 18:01:04.728  5362  5362 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,11-17 18:01:04.728  5362  5362 D SLinkSource: Samsung link source created
,11-17 18:01:04.738  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,11-17 18:01:04.748  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.748  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.748  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.758  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:01:04.758  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:04.758  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:01:04.758  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.768  5362  5381 D ContactProvider: getAllContactInfoList Start
,11-17 18:01:04.768  1017  1438 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,11-17 18:01:04.778  1017  1706 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,11-17 18:01:04.778  5362  5362 I PackagesMonitor: PackagesMonitor onReceive :com.google.android.gms
,11-17 18:01:04.788  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.788  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:01:04.788  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:01:04.788  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:01:04.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:01:04.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:01:04.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:01:04.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:01:04.798  5362  5381 D ContactProvider: getAllContactInfoList End
11-17 18:01:04.798  5362  5381 I syncContacts: thread: 908, sync time = 49
,11-17 18:01:04.798  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:04.808  1017  1041 D UsbSettingsManager: clearDefaults: com.example.hello
11-17 18:01:04.808  1017  1041 I CrashAnrDetector: onPackageRemoved : com.example.hello
,11-17 18:01:04.808  5267  5267 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,11-17 18:01:04.808  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.808  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:04.808  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:04.808  1017  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.828  5383  5383 E Zygote  : MountEmulatedStorage()
11-17 18:01:04.828  5383  5383 E Zygote  : v2
11-17 18:01:04.828  5383  5383 I libpersona: KNOX_SDCARD checking this for 10069
11-17 18:01:04.828  5383  5383 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:04.828  5383  5383 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,11-17 18:01:04.828  5383  5383 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,11-17 18:01:04.828  5383  5383 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:01:04.828  1017  1438 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5383 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:01:04.828  1017  1438 I ActivityManager: Killing 4671:com.sec.pcw.device/1000 (adj 15): empty #31
,11-17 18:01:04.848  5383  5383 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:04.848  5383  5383 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:04.868  5383  5383 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,11-17 18:01:04.878  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.878  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.878  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:04.878  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:04.898  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4671/cgroup.procs: No such file or directory
11-17 18:01:04.898  5399  5399 E Zygote  : MountEmulatedStorage()
11-17 18:01:04.898  5399  5399 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:01:04.898  5399  5399 E Zygote  : v2
11-17 18:01:04.898  5399  5399 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:04.898  1017  1030 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,11-17 18:01:04.898  5399  5399 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
11-17 18:01:04.898  1017  1030 I ActivityManager: Killing 4701:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,11-17 18:01:04.898  5399  5399 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
11-17 18:01:04.898  5399  5399 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:01:04.918  5399  5399 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:04.918  5399  5399 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:04.948  5399  5399 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,11-17 18:01:04.948  5399  5399 E SQLiteLog: (28) failed to open "/data/data/com.sec.knox.foldercontainer/databases/KnoxFolderContainer.db" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:01:04.948  5399  5399 E SQLiteDatabase: Failed to open database '/data/data/com.sec.knox.foldercontainer/databases/KnoxFolderContainer.db'.
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at com.sec.knox.foldercontainer.db.KnoxSetupWizardDbHelper.open(KnoxSetupWizardDbHelper.java:161)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at com.sec.knox.foldercontainer.db.KnoxSetupWizardDbHelper.getInstance(KnoxSetupWizardDbHelper.java:173)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at com.sec.knox.foldercontainer.ShortcutReceiver.onReceive(ShortcutReceiver.java:48)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:01:04.948  5399  5399 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,11-17 18:01:04.958  5399  5399 D AndroidRuntime: Shutting down VM
,11-17 18:01:04.958  5399  5399 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:01:04.958  5399  5399 E AndroidRuntime: Process: com.sec.knox.foldercontainer, PID: 5399
11-17 18:01:04.958  5399  5399 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.sec.knox.foldercontainer.ShortcutReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at com.sec.knox.foldercontainer.db.KnoxSetupWizardDbHelper.open(KnoxSetupWizardDbHelper.java:161)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at com.sec.knox.foldercontainer.db.KnoxSetupWizardDbHelper.getInstance(KnoxSetupWizardDbHelper.java:173)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at com.sec.knox.foldercontainer.ShortcutReceiver.onReceive(ShortcutReceiver.java:48)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	at android.app.ActivityT,hread.handleReceiver(ActivityThread.java:3125)
11-17 18:01:04.958  5399  5399 E AndroidRuntime: 	... 9 more
11-17 18:01:04.958  1017  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.knox.foldercontainer
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop163.tmp: open failed: EROFS (Read-only file system)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:01:04.968  1017  5415 E DropBoxManagerService: 	... 5 more
11-17 18:01:04.968  5399  5399 I Process : Sending signal. PID: 5399 SIG: 9
11-17 18:01:04.988  1017  1280 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,11-17 18:01:04.998  1017  1280 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:04.998  1017  1280 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:04.998  1017  1280 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:05.008  1933  5416 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,11-17 18:01:05.008  1017  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,11-17 18:01:05.008  1017  1761 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:05.008  1017  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
11-17 18:01:05.008  1017  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:05.008  1017  1041 W libprocessgroup: failed to open /acct/uid_10047/pid_4701/cgroup.procs: No such file or directory
,11-17 18:01:05.018  1017  3527 I ActivityManager: Process com.sec.knox.foldercontainer (pid 5399)(adj 9) has died(105,1104)
,11-17 18:01:05.018  1933  5416 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,11-17 18:01:05.018  1017  3531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,11-17 18:01:05.018  1017  3531 W ActivityManager: userId = 0, bbcId = -10000
```
