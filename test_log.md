#### Test 50388019dad02bc Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50388019dad02bc/serverApp/index.js',
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
Device test finished on W3D7N15428022572 
Device test finished on LGH8153b36be34 
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-T232: 
--------- beginning of /dev/log/system
I/ActivityManager( 1200): rtcc_minfree = 82449,70671,58892,47114,35335
I/ActivityManager( 1200): Config changes=1df8 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h961dp 213dpi lrg port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
I/ActivityManager( 1200): Config changes=408 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port ?uimode ?night finger -keyb/v/h -nav/h s.3}
I/ActivityManager( 1200): System now ready
I/ActivityManager( 1200): Config changes=200 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port finger -keyb/v/h -nav/h s.4}
I/ActivityManager( 1200): !@ mBooting is set true!
I/ActivityManager( 1200): RTCC_TRIGGER_MSG, ASYNC.
W/ActivityManager( 1200): mDVFSHelper.release()
E/ActivityThread( 1588): Failed to find provider info for com.samsung.helphub.provider
W/ActivityManager( 1200): Unable to start service Intent { cmp=com.samsung.android.app.gestureservice/.GestureService } U=0: not found
W/ActivityManager( 1200): !@call fb1: post finishBooting() with 1000msec delay
I/ActivityManager( 1200): !@Boot: bootcomplete
W/ActivityThread( 3180): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityThread( 3213): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1200): Killing 2764:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2793:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 1623:com.android.printspooler/u0a118 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2743:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2916:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2930:com.samsung.android.app.memo/u0a130 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2946:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3023:com.sec.phone/u0a127 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3084:com.google.android.configupdater/u0a2 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3111:com.sec.android.widgetapp.samsungapps/u0a120 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3158:com.sec.dsm.system/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3180:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3213:com.sec.factory/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3228:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3260:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 1503:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3277:com.android.onetimeinitializer/u0a21 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3292:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3320:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3336:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
W/ActivityManager( 1200): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1200): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1200): Killing 3350:com.osp.app.signin/u0a30 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2959:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2661:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 1646:com.android.settings/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3384:com.wssyncmldm/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 2620:com.google.android.partnersetup/u0a11 (adj 15): bgCount ##33
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{425d9258 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{428a4b50 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/ActivityManager( 1200): Killing 3409:com.google.android.googlequicksearchbox:search/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3453:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3435:com.samsung.android.intelligenceservice/u0a52 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3481:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1200): Process com.samsung.android.MtpApplication (pid 4179) (adj 0) has died.
I/ActivityManager( 1200): Killing 3496:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3510:com.wssnps/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3523:com.samsung.android.app.accesscontrol/u0a57 (adj 15): bgCount ##33
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{429c5b60 u0 com.samsung.android.providers.context/.ContextService}
I/ActivityManager( 1200): Killing 3541:com.sec.android.app.FileShareServer/u0a62 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3556:com.sec.android.nearby.mediaserver/u0a63 (adj 15): bgCount ##33
W/ActivityThread( 4166): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1200): Killing 3570:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
W/ActivityManager( 1200): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
I/ActivityManager( 1200): Killing 3586:com.sec.android.app.bluetoothtest/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3599:com.blurb.checkout/u0a67 (adj 15): bgCount ##33
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{42966fa8 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{425d9b48 u0 com.sec.esdk.elm/.service.ElmAgentService}
I/ActivityManager( 1200): Process com.sec.android.app.sysscope (pid 3957) (adj 0) has died.
I/ActivityManager( 1200): Process com.sec.factory (pid 4166) (adj 0) has died.
I/ActivityManager( 1200): Killing 3612:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3625:com.dropbox.android/u0a78 (adj 15): bgCount ##33
W/ActivityThread( 4540): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1200): Killing 3671:com.sec.factory.camera/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3686:com.samsung.android.app.watchmanagerstub/u0a86 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3759:com.samsung.scrc.idi.server/u0a91 (adj 15): bgCount ##33
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{424dc478 u0 com.android.exchange/.ExchangeService}
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{428a3e20 u0 com.android.exchange/.service.ExchangeBroadcastProcessorService}
I/ActivityManager( 1200): Killing 3773:com.samsung.helphub/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3789:com.LocalFota/u0a92 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3805:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3834:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{429d8638 u0 com.rxnetworks.rxnservicesxybrid/com.rxnetworks.rxnserviceslib.RXNetworksService}
I/ActivityManager( 1200): Killing 3858:com.sec.android.app.camera/u0a121 (adj 15): bgCount ##33
W/ActivityManager( 1200): mDVFSHelper.acquire()
I/ActivityManager( 1200): Waited long enough for: ServiceRecord{42984090 u0 com.samsung.android.MtpApplication/.MtpService}
W/ActivityManager( 1200): mDVFSHelper.release()
E/ActivityThread( 3144): Activity com.gameloft.android.gdc.StartActivity has leaked IntentReceiver hj@41e0a648 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3144): android.app.IntentReceiverLeaked: Activity com.gameloft.android.gdc.StartActivity has leaked IntentReceiver hj@41e0a648 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3144): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:809)
E/ActivityThread( 3144): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:610)
E/ActivityThread( 3144): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1816)
E/ActivityThread( 3144): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1796)
E/ActivityThread( 3144): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1790)
E/ActivityThread( 3144): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:479)
E/ActivityThread( 3144): 	at hj.b(Unknown Source)
E/ActivityThread( 3144): 	at hj.a(Unknown Source)
E/ActivityThread( 3144): 	at hm.a(Unknown Source)
E/ActivityThread( 3144): 	at hi.run(Unknown Source)
E/ActivityThread( 3144): 	at java.lang.Thread.run(Thread.java:841)
I/ActivityManager( 1200): Killing 1763:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3928:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3942:com.sec.android.app.worldclock/u0a135 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3970:com.sec.android.app.controlpanel/u0a141 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3984:com.samsung.android.service.travel/u0a143 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 4002:com.google.android.youtube/u0a146 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 4068:com.gameloft.android.gdc:remote/u0a152 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 4290:com.sec.spp.push:RemoteDlcProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 4307:com.sec.spp.push:RemoteNotiProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 4347:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 3728:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 4219:com.sec.android.widgetapp.SPlannerAppWidget/u0a34 (adj 15): bgCount ##33
I/ActivityManager( 1200): Killing 4248:com.android.calendar/u0a117 (adj 15): bgCount ##33
W/ActivityManager( 1200): mDVFSHelper.acquire()
W/ActivityManager( 1200): mDVFSHelper.release()
,--------- beginning of /dev/log/main
W/ActivityManager( 1200): mDVFSHelper.acquire()
W/ActivityManager( 1200): mDVFSHelper.release()
W/jxcore-log( 4945): Initializing JXcore engine
,W/jxcore-log( 4945): JXcore engine is ready
W/jxcore-log( 4945): Starting JXcore engine
W/jxcore-log( 4945): Platform android
W/jxcore-log( 4945): 
W/jxcore-log( 4945): Process ARCH arm
W/jxcore-log( 4945): 
I/jxcore-log( 4945): JXcore Cordova bridge is ready!
I/jxcore-log( 4945): 
W/jxcore-log( 4945): JXcore engine is started
E/jxcore-log( 4945): >> samsung-SM-T232
E/jxcore-log( 4945): 
I/jxcore-log( 4945): Total memory 1352024064
I/jxcore-log( 4945): 
I/jxcore-log( 4945): Free memory 219992064
I/jxcore-log( 4945): 
I/jxcore-log( 4945): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4945): 
I/jxcore-log( 4945): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4945): 
I/jxcore-log( 4945): userPath [ 'www' ]
I/jxcore-log( 4945): 
I/jxcore-log( 4945): Size 800 1280
I/jxcore-log( 4945): 
I/jxcore-log( 4945): Screen Brightness 143
I/jxcore-log( 4945): 
E/jxcore-log( 4945): Dummy Error Log.
E/jxcore-log( 4945): 
I/jxcore-log( 4945): getBuffer is called!!!!
I/jxcore-log( 4945): 
,I/jxcore-log( 4945): ****TEST TOOK:  5107  ms ****
I/jxcore-log( 4945): 
,I/jxcore-log( 4945): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4945): 
,I/ActivityManager( 1200): Killing 4945:com.example.hello/u0a357 (adj 0): stop com.example.hello
,I/ActivityThread( 2817): Removing dead content provider:android.content.ContentProviderProxy@41ef5748
,I/ActivityManager( 1200): Process com.google.process.gapps (pid 1708) (adj 0) has died.


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
I/ActivityManager( 3488): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9761 uid=10435 gids={50435, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 9761): Added TimaKeyStore provider
V/ActivityThread( 4253): updateVisibility : ActivityRecord{2d076b3f token=android.os.BinderProxy@3139ce75 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,W/ActivityManager( 3488): Activity pause timeout for ActivityRecord{313c9c7d u0 com.example.hello/.MainActivity t44}
,D/ActivityManager( 3488): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 9761): updateVisibility : ActivityRecord{1610c414 token=android.os.BinderProxy@c5f7a9e {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 3488): Displayed Component not be shown by security: +637ms
,W/ActivityManager( 3488): mDVFSHelper.release()
,W/jxcore-log( 9761): Initializing JXcore engine
W/jxcore-log( 9761): JXcore engine is ready
,W/jxcore-log( 9761): Starting JXcore engine
,W/jxcore-log( 9761): Platform android
W/jxcore-log( 9761): 
W/jxcore-log( 9761): Process ARCH arm
W/jxcore-log( 9761): 
,I/jxcore-log( 9761): JXcore Cordova bridge is ready!
I/jxcore-log( 9761): 
W/jxcore-log( 9761): JXcore engine is started
,E/jxcore-log( 9761): >> samsung-SM-G920F
E/jxcore-log( 9761): 
,I/jxcore-log( 9761): Total memory 2829074432
I/jxcore-log( 9761): 
I/jxcore-log( 9761): Free memory 48578560
I/jxcore-log( 9761): 
I/jxcore-log( 9761): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9761): 
I/jxcore-log( 9761): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9761): 
,I/jxcore-log( 9761): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9761): 
,I/jxcore-log( 9761): Size 1440 2560
I/jxcore-log( 9761): 
,I/jxcore-log( 9761): Screen Brightness 134
I/jxcore-log( 9761): 
E/jxcore-log( 9761): Dummy Error Log.
E/jxcore-log( 9761): 
,I/jxcore-log( 9761): getBuffer is called!!!!
I/jxcore-log( 9761): 
,I/jxcore-log( 9761): ****TEST TOOK:  5072  ms ****
I/jxcore-log( 9761): 
I/jxcore-log( 9761): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9761): 
,I/ActivityManager( 3488): Force stopping com.example.hello appid=10435 user=-1: uninstall pkg
,I/ActivityManager( 3488): Killing 9761:com.example.hello/u0a435 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3488):   Force finishing activity ActivityRecord{313c9c7d u0 com.example.hello/.MainActivity t44}
,I/ActivityManager( 3488): Force stopping com.example.hello appid=10435 user=0: pkg removed
,W/ActivityManager( 3488): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3488): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9869 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3488): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityThread( 9869): Added TimaKeyStore provider
,D/ActivityManager( 3488): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3488): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5191, uid=10127 that is not exported from uid 10125
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 3488): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,I/ActivityManager( 3488): Killing 9217:com.samsung.android.coreapps/u0a98 (adj 15): empty #25
,D/ActivityManager( 3488): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3488): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9892 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,D/ActivityThread( 9892): Added TimaKeyStore provider
,D/ActivityManager( 3488): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3488): userId = 0, bbcId = -10000
W/ActivityManager( 3488): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3488): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3488): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3488): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9908 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,I/ActivityManager( 3488): Killing 9198:com.android.mms/u0a48 (adj 15): empty #25
,D/ActivityThread( 9908): Added TimaKeyStore provider


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,I/ActivityManager( 2947): Displayed com.example.hello/.MainActivity: +759ms (total +830ms)
W/jxcore-log( 6732): Initializing JXcore engine
W/jxcore-log( 6732): JXcore engine is ready
W/jxcore-log( 6732): Starting JXcore engine
W/jxcore-log( 6732): Platform android
W/jxcore-log( 6732): 
W/jxcore-log( 6732): Process ARCH arm
W/jxcore-log( 6732): 
I/jxcore-log( 6732): JXcore Cordova bridge is ready!
I/jxcore-log( 6732): 
W/jxcore-log( 6732): JXcore engine is started
E/jxcore-log( 6732): >> HUAWEI-ALE-L21
E/jxcore-log( 6732): 
I/jxcore-log( 6732): Total memory 1949741056
I/jxcore-log( 6732): 
I/jxcore-log( 6732): Free memory 26800128
I/jxcore-log( 6732): 
I/jxcore-log( 6732): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6732): 
I/jxcore-log( 6732): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6732): 
I/jxcore-log( 6732): userPath [ 'www' ]
I/jxcore-log( 6732): 
I/jxcore-log( 6732): Size 720 1184
I/jxcore-log( 6732): 
I/jxcore-log( 6732): Screen Brightness 242
I/jxcore-log( 6732): 
E/jxcore-log( 6732): Dummy Error Log.
E/jxcore-log( 6732): 
,I/jxcore-log( 6732): getBuffer is called!!!!
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): ****TEST TOOK:  5096  ms ****
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6732): 
,I/ActivityManager( 2947): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2947): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1278): Start proc 8209:com.android.browser/u0a24 for broadcast com.android.browser/com.lge.browser.settings.BrowserSettingReceiver
I/ActivityManager( 1278): Start proc 8234:com.lge.appbox.client:SingleBinaryService/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver
I/ActivityManager( 1278): Killing 7349:com.lge.gnss.airtest/u0a80 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 8254:com.lge.appbox.client/u0a9 for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider
I/ActivityManager( 1278): Killing 7371:com.lge.springcleaning/1000 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 8276:com.android.cellbroadcastreceiver/u0a14 for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver
I/ActivityManager( 1278): Killing 7411:com.lge.hiddenmenu/1000 (adj 15): empty #22
I/ActivityManager( 1278): Waited long enough for: ServiceRecord{11ca7697 u0 com.android.calendar/.alerts.InitAlarmsService}
I/ActivityManager( 1278): Start proc 8299:com.lge.email/u0a56 for broadcast com.lge.email/.receiver.EmailSimChangedReceiver
I/ActivityManager( 1278): Start proc 8322:com.android.contacts/u0a18 for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver
I/ActivityManager( 1278): Killing 7433:com.lge.lockscreensettings/1000 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 8348:com.lge.wifisettings/1000 for broadcast com.lge.wifisettings/.wifioffload.WiFiOffLoadBroadcast
I/ActivityManager( 1278): Killing 7454:com.lge.lgfota.permission/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 8374:com.android.settings/1000 for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver
I/ActivityManager( 1278): Killing 7474:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #22
I/ActivityManager( 1278): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{7dd150b #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{7dd150b #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1278): Start proc 8412:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1278): Killing 7497:com.lge.ia.task.incalagent/u0a8 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 8434:com.lge.hiddenmenu/1000 for broadcast com.lge.hiddenmenu/.SVC.log_service.FactorySIMReceiver
I/ActivityManager( 1278): Waited long enough for: ServiceRecord{3adebddf u0 com.lge.lpd/.service.LPDRegistReceiverService}
I/ActivityManager( 1278): Killing 7517:com.android.providers.calendar/u0a19 (adj 15): empty #22
D/ActivityManager( 1278): enqueue in BackgroundQueue #78 Intent=Intent { act=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION flg=0x14 (has extras) }
I/ActivityManager( 1278): Start proc 8471:com.android.providers.partnerbookmarks/u0a103 for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver
I/ActivityManager( 1278): Start proc 8497:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseSIMObserver
I/ActivityManager( 1278): Killing 7538:com.google.android.apps.maps/u0a119 (adj 15): empty #22
I/ActivityManager( 1278): Killing 7574:com.google.android.gm/u0a113 (adj 15): empty #22
I/ActivityManager( 1278): Displayed com.example.hello/.MainActivity: +1s29ms (total +17s50ms)
W/jxcore-log( 8412): Initializing JXcore engine
W/jxcore-log( 8412): JXcore engine is ready
W/jxcore-log( 8412): Starting JXcore engine
I/ActivityManager( 1278): Start proc 8529:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
,I/ActivityManager( 1278): Start proc 8549:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
,W/jxcore-log( 8412): Platform android
W/jxcore-log( 8412): 
W/jxcore-log( 8412): Process ARCH arm
W/jxcore-log( 8412): 
,I/ActivityManager( 1278): Start proc 8571:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
,I/jxcore-log( 8412): JXcore Cordova bridge is ready!
I/jxcore-log( 8412): 
,W/jxcore-log( 8412): JXcore engine is started
,E/jxcore-log( 8412): >> LGE-LG-H815
E/jxcore-log( 8412): 
,I/jxcore-log( 8412): Total memory 2968948736
I/jxcore-log( 8412): 
,I/jxcore-log( 8412): Free memory 82776064
I/jxcore-log( 8412): 
I/jxcore-log( 8412): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8412): 
I/jxcore-log( 8412): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8412): 
,I/jxcore-log( 8412): userPath [ 'www' ]
I/jxcore-log( 8412): 
,I/jxcore-log( 8412): Size 1440 2392
I/jxcore-log( 8412): 
,I/jxcore-log( 8412): Screen Brightness 255
I/jxcore-log( 8412): 
E/jxcore-log( 8412): Dummy Error Log.
E/jxcore-log( 8412): 
,I/ActivityManager( 1278): Killing 7645:com.android.vending/u0a62 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 7693:com.google.android.youtube/u0a124 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 8599:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
,I/ActivityManager( 1278): Killing 7788:com.google.android.talk/u0a121 (adj 15): empty #22
,I/jxcore-log( 8412): getBuffer is called!!!!
I/jxcore-log( 8412): 
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Killing 7821:com.google.android.googlequicksearchbox:search/u0a63 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 8626:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.lockscreen.QuickUnlockReceiver
,I/ActivityManager( 1278): Start proc 8646:com.lge.qremote/u0a138 for broadcast com.lge.qremote/.settings.WiFiStateReceiver
,I/ActivityManager( 1278): Killing 7990:com.lge.qmemoplus/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 8024:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1278): Waited long enough for: ServiceRecord{9686519 u0 com.lge.springcleaning/.service.AppCleanupService}
,I/ActivityManager( 1278): Killing 8093:com.lge.lgaccount/u0a107 (adj 15): empty #22,
,I/ActivityManager( 1278): Start proc 8666:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 8701:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Killing 8118:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Killing 7856:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Killing 8209:com.android.browser/u0a24 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 8752:com.lge.sync/1000 for broadcast com.lge.sync/.StartReceiver
,I/ActivityManager( 1278): Start proc 8773:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
,I/ActivityManager( 1278): Killing 8234:com.lge.appbox.client:SingleBinaryService/u0a9 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 8797:com.lge.bnr/1000 for broadcast com.lge.bnr/.receiver.DamagedFileRemover
,I/ActivityManager( 1278): Start proc 8818:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager( 1278): Killing 8254:com.lge.appbox.client/u0a9 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 8849:com.lge.cic.eden.service/u0a7 for broadcast com.lge.cic.eden.service/com.lge.cic.eden.receiver.EdenBroadcastReceiver
,I/ActivityManager( 1278): Start proc 8873:com.lge.clock/u0a16 for broadcast com.lge.clock/.alarmclock.ToneMappingReceiver
,I/ActivityManager( 1278): Killing 8276:com.android.cellbroadcastreceiver/u0a14 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 8299:com.lge.email/u0a56 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 8322:com.android.contacts/u0a18 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 8896:com.android.gallery3d/u0a55 for broadcast com.android.gallery3d/com.lge.gallery.app.GalleryGlobalReceiver
,I/ActivityManager( 1278): Killing 8434:com.lge.hiddenmenu/1000 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 8412): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 8412): 
,I/jxcore-log( 8412): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8412): 
,I/ActivityManager( 1278): Killing 8471:com.android.providers.partnerbookmarks/u0a103 (adj 15): empty #22
,I/ActivityManager( 1278): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
I/ActivityManager( 1278): Killing 8412:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1278): Force removing ActivityRecord{70d7fe8 u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1278): Force stopping com.example.hello appid=10360 user=0: pkg removed
,W/ActivityManager( 1278): Spurious death for ProcessRecord{2e193983 8412:com.example.hello/u0a360}, curProc for 8412: null
,I/ActivityManager( 1278): Start proc 8945:com.lge.sizechangable.weather/u0a136 for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget
,I/ActivityManager( 1278): Start proc 8966:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1278): Displayed com.lge.launcher2/.Launcher: +251ms (total +22s214ms)
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 8995:com.lge.sizechangable.weather.platform/u0a96 for broadcast com.lge.sizechangable.weather.platform/.receiver.WeatherPlatformCommonReceiver
,I/ActivityManager( 1278): Killing 8497:com.lge.eula/u0a105 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 9016:com.lge.myplace/u0a30 for broadcast com.lge.myplace/.Receiver
,I/ActivityManager( 1278): Killing 8067:com.lge.lifetracker/u0a137 (adj 15): empty #22


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2887 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  761): Displayed com.example.hello/.MainActivity: +464ms (total +34s924ms)
,W/jxcore-log( 2887): Initializing JXcore engine
W/jxcore-log( 2887): JXcore engine is ready
,W/jxcore-log( 2887): Starting JXcore engine
,W/jxcore-log( 2887): Platform android
W/jxcore-log( 2887): 
,W/jxcore-log( 2887): Process ARCH arm
W/jxcore-log( 2887): 
,I/jxcore-log( 2887): JXcore Cordova bridge is ready!
I/jxcore-log( 2887): 
,W/jxcore-log( 2887): JXcore engine is started
,E/jxcore-log( 2887): >> LGE-Nexus 5
E/jxcore-log( 2887): 
I/jxcore-log( 2887): Total memory 1946181632
I/jxcore-log( 2887): 
I/jxcore-log( 2887): Free memory 330657792
I/jxcore-log( 2887): 
I/jxcore-log( 2887): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2887): 
I/jxcore-log( 2887): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2887): 
I/jxcore-log( 2887): userPath [ 'www' ]
I/jxcore-log( 2887): 
,I/jxcore-log( 2887): Size 1080 1776
I/jxcore-log( 2887): 
,I/jxcore-log( 2887): Screen Brightness 82
I/jxcore-log( 2887): 
,E/jxcore-log( 2887): Dummy Error Log.
E/jxcore-log( 2887): 
,I/jxcore-log( 2887): getBuffer is called!!!!
I/jxcore-log( 2887): 
,V/ActivityManager(  761): Display changed displayId=0
,I/jxcore-log( 2887): ****TEST TOOK:  5064  ms ****
I/jxcore-log( 2887): 
I/jxcore-log( 2887): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2887): 
,I/ActivityManager(  761): Killing 2344:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  761): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2887:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{16171989 u0 com.example.hello/.MainActivity t214}
V/ActivityManager(  761): Display changed displayId=0
W/ActivityManager(  761): Spurious death for ProcessRecord{146ce5d9 2887:com.example.hello/u0a277}, curProc for 2887: null
I/ActivityManager(  761): Force stopping com.example.hello appid=10277 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{16171989 u0 com.example.hello/.MainActivity t214 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{16171989 u0 com.example.hello/.MainActivity t214 f}
,I/ActivityManager(  761): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3045 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3077 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2381:com.google.android.youtube/u0a80 (adj 15): empty #17
,I/ActivityManager(  761): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3097 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2504:com.google.android.deskclock/u0a38 (adj 15): empty #17


LGE-LG-D722: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager(  957): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3186 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 3002} abi=armeabi-v7a
I/ActivityManager(  957): Killing 1905:com.android.printspooler/u0a87 (adj 15): empty #11
I/ActivityManager(  957): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  957): setTaskToReturnTo : TaskRecord{30f03ce9 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  957): setTaskToReturnTo : TaskRecord{30f03ce9 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
E/ActivityThread( 3186): Failed to find provider info for com.lge.ims.rcs
E/ActivityThread( 3186): Failed to find provider info for com.lge.ims.rcs
I/ActivityManager(  957): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3219 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityManager(  957): enqueue in BackgroundQueue #52 Intent=Intent { act=com.lge.qremote.action.wait_loading flg=0x14 cmp=com.lge.qremote/.appwidget.RemoteAppWidgetProvider (has extras) }
,E/ActivityThread( 3186): Failed to find provider info for com.lge.ims.provider.uc
,I/ActivityManager(  957): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=3288 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  957): Displayed com.example.hello/.MainActivity: +1s170ms
,I/ActivityManager(  957): Killing 2521:com.lge.qremote/u0a106 (adj 15): empty #11
,I/ActivityManager(  957): Killing 2939:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/jxcore-log( 3219): Initializing JXcore engine
W/jxcore-log( 3219): JXcore engine is ready
,W/jxcore-log( 3219): Starting JXcore engine
I/ActivityManager(  957): Start proc com.android.contacts for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver: pid=3314 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/jxcore-log( 3219): Platform android
W/jxcore-log( 3219): 
,W/jxcore-log( 3219): Process ARCH arm
W/jxcore-log( 3219): 
,I/jxcore-log( 3219): JXcore Cordova bridge is ready!
I/jxcore-log( 3219): 
W/jxcore-log( 3219): JXcore engine is started
E/jxcore-log( 3219): >> LGE-LG-D722
E/jxcore-log( 3219): 
,I/jxcore-log( 3219): Total memory 906309632
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Free memory 29802496
I/jxcore-log( 3219): 
I/jxcore-log( 3219): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3219): 
I/jxcore-log( 3219): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3219): 
I/jxcore-log( 3219): userPath [ 'www' ]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Size 720 1196
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Screen Brightness 255
I/jxcore-log( 3219): 
E/jxcore-log( 3219): Dummy Error Log.
E/jxcore-log( 3219): 
,I/ActivityManager(  957): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.wcdma_only.log_service.FactorySIMReceiver: pid=3340 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  957): Killing 2984:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/ActivityManager(  957): Start proc com.android.providers.partnerbookmarks for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver: pid=3357 uid=10071 gids={50071, 9997} abi=armeabi-v7a
I/ActivityManager(  957): Killing 3031:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
W/ActivityManager(  957): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
I/ActivityManager(  957): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3376 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  957): Killing 3050:com.lge.email/u0a21 (adj 15): empty #11
I/jxcore-log( 3219): getBuffer is called!!!!
I/jxcore-log( 3219): 
I/ActivityManager(  957): Killing 2494:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/ActivityManager(  957): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,W/ActivityManager(  957): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  957): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3412 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  957): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3442 uid=10008 gids={50008, 9997} abi=armeabi-v7a
,I/ActivityManager(  957): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3461 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3072:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.email for broadcast com.lge.email/.ui.widget.EmailWidgetProvider: pid=3483 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3095:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  957): Killing 3119:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=3507 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  957): Killing 3143:com.android.browser/u0a12 (adj 15): empty #11
W/ActivityManager(  957): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,I/ActivityManager(  957): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3524 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  957): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3554 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3288:com.android.settings/1000 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3585 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  957): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3605 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3357:com.android.providers.partnerbookmarks/u0a71 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3637 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3376:com.lge.eula/1000 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3654 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3314:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  957): Killing 3412:com.android.keychain/1000 (adj 15): empty #11
,I/ActivityManager(  957): Killing 3340:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3676 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  957): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3701 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  957): Killing 3442:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3734 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3461:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3760 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/jxcore-log( 3219): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3219): 
,I/ActivityManager(  957): Killing 3483:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  957): Waited long enough for: ServiceRecord{e627888 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,I/ActivityManager(  957): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3791 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  957): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3811 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 2459:com.android.defcontainer/u0a4 (adj 15): empty #11
,I/ActivityManager(  957): Waited long enough for: ServiceRecord{6a6d282 u0 com.lge.sizechangable.weather/.service.WeatherService}
,I/ActivityManager(  957): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3843 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  957): Killing 3524:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/ActivityManager(  957): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
,I/ActivityManager(  957): Killing 3219:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  957): Force removing ActivityRecord{e0f1d6e u0 com.example.hello/.MainActivity t219}: app died, no saved state
,I/ActivityManager(  957): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  957): Killing 3585:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  957): Killing 3605:com.lge.clock/u0a10 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3864 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  957): Spurious death for ProcessRecord{3f985f7 3219:com.example.hello/u0a30}, curProc for 3219: null
,I/ActivityManager(  957): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  957): Killing 3637:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  957): Killing 3654:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  957): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3910 uid=10062 gids={50062, 9997} abi=armeabi-v7a


```

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
W/ActivityManager( 2420): mDVFSHelper.acquire()
D/ActivityThread( 6595): Added TimaKesytore provider
,W/ActivityManager( 2420): mDVFSHelper.release()
W/jxcore-log( 6595): Initializing JXcore engine
W/jxcore-log( 6595): JXcore engine is ready
W/jxcore-log( 6595): Starting JXcore engine
W/jxcore-log( 6595): Platform android
W/jxcore-log( 6595): 
W/jxcore-log( 6595): Process ARCH arm
W/jxcore-log( 6595): 
,I/jxcore-log( 6595): JXcore Cordova bridge is ready!
I/jxcore-log( 6595): 
,W/jxcore-log( 6595): JXcore engine is started
,E/jxcore-log( 6595): >> samsung-SM-G800F
E/jxcore-log( 6595): 
,I/jxcore-log( 6595): Total memory 1319530496
I/jxcore-log( 6595): 
,I/jxcore-log( 6595): Free memory 32092160
I/jxcore-log( 6595): 
I/jxcore-log( 6595): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6595): 
,I/jxcore-log( 6595): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6595): 
,I/jxcore-log( 6595): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6595): 
,I/jxcore-log( 6595): Size 720 1280
I/jxcore-log( 6595): 
,I/jxcore-log( 6595): Screen Brightness 134
I/jxcore-log( 6595): 
,E/jxcore-log( 6595): Dummy Error Log.
E/jxcore-log( 6595): 
,I/jxcore-log( 6595): getBuffer is called!!!!
I/jxcore-log( 6595): 
,I/jxcore-log( 6595): ****TEST TOOK:  5099  ms ****
I/jxcore-log( 6595): 
,I/jxcore-log( 6595): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6595): 
,I/ActivityManager( 2420): Killing 6595:com.example.hello/u0a398 (adj 0): stop com.example.hello
,W/ActivityManager( 2420): Force removing ActivityRecord{43349f78 u0 com.example.hello/.MainActivity t4}: app died, no saved state,
,W/ActivityManager( 2420): mDVFSHelper.acquire()
,D/ActivityThread( 6664): Added TimaKesytore provider
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/ActivityThread( 6679): Added TimaKesytore provider,
,I/ActivityManager( 2420): Killing 5580:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/ActivityThread( 6700): Added TimaKesytore provider
,D/ActivityThread( 6716): Added TimaKesytore provider
,D/ActivityThread( 6746): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 5746:com.android.calendar/u0a144 (adj 15): empty #43
,D/ActivityThread( 6762): Added TimaKesytore provider
,I/ActivityManager( 2420): Killing 5778:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/ActivityThread( 6776): Added TimaKesytore provider
,D/ActivityThread( 6788): Added TimaKesytore provider,
,I/ActivityManager( 2420): Killing 5782:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43,
,I/ActivityManager( 2420): Killing 5298:com.google.android.talk/u0a109 (adj 15): empty #43
,I/ActivityManager( 2420): Process com.google.android.apps.docs (pid 6788) (adj 0) has died.,


motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3576
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3592 uid=10329 gids={50329, 3003, 3001, 3002}
,I/ActivityManager( 1018): Displayed com.example.hello/.MainActivity: +351ms (total +374ms)
,W/jxcore-log( 3592): Initializing JXcore engine
W/jxcore-log( 3592): JXcore engine is ready
W/jxcore-log( 3592): Starting JXcore engine
W/jxcore-log( 3592): Platform android
W/jxcore-log( 3592): 
W/jxcore-log( 3592): Process ARCH arm
W/jxcore-log( 3592): 
I/jxcore-log( 3592): JXcore Cordova bridge is ready!
I/jxcore-log( 3592): 
W/jxcore-log( 3592): JXcore engine is started
E/jxcore-log( 3592): >> motorola-XT1039
E/jxcore-log( 3592): 
I/jxcore-log( 3592): Total memory 893136896
I/jxcore-log( 3592): 
I/jxcore-log( 3592): Free memory 30683136
I/jxcore-log( 3592): 
I/jxcore-log( 3592): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3592): 
I/jxcore-log( 3592): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3592): 
I/jxcore-log( 3592): userPath [ 'www' ]
I/jxcore-log( 3592): 
I/jxcore-log( 3592): Size 720 1184
I/jxcore-log( 3592): 
I/jxcore-log( 3592): Screen Brightness 10
I/jxcore-log( 3592): 
E/jxcore-log( 3592): Dummy Error Log.
E/jxcore-log( 3592): 
I/jxcore-log( 3592): getBuffer is called!!!!
I/jxcore-log( 3592): 
,I/jxcore-log( 3592): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 3592): 
I/jxcore-log( 3592): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3592): 
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10329 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 3592:com.example.hello/u0a329 (adj 0): stop com.example.hello
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{42381db8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10329 user=0: pkg removed
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{42381db8 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{42381db8 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3677 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1018): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3698 uid=10058 gids={50058}
,I/ActivityManager( 1018): Killing 3288:com.android.providers.calendar/u0a8 (adj 15): empty #9
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3714 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1018): Killing 3451:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1018): Killing 3420:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1018): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3729 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 3158:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{21dd0b80 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{21dd0b80 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1036): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5982 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1036): Display changed displayId=0
,I/ActivityManager( 1036): Displayed com.example.hello/.MainActivity: +555ms (total +674ms)
,W/jxcore-log( 5982): Initializing JXcore engine
,W/jxcore-log( 5982): JXcore engine is ready
,W/jxcore-log( 5982): Starting JXcore engine
,W/jxcore-log( 5982): Platform android
W/jxcore-log( 5982): 
W/jxcore-log( 5982): Process ARCH arm
W/jxcore-log( 5982): 
,I/jxcore-log( 5982): JXcore Cordova bridge is ready!
I/jxcore-log( 5982): 
W/jxcore-log( 5982): JXcore engine is started
,E/jxcore-log( 5982): >> LGE-LG-D855
E/jxcore-log( 5982): 
I/jxcore-log( 5982): Total memory 2995761152
I/jxcore-log( 5982): 
I/jxcore-log( 5982): Free memory 672030720
I/jxcore-log( 5982): 
I/jxcore-log( 5982): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5982): 
I/jxcore-log( 5982): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5982): 
,I/jxcore-log( 5982): userPath [ 'www' ]
I/jxcore-log( 5982): 
I/jxcore-log( 5982): Size 1440 2392
I/jxcore-log( 5982): 
I/jxcore-log( 5982): Screen Brightness 50
I/jxcore-log( 5982): 
E/jxcore-log( 5982): Dummy Error Log.
E/jxcore-log( 5982): 
I/jxcore-log( 5982): getBuffer is called!!!!
I/jxcore-log( 5982): 
,I/jxcore-log( 5982): ****TEST TOOK:  5065  ms ****
I/jxcore-log( 5982): 
I/jxcore-log( 5982): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5982): 
,I/ActivityManager( 1036): Killing 5312:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1036): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1036): Killing 5982:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1036):   Force finishing activity ActivityRecord{299f15b9 u0 com.example.hello/.MainActivity t2}
,W/ActivityManager( 1036): Spurious death for ProcessRecord{2f68e8a4 5982:com.example.hello/u0a318}, curProc for 5982: null
I/ActivityManager( 1036): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{299f15b9 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{299f15b9 u0 com.example.hello/.MainActivity t2 f}
,I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6137 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 4457:com.google.android.talk/u0a72 (adj 15): empty #17
,I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6163 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 6163): Failed to find provider info for com.lge.lgaccount.provider
,I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6187 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 5611:com.google.android.apps.plus/u0a97 (adj 15): empty #17


```

####Node name: thali05
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/50388019dad02bc/build_android/android_0_50388019dad02bc.apk) to device 1d6a772d protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_50388019dad02bc.apk: No such file or directory



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
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1019): mDVFSHelper.acquire()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5366 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5366): Added TimaKeyStore provider
V/ActivityManager( 1019): Display changed displayId=0
V/ActivityThread( 1461): updateVisibility : ActivityRecord{1494de24 token=android.os.BinderProxy@14ed2522 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{3def96b3 u0 com.example.hello/.MainActivity t19}
,V/ActivityThread( 5366): updateVisibility : ActivityRecord{fc8bec7 token=android.os.BinderProxy@45922e1 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1019): Displayed Component not be shown by security: +640ms (total +717ms)
,W/ActivityManager( 1019): mDVFSHelper.release()
,W/jxcore-log( 5366): Initializing JXcore engine
W/jxcore-log( 5366): JXcore engine is ready
,W/jxcore-log( 5366): Starting JXcore engine
,W/jxcore-log( 5366): Platform android
W/jxcore-log( 5366): 
W/jxcore-log( 5366): Process ARCH arm
W/jxcore-log( 5366): 
,I/jxcore-log( 5366): JXcore Cordova bridge is ready!
I/jxcore-log( 5366): 
,W/jxcore-log( 5366): JXcore engine is started
,E/jxcore-log( 5366): >> samsung-SM-A300FU
E/jxcore-log( 5366): 
,I/jxcore-log( 5366): Total memory 1451114496
I/jxcore-log( 5366): 
,I/jxcore-log( 5366): Free memory 19210240
I/jxcore-log( 5366): 
I/jxcore-log( 5366): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5366): 
I/jxcore-log( 5366): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5366): 
,I/jxcore-log( 5366): userPath [ 'www' ]
I/jxcore-log( 5366): 
,I/jxcore-log( 5366): Size 540 960
I/jxcore-log( 5366): 
,I/jxcore-log( 5366): Screen Brightness 160
I/jxcore-log( 5366): 
,E/jxcore-log( 5366): Dummy Error Log.
E/jxcore-log( 5366): 
,I/jxcore-log( 5366): getBuffer is called!!!!
I/jxcore-log( 5366): 
,I/jxcore-log( 5366): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 5366): 
,I/jxcore-log( 5366): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5366): 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5366:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{3def96b3 u0 com.example.hello/.MainActivity t19}
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5431 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 5431): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/ActivityManager( 1019): Killing 4910:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5451 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,D/ActivityThread( 5451): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5468 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1019): Killing 4930:com.wssyncmldm/1000 (adj 15): empty #31
,D/ActivityThread( 5468): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5485 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5494 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,D/ActivityThread( 5485): Added TimaKeyStore provider
,D/ActivityThread( 5494): Added TimaKeyStore provider


HTC-HTC One M8s: 
--------- beginning of system
I/ActivityManager(  954): Recipient 4528
--------- beginning of main
,I/ActivityManager(  954): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5195 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
I/ActivityManager(  954): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  954): Killing 4551:com.android.smith/1000 (adj 15): empty #17
I/ActivityManager(  954): Recipient 4551
I/ActivityManager(  954): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5208 on display 0
I/ActivityManager(  954): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5272 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  954): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5295 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/ActivityManager(  954): Killing 4609:com.google.android.gms:car/u0a24 (adj 15): empty #17
I/ActivityManager(  954): Recipient 4609
,I/ActivityManager(  954): Killing 4572:com.android.vending/u0a72 (adj 15): empty #17
I/ActivityManager(  954): Recipient 4572
I/ActivityManager(  954): Waited long enough for: ServiceRecord{1891c942 u0 com.htc.HTCSpeaker/.NGFService}
I/ActivityManager(  954): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5324 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  954): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4482): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  954): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4482): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  954): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5384 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/ActivityManager(  954): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5417 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ActivityThread( 5384): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  954): Killing 3748:com.android.defcontainer/u0a15 (adj 15): empty #17
I/ActivityManager(  954): Recipient 3748
I/ActivityManager(  954): Displayed com.example.hello/.MainActivity: +1s360ms
I/ActivityManager(  954): Killing 4767:com.google.android.youtube/u0a176 (adj 15): empty #17
W/jxcore-log( 5272): Initializing JXcore engine
W/jxcore-log( 5272): JXcore engine is ready
W/jxcore-log( 5272): Starting JXcore engine
I/ActivityManager(  954): Recipient 4767
I/ActivityManager(  954): Killing 4846:com.google.android.gm/u0a106 (adj 15): empty #17
I/ActivityManager(  954): Recipient 4846
,W/jxcore-log( 5272): Platform android,
W/jxcore-log( 5272): 
W/jxcore-log( 5272): Process ARCH arm
W/jxcore-log( 5272): 
,I/jxcore-log( 5272): JXcore Cordova bridge is ready!
I/jxcore-log( 5272): 
,W/jxcore-log( 5272): JXcore engine is started
,E/jxcore-log( 5272): >> HTC-HTC One M8s
E/jxcore-log( 5272): 
,I/jxcore-log( 5272): Total memory 1931808768
I/jxcore-log( 5272): 
I/jxcore-log( 5272): Free memory 85725184
I/jxcore-log( 5272): 
I/jxcore-log( 5272): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5272): 
I/jxcore-log( 5272): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5272): 
I/jxcore-log( 5272): userPath [ 'www' ]
I/jxcore-log( 5272): 
,I/ActivityManager(  954): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5473 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/jxcore-log( 5272): Size 1080 1776
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Screen Brightness 142
I/jxcore-log( 5272): 
E/jxcore-log( 5272): Dummy Error Log.
E/jxcore-log( 5272): 
,I/ActivityManager(  954): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5498 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/ActivityManager(  954): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5527 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  954): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5549 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
I/ActivityManager(  954): Killing 5056:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,I/jxcore-log( 5272): getBuffer is called!!!!
I/jxcore-log( 5272): ,
,I/ActivityManager(  954): Recipient 5056
,I/ActivityManager(  954): Killing 5086:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 5086,
,I/ActivityManager(  954): Killing 5111:com.htc.mobiledata/u0a46 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 5111,
,I/ActivityManager(  954): Killing 4132:com.htc.sense.mms/u0a64 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 4132,
I/ActivityManager(  954): Killing 5032:com.htc.mobiledata:remote/u0a46 (adj 15): empty #18
,I/ActivityManager(  954): Recipient 5032,
,I/ActivityManager(  954): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5580 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
I/ActivityManager(  954): Killing 5132:com.htc.sense.news/u0a74 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 5132
,I/ActivityManager(  954): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5625 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,I/ActivityManager(  954): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5650 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  954): Killing 4734:com.google.android.talk/u0a112 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 4734
,I/ActivityManager(  954): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5683 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  954): Killing 5195:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 5195,
,I/ActivityManager(  954): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5716 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  954): Killing 5245:com.htc.backupreset/1000 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 5245
,I/ActivityManager(  954): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5750 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,I/ActivityManager(  954): Killing 5473:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 5473,
,W/ActivityThread( 5683): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  954): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=5781 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,I/ActivityManager(  954): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.googleplus/com.htc.plugin.googleplus.GooglePlusSocialPluginService: pid=5813 uid=10021 gids={50021, 9997, 3003, 1028, 1015, 1023} abi=arm64-v8a,
,I/ActivityManager(  954): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5844 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  954): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5857 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  954): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5895 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  954): Killing 5498:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 5498
,I/ActivityManager(  954): Killing 4919:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 4919
,I/ActivityManager(  954): Killing 5527:com.htc.cs.dm/u0a99 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 5527,
,I/ActivityManager(  954): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5919 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,I/jxcore-log( 5272): ****TEST TOOK:  5114  ms ****
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5272): 
,I/ActivityManager(  954): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5958 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/ActivityManager(  954): Killing 5549:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 5549
,I/ActivityManager(  954): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  954): Resuming delayed broadcast
,I/ActivityManager(  954): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,I/ActivityManager(  954): Killing 5272:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  954): Recipient 5272
,W/ActivityManager(  954): Force removing ActivityRecord{3331cd92 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  954): Force stopping com.example.hello appid=10373 user=0: pkg removed,
,W/ActivityManager(  954): Spurious death for ProcessRecord{14e50cf7 5272:com.example.hello/u0a373}, curProc for 5272: null
,I/ActivityManager(  954): Killing 5384:com.google.android.gms:car/u0a24 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 5384,
,I/ActivityManager(  954): Killing 4482:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 4482,
,I/ActivityManager(  954): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6036 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  954): Killing 5324:com.android.vending/u0a72 (adj 15): empty #17,
,I/ActivityManager(  954): Recipient 5324
,I/ActivityManager(  954): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6076 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/ActivityManager(  954): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager(  954): App crashed! Process: com.google.android.gm
,I/ActivityManager(  954): Killing 5580:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,I/ActivityManager(  954): Recipient 5580


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 3337:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ef80 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3929
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ef80 stackId=1, 2 tasks}
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{4322ef80 stackId=1, 2 tasks}
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  966): startService SlideAside
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ef80 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  966): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3947 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/ActivityManager( 3947): Timeline: Activity_idle id: android.os.BinderProxy@4286d3f8 time:47184
I/ActivityManager(  966): Displayed com.example.hello/.MainActivity: +394ms
W/jxcore-log( 3947): Initializing JXcore engine
W/jxcore-log( 3947): JXcore engine is ready
W/jxcore-log( 3947): Starting JXcore engine
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3} time:47567
D/ActivityManager(  966): no-history finish of ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{4309ae48 ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 3947): Platform android
W/jxcore-log( 3947): 
W/jxcore-log( 3947): Process ARCH arm
W/jxcore-log( 3947): 
I/jxcore-log( 3947): JXcore Cordova bridge is ready!
I/jxcore-log( 3947): 
W/jxcore-log( 3947): JXcore engine is started
,E/jxcore-log( 3947): >> LGE-LG-D802
E/jxcore-log( 3947): 
,I/jxcore-log( 3947): Total memory 1943035904
I/jxcore-log( 3947): 
I/jxcore-log( 3947): Free memory 470626304
I/jxcore-log( 3947): 
,I/jxcore-log( 3947): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3947): 
,I/jxcore-log( 3947): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3947): 
,I/jxcore-log( 3947): userPath [ 'www' ]
I/jxcore-log( 3947): 
,I/jxcore-log( 3947): Size 1080 1776
I/jxcore-log( 3947): 
,I/jxcore-log( 3947): Screen Brightness 255
I/jxcore-log( 3947): 
,E/jxcore-log( 3947): Dummy Error Log.
E/jxcore-log( 3947): 
,I/jxcore-log( 3947): getBuffer is called!!!!
I/jxcore-log( 3947): 
,I/ActivityManager(  966): Killing 3380:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ef80 stackId=1, 2 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3947): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 3947): 
,I/jxcore-log( 3947): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3947): 
,I/ActivityManager(  966): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  966): Killing 3947:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  966): Force removing ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3 f} (removed from history)
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{43287540 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{4322ef80 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  966): moveHomeStack:
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
,V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{42c5bfc8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4032 uid=10090 gids={50090}
,I/ActivityManager(  966): Killing 3279:com.google.android.music:main/u0a107 (adj 15): empty #17
,I/ActivityManager(  966): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4046 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
F/ActivityManager(  966): Service ServiceRecord{431ef228 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{430a9060 3279:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  966): Service ServiceRecord{430b52b0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{430a9060 3279:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Killing 2078:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4070 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  966): Delaying start of: ServiceRecord{43277100 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1} time:54201
,I/ActivityManager(  966): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4091 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  966): Killing 3726:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  966): Killing 3199:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4105 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  966): Killing 3818:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ba4640 stackId=0, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{430db150 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  966): Delaying start of: ServiceRecord{42c8a710 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager( 1488): Timeline: Activity_idle id: android.os.BinderProxy@42869f10 time:54475


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
--------- beginning of system
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
--------- beginning of main
I/ActivityManager(  887): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6241 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 6241): Added TimaKeyStore provider
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  887): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=6264 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 6264): Added TimaKeyStore provider
I/ActivityManager(  887): Killing 5390:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  887): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=6282 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 6282): Added TimaKeyStore provider
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  887): mDVFSHelper.acquire()
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  887): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6314 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6314): Added TimaKeyStore provider
V/ActivityManager(  887): Display changed displayId=0
I/ActivityManager(  887): Killing 5406:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6365 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 6365): Added TimaKeyStore provider
D/ActivityManager(  887): post active user change for 0
W/ActivityManager(  887): mDVFSHelper.release()
W/ActivityThread( 6365): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/jxcore-log( 6314): Initializing JXcore engine
W/jxcore-log( 6314): JXcore engine is ready
W/jxcore-log( 6314): Starting JXcore engine
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  887): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6419 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/jxcore-log( 6314): Platform android
W/jxcore-log( 6314): 
W/jxcore-log( 6314): Process ARCH arm
W/jxcore-log( 6314): 
,I/ActivityManager(  887): Killing 4604:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,D/ActivityThread( 6419): Added TimaKeyStore provider
,I/jxcore-log( 6314): JXcore Cordova bridge is ready!
I/jxcore-log( 6314): 
,W/jxcore-log( 6314): JXcore engine is started
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5044:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,E/ActivityThread( 6365): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@11293928 that was originally bound here
E/ActivityThread( 6365): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@11293928 that was originally bound here
E/ActivityThread( 6365): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 6365): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 6365): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 6365): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 6365): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6365): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 6365): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6365): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6365): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6365): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 6365): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 6365): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 6365): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 6365): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 6365): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 6365): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 6365): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 6365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 6365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6365): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6365): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 6365): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6365): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager(  887): Killing 5547:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,D/ActivityThread( 6443): Added TimaKeyStore provider
,E/jxcore-log( 6314): >> samsung-SM-G900F
E/jxcore-log( 6314): 
,I/jxcore-log( 6314): Total memory 1787449344
I/jxcore-log( 6314): 
,I/jxcore-log( 6314): Free memory 50401280
I/jxcore-log( 6314): 
I/jxcore-log( 6314): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6314): 
I/jxcore-log( 6314): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6314): 
,I/jxcore-log( 6314): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6314): 
,I/jxcore-log( 6314): Size 1080 1920
I/jxcore-log( 6314): 
,I/jxcore-log( 6314): Screen Brightness 134
I/jxcore-log( 6314): 
,E/jxcore-log( 6314): Dummy Error Log.
E/jxcore-log( 6314): 
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6458 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5566:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,D/ActivityThread( 6458): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 5582:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6478 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6478): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 4871:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=6501 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6501): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=6521 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5288:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/jxcore-log( 6314): getBuffer is called!!!!
I/jxcore-log( 6314): 
,D/ActivityThread( 6521): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=6540 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,D/ActivityThread( 6540): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 4948:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/ActivityManager(  887): Process com.samsung.indexservice (pid 6521)(adj 11) has died(56,587)
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6567 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6567): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 5133:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/ActivityManager(  887): Killing 5621:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/jxcore-log( 6314): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 6314): 
,I/jxcore-log( 6314): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6314): 
,I/ActivityManager(  887): Killing 5645:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/ActivityManager(  887): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  887): Killing 6314:com.example.hello/u0a374 (adj 0): stop com.example.hello
,I/ActivityManager(  887):   Force finishing activity ActivityRecord{2710b525 u0 com.example.hello/.MainActivity t11}
,I/ActivityManager(  887): Force stopping com.example.hello appid=10374 user=0: pkg removed
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6655 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{110e4018 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/ActivityThread( 6655): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6675 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5685:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/ActivityThread( 6675): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6692 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5742:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/ActivityThread( 6692): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6708 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5776:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/ActivityThread( 6708): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=6725 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5786:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/ActivityThread( 6725): Added TimaKeyStore provider
,E/ActivityThread( 6725): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  887): Process com.samsung.android.sdk.samsunglink (pid 6725)(adj 0) has died(171,571)
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6741 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6741): Added TimaKeyStore provider
,E/ActivityThread( 6741): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  887): Process com.osp.app.signin (pid 6741)(adj 0) has died(171,571)
,I/ActivityManager(  887): Process android.process.acore (pid 1769)(adj 0) has died(180,571)


samsung-SM-A500FU: 
--------- beginning of main
--------- beginning of system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4003 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4003): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4019 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3149:com.dropbox.android/u0a92 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 3191:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
D/ActivityThread( 4019): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4044 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4044): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 3207:com.fmm.ds/1000 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4060 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4060): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/ActivityManager( 1015): Killing 3239:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4088 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityThread( 4088): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4112 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3004:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3264:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #32
D/ActivityThread( 4112): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4130 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3319:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
D/ActivityThread( 4130): Added TimaKeyStore provider
W/ActivityManager( 1015): getTasks: caller 10146 does not hold GET_TASKS; limiting output
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): getTasks: caller 10145 does not hold GET_TASKS; limiting output
I/ActivityManager( 1015): Killing 3305:com.wssnps/1000 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/ActivityManager( 1015): Process com.android.exchange (pid 4112)(adj 9) has died(45,1098)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Process com.android.email (pid 4060)(adj 11) has died(49,1098)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): mDVFSHelper.acquire()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4163 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
V/ActivityThread( 1487): updateVisibility : ActivityRecord{2f66ccb9 token=android.os.BinderProxy@3d314456 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4163): Added TimaKeyStore provider
V/ActivityThread( 1487): updateVisibility : ActivityRecord{2f66ccb9 token=android.os.BinderProxy@3d314456 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,I/ActivityManager( 1015): Displayed Component not be shown by security: +766ms
,W/ActivityManager( 1015): mDVFSHelper.release()
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4226 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0,
,D/ActivityThread( 4226): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings


```

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
--------- beginning of system
W/ActivityManager( 1017): mDVFSHelper.acquire()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5084 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5084): Added TimaKeyStore provider
V/ActivityManager( 1017): Display changed displayId=0
V/ActivityThread( 1474): updateVisibility : ActivityRecord{c8d0b43 token=android.os.BinderProxy@4955bb3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{22ae4a24 u0 com.example.hello/.MainActivity t10}
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
V/ActivityThread( 5084): updateVisibility : ActivityRecord{2ff91eeb token=android.os.BinderProxy@347f9565 {com.example.hello/com.example.hello.MainActivity}} show : true
I/ActivityManager( 1017): Displayed Component not be shown by security: +691ms (total +779ms)
W/ActivityManager( 1017): mDVFSHelper.release()
,W/jxcore-log( 5084): Initializing JXcore engine
W/jxcore-log( 5084): JXcore engine is ready
,W/jxcore-log( 5084): Starting JXcore engine
,W/jxcore-log( 5084): Platform android
W/jxcore-log( 5084): 
W/jxcore-log( 5084): Process ARCH arm
W/jxcore-log( 5084): 
,I/jxcore-log( 5084): JXcore Cordova bridge is ready!
I/jxcore-log( 5084): 
,W/jxcore-log( 5084): JXcore engine is started
,E/jxcore-log( 5084): >> samsung-SM-A300FU
E/jxcore-log( 5084): 
,I/jxcore-log( 5084): Total memory 1451114496
I/jxcore-log( 5084): 
,I/jxcore-log( 5084): Free memory 21032960
I/jxcore-log( 5084): 
,I/jxcore-log( 5084): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5084): 
I/jxcore-log( 5084): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5084): 
,I/jxcore-log( 5084): userPath [ 'www' ]
I/jxcore-log( 5084): 
,I/jxcore-log( 5084): Size 540 960
I/jxcore-log( 5084): 
,I/jxcore-log( 5084): Screen Brightness 255
I/jxcore-log( 5084): 
,E/jxcore-log( 5084): Dummy Error Log.
E/jxcore-log( 5084): 
,I/jxcore-log( 5084): getBuffer is called!!!!
I/jxcore-log( 5084): 
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{2a2560ad u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5084): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 5084): 
,I/jxcore-log( 5084): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5084): 
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 5084:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{22ae4a24 u0 com.example.hello/.MainActivity t10},
,W/ActivityManager( 1017): Spurious death for ProcessRecord{1e961225 5084:com.example.hello/u0a333}, curProc for 5084: null
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5153 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5168 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 5153): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,D/ActivityThread( 5168): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5185 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5185): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5200 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 5200): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5219 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,D/ActivityThread( 5219): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5236 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3898:com.android.providers.calendar/u0a37 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 4238:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5236): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5253 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityThread( 5253): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5236): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5278 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 4184:com.google.android.music:main/u0a108 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3556:com.google.android.talk/u0a102 (adj 15): empty #31
,D/ActivityThread( 5278): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4586:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 4603:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 4765:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5303 uid=10086 gids={50086, 9997} abi=armeabi-v7a
,D/ActivityThread( 5303): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4703:com.google.android.gms:car/u0a11 (adj 15): empty #31


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main,
--------- beginning of /dev/log/system
I/ActivityManager(  900): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2291
I/ActivityManager(  900): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2302 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/ActivityManager(  900): Waited long enough for: ServiceRecord{425afc18 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2343 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  900): Displayed com.example.hello/.MainActivity: +279ms
,I/ActivityManager(  900): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2356 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  900): Killing 1911:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 1911
,I/ActivityManager(  900): Killing 1963:com.htc.showme/u0a82 (adj 15): empty #17
,I/ActivityManager(  900): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2374 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  900): Recipient 1963
,I/ActivityManager(  900): Killing 1975:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,I/ActivityManager(  900): Delay finish: com.android.providers.calendar/.CalendarReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,W/jxcore-log( 2302): Initializing JXcore engine
,W/jxcore-log( 2302): JXcore engine is ready
,I/ActivityManager(  900): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2392 uid=10016 gids={50016, 3003, 5012, 2001}
,W/jxcore-log( 2302): Starting JXcore engine
,I/ActivityManager(  900): Recipient 1975
,I/ActivityManager(  900): Killing 2078:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2078
,I/ActivityManager(  900): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2417 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  900): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2435 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
,I/ActivityManager(  900): Killing 2066:com.htc.mediamanager/u0a32 (adj 15): empty #17
,W/jxcore-log( 2302): Platform android
W/jxcore-log( 2302): 
,W/jxcore-log( 2302): Process ARCH arm
W/jxcore-log( 2302): 
,I/ActivityManager(  900): Killing 1929:com.htc.contacts/u0a41 (adj 15): empty #17
,I/jxcore-log( 2302): JXcore Cordova bridge is ready!
I/jxcore-log( 2302): 
,W/jxcore-log( 2302): JXcore engine is started
,I/ActivityManager(  900): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/ActivityManager(  900): Recipient 1929
I/ActivityManager(  900): Recipient 2066
I/ActivityManager(  900): Resuming delayed broadcast
,E/jxcore-log( 2302): >> HTC-HTC Desire 820
E/jxcore-log( 2302): 
,I/ActivityManager(  900): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/jxcore-log( 2302): Total memory 1964650496
I/jxcore-log( 2302): 
I/jxcore-log( 2302): Free memory 815587328
I/jxcore-log( 2302): 
I/jxcore-log( 2302): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2302): 
I/jxcore-log( 2302): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2302): 
I/jxcore-log( 2302): userPath [ 'www' ]
I/jxcore-log( 2302): 
I/jxcore-log( 2302): Size 720 1184
I/jxcore-log( 2302): 
I/jxcore-log( 2302): Screen Brightness 10
I/jxcore-log( 2302): 
E/jxcore-log( 2302): Dummy Error Log.
E/jxcore-log( 2302): 
,W/ActivityManager(  900): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2471 uid=10030 gids={50030}
,I/ActivityManager(  900): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2485 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  900): Killing 2133:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2133
,I/ActivityManager(  900): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Killing 2163:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2163
,I/jxcore-log( 2302): getBuffer is called!!!!
I/jxcore-log( 2302): 
I/ActivityManager(  900): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2509 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  900): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2521 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  900): Killing 2182:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2182
,I/ActivityManager(  900): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2533 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  900): Killing 2107:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2107
,I/ActivityManager(  900): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2550 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
I/ActivityManager(  900): Killing 1869:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/ActivityManager(  900): Killing 1848:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  900): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2562 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  900): Recipient 1869
,I/ActivityManager(  900): Recipient 1848
,I/ActivityManager(  900): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2576 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  900): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2592 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
I/ActivityManager(  900): Killing 1654:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,I/ActivityManager(  900): Killing 1947:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 1654
,I/ActivityManager(  900): Recipient 1947
,I/ActivityManager(  900): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2607 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  900): Killing 2343:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  900): Killing 2356:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  900): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2621 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007},
,I/ActivityManager(  900): Recipient 2356
,I/ActivityManager(  900): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Killing 2374:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  900): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  900): Recipient 2374
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2647 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,I/ActivityManager(  900): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2659 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  900): Killing 2392:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2392
,I/ActivityManager(  900): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2674 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,I/ActivityManager(  900): Killing 2417:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2417
,I/ActivityManager(  900): Delay finish: com.htc.lmw/.StorageBroadcastReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Delay finish: com.android.providers.media/.MediaScannerReceiver
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{42549ad8 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2691 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  900): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2715 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/ActivityManager(  900): Killing 2435:com.htc.fm/u0a24 (adj 15): empty #17
,I/ActivityManager(  900): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
,I/ActivityManager(  900): Recipient 2435
,I/jxcore-log( 2302): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 2302): 
I/jxcore-log( 2302): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2302): 
,I/ActivityManager(  900): Waited long enough for: ServiceRecord{426131a8 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2739 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/ActivityManager(  900): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2780 uid=10077 gids={50077}
,I/ActivityManager(  900): Killing 2471:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2471
,I/ActivityManager(  900): Killing 2485:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2485
I/ActivityManager(  900): Delay finish: com.android.systemui/.BootReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2796 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,I/ActivityManager(  900): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2810 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  900): Killing 2509:com.htc.csrecommend/u0a33 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2509
,I/ActivityManager(  900): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  900): Resuming delayed broadcast
,I/ActivityManager(  900): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2824 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
,I/ActivityManager(  900): Killing 2521:com.htc.home.personalize/1000 (adj 15): empty #17
I/ActivityManager(  900): Recipient 2521
,I/ActivityManager(  900): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  900): Killing 2302:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  900): Force removing ActivityRecord{4289a388 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  900): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  900): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/ActivityManager(  900): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=2843 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  900): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
,I/ActivityManager(  900): Killing 2533:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  900): Recipient 2533
,E/ActivityManager(  900): App crashed! Process: com.google.android.googlequicksearchbox:search


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2928 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 2500:com.htc.lmw/u0a60 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2500
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2946 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 2600:com.htc.reportagent/u0a66 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2600
I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2959 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  908): Killing 2618:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2618
I/ActivityManager(  908): Killing 2630:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2630
I/ActivityManager(  908): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2983 uid=9987 gids={49987}
I/ActivityManager(  908): Killing 2644:com.htc.updater/u0a85 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2644
I/ActivityManager(  908): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2999 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  908): Killing 2673:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2673
I/ActivityManager(  908): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3011 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 2529:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2529
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2940
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3025 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
,I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +282ms
I/ActivityManager(  908): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2733:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2733
W/jxcore-log( 3025): Initializing JXcore engine
W/jxcore-log( 3025): JXcore engine is ready
W/jxcore-log( 3025): Starting JXcore engine
W/jxcore-log( 3025): Platform android
W/jxcore-log( 3025): 
W/jxcore-log( 3025): Process ARCH arm
W/jxcore-log( 3025): 
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/jxcore-log( 3025): JXcore Cordova bridge is ready!
I/jxcore-log( 3025): 
W/jxcore-log( 3025): JXcore engine is started
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
E/jxcore-log( 3025): >> HTC-HTC Desire 820
E/jxcore-log( 3025): 
I/jxcore-log( 3025): Total memory 1964650496
I/jxcore-log( 3025): 
I/jxcore-log( 3025): Free memory 685506560
I/jxcore-log( 3025): 
I/jxcore-log( 3025): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3025): 
I/jxcore-log( 3025): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3025): 
I/jxcore-log( 3025): userPath [ 'www' ]
I/jxcore-log( 3025): 
I/jxcore-log( 3025): Size 720 1184
I/jxcore-log( 3025): 
I/jxcore-log( 3025): Screen Brightness 142
I/jxcore-log( 3025): 
E/jxcore-log( 3025): Dummy Error Log.
E/jxcore-log( 3025): 
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.frp.FrpUpdateIntentService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/jxcore-log( 3025): getBuffer is called!!!!
I/jxcore-log( 3025): 
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3146 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 2752:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Delay finish: com.htc.dotmatrix/.CoverStateReceiver
I/ActivityManager(  908): Recipient 2752
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3186 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Killing 2765:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2765
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3225 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  908): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3237 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007},
,I/ActivityManager(  908): Killing 2794:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  908): Killing 2779:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3253 uid=10041 gids={50041}
,I/ActivityManager(  908): Recipient 2794
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3268 uid=10078 gids={50078}
,I/ActivityManager(  908): Killing 2850:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  908): Killing 2876:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2876
,I/ActivityManager(  908): Recipient 2779
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3283 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Recipient 2850
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3299 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  908): Killing 2828:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2828
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3314 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3328 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 2895:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2895
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3343 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  908): Killing 2910:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2910
,I/ActivityManager(  908): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3356 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3368 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  908): Killing 2983:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  908): Killing 2959:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  908): Recipient 2983
,I/ActivityManager(  908): Recipient 2959
,I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3384 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  908): Killing 2999:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2999
,I/ActivityManager(  908): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3398 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
I/ActivityManager(  908): Killing 3011:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3146:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3146
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  908): Recipient 3011
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3426 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  908): Killing 2946:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2946
,I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3446 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 3186:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3186
,I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3463 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 3225:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3225
,I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3480 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3498 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 3237:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3237
,I/ActivityManager(  908): Killing 3283:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3283
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/jxcore-log( 3025): ****TEST TOOK:  5058  ms ****
I/jxcore-log( 3025): 
,I/jxcore-log( 3025): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3025): 
I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3521 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,I/ActivityManager(  908): Killing 3025:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  908): Force removing ActivityRecord{424ef148 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3553 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  908): Killing 2928:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2928
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  773): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.ads.preload.PreloadVideosTransferService$DeviceStateReceiver
I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Killing 1488:com.google.android.dialer/u0a8 (adj 15): empty #17
I/ActivityManager(  773): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2082 uid=10058 gids={50058, 3003, 1028, 1015}
,I/ActivityManager(  773): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2094
I/ActivityManager(  773): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2122 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  773): Killing 1538:com.google.android.configupdater/u0a2 (adj 15): empty #17
I/ActivityManager(  773): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Killing 1579:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
,I/ActivityManager(  773): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  773): Displayed com.example.hello/.MainActivity: +303ms
,W/jxcore-log( 2122): Initializing JXcore engine
,W/jxcore-log( 2122): JXcore engine is ready
,W/jxcore-log( 2122): Starting JXcore engine
,W/jxcore-log( 2122): Platform android
W/jxcore-log( 2122): 
,W/jxcore-log( 2122): Process ARCH arm
W/jxcore-log( 2122): 
,I/jxcore-log( 2122): JXcore Cordova bridge is ready!
I/jxcore-log( 2122): 
,W/jxcore-log( 2122): JXcore engine is started
,E/jxcore-log( 2122): >> LGE-Nexus 5
E/jxcore-log( 2122): 
,I/jxcore-log( 2122): Total memory 1945137152
I/jxcore-log( 2122): 
I/jxcore-log( 2122): Free memory 936038400
I/jxcore-log( 2122): 
I/jxcore-log( 2122): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2122): 
,I/jxcore-log( 2122): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2122): 
,I/jxcore-log( 2122): userPath [ 'www' ]
I/jxcore-log( 2122): 
,I/jxcore-log( 2122): Size 1080 1776
I/jxcore-log( 2122): 
,I/jxcore-log( 2122): Screen Brightness 82
I/jxcore-log( 2122): 
,E/jxcore-log( 2122): Dummy Error Log.
E/jxcore-log( 2122): 
,I/jxcore-log( 2122): getBuffer is called!!!!
I/jxcore-log( 2122): 
,I/ActivityManager(  773): Killing 1249:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast,
,I/ActivityManager(  773): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2258 uid=10011 gids={50011, 3003}
,I/ActivityManager(  773): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2276 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  773): Killing 1625:com.android.vending/u0a14 (adj 15): empty #17
,I/ActivityManager(  773): Killing 1698:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  773): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2291 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  773): Killing 1740:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  773): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  773): Delaying start of: ServiceRecord{42c6c760 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/jxcore-log( 2122): ****TEST TOOK:  5026  ms ****
I/jxcore-log( 2122): 
,I/jxcore-log( 2122): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2122): 
,I/ActivityManager(  773): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  773): Killing 2122:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  773): Force removing ActivityRecord{42ef5ee8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  773): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  773): Resuming delayed broadcast


```




###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AC820B7A-4D13-437F-97CD-606269ED97F0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AC820B7A-4D13-437F-97CD-606269ED97F0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B9399C37-866A-426D-A42D-0B9C93149161/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54782"
,(lldb)     command script import "/tmp/AC820B7A-4D13-437F-97CD-606269ED97F0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-11 15:25:59.117 HelloWorld[1997:2310756] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B161EF1F-D0B0-4D8F-8494-D3449A6663D4/Library/Cookies/Cookies.binarycookies
,2015-11-11 15:25:59.495 HelloWorld[1997:2310756] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-11 15:25:59.496 HelloWorld[1997:2310756] Multi-tasking -> Device: YES, App: YES
,2015-11-11 15:25:59.499 HelloWorld[1997:2310756] Unlimited access to network resources
,2015-11-11 15:25:59.505 HelloWorld[1997:2310756] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-11 15:26:03.214 HelloWorld[1997:2310756] Resetting plugins due to page load.
,2015-11-11 15:26:03.653 HelloWorld[1997:2310756] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/B9399C37-866A-426D-A42D-0B9C93149161/HelloWorld.app/www/index.html
,2015-11-11 15:26:03.764 HelloWorld[1997:2310756] JXcore Cordova plugin initializing
2015-11-11 15:26:03.765 HelloWorld[1997:2310870] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 124391424
execPath /private/var/mobile/Containers/Bundle/Application/B9399C37-866A-426D-A42D-0B9C93149161/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/B9,399C37-866A-426D-A42D-0B9C93149161/HelloWorld.app/www/jxcore/
userPath []
2015-11-11 15:26:04.032 HelloWorld[1997:2310870] Native method ScreenInfo not found.
2015-11-11 15:26:04.033 HelloWorld[1997:2310870] Native method ScreenBrightness not found.
Du,mmy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5117  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F8AE54D6-9511-4496-99C0-43C73C0AF1BB/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F8AE54D6-9511-4496-99C0-43C73C0AF1BB/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/7714EFCC-1060-4002-958F-C250F200BE3B/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54780"
,(lldb)     command script import "/tmp/F8AE54D6-9511-4496-99C0-43C73C0AF1BB/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-11 15:26:20.093 HelloWorld[1599:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-11 15:26:20.096 HelloWorld[1599:60b] Multi-tasking -> Device: YES, App: YES
2015-11-11 15:26:20.101 HelloWorld[1599:60b] Unlimited access to network resources
2015-11-11 15:26:20.106 HelloWorld[1599:60b] 

Started backup to iCloud! Please be ca,reful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, se,t the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-11 15:26:26.255 HelloWorld[1599:60b] Resetting plugins due to page load.
,2015-11-11 15:26:26.752 HelloWorld[1599:60b] Finished load of: file:///var/mobile/Applications/7714EFCC-1060-4002-958F-C250F200BE3B/HelloWorld.app/www/index.html
,2015-11-11 15:26:26.831 HelloWorld[1599:60b] JXcore Cordova plugin initializing
,2015-11-11 15:26:26.832 HelloWorld[1599:6807] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 478498816
execPath /private/var/mobile/Applications/7714EFCC-1060-4002-958F-C250F200BE3B/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/7714EFCC-1060-4002-958F-C250F200BE3B/HelloWor,ld.app/www/jxcore/
userPath []
,2015-11-11 15:26:27.199 HelloWorld[1599:6807] Native method ScreenInfo not found.
,2015-11-11 15:26:27.203 HelloWorld[1599:6807] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5172  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A630EE84-BCDF-4F8B-8D35-7715FEE21746/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A630EE84-BCDF-4F8B-8D35-7715FEE21746/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ABF128BE-CC1B-4DC9-B05A-9D12F9A8B073/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54785"
,(lldb)     command script import "/tmp/A630EE84-BCDF-4F8B-8D35-7715FEE21746/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-11 15:25:57.059 HelloWorld[3078:3409839] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88AAE18C-9381-43E2-944B-25BC587DCCD9/Library/Cookies/Cookies.binarycookies
,2015-11-11 15:25:57.345 HelloWorld[3078:3409839] Apache Cordova native platform version 3.9.2 is starting.
2015-11-11 15:25:57.346 HelloWorld[3078:3409839] Multi-tasking -> Device: YES, App: YES
,2015-11-11 15:25:57.348 HelloWorld[3078:3409839] Unlimited access to network resources
2015-11-11 15:25:57.352 HelloWorld[3078:3409839] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much dat,a.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-11 15:25:59.581 HelloWorld[3078:3409839] Resetting plugins due to page load.
,2015-11-11 15:25:59.748 HelloWorld[3078:3409839] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/ABF128BE-CC1B-4DC9-B05A-9D12F9A8B073/HelloWorld.app/www/index.html
,2015-11-11 15:25:59.796 HelloWorld[3078:3409839] JXcore Cordova plugin initializing
2015-11-11 15:25:59.797 HelloWorld[3078:3409926] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
,Total memory 1035988992
,Free memory 80637952
,execPath /private/var/mobile/Containers/Bundle/Application/ABF128BE-CC1B-4DC9-B05A-9D12F9A8B073/HelloWorld.app/HelloWorld
,process.cwd /private/var/mobile/Containers/Bundle/Application/ABF128BE-CC1B-4DC9-B05A-9D12F9A8B073/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-11 15:25:59.979 HelloWorld[3078:3409926] Native method ScreenInfo not found.
,2015-11-11 15:25:59.980 HelloWorld[3078:3409926] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5084  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4193E30D-5848-4C89-9644-4F1737E55145/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4193E30D-5848-4C89-9644-4F1737E55145/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50388019dad02bc/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/90E019F5-FA65-40F7-8CF5-9DB020C4B29A/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54779"
,(lldb)     command script import "/tmp/4193E30D-5848-4C89-9644-4F1737E55145/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-11 15:25:56.927 HelloWorld[2038:4477056] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F23B88AE-10F4-4B88-970E-21C31484D849/Library/Cookies/Cookies.binarycookies
,2015-11-11 15:25:57.214 HelloWorld[2038:4477056] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-11 15:25:57.214 HelloWorld[2038:4477056] Multi-tasking -> Device: YES, App: YES
,2015-11-11 15:25:57.216 HelloWorld[2038:4477056] Unlimited access to network resources
,2015-11-11 15:25:57.221 HelloWorld[2038:4477056] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-11 15:26:01.496 HelloWorld[2038:4477056] Resetting plugins due to page load.
,2015-11-11 15:26:02.943 HelloWorld[2038:4477056] Finished load of: file:///var/mobile/Containers/Bundle/Application/90E019F5-FA65-40F7-8CF5-9DB020C4B29A/HelloWorld.app/www/index.html
,2015-11-11 15:26:02.989 HelloWorld[2038:4477056] JXcore Cordova plugin initializing
,2015-11-11 15:26:02.990 HelloWorld[2038:4477230] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
Total memory 2084569088
Free memory 387694592
execPath /private/var/mobile/Containers/Bundle/Application/90E019F5-FA65-40F7-8CF5-9DB020C4B29A/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/90E019F5-FA65-40F7-8CF5-9DB020C4B29A/HelloWorld.app/www/jxcore/
userPath []
2015-11-11 15:26:03.164 HelloWorld[2038:4477230] Native method ScreenInfo not found.
2015-11-11 15:26:03.164 HelloWorld[2038:4477230] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5100  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50388019dad02bc/serverApp/index.js',
  '{"devices":{"ios":4,"android":18,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 18, cancel: 1 } }


```

