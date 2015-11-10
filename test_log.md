#### Test 50242285e222b78 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50242285e222b78/serverApp/index.js',
  '{"devices":{"ios":4,"android":18,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 18, cancel: 1 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
STOP log received from  03157df360a1882a Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-T232: 
--------- beginning of /dev/log/system
I/ActivityManager( 1195): rtcc_minfree = 82449,70671,58892,47114,35335
I/ActivityManager( 1195): Config changes=1df8 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h961dp 213dpi lrg port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
I/ActivityManager( 1195): Config changes=408 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port ?uimode ?night finger -keyb/v/h -nav/h s.3}
I/ActivityManager( 1195): System now ready
I/ActivityManager( 1195): Config changes=200 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port finger -keyb/v/h -nav/h s.4}
I/ActivityManager( 1195): !@ mBooting is set true!
I/ActivityManager( 1195): RTCC_TRIGGER_MSG, ASYNC.
W/ActivityManager( 1195): mDVFSHelper.release()
E/ActivityThread( 1576): Failed to find provider info for com.samsung.helphub.provider
W/ActivityManager( 1195): Unable to start service Intent { cmp=com.samsung.android.app.gestureservice/.GestureService } U=0: not found
W/ActivityManager( 1195): !@call fb1: post finishBooting() with 1000msec delay
I/ActivityManager( 1195): !@Boot: bootcomplete
W/ActivityThread( 3152): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityThread( 3192): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1195): Killing 2652:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2721:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 1608:com.android.printspooler/u0a118 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2637:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2895:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2911:com.samsung.android.app.memo/u0a130 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2925:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3002:com.sec.phone/u0a127 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3060:com.google.android.configupdater/u0a2 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3090:com.sec.android.widgetapp.samsungapps/u0a120 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3137:com.sec.dsm.system/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3152:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3192:com.sec.factory/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3207:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3241:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 1496:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3258:com.android.onetimeinitializer/u0a21 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3273:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3301:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3317:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
W/ActivityManager( 1195): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1195): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1195): Killing 3331:com.osp.app.signin/u0a30 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2938:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2569:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 1636:com.android.settings/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3369:com.wssyncmldm/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2556:com.google.android.partnersetup/u0a11 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{427e7e90 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1195): Killing 3392:com.google.android.googlequicksearchbox:search/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{42828240 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/ActivityManager( 1195): Killing 3436:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3421:com.samsung.android.intelligenceservice/u0a52 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3466:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1195): Process com.samsung.android.MtpApplication (pid 4156) (adj 0) has died.
I/ActivityManager( 1195): Killing 3480:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3494:com.wssnps/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3507:com.samsung.android.app.accesscontrol/u0a57 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{42968fa0 u0 com.samsung.android.providers.context/.ContextService}
I/ActivityManager( 1195): Killing 3525:com.sec.android.app.FileShareServer/u0a62 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3540:com.sec.android.nearby.mediaserver/u0a63 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3555:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
W/ActivityThread( 4143): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityManager( 1195): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
I/ActivityManager( 1195): Killing 3570:com.sec.android.app.bluetoothtest/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3583:com.blurb.checkout/u0a67 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{42958ce0 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{424e53f0 u0 com.sec.esdk.elm/.service.ElmAgentService}
I/ActivityManager( 1195): Process com.sec.android.app.sysscope (pid 3936) (adj 0) has died.
I/ActivityManager( 1195): Process com.sec.factory (pid 4143) (adj 0) has died.
I/ActivityManager( 1195): Killing 3596:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3611:com.dropbox.android/u0a78 (adj 15): bgCount ##33
W/ActivityThread( 4514): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1195): Killing 3655:com.sec.factory.camera/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3669:com.samsung.android.app.watchmanagerstub/u0a86 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3741:com.samsung.scrc.idi.server/u0a91 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{428dd8a8 u0 com.android.exchange/.ExchangeService}
I/ActivityManager( 1195): Killing 3755:com.samsung.helphub/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{4299cd08 u0 com.android.exchange/.service.ExchangeBroadcastProcessorService}
I/ActivityManager( 1195): Killing 3768:com.LocalFota/u0a92 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3785:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3814:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{42829bb0 u0 com.rxnetworks.rxnservicesxybrid/com.rxnetworks.rxnserviceslib.RXNetworksService}
I/ActivityManager( 1195): Killing 3838:com.sec.android.app.camera/u0a121 (adj 15): bgCount ##33
W/ActivityManager( 1195): mDVFSHelper.acquire()
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{428ecf60 u0 com.samsung.android.MtpApplication/.MtpService}
W/ActivityManager( 1195): mDVFSHelper.release()
E/ActivityThread( 3124): Activity com.gameloft.android.gdc.StartActivity has leaked IntentReceiver hj@41d5d5c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3124): android.app.IntentReceiverLeaked: Activity com.gameloft.android.gdc.StartActivity has leaked IntentReceiver hj@41d5d5c0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3124): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:809)
E/ActivityThread( 3124): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:610)
E/ActivityThread( 3124): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1816)
E/ActivityThread( 3124): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1796)
E/ActivityThread( 3124): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1790)
E/ActivityThread( 3124): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:479)
E/ActivityThread( 3124): 	at hj.b(Unknown Source)
E/ActivityThread( 3124): 	at hj.a(Unknown Source)
E/ActivityThread( 3124): 	at hm.a(Unknown Source)
E/ActivityThread( 3124): 	at hi.run(Unknown Source)
E/ActivityThread( 3124): 	at java.lang.Thread.run(Thread.java:841)
I/ActivityManager( 1195): Killing 1775:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3908:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3921:com.sec.android.app.worldclock/u0a135 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3949:com.sec.android.app.controlpanel/u0a141 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3963:com.samsung.android.service.travel/u0a143 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3979:com.google.android.youtube/u0a146 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4044:com.gameloft.android.gdc:remote/u0a152 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4269:com.sec.spp.push:RemoteDlcProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4285:com.sec.spp.push:RemoteNotiProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4321:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3711:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4195:com.sec.android.widgetapp.SPlannerAppWidget/u0a34 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4224:com.android.calendar/u0a117 (adj 15): bgCount ##33
W/ActivityManager( 1195): mDVFSHelper.acquire()
W/ActivityManager( 1195): mDVFSHelper.release()
,--------- beginning of /dev/log/main
W/ActivityManager( 1195): mDVFSHelper.acquire()
W/ActivityManager( 1195): mDVFSHelper.release()
,W/jxcore-log( 4923): Initializing JXcore engine
W/jxcore-log( 4923): JXcore engine is ready
W/jxcore-log( 4923): Starting JXcore engine
W/jxcore-log( 4923): Platform android
W/jxcore-log( 4923): 
W/jxcore-log( 4923): Process ARCH arm
W/jxcore-log( 4923): 
I/jxcore-log( 4923): JXcore Cordova bridge is ready!
I/jxcore-log( 4923): 
W/jxcore-log( 4923): JXcore engine is started
E/jxcore-log( 4923): >> samsung-SM-T232
E/jxcore-log( 4923): 
I/jxcore-log( 4923): Total memory 1352024064
I/jxcore-log( 4923): 
I/jxcore-log( 4923): Free memory 214986752
I/jxcore-log( 4923): 
I/jxcore-log( 4923): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4923): 
I/jxcore-log( 4923): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4923): 
I/jxcore-log( 4923): userPath [ 'www' ]
I/jxcore-log( 4923): 
I/jxcore-log( 4923): Size 800 1280
I/jxcore-log( 4923): 
I/jxcore-log( 4923): Screen Brightness 143
I/jxcore-log( 4923): 
E/jxcore-log( 4923): Dummy Error Log.
E/jxcore-log( 4923): 
I/jxcore-log( 4923): getBuffer is called!!!!
I/jxcore-log( 4923): 
,I/jxcore-log( 4923): ****TEST TOOK:  5110  ms ****
I/jxcore-log( 4923): 
,I/jxcore-log( 4923): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4923): 
,I/ActivityManager( 1195): Killing 4923:com.example.hello/u0a357 (adj 0): stop com.example.hello


samsung-SM-G920F: 
--------- beginning of system
W/ActivityManager( 3488): mDVFSHelper.release()
--------- beginning of main
,I/ActivityManager( 3488): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3488): mDVFSHelper.acquire()
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3488): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9768 uid=10433 gids={50433, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 9768): Added TimaKeyStore provider
V/ActivityThread( 4254): updateVisibility : ActivityRecord{336a2982 token=android.os.BinderProxy@dc563e9 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,W/ActivityManager( 3488): Activity pause timeout for ActivityRecord{4930c7e u0 com.example.hello/.MainActivity t44}
,D/ActivityManager( 3488): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 9768): updateVisibility : ActivityRecord{6593258 token=android.os.BinderProxy@287bf4c2 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 3488): Displayed Component not be shown by security: +954ms
,W/ActivityManager( 3488): mDVFSHelper.release()
,W/jxcore-log( 9768): Initializing JXcore engine
W/jxcore-log( 9768): JXcore engine is ready
,W/jxcore-log( 9768): Starting JXcore engine
,W/jxcore-log( 9768): Platform android
W/jxcore-log( 9768): 
W/jxcore-log( 9768): Process ARCH arm
W/jxcore-log( 9768): 
,I/jxcore-log( 9768): JXcore Cordova bridge is ready!
I/jxcore-log( 9768): 
W/jxcore-log( 9768): JXcore engine is started
,E/jxcore-log( 9768): >> samsung-SM-G920F
E/jxcore-log( 9768): 
,I/jxcore-log( 9768): Total memory 2829074432
I/jxcore-log( 9768): 
I/jxcore-log( 9768): Free memory 49336320
I/jxcore-log( 9768): 
I/jxcore-log( 9768): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9768): 
I/jxcore-log( 9768): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9768): 
,I/jxcore-log( 9768): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9768): 
,I/jxcore-log( 9768): Size 1440 2560
I/jxcore-log( 9768): 
,I/jxcore-log( 9768): Screen Brightness 134
I/jxcore-log( 9768): 
E/jxcore-log( 9768): Dummy Error Log.
E/jxcore-log( 9768): 
,I/jxcore-log( 9768): getBuffer is called!!!!
I/jxcore-log( 9768): 
,I/jxcore-log( 9768): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 9768): 
,I/jxcore-log( 9768): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9768): 
,I/ActivityManager( 3488): Force stopping com.example.hello appid=10433 user=-1: uninstall pkg
,I/ActivityManager( 3488): Killing 9768:com.example.hello/u0a433 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3488):   Force finishing activity ActivityRecord{4930c7e u0 com.example.hello/.MainActivity t44}
,I/ActivityManager( 3488): Force stopping com.example.hello appid=10433 user=0: pkg removed
,W/ActivityManager( 3488): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3488): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9901 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/ActivityManager( 3488): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityThread( 9901): Added TimaKeyStore provider
,D/ActivityManager( 3488): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3488): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5240, uid=10127 that is not exported from uid 10125
,W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 3488): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,I/ActivityManager( 3488): Killing 9191:com.samsung.android.coreapps/u0a98 (adj 15): empty #25
,D/ActivityManager( 3488): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
,W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3488): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9923 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,D/ActivityThread( 9923): Added TimaKeyStore provider
,D/ActivityManager( 3488): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3488): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,I/ActivityManager( 3488): Killing 9172:com.android.mms/u0a48 (adj 15): empty #25
,D/ActivityThread( 9941): Added TimaKeyStore provider


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
,I/ActivityManager( 3029): Displayed com.example.hello/.MainActivity: +830ms (total +910ms)
W/jxcore-log( 6702): Initializing JXcore engine
W/jxcore-log( 6702): JXcore engine is ready
W/jxcore-log( 6702): Starting JXcore engine
W/jxcore-log( 6702): Platform android
W/jxcore-log( 6702): 
W/jxcore-log( 6702): Process ARCH arm
W/jxcore-log( 6702): 
I/jxcore-log( 6702): JXcore Cordova bridge is ready!
I/jxcore-log( 6702): 
W/jxcore-log( 6702): JXcore engine is started
E/jxcore-log( 6702): >> HUAWEI-ALE-L21
E/jxcore-log( 6702): 
I/jxcore-log( 6702): Total memory 1949741056
I/jxcore-log( 6702): 
I/jxcore-log( 6702): Free memory 48713728
I/jxcore-log( 6702): 
I/jxcore-log( 6702): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6702): 
I/jxcore-log( 6702): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6702): 
I/jxcore-log( 6702): userPath [ 'www' ]
I/jxcore-log( 6702): 
I/jxcore-log( 6702): Size 720 1184
I/jxcore-log( 6702): 
I/jxcore-log( 6702): Screen Brightness 242
I/jxcore-log( 6702): 
E/jxcore-log( 6702): Dummy Error Log.
E/jxcore-log( 6702): 
,I/jxcore-log( 6702): getBuffer is called!!!!
I/jxcore-log( 6702): 
,I/jxcore-log( 6702): ****TEST TOOK:  5097  ms ****
I/jxcore-log( 6702): 
,I/jxcore-log( 6702): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6702): 
,I/ActivityManager( 3029): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 3029): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1280): Start proc 8256:com.android.contacts/u0a18 for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver
I/ActivityManager( 1280): Start proc 8284:com.lge.email/u0a56 for broadcast com.lge.email/.receiver.EmailSimChangedReceiver
I/ActivityManager( 1280): Killing 7388:com.lge.lockscreensettings/1000 (adj 15): empty #22
I/ActivityManager( 1280): Killing 7410:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #22
I/ActivityManager( 1280): Start proc 8310:com.android.settings/1000 for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver
I/ActivityManager( 1280): Killing 7432:com.lge.ia.task.incalagent/u0a8 (adj 15): empty #22
I/ActivityManager( 1280): Start proc 8334:com.lge.hiddenmenu/1000 for broadcast com.lge.hiddenmenu/.SVC.log_service.FactorySIMReceiver
I/ActivityManager( 1280): Start proc 8354:com.android.providers.partnerbookmarks/u0a103 for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver
I/ActivityManager( 1280): Killing 7452:com.android.providers.calendar/u0a19 (adj 15): empty #22
I/ActivityManager( 1280): Killing 7473:com.google.android.gm/u0a113 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 8377:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseSIMObserver
I/ActivityManager( 1280): Start proc 8398:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
I/ActivityManager( 1280): Killing 7514:com.google.android.apps.maps/u0a119 (adj 15): empty #22
I/ActivityManager( 1280): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1280): setTaskToReturnTo : TaskRecord{25928c9a #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1280): setTaskToReturnTo : TaskRecord{25928c9a #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1280): Start proc 8436:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1280): Killing 7556:com.google.android.youtube/u0a124 (adj 15): empty #22
I/ActivityManager( 1280): Waited long enough for: ServiceRecord{36f566b4 u0 com.lge.springcleaning/.service.AppCleanupService}
I/ActivityManager( 1280): Start proc 8480:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
I/ActivityManager( 1280): Start proc 8500:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
I/ActivityManager( 1280): Start proc 8528:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.lockscreen.QuickUnlockReceiver
I/ActivityManager( 1280): Start proc 8557:com.lge.qremote/u0a138 for broadcast com.lge.qremote/.settings.WiFiStateReceiver
I/ActivityManager( 1280): Killing 7680:com.android.vending/u0a62 (adj 15): empty #22
I/ActivityManager( 1280): Killing 7724:com.google.android.talk/u0a121 (adj 15): empty #22
I/ActivityManager( 1280): Displayed com.example.hello/.MainActivity: +818ms (total +19s783ms)
I/ActivityManager( 1280): Killing 7758:com.google.android.googlequicksearchbox:search/u0a63 (adj 15): empty #22
W/jxcore-log( 8436): Initializing JXcore engine
W/jxcore-log( 8436): JXcore engine is ready
W/jxcore-log( 8436): Starting JXcore engine
W/jxcore-log( 8436): Platform android
W/jxcore-log( 8436): 
W/jxcore-log( 8436): Process ARCH arm
W/jxcore-log( 8436): 
I/jxcore-log( 8436): JXcore Cordova bridge is ready!
I/jxcore-log( 8436): 
W/jxcore-log( 8436): JXcore engine is started
E/jxcore-log( 8436): >> LGE-LG-H815
E/jxcore-log( 8436): 
I/jxcore-log( 8436): Total memory 2968948736
I/jxcore-log( 8436): 
I/jxcore-log( 8436): Free memory 120274944
I/jxcore-log( 8436): 
I/jxcore-log( 8436): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8436): 
I/jxcore-log( 8436): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8436): 
I/jxcore-log( 8436): userPath [ 'www' ]
I/jxcore-log( 8436): 
I/jxcore-log( 8436): Size 1440 2392
I/jxcore-log( 8436): 
I/jxcore-log( 8436): Screen Brightness 255
I/jxcore-log( 8436): 
E/jxcore-log( 8436): Dummy Error Log.
E/jxcore-log( 8436): 
I/ActivityManager( 1280): Start proc 8580:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
I/ActivityManager( 1280): Start proc 8608:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
I/ActivityManager( 1280): Killing 7931:com.lge.qmemoplus/1000 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 8637:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Killing 7953:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 7994:com.lge.lgaccount/u0a107 (adj 15): empty #22
,I/jxcore-log( 8436): getBuffer is called!!!!
I/jxcore-log( 8436): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Killing 8037:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Killing 8160:com.android.browser/u0a24 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 8692:com.lge.sync/1000 for broadcast com.lge.sync/.StartReceiver
,I/ActivityManager( 1280): Killing 8185:com.lge.appbox.client:SingleBinaryService/u0a9 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 8713:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
,I/ActivityManager( 1280): Killing 8205:com.lge.appbox.client/u0a9 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 8739:com.lge.bnr/1000 for broadcast com.lge.bnr/.receiver.DamagedFileRemover
,I/ActivityManager( 1280): Start proc 8759:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager( 1280): Killing 7793:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 8789:com.lge.cic.eden.service/u0a7 for broadcast com.lge.cic.eden.service/com.lge.cic.eden.receiver.EdenBroadcastReceiver
,I/ActivityManager( 1280): Start proc 8812:com.lge.clock/u0a16 for broadcast com.lge.clock/.alarmclock.ToneMappingReceiver
,I/ActivityManager( 1280): Killing 8230:com.android.cellbroadcastreceiver/u0a14 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 8256:com.android.contacts/u0a18 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 8284:com.lge.email/u0a56 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 8836:com.android.gallery3d/u0a55 for broadcast com.android.gallery3d/com.lge.gallery.app.GalleryGlobalReceiver
,I/ActivityManager( 1280): Killing 8334:com.lge.hiddenmenu/1000 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 8864:com.lge.sizechangable.weather/u0a136 for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 8889:com.lge.sizechangable.weather.platform/u0a96 for broadcast com.lge.sizechangable.weather.platform/.receiver.WeatherPlatformCommonReceiver
,I/ActivityManager( 1280): Killing 8354:com.android.providers.partnerbookmarks/u0a103 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 8377:com.lge.eula/u0a105 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 8910:com.lge.myplace/u0a30 for broadcast com.lge.myplace/.Receiver
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Killing 7974:com.lge.lifetracker/u0a137 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 8528:com.lge.lockscreensettings/1000 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 8436): ****TEST TOOK:  5252  ms ****
I/jxcore-log( 8436): 
I/jxcore-log( 8436): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8436): 
,I/ActivityManager( 1280): Start proc 8933:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,D/ActivityThread( 8933): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1280): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1280): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1280): Killing 8017:com.lge.lgdmsclient/1000 (adj 15): empty #22
,I/ActivityManager( 1280): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
I/ActivityManager( 1280): Killing 8436:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1280): Force removing ActivityRecord{3f58f9cb u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1280): Force stopping com.example.hello appid=10360 user=0: pkg removed,
,W/ActivityManager( 1280): Spurious death for ProcessRecord{492679a 8436:com.example.hello/u0a360}, curProc for 8436: null
,I/ActivityManager( 1280): Start proc 9002:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1280): Displayed com.lge.launcher2/.Launcher: +265ms (total +25s306ms)
,I/ActivityManager( 1280): Killing 8637:com.lge.ia.task.smartsetting/u0a21 (adj 15): empty #22


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  996): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=4180 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ActivityThread( 4180): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  996): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  996): setTaskToReturnTo : TaskRecord{3ef63870 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  996): setTaskToReturnTo : TaskRecord{3ef63870 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  996): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4237 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  996): Waited long enough for: ServiceRecord{52b1617 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  996): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4338 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  996): Displayed com.example.hello/.MainActivity: +1s339ms
,W/jxcore-log( 4237): Initializing JXcore engine
W/jxcore-log( 4237): JXcore engine is ready
,W/jxcore-log( 4237): Starting JXcore engine
,I/ActivityManager(  996): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4381 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  996): Killing 3933:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/jxcore-log( 4237): Platform android
W/jxcore-log( 4237): 
W/jxcore-log( 4237): Process ARCH arm
W/jxcore-log( 4237): 
,I/jxcore-log( 4237): JXcore Cordova bridge is ready!
I/jxcore-log( 4237): 
W/jxcore-log( 4237): JXcore engine is started
,E/jxcore-log( 4237): >> LGE-LG-D722
E/jxcore-log( 4237): 
I/jxcore-log( 4237): Total memory 906309632
I/jxcore-log( 4237): 
,I/jxcore-log( 4237): Free memory 20561920
I/jxcore-log( 4237): 
I/jxcore-log( 4237): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4237): 
I/jxcore-log( 4237): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4237): 
I/jxcore-log( 4237): userPath [ 'www' ]
I/jxcore-log( 4237): 
I/jxcore-log( 4237): Size 720 1196
I/jxcore-log( 4237): 
,I/jxcore-log( 4237): Screen Brightness 255
I/jxcore-log( 4237): 
E/jxcore-log( 4237): Dummy Error Log.
E/jxcore-log( 4237): 
,I/ActivityManager(  996): Process com.lge.cloudhub (pid 3959) has died
,I/jxcore-log( 4237): getBuffer is called!!!!
I/jxcore-log( 4237): 
,I/ActivityManager(  996): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4470 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  996): Process com.android.providers.calendar (pid 4060) has died
,W/ActivityManager(  996): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  996): Process com.lge.hiddenmenu (pid 4039) has died
,W/ActivityManager(  996): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  996): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  996): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  996): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  996): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4470): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@214d68a4 that was originally bound here
E/ActivityThread( 4470): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@214d68a4 that was originally bound here
E/ActivityThread( 4470): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4470): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4470): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4470): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4470): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4470): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4470): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4470): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4470): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4470): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4470): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4470): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4470): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4470): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4470): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  996): Unbind failed: could not find connection for android.os.BinderProxy@675244
I/ActivityManager(  996): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4517 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  996): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4550 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  996): Process com.lge.lockscreensettings (pid 4077) has died
,I/ActivityManager(  996): Waited long enough for: ServiceRecord{731f80 u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager(  996): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4616 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  996): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4645 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  996): Killing 3978:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,I/ActivityManager(  996): Process com.google.android.talk (pid 4338) has died
,I/ActivityManager(  996): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4669 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  996): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4691 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  996): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4724 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  996): Process com.google.android.youtube (pid 4381) has died
,D/ActivityManager(  996): enqueue in BackgroundQueue #69 Intent=Intent { act=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION flg=0x14 (has extras) }
,I/ActivityManager(  996): Killing 4002:com.lge.lgfota.permission/1000 (adj 15): empty #11
,I/ActivityManager(  996): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4753 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  996): Killing 4096:com.lge.springcleaning/1000 (adj 15): empty #11
,I/ActivityManager(  996): Killing 4130:com.google.android.configupdater/u0a3 (adj 15): empty #11
,I/jxcore-log( 4237): ****TEST TOOK:  5086  ms ****
I/jxcore-log( 4237): 
I/jxcore-log( 4237): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4237): 
,I/ActivityManager(  996): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4812 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  996): Killing 4160:com.lge.eula/1000 (adj 15): empty #11
,I/ActivityManager(  996): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4845 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  996): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  996): Killing 4237:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  996): Force removing ActivityRecord{2aa857e9 u0 com.example.hello/.MainActivity t219}: app died, no saved state
,W/ActivityManager(  996): Spurious death for ProcessRecord{14b29f00 4237:com.example.hello/u0a30}, curProc for 4237: null
,I/ActivityManager(  996): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  996): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4866 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  996): Process com.android.bluetooth (pid 2026) has died
W/ActivityManager(  996): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
W/ActivityManager(  996): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,I/ActivityManager(  996): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4896 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,I/ActivityManager(  996): Killing 4470:com.google.android.gm/u0a53 (adj 15): empty #11
,I/ActivityManager(  996): Waited long enough for: ServiceRecord{1bc62753 u0 com.lge.mlt/.MltMonitorService}
,I/ActivityManager(  996): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4928 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  996): Killing 4550:com.android.vending/u0a36 (adj 15): empty #11


LGE-Nexus 5: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  758): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2020 uid=10012 gids={50012, 9997} abi=armeabi-v7a
I/ActivityManager(  758): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2046 uid=10014 gids={50014, 9997, 1028, 3003} abi=armeabi-v7a
I/ActivityManager(  758): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=2074 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2127 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  758): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2175 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  758): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2234 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): Displayed com.example.hello/.MainActivity: +1s577ms (total +18s686ms)
,W/jxcore-log( 2127): Initializing JXcore engine
W/jxcore-log( 2127): JXcore engine is ready
,W/jxcore-log( 2127): Starting JXcore engine
,I/ActivityManager(  758): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2262 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/jxcore-log( 2127): Platform android
W/jxcore-log( 2127): 
,W/jxcore-log( 2127): Process ARCH arm
W/jxcore-log( 2127): 
,I/jxcore-log( 2127): JXcore Cordova bridge is ready!
I/jxcore-log( 2127): 
W/jxcore-log( 2127): JXcore engine is started
,E/jxcore-log( 2127): >> LGE-Nexus 5
E/jxcore-log( 2127): 
,I/jxcore-log( 2127): Total memory 1946181632
I/jxcore-log( 2127): 
,I/jxcore-log( 2127): Free memory 514301952
I/jxcore-log( 2127): 
,I/jxcore-log( 2127): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2127): 
I/jxcore-log( 2127): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2127): 
,I/jxcore-log( 2127): userPath [ 'www' ]
I/jxcore-log( 2127): 
,I/jxcore-log( 2127): Size 1080 1776
I/jxcore-log( 2127): 
,I/jxcore-log( 2127): Screen Brightness 82
I/jxcore-log( 2127): 
E/jxcore-log( 2127): Dummy Error Log.
E/jxcore-log( 2127): 
,I/ActivityManager(  758): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2279 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  758): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2298 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 2127): getBuffer is called!!!!
I/jxcore-log( 2127): 
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2406 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  758): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2431 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 2431): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  758): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2465 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2495 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  758): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/ActivityManager(  758): Killing 1605:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  758): Killing 1257:com.android.printspooler/u0a72 (adj 15): empty #17
,I/ActivityManager(  758): Killing 1681:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,I/ActivityManager(  758): Killing 1919:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  758): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2605 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  758): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2625 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 1940:com.google.android.dialer/u0a10 (adj 15): empty #17
,I/jxcore-log( 2127): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 2127): 
I/jxcore-log( 2127): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2127): 
,I/ActivityManager(  758): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2675 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 2020:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,I/ActivityManager(  758): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 2127:com.example.hello/u0a277 (adj 0): stop com.example.hello
,W/ActivityManager(  758): Force removing ActivityRecord{34d62647 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  758): Spurious death for ProcessRecord{3fee110d 2127:com.example.hello/u0a277}, curProc for 2127: null
,I/ActivityManager(  758): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/ActivityManager(  758): Killing 2046:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,I/ActivityManager(  758): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2742 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 1984:com.android.providers.calendar/u0a2 (adj 15): empty #17
,I/ActivityManager(  758): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2764 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a


```

####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on 320414cd475f91e3 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/ActivityManager( 2382): mDVFSHelper.acquire()
D/ActivityThread( 6869): Added TimaKesytore provider
,W/ActivityManager( 2382): mDVFSHelper.release()
W/jxcore-log( 6869): Initializing JXcore engine
W/jxcore-log( 6869): JXcore engine is ready
W/jxcore-log( 6869): Starting JXcore engine
,W/jxcore-log( 6869): Platform android
W/jxcore-log( 6869): 
,W/jxcore-log( 6869): Process ARCH arm
W/jxcore-log( 6869): 
,I/jxcore-log( 6869): JXcore Cordova bridge is ready!
I/jxcore-log( 6869): 
,W/jxcore-log( 6869): JXcore engine is started
,E/jxcore-log( 6869): >> samsung-SM-G800F
E/jxcore-log( 6869): 
,I/jxcore-log( 6869): Total memory 1319530496
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): Free memory 36777984
I/jxcore-log( 6869): 
I/jxcore-log( 6869): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): Size 720 1280
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): Screen Brightness 134
I/jxcore-log( 6869): 
,E/jxcore-log( 6869): Dummy Error Log.
E/jxcore-log( 6869): 
,I/jxcore-log( 6869): getBuffer is called!!!!
I/jxcore-log( 6869): 
,I/ActivityManager( 2382): Killing 6383:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/jxcore-log( 6869): ****TEST TOOK:  5150  ms ****
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6869): 
,D/ActivityThread( 6938): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6869:com.example.hello/u0a396 (adj 0): stop com.example.hello
,W/ActivityManager( 2382): Force removing ActivityRecord{4241a8b0 u0 com.example.hello/.MainActivity t5}: app died, no saved state
,W/ActivityManager( 2382): mDVFSHelper.acquire()
,I/ActivityManager( 2382): Killing 6193:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,W/ActivityManager( 2382): mDVFSHelper.release()
,D/ActivityThread( 6977): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6473:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/ActivityThread( 6994): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6499:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/ActivityThread( 7006): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6332:com.sec.phone/1001 (adj 15): empty #43
,D/ActivityThread( 7018): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6068:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/ActivityThread( 7030): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6514:com.android.musicfx/u0a24 (adj 15): empty #43
,D/ActivityThread( 7068): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6542:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/ActivityThread( 7088): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 5956:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,I/ActivityManager( 2382): Killing 6572:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,D/ActivityThread( 7104): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6397:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/ActivityThread( 7118): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6600:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,D/ActivityThread( 7134): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6614:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/ActivityThread( 7148): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6626:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
D/ActivityThread( 7164): Added TimaKesytore provider
,I/ActivityManager( 2382): Killing 6639:com.samsung.helphub/1000 (adj 15): empty #43
,D/ActivityThread( 7179): Added TimaKesytore provider


motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3509
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3525 uid=10327 gids={50327, 3003, 3001, 3002}
,I/ActivityManager( 1020): Displayed com.example.hello/.MainActivity: +339ms (total +366ms)
,W/jxcore-log( 3525): Initializing JXcore engine
,W/jxcore-log( 3525): JXcore engine is ready
,W/jxcore-log( 3525): Starting JXcore engine
,W/jxcore-log( 3525): Platform android
W/jxcore-log( 3525): 
W/jxcore-log( 3525): Process ARCH arm
W/jxcore-log( 3525): 
I/jxcore-log( 3525): JXcore Cordova bridge is ready!
I/jxcore-log( 3525): 
W/jxcore-log( 3525): JXcore engine is started
E/jxcore-log( 3525): >> motorola-XT1039
E/jxcore-log( 3525): 
I/jxcore-log( 3525): Total memory 893136896
I/jxcore-log( 3525): 
I/jxcore-log( 3525): Free memory 33406976
I/jxcore-log( 3525): 
I/jxcore-log( 3525): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3525): 
I/jxcore-log( 3525): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3525): 
I/jxcore-log( 3525): userPath [ 'www' ]
I/jxcore-log( 3525): 
I/jxcore-log( 3525): Size 720 1184
I/jxcore-log( 3525): 
I/jxcore-log( 3525): Screen Brightness 10
I/jxcore-log( 3525): 
E/jxcore-log( 3525): Dummy Error Log.
E/jxcore-log( 3525): 
I/jxcore-log( 3525): getBuffer is called!!!!
I/jxcore-log( 3525): 
,I/jxcore-log( 3525): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 3525): 
I/jxcore-log( 3525): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3525): 
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10327 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 3525:com.example.hello/u0a327 (adj 0): stop com.example.hello
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{420432f0 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10327 user=0: pkg removed
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{420432f0 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1020): Duplicate finish request for ActivityRecord{420432f0 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3613 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3633 uid=10058 gids={50058}
,I/ActivityManager( 1020): Killing 3309:com.android.calendar/u0a7 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3653 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1020): Killing 3371:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1020): Killing 3332:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3669 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3094:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager( 1034): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{c1737ad #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{c1737ad #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1034): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5915 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1034): Display changed displayId=0
,W/ActivityManager( 1034): Activity pause timeout for ActivityRecord{35a79ae2 u0 com.example.hello/.MainActivity t2}
,I/ActivityManager( 1034): Displayed com.example.hello/.MainActivity: +651ms (total +773ms)
,W/jxcore-log( 5915): Initializing JXcore engine
,W/jxcore-log( 5915): JXcore engine is ready
,W/jxcore-log( 5915): Starting JXcore engine
,W/jxcore-log( 5915): Platform android
W/jxcore-log( 5915): 
,W/jxcore-log( 5915): Process ARCH arm
W/jxcore-log( 5915): 
,I/jxcore-log( 5915): JXcore Cordova bridge is ready!
I/jxcore-log( 5915): 
,W/jxcore-log( 5915): JXcore engine is started
,E/jxcore-log( 5915): >> LGE-LG-D855
E/jxcore-log( 5915): 
I/jxcore-log( 5915): Total memory 2995761152
I/jxcore-log( 5915): 
I/jxcore-log( 5915): Free memory 667594752
I/jxcore-log( 5915): 
I/jxcore-log( 5915): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5915): 
I/jxcore-log( 5915): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5915): 
,I/jxcore-log( 5915): userPath [ 'www' ]
I/jxcore-log( 5915): 
I/jxcore-log( 5915): Size 1440 2392
I/jxcore-log( 5915): 
I/jxcore-log( 5915): Screen Brightness 50
I/jxcore-log( 5915): 
E/jxcore-log( 5915): Dummy Error Log.
E/jxcore-log( 5915): 
I/jxcore-log( 5915): getBuffer is called!!!!
I/jxcore-log( 5915): 
,I/jxcore-log( 5915): ****TEST TOOK:  5061  ms ****
I/jxcore-log( 5915): 
I/jxcore-log( 5915): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5915): 
,I/ActivityManager( 1034): Killing 5307:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1034): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1034): Killing 5915:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1034):   Force finishing activity ActivityRecord{35a79ae2 u0 com.example.hello/.MainActivity t2}
,W/ActivityManager( 1034): Spurious death for ProcessRecord{22a798a8 5915:com.example.hello/u0a318}, curProc for 5915: null
I/ActivityManager( 1034): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1034):   Force finishing activity ActivityRecord{35a79ae2 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1034): Duplicate finish request for ActivityRecord{35a79ae2 u0 com.example.hello/.MainActivity t2 f}
,I/ActivityManager( 1034): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6041 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 4442:com.google.android.talk/u0a72 (adj 15): empty #17
,I/ActivityManager( 1034): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6066 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 6066): Failed to find provider info for com.lge.lgaccount.provider
,I/ActivityManager( 1034): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6088 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 5593:com.google.android.apps.plus/u0a97 (adj 15): empty #17


```

####Node name: thali05
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/50242285e222b78/build_android/android_0_50242285e222b78.apk) to device 1d6a772d - waiting for device -
rm: /data/local/tmp/android_0_50242285e222b78.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on FA55PYS00566 
Device test finished on 7970f88c 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6087 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 6087): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1019): mDVFSHelper.acquire()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6124 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6124): Added TimaKeyStore provider
V/ActivityManager( 1019): Display changed displayId=0
V/ActivityThread( 1476): updateVisibility : ActivityRecord{1c1edd69 token=android.os.BinderProxy@19a56bce {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4971:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{2dd1ee8 u0 com.example.hello/.MainActivity t19}
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 6124): updateVisibility : ActivityRecord{3dbc2a54 token=android.os.BinderProxy@30c45e66 {com.example.hello/com.example.hello.MainActivity}} show : true,
,I/ActivityManager( 1019): Displayed Component not be shown by security: +692ms (total +780ms)
,W/ActivityManager( 1019): mDVFSHelper.release()
,W/jxcore-log( 6124): Initializing JXcore engine
W/jxcore-log( 6124): JXcore engine is ready
,W/jxcore-log( 6124): Starting JXcore engine
,W/jxcore-log( 6124): Platform android
W/jxcore-log( 6124): 
W/jxcore-log( 6124): Process ARCH arm
W/jxcore-log( 6124): 
,I/jxcore-log( 6124): JXcore Cordova bridge is ready!,
I/jxcore-log( 6124): 
W/jxcore-log( 6124): JXcore engine is started
,E/jxcore-log( 6124): >> samsung-SM-A300FU
E/jxcore-log( 6124): 
,I/jxcore-log( 6124): Total memory 1451114496
I/jxcore-log( 6124): 
,I/jxcore-log( 6124): Free memory 22241280
I/jxcore-log( 6124): 
I/jxcore-log( 6124): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6124): 
I/jxcore-log( 6124): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6124): 
,I/jxcore-log( 6124): userPath [ 'www' ]
I/jxcore-log( 6124): 
,I/jxcore-log( 6124): Size 540 960
I/jxcore-log( 6124): 
,I/jxcore-log( 6124): Screen Brightness 160
I/jxcore-log( 6124): 
E/jxcore-log( 6124): Dummy Error Log.
E/jxcore-log( 6124): 
,I/jxcore-log( 6124): getBuffer is called!!!!
I/jxcore-log( 6124): 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/jxcore-log( 6124): ****TEST TOOK:  5086  ms ****
I/jxcore-log( 6124): 
,I/jxcore-log( 6124): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6124): 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6186 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/ActivityThread( 6186): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 5256:com.google.android.gm/u0a99 (adj 15): empty #31
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 6124:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{2dd1ee8 u0 com.example.hello/.MainActivity t19}
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6222 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityThread( 6222): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/ActivityManager( 1019): Process com.android.bluetooth (pid 2659)(adj 0) has died(71,702)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6259 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,D/ActivityThread( 6259): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6276 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6288 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 6276): Added TimaKeyStore provider
,D/ActivityThread( 6288): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6307 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a


HTC-HTC One M8s: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  960): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4997 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
I/ActivityManager(  960): Killing 4437:com.google.android.youtube/u0a176 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4437
I/ActivityManager(  960): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  960): Killing 4520:com.google.android.gm/u0a106 (adj 15): empty #17
I/ActivityManager(  960): Recipient 4520
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5020 on display 0
I/ActivityManager(  960): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5074 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  960): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5097 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  960): Killing 3783:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 3783
I/ActivityManager(  960): Killing 4562:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
I/ActivityManager(  960): Recipient 4562
I/ActivityManager(  960): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=5139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  960): Killing 4704:com.htc.showme/u0a81 (adj 15): empty #17
I/ActivityManager(  960): Recipient 4704
I/ActivityManager(  960): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5169 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/ActivityManager(  960): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5200 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
I/ActivityManager(  960): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5222 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  960): Displayed com.example.hello/.MainActivity: +1s423ms
I/ActivityManager(  960): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5257 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  960): Killing 4738:com.htc.sense.browser/u0a9 (adj 15): empty #17
W/jxcore-log( 5074): Initializing JXcore engine
W/jxcore-log( 5074): JXcore engine is ready
W/jxcore-log( 5074): Starting JXcore engine
I/ActivityManager(  960): Recipient 4738
,W/jxcore-log( 5074): Platform android
W/jxcore-log( 5074): 
,W/jxcore-log( 5074): Process ARCH arm
W/jxcore-log( 5074): 
,I/jxcore-log( 5074): JXcore Cordova bridge is ready!
I/jxcore-log( 5074): 
,W/jxcore-log( 5074): JXcore engine is started
,E/jxcore-log( 5074): >> HTC-HTC One M8s
E/jxcore-log( 5074): 
,I/jxcore-log( 5074): Total memory 1931808768
I/jxcore-log( 5074): 
I/jxcore-log( 5074): Free memory 86495232
I/jxcore-log( 5074): 
I/jxcore-log( 5074): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5074): 
I/jxcore-log( 5074): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5074): 
,I/jxcore-log( 5074): userPath [ 'www' ],
I/jxcore-log( 5074): 
,I/jxcore-log( 5074): Size 1080 1776
I/jxcore-log( 5074): 
I/jxcore-log( 5074): Screen Brightness 142
I/jxcore-log( 5074): 
,E/jxcore-log( 5074): Dummy Error Log.
E/jxcore-log( 5074): 
,I/ActivityManager(  960): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5300 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  960): Killing 4592:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4592
,I/ActivityManager(  960): Killing 4793:com.htc.contacts/u0a38 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4793
,I/ActivityManager(  960): Killing 4848:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,I/jxcore-log( 5074): getBuffer is called!!!!,
I/jxcore-log( 5074): 
,I/ActivityManager(  960): Recipient 4848
,W/ActivityThread( 5257): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  960): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5336 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  960): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5362 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 4873:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4873
,I/ActivityManager(  960): Killing 4915:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4915
,I/ActivityManager(  960): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5386 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  960): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5417 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/ActivityManager(  960): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5439 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  960): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  960): Resuming delayed broadcast,
,I/ActivityManager(  960): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  960): Resuming delayed broadcast
,I/ActivityManager(  960): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5466 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  960): Killing 4942:com.htc.mobiledata/u0a46 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4942,
,I/ActivityManager(  960): Killing 4404:com.google.android.talk/u0a112 (adj 15): empty #17,
,I/ActivityManager(  960): Recipient 4404,
,I/ActivityManager(  960): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5489 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,I/ActivityManager(  960): Killing 4997:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4997
,I/ActivityManager(  960): Killing 5051:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 5051
,I/ActivityManager(  960): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5513 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  960): Killing 5097:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 5097
,I/ActivityManager(  960): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5535 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  960): Killing 4894:com.htc.sense.news/u0a74 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4894,
,I/ActivityManager(  960): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 5513): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  960): Cannot resolve ContentProvider=com.htc.vowifi,
E/ActivityThread( 5513): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  960): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5576 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager(  960): Killing 5169:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17,
,I/ActivityManager(  960): Recipient 5169
,W/ActivityThread( 5576): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  960): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5615 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/ActivityManager(  960): Killing 5139:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/ActivityManager(  960): Recipient 5139
,I/jxcore-log( 5074): ****TEST TOOK:  5076  ms ****
I/jxcore-log( 5074): 
,I/jxcore-log( 5074): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5074): 
,I/ActivityManager(  960): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5673 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  960): Killing 4966:com.htc.task/u0a69 (adj 15): empty #17
,I/ActivityManager(  960): Recipient 4966,
,I/ActivityManager(  960): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,I/ActivityManager(  960): Killing 5074:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  960): Recipient 5074
,W/ActivityManager(  960): Force removing ActivityRecord{18bad6c3 u0 com.example.hello/.MainActivity t8}: app died, no saved state,
,I/ActivityManager(  960): Force stopping com.example.hello appid=10373 user=0: pkg removed,
,W/ActivityManager(  960): Spurious death for ProcessRecord{2bbc7faf 5074:com.example.hello/u0a373}, curProc for 5074: null
,I/ActivityManager(  960): Killing 5222:com.htc.android.mail:sync/u0a62 (adj 15): empty #17,
,I/ActivityManager(  960): Recipient 5222
,I/ActivityManager(  960): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5720 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/ActivityManager(  960): Killing 5300:com.htc.task.gtask/u0a66 (adj 15): empty #17,
,I/ActivityManager(  960): Recipient 5300
,E/ActivityManager(  960): App crashed! Process: com.google.android.music:main,
,I/ActivityManager(  960): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5766 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,E/ActivityManager(  960): App crashed! Process: com.google.android.googlequicksearchbox:search
,E/ActivityManager(  960): App crashed! Process: com.google.process.gapps,


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  963): Killing 3361:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431e9890 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3887
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431e9890 stackId=1, 2 tasks}
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{431e9890 stackId=1, 2 tasks}
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431e9890 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  963): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3905 uid=10311 gids={50311, 3003, 3001, 3002}
I/ActivityManager(  963): startService SlideAside
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3} (starting new instance)
,I/ActivityManager(  963): Displayed com.example.hello/.MainActivity: +452ms
I/ActivityManager( 3905): Timeline: Activity_idle id: android.os.BinderProxy@42831448 time:46332
W/jxcore-log( 3905): Initializing JXcore engine
W/jxcore-log( 3905): JXcore engine is ready
W/jxcore-log( 3905): Starting JXcore engine
I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3} time:46652
D/ActivityManager(  963): no-history finish of ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{4312d370 ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 3905): Platform android
W/jxcore-log( 3905): 
W/jxcore-log( 3905): Process ARCH arm
W/jxcore-log( 3905): 
I/jxcore-log( 3905): JXcore Cordova bridge is ready!
I/jxcore-log( 3905): 
W/jxcore-log( 3905): JXcore engine is started
,E/jxcore-log( 3905): >> LGE-LG-D802
E/jxcore-log( 3905): 
,I/jxcore-log( 3905): Total memory 1943035904
I/jxcore-log( 3905): 
I/jxcore-log( 3905): Free memory 475967488
I/jxcore-log( 3905): 
I/jxcore-log( 3905): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3905): 
,I/jxcore-log( 3905): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3905): 
,I/jxcore-log( 3905): userPath [ 'www' ]
I/jxcore-log( 3905): 
,I/jxcore-log( 3905): Size 1080 1776
I/jxcore-log( 3905): 
,I/jxcore-log( 3905): Screen Brightness 255
I/jxcore-log( 3905): 
,E/jxcore-log( 3905): Dummy Error Log.
E/jxcore-log( 3905): 
,I/jxcore-log( 3905): getBuffer is called!!!!
I/jxcore-log( 3905): 
,I/ActivityManager(  963): Killing 3320:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431e9890 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3905): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 3905): 
I/jxcore-log( 3905): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3905): 
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  963): Killing 3905:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  963): Force removing ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{4319a2a0 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{431e9890 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  963): moveHomeStack:
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{43167660 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4017 uid=10090 gids={50090}
,I/ActivityManager(  963): Killing 3269:com.google.android.music:main/u0a107 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4033 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
F/ActivityManager(  963): Service ServiceRecord{4328f910 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43267d38 3269:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  963): Service ServiceRecord{43250118 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43267d38 3269:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Waited long enough for: ServiceRecord{4324bc18 u0 com.android.mms/.transaction.SmsReceiverService}
,I/ActivityManager(  963): Killing 3187:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4061 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  963): Delaying start of: ServiceRecord{43318a38 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1} time:53347
,I/ActivityManager(  963): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4077 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  963): Killing 2084:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): Killing 3738:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager( 1490): Timeline: Activity_idle id: android.os.BinderProxy@4282bfb8 time:53398
,I/ActivityManager(  963): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4091 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  963): Killing 3786:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bcc360 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b97c00 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Delaying start of: ServiceRecord{43244ad8 u0 com.android.providers.downloads/.DownloadService}


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.example.hello code:0 
child process exited with code 0 on device f56ad48d 
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of main
D/ActivityThread( 6318): Added TimaKeyStore provider
,--------- beginning of system
W/ActivityThread( 6318): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  840): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6366 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 6366): Added TimaKeyStore provider
I/ActivityManager(  840): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  840): mDVFSHelper.acquire()
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  840): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6384 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  840): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6401 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 6384): Added TimaKeyStore provider
D/ActivityThread( 6401): Added TimaKeyStore provider
I/ActivityManager(  840): Killing 5443:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  840): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6424 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  840): Killing 5580:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
D/ActivityThread( 6424): Added TimaKeyStore provider
E/ActivityThread( 6318): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2ce17966 that was originally bound here
E/ActivityThread( 6318): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2ce17966 that was originally bound here
E/ActivityThread( 6318): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 6318): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 6318): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 6318): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 6318): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6318): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 6318): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6318): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6318): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6318): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 6318): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 6318): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 6318): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 6318): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 6318): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 6318): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 6318): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 6318): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 6318): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6318): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6318): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 6318): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6318): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6318): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6318): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager(  840): Killing 5599:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
I/ActivityManager(  840): Killing 5617:com.sec.pcw.device/1000 (adj 15): bgCount ##41
I/ActivityManager(  840): Killing 4924:com.policydm/1000 (adj 15): bgCount ##41
D/ActivityManager(  840): post active user change for 0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  840): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=6480 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 6480): Added TimaKeyStore provider
I/ActivityManager(  840): Displayed com.example.hello/.MainActivity: +846ms
W/ActivityManager(  840): mDVFSHelper.release()
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  840): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=6504 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  840): Killing 5308:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,D/ActivityThread( 6504): Added TimaKeyStore provider
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=6522 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,D/ActivityThread( 6522): Added TimaKeyStore provider
,W/jxcore-log( 6384): Initializing JXcore engine
W/jxcore-log( 6384): JXcore engine is ready
,W/jxcore-log( 6384): Starting JXcore engine
,I/ActivityManager(  840): Killing 4981:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/ActivityManager(  840): Process com.samsung.indexservice (pid 6504)(adj 11) has died(62,590)
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6550 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6550): Added TimaKeyStore provider
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 6384): Platform android
W/jxcore-log( 6384): 
W/jxcore-log( 6384): Process ARCH arm
W/jxcore-log( 6384): 
,I/ActivityManager(  840): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6565 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/jxcore-log( 6384): JXcore Cordova bridge is ready!
I/jxcore-log( 6384): 
,W/jxcore-log( 6384): JXcore engine is started
,I/ActivityManager(  840): Killing 5147:com.android.mms/u0a50 (adj 15): bgCount ##41
,E/jxcore-log( 6384): >> samsung-SM-G900F
E/jxcore-log( 6384): 
,D/ActivityThread( 6565): Added TimaKeyStore provider
I/jxcore-log( 6384): Total memory 1787449344
I/jxcore-log( 6384): 
,I/jxcore-log( 6384): Free memory 66101248
I/jxcore-log( 6384): 
I/jxcore-log( 6384): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6384): 
I/jxcore-log( 6384): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6384): 
,I/jxcore-log( 6384): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6384): 
I/jxcore-log( 6384): Size 1080 1920
I/jxcore-log( 6384): 
I/jxcore-log( 6384): Screen Brightness 134
I/jxcore-log( 6384): 
E/jxcore-log( 6384): Dummy Error Log.
E/jxcore-log( 6384): 
,I/ActivityManager(  840): Killing 5652:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/jxcore-log( 6384): getBuffer is called!!!!
I/jxcore-log( 6384): 
,I/ActivityManager(  840): Killing 5675:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/ActivityManager(  840): Killing 5718:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/ActivityManager(  840): Killing 5783:com.vlingo.midas/u0a33 (adj 15): bgCount ##41,
,I/jxcore-log( 6384): ****TEST TOOK:  5045  ms ****
I/jxcore-log( 6384): 
,I/jxcore-log( 6384): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6384): 
,I/ActivityManager(  840): Waited long enough for: ServiceRecord{908afb0 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/ActivityManager(  840): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  840): Killing 6384:com.example.hello/u0a374 (adj 0): stop com.example.hello
,W/ActivityManager(  840): Force removing ActivityRecord{3910f300 u0 com.example.hello/.MainActivity t11}: app died, no saved state
,W/ActivityManager(  840): mDVFSHelper.acquire()
,I/ActivityManager(  840): Force stopping com.example.hello appid=10374 user=0: pkg removed
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6670 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager(  840): handle home activity for 0
D/ActivityManager(  840): post active user change for 0
,D/ActivityThread( 6670): Added TimaKeyStore provider
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=6687 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActivityThread( 6687): Added TimaKeyStore provider
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6710 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 5749:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,W/ActivityManager(  840): mDVFSHelper.release()
,I/ActivityManager(  840): Killing 5817:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/ActivityThread( 6710): Added TimaKeyStore provider
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6727 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/ActivityThread( 6727): Added TimaKeyStore provider
,I/ActivityManager(  840): Killing 5826:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6743 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 5846:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ActivityThread( 6743): Added TimaKeyStore provider
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=6760 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  840): Killing 5867:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/ActivityThread( 6760): Added TimaKeyStore provider
,I/ActivityManager(  840): Process com.samsung.android.sdk.samsunglink (pid 6760)(adj 0) has died(180,581)
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6777 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6777): Added TimaKeyStore provider
,E/ActivityThread( 6777): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  840): Process com.osp.app.signin (pid 6777)(adj 0) has died(179,582)
,E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  840): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  840): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=6793 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager(  840): Process android.process.acore (pid 1789)(adj 0) has died(187,582)


samsung-SM-A500FU: 
--------- beginning of main
--------- beginning of system
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3990 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3087:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
D/ActivityThread( 3990): Added TimaKeyStore provider
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4011 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3129:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
D/ActivityThread( 4011): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4028 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3195:com.fmm.ds/1000 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4028): Added TimaKeyStore provider
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4052 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4052): Added TimaKeyStore provider
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4065 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
D/ActivityThread( 4065): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 3216:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
I/ActivityManager( 1018): Killing 2973:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4084 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/ActivityThread( 4084): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/ActivityManager( 1018): Killing 3255:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4122 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4122): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4145 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3335:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 3271:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #32
D/ActivityThread( 4145): Added TimaKeyStore provider
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1018): mDVFSHelper.acquire()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4163 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 1491): updateVisibility : ActivityRecord{3ee28ff0 token=android.os.BinderProxy@11470c15 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 4163): Added TimaKeyStore provider
V/ActivityThread( 1491): updateVisibility : ActivityRecord{3ee28ff0 token=android.os.BinderProxy@11470c15 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,D/ActivityThread( 4180): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 3300:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3044:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Process com.android.email (pid 4084)(adj 9) has died(74,1085)
,I/ActivityThread( 4145): Removing dead content provider:android.content.ContentProviderProxy@e75db3a
,I/ActivityThread( 4145): Removing dead content provider:android.content.ContentProviderProxy@e75db3a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4198 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityThread( 4198): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 3389:com.sec.factory.camera/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Process com.android.exchange (pid 4145)(adj 11) has died(55,1091)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Displayed Component not be shown by security: +915ms
,W/ActivityManager( 1018): mDVFSHelper.release()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4276 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityThread( 4276): Added TimaKeyStore provider


```

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
--------- beginning of main
,I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1018): mDVFSHelper.acquire()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5091 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5091): Added TimaKeyStore provider
V/ActivityManager( 1018): Display changed displayId=0
V/ActivityThread( 1476): updateVisibility : ActivityRecord{2655fd2a token=android.os.BinderProxy@16a24df1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{2eae366 u0 com.example.hello/.MainActivity t10}
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 5091): updateVisibility : ActivityRecord{39c0f570 token=android.os.BinderProxy@1adbd522 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1018): Displayed Component not be shown by security: +671ms (total +752ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
,W/jxcore-log( 5091): Initializing JXcore engine
,W/jxcore-log( 5091): JXcore engine is ready
,W/jxcore-log( 5091): Starting JXcore engine
,W/jxcore-log( 5091): Platform android
W/jxcore-log( 5091): 
W/jxcore-log( 5091): Process ARCH arm
W/jxcore-log( 5091): 
,I/jxcore-log( 5091): JXcore Cordova bridge is ready!,
I/jxcore-log( 5091): 
W/jxcore-log( 5091): JXcore engine is started,
,E/jxcore-log( 5091): >> samsung-SM-A300FU
E/jxcore-log( 5091): 
,I/jxcore-log( 5091): Total memory 1451114496
I/jxcore-log( 5091): 
,I/jxcore-log( 5091): Free memory 25649152
I/jxcore-log( 5091): 
I/jxcore-log( 5091): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5091): 
I/jxcore-log( 5091): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5091): 
,I/jxcore-log( 5091): userPath [ 'www' ],
I/jxcore-log( 5091): 
,I/jxcore-log( 5091): Size 540 960,
I/jxcore-log( 5091): 
,I/jxcore-log( 5091): Screen Brightness 255
I/jxcore-log( 5091): 
E/jxcore-log( 5091): Dummy Error Log.
E/jxcore-log( 5091): 
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{18358a79 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5091): getBuffer is called!!!!
I/jxcore-log( 5091): 
,I/jxcore-log( 5091): ****TEST TOOK:  5084  ms ****
I/jxcore-log( 5091): 
,I/jxcore-log( 5091): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5091): 
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5091:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{2eae366 u0 com.example.hello/.MainActivity t10}
,W/ActivityManager( 1018): Spurious death for ProcessRecord{30efd4d9 5091:com.example.hello/u0a333}, curProc for 5091: null
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5159 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5172 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,D/ActivityThread( 5172): Added TimaKeyStore provider
,D/ActivityThread( 5159): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5191 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 5191): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 5207): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5229 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5229): Added TimaKeyStore provider
I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5243 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5243): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 4494:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 4237:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 4184:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5243): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5268): Added TimaKeyStore provider
,I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5286 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5286): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 3569:com.google.android.talk/u0a102 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 4703:com.google.android.gms:car/u0a11 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2933 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
I/ActivityManager(  903): Killing 1761:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
I/ActivityManager(  903): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
I/ActivityManager(  903): Recipient 1761
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2946
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2961 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
,I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +259ms
W/jxcore-log( 2961): Initializing JXcore engine
W/jxcore-log( 2961): JXcore engine is ready
W/jxcore-log( 2961): Starting JXcore engine
W/jxcore-log( 2961): Platform android
W/jxcore-log( 2961): 
W/jxcore-log( 2961): Process ARCH arm
W/jxcore-log( 2961): 
I/jxcore-log( 2961): JXcore Cordova bridge is ready!
I/jxcore-log( 2961): 
W/jxcore-log( 2961): JXcore engine is started
E/jxcore-log( 2961): >> HTC-HTC Desire 820
E/jxcore-log( 2961): 
I/jxcore-log( 2961): Total memory 1964650496
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Free memory 754192384
I/jxcore-log( 2961): 
I/jxcore-log( 2961): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2961): 
I/jxcore-log( 2961): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2961): 
I/jxcore-log( 2961): userPath [ 'www' ]
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Size 720 1184
I/jxcore-log( 2961): 
I/jxcore-log( 2961): Screen Brightness 10
I/jxcore-log( 2961): 
E/jxcore-log( 2961): Dummy Error Log.
E/jxcore-log( 2961): 
,I/jxcore-log( 2961): getBuffer is called!!!!
I/jxcore-log( 2961): 
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 2222:com.google.android.gms/u0a28 (adj 15): empty #17
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3003 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/ActivityManager(  903): Recipient 2222
,I/ActivityManager(  903): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=3020 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3051 uid=10077 gids={50077}
,I/ActivityManager(  903): Killing 2622:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  903): Killing 2608:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #18
,I/ActivityManager(  903): Recipient 2608
,I/ActivityManager(  903): Recipient 2622
,I/ActivityManager(  903): Killing 2647:com.htc.csrecommend/u0a33 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2647
I/ActivityManager(  903): Delay finish: com.android.stk/.BootCompletedReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3069 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,I/ActivityManager(  903): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3084 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  903): Killing 2660:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2660
,I/ActivityManager(  903): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3098 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
I/ActivityManager(  903): Killing 2672:com.htc.contacts/u0a41 (adj 15): empty #17
I/ActivityManager(  903): Waited long enough for: ServiceRecord{426a6fb0 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  903): Recipient 2672
,I/ActivityManager(  903): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3113 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
,I/ActivityManager(  903): Killing 2689:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2689
,I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3160 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/jxcore-log( 2961): ****TEST TOOK:  5130  ms ****
I/jxcore-log( 2961): 
,I/jxcore-log( 2961): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2961): 
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3182 uid=10037 gids={50037, 3002, 3001}
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{4266e838 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  903): Killing 2701:com.htc.aurora/u0a47 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2701
,I/ActivityManager(  903): Killing 2715:com.htc.aurora:remote/u0a47 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2715
,I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3205 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  903): Killing 2731:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2731
,I/ActivityManager(  903): Killing 2746:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2746
,I/ActivityManager(  903): Killing 2759:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  903): Killing 2961:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  903): Force removing ActivityRecord{41f3dbe0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  903): Recipient 2759
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3232 uid=10090 gids={50090, 3003, 5012, 1028}
,I/ActivityManager(  903): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
,I/ActivityManager(  903): Killing 2781:com.htc.HTCSpeaker/u0a55 (adj 15): empty #17
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
I/ActivityManager(  903): Recipient 2781
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=3255 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3268 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  903): Killing 2796:com.htc.video/u0a56 (adj 15): empty #17
,E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
I/ActivityManager(  903): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3284 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  903): Killing 2811:com.htc.lmw/u0a59 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2811
,I/ActivityManager(  903): Recipient 2796
,I/ActivityManager(  903): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3098 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3072
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3120 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  906): Killing 2767:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2767
I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3171 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +359ms
I/ActivityManager(  906): Killing 2559:com.android.defcontainer/u0a19 (adj 15): empty #17
W/jxcore-log( 3120): Initializing JXcore engine
W/jxcore-log( 3120): JXcore engine is ready
I/ActivityManager(  906): Recipient 2559
W/jxcore-log( 3120): Starting JXcore engine
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3222 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3234 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2796:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  906): Killing 2831:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2796
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3250 uid=10041 gids={50041}
I/ActivityManager(  906): Recipient 2831
W/jxcore-log( 3120): Platform android
W/jxcore-log( 3120): 
W/jxcore-log( 3120): Process ARCH arm
W/jxcore-log( 3120): 
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3266 uid=10078 gids={50078}
I/ActivityManager(  906): Killing 2780:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/jxcore-log( 3120): JXcore Cordova bridge is ready!
I/jxcore-log( 3120): 
W/jxcore-log( 3120): JXcore engine is started
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3278 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 2851:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2780
E/jxcore-log( 3120): >> HTC-HTC Desire 820
E/jxcore-log( 3120): 
I/jxcore-log( 3120): Total memory 1964650496
I/jxcore-log( 3120): 
I/jxcore-log( 3120): Free memory 692678656
I/jxcore-log( 3120): 
I/jxcore-log( 3120): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3120): 
I/jxcore-log( 3120): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3120): 
I/jxcore-log( 3120): userPath [ 'www' ]
I/jxcore-log( 3120): 
I/jxcore-log( 3120): Size 720 1184
I/jxcore-log( 3120): 
I/jxcore-log( 3120): Screen Brightness 142
I/jxcore-log( 3120): 
E/jxcore-log( 3120): Dummy Error Log.
E/jxcore-log( 3120): 
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3293 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  906): Killing 2878:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2878
,I/ActivityManager(  906): Recipient 2851
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3308 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3322 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 2895:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2895
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3337 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  906): Killing 2910:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3349 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  906): Recipient 2910
,I/ActivityManager(  906): Killing 2936:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2936
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3361 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  906): Killing 2964:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2964
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2979:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2979
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/jxcore-log( 3120): getBuffer is called!!!!
I/jxcore-log( 3120): 
I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3383 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3397 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2994:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  906): Killing 3098:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3098
I/ActivityManager(  906): Recipient 2994
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3419 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3171:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3440 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Recipient 3171
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3222:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3222
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3458 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3476 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3234:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3234
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3278:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3278
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3498 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3517 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  906): Killing 2924:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2924
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/jxcore-log( 3120): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 3120): 
I/jxcore-log( 3120): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3120): 
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,I/ActivityManager(  906): Killing 3120:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  906): Force removing ActivityRecord{428f1050 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3337:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3337
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Delaying start of: ServiceRecord{427923a8 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,I/ActivityManager(  906): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=3557 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42626120 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=3574 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
,E/ActivityManager(  906): App crashed! Process: com.htc.launcher:biclient
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3592 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver


LGE-Nexus 5: 
--------- beginning of /dev/log/system
I/ActivityManager(  796): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=2182 uid=10031 gids={50031, 3003, 1028, 1015}
--------- beginning of /dev/log/main
I/ActivityManager(  796): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2215 uid=10068 gids={50068}
I/ActivityManager(  796): Killing 1653:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
I/ActivityManager(  796): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
I/ActivityManager(  796): Resuming delayed broadcast
I/ActivityManager(  796): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2235 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
I/ActivityManager(  796): Killing 1689:com.android.vending/u0a14 (adj 15): empty #17
I/ActivityManager(  796): Killing 1272:com.google.android.partnersetup/u0a11 (adj 15): empty #17
I/ActivityManager(  796): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2249 uid=10058 gids={50058, 3003, 1028, 1015}
,I/ActivityManager(  796): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  796): Resuming delayed broadcast
I/ActivityManager(  796): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  796): Resuming delayed broadcast
I/ActivityManager(  796): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  796): Resuming delayed broadcast
I/ActivityManager(  796): Killing 1554:com.android.providers.calendar/u0a1 (adj 15): empty #17
I/ActivityManager(  796): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
I/ActivityManager(  796): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2283
I/ActivityManager(  796): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2322 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  796): Killing 1811:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  796): Displayed com.example.hello/.MainActivity: +469ms
,W/jxcore-log( 2322): Initializing JXcore engine
,W/jxcore-log( 2322): JXcore engine is ready
,W/jxcore-log( 2322): Starting JXcore engine
,W/jxcore-log( 2322): Platform android
W/jxcore-log( 2322): 
,W/jxcore-log( 2322): Process ARCH arm
W/jxcore-log( 2322): 
,I/jxcore-log( 2322): JXcore Cordova bridge is ready!
I/jxcore-log( 2322): 
,W/jxcore-log( 2322): JXcore engine is started
,E/jxcore-log( 2322): >> LGE-Nexus 5
E/jxcore-log( 2322): 
,I/jxcore-log( 2322): Total memory 1945137152
I/jxcore-log( 2322): 
I/jxcore-log( 2322): Free memory 870715392
I/jxcore-log( 2322): 
I/jxcore-log( 2322): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2322): 
,I/jxcore-log( 2322): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2322): 
,I/jxcore-log( 2322): userPath [ 'www' ]
I/jxcore-log( 2322): 
,I/jxcore-log( 2322): Size 1080 1776
I/jxcore-log( 2322): 
,I/jxcore-log( 2322): Screen Brightness 82
I/jxcore-log( 2322): 
,E/jxcore-log( 2322): Dummy Error Log.
E/jxcore-log( 2322): 
,I/jxcore-log( 2322): getBuffer is called!!!!
I/jxcore-log( 2322): 
,W/ActivityThread(  796): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  796): Killing 1855:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  796): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2387 uid=10001 gids={50001, 3003, 1028, 1015}
,I/ActivityManager(  796): Killing 1886:com.google.android.gm/u0a41 (adj 15): empty #17
,I/ActivityManager(  796): Resuming delayed broadcast
,I/ActivityManager(  796): Killing 956:android.process.acore/u0a3 (adj 15): empty #17
,I/ActivityManager(  796): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=2403 uid=10041 gids={50041, 3003, 1028, 1015}
,D/ActivityThread( 2403): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,I/ActivityManager(  796): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  796): Killing 1920:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  796): Delaying start of: ServiceRecord{4368e790 u0 com.google.android.gms/.icing.service.IndexWorkerService}
,I/jxcore-log( 2322): ****TEST TOOK:  5085  ms ****
I/jxcore-log( 2322): 
,I/jxcore-log( 2322): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2322): 
,I/ActivityManager(  796): Resuming delayed broadcast
,I/ActivityManager(  796): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  796): Resuming delayed broadcast
,I/ActivityManager(  796): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  796): Resuming delayed broadcast
I/ActivityManager(  796): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  796): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  796): Killing 2322:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  796): Force removing ActivityRecord{43487cc8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  796): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  796): Resuming delayed broadcast
,I/ActivityManager(  796): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  796): Resuming delayed broadcast


```




###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/252F0045-56BE-481A-B6BD-3320AE58AAB2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/252F0045-56BE-481A-B6BD-3320AE58AAB2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9B4303FE-7B1A-41C8-A7C4-65A3F5594861/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53244"
,(lldb)     command script import "/tmp/252F0045-56BE-481A-B6BD-3320AE58AAB2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 12:28:45.981 HelloWorld[1906:2179439] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8DC95B64-DDF1-4FF7-AB0D-E5425A8FE730/Library/Cookies/Cookies.binarycookies
,2015-11-10 12:28:46.313 HelloWorld[1906:2179439] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-10 12:28:46.314 HelloWorld[1906:2179439] Multi-tasking -> Device: YES, App: YES
,2015-11-10 12:28:46.317 HelloWorld[1906:2179439] Unlimited access to network resources
,2015-11-10 12:28:46.322 HelloWorld[1906:2179439] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 12:28:49.104 HelloWorld[1906:2179439] Resetting plugins due to page load.
,2015-11-10 12:28:49.419 HelloWorld[1906:2179439] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/9B4303FE-7B1A-41C8-A7C4-65A3F5594861/HelloWorld.app/www/index.html
,2015-11-10 12:28:49.492 HelloWorld[1906:2179439] JXcore Cordova plugin initializing
2015-11-10 12:28:49.493 HelloWorld[1906:2179668] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 119500800
execPath /private/var/mobile/Containers/Bundle/Application/9B4303FE-7B1A-41C8-A7C4-65A3F5594861/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/9B,4303FE-7B1A-41C8-A7C4-65A3F5594861/HelloWorld.app/www/jxcore/
userPath []
2015-11-10 12:28:49.746 HelloWorld[1906:2179668] Native method ScreenInfo not found.
2015-11-10 12:28:49.746 HelloWorld[1906:2179668] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5108  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2CA7EB6A-0786-4D31-B21C-617E12D14A1E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/2CA7EB6A-0786-4D31-B21C-617E12D14A1E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/9F44123E-D782-4ECF-99C0-D04A671A5A20/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53241"
,(lldb)     command script import "/tmp/2CA7EB6A-0786-4D31-B21C-617E12D14A1E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 12:29:07.809 HelloWorld[1567:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-10 12:29:07.814 HelloWorld[1567:60b] Multi-tasking -> Device: YES, App: YES
2015-11-10 12:29:07.818 HelloWorld[1567:60b] Unlimited access to ne,twork resources
2015-11-10 12:29:07.824 HelloWorld[1567:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
htt,ps://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 12:29:14.191 HelloWorld[1567:60b] Resetting plugins due to page load.
,2015-11-10 12:29:14.703 HelloWorld[1567:60b] Finished load of: file:///var/mobile/Applications/9F44123E-D782-4ECF-99C0-D04A671A5A20/HelloWorld.app/www/index.html
,2015-11-10 12:29:14.773 HelloWorld[1567:60b] JXcore Cordova plugin initializing
,2015-11-10 12:29:14.774 HelloWorld[1567:6607] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 484225024
execPath /private/var/mobile/Applications/9F44123E-D782-4ECF-99C0-D04A671A5A20/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/9F44123E-D782-4ECF-99C0-D04A671A5A20/HelloWor,ld.app/www/jxcore/
userPath []
2015-11-10 12:29:15.113 HelloWorld[1567:6607] Native method ScreenInfo not found.
,2015-11-10 12:29:15.115 HelloWorld[1567:6607] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5155  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F3528FE7-BB97-45B6-8BE0-16D8A7576E14/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F3528FE7-BB97-45B6-8BE0-16D8A7576E14/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FA1D2AAF-2E0B-4AA3-A846-ECD2C71D27EF/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53246"
,(lldb)     command script import "/tmp/F3528FE7-BB97-45B6-8BE0-16D8A7576E14/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 12:28:44.464 HelloWorld[2983:3282839] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8B334368-DB38-4FFA-AA8A-FF5BE3FD334D/Library/Cookies/Cookies.binarycookies
,2015-11-10 12:28:44.752 HelloWorld[2983:3282839] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-10 12:28:44.753 HelloWorld[2983:3282839] Multi-tasking -> Device: YES, App: YES
,2015-11-10 12:28:44.755 HelloWorld[2983:3282839] Unlimited access to network resources
,2015-11-10 12:28:44.759 HelloWorld[2983:3282839] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 12:28:46.990 HelloWorld[2983:3282839] Resetting plugins due to page load.
,2015-11-10 12:28:47.161 HelloWorld[2983:3282839] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/FA1D2AAF-2E0B-4AA3-A846-ECD2C71D27EF/HelloWorld.app/www/index.html
,2015-11-10 12:28:47.214 HelloWorld[2983:3282839] JXcore Cordova plugin initializing
2015-11-10 12:28:47.215 HelloWorld[2983:3282915] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
,Free memory 78757888
,execPath /private/var/mobile/Containers/Bundle/Application/FA1D2AAF-2E0B-4AA3-A846-ECD2C71D27EF/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/FA1D2AAF-2E0B-4AA3-A846-ECD2C71D27EF/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-10 12:28:47.398 HelloWorld[2983:3282915] Native method ScreenInfo not found.
,2015-11-10 12:28:47.400 HelloWorld[2983:3282915] Native method ScreenBrightness not found.
,Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5086  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F4D67034-AF47-4154-9E72-582B60545016/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F4D67034-AF47-4154-9E72-582B60545016/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285e222b78/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/15596D7B-10FA-481B-9344-858642C8FB0D/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53240"
,(lldb)     command script import "/tmp/F4D67034-AF47-4154-9E72-582B60545016/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 12:28:45.844 HelloWorld[1974:4287832] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EBC7C4B9-1846-41B0-BBF3-A0255A3BFF2F/Library/Cookies/Cookies.binarycookies
,2015-11-10 12:28:46.106 HelloWorld[1974:4287832] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-10 12:28:46.107 HelloWorld[1974:4287832] Multi-tasking -> Device: YES, App: YES
,2015-11-10 12:28:46.109 HelloWorld[1974:4287832] Unlimited access to network resources
,2015-11-10 12:28:46.113 HelloWorld[1974:4287832] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 12:28:50.289 HelloWorld[1974:4287832] Resetting plugins due to page load.
,2015-11-10 12:28:51.687 HelloWorld[1974:4287832] Finished load of: file:///var/mobile/Containers/Bundle/Application/15596D7B-10FA-481B-9344-858642C8FB0D/HelloWorld.app/www/index.html
,2015-11-10 12:28:51.733 HelloWorld[1974:4287832] JXcore Cordova plugin initializing
,2015-11-10 12:28:51.733 HelloWorld[1974:4288007] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
Total memory 2084569088
Free memory 338788352
execPath /private/var/mobile/Containers/Bundle/Application/15596D7B-10FA-481B-9344-858642C8FB0D/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/15596D7B-1,0FA-481B-9344-858642C8FB0D/HelloWorld.app/www/jxcore/
userPath []
2015-11-10 12:28:51.910 HelloWorld[1974:4288007] Native method ScreenInfo not found.
2015-11-10 12:28:51.910 HelloWorld[1974:4288007] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5104  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50242285e222b78/serverApp/index.js',
  '{"devices":{"ios":4,"android":18,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 18, cancel: 1 } }


```

