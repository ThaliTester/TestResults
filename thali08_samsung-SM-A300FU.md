#### Test 6012434713fea37_thali08_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ResourcesManager( 3845): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
--------- beginning of main
V/AuthZen ( 2099): Handling intent: android.intent.action.BOOT_COMPLETED
W/libprocessgroup( 1017): failed to open /acct/uid_10081/pid_2903/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_1609/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3099/cgroup.procs: No such file or directory
I/CheckinService( 2099): Checking schedule, now: 1457574226676 next: 1457732977569
I/CheckinService( 2099): active receiver: disabled
I/SystemUpdateService( 2099): cancelUpdate (empty URL)
I/SystemUpdateService( 2099): active receiver: disabled
W/ContextImpl( 3845): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3877): MountEmulatedStorage()
E/Zygote  ( 3877): v2
I/libpersona( 3877): KNOX_SDCARD checking this for 1000
I/libpersona( 3877): KNOX_SDCARD not a persona
I/SELinux ( 3877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PowerManagerService( 1017): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1172 (0x0)
I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3877 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3877): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/F_PHONE ( 3845): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
D/AuthZenEventHandler( 2099): Handling event: android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 3845): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/GoogleHttpServiceClient( 1821): Timeout on service connection
W/GoogleHttpServiceClient( 1821): java.lang.Throwable
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.http.e.a(SourceFile:97)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.http.g.a(SourceFile:146)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:757)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:665)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.j.a.a(SourceFile:77)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.j.a.a(SourceFile:114)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.be.account.b.e.a(SourceFile:115)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.be.p.a(SourceFile:355)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.be.o.a(SourceFile:260)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.firstparty.dataservice.y.a(SourceFile:197)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:558)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:196)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.o.a(SourceFile:276)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.o.a(SourceFile:196)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.gms.auth.o.a(SourceFile:118)
W/GoogleHttpServiceClient( 1821): 	at com.google.android.b.b.onTransact(SourceFile:63)
W/GoogleHttpServiceClient( 1821): 	at android.os.Binder.execTransact(Binder.java:461)
I/VlingoApplication( 3804): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
E/Gmail   ( 3689): Error finding the version of the Email provider.....
E/Gmail   ( 3689): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3689): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3689): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3689): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3689): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3689): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3689): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3689): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/FactoryTestApp( 2626): [DummyFtClient$onDestroy](2626) Destroy DummyFtClient service
W/EmailMigration( 3689): We do not support migrating this version of the Email provider.
D/TimaKeyStoreProvider( 3877): TimaSignature is unavailable
D/ActivityThread( 3877): Added TimaKeyStore provider
I/Gmail   ( 3689): getAccountsCursor
I/Gmail   ( 3689): Observing account changes for notifications
D/FactoryTestApp( 2626): [Support$Values.getString](2626) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2626): [ModuleCommon$isConnectionModeNone](2626) mConnectionMode = gsm
I/FactoryTestApp( 2626): [ModuleCommon$isRunningFtClient](2626) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2626): [DummyFtClient$onDestroy](2626) kill process
I/Process ( 2626): Sending signal. PID: 2626 SIG: 9
D/F_PHONE ( 3845): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3845): default registerAction()
I/F_PHONE ( 3845): [[com.sec.bcservice]] sendPendingMessage()
I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Process com.sec.factory (pid 2626)(adj 0) has died(67,629)
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ResourcesManager( 3877): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothBDAdrressReceiver( 3877): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 3877): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
W/art     ( 2099): Suspending all threads took: 63.581ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3300): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1457): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothBDTestService( 1457): onCreate()
E/BluetoothBDTestService( 1457): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1457): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1457): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/System.out( 1821): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1821): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1821): (HTTPLog)-Static: isShipBuild true
I/System.out( 1821): (HTTPLog)-Thread-156-811726218: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1821): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
E/Zygote  ( 3907): MountEmulatedStorage()
E/Zygote  ( 3907): v2
I/libpersona( 3907): KNOX_SDCARD checking this for 1000
I/libpersona( 3907): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 3300): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
E/SELinux ( 3907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 3300): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/DBG_POLICYDM( 3300): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3300): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3300): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3300): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 3300): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
I/art     (  308): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 22.252ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 691us total 19.078ms
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/TimaKeyStoreProvider( 3907): TimaSignature is unavailable
D/ActivityThread( 3907): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 761us total 18.494ms
I/System.out( 1821): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1821): Tagging socket 77 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1821, getuid(): 10011
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3830): Resource data:2131165186
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3830): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3830): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
I/GoogleHttpClient( 1638): GMS http client unavailable, use old client
E/Zygote  ( 3922): MountEmulatedStorage()
I/libpersona( 3922): KNOX_SDCARD checking this for 10102
E/Zygote  ( 3922): v2
I/libpersona( 3922): KNOX_SDCARD not a persona
I/SELinux ( 3922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3922): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3922 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ResourcesManager( 3907): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3830): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
E/ActivityThread( 3689): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2682e015 that was originally bound here
E/ActivityThread( 3689): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2682e015 that was originally bound here
E/ActivityThread( 3689): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3689): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3689): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3689): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3689): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3689): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3689): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3689): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3689): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3689): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3689): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3689): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3689): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3689): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3689): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3689): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@2426e881
D/TimaKeyStoreProvider( 3922): TimaSignature is unavailable
D/ActivityThread( 3922): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 3922): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/VlingoAndroidCore( 3804): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
I/qtaguid ( 1821): Tagging socket 82 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1821, getuid(): 10011
D/ChimeraCfgMgr( 2099): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/BaseAppContext( 2099): Using Auth Proxy for data requests.
I/KnoxUsageLogPro( 3907): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
D/GCM     ( 1821): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
I/KnoxUsageLogPro( 3907): premStatus:2
I/KnoxUsageLogPro( 3907): isEulaShown : false
I/KnoxUsageLogPro( 3907): KnoxUsageReceiver onReceive : not Processible, just return
I/KnoxUsageLogPro( 3907): savePreference: key = previous_sys_time value = 1457574227133
I/ActivityManager( 1017): Killing 3076:com.sec.dsm.system/1000 (adj 15): empty #31
I/GCoreUlr( 1821): DispatchingService.onCreate()
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BootCompletedReceiver( 2099): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 2099): Got an BootCompleted event.
D/BootCompletedReceiver( 2099): Will NOT schedule AdAttestation signal task because it's disabled.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3076/cgroup.procs: No such file or directory
I/Icing   ( 2099): Storage manager: low false usage 2.09MB avail 9.96GB capacity 11.63GB
I/AMMetaDataParserService( 3830): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
I/KnoxUsageLogPro( 3907): savePreference: key = previous_elapsed_time value = 42062
I/GCM     ( 1821): GCM config loaded
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/BaseAppContext( 2099): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/AMMetaDataParserService( 3830): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
D/SystemUpdateService( 2099): onDestroy
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131034113
W/ResourcesManager( 3830): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AuthZen ( 2099): Fetching signing key...
D/AndroidRuntime( 3901): 
D/AndroidRuntime( 3901): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3901): CheckJNI is OFF
D/AndroidRuntime( 3901): readGMSProperty: start
D/AndroidRuntime( 3901): readGMSProperty: already setted!!
D/AndroidRuntime( 3901): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3901): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3901): readGMSProperty: end
D/AndroidRuntime( 3901): addProductProperty: start
I/AMMetaDataParserService( 3830): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/VlingoApplication( 3804): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3804): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 2099): (10) POSIX Error : 11 SQLite Error : 3850
V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AuthZen ( 2099): Signing key fetched successfully!
E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/DialogFlow( 3804): initQueue()
I/GFX construct_block_size_descriptor_2d second part( 3830): took 2.332292ms for 0*0 texture 0
I/GFX generate_partition_tables( 3830): took 6.110572ms for 0*0 texture 0
I/GFX raster( 3830): took 9.833333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78d6660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78dbee0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3830): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
I/GCoreUlr( 1821): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3830): took 0.976144ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78d6660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78f91a8 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3830): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
E/Zygote  ( 3982): MountEmulatedStorage()
E/Zygote  ( 3982): v2
I/libpersona( 3982): KNOX_SDCARD checking this for 10029
I/libpersona( 3982): KNOX_SDCARD not a persona
I/SELinux ( 3982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3982 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 3982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3130:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3982): TimaSignature is unavailable
D/ActivityThread( 3982): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3130/cgroup.procs: No such file or directory
I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
E/AffinityControl( 3901): AffinityControl: registerfunction enter
D/AndroidRuntime( 3901): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1487
D/AndroidRuntime( 3901): Shutting down VM
D/Launcher.HomeView( 1487): onPause
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : -2122120936
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/Zygote  ( 4002): MountEmulatedStorage()
E/Zygote  ( 4002): v2
I/libpersona( 4002): KNOX_SDCARD checking this for 10030
I/libpersona( 4002): KNOX_SDCARD not a persona
I/SELinux ( 4002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 4002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4002 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 4002): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3152:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4014): MountEmulatedStorage()
E/Zygote  ( 4014): v2
I/libpersona( 4014): KNOX_SDCARD checking this for 10167
I/libpersona( 4014): KNOX_SDCARD not a persona
I/SELinux ( 4014): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4014 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4014): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4014): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4002): TimaSignature is unavailable
D/ActivityThread( 4002): Added TimaKeyStore provider
V/ActivityThread( 1487): updateVisibility : ActivityRecord{23097f91 token=android.os.BinderProxy@114cc780 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 4014): TimaSignature is unavailable
D/ActivityThread( 4014): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1487): onStop
V/ActivityThread( 1487): updateVisibility : ActivityRecord{23097f91 token=android.os.BinderProxy@114cc780 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/libprocessgroup( 1017): failed to open /acct/uid_10146/pid_3152/cgroup.procs: No such file or directory
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/Launcher( 1487): onTrimMemory. Level: 20
W/art     ( 3901): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  289): DCD OFF,
,W/BaseAppContext( 2099): Using Auth Proxy for data requests.
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb7d8d5b0, enabled=0),
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1017): [SO] changed settle time [1]
,D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb7e88400, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/Babel   ( 3922): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3922): MmsConfig.loadMmsSettings
,I/Gmail   ( 3689): getAccountsCursor
,I/Babel   ( 3922): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/Babel   ( 3922): MmsConfig.loadFromDatabase
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ContactAccountLoggerTas( 3265): canRun() : Opted Out
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1],
,D/a       ( 2099): Opening database auth.proximity.permit_store...,
,D/AuthZenTransactionCache( 2099): Initialized cache in: /data/data/com.google.android.gms/files,
D/AuthZenTransactionCache( 2099): Clearing transaction cache
,E/Babel   ( 3922): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3922): MmsConfig.loadFromResources
,E/Babel   ( 3922): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3922): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,E/SQLiteLog( 3689): (283) recovered 92 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/System.out( 3235): Thread-418(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3235): Thread-418(ApacheHTTPLog):isShipBuild true
I/System.out( 3235): Thread-418(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 3235): Thread-418(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10088
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3830): took 2.266042ms for 0*0 texture 0
,W/Settings( 3922): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WebViewFactory( 4014): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/SensorService( 1017): [SO] -0.402 0.153 9.902
,D/SensorService( 1017): [SO] [100 -> 255]
,W/VideoCapabilities( 3922): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 4002): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4002): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4002): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/LibraryLoader( 4014): Loading: webviewchromium
,I/LibraryLoader( 4014): Time to load native libraries: 4 ms (timestamps 3445-3449)
,I/LibraryLoader( 4014): Expected native library version number "",actual native library version number ""
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3441): unregister AuthInfo UpdateReceiver v2.0
,D/GCMRegistrar( 3235): resetting backoff for com.dropbox.android
,V/GCMRegistrar( 3235): Registering app com.dropbox.android of senders 735665981150
,I/GFX generate_partition_tables( 3830): took 8.736562ms for 0*0 texture 0
,I/GFX raster( 3830): took 11.965936ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f7c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78dbee0 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3922): Unsupported mime audio/evrc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 3922): Unsupported mime audio/qcelp
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 31327(1769KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 16.302ms total 191.722ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/WebViewChromiumFactoryProvider( 4014): Binding Chromium to main looper Looper (main, tid 1) {336d813c}
I/LibraryLoader( 4014): Expected native library version number "",actual native library version number ""
,W/AudioCapabilities( 3922): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3922): Unsupported mime audio/mpeg-L2
I/chromium( 4014): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     ( 1821): Explicit concurrent mark sweep GC freed 29356(1661KB) AllocSpace objects, 18(480KB) LOS objects, 39% free, 9MB/16MB, paused 1.425ms total 81.917ms
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
,W/ResourcesManager( 4002): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4002): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4002): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3830): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/BrowserStartupController( 4014): Initializing chromium process, renderers=0
,W/AudioCapabilities( 3922): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 4014): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 4002): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,W/ResourcesManager( 4002): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{1045a5f2 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,W/AudioCapabilities( 3922): Unsupported mime audio/x-ima
,E/File    ( 3689): fail readDirectory() errno=2
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.595261ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f91a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78f86a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/GCoreFlp( 1821): No location to return for getLastLocation()
,W/FusedLocationProvider( 1821): location=null
,I/AMMetaDataParserService( 3830): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/GCoreUlr( 1821): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/Gmail   ( 3689): notifyAccountChanged
,W/AudioCapabilities( 3922): Unsupported mime audio/qcelp
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.874271ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78dbee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78f86a8 counterpartCT=4 counterpartW=96 counterparth=96
W/chromium( 4014): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4014): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/AMMetaDataParserService( 3830): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/GCM     ( 1821): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,I/chromium( 4014): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Gmail   ( 3689): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/Auth    ( 1821): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/Gmail   ( 3689): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/GCoreFlp( 1821): No location to return for getLastLocation()
,W/FusedLocationProvider( 1821): location=null
,I/art     ( 1638): Explicit concurrent mark sweep GC freed 5548(227KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 4MB/6MB, paused 877us total 35.252ms
,I/Gmail   ( 3689): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3689): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Adreno-EGL( 4014): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4014): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4014): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4014): Local Branch: 
I/Adreno-EGL( 4014): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4014): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4014):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/AudioCapabilities( 3922): Unsupported mime audio/evrc
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.626146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f86a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78f0658 counterpartCT=4 counterpartW=96 counterparth=96
,I/Icing   ( 2099): updateResources: need to parse f{com.google.android.gms}
I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/GCoreUlr( 1821): Unbound from all location providers
I/GCoreUlr( 1821): Place inference reporting - stopped
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SQLiteConnectionPool( 1638): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/Babel   ( 3922): babel boot account: SMS
,V/Babel   ( 3922): babel boot account: thalitester@gmail.com
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.678177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f0658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78dd180 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/VideoCapabilities( 3922): Unsupported mime video/wvc1
,W/VideoCapabilities( 3922): Unsupported mime video/x-ms-wmv
,E/Zygote  ( 4072): MountEmulatedStorage()
,E/Zygote  ( 4072): v2
I/libpersona( 4072): KNOX_SDCARD checking this for 1000
I/libpersona( 4072): KNOX_SDCARD not a persona
I/SELinux ( 4072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4072 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Killing 3190:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,E/SELinux ( 4072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/VideoCapabilities( 3922): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 3922): Unsupported mime video/wvc1
,W/VideoCapabilities( 3922): Unsupported mime video/x-ms-wmv
W/art     ( 2099): Suspending all threads took: 28.050ms
,I/GCoreUlr( 1821): DispatchingService.onDestroy()
I/GCoreUlr( 1821): Stopping handler for UlrDispSvcFast
,I/System.out( 1821): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1821): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1017): Killing 3235:com.dropbox.android/u0a88 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3170:com.google.android.configupdater/u0a82 (adj 15): empty #32
,I/System.out( 3804): INFO:Resource not found:/Common.properties Using default values
,W/VideoCapabilities( 3922): Unsupported mime video/x-ms-wmv7
,V/AlarmManager( 1017): waitForAlarm result :4
,V/AlarmManager( 1017): waitForAlarm result :4
,I/GCoreUlr( 1821): Unbound from all location providers
I/GCoreUlr( 1821): Place inference reporting - stopped
,W/VideoCapabilities( 3922): Unsupported mime video/x-ms-wmv8
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.525209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78dd180 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78edb80 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4072): TimaSignature is unavailable
,D/ActivityThread( 4072): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/chromium( 4014): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/VideoCapabilities( 3922): Unsupported mime video/mp43
,W/chromium( 4014): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/PersistentNotificationBroadcastReceiver( 1821): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/VideoCapabilities( 3922): Unsupported mime video/sorenson
,W/VideoCapabilities( 3922): Unsupported mime video/mp4v-esdp
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131034113
,I/AMMetaDataParserService( 3830): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.904843ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78d6660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78e6c28 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 4014): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3190/cgroup.procs: No such file or directory
,W/AwContents( 4014): onDetachedFromWindow called when already detached. Ignoring
,I/VideoCapabilities( 3922): Unsupported profile 4 for video/mp4v-es
,D/PhoneWindow( 4014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4014): *FMB* installDecor flags : -2139027200
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemWebViewEngine( 4014): CordovaWebView is running on device made by: samsung
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4099): MountEmulatedStorage(),
,E/Zygote  ( 4099): v2
I/libpersona( 4099): KNOX_SDCARD checking this for 10026
I/SELinux ( 4099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4099): KNOX_SDCARD not a persona
,I/SELinux ( 4099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4099): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4099 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 4014): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4014): Attempt to remove local handle scope entry from IRT, ignoring
,D/SSRM:n  ( 1017): SIOP:: AP = 410
,D/TimaKeyStoreProvider( 4099): TimaSignature is unavailable
,D/ActivityThread( 4099): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4120): MountEmulatedStorage()
E/Zygote  ( 4120): v2
I/libpersona( 4120): KNOX_SDCARD checking this for 1000
I/libpersona( 4120): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3280:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3689): getAccountsCursor
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3235/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10082/pid_3170/cgroup.procs: No such file or directory
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 4120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.836563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78d6660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,D/OpenGLRenderer( 4014): Render dirty regions requested: true
,D/TimaKeyStoreProvider( 4120): TimaSignature is unavailable
,D/ActivityThread( 4120): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3280/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,I/Gmail   ( 3689): getAccountsCursor
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/PhoneWindow( 4014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4014): *FMB* isFloatingMenuEnabled return false
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3830): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,W/ResourcesManager( 3982): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/InputDispatcher( 1017): Focus entered window: 4014
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4014): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4014): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4014): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4014): Enabling debug mode 0
,E/KnoxSetupWizardClient( 4120): isShipMode : 1
I/KnoxSetupWizardClient( 4120): onReceive : android.intent.action.BOOT_COMPLETED
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/Process ( 4002): Sending signal. PID: 4002 SIG: 9
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s480ms
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ShortcutReceiver( 4120):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/KnoxShortcutUtil( 4120): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4120):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4120):  shortcut migration not required 
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{1b6498ba u0 com.test.thalitest/.MainActivity t11} time:44557
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 4002)(adj 0) has died(26,661)
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,W/art     ( 3804): Suspending all threads took: 30.408ms
,W/System.err( 4120): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/System.err( 4120): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4120): 	at android.os.Parcel.readException(Parcel.java:1493)
,W/System.err( 4120): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4120): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4120): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4120): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/ResourcesManager( 3982): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3982): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3982): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4160): MountEmulatedStorage()
,E/Zygote  ( 4160): v2
I/libpersona( 4160): KNOX_SDCARD checking this for 1000
I/libpersona( 4160): KNOX_SDCARD not a persona
,I/SELinux ( 4160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4160 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4160): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4173): MountEmulatedStorage()
I/libpersona( 4173): KNOX_SDCARD checking this for 10031
E/Zygote  ( 4173): v2
I/libpersona( 4173): KNOX_SDCARD not a persona
,I/SELinux ( 4173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 4160): TimaSignature is unavailable
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4173 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
I/Timeline( 4014): Timeline: Activity_idle id: android.os.BinderProxy@eade93b time:44636
D/ActivityThread( 4160): Added TimaKeyStore provider
,I/SELinux ( 4173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4173): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.666041ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f7c08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4173): TimaSignature is unavailable
,D/ActivityThread( 4173): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/SamsungIME( 1860): getCurrentCandidateView
E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.845313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f91a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/8)
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/StatusChecker( 4160): onReceive : android.intent.action.BOOT_COMPLETED
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.833073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78dbee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 4099): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3830): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/GAV2    ( 3265): Thread[GAThread,5,main]: No campaign data found.
I/StatusChecker( 4160): onReceive : net.mt.init : DONE
,D/SamsungIME( 1860): Dismiss ExpandCandiate
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/JsMessageQueue( 4014): Set native->JS mode to OnlineEventsBridgeMode
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4205): MountEmulatedStorage()
E/Zygote  ( 4205): v2
I/libpersona( 4205): KNOX_SDCARD checking this for 10113
I/libpersona( 4205): KNOX_SDCARD not a persona
,I/SELinux ( 4205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4205 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,E/SELinux ( 4205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,I/ActivityManager( 1017): Killing 3300:com.policydm/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3400:com.fmm.dm/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4205): TimaSignature is unavailable
,D/ActivityThread( 4205): Added TimaKeyStore provider
,I/SamsungIME( 1860): getDebugLevel  : 0x4f4c
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/PageBuddyNotiSvc( 4205): Intent received : action=android.intent.action.BOOT_COMPLETED
I/GFX raster( 3830): took 0.653177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f86a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ContextImpl( 4205): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/jxcore_app_log( 4014): JniHelper::setJavaVM(0xb753c448), pthread_self() = -1212902256
I/PageBuddyNotiSvc( 4205): onCreate mCpBitFlag=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4224): MountEmulatedStorage()
E/Zygote  ( 4224): v2
I/libpersona( 4224): KNOX_SDCARD checking this for 10121
I/libpersona( 4224): KNOX_SDCARD not a persona
E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 4224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4014): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4014):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4014):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4014):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4014):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4014): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32449d46 added. We now have 1 listener(s)
,I/SELinux ( 4224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3400/cgroup.procs: No such file or directory
E/SELinux ( 4224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4224 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/GFX raster( 3830): took 0.697396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f0658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014): setBluetoothMacAddress: 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4014): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4014): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9d47d2 added. We now have 1 listener(s)
I/SamsungIME( 1860): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3300/cgroup.procs: No such file or directory
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4014): addListener: New listener added - the number of listeners is now 1
,I/art     (  308): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 37.966ms
,D/TimaKeyStoreProvider( 4224): TimaSignature is unavailable
,D/ActivityThread( 4224): Added TimaKeyStore provider
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.541615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78dd180 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
I/SamsungIME( 1860): KeybaordView init() : load resources
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3830): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3830): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 17.239ms
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131034112
,I/AMMetaDataParserService( 3830): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.600834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f91a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.606ms
,E/Zygote  ( 4249): MountEmulatedStorage(),
E/Zygote  ( 4249): v2
I/libpersona( 4249): KNOX_SDCARD checking this for 10032
I/SamsungIME( 1860): getCurrentKeyboard
I/libpersona( 4249): KNOX_SDCARD not a persona
,I/SamsungIME( 1860): getTextKeyboard
,I/SELinux ( 4249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4014): setDiscoveryMode: Discovery mode BLE is supported
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4249 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4249): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4224): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4224): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4224): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4249): TimaSignature is unavailable
,D/ActivityThread( 4249): Added TimaKeyStore provider
,V/AlarmManager( 1017): waitForAlarm result :8
,D/SamsungIME( 1860): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/Finsky  ( 4099): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/QuickConnect( 4224): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1017): name = scon_is_running
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10121
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,W/Settings( 4099): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4099): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/QuickConnect( 4224): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4224): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4224): PeriphStartReceiver.onReceive - no need to start
,I/chromium( 4014): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4014): 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4272): MountEmulatedStorage(),
I/libpersona( 4272): KNOX_SDCARD checking this for 10127
E/Zygote  ( 4272): v2
I/libpersona( 4272): KNOX_SDCARD not a persona
I/SELinux ( 4272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4272 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 4272): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3483:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,E/SPPClientService( 4249): ============PushLog. commonIsShipBuild. stop!,
E/SPPClientService( 4249): [PushClientApplication] Push log off : This is Ship build version
,I/chromium( 4014): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TimaKeyStoreProvider( 4272): TimaSignature is unavailable
,D/ActivityThread( 4272): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 3499:com.fmm.ds/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3464:com.sec.esdk.elm/u0a90 (adj 15): empty #32
,D/Volley  ( 4099): [598] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4099): [591] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 4099): Skipping gmscore version check
,E/SPPClientService( 4249): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/ResourcesManager( 4272): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4272): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4272): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4272): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 4099): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4099): [1] Libraries$2.run: Finished loading 1 libraries.
,W/libprocessgroup( 1017): failed to open /acct/uid_10055/pid_3483/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3499/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10090/pid_3464/cgroup.procs: No such file or directory
,D/SPPClientService( 4249): PushLog.txt file is not deleted.
,D/SPPClientService( 4249): PushLog.txt file is not deleted.
D/SPPClientService( 4249): ============PushLog. stop!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4099): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4294): MountEmulatedStorage()
I/libpersona( 4294): KNOX_SDCARD checking this for 10036
E/Zygote  ( 4294): v2
I/libpersona( 4294): KNOX_SDCARD not a persona
,I/SELinux ( 4294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4294): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4294 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4294): TimaSignature is unavailable
,D/ActivityThread( 4294): Added TimaKeyStore provider
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,D/Finsky  ( 4099): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,I/SA      ( 4294): [SSP] onCreated
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2649): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/SBrowserFeatureFlag( 4272): initialized in static block : loadCscFeatureValue() succeed! 
,I/ActivityManager( 1017): Killing 3523:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.628802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f91a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7593c30 counterpartCT=4 counterpartW=96 counterparth=96
,D/ManifestProvider( 4272): onCreate()
,I/AMMetaDataParserService( 3830): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/art     ( 4014): Background sticky concurrent mark sweep GC freed 17077(2MB) AllocSpace objects, 0(0B) LOS objects, 5% free, 12MB/13MB, paused 1.032ms total 136.985ms
,I/SA      ( 4294): [TPM] There is no property file
,I/SA      ( 4294): [SCU] isHaveSA() - false
,I/SA      ( 4294): [TPM] getModelProperty : null
I/SA      ( 4294): [TPM] getCSCProperty : null
,I/SA      ( 4294): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4294): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4294): [DM] TFT FEATURE: false
,E/NetworkSettingsReceiver( 4272): onReceive: android.intent.action.BOOT_COMPLETED
,W/System.err( 4272): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4272): 	at java.lang.Class.getMethod(Class.java:665)
,W/System.err( 4272): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4272): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
,W/System.err( 4272): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4272): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4272): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4272): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4272): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4272): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4272): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
,W/System.err( 4272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4272): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4272): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,W/System.err( 4272): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4272): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4272): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4272): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4272): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@35d74241
,D/SBrowserFeatureFlag( 4272): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4272): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4294): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4294): [DM] init START
,I/SA      ( 4294): [DM] This device is not a Vodafone
E/Zygote  ( 4316): MountEmulatedStorage()
I/libpersona( 4316): KNOX_SDCARD checking this for 10131
E/Zygote  ( 4316): v2
I/libpersona( 4316): KNOX_SDCARD not a persona
,I/SELinux ( 4316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4316 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3349:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,I/SELinux ( 4316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 4294): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4294): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,D/TimaKeyStoreProvider( 4316): TimaSignature is unavailable
,D/ActivityThread( 4316): Added TimaKeyStore provider
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.784583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7593c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78eda40 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourceType( 4294): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4294): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4294): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
I/AMMetaDataParserService( 3830): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/ResourceType( 4294): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4294): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.773436ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f86a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78eda40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/SA      ( 4294): [SCU] isHaveSA() - false
I/SA      ( 4294): support phone number id : false
I/SA      ( 4294): [DM] Supports Ref Jpn : true
I/SA      ( 4294): [DM] init END
,I/SA      ( 4294): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4294): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ResourcesManager( 4316): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4316): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4316): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/libprocessgroup( 1017): failed to open /acct/uid_10056/pid_3523/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10008/pid_3349/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4294): [OR] onReceive END
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4332): MountEmulatedStorage()
,I/libpersona( 4332): KNOX_SDCARD checking this for 10037
E/Zygote  ( 4332): v2
I/libpersona( 4332): KNOX_SDCARD not a persona
I/SELinux ( 4332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4332 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4332): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4332): TimaSignature is unavailable
,D/ActivityThread( 4332): Added TimaKeyStore provider
,E/SMD     (  289): DCD OFF
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/SA      ( 4294): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4294): [ODM] queryOpenData(key= GEO_IP )
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
,I/SA      ( 4294): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4294): [LBE] REF_JPN : true
I/SA      ( 4294): [BDC] create
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131034113
,I/AMMetaDataParserService( 3830): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3830): getResourceTypeNamexml
E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3830): took 0.814062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78dbee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78f91a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ResourcesManager( 4332): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.802968ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78dbee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7538610 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4294): [DBMV2] getEmailID
,I/SA      ( 4294): [DBMV2] getDataV02ForItems
,I/AMMetaDataParserService( 3830): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/SA      ( 4294): [SSP] query invoked
,I/SA      ( 4294): [SCU] get signed id from samsung account2.0 DB.
,V/AlarmManager( 1017): waitForAlarm result :4
,I/SA      ( 4294): [SCU] get signed id from samsung account1.0 DB.
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.655989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78f86a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78d6660 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4294): [BDC] destroy
,I/AMMetaDataParserService( 3830): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3689): Thread[GAThread,5,main]: No campaign data found.
,D/daemonapp( 1804): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/CalendarProvider2( 4332): CalendarProvider2.onCreate() called
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.592917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7593c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78f91a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/iu.UploadsManager( 2099): End new media; added: 0, uploading: 0, time: 101 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3830): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.821614ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7838498 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7538610 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 3845): WaitForGcToComplete blocked for 11.089ms for cause HomogeneousSpaceCompact
,I/AMMetaDataParserService( 3830): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 35295(1955KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 22MB/34MB, paused 2.832ms total 197.183ms
,I/ActivityManager( 1017): Killing 3550:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.630156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb78d6660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78f91a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/GFX raster( 3830): took 0.686927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7538610 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78f91a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
,E/Zygote  ( 4361): MountEmulatedStorage()
I/libpersona( 4361): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4361): v2
I/libpersona( 4361): KNOX_SDCARD not a persona
,I/SELinux ( 4361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4361 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,I/SELinux ( 4361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3830): took 0.523698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7537618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78f91a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4361): TimaSignature is unavailable
,D/ActivityThread( 4361): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/ResourcesManager( 4361): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4361): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4361): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4361): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4361): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10058/pid_3550/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/Icing   ( 2099): Internal init done: storage state 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,W/jxcore-log( 4014): Initializing JXcore engine
W/jxcore-log( 4014): JXcore engine is ready
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830,): Resource data:2131165203
W/ResourcesManager( 3830): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3830): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
I/Icing   ( 2099): Post-init done
,E/audit   ( 1980): type=1400 msg=audit(1457574231.912:205): avc:  denied  { ioctl } for  pid=4257 comm="Thread-597" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1980):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1980): type=1300 msg=audit(1457574231.912:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9eef78f8 items=0 ppid=308 ppcomm=main pid=4257 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-597" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,E/audit   ( 1980): type=1320 msg=audit(1457574231.912:205): 
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/ActivityManager( 1017): Killing 3564:com.sec.factory.camera/1000 (adj 15): empty #31
,I/GFX construct_block_size_descriptor_2d second part( 3830): took 3.804063ms for 0*0 texture 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 4014): Starting JXcore engine
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4378): MountEmulatedStorage(),
E/Zygote  ( 4378): v2
I/libpersona( 4378): KNOX_SDCARD checking this for 10141
I/GFX generate_partition_tables( 3830): took 17.321250ms for 0*0 texture 0
I/libpersona( 4378): KNOX_SDCARD not a persona
I/GFX raster( 3830): took 21.668490ms for 80*80 texture 0,
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4378 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7abd9c0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb7abe680 counterpartCT=4 counterpartW=80 counterparth=80
I/SELinux ( 4378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3830): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 4332): CalendarProvider2.onCreate() called
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,D/TimaKeyStoreProvider( 4378): TimaSignature is unavailable
,D/ActivityThread( 4378): Added TimaKeyStore provider
,I/GFX construct_block_size_descriptor_2d second part( 3830): took 2.304166ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3830): took 5.261145ms for 0*0 texture 0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3564/cgroup.procs: No such file or directory
,W/ResourcesManager( 4378): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4378): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4378): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4378): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/GFX raster( 3830): took 8.645831ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7c68b00 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c68ba8 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3830): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/jxcore-log( 4014): Platform android,
W/jxcore-log( 4014): 
W/jxcore-log( 4014): Process ARCH arm
W/jxcore-log( 4014): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/art     ( 1725): Suspending all threads took: 37.586ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1017): Killing 3582:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_10013/pid_3582/cgroup.procs: No such file or directory
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3830): took 0.686042ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7c68b00 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c6b940 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3830): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3830): took 0.861563ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7c68b00 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c6b158 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3830): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3830): took 0.625468ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7c68170 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c68218 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3830): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4407): MountEmulatedStorage(),
E/Zygote  ( 4407): v2
I/libpersona( 4407): KNOX_SDCARD checking this for 10068
I/libpersona( 4407): KNOX_SDCARD not a persona
,I/SELinux ( 4407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId,
,I/SELinux ( 4407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4407): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4407 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
E/        ( 3830): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3830): took 0.660260ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3830): Bitmap=0xb7c68170 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c68ba8 counterpartCT=4 counterpartW=80 counterparth=80
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3830): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/TimaKeyStoreProvider( 4407): TimaSignature is unavailable
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/ActivityThread( 4407): Added TimaKeyStore provider
,I/jxcore-log( 4014): JXcore Cordova bridge is ready!
I/jxcore-log( 4014): 
,W/jxcore-log( 4014): JXcore engine is started
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/org.thaliproject.p2p.ThaliPermissions( 4014): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 4014): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4014): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/BadgeProvider( 4407): onCreate
,D/BadgeProvider( 4407): DatabaseHelper
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131099648
,E/Zygote  ( 4428): MountEmulatedStorage()
E/Zygote  ( 4428): v2
I/libpersona( 4428): KNOX_SDCARD checking this for 10142
I/libpersona( 4428): KNOX_SDCARD not a persona
,I/SELinux ( 4428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4428 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
W/ResourcesManager( 3830): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3830): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,I/ActivityManager( 1017): Killing 3625:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
I/ActivityManager( 1017): Killing 3597:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #32
I/SELinux ( 4428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 4014): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 4014
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/TimaKeyStoreProvider( 4428): TimaSignature is unavailable
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (191 us)
D/ActivityThread( 4428): Added TimaKeyStore provider
I/AMMetaDataParserService( 3830): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/BadgeProvider( 4407): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/AMMetaDataParserService( 3830): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/PluginManager( 4014): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 54ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,W/libprocessgroup( 1017): failed to open /acct/uid_10095/pid_3597/cgroup.procs: No such file or directory
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,W/ResourcesManager( 4428): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3830): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/Launcher( 1487): onRestart, Launcher: 903299649
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3625/cgroup.procs: No such file or directory
,D/Launcher( 1487): onStart, Launcher: 903299649,
,D/Launcher.HomeView( 1487): onStart
D/Launcher( 1487): onResume, Launcher: 903299649
D/SettingsProvider( 1017): name = kids_home_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SettingsProvider( 1017): selectionArgs: 10006
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/Launcher.HomeView( 1487): onResume
,D/SensorService( 1017): [SO] activate (ident=0xb7e88400, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/BadgeProvider( 4407): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4407): sendNotify, [notify] : null
D/BadgeProvider( 4407): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4407): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4407): update, [UpdateCount] : 1
,D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
D/MenuAppsGridFragment( 1487): onResume
,D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb7e88400, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/SurfaceFlinger(  258): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 1487
,D/SRIB_DCS( 1487): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/Launcher.Model( 1487): reloadBadges entered.
,D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 4014): showStatusIcon on inactive InputConnection
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) ,
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/SamsungIME( 1860): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,W/ActivityManager( 1017): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/AMMetaDataParserService( 3830): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,E/Zygote  ( 4450): MountEmulatedStorage()
I/libpersona( 4450): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4450): v2
I/libpersona( 4450): KNOX_SDCARD not a persona
I/SELinux ( 4450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131099648
,I/ActivityManager( 1017): Displayed Component not be shown by security: +154ms
,I/Timeline( 1487): Timeline: Activity_idle id: android.os.BinderProxy@114cc780 time:47806
I/AMMetaDataParserService( 3830): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,I/Process ( 4378): Sending signal. PID: 4378 SIG: 9
,E/lowmemorykiller(  255): Error writing /proc/4378/oom_score_adj; errno=22,
,I/ActivityManager( 1017): Killing 3322:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/lowmemorykiller(  255): Error writing /proc/4378/oom_score_adj; errno=22
,I/AMMetaDataParserService( 3830): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4450): TimaSignature is unavailable
,D/ActivityThread( 4450): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3830): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_3322/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3830): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/ActivityManager( 1017): Process com.android.email (pid 4378)(adj 9) has died(38,584)
,I/ActivityThread( 4428): Removing dead content provider:android.content.ContentProviderProxy@38a9b72f
I/ActivityThread( 4428): Removing dead content provider:android.content.ContentProviderProxy@38a9b72f
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131099648
,I/AMMetaDataParserService( 3830): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4466 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4466): MountEmulatedStorage()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4466): v2
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/libpersona( 4466): KNOX_SDCARD checking this for 1000
I/libpersona( 4466): KNOX_SDCARD not a persona
,I/SELinux ( 4466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4466): TimaSignature is unavailable
,D/ActivityThread( 4466): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/art     (  308): Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 33.350ms
,I/AMMetaDataParserService( 3830): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.513ms
,I/AMMetaDataParserService( 3830): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.532ms
,I/AMMetaDataParserService( 3830): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131099648
,E/Zygote  ( 4481): MountEmulatedStorage()
I/AMMetaDataParserService( 3830): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,E/Zygote  ( 4481): v2
I/libpersona( 4481): KNOX_SDCARD checking this for 10141
I/libpersona( 4481): KNOX_SDCARD not a persona
I/SELinux ( 4481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SELinux ( 4481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4481): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4481 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/AMMetaDataParserService( 3830): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/CalendarProvider2( 4332): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3830): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/TimaKeyStoreProvider( 4481): TimaSignature is unavailable
,D/ActivityThread( 4481): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 3656:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3705:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/AMMetaDataParserService( 3830): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/SecurityLogAgent( 4466): KnoxConfiguration : Current State = 1
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 4481): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4481): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SecurityLogAgent( 4466): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4466): StateMachine : Current State = 1,
,D/SecurityLogAgent( 4466): BootReceiver : completed task. Failed to return wakelock . ,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4497): MountEmulatedStorage()
I/libpersona( 4497): KNOX_SDCARD checking this for 10148
E/Zygote  ( 4497): v2
I/libpersona( 4497): KNOX_SDCARD not a persona
I/SELinux ( 4497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4497 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 4497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 3672:com.wssnps/1000 (adj 15): empty #31
,D/SensorService( 1017): [SO] currT = 48111043000, prevT = 47631164000, diff = 479879000, [-0.402 0.172 9.883]
,D/SensorService( 1017): [SO] -0.402 0.172 9.883
D/SensorService( 1017): [SO] [100 -> 255]
,I/AMMetaDataParserService( 3830): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131099648
,D/TimaKeyStoreProvider( 4497): TimaSignature is unavailable
,I/AMMetaDataParserService( 3830): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,D/ActivityThread( 4497): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,I/AMMetaDataParserService( 3830): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1017): failed to open /acct/uid_10020/pid_3705/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_3656/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3672/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/SQLiteLog( 4497): (284) automatic index on shooting_modes(title_id)
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3830): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3830): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/Zygote  ( 4519): MountEmulatedStorage()
E/Zygote  ( 4519): v2
I/libpersona( 4519): KNOX_SDCARD checking this for 1000
I/libpersona( 4519): KNOX_SDCARD not a persona
,I/SELinux ( 4519): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/CalendarProvider2( 4332): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/SELinux ( 4519): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4519): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4519 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/ActivityManager( 1017): Killing 3724:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{27217784 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:48231
,I/ActivityManager( 1017): Killing 3749:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4519): TimaSignature is unavailable
,D/ActivityThread( 4519): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
I/SurfaceFlinger(  258): id=12 Removed NainActivit (7/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,I/AMMetaDataParserService( 3830): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ScreenOrientationListener( 4014): Removing an inexistent observer!
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131099648
,I/AMMetaDataParserService( 3830): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1017): Killing 1518:com.android.defcontainer/u0a3 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 3441): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3441): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3441): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3441): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/AMMetaDataParserService( 3830): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/splitIntent( 1017): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,I/splitIntent( 1017): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3830): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,E/Zygote  ( 4536): MountEmulatedStorage()
I/libpersona( 4536): KNOX_SDCARD checking this for 10108
E/Zygote  ( 4536): v2
,I/libpersona( 4536): KNOX_SDCARD not a persona
I/SELinux ( 4536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4536 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4536): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3640): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 02:43:53 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/accuweather( 1746): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/AMMetaDataParserService( 3830): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/KLMS-2.5.123: ( 3640): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 1804): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1746): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/TimaKeyStoreProvider( 4536): TimaSignature is unavailable
D/accuweather( 1746): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1746): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1746): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/ActivityThread( 4536): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/KLMS-2.5.123: ( 3640): KLMSIntentService(): onCreate()
,D/BadgeProvider( 4407): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/KLMS-2.5.123: ( 3640): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3640): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/KLMS-2.5.123: ( 3640): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/KLMS-2.5.123: ( 3640): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 4554): MountEmulatedStorage(),
I/AMMetaDataParserService( 3830): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
E/Zygote  ( 4554): v2
I/libpersona( 4554): KNOX_SDCARD checking this for 1000
I/libpersona( 4554): KNOX_SDCARD not a persona
,I/SELinux ( 4554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4554 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4554): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,I/KLMS-2.5.123: ( 3640): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
D/accuweather( 1746): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1746): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.123: ( 3640): StateImplV2(): networkChangeListener().START
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3640): NetworkChangeOperations(): uploadRequestLog().START 
,D/Launcher.Model( 1487): reloadBadges entered.
D/BadgeProvider( 4407): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4407): sendNotify, [notify] : null
D/BadgeProvider( 4407): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4407): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4407): update, [UpdateCount] : 1
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4567 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4567): MountEmulatedStorage()
I/libpersona( 4567): KNOX_SDCARD checking this for 10077
E/Zygote  ( 4567): v2
I/libpersona( 4567): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3640): NetworkChangeOperations(): uploadRequestLog().END 
I/SELinux ( 4567): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/KLMS-2.5.123: ( 3640): StateImplV2(): networkChangeListener().END
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/SELinux ( 4567): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4567): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3830): Reso,urce data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/SecurityLogAgent( 4466): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4466): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4466): StateMachine : Current State = 1
D/SecurityLogAgent( 4466): StateMachine : Changed Current State = 1
D/TimaKeyStoreProvider( 4554): TimaSignature is unavailable
D/ActivityThread( 4554): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 4567): TimaSignature is unavailable
D/ActivityThread( 4567): Added TimaKeyStore provider
I/Process ( 4428): Sending signal. PID: 4428 SIG: 9
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131165197
,W/ResourcesManager( 3830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3830): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
I/KLMS-2.5.123: ( 3640): KLMSIntentService(): onDestroy()
,I/ActivityManager( 1017): Process com.android.exchange (pid 4428)(adj 15) has died(28,585)
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4554): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4554): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3724/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3749/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_1518/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,E/Watchdog( 1017): !@Sync 1
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/iu.SyncManager( 2099): SYNC; picasa accounts
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,D/SettingsProvider( 1017): name = audio_safe_volume_state
,I/MusicStore( 4536): Database version: 104
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4597): MountEmulatedStorage()
E/Zygote  ( 4597): v2
I/libpersona( 4597): KNOX_SDCARD checking this for 10110
I/libpersona( 4597): KNOX_SDCARD not a persona
,I/SELinux ( 4597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4597 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 3830): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,E/SELinux ( 4597): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !,
,I/AMMetaDataParserService( 3830): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/DBG_POLICYDM( 4554): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 4597): TimaSignature is unavailable
,D/ActivityThread( 4597): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4554): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 4554): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,E/SPPClientService( 4249): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 4294): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ],
,I/SA      ( 4294): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4294): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4294): [SLFUCHKMGR] constructor called
,I/AMMetaDataParserService( 3830): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/NetworkLogImpl( 2099): Loaded NetworkSpeedPredictor
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SA      ( 4294): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4294): [OR] == isSIMCardReady false ==
,I/iu.Environment( 2099): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SA      ( 4294): [SCU] == networkStateCheck == true
,I/SA      ( 4294): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4294): isChinaCountryCode : false
I/SA      ( 4294): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4294): [OR] == networkStateCheck true ==
,I/SA      ( 4294): [OR] GetMyCountryZoneTask
,I/SA      ( 4294): [OR] onReceive END
,I/ActivityManager( 1017): Killing 3770:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/iu.UploadsManager( 2099): num queued entries: 0
,I/iu.UploadsManager( 2099): num updated entries: 0
,I/iu.SyncManager( 2099): NEXT; no task
,I/SA      ( 4294): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 4554): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4554): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4294): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4294): [SSP] query invoked
,E/Zygote  ( 4618): MountEmulatedStorage()
E/Zygote  ( 4618): v2
I/libpersona( 4618): KNOX_SDCARD checking this for 10009
I/libpersona( 4618): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4618 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4618): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SA      ( 4294): [TPMU] GetMccFromDB : null
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/SA      ( 4294): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4294): [TPM] isNoProxy(default) : true
,D/TimaKeyStoreProvider( 4618): TimaSignature is unavailable
,D/ActivityThread( 4618): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131165197
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 4554): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/AMMetaDataParserService( 3830): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,W/libprocessgroup( 1017): failed to open /acct/uid_10065/pid_3770/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/AMMetaDataParserService( 3830): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  289): DCD OFF
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/File    ( 4294): fail readDirectory() errno=2
,I/AMMetaDataParserService( 3830): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/WaitQueueForNetworkActivate( 4618): notifyNetworkActivated
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/AMMetaDataParserService( 3830): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,W/ContextImpl( 4618): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/DBG_POLICYDM( 4554): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4554): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4554): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4554): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/13/12:50:23
,I/DBG_POLICYDM( 4554): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/10/02:43:54
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131165197
I/DBG_POLICYDM( 4554): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/AMMetaDataParserService( 3830): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,W/ResourcesManager( 4536): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4536): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 4554): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/AMMetaDataParserService( 3830): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4597): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,V/JNIHelp ( 4536): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/DBG_POLICYDM( 4554): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4554): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/AMMetaDataParserService( 3830): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/DBG_POLICYDM( 4554): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4554): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4554): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,W/ContextImpl( 4597): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DBG_POLICYDM( 4554): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/AMMetaDataParserService( 3830): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/ActivityThread( 4536): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4536): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1eec98c9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4536): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4536): GMSCore installation verified
,I/AMMetaDataParserService( 3830): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4597): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4597): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131099648
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 25530(1425KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 4.363ms total 170.760ms
,W/ResourcesManager( 3830): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3830): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/ConfigStore( 4536): Config Database version: 1
,I/DBG_POLICYDM( 4554): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/AMMetaDataParserService( 3830): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/DBG_POLICYDM( 4554): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 4554): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/AMMetaDataParserService( 3830): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/WebViewFactory( 4597): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/LibraryLoader( 4597): Loading: webviewchromium
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/hcjo    ( 4618): AutoUpdateManager:IDLE:execute
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,D/InitializeManagerStateMachine( 4618): execute::IDLE:EXECUTE
,I/LibraryLoader( 4597): Time to load native libraries: 28 ms (timestamps 9927-9955)
I/LibraryLoader( 4597): Expected native library version number "",actual native library version number ""
,D/InitializeManagerStateMachine( 4618): exit::IDLE
,D/InitializeManagerStateMachine( 4618): entry::NETWORK_CHECK
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/InitializeManagerStateMachine( 4618): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 4618): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4618): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4618): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4618): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4618): entry::SUCCESS
D/hcjo    ( 4618): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 0
,I/MediaRouter( 4536): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/hcjo    ( 4618): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,D/hcjo    ( 4618): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4618): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
V/WebViewChromiumFactoryProvider( 4597): Binding Chromium to main looper Looper (main, tid 1) {35e8070b}
,I/LibraryLoader( 4597): Expected native library version number "",actual native library version number ""
,I/chromium( 4597): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/InitializeManagerStateMachine( 4618): exit::SUCCESS
,D/InitializeManagerStateMachine( 4618): entry::IDLE
,I/NetworkMonitor( 4536): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4666): MountEmulatedStorage(),
E/Zygote  ( 4666): v2
I/libpersona( 4666): KNOX_SDCARD checking this for 10001
,I/libpersona( 4666): KNOX_SDCARD not a persona
,I/SELinux ( 4666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.GridSettings,
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:assistant
I/AMMetaDataParserService( 3830): Resource data:2131165220,
,I/SELinux ( 4666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/BrowserStartupController( 4597): Initializing chromium process, renderers=0
E/SELinux ( 4666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 4597): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4666 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3830): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3830): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3830): getResourceTypeNamexml
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AMMetaDataParserService( 3830): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,I/NetworkMonitor( 4536): type=WIFI subType= reason=null isConnected=true
,I/AMMetaDataParserService( 3830): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/ActivityManager( 1017): Killing 3877:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,W/chromium( 4597): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4597): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 4597): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/TimaKeyStoreProvider( 4666): TimaSignature is unavailable
,D/ActivityThread( 4666): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
W/AudioManagerAndroid( 4597): Requires BLUETOOTH permission
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop ,for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
W/ContextImpl( 3830): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1017): Killing 3830:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Display
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3877/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
,I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PhoneVibration
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3830): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3830): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3830): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/Adreno-EGL( 4597): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4597): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4597): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4597): Local Branch: 
I/Adreno-EGL( 4597): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4597): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4597):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/NSApplication( 4597): Starting up...
,I/ActivityManager( 1017): Killing 3689:com.google.android.gm/u0a99 (adj 15): empty #31
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4702): MountEmulatedStorage()
I/libpersona( 4702): KNOX_SDCARD checking this for 1000,
E/Zygote  ( 4702): v2
I/libpersona( 4702): KNOX_SDCARD not a persona
I/SELinux ( 4702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4702 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3922:com.google.android.talk/u0a102 (adj 15): empty #31
,I/SELinux ( 4702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3830/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/QuickConnect( 4224): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 4224): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4224): PeriphStartReceiver.onReceive - no need to start
,I/ActivityManager( 1017): Killing 3907:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4702): TimaSignature is unavailable
,D/ActivityThread( 4702): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_3689/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 4702): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1017): failed to open /acct/uid_10102/pid_3922/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3907/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 4702): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 4702): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 4702): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4702): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4702): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4702): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4554): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4719 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4719): MountEmulatedStorage(),
E/Zygote  ( 4719): v2
I/libpersona( 4719): KNOX_SDCARD checking this for 10008
I/libpersona( 4719): KNOX_SDCARD not a persona
,I/SELinux ( 4719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4719): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4719): TimaSignature is unavailable
,D/ActivityThread( 4719): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 47.729ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.421ms
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{ee588b8 u0 com.android.settings/.wifi.WifiCredService}
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.315ms
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,I/ActivityManager( 1017): Killing 3804:com.vlingo.midas/u0a28 (adj 15): empty #31
,I/FOTA_Client( 4719): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4719): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4719): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4719): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/splitIntent( 1017): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 4072:com.samsung.helphub/1000 (adj 15): empty #31
,I/splitIntent( 1017): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1017): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4737): MountEmulatedStorage(),
E/Zygote  ( 4737): v2
I/libpersona( 4737): KNOX_SDCARD checking this for 10058
I/libpersona( 4737): KNOX_SDCARD not a persona
,I/SELinux ( 4737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4737 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/SA      ( 4294): [RC New] Execute method=[GET] start
,D/TimaKeyStoreProvider( 4737): TimaSignature is unavailable
,D/ActivityThread( 4737): Added TimaKeyStore provider
,D/daemonapp( 1804): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1804): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/daemonapp( 1804): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1804): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/FOTA_Client( 4719): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/daemonapp( 1804): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1804): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/SecurityLogAgent( 4466): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4466): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4466): StateMachine : Current State = 1
,D/comsamsunglog( 1804): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1804): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1804): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1804): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1804): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1804): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/FOTA_Client( 4719): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{2fb566c9 u0 com.samsung.android.providers.context/.ContextService}
,D/daemonapp( 1804): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,W/ContextImpl( 2941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3640): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 10 02:43:55 GMT+01:00 2016
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4072/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_3804/cgroup.procs: No such file or directory
,D/daemonapp( 1804): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1804): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1804): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1804): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1804): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,E/Zygote  ( 4755): MountEmulatedStorage()
I/libpersona( 4755): KNOX_SDCARD checking this for 10153
E/Zygote  ( 4755): v2
I/libpersona( 4755): KNOX_SDCARD not a persona
,I/SELinux ( 4755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4755 uid=10153 gids={50153, 9997} abi=armeabi-v7a
E/SELinux ( 4755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/SA      ( 4294): [RC New] Security=[true]
,I/KLMS-2.5.123: ( 3640): KLMSAbstractReciever(): onReceive().END.
,I/System.out( 4294): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/DBG_DM  ( 3110): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/SA      ( 4294): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/DBG_DM  ( 3110): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3110): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/Process ( 2941): Sending signal. PID: 2941 SIG: 9
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,W/art     ( 4294): Suspending all threads took: 8.611ms
,I/KLMS-2.5.123: ( 3640): KLMSIntentService(): onCreate()
D/comdaemonstockapp( 1804): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1804): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/TimaKeyStoreProvider( 4755): TimaSignature is unavailable
,D/ActivityThread( 4755): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3640): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/System.out( 4294): Thread-630(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 4294): Thread-630(ApacheHTTPLog):isShipBuild true
I/System.out( 4294): Thread-630(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4294): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10036
,I/ExternalOEMControlProvider( 4737): onCreate
,I/KLMS-2.5.123: ( 3640): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3640): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 3640): KLMSIntentService(): TIME_CHANGED
,D/accuweather( 1746): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
I/KLMS-2.5.123: ( 3640): StateImplV2(): dateTimeChanged().START : Thu Mar 10 02:43:56 GMT+01:00 2016
W/ResourcesManager( 4755): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1746): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.123: ( 3640): StateImplV2(): dateTimeChanged().END
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ Time Manager ( 4737): Time Difference not stored. TIME_DIFFERENCE
,E/Zygote  ( 4773): MountEmulatedStorage()
I/libpersona( 4773): KNOX_SDCARD checking this for 10081
E/Zygote  ( 4773): v2
I/libpersona( 4773): KNOX_SDCARD not a persona
,I/SELinux ( 4773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4773 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4773): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3640): KLMSIntentService(): onDestroy()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4773): TimaSignature is unavailable
,D/ActivityThread( 4773): Added TimaKeyStore provider
,E/Zygote  ( 4786): MountEmulatedStorage()
,E/Zygote  ( 4786): v2
I/libpersona( 4786): KNOX_SDCARD checking this for 10041
I/libpersona( 4786): KNOX_SDCARD not a persona
,I/SELinux ( 4786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4786 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 4786): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Process com.sec.android.app.sysscope (pid 2941)(adj 0) has died(64,582)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4786): TimaSignature is unavailable
,D/ActivityThread( 4786): Added TimaKeyStore provider
,W/ResourcesManager( 4773): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4773): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4773): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4773): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4773): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/Zygote  ( 4802): MountEmulatedStorage()
E/Zygote  ( 4802): v2
I/libpersona( 4802): KNOX_SDCARD checking this for 1000
I/libpersona( 4802): KNOX_SDCARD not a persona
,I/SELinux ( 4802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4802 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4120:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/CheckinService( 2099): Checkin interval check for package: unspecified last checkin: 1457166050648 min interval config: 0 actual interval: 408185520
,D/TimaKeyStoreProvider( 4802): TimaSignature is unavailable
,D/ActivityThread( 4802): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4160:com.sec.android.app.mt/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ResourcesManager( 4786): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 4786): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4786): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4786): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4786): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4120/cgroup.procs: No such file or directory
,D/TimeService( 4802): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457574236294
,D/        ( 4802): TimeServiceNative: User Time to be set is 1457574236295
D/QC-time-services( 4802): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 4802): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4802): Lib:time_genoff_operation: pargs->ts_val = 1457574236295
,D/QC-time-services(  326): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4802): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  326): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457574236295
D/QC-time-services(  326): Daemon:genoff_opr: Base = 2, val = 1457574236295, operation = 0
,D/QC-time-services(  326): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/5/70 5:20:39
D/QC-time-services(  326): Daemon:Value read from RTC seconds = 21360039000
D/QC-time-services(  326): Daemon:new time 1457574236295 
D/QC-time-services(  326): Daemon: delta 1436214197295 genoff 1436214197295 
D/QC-time-services(  326): Daemon:genoff_persistent_update: Writing genoff = 1436214197295 to memory
D/QC-time-services(  326): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  326): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4160/cgroup.procs: No such file or directory
,D/Mms/MmsApp( 4786): [start]    onCreate() consume time = 0.0
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/SettingsProvider( 1017): name = next_alarm_formatted
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10081
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/QC-time-services(  326): Updating the TOD offset
D/QC-time-services(  326): Daemon:genoff_persistent_update: Writing genoff = 1436214197295 to memory
D/QC-time-services(  326): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  326): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  326): Daemon:Update to modem bit set
D/QC-time-services(  326): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  326): Daemon: Base = 2, Value being sent to MODEM = 1120249397295
,E/QC-time-services( 4802): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  326): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  326): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1017): Killing 4272:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,W/art     ( 4786): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 110.200ms
,W/art     ( 4773): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 113.114ms,
,W/libprocessgroup( 1017): failed to open /acct/uid_10127/pid_4272/cgroup.procs: No such file or directory
,D/Mms/ArtClassLoader( 4786): init before art
,D/Mms/TelephonyPermission( 4786): start operation mode monitor
,W/ResourcesManager( 4786): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4821): MountEmulatedStorage()
E/Zygote  ( 4821): v2
I/libpersona( 4821): KNOX_SDCARD checking this for 10090
I/libpersona( 4821): KNOX_SDCARD not a persona
,I/SELinux ( 4821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4821 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4099:com.android.vending/u0a26 (adj 15): empty #31
,D/Mms/TelephonyPermission( 4786): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4786): isDefault true
D/Mms/MmsApp( 4786): onCreate() com.android.mms
,D/TimaKeyStoreProvider( 4821): TimaSignature is unavailable
,D/ActivityThread( 4821): Added TimaKeyStore provider
,D/Mms/MmsApp( 4786): [start]    initCountryIso consume time = 275.363386
,D/elm:15121( 4821): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 4821): ELMEngine.ELMEngine( context ).
,D/elm:15121( 4821): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/CountryDetector( 1017): The first listener is added
,D/elm:15121( 4821): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:15121( 4821): ElmAgentService : onCreate()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 4821): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/Mms/MmsApp( 4786): [end]    initCountryIso consume time = 28.699896
D/Mms/MmsConfig( 4786): [start]    MmsConfig.init() consume time = 0.101927
,D/elm:15121( 4821): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 4821): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 4821): ModuleBase.ModifySetAlarm()
D/elm:15121( 4821): MDMBridge.getInstance()
D/elm:15121( 4821): MDMBridge.getAllLicenseInfoFromSDK()
,D/PackageManager( 1017): [MSG] SEND_PENDING_BROADCAST
,E/Zygote  ( 4840): MountEmulatedStorage()
I/libpersona( 4840): KNOX_SDCARD checking this for 10130
E/Zygote  ( 4840): v2
I/libpersona( 4840): KNOX_SDCARD not a persona
,I/SELinux ( 4840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4840): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4840 uid=10130 gids={50130, 9997} abi=armeabi-v7a
D/elm:15121( 4821): ElmAgentService : onDestroy().
,D/Mms/MmsConfig( 4786): before partial update,
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4205): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/ActivityManager( 1017): Killing 4361:com.sec.android.app.camera/u0a135 (adj 15): empty #31
D/TimaKeyStoreProvider( 4840): TimaSignature is unavailable
,D/ActivityThread( 4840): Added TimaKeyStore provider
,W/IntentResolver( 1017): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/Mms/MmsConfig( 4786): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4786): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4786): isAuth is false
,D/Mms/MmsConfig( 4786): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/RegisteredServicesCache( 1443): empty dynamic service
,D/TP/MmsSmsProvider( 1457): query,matched:2117, calling pid = 4786
,D/TP/MmsSmsProvider( 1457): match 2117:Elapsed time : 2.608 ms
,D/EasySignUpManager_1.0.1( 4786): isAuth is false
,D/EasySignUpManager_1.0.1( 4786): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4786): mps_code.dat does not exist
E/CscParser( 4786): customer_path =/system/csc/customer.xml
E/CscParser( 4786): fileName + /system/csc/customer.xml
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/ResourcesManager( 4840): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4840): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/CscParser( 4786): mps_code.dat does not exist
,E/CscParser( 4786): customer_path =/system/csc/customer.xml
,E/CscParser( 4786): fileName + /system/csc/customer.xml
,I/SA      ( 4294): [RC New] [v2liruge] api execute + 780
,I/SA      ( 4294): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4294): AsyncTask #1 calls detatch()
,D/CscParser( 4786): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4786):  enable multiwindow = false
,I/SA      ( 4294): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 4294): [OCP] update openData : PL
,I/ActivityManager( 1017): Killing 4450:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,E/Mms/MessageUtils( 4786): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4786): updateCountryIso : update country iso info 
,I/SA      ( 4294): [TPMU] getNetworkMcc : 
,I/SA      ( 4294): [SCU] saveMccToPreferece Start
I/SA      ( 4294): [SCU] RegionMCC : 260
I/SA      ( 4294): [SSP] query invoked
,I/SA      ( 4294): [TPMU] GetMccFromDB : null
,I/SA      ( 4294): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4294): [SCU] saveMccToPreferece End
,I/SA      ( 4294): [RC New] executeRequest [v2liruge] end. 919
I/SA      ( 4294): [RC New] Execute end
,I/SA      ( 4294): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4294): [OR] GetMyCountryZoneTask Success
,D/Mms/MmsConfig( 4786): [end]    init() consume time = 207.886979
D/Mms/Contact( 4786): [start]    init() consume time = 0.727239
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService( 1017): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,I/DBG_DM  ( 3110): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/BackupManagerService( 1017): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/Mms/ArtClassLoader( 4786): init [DONE] art
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,D/TP/MmsSmsProvider( 1457): query,matched:13, calling pid = 4786
,I/DBG_DM  ( 3110): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/Contact( 4786): [end]    init consume time = 23.556459
,D/TP/MmsSmsProvider( 1457): match 13:Elapsed time : 3.611 ms
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/DraftCache( 4786): [start]    rebuildCache consume time = 6.959687
,D/Mms/MethodReflector( 4786): getSubId is called
,D/Mms/TelephonyUtils( 4786): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4786): getTelephonyProperty is called
D/Mms/DownloadManager( 4786): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4786): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4786): auto download without roaming -> true
D/Mms/DownloadManager( 4786): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4786): getSubId is called
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/MethodReflector( 4786): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 4786): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4786): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4786): getTelephonyProperty is called
,D/Mms/DownloadManager( 4786): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4786): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4786): auto download without roaming -> true
,D/Mms/DownloadManager( 4786): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4786): auto download during roaming secondary -> false
,D/Mms/DownloadManager( 4786): mAutoDownload ------> true
,V/BackupManagerService( 1017): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1017): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@14c2322b
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/TP/MmsSmsProvider( 1457): query,matched:12, calling pid = 4786
,D/TP/MmsSmsProvider( 1457): match 12:Elapsed time : 6.238 ms
,D/Mms/DraftCache( 4786): [end]    rebuildCache consume time = 32.809115
,D/ComposerPerformance( 4786): 1457574236927 ms / [DONE] Composer constructor
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,D/Mms/Conversation( 4786): [start]    init() consume time = 15.034427
,D/TP/MmsSmsProvider( 1457): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1457): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1457): updateThread(), thread_id = 9223372036854775807
I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,V/TP/MmsSmsDatabaseHelper( 1457): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1457): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1457): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1457): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1457): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1457): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1457): (284) automatic index on im_threads(normal_thread_id)
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,D/TP/MmsSmsProvider( 1457): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1457): need read changed broadcast:false
,D/Mms/Conversation( 4786): [end]    init consume time = 20.665364
,I/art     ( 1487): Background sticky concurrent mark sweep GC freed 35245(1971KB) AllocSpace objects, 42(1564KB) LOS objects, 12% free, 18MB/20MB, paused 12.606ms total 89.954ms
,E/CII     ( 4786): CommonIMSInterface: VoLTE CSC feature disabled.
D/Mms/MessagingNotification( 4786): [start]    init() consume time = 2.127032
,I/Mms/ReservationManager( 4786): ReservationManager()
,I/Mms/ReservationManager( 4786): resetAfterConnected()
,D/Mms/MessagingNotification( 4786): [end]    init consume time = 4.494218
,D/TP/MmsSmsProvider( 1457): query,matched:7, calling pid = 4786
,D/TP/MmsSmsProvider( 1457): query,matched:0, calling pid = 4786
,V/TP/MmsSmsProvider( 1457): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1457): match 0:Elapsed time : 2.077 ms
,D/TP/MmsSmsProvider( 1457): match 7:Elapsed time : 3.711 ms
,D/Mms/SpamFilter( 4786): [start]    SpamFilter fill() begin consume time = 7.841615
,D/TP/MmsSmsProvider( 1457): query,matched:400, calling pid = 4786
,I/DBG_DM  ( 3110): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/Mms/ReservationManager( 4786): getReservedSendMessageCount(): retMessageCount=0
,I/DBG_DM  ( 3110): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,D/Mms/Synchronizer( 4786): [start]    doSync consume time = 9.77625
,D/Mms/SpamFilter( 4786): [end]    SpamFilter fill() finished consume time = 4.899479
,D/TP/MmsSmsProvider( 1457): update, matched:300, calling pid = 4786
,V/TP/MmsSmsProvider( 1457): syncDBData start
,D/Mms/MmsApp( 4786): [end]    onCreate() consume time = 2.630469
,I/DBG_DM  ( 3110): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,V/TP/MmsSmsProvider( 1457): syncDBData sms end
D/Mms/DownloadManager( 4786): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4786): roaming ------> false, mSimSlot = 0
,V/TP/MmsSmsProvider( 1457): syncDBData mms end
D/Mms/MethodReflector( 4786): getSubId is called
D/Mms/TelephonyUtils( 4786): getLongSubId from simSlot 0, return Value = -1
V/TP/MmsSmsProvider( 1457): syncDBData end
,D/Mms/MethodReflector( 4786): getTelephonyProperty is called
,D/Mms/DownloadManager( 4786): roaming -> false (slotId = 0)
I/DBG_DM  ( 3110): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
D/Mms/DownloadManager( 4786): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4786): auto download without roaming -> true
D/Mms/DownloadManager( 4786): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4786): mAutoDownload ------> true
,I/splitIntent( 1017): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,I/DBG_DM  ( 3110): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,I/DBG_DM  ( 3110): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1017): Killing 4497:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/Synchronizer( 4786): [end]    doSync consume time = 21.805937
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 3110): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,I/DBG_DM  ( 3110): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,V/AlarmManager( 1017): waitForAlarm result :4
,D/Mms/MessagingNotification( 4786): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/DBG_DM  ( 3110): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@1ea4c9fc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,W/ContextImpl( 3110): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,W/ContextImpl( 3110): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/Timeline( 3110): Timeline: Activity_launch_request id:com.wssyncmldm time:52038
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1821): callingUid 10011, callindPid: 1821
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1821): [257] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1017): Set to : 0
,D/Launcher.HomeView( 1487): onPause
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher,
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1017): Focused application set to: xxxx
D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1017): Focus left window: 1487
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreNlp( 1821): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2099): Restart initialization of location
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 35317(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 5.277ms total 164.855ms
,D/TP/SmsProvider( 1457): query,matched:26, calling pid = 4786
,D/TP/SmsProvider( 1457): match 26:Elapsed time : 2.371 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb7e88400, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb7f3a258, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  ,
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,W/libprocessgroup( 1017): failed to open /acct/uid_10026/pid_4099/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_4361/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1457): query,matched:6, calling pid = 4786
,D/TP/MmsSmsProvider( 1457): match 6:Elapsed time : 3.797 ms
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4450/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_4497/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1017): applying state to connected service
,D/AuthorizationBluetoothService( 1821): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationProviderProxy( 1017): applying state to connected service
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/Timeline( 3110): Timeline: Activity_launch_request id:com.wssyncmldm time:52240
,E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,V/GLSActivity( 1821): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
E/SMD     (  289): DCD OFF
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7,
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1017): Focused application set to: xxxx
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1821): No location to return for getLastLocation()
,W/FusedLocationProvider( 1821): location=null
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,E/Zygote  ( 4873): MountEmulatedStorage()
I/libpersona( 4873): KNOX_SDCARD checking this for 10023
E/Zygote  ( 4873): v2
I/libpersona( 4873): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4873 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/SELinux ( 4873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 4873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/ActivityManager( 1017): post active user change for 0 fullscreen false record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): Target Activity is not fullscreen. We will not show this activity0
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/TimaKeyStoreProvider( 4873): TimaSignature is unavailable
,D/ActivityThread( 4873): Added TimaKeyStore provider
,D/SensorService( 1017): [SO] -0.421 0.172 9.902
D/SensorService( 1017): [SO] -0.421 0.172 9.902
D/SensorService( 1017): [SO] [100 -> 255]
,I/ActivityManager( 1017): Killing 4014:com.test.thalitest/u0a167 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 23
,I/OMACP   ( 4873): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/PhoneWindow( 3110): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3110): *FMB* installDecor flags : -2139029248
,D/Mms/Omacp( 4786): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4873): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1821): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,E/Zygote  ( 4891): MountEmulatedStorage()
E/Zygote  ( 4891): v2
I/libpersona( 4891): KNOX_SDCARD checking this for 1000
I/libpersona( 4891): KNOX_SDCARD not a persona
,I/SELinux ( 4891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/libprocessgroup( 1017): failed to open /acct/uid_10167/pid_4014/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4891 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4891): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/Mms/Contact( 4786): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4786): performUpdate:widgetCount=0
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/ValidateNoPeople( 1017): mEvictionCount: 0
,D/Mms/ContactsCache( 4786): [start]    invalidate() consume time = 632.468438
,D/Mms/ContactsCache( 4786): [end]    invalidate() consume time = 0.419948
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/TimaKeyStoreProvider( 4891): TimaSignature is unavailable
,D/ActivityThread( 4891): Added TimaKeyStore provider
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1172): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,E/MTPRx   ( 4891): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1017): mCursor = null
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,V/MTPRx   ( 4891): sealedState: false
V/MTPRx   ( 4891): sealedUsbMassStorageState: false
E/MTPRx   ( 4891): check value of boot_completed is1
E/MTPRx   ( 4891): check booting is completed_sys.boot_completed
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,E/MTPRx   ( 4891): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4891): Status for mount/Unmount :removed
E/MTPRx   ( 4891): SDcard is not available
,W/MTPRx   ( 4891): value of connected istrue
W/MTPRx   ( 4891): value of configured istrue
W/MTPRx   ( 4891): value of mtpEnabled istrue
W/MTPRx   ( 4891): value of ptpEnabled isfalse
,E/MTPRx   ( 4891): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4891): mFirstTime: false
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,D/        ( 4891): MTP: reading debug level property
,E/MTPJNIInterface( 4891): Getting CryptionKey from JAVA
I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,E/MTPRx   ( 4891): currentUserId is 0
,E/MTPRx   ( 4891): Start observing USB_STATE_MATCH 
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,E/MTPRx   ( 4891): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4891): is_Privatemode is NOT 1
,D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
,D/SettingsProvider( 1017): name = boot_time_connected
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,E/MTPRx   ( 4891): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4891): noti = 17
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,D/SecContentProvider( 1017): uri = 18 selection = isUsbMediaPlayerAvailable
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
,E/MTPRx   ( 4891): sending MTP_ICON_ENABLED to stack
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0,
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 23
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,I/DBG_DM  ( 3110): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,E/MTPRx   ( 4891): else part ... so first time!!!
E/MTPPlaObsrvr( 4891): inside setContext()
E/MTPPlaObsrvr( 4891):  inside createplafiles
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/DBG_DM  ( 3110): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
E/MTPPlaObsrvr( 4891): playlist count is0
E/MTPPlaObsrvr( 4891):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4891):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4891): Inside registerContentObserver
,E/MtpAdbObserver( 4891): inside setContext()
,E/MtpAdbObserver( 4891): Inside registerContentObserver
W/Settings( 4891): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/SettingsProvider( 1017): name = mtp_running_status
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MtpService( 4891): onCreate.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,V/MtpMediaDBManager( 4891): inside deleteAllDB
,E/MtpService( 4891): < MTP > Registering BroadCast receiver :::::
,D/MtpService( 1229): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4891): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/Zygote  ( 4911): MountEmulatedStorage()
E/Zygote  ( 4911): v2
I/libpersona( 4911): KNOX_SDCARD checking this for 1000
I/libpersona( 4911): KNOX_SDCARD not a persona
I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/SELinux ( 4911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/MtpMediaDBManager( 4891): inside Thread updateDB
,I/SELinux ( 4911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4911): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/ActivityManager( 1017): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4911 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/MtpService( 4891): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
I/DBG_DM  ( 3110): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,E/MtpMediaDBManager( 4891): count : 26
I/DBG_DM  ( 3110): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
E/MtpService( 4891): onStartCommand.
W/MTPRx   ( 4891): calling native method
E/MTPJNIInterface( 4891): < MTP > Registering BroadCast receiver :::::
I/DBG_DM  ( 3110): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
E/MtpService( 4891): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,I/DBG_DM  ( 3110): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,E/MTPJNIInterface( 4891): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4891): noti = 10
,E/MtpService( 4891): onStartCommand.
W/MTPRx   ( 4891): calling native method
E/MTPRx   ( 4891): Checking the driver time out
E/MTPJNIInterface( 4891): noti = 2
D/        ( 4891): deleting sockets before message queue initialization
,D/        ( 4891): event handler thread is created, so set the flag
,E/MTPRx   ( 4891): called native method
E/MTPJNIInterface( 4891): setting Media scanner status0
E/MTPJNIInterface( 4891): After setting Media scanner status0
,W/MTPRx   ( 4891): notification from stack 1
E/MtpService( 4891): handleMessage. msg= { when=-6ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/        ( 4891): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594],
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/MTPJNIInterface( 4891): Getting media scanner status0
D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
E/MTPJNIInterface( 4891): DeviceName is Thali Test (Galaxy A3)
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/OpenGLRenderer( 3110): Render dirty regions requested: true
,D/TimaKeyStoreProvider( 4911): TimaSignature is unavailable
,D/ActivityThread( 4911): Added TimaKeyStore provider
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,W/MtpMediaDBManager( 4891): sending db update complete noti to stack
E/MTPJNIInterface( 4891): noti = 29
,D/PhoneWindow( 3110): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3110): *FMB* isFloatingMenuEnabled return false
,E/MTPJNIInterface( 4891): Status for mount/Unmount :removed
E/MTPJNIInterface( 4891): SDcard is not available
,E/        ( 4891): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/DBG_POLICYDM( 4554): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/MTPJNIInterface( 4891): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4891): SDcard is not available
,E/SQLiteLog( 4891): (21) API call with NULL database connection pointer
E/SQLiteLog( 4891): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4891): (21) API call with NULL database connection pointer
E/SQLiteLog( 4891): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4891): (21) API call with NULL database connection pointer
E/SQLiteLog( 4891): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4891): (21) API call with NULL database connection pointer
E/SQLiteLog( 4891): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4891): notification from stack 2
,D/        ( 4891): [mtp_init_device] Library open with 32 bits.
,D/        ( 4891): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4891): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=404, YUIInstallC
,D/        ( 4891): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4891):  [sua_support_present:1287] returning false 
D/        ( 4891): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams

```
