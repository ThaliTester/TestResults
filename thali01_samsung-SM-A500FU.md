#### Test 50242285e132180_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/FileShare-Server( 3638): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
E/SMD     (  292): DCD OFF
D/SettingsProvider( 1014): name = mtp_open_session
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
I/DBG_DM  ( 3018): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
I/PCWCLIENTTRACE_PushUtil( 3244): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3244): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3244): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3244): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3244): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3244): ACTION_BOOTUP - Push type: [SPP, GCM]
--------- beginning of system
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3116): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/ServiceManager(  332): Waiting for service AtCmdFwd...
W/PCWCLIENTTRACE_PCWHandler( 3244): [ensureRegistration] - netwrok is not available. action ignored
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3116): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 3116): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3670): MountEmulatedStorage()
E/Zygote  ( 3670): v2
I/libpersona( 3670): KNOX_SDCARD checking this for 10031
I/libpersona( 3670): KNOX_SDCARD not a persona
I/SELinux ( 3670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3670 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 3670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3670): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 2924:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/art     (  321): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 672us total 22.162ms
D/TimaKeyStoreProvider( 3670): TimaSignature is unavailable
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.631ms total 18.291ms
D/ActivityThread( 3670): Added TimaKeyStore provider
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.375ms total 18.015ms
W/ResourcesManager( 3670): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1014): Killing 2940:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/libprocessgroup( 1014): failed to open /acct/uid_10159/pid_2924/cgroup.procs: No such file or directory
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1014): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3706): MountEmulatedStorage()
E/Zygote  ( 3706): v2
I/libpersona( 3706): KNOX_SDCARD checking this for 1000
I/libpersona( 3706): KNOX_SDCARD not a persona
I/SELinux ( 3706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3706 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3706): TimaSignature is unavailable
D/ActivityThread( 3706): Added TimaKeyStore provider
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2940/cgroup.procs: No such file or directory
D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/ContextImpl( 1934): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1014): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/SecUISvc( 1934): Thread created.
D/SecUISvc( 1934): Service started flags 0 startId 1
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/VlingoApplication( 3670): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
D/BluetoothAdapter( 3670): 338717491: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3670): 338717491: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3670): 338717491: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3670): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
I/ActivityManager( 1014): Killing 2908:com.sec.knox.bridge/1000 (adj 15): empty #31
I/Gmail   ( 3626): getAccountsCursor
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2908/cgroup.procs: No such file or directory
V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/VlingoApplication( 3670): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3670): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/DialogFlow( 3670): initQueue()
W/GAV2    ( 3626): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3746): MountEmulatedStorage()
E/Zygote  ( 3746): v2
I/libpersona( 3746): KNOX_SDCARD checking this for 10032
I/libpersona( 3746): KNOX_SDCARD not a persona
I/SELinux ( 3746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3746 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 3746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 2955:com.sec.usbsettings/1000 (adj 15): empty #31
E/SELinux ( 3746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3746): TimaSignature is unavailable
D/ActivityThread( 3746): Added TimaKeyStore provider
D/FileApkUtils( 1984): Spent 43ms computing apk sha1.
D/FileApkUtils( 1984): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 1984): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/DexOptUtils( 1984): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1984): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1984): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1984): Primary ABI of odexing process is armeabi-v7a
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2955/cgroup.procs: No such file or directory
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 3626): Observing account changes for notifications
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3706): Resource data:2131165186
W/ResourcesManager( 3706): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3706): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/art     ( 3670): Suspending all threads took: 5.052ms
I/dex2oat ( 3764): ----------------------------------------------------
I/dex2oat ( 3764): <SS>: S T A R T I N G . . .
I/dex2oat ( 3764): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3764): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3706): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/Gmail   ( 3626): Error finding the version of the Email provider.....
E/Gmail   ( 3626): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3626): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3626): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3626): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3626): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3626): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3626): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3626): We do not support migrating this version of the Email provider.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 3626): getAccountsCursor
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
I/GoogleHttpClient( 1644): GMS http client unavailable, use old client
I/AMMetaDataParserService( 3706): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
I/AMMetaDataParserService( 3706): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/DBG_DM  ( 3018): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
I/art     ( 1014): Explicit concurrent mark sweep GC freed 41686(2MB) AllocSpace objects, 4(184KB) LOS objects, 33% free, 26MB/39MB, paused 2.564ms total 178.503ms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3787): MountEmulatedStorage()
E/Zygote  ( 3787): v2
I/libpersona( 3787): KNOX_SDCARD checking this for 10104
I/libpersona( 3787): KNOX_SDCARD not a persona
I/SELinux ( 3787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3787 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 3787): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
D/GCM     ( 1984): COMPAT: Multi user not supported
D/TimaKeyStoreProvider( 3787): TimaSignature is unavailable
D/ActivityThread( 3787): Added TimaKeyStore provider
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1014): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3804 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 1555:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
E/Zygote  ( 3804): MountEmulatedStorage()
I/libpersona( 3804): KNOX_SDCARD checking this for 10033
E/Zygote  ( 3804): v2
I/libpersona( 3804): KNOX_SDCARD not a persona
I/SELinux ( 3804): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3804): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3804): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 3804): TimaSignature is unavailable
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3804): Added TimaKeyStore provider
D/GCM     ( 1644): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CheckinService( 1984): Checkin interval check for package: unspecified last checkin: 1449470940712 min interval config: 0 actual interval: 30164255
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/FactoryTestApp( 2545): [DummyFtClient$onDestroy](2545) Destroy DummyFtClient service
W/ResourcesManager( 3787): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131034113
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/FactoryTestApp( 2545): [Support$Values.getString](2545) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2545): [ModuleCommon$isConnectionModeNone](2545) mConnectionMode = gsm
I/FactoryTestApp( 2545): [ModuleCommon$isRunningFtClient](2545) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2545): [DummyFtClient$onDestroy](2545) kill process
I/Process ( 2545): Sending signal. PID: 2545 SIG: 9
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCoreUlr( 1984): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCoreUlr( 1791): DispatchingService.onCreate()
D/SystemUpdateService( 1984): onCreate
I/CheckinService( 1984): Disabling old GoogleServicesFramework version
W/ResourcesManager( 3706): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3706): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 3626): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1d5c9738 that was originally bound here
E/ActivityThread( 3626): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1d5c9738 that was originally bound here
E/ActivityThread( 3626): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3626): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3626): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3626): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3626): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3626): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3626): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3626): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3626): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3626): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3626): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3626): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3626): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3626): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3626): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1014): Unbind failed: could not find connection for android.os.BinderProxy@1b3c523f
I/CheckinService( 1984): Checking schedule, now: 1449501105156 next: 1450010203660
I/CheckinService( 1984): active receiver: disabled
D/SystemUpdateService( 1984): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_1555/cgroup.procs: No such file or directory
I/ActivityManager( 1014): Process com.sec.factory (pid 2545)(adj 0) has died(225,1055)
V/AuthZen ( 1984): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1984): Handling event: android.intent.action.BOOT_COMPLETED
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3706): took 2.263282ms for 0*0 texture 0
I/GFX generate_partition_tables( 3706): took 6.033750ms for 0*0 texture 0
I/GFX raster( 3706): took 9.546354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84b0520 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 3626): (283) recovered 28 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ResourcesManager( 3804): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3804): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3804): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3706): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.824010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84b85b0 counterpartCT=4 counterpartW=96 counterparth=96
I/GCoreUlr( 1791): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 3706): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3706): took 2.256458ms for 0*0 texture 0
D/AndroidRuntime( 3834): 
D/AndroidRuntime( 3834): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3834): CheckJNI is OFF
D/AndroidRuntime( 3834): readGMSProperty: start
D/AndroidRuntime( 3834): readGMSProperty: already setted!!
D/AndroidRuntime( 3834): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3834): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3834): readGMSProperty: end
D/AndroidRuntime( 3834): addProductProperty: start
W/art     ( 3160): Suspending all threads took: 5.933ms
I/GFX generate_partition_tables( 3706): took 8.952185ms for 0*0 texture 0
I/GFX raster( 3706): took 12.199373ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4db8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b4f20 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3706): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
I/DBG_DM  ( 3018): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
E/AffinityControl( 3834): AffinityControl: registerfunction enter
W/ResourcesManager( 3804): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3804): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3804): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 3834): Calling main entry com.android.commands.am.Am
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.945105ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b9788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b98f0 counterpartCT=4 counterpartW=96 counterparth=96
V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AMMetaDataParserService( 3706): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 3804): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3804): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3804): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1014): mDVFSHelper.acquire()
I/SurfaceFlinger(  256): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  256): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1014): Set to : 0
I/dex2oat ( 3764): dex2oat took 1.426s (threads: 4)
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.825521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b6288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b63f0 counterpartCT=4 counterpartW=96 counterparth=96
E/File    ( 3626): fail readDirectory() errno=2
D/DexOptUtils( 1984): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex
D/DexOptUtils( 1984): Set odex to world readable.
D/DexOptUtils( 1984): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.odex
I/Gmail   ( 3626): notifyAccountChanged
D/FileApkUtils( 1984): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 1469
D/Launcher.HomeView( 1469): onPause
D/Launcher( 1469): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 3834): Shutting down VM
I/Gmail   ( 3626): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/BaseAppContext( 1984): Using Auth Proxy for data requests.
I/AMMetaDataParserService( 3706): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/Gmail   ( 3626): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/Zygote  ( 3848): MountEmulatedStorage()
E/Zygote  ( 3848): v2
I/libpersona( 3848): KNOX_SDCARD checking this for 10174
I/libpersona( 3848): KNOX_SDCARD not a persona
I/SELinux ( 3848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3848): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3848 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, iello
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 3848): TimaSignature is unavailable
W/ResourcesManager( 3746): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ActivityThread( 3848): Added TimaKeyStore provider
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/Gmail   ( 3626): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/GFX raster( 3706): took 0.625000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b5590 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b56f8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/Gmail   ( 3626): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.685000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b4ad0 counterpartCT=4 counterpartW=96 counterparth=96
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
V/ActivityThread( 1469): updateVisibility : ActivityRecord{332d667 token=android.os.BinderProxy@be2872e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1469): onStop
V/ActivityThread( 1469): updateVisibility : ActivityRecord{332d667 token=android.os.BinderProxy@be2872e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.520260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b93e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b3340 counterpartCT=4 counterpartW=96 counterparth=96
D/PersonaManager( 1014): isKioskContainerExistOnDevice
I/AMMetaDataParserService( 3706): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
W/ResourcesManager( 3746): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131034113
I/AMMetaDataParserService( 3706): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.841458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84b6210 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/art     ( 3834): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/AMMetaDataParserService( 3706): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.867500ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
,D/Launcher( 1469): onTrimMemory. Level: 20
,D/GmsModuleFndr( 1984): Beginning GMS chimera module scan
,I/AMMetaDataParserService( 3706): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1014): [SO] activate (ident=0xb8b49bf8, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/GmsModuleFndr( 1984): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1984): Beginning module configuration check
I/SystemUpdateService( 1984): cancelUpdate (empty URL)
I/SystemUpdateService( 1984): active receiver: disabled
D/ChimeraCfgMgr( 1984): Module APKs unchanged, check complete
,D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 3033:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/SensorService( 1014): [SO] changed settle time [1]
D/SensorService( 1014): [SO] setDelay [66000000]
D/SensorService( 1014): [SO] activate (ident=0xb8a1d5d0, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.606302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4db8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
,D/ChimeraCfgMgr( 1984): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/AMMetaDataParserService( 3706): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 3848): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/AuthZen ( 1984): Fetching signing key...
,I/LibraryLoader( 3848): Time to load native libraries: 2 ms (timestamps 213-215)
I/LibraryLoader( 3848): Expected native library version number "",actual native library version number ""
I/GFX raster( 3706): took 0.649272ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b9788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_3033/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3706): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1014): [SO] currT = 40250105922, prevT = 39930107067, diff = 319998855, [0.172 0.096 10.132]
D/SensorService( 1014): [SO] 0.172 0.096 10.132
D/SensorService( 1014): [SO] [100 -> 255]
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.834583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b6288 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
,V/WebViewChromiumFactoryProvider( 3848): Binding Chromium to main looper Looper (main, tid 1) {163e2b43}
,I/LibraryLoader( 3848): Expected native library version number "",actual native library version number ""
I/AuthZen ( 1984): Signing key fetched successfully!
I/chromium( 3848): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/AMMetaDataParserService( 3706): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/BaseAppContext( 1984): Using Auth Proxy for data requests.
,D/a       ( 1984): Opening database auth.proximity.permit_store...
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/AuthZenTransactionCache( 1984): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1984): Clearing transaction cache
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BrowserStartupController( 3848): Initializing chromium process, singleProcess=true
,W/art     ( 3848): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3848): ApplicationContext is null in ApplicationStatus
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.628021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b5590 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
W/chromium( 3848): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,W/chromium( 3848): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 3848): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 3848): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/Adreno-EGL( 3848): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3848): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3848): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3848): Local Branch: 
I/Adreno-EGL( 3848): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3848): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3848):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ChimeraCfgMgr( 1984): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GFX raster( 3706): took 0.694740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1984): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 1984): [KidAccountFixer] No network connection
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  256): id=6 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=6 Removed Mauncher (-2/8)
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.525208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b93e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel   ( 3787): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3787): MmsConfig.loadMmsSettings
I/Babel   ( 3787): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 3787): MmsConfig.loadFromDatabase
,I/AMMetaDataParserService( 3706): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/SystemUpdateService( 1984): onDestroy
,W/Auth    ( 1644): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3706): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3706): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131034112
,I/AMMetaDataParserService( 3706): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 1.179115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b9788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3706): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
D/BluetoothAdapter( 3848): 898513055: getState() :  mService = null. Returning STATE_OFF
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
W/GCoreFlp( 1791): No location to return for getLastLocation()
W/FusedLocationProvider( 1984): location=null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Process ( 3804): Sending signal. PID: 3804 SIG: 9
,I/art     ( 1984): Explicit concurrent mark sweep GC freed 28772(2MB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 10MB/17MB, paused 1.250ms total 60.453ms
,V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 3787): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3787): MmsConfig.loadFromResources
,V/GmsCoreStatsServiceLauncher( 1984): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/Babel   ( 3787): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3787): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  292): DCD OFF
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.601198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b9788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b5f08 counterpartCT=4 counterpartW=96 counterparth=96
,W/GCoreFlp( 1791): No location to return for getLastLocation()
,W/FusedLocationProvider( 1984): location=null
,I/AMMetaDataParserService( 3706): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/art     ( 3787): Suspending all threads took: 7.346ms
,I/DBG_DM  ( 3018): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/PersistentNotificationBroadcastReceiver( 1644): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager( 1014): Process com.sec.android.app.sns3 (pid 3804)(adj 0) has died(208,1071)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3920): MountEmulatedStorage(),
E/Zygote  ( 3920): v2
,I/libpersona( 3920): KNOX_SDCARD checking this for 10034
I/libpersona( 3920): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3920 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,I/SELinux ( 3920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3920): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1644): Explicit concurrent mark sweep GC freed 8284(465KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 4.604ms total 500.370ms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,W/chromium( 3848): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.653698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8498130 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8497de0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3930): MountEmulatedStorage()
,E/Zygote  ( 3930): v2
I/libpersona( 3930): KNOX_SDCARD checking this for 10028
I/SELinux ( 3930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3930): KNOX_SDCARD not a persona
,I/SELinux ( 3930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3930): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3930 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3920): TimaSignature is unavailable
,D/ActivityThread( 3920): Added TimaKeyStore provider
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3706): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,D/TimaKeyStoreProvider( 3930): TimaSignature is unavailable
,D/ActivityThread( 3930): Added TimaKeyStore provider
,W/Settings( 3787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/art     ( 3848): Attempt to remove local handle scope entry from IRT, ignoring
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.645365ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b5f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b0410 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,W/AwContents( 3848): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 3848): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3848): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 3848): CordovaWebView is running on device made by: samsung
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131034113
I/AMMetaDataParserService( 3706): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.826562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb81f4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb847b8c0 counterpartCT=4 counterpartW=96 counterparth=96
W/art     ( 3848): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3848): Attempt to remove local handle scope entry from IRT, ignoring
I/AMMetaDataParserService( 3706): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.819219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb81f4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84b4c20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.624062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8497de0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b0410 counterpartCT=4 counterpartW=96 counterparth=96
,D/OpenGLRenderer( 3848): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
I/Babel_StickerModule( 3787): App launched.
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PhoneWindow( 3848): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3848): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/AMMetaDataParserService( 3706): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/InputDispatcher( 1014): Focus entered window: 3848
,E/Zygote  ( 3960): MountEmulatedStorage()
E/Zygote  ( 3960): v2
I/libpersona( 3960): KNOX_SDCARD checking this for 10035
I/libpersona( 3960): KNOX_SDCARD not a persona
,I/SELinux ( 3960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SRIB_DCS( 3848): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3848): Initialized EGL, version 1.4
I/SELinux ( 3960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3960 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3960): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Killing 2992:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 3848): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3848): Enabling debug mode 0
,D/TimaKeyStoreProvider( 3960): TimaSignature is unavailable
,D/ActivityThread( 3960): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 3134:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/System.out( 3670): INFO:Resource not found:/Common.properties Using default values
,V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3134/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_2992/cgroup.procs: No such file or directory
,I/Gmail   ( 3626): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/Babel   ( 3787): babel boot account: SMS
,V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1177 (0x0)
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1014): Displayed Component not be shown by security: +1s316ms
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{a3152d3 u0 com.example.hello/.MainActivity t2} time:41130
,D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Gmail   ( 3626): getAccountsCursor
,I/Timeline( 3848): Timeline: Activity_idle id: android.os.BinderProxy@13e066ee time:41137
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SamsungIME( 1759): getCurrentCandidateView
,W/Babel   ( 3787): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 3787): java.lang.Exception
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3787): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3787): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3787): 	at ckh.a(SourceFile:67)
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3787): 	at bhn.a(SourceFile:301)
W/Babel   ( 3787): 	at bhn.a(SourceFile:137)
W/Babel   ( 3787): 	at bhn.a(SourceFile:126)
W/Babel   ( 3787): 	at bhn.a(SourceFile:159)
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3787): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3787): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3787): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3787): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3787): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3787): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/Babel   ( 3787): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3787): java.lang.Exception
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3787): 	at aes.a(SourceFile:145)
W/Babel   ( 3787): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3787): 	at ckh.a(SourceFile:67)
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3787): 	at bhn.a(SourceFile:301)
W/Babel   ( 3787): 	at bhn.a(SourceFile:137)
W/Babel   ( 3787): 	at bhn.a(SourceFile:126)
W/Babel   ( 3787): 	at bhn.a(SourceFile:159)
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3787): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3787): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3787): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3787): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3787): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3787): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SPPClientService( 3960): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 3960): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 3960): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/SecDataIO(  255): Write to block
,D/SamsungIME( 1759): Dismiss ExpandCandiate
,I/SurfaceFlinger(  256): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  256): id=10 Removed iello (-2/8)
,D/SSRM:n  ( 1014): SIOP:: AP = 360
,D/SPPClientService( 3960): PushLog.txt file is not deleted.
,D/SPPClientService( 3960): PushLog.txt file is not deleted.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
D/SPPClientService( 3960): ============PushLog. stop!,
D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 3787): babel boot account: thalitester@gmail.com
,W/ContextImpl( 2527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 3018): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3018): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3018): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,W/Babel   ( 3787): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3787): java.lang.Exception
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3787): 	at aes.a(SourceFile:145)
W/Babel   ( 3787): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3787): 	at ckh.a(SourceFile:67)
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3787): 	at bhn.a(SourceFile:301)
W/Babel   ( 3787): 	at bhn.a(SourceFile:137)
W/Babel   ( 3787): 	at bhn.a(SourceFile:126)
W/Babel   ( 3787): 	at bhn.a(SourceFile:159)
W/Babel   ( 3787): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3787): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3787): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3787): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3787): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3787): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3787): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/DBG_DM  ( 3018): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@11
,D/Finsky  ( 3930): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,E/Zygote  ( 3996): MountEmulatedStorage(),
E/Zygote  ( 3996): v2
,I/libpersona( 3996): KNOX_SDCARD checking this for 10041
I/libpersona( 3996): KNOX_SDCARD not a persona
,I/SELinux ( 3996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3996): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=3996 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 3075:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3996): TimaSignature is unavailable
,D/ActivityThread( 3996): Added TimaKeyStore provider
,W/BindingManager( 3848): Cannot call determinedVisibility() - never saw a connection for the pid: 3848
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.679583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b9788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b4c20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/chromium( 3848): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1791): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.990313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb847b8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b0410 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 36219(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 26MB/39MB, paused 2.633ms total 177.404ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3706): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Process ( 2527): Sending signal. PID: 2527 SIG: 9
D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.714479ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b5f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b4c20 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4017): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4017 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4017): v2
,I/libpersona( 4017): KNOX_SDCARD checking this for 1000
I/libpersona( 4017): KNOX_SDCARD not a persona
,I/SELinux ( 4017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/SELinux ( 4017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4017): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3018): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/DBG_DM  ( 3018): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3018): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/JsMessageQueue( 3848): Set native->JS mode to OnlineEventsBridgeMode
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.681406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b0410 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b4c20 counterpartCT=4 counterpartW=96 counterparth=96
,E/DBG_DM  ( 3018): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,E/AndroidProtocolHandler( 3848): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_DM  ( 3018): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/ActivityManager( 1014): Process com.sec.android.app.sysscope (pid 2527)(adj 0) has died(162,1099)
D/TimaKeyStoreProvider( 4017): TimaSignature is unavailable
,D/ActivityThread( 4017): Added TimaKeyStore provider
,I/GCoreUlr( 1791): Unbound from all location providers
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  286): getCameraInfo: X
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  286): getCameraInfo: X
,E/libprocessgroup( 1014): failed to kill 1 processes for processgroup 3075
,W/VideoCapabilities( 3787): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3787): Unsupported mime audio/evrc
,W/AudioCapabilities( 3787): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3787): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3787): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3787): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3787): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3787): Unsupported mime audio/qcelp
,I/SamsungIME( 1759): getDebugLevel  : 0x4f4c
,D/GCMRegistrar( 3254): resetting backoff for com.dropbox.android
V/GCMRegistrar( 3254): Registering app com.dropbox.android of senders 735665981150
,W/AudioCapabilities( 3787): Unsupported mime audio/evrc
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1791): DispatchingService.onDestroy()
,I/GCoreUlr( 1791): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1791): Unbound from all location providers
,W/VideoCapabilities( 3787): Unsupported mime video/wvc1
,W/VideoCapabilities( 3787): Unsupported mime video/x-ms-wmv
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1644): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,I/SA      ( 3996): [SSP] onCreated
,W/art     ( 3670): Suspending all threads took: 6.583ms
W/VideoCapabilities( 3787): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3787): Unsupported mime video/wvc1
,W/VideoCapabilities( 3787): Unsupported mime video/x-ms-wmv
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.541458ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b93e0 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3787): Unsupported mime video/x-ms-wmv7
,I/AMMetaDataParserService( 3706): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/VideoCapabilities( 3787): Unsupported mime video/x-ms-wmv8
,D/jxcore_app_log( 3848): JniHelper::setJavaVM(0xb80dc450), pthread_self() = -1201672632
D/JX-Cordova( 3848): jxcore cordova android initializing
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3787): Unsupported mime video/mp43,
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/GCM     ( 1644): GCM config loaded,
,E/Zygote  ( 4049): MountEmulatedStorage(),
E/Zygote  ( 4049): v2
,I/libpersona( 4049): KNOX_SDCARD checking this for 1000
I/libpersona( 4049): KNOX_SDCARD not a persona
,I/SELinux ( 4049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SA      ( 3996): [TPM] There is no property file,
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
W/ResourcesManager( 3706): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.MessageListXL,
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131165203
,I/SA      ( 3996): [SCU] isHaveSA() - false
I/SA      ( 3996): [TPM] getModelProperty : null
,I/SA      ( 3996): [TPM] getCSCProperty : null
,W/ResourcesManager( 3706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3787): Unsupported mime video/sorenson
,I/art     (  321): Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 665us total 36.625ms
W/ResourcesManager( 3706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4049): TimaSignature is unavailable
,W/jxcore-log( 3848): Initializing JXcore engine
W/jxcore-log( 3848): JXcore engine is ready
D/ActivityThread( 4049): Added TimaKeyStore provider
,W/ResourcesManager( 3706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/jxcore-log( 3848): Starting JXcore engine
,I/AMMetaDataParserService( 3706): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 17.186ms
,W/VideoCapabilities( 3787): Unsupported mime video/mp4v-esdp
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 697us total 19.708ms
,I/GFX construct_block_size_descriptor_2d second part( 3706): took 3.060157ms for 0*0 texture 0
,I/SA      ( 3996): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 3996): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 3996): [DM] TFT FEATURE: false
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/SamsungIME( 1759): getDebugLevel  : 0x4f4c
,I/SA      ( 3996): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 3996): [DM] init START
,I/ActivityManager( 1014): Killing 3199:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/SA      ( 3996): [DM] This device is not a Vodafone
,I/GFX generate_partition_tables( 3706): took 10.282083ms for 0*0 texture 0
,I/GFX raster( 3706): took 14.213282ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb86620f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8662198 counterpartCT=4 counterpartW=96 counterparth=96
,I/VideoCapabilities( 3787): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ResourceType( 3996): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourceType( 3996): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
I/AMMetaDataParserService( 3706): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/ResourceType( 3996): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ResourceType( 3996): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 3996): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,I/ActivityManager( 1014): Killing 3217:com.fmm.dm/1000 (adj 15): empty #31
,I/SamsungIME( 1759): KeybaordView init() : load resources
,W/ResourceType( 3996): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 3996): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,E/audit   ( 1904): type=1400 msg=audit(1449501108.220:203): avc:  denied  { ioctl } for  pid=3848 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/ResourceType( 3996): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,E/audit   ( 1904):  SEPF_SM-A500FU_5.0.2-1_0038
,E/audit   ( 1904): type=1300 msg=audit(1449501108.220:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bed29d58 items=0 ppid=321 ppcomm=main pid=3848 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1904): type=1320 msg=audit(1449501108.220:203): 
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourceType( 3996): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 3996): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 3996): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
I/GFX raster( 3706): took 0.801875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8810ed8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8810fa0 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourceType( 3996): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 3996): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 3996): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/KnoxSetupWizardDbHelper( 4049): dbMigrationFlag : false
,D/ShortcutReceiver( 4049):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/SA      ( 3996): [SCU] isHaveSA() - false
I/AMMetaDataParserService( 3706): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/SA      ( 3996): support phone number id : false
I/SA      ( 3996): [DM] Supports Ref Jpn : true
,I/SA      ( 3996): [DM] init END
,I/SA      ( 3996): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 3996): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1014): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,D/KnoxShortcutUtil( 4049): getIsShortcutMigrationFor_2_3_0_Done true
,I/SA      ( 3996): [OR] onReceive END
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ShortcutReceiver( 4049):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4049):  shortcut migration not required 
,I/GFX raster( 3706): took 0.790156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8810ed8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88125d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 3930): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1759): getCurrentKeyboard
I/SamsungIME( 1759): getTextKeyboard
,I/AMMetaDataParserService( 3706): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575,
I/libpersona( 4073): KNOX_SDCARD checking this for 10042
E/Zygote  ( 4073): MountEmulatedStorage()
I/libpersona( 4073): KNOX_SDCARD not a persona
,E/Zygote  ( 4073): v2
I/ActivityManager( 1014): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4073 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/SELinux ( 4073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4073): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SamsungIME( 1759): [SwiftkeyWrapper] currentLangauge : 1701729619
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3706): took 0.954166ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8810ed8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8813bb8 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 3996): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/libpersona( 4089): KNOX_SDCARD checking this for 1000,
E/Zygote  ( 4089): MountEmulatedStorage()
I/libpersona( 4089): KNOX_SDCARD not a persona
E/Zygote  ( 4089): v2
I/SA      ( 3996): [ODM] queryOpenData(key= GEO_IP ),
I/SELinux ( 4089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 4089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Killing 3181:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4073): TimaSignature is unavailable,
,D/ActivityThread( 4073): Added TimaKeyStore provider
,E/SELinux ( 4089): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/SA      ( 3996): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 3996): [LBE] REF_JPN : true,
I/SA      ( 3996): [BDC] create
,I/AMMetaDataParserService( 3706): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/ResourcesManager( 4073): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4089): TimaSignature is unavailable
,D/ActivityThread( 4089): Added TimaKeyStore provider
,W/Settings( 3930): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3930): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/jxcore-log( 3848): Platform android
W/jxcore-log( 3848): 
,W/jxcore-log( 3848): Process ARCH arm
W/jxcore-log( 3848): 
,I/System.out( 1644): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1644): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1644): (HTTPLog)-Static: isShipBuild true
I/System.out( 1644): (HTTPLog)-Thread-183-625216410: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1644): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10012
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3217/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_3199/cgroup.procs: No such file or directory
,E/KnoxSetupWizardClient( 4089): isShipMode : 1
I/KnoxSetupWizardClient( 4089): onReceive : android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1014): failed to open /acct/uid_10086/pid_3181/cgroup.procs: No such file or directory
,I/jxcore-log( 3848): JXcore Cordova bridge is ready!
I/jxcore-log( 3848): 
,W/jxcore-log( 3848): JXcore engine is started
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4114): MountEmulatedStorage()
,E/Zygote  ( 4114): v2
I/libpersona( 4114): KNOX_SDCARD checking this for 10107
I/libpersona( 4114): KNOX_SDCARD not a persona
I/SELinux ( 4114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 4114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4114 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4114): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 3254:com.dropbox.android/u0a92 (adj 15): empty #31
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.713490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8815368 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8815410 counterpartCT=4 counterpartW=96 counterparth=96
,E/jxcore-log( 3848): >> samsung-SM-A500FU
E/jxcore-log( 3848): 
,I/jxcore-log( 3848): Total memory 1983791104
I/jxcore-log( 3848): 
,I/jxcore-log( 3848): Free memory 135577600
I/jxcore-log( 3848): 
I/AMMetaDataParserService( 3706): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
I/jxcore-log( 3848): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3848): 
I/jxcore-log( 3848): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3848): 
,I/CalendarProvider2( 4073): CalendarProvider2.onCreate() called
,D/TimaKeyStoreProvider( 4114): TimaSignature is unavailable
,I/jxcore-log( 3848): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3848): 
,D/ActivityThread( 4114): Added TimaKeyStore provider
,I/jxcore-log( 3848): Size 720 1280
I/jxcore-log( 3848): 
,I/SA      ( 3996): [DBMV2] getEmailID
,I/jxcore-log( 3848): Screen Brightness 5
I/jxcore-log( 3848): 
,E/jxcore-log( 3848): Dummy Error Log.
E/jxcore-log( 3848): 
,I/SA      ( 3996): [DBMV2] getDataV02ForItems
I/SA      ( 3996): [SSP] query invoked
,I/SA      ( 3996): [SCU] get signed id from samsung account2.0 DB.
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.625000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8815368 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661690 counterpartCT=4 counterpartW=96 counterparth=96
,W/System.err( 4089): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4089): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4089): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4089): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4089): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
,W/System.err( 4089): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4089): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/SA      ( 3996): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 3996): [BDC] destroy
,I/ActivityManager( 1014): Killing 3274:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/AMMetaDataParserService( 3706): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/ActivityManager( 1014): Killing 3293:com.fmm.ds/1000 (adj 15): empty #31
,E/SQLiteLog( 3787): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,D/Volley  ( 3930): [603] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3930): [596] DiskBasedCache.clear: Cache cleared.
,E/SQLiteLog( 3787): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131099648
,D/Ads     ( 3930): Skipping gmscore version check
,W/ResourcesManager( 3706): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3706): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 1.438438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb89bd618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89bd8f0 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3787): (284) automatic index on conversation_participants_view(conversation_id)
,W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3254/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10060/pid_3274/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3293/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/Finsky  ( 3930): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3930): [1] Libraries$2.run: Finished loading 1 libraries.
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3706): took 2.259844ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3706): took 8.841927ms for 0*0 texture 0
,I/GFX raster( 3706): took 12.104063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb84b7f18 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3787): (284) automatic index on conversation_participants_view(conversation_id)
,D/Finsky  ( 3930): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
I/AMMetaDataParserService( 3706): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/SQLiteLog( 3787): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.614063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b7f88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb81f4b28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.645885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb847b8c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84b7f18 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3706): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/Finsky  ( 3930): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.660520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84971d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81f4b28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.981354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b8040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8812450 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131099648
,I/AMMetaDataParserService( 3706): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.787710ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb81f4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8662500 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.715781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b7f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8475c80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.635937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb84ba050 counterpartCT=4 counterpartW=96 counterparth=96
D/StrictMode( 4114): StrictMode policy violation; ~duration=317 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4114): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4114): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4114): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4114): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4114): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4114): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4114): StrictMode policy violation; ~duration=302 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4114): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4114): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4114): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4114): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4114): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.,java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4114): StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4114): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4114): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4114): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4114): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4114): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4114): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4114): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4114): StrictMode policy violation; ~duration=225 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4114): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4114): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4114): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4114): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4114): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4114): StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4114): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4114): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4114): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4114): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4114): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4114): StrictMode policy violation; ~duration=221 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4114): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4114): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4114): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4114): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4114): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4114): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4114): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4114): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4114): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4114): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4114): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4114): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4114): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/StrictMode( 4114): StrictMode policy violation; ~duration=217 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4114): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4114): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4114): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4114): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4114): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4114): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4114): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4114): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4114): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4114): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4114): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4114): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4114): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4114): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4114): StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4114): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4114): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4114): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4114): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4114): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4114): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4114): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4114): StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4114): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4114): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4114): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4114): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4114): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4114): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4114): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4114): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4114): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4114): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4114): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4114): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4114): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4114): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/AMMetaDataParserService( 3706): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/jxcore-log( 3848): getBuffer is called!!!!
I/jxcore-log( 3848): 
E/Zygote  ( 4146): MountEmulatedStorage()
E/Zygote  ( 4146): v2
I/libpersona( 4146): KNOX_SDCARD checking this for 1000
I/libpersona( 4146): KNOX_SDCARD not a persona
I/SELinux ( 4146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4146 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 3320:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.657917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb847b8c0 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1014): Killing 3341:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
D/TimaKeyStoreProvider( 4146): TimaSignature is unavailable
D/ActivityThread( 4146): Added TimaKeyStore provider
I/AMMetaDataParserService( 3706): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.680155ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661b18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/StatusChecker( 4146): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4146): onReceive : net.mt.init : DONE
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,I/GFX raster( 3706): took 0.724844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b8040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb845bfb8 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3706): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Zygote  ( 4164): MountEmulatedStorage()
E/Zygote  ( 4164): v2
I/libpersona( 4164): KNOX_SDCARD checking this for 10116
I/libpersona( 4164): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,I/SELinux ( 4164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131099648
,I/SELinux ( 4164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4164): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AlarmManager( 1014): waitForAlarm result :4
,I/ActivityManager( 1014): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4164 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3370:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3706): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.707344ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb81f4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b9f38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4164): TimaSignature is unavailable
,D/ActivityThread( 4164): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.688958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b7f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8662500 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.650261ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb847b8c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/PageBuddyNotiSvc( 4164): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/iu.UploadsManager( 1984): End new media; added: 0, uploading: 0, time: 53 ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_3320/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3341/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3370/cgroup.procs: No such file or directory
,W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/AMMetaDataParserService( 3706): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/PageBuddyNotiSvc( 4164): onCreate mCpBitFlag=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3706): took 0.651667ms for 96*96 texture 0
I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4182 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84aab38 counterpartCT=4 counterpartW=96 counterparth=96
,W/com.google.a.a.b.d.a( 4114): Application name is not set. Call Builder#setApplicationName.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,E/Zygote  ( 4182): MountEmulatedStorage(),
E/Zygote  ( 4182): v2
I/libpersona( 4182): KNOX_SDCARD checking this for 10125,
I/libpersona( 4182): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3706): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SELinux ( 4182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3706): took 0.626979ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8475c80 counterpartCT=4 counterpartW=96 counterparth=96
,E/SELinux ( 4182): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GAV2    ( 3626): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4182): TimaSignature is unavailable
,D/ActivityThread( 4182): Added TimaKeyStore provider
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourcesManager( 4182): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4182): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4182): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/GFX raster( 3706): took 0.943176ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b8040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b0410 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1759): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3706): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131099648
I/AMMetaDataParserService( 3706): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.681458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb81f4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8662500 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.645625ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b7f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb84aab38 counterpartCT=4 counterpartW=96 counterparth=96
,D/QuickConnect( 4182): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3706): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/QuickConnect( 4182): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1014): name = scon_is_running
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 10125
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.650886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8661b18 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/AMMetaDataParserService( 3706): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/QuickConnect( 4182): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/QuickConnect( 4182): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.664323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84aab38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
,E/Zygote  ( 4198): MountEmulatedStorage()
E/Zygote  ( 4198): v2
,I/libpersona( 4198): KNOX_SDCARD checking this for 10131
I/libpersona( 4198): KNOX_SDCARD not a persona
,I/SELinux ( 4198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4198 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 4198): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.655625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb845c600 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4198): TimaSignature is unavailable
,D/ActivityThread( 4198): Added TimaKeyStore provider
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.735625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b8040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661b18 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4198): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4198): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4198): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4198): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3706): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131099648
,I/AMMetaDataParserService( 3706): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.682865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb81f4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb847b8c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.658958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b7f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8661b18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.780052ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb80e2ad0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SBrowserFeatureFlag( 4198): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3706): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.662500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8662500 counterpartCT=4 counterpartW=96 counterparth=96
,D/ManifestProvider( 4198): onCreate()
,I/AMMetaDataParserService( 3706): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.631822ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b9f38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/NetworkSettingsReceiver( 4198): onReceive: android.intent.action.BOOT_COMPLETED
,E/SBrowserFeatureFlag( 4198): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@1bc9f44a
,D/SBrowserFeatureFlag( 4198): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4198): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.770365ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b8040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8661b18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ConversationList,
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3706): Resource data:2131099648
,I/AMMetaDataParserService( 3706): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3706): took 0.675209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb81f4b28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84aab38 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4217): MountEmulatedStorage()
,E/Zygote  ( 4217): v2
I/libpersona( 4217): KNOX_SDCARD checking this for 10135
I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
I/libpersona( 4217): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4217 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 4217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Killing 3100:com.sec.android.fotaclient/u0a9 (adj 15): empty #31,
,I/SELinux ( 4217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.635781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b7f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8662500 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4217): TimaSignature is unavailable
,D/ActivityThread( 4217): Added TimaKeyStore provider
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.778437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b4c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb845c600 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourcesManager( 4217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.788281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84aab38 counterpartCT=4 counterpartW=96 counterparth=96
,E/SMD     (  292): DCD OFF,
,I/AMMetaDataParserService( 3706): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.658229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84ba050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb847b8c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.739792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb84b8040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84aab38 counterpartCT=4 counterpartW=96 counterparth=96
,D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3706): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3706): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131165197
,W/ResourcesManager( 3706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3706): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3706): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,I/AMMetaDataParserService( 3706): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3706): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,E/Zygote  ( 4239): MountEmulatedStorage()
,E/Zygote  ( 4239): v2
I/libpersona( 4239): KNOX_SDCARD checking this for 10139
I/libpersona( 4239): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3706): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/SELinux ( 4239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4239 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/SELinux ( 4239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/TimaKeyStoreProvider( 4239): TimaSignature is unavailable
,D/ActivityThread( 4239): Added TimaKeyStore provider
,W/ResourcesManager( 4239): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4239): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4239): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4239): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4239): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4073): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131165197
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 3706): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,W/libprocessgroup( 1014): failed to open /acct/uid_10009/pid_3100/cgroup.procs: No such file or directory
,I/ActivityManager( 1014): Killing 3402:com.wssnps/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3706): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/ActivityManager( 1014): Killing 3422:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 3469:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/AMMetaDataParserService( 3706): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3706): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/Zygote  ( 4258): MountEmulatedStorage()
,E/Zygote  ( 4258): v2
I/libpersona( 4258): KNOX_SDCARD checking this for 10145
I/libpersona( 4258): KNOX_SDCARD not a persona
,I/SELinux ( 4258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4258 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131165197
,I/AMMetaDataParserService( 3706): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4258): TimaSignature is unavailable
,D/ActivityThread( 4258): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3706): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3706): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ResourcesManager( 4258): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4258): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4258): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4258): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3706): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3706): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/libprocessgroup( 1014): failed to open /acct/uid_10094/pid_3469/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3402/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10014/pid_3422/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartM,msSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131099648
,W/ResourcesManager( 3706): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3706): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
,I/AMMetaDataParserService( 3706): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3706): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:assistant
I/AMMetaDataParserService( 3706): Resource data:2131165220
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,W/ResourcesManager( 3706): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3706): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3706): getResourceTypeNamexml
E/Zygote  ( 4281): MountEmulatedStorage()
E/Zygote  ( 4281): v2
I/libpersona( 4281): KNOX_SDCARD checking this for 10072
I/libpersona( 4281): KNOX_SDCARD not a persona
I/SELinux ( 4281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4281): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4281 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/TimaKeyStoreProvider( 4281): TimaSignature is unavailable
,D/ActivityThread( 4281): Added TimaKeyStore provider
I/art     (  321): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 878us total 24.971ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 17.715ms
,D/BadgeProvider( 4281): onCreate
,D/BadgeProvider( 4281): DatabaseHelper
,E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3706): took 0.695417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8bb4908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bb46d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.813ms
,I/AMMetaDataParserService( 3706): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,D/BadgeProvider( 4281): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 3439:com.samsung.android.sm/1000 (adj 15): empty #31
I/ActivityManager( 1014): Killing 3535:com.android.managedprovisioning/u0a22 (adj 15): empty #32
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4281): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4281): sendNotify, [notify] : null
D/BadgeProvider( 4281): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4281): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4281): update, [UpdateCount] : 1
D/Launcher.Model( 1469): reloadBadges entered.
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/        ( 3706): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3706): took 0.590885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3706): Bitmap=0xb8bb47b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bc7438 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3706): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): ge,tResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Use,rDictionarySettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/WearableService( 1791): callingUid 10012, callindPid: 1791
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SViewColor2014
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaData,ParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/ActivityManager( 1014): Killing 3554:com.sec.factory.camera/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.activekey.AppList
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
,I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3706): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3706): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog,
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3706): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/MDM     ( 1791): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
D/LocationInitializer( 1984): Restart initialization of location
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AuthorizationBluetoothService( 1644): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1644): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1644): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 30536(1846KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.910ms total 171.627ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1984): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1791): No location to return for getLastLocation()
,W/FusedLocationProvider( 1644): location=null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1014): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 4258): Sending signal. PID: 4258 SIG: 9
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10022/pid_3535/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3439/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3554/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/lowmemorykiller(  253): Error writing /proc/4258/oom_score_adj; errno=22
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MTPRx   ( 3578): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1014): mCursor = null
,V/MTPRx   ( 3578): sealedState: false
V/MTPRx   ( 3578): sealedUsbMassStorageState: false
E/MTPRx   ( 3578): check value of boot_completed is1
E/MTPRx   ( 3578): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3578): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 3578): Status for mount/Unmount :removed
,E/MTPRx   ( 3578): SDcard is not available
,W/MTPRx   ( 3578): value of connected istrue
,W/MTPRx   ( 3578): value of configured istrue
,W/MTPRx   ( 3578): value of mtpEnabled istrue
W/MTPRx   ( 3578): value of ptpEnabled isfalse
,E/MTPRx   ( 3578): Received USB_STATE with sdCardLaunch = 0
,I/ValidateNoPeople( 1014): mEvictionCount: 0
,E/MTPRx   ( 3578): mFirstTime: false
,I/ActivityManager( 1014): Process com.android.email (pid 4258)(adj 11) has died(111,1119)
,D/        ( 3578): MTP: reading debug level property
,E/MTPJNIInterface( 3578): Getting CryptionKey from JAVA
,E/MTPRx   ( 3578): currentUserId is 0
,E/MTPRx   ( 3578): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3578): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 3578): is_Privatemode is NOT 1
,D/SettingsProvider( 1014): name = boot_time_connected
,E/MTPRx   ( 3578): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3578): noti = 17
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,D/SecContentProvider( 1014): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 3578): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MTPRx   ( 3578): else part ... so first time!!!
,E/MTPPlaObsrvr( 3578): inside setContext()
E/MTPPlaObsrvr( 3578):  inside createplafiles
,E/MTPPlaObsrvr( 3578): playlist count is0
E/MTPPlaObsrvr( 3578):  inside try branch createplafiles
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
E/MTPPlaObsrvr( 3578):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3578): Inside registerContentObserver
,E/MtpAdbObserver( 3578): inside setContext()
,E/MtpAdbObserver( 3578): Inside registerContentObserver
,W/Settings( 3578): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,V/MtpMediaDBManager( 3578): inside deleteAllDB
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MtpService( 3578): onCreate.
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 3578): < MTP > Registering BroadCast receiver :::::
,D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MtpService( 3578): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3578): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3578): onStartCommand.
,W/MTPRx   ( 3578): calling native method
E/MTPJNIInterface( 3578): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3578): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 3578): < MTP > Registering BroadCast receiver :::::::
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,V/MtpMediaDBManager( 3578): inside Thread updateDB
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 3578): noti = 10
E/MtpService( 3578): onStartCommand.
,W/MTPRx   ( 3578): calling native method
E/MTPRx   ( 3578): Checking the driver time out
E/MTPJNIInterface( 3578): noti = 2
D/        ( 3578): deleting sockets before message queue initialization
,V/UserPresentBroadcastReceiver( 1791): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/        ( 3578): event handler thread is created, so set the flag
,E/MTPRx   ( 3578): called native method
,E/MtpService( 3578): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 3578): setting Media scanner status0
E/MTPJNIInterface( 3578): After setting Media scanner status0
,E/        ( 3578): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 3578): Getting media scanner status0
,W/MTPRx   ( 3578): notification from stack 1
,E/MTPJNIInterface( 3578): DeviceName is A5-1
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MtpMediaDBManager( 3578): count : 27,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1312): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1312): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/MtpMediaDBManager( 3578): sending db update complete noti to stack
E/MTPJNIInterface( 3578): noti = 29
,D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1312): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1312): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1312): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1312): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1449522660000
,D/daemonapp( 1312): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1449501110837
D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1312): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,E/MTPJNIInterface( 3578): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3578): SDcard is not available
,D/daemonapp( 1312): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1312): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1312): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1312): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1312): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3578): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 3578): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 3578): Status for mount/Unmount :removed
E/MTPJNIInterface( 3578): SDcard is not available
E/SQLiteLog( 3578): (21) API call with NULL database connection pointer
E/SQLiteLog( 3578): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 3578): (21) API call with NULL database connection pointer
E/SQLiteLog( 3578): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 3578): (21) API call with NULL database connection pointer
E/SQLiteLog( 3578): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 3578): (21) API call with NULL database connection pointer
E/SQLiteLog( 3578): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 3578): notification from stack 2
,D/        ( 3578): [mtp_init_device] Library open with 32 bits.
D/        ( 3578): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3578): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 3578): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 3578):  [sua_support_present:1287] returning false 
D/        ( 3578): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
E/Zygote  ( 4315): MountEmulatedStorage()
E/Zygote  ( 4315): v2
I/libpersona( 4315): KNOX_SDCARD checking this for 10111
I/libpersona( 4315): KNOX_SDCARD not a persona
,I/SELinux ( 4315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4315): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4315 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a

```
