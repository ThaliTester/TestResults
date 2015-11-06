#### Test 476722347fc8662 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_476722347fc8662/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":22,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 22, cancel: 1 } }



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
Error: problem stopping Android apk(com.example.hello) to device 30049d9501da2100 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 03157df360a1882a error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device W3D7N15428022572 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device LGH8153b36be34 error: device not found
 
```

Logcat output:
```
samsung-SM-T232: 
--------- beginning of /dev/log/system
I/ActivityManager( 1197): rtcc_minfree = 82449,70671,58892,47114,35335
I/ActivityManager( 1197): Config changes=1df8 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h961dp 213dpi lrg port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
I/ActivityManager( 1197): Config changes=408 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port ?uimode ?night finger -keyb/v/h -nav/h s.3}
I/ActivityManager( 1197): System now ready
I/ActivityManager( 1197): Config changes=200 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port finger -keyb/v/h -nav/h s.4}
I/ActivityManager( 1197): !@ mBooting is set true!
I/ActivityManager( 1197): RTCC_TRIGGER_MSG, ASYNC.
W/ActivityManager( 1197): mDVFSHelper.release()
W/ActivityManager( 1197): Unable to start service Intent { cmp=com.samsung.android.app.gestureservice/.GestureService } U=0: not found
W/ActivityManager( 1197): !@call fb1: post finishBooting() with 1000msec delay
I/ActivityManager( 1197): !@Boot: bootcomplete
I/ActivityManager( 1197): Killing 2745:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2774:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 1587:com.android.printspooler/u0a118 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2724:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2897:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2914:com.samsung.android.app.memo/u0a130 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2927:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2998:com.sec.phone/u0a127 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3060:com.google.android.configupdater/u0a2 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3088:com.sec.android.widgetapp.samsungapps/u0a120 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3133:com.sec.dsm.system/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3155:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3188:com.sec.factory/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3204:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3234:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 1492:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3255:com.android.onetimeinitializer/u0a21 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3270:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3298:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3314:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
W/ActivityManager( 1197): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1197): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1197): Killing 3328:com.osp.app.signin/u0a30 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2940:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2644:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 1643:com.android.settings/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3361:com.wssyncmldm/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2603:com.google.android.partnersetup/u0a11 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42ee0fa0 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42f3c428 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/ActivityManager( 1197): Killing 3384:com.google.android.googlequicksearchbox:search/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3420:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3404:com.samsung.android.intelligenceservice/u0a52 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3454:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1197): Process com.samsung.android.MtpApplication (pid 4157) (adj 0) has died.
I/ActivityManager( 1197): Killing 3472:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3486:com.wssnps/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3499:com.samsung.android.app.accesscontrol/u0a57 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{4309c2f8 u0 com.samsung.android.providers.context/.ContextService}
I/ActivityManager( 1197): Killing 3516:com.sec.android.app.FileShareServer/u0a62 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3535:com.sec.android.nearby.mediaserver/u0a63 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3550:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
W/ActivityManager( 1197): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
I/ActivityManager( 1197): Killing 3564:com.sec.android.app.bluetoothtest/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3577:com.blurb.checkout/u0a67 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{4304f7c0 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42ef0298 u0 com.sec.esdk.elm/.service.ElmAgentService}
I/ActivityManager( 1197): Process com.sec.android.app.sysscope (pid 3932) (adj 0) has died.
I/ActivityManager( 1197): Process com.sec.factory (pid 4144) (adj 0) has died.
I/ActivityManager( 1197): Killing 3590:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3606:com.dropbox.android/u0a78 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3649:com.sec.factory.camera/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3663:com.samsung.android.app.watchmanagerstub/u0a86 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3736:com.samsung.scrc.idi.server/u0a91 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42d97b98 u0 com.android.exchange/.ExchangeService}
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42f30d68 u0 com.android.exchange/.service.ExchangeBroadcastProcessorService}
I/ActivityManager( 1197): Killing 3750:com.samsung.helphub/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3763:com.LocalFota/u0a92 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3780:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3807:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42f0cdb8 u0 com.rxnetworks.rxnservicesxybrid/com.rxnetworks.rxnserviceslib.RXNetworksService}
I/ActivityManager( 1197): Killing 3831:com.sec.android.app.camera/u0a121 (adj 15): bgCount ##33
W/ActivityManager( 1197): mDVFSHelper.acquire()
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{430ef810 u0 com.samsung.android.MtpApplication/.MtpService}
W/ActivityManager( 1197): mDVFSHelper.release()
I/ActivityManager( 1197): Killing 1698:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3900:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3917:com.sec.android.app.worldclock/u0a135 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3946:com.sec.android.app.controlpanel/u0a141 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3959:com.samsung.android.service.travel/u0a143 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3974:com.google.android.youtube/u0a146 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4042:com.gameloft.android.gdc:remote/u0a152 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4266:com.sec.spp.push:RemoteDlcProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4282:com.sec.spp.push:RemoteNotiProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4324:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3703:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4196:com.sec.android.widgetapp.SPlannerAppWidget/u0a34 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4225:com.android.calendar/u0a117 (adj 15): bgCount ##33
W/ActivityManager( 1197): mDVFSHelper.acquire()
W/ActivityManager( 1197): mDVFSHelper.release()
,--------- beginning of /dev/log/main
W/ActivityManager( 1197): mDVFSHelper.acquire()
W/ActivityManager( 1197): mDVFSHelper.release()
W/jxcore-log( 4919): Initializing JXcore engine
W/jxcore-log( 4919): JXcore engine is ready
W/jxcore-log( 4919): Starting JXcore engine
,W/jxcore-log( 4919): Platform android
W/jxcore-log( 4919): 
W/jxcore-log( 4919): Process ARCH arm
W/jxcore-log( 4919): 
I/jxcore-log( 4919): JXcore Cordova bridge is ready!
I/jxcore-log( 4919): 
W/jxcore-log( 4919): JXcore engine is started
E/jxcore-log( 4919): >> samsung-SM-T232
E/jxcore-log( 4919): 
I/jxcore-log( 4919): Total memory 1352024064
I/jxcore-log( 4919): 
I/jxcore-log( 4919): Free memory 220377088
I/jxcore-log( 4919): 
I/jxcore-log( 4919): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4919): 
I/jxcore-log( 4919): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4919): 
I/jxcore-log( 4919): userPath [ 'www' ]
I/jxcore-log( 4919): 
I/jxcore-log( 4919): Size 800 1280
I/jxcore-log( 4919): 
I/jxcore-log( 4919): Screen Brightness 143
I/jxcore-log( 4919): 
E/jxcore-log( 4919): Dummy Error Log.
E/jxcore-log( 4919): 
I/jxcore-log( 4919): getBuffer is called!!!!
I/jxcore-log( 4919): 
,I/jxcore-log( 4919): ****TEST TOOK:  5130  ms ****
I/jxcore-log( 4919): 
,I/jxcore-log( 4919): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4919): 
,I/ActivityManager( 1197): Killing 4919:com.example.hello/u0a357 (adj 0): stop com.example.hello
,I/ActivityManager( 1197): Killing 4212:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
,I/ActivityManager( 1197): Killing 3676:com.google.android.gm/u0a87 (adj 15): bgCount ##33
,I/ActivityManager( 1197): Killing 4388:com.sec.android.app.myfiles/u0a37 (adj 15): bgCount ##33


samsung-SM-G920F: 
--------- beginning of system
W/ActivityManager( 3487): mDVFSHelper.release()
,--------- beginning of main
I/ActivityManager( 3487): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3487): mDVFSHelper.acquire()
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9654 uid=10424 gids={50424, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 3487): Activity pause timeout for ActivityRecord{3e4a2986 u0 com.example.hello/.MainActivity t44}
,D/ActivityManager( 3487): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/ActivityManager( 3487): Displayed Component not be shown by security: +900ms
,W/ActivityManager( 3487): mDVFSHelper.release()
,W/jxcore-log( 9654): Initializing JXcore engine
W/jxcore-log( 9654): JXcore engine is ready
,W/jxcore-log( 9654): Starting JXcore engine
,W/jxcore-log( 9654): Platform android
W/jxcore-log( 9654): 
W/jxcore-log( 9654): Process ARCH arm
W/jxcore-log( 9654): 
,I/jxcore-log( 9654): JXcore Cordova bridge is ready!
I/jxcore-log( 9654): 
W/jxcore-log( 9654): JXcore engine is started
,E/jxcore-log( 9654): >> samsung-SM-G920F
E/jxcore-log( 9654): 
,I/jxcore-log( 9654): Total memory 2829074432
I/jxcore-log( 9654): 
I/jxcore-log( 9654): Free memory 58335232
I/jxcore-log( 9654): 
I/jxcore-log( 9654): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9654): 
I/jxcore-log( 9654): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9654): 
,I/jxcore-log( 9654): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9654): 
,I/jxcore-log( 9654): Size 1440 2560
I/jxcore-log( 9654): 
,I/jxcore-log( 9654): Screen Brightness 134
I/jxcore-log( 9654): 
E/jxcore-log( 9654): Dummy Error Log.
E/jxcore-log( 9654): 
,I/jxcore-log( 9654): getBuffer is called!!!!
I/jxcore-log( 9654): 
,I/jxcore-log( 9654): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 9654): 
,I/jxcore-log( 9654): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9654): 
,I/ActivityManager( 3487): Force stopping com.example.hello appid=10424 user=-1: uninstall pkg
,I/ActivityManager( 3487): Killing 9654:com.example.hello/u0a424 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3487):   Force finishing activity ActivityRecord{3e4a2986 u0 com.example.hello/.MainActivity t44}
,I/ActivityManager( 3487): Force stopping com.example.hello appid=10424 user=0: pkg removed
,W/ActivityManager( 3487): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9762 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
,W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5289, uid=10127 that is not exported from uid 10125
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 3487): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,I/ActivityManager( 3487): Killing 9188:com.sec.pcw.device/1000 (adj 15): empty #25
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9782 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=9796 uid=10054 gids={50054, 9997, 3003, 3002} abi=arm64-v8a
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=9812 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9828 uid=10102 gids={50102, 9997, 1028, 3003, 1015} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=9846 uid=10001 gids={50001, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=arm64-v8a
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9862 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3487): Killing 8675:com.samsung.android.app.galaxyfinder/u0a27 (adj 15): empty #25
,I/ActivityManager( 3487): Killing 9219:com.policydm/1000 (adj 15): empty #25
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.sec.android.app.vepreload for broadcast com.sec.android.app.vepreload/.VEExtensionPackUpdateReceiver: pid=9879 uid=10170 gids={50170, 9997, 1028, 1015, 1003, 3003} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3487): Killing 9239:com.sec.spp.push/u0a33 (adj 15): empty #25
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/ActivityManager( 3487): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3487): Killing 8690:com.google.android.apps.plus/u0a136 (adj 15): empty #25
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9901 uid=10027 gids={50027, 9997, 1028, 1015, 3003, 3002} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.vodafone.smhs, destAppInfo.processName = com.vodafone.smhs
,I/ActivityManager( 3487): Killing 9281:com.sec.spp.push:RemoteNotiProcess/u0a33 (adj 15): empty #25
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
,W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.SnippetsWidgetService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3487): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.DashboardsWidgetService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9940 uid=10136 gids={50136, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3487): Killing 8640:com.sec.android.app.shealth/u0a28 (adj 15): empty #25
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=9960 uid=10033 gids={50033, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/ActivityManager( 3487): Process com.google.android.gms (pid 4558)(adj 0) has died(207,1004)
,W/ActivityManager( 3487): Exception when unbinding service com.google.android.gms/.icing.service.LightweightIndexService
W/ActivityManager( 3487): android.os.TransactionTooLargeException
W/ActivityManager( 3487): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3487): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3487): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 3487): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1904)
W/ActivityManager( 3487): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2288)
W/ActivityManager( 3487): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18330)
W/ActivityManager( 3487): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6504)
W/ActivityManager( 3487): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6710)
W/ActivityManager( 3487): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1596)
W/ActivityManager( 3487): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.cast.media.CastMediaRouteProviderService in 11000ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 31000ms
,W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 30999ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 40999ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 50999ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 50999ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 50999ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 50999ms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/ActivityManager( 3487): Process com.google.process.gapps (pid 4298)(adj 0) has died(205,1004)
,W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 60968ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService$LightweightWorkerService in 70968ms
,W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.auth.GoogleAccountAuthenticatorService in 70968ms
W/ActivityManager( 3487): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 80968ms
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,I/ActivityManager( 2952): Displayed com.example.hello/.MainActivity: +907ms (total +979ms)
W/jxcore-log( 6698): Initializing JXcore engine
W/jxcore-log( 6698): JXcore engine is ready
W/jxcore-log( 6698): Starting JXcore engine
W/jxcore-log( 6698): Platform android
W/jxcore-log( 6698): 
W/jxcore-log( 6698): Process ARCH arm
W/jxcore-log( 6698): 
I/jxcore-log( 6698): JXcore Cordova bridge is ready!
I/jxcore-log( 6698): 
W/jxcore-log( 6698): JXcore engine is started
E/jxcore-log( 6698): >> HUAWEI-ALE-L21
E/jxcore-log( 6698): 
I/jxcore-log( 6698): Total memory 1949741056
I/jxcore-log( 6698): 
I/jxcore-log( 6698): Free memory 18735104
I/jxcore-log( 6698): 
I/jxcore-log( 6698): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6698): 
I/jxcore-log( 6698): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6698): 
I/jxcore-log( 6698): userPath [ 'www' ]
I/jxcore-log( 6698): 
I/jxcore-log( 6698): Size 720 1184
I/jxcore-log( 6698): 
I/jxcore-log( 6698): Screen Brightness 242
I/jxcore-log( 6698): 
E/jxcore-log( 6698): Dummy Error Log.
E/jxcore-log( 6698): 
,I/jxcore-log( 6698): getBuffer is called!!!!
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): ****TEST TOOK:  5098  ms ****
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6698): 
,I/ActivityManager( 2952): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2952): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1295): Start proc 8040:com.lge.lgdmsclient/1000 for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver
I/ActivityManager( 1295): Killing 7161:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #22
I/ActivityManager( 1295): Waited long enough for: ServiceRecord{13a6a0ea u0 com.lge.lpd/.service.LPDRegistReceiverService}
I/ActivityManager( 1295): Start proc 8061:com.lge.email/u0a56 for broadcast com.lge.email/.receiver.EmailSimChangedReceiver
I/ActivityManager( 1295): Killing 7182:com.lge.springcleaning/1000 (adj 15): empty #22
I/ActivityManager( 1295): Start proc 8104:com.android.contacts/u0a18 for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver
I/ActivityManager( 1295): Start proc 8131:com.android.settings/1000 for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver
I/ActivityManager( 1295): Killing 7222:com.lge.lockscreensettings/1000 (adj 15): empty #22
I/ActivityManager( 1295): Start proc 8153:com.lge.wifisettings/1000 for broadcast com.lge.wifisettings/.wifioffload.WiFiOffLoadBroadcast
I/ActivityManager( 1295): Killing 7245:com.lge.hiddenmenu/1000 (adj 15): empty #22
I/ActivityManager( 1295): Killing 7266:com.google.android.talk/u0a121 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8177:com.android.providers.partnerbookmarks/u0a103 for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver
I/ActivityManager( 1295): Start proc 8199:com.lge.hiddenmenu/1000 for broadcast com.lge.hiddenmenu/.SVC.log_service.FactorySIMReceiver
I/ActivityManager( 1295): Killing 7501:com.lge.ia.task.incalagent/u0a8 (adj 15): empty #22
I/ActivityManager( 1295): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1295): setTaskToReturnTo : TaskRecord{11704d67 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1295): setTaskToReturnTo : TaskRecord{11704d67 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1295): Start proc 8237:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1295): Start proc 8257:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseSIMObserver
I/ActivityManager( 1295): Killing 7522:com.android.providers.calendar/u0a19 (adj 15): empty #22
I/ActivityManager( 1295): Killing 7298:com.google.android.googlequicksearchbox:search/u0a63 (adj 15): empty #22
I/ActivityManager( 1295): Waited long enough for: ServiceRecord{294d3e25 u0 com.lge.springcleaning/.service.AppCleanupService}
I/ActivityManager( 1295): Start proc 8312:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
I/ActivityManager( 1295): Start proc 8332:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
I/ActivityManager( 1295): Killing 7543:com.google.android.youtube/u0a124 (adj 15): empty #22
I/ActivityManager( 1295): Displayed com.example.hello/.MainActivity: +951ms (total +21s95ms)
I/ActivityManager( 1295): Killing 7636:com.google.android.apps.maps/u0a119 (adj 15): empty #22
W/jxcore-log( 8237): Initializing JXcore engine
W/jxcore-log( 8237): JXcore engine is ready
W/jxcore-log( 8237): Starting JXcore engine
,W/jxcore-log( 8237): Platform android
W/jxcore-log( 8237): 
W/jxcore-log( 8237): Process ARCH arm
W/jxcore-log( 8237): 
,I/jxcore-log( 8237): JXcore Cordova bridge is ready!
I/jxcore-log( 8237): 
W/jxcore-log( 8237): JXcore engine is started
,E/jxcore-log( 8237): >> LGE-LG-H815
E/jxcore-log( 8237): 
I/jxcore-log( 8237): Total memory 2968948736
I/jxcore-log( 8237): 
I/jxcore-log( 8237): Free memory 108912640
I/jxcore-log( 8237): 
I/jxcore-log( 8237): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8237): 
I/jxcore-log( 8237): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8237): 
,I/jxcore-log( 8237): userPath [ 'www' ]
I/jxcore-log( 8237): 
,I/jxcore-log( 8237): Size 1440 2392
I/jxcore-log( 8237): 
,I/jxcore-log( 8237): Screen Brightness 255
I/jxcore-log( 8237): 
E/jxcore-log( 8237): Dummy Error Log.
E/jxcore-log( 8237): 
,I/ActivityManager( 1295): Start proc 8371:com.lge.qremote/u0a138 for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider
,I/ActivityManager( 1295): Start proc 8392:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
,I/ActivityManager( 1295): Killing 7673:com.google.android.gm/u0a113 (adj 15): empty #22
,I/jxcore-log( 8237): getBuffer is called!!!!
I/jxcore-log( 8237): 
,I/ActivityManager( 1295): Start proc 8428:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
,I/ActivityManager( 1295): Killing 7714:com.android.vending/u0a62 (adj 15): empty #22
,I/ActivityManager( 1295): Killing 7763:com.lge.qmemoplus/1000 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8457:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.lockscreen.QuickUnlockReceiver
,I/ActivityManager( 1295): Start proc 8480:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
,I/ActivityManager( 1295): Killing 7810:com.lge.lgaccount/u0a107 (adj 15): empty #22
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1295): Start proc 8504:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1295): Killing 7833:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1295): Killing 7869:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1295): Start proc 8549:com.lge.sync/1000 for broadcast com.lge.sync/.StartReceiver
,I/ActivityManager( 1295): Killing 7788:com.lge.lifetracker/u0a137 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8570:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
,I/ActivityManager( 1295): Killing 7333:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8595:com.lge.sizechangable.weather/u0a136 for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget
,I/ActivityManager( 1295): Killing 7935:com.lge.appbox.client:SingleBinaryService/u0a9 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8616:com.lge.bnr/1000 for broadcast com.lge.bnr/.receiver.DamagedFileRemover
,I/ActivityManager( 1295): Killing 7956:com.lge.appbox.client/u0a9 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8636:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager( 1295): Killing 7980:com.android.browser/u0a24 (adj 15): empty #22
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1295): Start proc 8665:com.lge.cic.eden.service/u0a7 for broadcast com.lge.cic.eden.service/com.lge.cic.eden.receiver.EdenBroadcastReceiver
,I/ActivityManager( 1295): Killing 8014:com.android.cellbroadcastreceiver/u0a14 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8687:com.lge.clock/u0a16 for broadcast com.lge.clock/.alarmclock.ToneMappingReceiver
,I/ActivityManager( 1295): Killing 8061:com.lge.email/u0a56 (adj 15): empty #22
,W/ActivityManager( 1295): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 8237): ****TEST TOOK:  5112  ms ****
I/jxcore-log( 8237): 
,I/jxcore-log( 8237): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8237): 
,I/ActivityManager( 1295): Killing 8104:com.android.contacts/u0a18 (adj 15): empty #22
,I/ActivityManager( 1295): Killing 8177:com.android.providers.partnerbookmarks/u0a103 (adj 15): empty #22
,I/ActivityManager( 1295): Start proc 8727:com.android.gallery3d/u0a55 for broadcast com.android.gallery3d/com.lge.gallery.app.GalleryGlobalReceiver
,I/ActivityManager( 1295): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
I/ActivityManager( 1295): Killing 8237:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1295): Force removing ActivityRecord{29108714 u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1295): Force stopping com.example.hello appid=10360 user=0: pkg removed
,W/ActivityManager( 1295): Spurious death for ProcessRecord{3f402eb 8237:com.example.hello/u0a360}, curProc for 8237: null
,I/ActivityManager( 1295): Start proc 8756:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1295): Displayed com.lge.launcher2/.Launcher: +170ms (total +26s444ms)
,I/ActivityManager( 1295): Killing 8199:com.lge.hiddenmenu/1000 (adj 15): empty #22


```

####Node name: thali02
Console output:
```
STOP log received from  FA533YJ03104 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on FA533YJ03104 
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 09a9416e0297d102 error: device not found
 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3016 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager(  735): Display changed displayId=0
,I/ActivityManager(  735): Displayed com.example.hello/.MainActivity: +352ms (total +1m10s671ms)
,W/jxcore-log( 3016): Initializing JXcore engine
W/jxcore-log( 3016): JXcore engine is ready
,W/jxcore-log( 3016): Starting JXcore engine
,W/jxcore-log( 3016): Platform android
W/jxcore-log( 3016): 
W/jxcore-log( 3016): Process ARCH arm
W/jxcore-log( 3016): 
,I/jxcore-log( 3016): JXcore Cordova bridge is ready!
I/jxcore-log( 3016): 
,W/jxcore-log( 3016): JXcore engine is started
,E/jxcore-log( 3016): >> LGE-Nexus 5
E/jxcore-log( 3016): 
I/jxcore-log( 3016): Total memory 1946181632
I/jxcore-log( 3016): 
I/jxcore-log( 3016): Free memory 361324544
I/jxcore-log( 3016): 
I/jxcore-log( 3016): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3016): 
I/jxcore-log( 3016): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3016): 
,I/jxcore-log( 3016): userPath [ 'www' ]
I/jxcore-log( 3016): 
,I/jxcore-log( 3016): Size 1080 1776
I/jxcore-log( 3016): 
,I/jxcore-log( 3016): Screen Brightness 82
I/jxcore-log( 3016): 
E/jxcore-log( 3016): Dummy Error Log.
E/jxcore-log( 3016): 
,I/jxcore-log( 3016): getBuffer is called!!!!
I/jxcore-log( 3016): 
,I/jxcore-log( 3016): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 3016): 
I/jxcore-log( 3016): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3016): 
,I/ActivityManager(  735): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 3016:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{5b124be u0 com.example.hello/.MainActivity t214}
,W/ActivityManager(  735): Spurious death for ProcessRecord{1d71da1e 3016:com.example.hello/u0a277}, curProc for 3016: null
I/ActivityManager(  735): Force stopping com.example.hello appid=10277 user=0: pkg removed
I/ActivityManager(  735):   Force finishing activity ActivityRecord{5b124be u0 com.example.hello/.MainActivity t214 f}
W/ActivityManager(  735): Duplicate finish request for ActivityRecord{5b124be u0 com.example.hello/.MainActivity t214 f}
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3115 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2317:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3148 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3172 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 1776:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/ActivityManager(  735): Killing 2489:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,--------- beginning of crash


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  972): Killing 3606:com.android.defcontainer/u0a4 (adj 15): empty #11
,I/ActivityManager(  972): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4645 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  972): Killing 4412:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4673 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  972): Killing 3949:com.google.android.talk/u0a61 (adj 15): empty #11
I/ActivityManager(  972): Killing 4459:com.android.settings/1000 (adj 15): empty #11
I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4706 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{297f76b9 #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{297f76b9 #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  972): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4728 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4761 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  972): Killing 4389:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/ActivityManager(  972): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4783 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4821 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 4490:com.lge.sync/1000 (adj 15): empty #11
,I/ActivityManager(  972): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4848 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  972): Killing 4371:com.lge.qremote/u0a106 (adj 15): empty #11
,I/ActivityManager(  972): Killing 4510:com.lge.clock/u0a10 (adj 15): empty #11
,I/ActivityManager(  972): Displayed com.example.hello/.MainActivity: +1s450ms
,I/ActivityManager(  972): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4876 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 4528:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/ActivityManager(  972): Killing 4554:com.lge.bnr/1000 (adj 15): empty #11
,W/jxcore-log( 4728): Initializing JXcore engine
W/jxcore-log( 4728): JXcore engine is ready
,W/jxcore-log( 4728): Starting JXcore engine
,W/jxcore-log( 4728): Platform android
W/jxcore-log( 4728): 
W/jxcore-log( 4728): Process ARCH arm
W/jxcore-log( 4728): 
,I/jxcore-log( 4728): JXcore Cordova bridge is ready!
I/jxcore-log( 4728): 
,W/jxcore-log( 4728): JXcore engine is started
E/jxcore-log( 4728): >> LGE-LG-D722
E/jxcore-log( 4728): 
,I/jxcore-log( 4728): Total memory 906309632
I/jxcore-log( 4728): 
I/jxcore-log( 4728): Free memory 28196864
I/jxcore-log( 4728): 
I/jxcore-log( 4728): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4728): 
I/jxcore-log( 4728): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4728): 
I/jxcore-log( 4728): userPath [ 'www' ]
I/jxcore-log( 4728): 
I/jxcore-log( 4728): Size 720 1196
I/jxcore-log( 4728): 
,I/jxcore-log( 4728): Screen Brightness 255
I/jxcore-log( 4728): 
E/jxcore-log( 4728): Dummy Error Log.
E/jxcore-log( 4728): 
,I/ActivityManager(  972): Killing 4590:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/jxcore-log( 4728): getBuffer is called!!!!
I/jxcore-log( 4728): 
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4934 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Waited long enough for: ServiceRecord{390ef8ef u0 com.lge.springcleaning/.service.AppCleanupService}
,I/ActivityManager(  972): Process com.lge.email (pid 4613) has died
,I/ActivityManager(  972): Process com.lge.appbox.client (pid 4673) has died
,I/ActivityManager(  972): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=4961 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4983 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Process com.android.gallery3d (pid 4706) has died
,I/ActivityManager(  972): Process com.android.contacts (pid 4761) has died
,I/ActivityManager(  972): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5051 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  972): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5113 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  972): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5138 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5160 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 4645:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/jxcore-log( 4728): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 4728): 
I/jxcore-log( 4728): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4728): 
,I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5213 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 4821:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5236 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  972): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  972): Killing 4728:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  972): Force removing ActivityRecord{d881afe u0 com.example.hello/.MainActivity t217}: app died, no saved state
,I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5272 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 4848:com.lge.eula/1000 (adj 15): empty #11
W/ActivityManager(  972): Spurious death for ProcessRecord{36aec3e3 4728:com.example.hello/u0a30}, curProc for 4728: null
,I/ActivityManager(  972): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5298 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 4876:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,I/ActivityManager(  972): Killing 4934:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5324 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a


HTC-HTC One M9: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1054): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=5070 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager( 1054): Killing 4383:com.htc.android.worldclock/u0a75 (adj 15): empty #17
I/ActivityManager( 1054): Recipient 4383
I/ActivityManager( 1054): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=5113 uid=10139 gids={50139, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 1054): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5142 uid=10061 gids={50061, 9997} abi=arm64-v8a
I/ActivityManager( 1054): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=5168 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager( 1054): Killing 4415:com.google.android.configupdater/u0a87 (adj 15): empty #17
I/ActivityManager( 1054): Recipient 4415
I/ActivityManager( 1054): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5138 on display 0
I/ActivityManager( 1054): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5218 uid=10193 gids={50193, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1054): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5242 uid=10008 gids={50008, 9997, 1028, 1015, 5001, 5011, 3003} abi=arm64-v8a
,I/ActivityManager( 1054): Killing 4491:com.google.android.gm/u0a95 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4491
,I/ActivityManager( 1054): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5290 uid=10062 gids={50062, 9997, 3003} abi=arm64-v8a
,I/ActivityManager( 1054): Start proc com.htc.updater for broadcast com.htc.updater/.download.DownloadReceiver: pid=5321 uid=10068 gids={50068, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
,I/ActivityManager( 1054): Killing 4463:com.htc.cs.dm/u0a88 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4463
,I/ActivityManager( 1054): Displayed com.example.hello/.MainActivity: +863ms
,W/jxcore-log( 5218): Initializing JXcore engine
,W/jxcore-log( 5218): JXcore engine is ready
I/ActivityManager( 1054): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5351 uid=10084 gids={50084, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/jxcore-log( 5218): Starting JXcore engine
,I/ActivityManager( 1054): Killing 4235:com.htc.sense.mms/u0a54 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4235
,W/jxcore-log( 5218): Platform android
W/jxcore-log( 5218): 
W/jxcore-log( 5218): Process ARCH arm
W/jxcore-log( 5218): 
,I/jxcore-log( 5218): JXcore Cordova bridge is ready!,
I/jxcore-log( 5218): 
W/jxcore-log( 5218): JXcore engine is started
,I/ActivityManager( 1054): Start proc com.aiqidii.mercury for broadcast com.aiqidii.mercury/.service.NetworkReceiver: pid=5373 uid=10086 gids={50086, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1054): Killing 4600:com.google.android.talk/u0a102 (adj 15): empty #17
,E/jxcore-log( 5218): >> HTC-HTC One M9,
E/jxcore-log( 5218): 
,I/jxcore-log( 5218): Total memory 2860257280
I/jxcore-log( 5218): 
I/jxcore-log( 5218): Free memory 191934464,
I/jxcore-log( 5218): 
I/jxcore-log( 5218): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5218): 
I/jxcore-log( 5218): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5218): 
,I/jxcore-log( 5218): userPath [ 'www' ],
I/jxcore-log( 5218): 
,I/jxcore-log( 5218): Size 1080 1776
I/jxcore-log( 5218): 
,I/jxcore-log( 5218): Screen Brightness 142
I/jxcore-log( 5218): ,
E/jxcore-log( 5218): Dummy Error Log.
E/jxcore-log( 5218): 
,I/ActivityManager( 1054): Recipient 4600
,I/ActivityManager( 1054): Killing 4648:com.htc.cs.pns:boot_complete/u0a119 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4648
,I/ActivityManager( 1054): Killing 4674:com.htc.cs.pns/u0a119 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4674
,I/jxcore-log( 5218): getBuffer is called!!!!
I/jxcore-log( 5218): 
,I/ActivityManager( 1054): Cannot resolve ContentProvider=com.google.android.wearable.settings
,I/ActivityManager( 1054): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5406 uid=10117 gids={50117, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager( 1054): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5480 uid=10126 gids={50126, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1054): Killing 4793:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4793,
,I/ActivityManager( 1054): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5510 uid=10020 gids={50020, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager( 1054): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5569 uid=10003 gids={50003, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/ActivityManager( 1054): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcSystemReceiver: pid=5608 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
,I/ActivityManager( 1054): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5632 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
,I/ActivityManager( 1054): Killing 4816:com.android.smith/1000 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4816
,I/ActivityManager( 1054): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5659 uid=10031 gids={50031, 9997, 3003, 1028, 3002, 3001} abi=arm64-v8a,
,I/ActivityManager( 1054): Killing 4830:com.android.settings:remote/1000 (adj 15): empty #17,
,I/ActivityManager( 1054): Recipient 4830
,I/ActivityManager( 1054): Killing 4861:com.htc.usage/1000 (adj 15): empty #17,
,I/ActivityManager( 1054): Recipient 4861
,I/ActivityManager( 1054): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5681 uid=10036 gids={50036, 9997, 3003, 1028, 3002, 3001} abi=arm64-v8a
,I/ActivityManager( 1054): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5706 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
,I/ActivityManager( 1054): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5737 uid=10024 gids={50024, 9997, 1028, 1015, 3003, 1023, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1054): Killing 4883:com.htc.WifiRouter/u0a134 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4883
,I/ActivityManager( 1054): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5766 uid=10012 gids={50012, 9997, 3003, 1028, 1015, 1023} abi=arm64-v8a,
,I/ActivityManager( 1054): Killing 4936:com.htc.themepicker/u0a59 (adj 15): empty #17,
,I/ActivityManager( 1054): Recipient 4936
,I/ActivityManager( 1054): Start proc com.htc.music:musicenhancer for broadcast com.htc.music/com.htc.musicenhancer.provider.MScannerReceiver: pid=5790 uid=10025 gids={50025, 9997, 1028, 1015, 3003, 3002, 1023} abi=armeabi-v7a,
,I/ActivityManager( 1054): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5812 uid=10064 gids={50064, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager( 1054): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver,
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Killing 5070:com.android.vending/u0a57 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 5070
,I/ActivityManager( 1054): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager( 1054): Resuming delayed broadcast,
,I/ActivityManager( 1054): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5843 uid=10095 gids={50095, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,W/ActivityManager( 1054): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager( 1054): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/ActivityManager( 1054): Killing 5113:com.htc.club/u0a139 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 5113,
,W/ActivityManager( 1054): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1054): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1054): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1054): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1054): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1054): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Cannot resolve ContentProvider=com.google.android.wearable.settings
,I/ActivityManager( 1054): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.htc.music/com.htc.musicenhancer.provider.MScannerReceiver,
,I/ActivityManager( 1054): Resuming delayed broadcast,
,I/ActivityManager( 1054): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver,
,I/ActivityManager( 1054): Resuming delayed broadcast,
,I/ActivityManager( 1054): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver,
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver,
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Start proc com.htc.autobot for broadcast com.htc.autobot/.AlarmReceiver: pid=5906 uid=10027 gids={50027, 9997, 3003, 3002, 3001, 1024, 5003} abi=arm64-v8a,
,I/ActivityManager( 1054): Killing 4554:com.htc.backup/u0a98 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4554
,I/ActivityManager( 1054): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.google.android.gm/.GmailReceiver
,I/jxcore-log( 5218): ****TEST TOOK:  5201  ms ****,
I/jxcore-log( 5218): 
I/jxcore-log( 5218): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5218): 
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver,
,I/ActivityManager( 1054): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5953 uid=10039 gids={50039, 9997, 3003, 1028} abi=arm64-v8a
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Killing 5142:com.htc.mms.backupagent/u0a61 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 5142
,I/ActivityManager( 1054): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver,
,W/ActivityManager( 1054): Unable to start service Intent { cmp=com.android.bluetooth/.map.BluetoothMapService (has extras) } U=0: not found
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver,
,I/ActivityManager( 1054): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5998 uid=10039 gids={50039, 9997, 3003, 1028} abi=arm64-v8a,
,I/ActivityManager( 1054): Recipient 3741
,I/ActivityManager( 1054): Process com.android.bluetooth (pid 3741) has died
,W/ActivityManager( 1054): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,I/ActivityManager( 1054): Force stopping com.example.hello appid=10193 user=0: pkg removed
I/ActivityManager( 1054): Killing 5218:com.example.hello/u0a193 (adj 0): stop com.example.hello
,I/ActivityManager( 1054): Recipient 5218,
,W/ActivityManager( 1054): Force removing ActivityRecord{1e4e264b u0 com.example.hello/.MainActivity t67}: app died, no saved state
,W/ActivityManager( 1054): Spurious death for ProcessRecord{1d028d30 5218:com.example.hello/u0a193}, curProc for 5218: null,
I/ActivityManager( 1054): Force stopping com.example.hello appid=10193 user=-1: uninstall pkg
,I/ActivityManager( 1054): Waited long enough for: ServiceRecord{39d6e21 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager( 1054): Resuming delayed broadcast,
,I/ActivityManager( 1054): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6032 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager( 1054): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6066 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/ActivityManager( 1054): Killing 5290:com.google.android.setupwizard/u0a62 (adj 15): empty #17,
,I/ActivityManager( 1054): Recipient 5290
,I/ActivityManager( 1054): Killing 5351:com.android.chrome/u0a84 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 5351
,I/ActivityManager( 1054): Killing 5406:com.google.android.apps.magazines/u0a117 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 5406
,E/ActivityManager( 1054): App crashed! Process: com.google.android.talk,
,I/ActivityManager( 1054): Killing 4693:tv.peel.app/u0a123 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 4693
,I/ActivityManager( 1054): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6103 uid=10023 gids={50023, 9997, 3003} abi=arm64-v8a
,E/ActivityManager( 1054): App crashed! Process: com.google.android.music:main
,I/ActivityManager( 1054): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast
,I/ActivityManager( 1054): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,I/ActivityManager( 1054): Resuming delayed broadcast,
,I/ActivityManager( 1054): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6131 uid=10088 gids={50088, 9997, 3003} abi=arm64-v8a
,I/ActivityManager( 1054): Killing 5480:com.google.android.apps.plus/u0a126 (adj 15): empty #17,
,I/ActivityManager( 1054): Recipient 5480,
,E/ActivityManager( 1054): App crashed! Process: com.google.android.googlequicksearchbox:search,
,I/ActivityManager( 1054): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6156 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1054): Killing 5632:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager( 1054): Recipient 5632,


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on 320414cd475f91e3 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 320414cd475f91e3 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device TA4750HV7I error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device LGD8553bed2d08 error: device not found
 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/ActivityManager( 2405): mDVFSHelper.acquire()
,W/ActivityManager( 2405): mDVFSHelper.release()
,W/jxcore-log( 6653): Initializing JXcore engine
,W/jxcore-log( 6653): JXcore engine is ready
,W/jxcore-log( 6653): Starting JXcore engine
,W/jxcore-log( 6653): Platform android
W/jxcore-log( 6653): 
,W/jxcore-log( 6653): Process ARCH arm
W/jxcore-log( 6653): 
,I/jxcore-log( 6653): JXcore Cordova bridge is ready!
I/jxcore-log( 6653): 
,W/jxcore-log( 6653): JXcore engine is started
,E/jxcore-log( 6653): >> samsung-SM-G800F
E/jxcore-log( 6653): 
,I/jxcore-log( 6653): Total memory 1319530496
I/jxcore-log( 6653): 
I/jxcore-log( 6653): Free memory 40161280
I/jxcore-log( 6653): 
I/jxcore-log( 6653): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6653): 
,I/jxcore-log( 6653): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6653): 
,I/jxcore-log( 6653): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6653): 
,I/jxcore-log( 6653): Size 720 1280
I/jxcore-log( 6653): 
,I/jxcore-log( 6653): Screen Brightness 134
I/jxcore-log( 6653): 
,E/jxcore-log( 6653): Dummy Error Log.
E/jxcore-log( 6653): 
,I/jxcore-log( 6653): getBuffer is called!!!!
I/jxcore-log( 6653): 
,I/jxcore-log( 6653): ****TEST TOOK:  5081  ms ****
I/jxcore-log( 6653): 
I/jxcore-log( 6653): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6653): 
,I/ActivityManager( 2405): Killing 6653:com.example.hello/u0a387 (adj 0): stop com.example.hello
,I/ActivityManager( 2405): Killing 5712:com.android.calendar/u0a144 (adj 15): empty #43
,I/ActivityManager( 2405): Killing 5566:com.google.android.music:main/u0a125 (adj 15): empty #43,
,I/ActivityManager( 2405): Process com.google.android.googlequicksearchbox:search (pid 5875) (adj 5) has died.
,I/ActivityManager( 2405): Process com.samsung.android.magazine.service (pid 6290) (adj 5) has died.
,I/ActivityManager( 2405): Process com.android.keychain (pid 6791) (adj 5) has died.
,I/ActivityManager( 2405): Process com.google.process.gapps (pid 2846) (adj 1) has died.
,I/ActivityManager( 2405): Process com.google.android.gms (pid 3435) (adj 0) has died.
,I/ActivityManager( 2405): Killing 5768:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/ActivityManager( 2405): Process com.android.documentsui (pid 6819) (adj 9) has died.
,I/ActivityManager( 2405): Process com.google.process.gapps (pid 6875) (adj 0) has died.
,W/ActivityManager( 2405): Service crashed 2 times, stopping: ServiceRecord{42fb8070 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
,W/ActivityManager( 2405): Service crashed 2 times, stopping: ServiceRecord{42e5c768 u0 com.google.android.gms/.gcm.GcmService}
,W/ActivityManager( 2405): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2405): Killing 6895:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2405): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2405): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
,I/ActivityManager( 2405): Process com.google.process.gapps (pid 6911) (adj 0) has died.,
,W/ActivityManager( 2405): Process com.google.process.gapps has crashed too many times: killing!,
I/ActivityManager( 2405): Killing 6928:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2405): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,I/ActivityManager( 2405): Process android.process.acore (pid 2991) (adj -12) has died.,
,I/ActivityManager( 2405): Process com.google.process.gapps (pid 6948) (adj 0) has died.
,W/ActivityManager( 2405): Process android.process.acore has crashed too many times: killing!
,I/ActivityManager( 2405): Process android.process.acore (pid 6944) (adj -12) has died.
,F/ActivityManager( 2405): Service ServiceRecord{430c6d40 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{42f28320 6944:android.process.acore/u0a20} not same as in map: null
,W/ActivityManager( 2405): Process com.google.process.gapps has crashed too many times: killing!
,I/ActivityManager( 2405): Killing 6974:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2405): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null


motorola-XT1039: 
--------- beginning of /dev/log/main,
--------- beginning of /dev/log/system
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3465
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3481 uid=10318 gids={50318, 3003, 3001, 3002}
,I/ActivityManager( 1015): Displayed com.example.hello/.MainActivity: +328ms (total +352ms)
,W/jxcore-log( 3481): Initializing JXcore engine
,W/jxcore-log( 3481): JXcore engine is ready
,W/jxcore-log( 3481): Starting JXcore engine
,W/jxcore-log( 3481): Platform android
W/jxcore-log( 3481): 
,W/jxcore-log( 3481): Process ARCH arm
W/jxcore-log( 3481): 
,I/jxcore-log( 3481): JXcore Cordova bridge is ready!
I/jxcore-log( 3481): 
,W/jxcore-log( 3481): JXcore engine is started
,E/jxcore-log( 3481): >> motorola-XT1039
E/jxcore-log( 3481): 
,I/jxcore-log( 3481): Total memory 893136896
I/jxcore-log( 3481): 
I/jxcore-log( 3481): Free memory 36794368
I/jxcore-log( 3481): 
I/jxcore-log( 3481): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3481): 
,I/jxcore-log( 3481): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3481): 
,I/jxcore-log( 3481): userPath [ 'www' ]
I/jxcore-log( 3481): 
,I/jxcore-log( 3481): Size 720 1184
I/jxcore-log( 3481): 
,I/jxcore-log( 3481): Screen Brightness 10
I/jxcore-log( 3481): 
,E/jxcore-log( 3481): Dummy Error Log.
E/jxcore-log( 3481): 
,I/jxcore-log( 3481): getBuffer is called!!!!
I/jxcore-log( 3481): 
,I/jxcore-log( 3481): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 3481): 
I/jxcore-log( 3481): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3481): 
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 3481:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{420fa410 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1015):   Force finishing activity ActivityRecord{420fa410 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{420fa410 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3581 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1015): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3601 uid=10058 gids={50058}
,I/ActivityManager( 1015): Killing 3322:com.android.calendar/u0a7 (adj 15): empty #9
,I/ActivityManager( 1015): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3618 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1015): Killing 3308:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1015): Killing 3360:com.google.android.partnersetup/u0a25 (adj 15): empty #10
,I/ActivityManager( 1015): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3633 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1015): Killing 3067:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 1040): Killing 4817:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
I/ActivityManager( 1040): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{3df604db #8 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{3df604db #8 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1040): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6337 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1040): Display changed displayId=0
,I/ActivityManager( 1040): Displayed com.example.hello/.MainActivity: +605ms (total +734ms)
W/jxcore-log( 6337): Initializing JXcore engine
W/jxcore-log( 6337): JXcore engine is ready
W/jxcore-log( 6337): Starting JXcore engine
W/jxcore-log( 6337): Platform android
W/jxcore-log( 6337): 
W/jxcore-log( 6337): Process ARCH arm
W/jxcore-log( 6337): 
I/jxcore-log( 6337): JXcore Cordova bridge is ready!
I/jxcore-log( 6337): 
W/jxcore-log( 6337): JXcore engine is started
,E/jxcore-log( 6337): >> LGE-LG-D855
E/jxcore-log( 6337): 
I/jxcore-log( 6337): Total memory 2995761152
I/jxcore-log( 6337): 
I/jxcore-log( 6337): Free memory 575102976
I/jxcore-log( 6337): 
I/jxcore-log( 6337): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6337): 
I/jxcore-log( 6337): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6337): 
,I/jxcore-log( 6337): userPath [ 'www' ]
I/jxcore-log( 6337): 
I/jxcore-log( 6337): Size 1440 2392
I/jxcore-log( 6337): 
,I/jxcore-log( 6337): Screen Brightness 50
I/jxcore-log( 6337): 
E/jxcore-log( 6337): Dummy Error Log.
E/jxcore-log( 6337): 
,I/jxcore-log( 6337): getBuffer is called!!!!
I/jxcore-log( 6337): 
,I/ActivityManager( 1040): Waited long enough for: ServiceRecord{2bc8181d u0 com.google.android.music/.wear.WearMetadataSyncService}
,I/ActivityManager( 1040): Killing 5950:com.lge.clock/u0a10 (adj 15): empty #17
,I/ActivityManager( 1040): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6397 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6337): ****TEST TOOK:  5252  ms ****
I/jxcore-log( 6337): 
I/jxcore-log( 6337): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6337): 
,I/ActivityManager( 1040): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6441 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 5771:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1040): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1040): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1040): Killing 6337:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1040):   Force finishing activity ActivityRecord{339cfb78 u0 com.example.hello/.MainActivity t8}
,W/ActivityManager( 1040): Spurious death for ProcessRecord{2ae95b4c 6337:com.example.hello/u0a318}, curProc for 6337: null
I/ActivityManager( 1040): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1040):   Force finishing activity ActivityRecord{339cfb78 u0 com.example.hello/.MainActivity t8 f}
W/ActivityManager( 1040): Duplicate finish request for ActivityRecord{339cfb78 u0 com.example.hello/.MainActivity t8 f}
,I/ActivityManager( 1040): Killing 6184:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager( 1040): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6500 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,W/ActivityManager( 1040): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,I/ActivityManager( 1040): Killing 6203:com.android.contacts/u0a19 (adj 15): empty #17
,I/ActivityManager( 1040): Process com.android.bluetooth (pid 3697) has died
,W/ActivityManager( 1040): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,I/ActivityManager( 1040): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6535 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6552 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6231:com.android.gallery3d/u0a27 (adj 15): empty #17


```

####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on SH47FWM00508 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.example.hello code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device ZX1G429CRK error: device not found
 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of system
--------- beginning of main
,I/ActivityManager(  761): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  761): mDVFSHelper.acquire()
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  761): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6293 uid=10403 gids={50403, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager(  761): Display changed displayId=0
D/ActivityManager(  761): post active user change for 0
I/ActivityManager(  761): Displayed com.example.hello/.MainActivity: +564ms
W/jxcore-log( 6293): Initializing JXcore engine
W/jxcore-log( 6293): JXcore engine is ready
W/jxcore-log( 6293): Starting JXcore engine
W/ActivityManager(  761): mDVFSHelper.release()
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  761): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6349 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 6293): Platform android
W/jxcore-log( 6293): 
W/jxcore-log( 6293): Process ARCH arm
W/jxcore-log( 6293): 
I/ActivityManager(  761): Killing 5343:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
I/jxcore-log( 6293): JXcore Cordova bridge is ready!
I/jxcore-log( 6293): 
W/jxcore-log( 6293): JXcore engine is started
E/jxcore-log( 6293): >> samsung-SM-N9005
E/jxcore-log( 6293): 
I/jxcore-log( 6293): Total memory 2971471872
I/jxcore-log( 6293): 
I/jxcore-log( 6293): Free memory 397332480
I/jxcore-log( 6293): 
I/jxcore-log( 6293): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6293): 
I/jxcore-log( 6293): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6293): 
I/jxcore-log( 6293): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6293): 
I/jxcore-log( 6293): Size 1080 1920
I/jxcore-log( 6293): 
I/jxcore-log( 6293): Screen Brightness 162
I/jxcore-log( 6293): 
E/jxcore-log( 6293): Dummy Error Log.
E/jxcore-log( 6293): 
,I/jxcore-log( 6293): getBuffer is called!!!!
I/jxcore-log( 6293): 
,I/jxcore-log( 6293): ****TEST TOOK:  5073  ms ****
I/jxcore-log( 6293): 
,I/jxcore-log( 6293): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6293): 
,I/ActivityManager(  761): Force stopping com.example.hello appid=10403 user=-1: uninstall pkg
,I/ActivityManager(  761): Killing 6293:com.example.hello/u0a403 (adj 0): stop com.example.hello
,W/ActivityManager(  761): Force removing ActivityRecord{1b84d268 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  761): mDVFSHelper.acquire()
,W/ActivityManager(  761): Spurious death for ProcessRecord{1915165e 6293:com.example.hello/u0a403}, curProc for 6293: null
,I/ActivityManager(  761): Force stopping com.example.hello appid=10403 user=0: pkg removed
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  761): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6412 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager(  761): handle home activity for 0
,D/ActivityManager(  761): post active user change for 0
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  761): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6438 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 5400:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,W/ActivityManager(  761): mDVFSHelper.release()
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  761): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6456 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 5494:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  761): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6472 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 5072:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,I/ActivityManager(  761): Killing 4447:com.android.providers.calendar/u0a51 (adj 13): bgCount ##41
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  761): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  761): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6495 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a


HTC-HTC One_M8: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager(  892): Killing 5117:com.google.android.partnersetup/u0a28 (adj 15): empty #17
I/ActivityManager(  892): Recipient 5117
I/ActivityManager(  892): Killing 5162:com.htc.backup/u0a118 (adj 15): empty #17
I/ActivityManager(  892): Recipient 5162
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  892): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5640 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Displayed com.example.hello/.MainActivity: +434ms
W/jxcore-log( 5640): Initializing JXcore engine
W/jxcore-log( 5640): JXcore engine is ready
W/jxcore-log( 5640): Starting JXcore engine
,W/jxcore-log( 5640): Platform android
W/jxcore-log( 5640): 
W/jxcore-log( 5640): Process ARCH arm
W/jxcore-log( 5640): 
,I/jxcore-log( 5640): JXcore Cordova bridge is ready!,
I/jxcore-log( 5640): 
W/jxcore-log( 5640): JXcore engine is started
,E/jxcore-log( 5640): >> HTC-HTC One_M8,
E/jxcore-log( 5640): 
,I/jxcore-log( 5640): Total memory 1912020992,
I/jxcore-log( 5640): 
I/jxcore-log( 5640): Free memory 141152256
I/jxcore-log( 5640): 
,I/jxcore-log( 5640): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5640): 
I/jxcore-log( 5640): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5640): 
,I/jxcore-log( 5640): userPath [ 'www' ],
I/jxcore-log( 5640): 
,I/jxcore-log( 5640): Size 1080 1776,
I/jxcore-log( 5640): 
,I/jxcore-log( 5640): Screen Brightness 142
I/jxcore-log( 5640): 
,E/jxcore-log( 5640): Dummy Error Log.
E/jxcore-log( 5640): 
,I/jxcore-log( 5640): getBuffer is called!!!!,
I/jxcore-log( 5640): 
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{1b38b5a5 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{311628eb u0 com.htc.musicenhancer/.EnhancerService},
,I/ActivityManager(  892): Killing 5183:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5183,
,I/ActivityManager(  892): Killing 5141:com.htc.cs.dm/u0a105 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5141,
,I/jxcore-log( 5640): ****TEST TOOK:  5098  ms ****,
I/jxcore-log( 5640): 
I/jxcore-log( 5640): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5640): 
,I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
,I/ActivityManager(  892): Killing 5640:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  892): Recipient 5640,
,W/ActivityManager(  892): Force removing ActivityRecord{2299e68b u0 com.example.hello/.MainActivity t27}: app died, no saved state,
,W/ActivityManager(  892): Spurious death for ProcessRecord{b90bd55 5640:com.example.hello/u0a380}, curProc for 5640: null,
I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  892): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5736 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5326:com.google.android.apps.docs/u0a107 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5326,
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5766 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5824 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,E/ActivityManager(  892): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4300, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
,W/ActivityManager(  892): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  892): android.os.TransactionTooLargeException
W/ActivityManager(  892): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  892): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  892): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2009)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1547)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1060)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:958)
W/ActivityManager(  892): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6859)
W/ActivityManager(  892): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
W/ActivityManager(  892): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/ActivityManager(  892): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  892): Recipient 5766
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=5841 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/ActivityManager(  892): Spurious death for ProcessRecord{316a421c 5841:com.google.android.apps.docs/u0a107}, curProc for 5766: null
,I/ActivityManager(  892): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5861 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5880 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5897 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a
E/ActivityManager(  892): App crashed! Process: com.android.documentsui,
,I/ActivityManager(  892): Killing 5262:com.google.android.gms:car/u0a25 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5262,
,W/ActivityManager(  892): Can't addPackageDependency on system process
,I/ActivityManager(  892): Killing 4771:com.google.android.music:main/u0a167 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 4771
,I/ActivityManager(  892): Killing 5490:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5490,
,I/ActivityManager(  892): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0,
,I/ActivityManager(  892): Recipient 5841
,I/ActivityManager(  892): Process com.google.android.apps.docs (pid 5841) has died,
W/ActivityManager(  892): Force removing ActivityRecord{360e2052 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t28}: app died, no saved state
,I/ActivityManager(  892): Killing 5399:com.google.android.gm/u0a115 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5399
,E/ActivityManager(  892): App crashed! Process: com.htc.launcher,
,W/ActivityManager(  892):   Force finishing activity com.htc.launcher/.Launcher
,I/ActivityManager(  892): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0,
,I/ActivityManager(  892): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=5937 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a


motorola-Nexus 6: 
--------- beginning of main
--------- beginning of system
W/ActivityManager(  820): Can't addPackageDependency on system process
I/ActivityManager(  820): Config changes=1df8 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h731dp 560dpi nrml long port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
I/ActivityManager(  820): Config changes=508 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h658dp 560dpi nrml port ?uimode ?night finger -keyb/v/h -nav/h s.3}
,I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
,I/ActivityManager(  820): Config changes=200 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h658dp 560dpi nrml port finger -keyb/v/h -nav/h s.4}
,I/ActivityManager(  820): System now ready
,I/ActivityManager(  820): Start proc WebViewLoader-armeabi-v7a [android.webkit.WebViewFactory$RelroFileCreator] for : pid=1089 uid=1037 gids={} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.systemui for service com.android.systemui/.SystemUIService: pid=1106 uid=10024 gids={50024, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc android.process.media for broadcast com.android.providers.media/.MtpReceiver: pid=1129 uid=10008 gids={50008, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 1024} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.googlequicksearchbox:interactor for service com.google.android.googlequicksearchbox/com.google.android.voiceinteraction.GsaVoiceInteractionService: pid=1239 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.inputmethod.latin for service com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME: pid=1256 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.phone for service com.android.mms.service/.MmsService: pid=1283 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.server.telecom for added application com.android.server.telecom: pid=1301 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.nfc for added application com.android.nfc: pid=1313 uid=1027 gids={41027, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.phone for added application com.android.phone: pid=1355 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,I/ActivityManager(  820): Start proc com.google.android.googlequicksearchbox for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: pid=1385 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/ActivityManager(  820): No pending application record for pid 1283 (IApplicationThread android.app.ApplicationThreadProxy@29400df); dropping process
,I/ActivityManager(  820): Start proc com.android.printspooler for service com.android.printspooler/.model.PrintSpoolerService: pid=1424 uid=10081 gids={50081, 9997} abi=armeabi-v7a
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Start proc android.process.acore for content provider com.android.providers.contacts/.CallLogProvider: pid=1445 uid=10005 gids={50005, 9997} abi=armeabi-v7a
,V/ActivityManager(  820): Display changed displayId=0
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Start proc com.google.android.gms.persistent for broadcast com.google.android.gms/com.google.android.location.internal.NlpNetworkProviderSettingsUpdateReceiver: pid=1474 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService: pid=1540 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.process.gapps for service com.google.android.gms/.config.ConfigService: pid=1564 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=1643 uid=10016 gids={50016, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  820): Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +1s750ms
,I/ActivityManager(  820): Start proc com.google.android.gms for service com.google.android.gms/.usagereporting.service.UsageReportingService: pid=1758 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=1798 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.audio.MediaButtonIntentReceiver: pid=1852 uid=10067 gids={50067, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider: pid=1958 uid=10051 gids={50051, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=1976 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=2001 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2040 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Start proc com.google.android.dialer for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver: pid=2050 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.motorola.motocit for broadcast com.motorola.motocit/.CQATestBootReceiver: pid=2106 uid=10002 gids={50002, 9997, 3002, 3001, 1028, 1015, 1023, 3003} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=2129 uid=10003 gids={50003, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2152 uid=10015 gids={50015, 9997} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2178 uid=10017 gids={50017, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2199 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc org.simalliance.openmobileapi.service:remote for service org.simalliance.openmobileapi.service/.SmartcardService: pid=2216 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=2233 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2261 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2338 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2460 uid=10044 gids={50044, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  820): Killing 1852:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  820): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2504 uid=10019 gids={50019, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  820): Killing 1424:com.android.printspooler/u0a81 (adj 15): empty #17
,I/ActivityManager(  820): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=2547 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2567 uid=10078 gids={50078, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  820): Killing 2040:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2050:com.google.android.dialer/u0a13 (adj 15): empty #17
,I/ActivityManager(  820): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2602 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  820): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/ActivityManager(  820): Start proc com.google.android.apps.messaging for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver: pid=2635 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Killing 2106:com.motorola.motocit/u0a2 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2152:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
,I/ActivityManager(  820): Start proc com.android.sdm.plugins.sprintdm for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver: pid=2671 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2692 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/ActivityManager(  820): Killing 2178:com.android.managedprovisioning/u0a17 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2199:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/ActivityManager(  820): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2714 uid=10066 gids={50066, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Killing 2129:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2261:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/ActivityManager(  820): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2762 uid=10003 gids={50003, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  820): Resuming delayed broadcast
,I/ActivityManager(  820): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2813 uid=10074 gids={50074, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  820): Killing 1976:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{3908f885 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{1d48aa2c u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  820): Killing 2338:com.google.android.youtube/u0a86 (adj 15): empty #17,
,I/ActivityManager(  820): Killing 2460:com.google.android.deskclock/u0a44 (adj 15): empty #17
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Killing 2547:com.google.android.gms:car/u0a11 (adj 15): empty #17
,TIME-OUT KILL (timeout was 150000ms),I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  820): Force stopping com.example.hello appid=10272 user=0: pkg removed
I/ActivityManager(  820): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2912 uid=10018 gids={50018, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  820): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2932 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  820): Killing 2602:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/ActivityManager(  820): Killing 1958:com.google.android.apps.fitness/u0a51 (adj 15): empty #17


```

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 7970f88c error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device FA55PYS00566 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 022678fb504e29b0 error: device not found
 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1016): mDVFSHelper.acquire()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5342 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1016): Display changed displayId=0
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/ActivityManager( 1016): Displayed Component not be shown by security: +577ms (total +656ms)
,W/ActivityManager( 1016): mDVFSHelper.release()
,W/jxcore-log( 5342): Initializing JXcore engine
W/jxcore-log( 5342): JXcore engine is ready
,W/jxcore-log( 5342): Starting JXcore engine
,W/jxcore-log( 5342): Platform android
W/jxcore-log( 5342): 
W/jxcore-log( 5342): Process ARCH arm
W/jxcore-log( 5342): 
,I/jxcore-log( 5342): JXcore Cordova bridge is ready!,
I/jxcore-log( 5342): 
W/jxcore-log( 5342): JXcore engine is started
,E/jxcore-log( 5342): >> samsung-SM-A300FU
E/jxcore-log( 5342): 
,I/jxcore-log( 5342): Total memory 1451114496
I/jxcore-log( 5342): 
,I/jxcore-log( 5342): Free memory 22671360
I/jxcore-log( 5342): 
I/jxcore-log( 5342): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5342): 
I/jxcore-log( 5342): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5342): 
,I/jxcore-log( 5342): userPath [ 'www' ]
I/jxcore-log( 5342): 
,I/jxcore-log( 5342): Size 540 960
I/jxcore-log( 5342): 
,I/jxcore-log( 5342): Screen Brightness 160
I/jxcore-log( 5342): 
,E/jxcore-log( 5342): Dummy Error Log.
E/jxcore-log( 5342): 
,I/jxcore-log( 5342): getBuffer is called!!!!
I/jxcore-log( 5342): 
,I/jxcore-log( 5342): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 5342): 
,I/jxcore-log( 5342): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5342): 
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg,
I/ActivityManager( 1016): Killing 5342:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{3fce5c4d u0 com.example.hello/.MainActivity t19}
,W/ActivityManager( 1016): Spurious death for ProcessRecord{39b013dc 5342:com.example.hello/u0a345}, curProc for 5342: null
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=0: pkg removed
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{3fce5c4d u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1016): Duplicate finish request for ActivityRecord{3fce5c4d u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5409 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/ActivityManager( 1016): Killing 4860:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5429 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5446 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4876:com.wssyncmldm/1000 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5463 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5476 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5494 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,


HTC-HTC One M8s: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager(  969): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=5063 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  969): Killing 4534:com.google.android.configupdater/u0a98 (adj 15): empty #17
I/ActivityManager(  969): Recipient 4534
I/ActivityManager(  969): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5032 on display 0
I/ActivityManager(  969): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5103 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  969): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  969): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  969): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  969): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  969): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=5145 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/ActivityManager(  969): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  969): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  969): Unbind failed: could not find connection for android.os.BinderProxy@3bc65a86
I/ActivityManager(  969): Killing 3454:com.htc.cs.dm/u0a99 (adj 15): empty #17
I/ActivityManager(  969): Recipient 3454
I/ActivityManager(  969): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5196 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
I/ActivityManager(  969): Displayed com.example.hello/.MainActivity: +924ms
I/ActivityManager(  969): Killing 4576:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  969): Recipient 4576
I/ActivityManager(  969): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5245 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  969): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=5269 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  969): Killing 4671:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
W/jxcore-log( 5103): Initializing JXcore engine
W/jxcore-log( 5103): JXcore engine is ready
W/jxcore-log( 5103): Starting JXcore engine
I/ActivityManager(  969): Recipient 4671
I/ActivityManager(  969): Killing 4603:com.htc.htccupd/u0a13 (adj 15): empty #18
I/ActivityManager(  969): Recipient 4603
W/jxcore-log( 5103): Platform android
W/jxcore-log( 5103): 
W/jxcore-log( 5103): Process ARCH arm
W/jxcore-log( 5103): 
I/jxcore-log( 5103): JXcore Cordova bridge is ready!
I/jxcore-log( 5103): 
W/jxcore-log( 5103): JXcore engine is started
E/jxcore-log( 5103): >> HTC-HTC One M8s
E/jxcore-log( 5103): 
I/jxcore-log( 5103): Total memory 1931808768
I/jxcore-log( 5103): 
I/jxcore-log( 5103): Free memory 83910656
I/jxcore-log( 5103): 
I/jxcore-log( 5103): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5103): 
I/jxcore-log( 5103): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5103): 
I/jxcore-log( 5103): userPath [ 'www' ]
I/jxcore-log( 5103): 
I/jxcore-log( 5103): Size 1080 1776
I/jxcore-log( 5103): 
I/jxcore-log( 5103): Screen Brightness 142
I/jxcore-log( 5103): 
E/jxcore-log( 5103): Dummy Error Log.
E/jxcore-log( 5103): 
I/ActivityManager(  969): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5324 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/ActivityManager(  969): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5360 uid=10035 gids={50035, 9997} abi=arm64-v8a
,I/ActivityManager(  969): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5389 uid=10076 gids={50076, 9997} abi=arm64-v8a
,I/jxcore-log( 5103): getBuffer is called!!!!
I/jxcore-log( 5103): 
,I/ActivityManager(  969): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5421 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  969): Killing 4694:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4694,
,I/ActivityManager(  969): Killing 3688:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 3688,
,I/ActivityManager(  969): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5464 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/ActivityManager(  969): Killing 4718:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4718
,I/ActivityManager(  969): Killing 4742:com.android.smith/1000 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4742,
,I/ActivityManager(  969): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5505 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  969): Killing 4800:com.google.android.gms:car/u0a24 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4800,
,I/ActivityManager(  969): Waited long enough for: ServiceRecord{ee07718 u0 com.htc.HTCSpeaker/.NGFService},
,I/ActivityManager(  969): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5540 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  969): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5564 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/ActivityManager(  969): Killing 4763:com.android.vending/u0a72 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4763
,I/ActivityManager(  969): Killing 4940:com.htc.mobiledata/u0a46 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4940,
,I/ActivityManager(  969): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=5607 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  969): Killing 4978:com.google.android.youtube/u0a176 (adj 15): empty #17,
,I/ActivityManager(  969): Recipient 4978
,I/ActivityManager(  969): Killing 5063:com.google.android.gm/u0a106 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 5063
,I/ActivityManager(  969): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5655 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,I/jxcore-log( 5103): ****TEST TOOK:  5373  ms ****,
I/jxcore-log( 5103): 
I/jxcore-log( 5103): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5103): 
,I/ActivityManager(  969): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5685 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  969): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5716 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  969): Killing 5269:com.htc.club/u0a181 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 5269
,I/ActivityManager(  969): Killing 5196:com.htc.sense.news/u0a74 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 5196
,I/ActivityManager(  969): Force stopping com.example.hello appid=10373 user=0: pkg removed,
I/ActivityManager(  969): Killing 5103:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  969): Recipient 5103,
,W/ActivityManager(  969): Force removing ActivityRecord{28acd123 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  969): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5757 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,W/ActivityManager(  969): Spurious death for ProcessRecord{2513192 5103:com.example.hello/u0a373}, curProc for 5103: null,
,I/ActivityManager(  969): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,I/ActivityManager(  969): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5783 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  969): Killing 5360:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 5360,
,I/ActivityManager(  969): Cannot resolve ContentProvider=com.htc.vowifi
,I/ActivityManager(  969): Cannot resolve ContentProvider=com.htc.vowifi
,I/ActivityManager(  969): Recipient 3432
,I/ActivityManager(  969): Process com.android.bluetooth (pid 3432) has died
,W/ActivityManager(  969): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  969): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,I/ActivityManager(  969): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5826 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  969): Killing 5389:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 5389,
,I/ActivityManager(  969): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5858 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager(  969): Killing 4324:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4324
,E/ActivityManager(  969): App crashed! Process: com.android.vending
,I/ActivityManager(  969): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5885 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  969): Killing 4895:com.google.android.talk/u0a112 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 4895
,I/ActivityManager(  969): Killing 5421:com.htc.task/u0a69 (adj 15): empty #17
,I/ActivityManager(  969): Recipient 5421
,I/ActivityManager(  969): Killing 5464:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
,I/ActivityManager(  969): Recipient 5464
,I/ActivityManager(  969): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5920 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  953): Delaying start of: ServiceRecord{4361de10 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ActivityManager(  953): Killing 3345:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{432c20d8 stackId=1, 1 tasks}
D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3970
I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{432c20d8 stackId=1, 2 tasks}
V/ActivityManager(  953): Moving to PAUSING: ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  953): resumeTopActivityLocked: Pausing null
V/ActivityManager(  953): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  953): startService SlideAside
D/ActivityManager(  953): setFocusedStack: mFocusedStack=ActivityStack{432c20d8 stackId=1, 2 tasks}
D/ActivityManager(  953): allPausedActivitiesComplete: r=ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  953): Moving to PAUSED: ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{432c20d8 stackId=1, 2 tasks}
D/ActivityManager(  953): resumeTopActivityLocked: Restarting ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  953): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4006 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  953): Moving to RESUMED: ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/ActivityManager(  953): Displayed com.example.hello/.MainActivity: +315ms
I/ActivityManager( 4006): Timeline: Activity_idle id: android.os.BinderProxy@4287b168 time:47440
W/jxcore-log( 4006): Initializing JXcore engine
W/jxcore-log( 4006): JXcore engine is ready
W/jxcore-log( 4006): Starting JXcore engine
I/ActivityManager(  953): Timeline: Activity_windows_visible id: ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3} time:47879
D/ActivityManager(  953): no-history finish of ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  953): Finishing activity token=Token{43290548 ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  953): Moving to FINISHING: ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  953): Moving to STOPPING: ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  953): Moving to STOPPED: ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 4006): Platform android
W/jxcore-log( 4006): 
W/jxcore-log( 4006): Process ARCH arm
W/jxcore-log( 4006): 
,I/jxcore-log( 4006): JXcore Cordova bridge is ready!
I/jxcore-log( 4006): 
,W/jxcore-log( 4006): JXcore engine is started
,E/jxcore-log( 4006): >> LGE-LG-D802
E/jxcore-log( 4006): 
,I/jxcore-log( 4006): Total memory 1943035904
I/jxcore-log( 4006): 
,I/jxcore-log( 4006): Free memory 464539648
I/jxcore-log( 4006): 
I/jxcore-log( 4006): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4006): 
I/jxcore-log( 4006): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4006): 
I/jxcore-log( 4006): userPath [ 'www' ]
I/jxcore-log( 4006): 
I/jxcore-log( 4006): Size 1080 1776
I/jxcore-log( 4006): 
I/jxcore-log( 4006): Screen Brightness 255
I/jxcore-log( 4006): 
,E/jxcore-log( 4006): Dummy Error Log.
E/jxcore-log( 4006): 
,I/jxcore-log( 4006): getBuffer is called!!!!
I/jxcore-log( 4006): 
,I/ActivityManager(  953): Killing 3410:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{432c20d8 stackId=1, 2 tasks}
,D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 4006): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 4006): 
,I/jxcore-log( 4006): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4006): 
,I/ActivityManager(  953): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  953): Killing 4006:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  953): Force removing ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  953): Moving to DESTROYED: ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  953): Moving to DESTROYED: ActivityRecord{42c66920 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{432c20d8 stackId=1, 1 tasks}
,D/ActivityManager(  953): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  953): moveHomeStack:
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
,V/ActivityManager(  953): Moving to RESUMED: ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  953): resumeTopActivityLocked: Resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  953): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
,D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  953): Waited long enough for: ServiceRecord{43255ff8 u0 com.android.mms/.transaction.SmsReceiverService}
,V/ActivityManager(  953): Moving to DESTROYING: ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  953): Moving to DESTROYED: ActivityRecord{432903e0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  953): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
,D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  953): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4102 uid=10090 gids={50090}
,I/ActivityManager(  953): Killing 3296:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  953): Service ServiceRecord{4333ba10 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432325d0 3296:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  953): Service ServiceRecord{43188440 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432325d0 3296:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  953): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4132 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  953): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4157 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  953): Killing 2081:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
,D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  953): Delaying start of: ServiceRecord{432e9fc0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  953): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4176 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  953): Killing 3805:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  953): Killing 3219:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
,D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  953): Timeline: Activity_windows_visible id: ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1} time:54607
,I/ActivityManager(  953): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4191 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  953): Killing 3869:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  953): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c05210 stackId=0, 1 tasks}
,D/ActivityManager(  953): resumeTopActivityLocked: Top activity resumed ActivityRecord{4306bfe8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  953): Delaying start of: ServiceRecord{432867c8 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager( 1486): Timeline: Activity_idle id: android.os.BinderProxy@42874f58 time:54692


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.example.hello code:0 
child process exited with code 0 on device f56ad48d 
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device c5afcdcb error: device not found
 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of system
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6313 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=6331 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6356 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6379 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  848): Killing 4661:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  848): Killing 5121:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
I/ActivityManager(  848): Killing 5554:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
I/ActivityManager(  848): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  848): mDVFSHelper.acquire()
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  848): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6436 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=6457 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityManager(  848): post active user change for 0
,I/ActivityManager(  848): Killing 5508:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=6505 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Displayed com.example.hello/.MainActivity: +707ms
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  848): mDVFSHelper.release()
,W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  848): Killing 5632:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  848): Killing 5650:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6548 uid=10168 gids={50168, 9997} abi=armeabi-v7a
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6554 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 6436): Initializing JXcore engine
,W/jxcore-log( 6436): JXcore engine is ready
,W/jxcore-log( 6436): Starting JXcore engine
,I/ActivityManager(  848): Killing 5668:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,W/jxcore-log( 6436): Platform android
W/jxcore-log( 6436): 
W/jxcore-log( 6436): Process ARCH arm
W/jxcore-log( 6436): 
,I/jxcore-log( 6436): JXcore Cordova bridge is ready!
I/jxcore-log( 6436): 
,W/jxcore-log( 6436): JXcore engine is started
,E/jxcore-log( 6436): >> samsung-SM-G900F
E/jxcore-log( 6436): 
,I/jxcore-log( 6436): Total memory 1787449344
I/jxcore-log( 6436): 
,I/jxcore-log( 6436): Free memory 46043136
I/jxcore-log( 6436): 
I/jxcore-log( 6436): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6436): 
I/jxcore-log( 6436): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6436): 
,I/jxcore-log( 6436): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6436): 
,I/jxcore-log( 6436): Size 1080 1920
I/jxcore-log( 6436): 
,I/jxcore-log( 6436): Screen Brightness 134
I/jxcore-log( 6436): 
,E/jxcore-log( 6436): Dummy Error Log.
E/jxcore-log( 6436): 
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=6614 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6436): getBuffer is called!!!!
I/jxcore-log( 6436): 
,I/ActivityManager(  848): Killing 4969:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=6631 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5298:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=6650 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5016:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/ActivityManager(  848): Process com.samsung.indexservice (pid 6631)(adj 9) has died(55,592)
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6672 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6688 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5315:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/ActivityManager(  848): Killing 5705:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/ActivityManager(  848): Killing 5728:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=6712 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5767:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/ActivityManager(  848): Killing 5830:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/jxcore-log( 6436): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 6436): 
,I/jxcore-log( 6436): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6436): 
,I/ActivityManager(  848): Killing 5808:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/ActivityManager(  848): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  848): Killing 6436:com.example.hello/u0a374 (adj 0): stop com.example.hello
,W/ActivityManager(  848): Force removing ActivityRecord{1375ba8 u0 com.example.hello/.MainActivity t11}: app died, no saved state
,W/ActivityManager(  848): mDVFSHelper.acquire()
,I/ActivityManager(  848): Force stopping com.example.hello appid=10374 user=0: pkg removed
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6804 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager(  848): handle home activity for 0
D/ActivityManager(  848): post active user change for 0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=6822 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,W/ActivityManager(  848): mDVFSHelper.release()
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6850 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5864:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/ActivityManager(  848): Killing 5870:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/ActivityManager(  848): Waited long enough for: ServiceRecord{4618b4e u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6866 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5894:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5911:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=6898 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 5979:com.samsung.helphub/1000 (adj 15): bgCount ##41
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  848): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  848): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6917 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a


samsung-SM-A500FU: 
--------- beginning of main
--------- beginning of system
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3945 uid=10116 gids={50116, 9997} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 3068:com.fmm.dm/1000 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=3965 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3091:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3983 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1017): mDVFSHelper.acquire()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4016 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4032 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3122:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4049 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4082 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3155:com.fmm.ds/1000 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 3175:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 2982:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4120 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Displayed Component not be shown by security: +946ms
W/ActivityManager( 1017): mDVFSHelper.release()
,I/ActivityManager( 1017): Killing 3244:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4152 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,W/jxcore-log( 4016): Initializing JXcore engine
W/jxcore-log( 4016): JXcore engine is ready
,W/jxcore-log( 4016): Starting JXcore engine
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/jxcore-log( 4016): Platform android
W/jxcore-log( 4016): 
W/jxcore-log( 4016): Process ARCH arm
W/jxcore-log( 4016): 
,I/jxcore-log( 4016): JXcore Cordova bridge is ready!
I/jxcore-log( 4016): 
,W/jxcore-log( 4016): JXcore engine is started
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4178 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/jxcore-log( 4016): >> samsung-SM-A500FU
E/jxcore-log( 4016): 
,I/jxcore-log( 4016): Total memory 1983787008
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): Free memory 36687872
I/jxcore-log( 4016): 
I/jxcore-log( 4016): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4016): 
I/jxcore-log( 4016): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): Size 720 1280
I/jxcore-log( 4016): 
,I/jxcore-log( 4016): Screen Brightness 255
I/jxcore-log( 4016): 
,E/jxcore-log( 4016): Dummy Error Log.
E/jxcore-log( 4016): 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1017): Killing 3263:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4199 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3046:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/ActivityManager( 1017): Killing 3286:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #32
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/ActivityManager( 1017): Process com.android.email (pid 4152)(adj 9) has died(51,1097)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4215 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4231 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1017): Killing 3360:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3340:com.wssnps/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 4016): getBuffer is called!!!!
I/jxcore-log( 4016): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): getTasks: caller 10146 does not hold GET_TASKS; limiting output
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Process com.android.exchange (pid 4199)(adj 11) has died(51,1087),
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a


```

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device 4325e43f error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device HT574YC04723 error: device not found
 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1015): mDVFSHelper.acquire()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5038 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5050 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3921:com.android.providers.calendar/u0a37 (adj 15): empty #31
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/ActivityManager( 1015): Displayed Component not be shown by security: +751ms
W/ActivityManager( 1015): mDVFSHelper.release()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/ActivityManager( 1015): Display changed displayId=0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/jxcore-log( 5050): Initializing JXcore engine
W/jxcore-log( 5050): JXcore engine is ready
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/jxcore-log( 5050): Starting JXcore engine
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/jxcore-log( 5050): Platform android,
W/jxcore-log( 5050): 
W/jxcore-log( 5050): Process ARCH arm
W/jxcore-log( 5050): 
,I/jxcore-log( 5050): JXcore Cordova bridge is ready!,
I/jxcore-log( 5050): 
W/jxcore-log( 5050): JXcore engine is started
,E/jxcore-log( 5050): >> samsung-SM-A300FU
E/jxcore-log( 5050): 
,I/jxcore-log( 5050): Total memory 1451114496
I/jxcore-log( 5050): 
,I/jxcore-log( 5050): Free memory 20029440
I/jxcore-log( 5050): 
I/jxcore-log( 5050): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5050): 
I/jxcore-log( 5050): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5050): 
,I/jxcore-log( 5050): userPath [ 'www' ]
I/jxcore-log( 5050): 
,I/jxcore-log( 5050): Size 540 960
I/jxcore-log( 5050): 
,I/jxcore-log( 5050): Screen Brightness 255
I/jxcore-log( 5050): 
,E/jxcore-log( 5050): Dummy Error Log.
E/jxcore-log( 5050): 
,I/jxcore-log( 5050): getBuffer is called!!!!
I/jxcore-log( 5050): 
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{225907c4 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5050): ****TEST TOOK:  5098  ms ****
I/jxcore-log( 5050): 
,I/jxcore-log( 5050): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5050): 
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 5050:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{3f91be20 u0 com.example.hello/.MainActivity t10}
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10333 user=0: pkg removed
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{3f91be20 u0 com.example.hello/.MainActivity t10 f}
,W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{3f91be20 u0 com.example.hello/.MainActivity t10 f}
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5135 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5146 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5167 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5202 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5218 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4480:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5233 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 4219:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5256 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4167:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/ActivityManager( 1015): Killing 3638:com.google.android.talk/u0a102 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4570:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/ActivityManager( 1015): Killing 4585:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4749:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5285 uid=10086 gids={50086, 9997} abi=armeabi-v7a,
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5301 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4774:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4812:com.policydm/1000 (adj 15): empty #31


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2195
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2206 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
,I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +234ms
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4258c910 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2251 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2266 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 1532:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1532
,W/jxcore-log( 2206): Initializing JXcore engine
,W/jxcore-log( 2206): JXcore engine is ready
,W/jxcore-log( 2206): Starting JXcore engine
,I/ActivityManager(  908): Killing 1823:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1823
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2280 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2292 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,I/ActivityManager(  908): Killing 1889:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  908): Recipient 1889
,I/ActivityManager(  908): Delay finish: com.android.providers.calendar/.CalendarReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2313 uid=10016 gids={50016, 3003, 5012, 2001}
,W/jxcore-log( 2206): Platform android
W/jxcore-log( 2206): 
,W/jxcore-log( 2206): Process ARCH arm
W/jxcore-log( 2206): 
,I/ActivityManager(  908): Killing 1261:com.android.printspooler/u0a161 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1261
,I/jxcore-log( 2206): JXcore Cordova bridge is ready!
I/jxcore-log( 2206): 
,W/jxcore-log( 2206): JXcore engine is started
,I/ActivityManager(  908): Killing 1968:com.htc.showme/u0a82 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1968
,E/jxcore-log( 2206): >> HTC-HTC Desire 820
E/jxcore-log( 2206): 
,I/jxcore-log( 2206): Total memory 1964650496
I/jxcore-log( 2206): 
,I/jxcore-log( 2206): Free memory 835764224
I/jxcore-log( 2206): 
I/jxcore-log( 2206): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2206): 
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2341 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/jxcore-log( 2206): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2206): 
,I/jxcore-log( 2206): userPath [ 'www' ]
I/jxcore-log( 2206): 
I/jxcore-log( 2206): Size 720 1184
I/jxcore-log( 2206): 
I/jxcore-log( 2206): Screen Brightness 10
I/jxcore-log( 2206): 
E/jxcore-log( 2206): Dummy Error Log.
E/jxcore-log( 2206): 
,I/ActivityManager(  908): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2358 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 1986:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,I/ActivityManager(  908): Killing 1901:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1986
I/ActivityManager(  908): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/ActivityManager(  908): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
I/ActivityManager(  908): Recipient 1901
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2394 uid=10030 gids={50030}
,I/ActivityManager(  908): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2408 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  908): Killing 1847:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  908): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/jxcore-log( 2206): getBuffer is called!!!!
I/jxcore-log( 2206): 
I/ActivityManager(  908): Recipient 1847
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 2044:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2044
,I/ActivityManager(  908): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2435 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  908): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2447 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 1920:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1920
,I/ActivityManager(  908): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2459 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 2058:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2058
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2476 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
I/ActivityManager(  908): Killing 2078:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  908): Killing 2100:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2100
,I/ActivityManager(  908): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2488 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
I/ActivityManager(  908): Recipient 2078
,I/ActivityManager(  908): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2502 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  908): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2518 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/ActivityManager(  908): Killing 1631:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1631
,I/ActivityManager(  908): Killing 1935:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2533 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  908): Killing 2251:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 1935
,I/ActivityManager(  908): Killing 2266:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2266
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2546 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 2280:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Recipient 2280
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2572 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,I/ActivityManager(  908): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2584 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Killing 2313:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2313
,I/ActivityManager(  908): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2599 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,I/ActivityManager(  908): Killing 2341:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2341
,I/ActivityManager(  908): Delay finish: com.htc.lmw/.StorageBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.android.providers.media/.MediaScannerReceiver
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{425cb460 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2616 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Delay finish: com.htc.sense.mms/.PolicyReceiver
,I/ActivityManager(  908): Killing 2358:com.htc.fm/u0a24 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2358
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{42639168 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2642 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2655 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/jxcore-log( 2206): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 2206): 
,I/jxcore-log( 2206): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2206): 
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2694 uid=10077 gids={50077}
,I/ActivityManager(  908): Killing 2394:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2394
,I/ActivityManager(  908): Delay finish: com.htc.mms.backupagent/.SMSBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2408:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2408
,I/ActivityManager(  908): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2710 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2724 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  908): Killing 2435:com.htc.csrecommend/u0a33 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2435
,I/ActivityManager(  908): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2738 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
I/ActivityManager(  908): Killing 2447:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2447
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=2760 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
,I/ActivityManager(  908): Killing 2459:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2459
,I/ActivityManager(  908): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  908): Killing 2206:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  908): Force removing ActivityRecord{425fd1b0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  908): Force stopping com.example.hello appid=10355 user=0: pkg removed
,E/ActivityManager(  908): App crashed! Process: com.google.android.googlequicksearchbox:search


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
Error: problem stopping Android apk(com.example.hello) to device CC51WYC03425 error: device not found
 
Error: problem stopping Android apk(com.example.hello) to device 0c6a0f3c0bdb4e77 error: device not found
 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  909): Killing 2773:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2773
I/ActivityManager(  909): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3174 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  909): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3186 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  909): Killing 2802:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  909): Killing 2836:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2802
I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3211 uid=10041 gids={50041}
I/ActivityManager(  909): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3225 uid=10078 gids={50078}
I/ActivityManager(  909): Killing 2787:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2836
I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3237 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  909): Killing 2857:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2787
I/ActivityManager(  909): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3252 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  909): Recipient 2857
I/ActivityManager(  909): Killing 2883:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2883
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3151
I/ActivityManager(  909): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3268 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  909): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3282 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3297 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Killing 2901:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2901
I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3332 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  909): Killing 2916:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2916
I/ActivityManager(  909): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3350 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  909): Displayed com.example.hello/.MainActivity: +278ms
I/ActivityManager(  909): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3364 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  909): Killing 2975:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  909): Killing 2947:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
I/ActivityManager(  909): Recipient 2975
I/ActivityManager(  909): Recipient 2947
I/ActivityManager(  909): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 2989:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2989
I/ActivityManager(  909): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3383 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  909): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/ActivityManager(  909): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3397 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3001:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  909): Killing 3089:com.android.vending/u0a74 (adj 15): empty #17
I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  909): Recipient 3001
I/ActivityManager(  909): Resuming delayed broadcast
W/jxcore-log( 3268): Initializing JXcore engine
W/jxcore-log( 3268): JXcore engine is ready
W/jxcore-log( 3268): Starting JXcore engine
I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
I/ActivityManager(  909): Recipient 3089
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  909): Resuming delayed broadcast
W/jxcore-log( 3268): Platform android
W/jxcore-log( 3268): 
W/jxcore-log( 3268): Process ARCH arm
W/jxcore-log( 3268): 
I/ActivityManager(  909): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3424 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/jxcore-log( 3268): JXcore Cordova bridge is ready!
I/jxcore-log( 3268): 
W/jxcore-log( 3268): JXcore engine is started
E/jxcore-log( 3268): >> HTC-HTC Desire 820
E/jxcore-log( 3268): 
I/jxcore-log( 3268): Total memory 1964650496
I/jxcore-log( 3268): 
I/jxcore-log( 3268): Free memory 698871808
I/jxcore-log( 3268): 
I/jxcore-log( 3268): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3268): 
I/jxcore-log( 3268): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3268): 
I/jxcore-log( 3268): userPath [ 'www' ]
I/jxcore-log( 3268): 
I/jxcore-log( 3268): Size 720 1184
I/jxcore-log( 3268): 
I/jxcore-log( 3268): Screen Brightness 142
I/jxcore-log( 3268): 
E/jxcore-log( 3268): Dummy Error Log.
E/jxcore-log( 3268): 
I/ActivityManager(  909): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3129:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3445 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  909): Recipient 3129
I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3174:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3174
,I/ActivityManager(  909): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3462 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/jxcore-log( 3268): getBuffer is called!!!!
I/jxcore-log( 3268): 
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3480 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  909): Killing 3186:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3186
,I/ActivityManager(  909): Killing 3237:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3237
,I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3502 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  909): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3521 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  909): Killing 2930:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2930
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3332:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3332
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Delaying start of: ServiceRecord{4286ef40 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,I/ActivityManager(  909): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=3545 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{4271ab68 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  909): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=3564 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/jxcore-log( 3268): ****TEST TOOK:  5041  ms ****
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3268): 
,I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  909): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3591 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Killing 3350:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/ActivityManager(  909): Recipient 3350
,I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  909): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3626 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3211:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3225:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3225
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  909): Recipient 3211
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3660 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  909): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3383:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Recipient 3383
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  909): Killing 3268:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  909): Force removing ActivityRecord{42650830 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  909): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3688 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3701 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Killing 3397:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3397


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  775): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Killing 1479:com.google.android.dialer/u0a8 (adj 15): empty #17
,I/ActivityManager(  775): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2029
I/ActivityManager(  775): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2076 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  775): Killing 1507:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/ActivityManager(  775): Displayed com.example.hello/.MainActivity: +820ms
,I/ActivityManager(  775): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2129 uid=10058 gids={50058, 3003, 1028, 1015}
,W/jxcore-log( 2076): Initializing JXcore engine
,W/jxcore-log( 2076): JXcore engine is ready
,W/jxcore-log( 2076): Starting JXcore engine
,I/ActivityManager(  775): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,W/jxcore-log( 2076): Platform android
W/jxcore-log( 2076): 
,W/jxcore-log( 2076): Process ARCH arm
W/jxcore-log( 2076): 
,I/ActivityManager(  775): Killing 1550:com.google.android.configupdater/u0a2 (adj 15): empty #17
,I/jxcore-log( 2076): JXcore Cordova bridge is ready!
I/jxcore-log( 2076): 
,W/jxcore-log( 2076): JXcore engine is started
,E/jxcore-log( 2076): >> LGE-Nexus 5
E/jxcore-log( 2076): 
,I/jxcore-log( 2076): Total memory 1945137152
I/jxcore-log( 2076): 
I/jxcore-log( 2076): Free memory 920985600
I/jxcore-log( 2076): 
I/jxcore-log( 2076): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2076): 
,I/jxcore-log( 2076): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2076): 
,I/jxcore-log( 2076): userPath [ 'www' ]
I/jxcore-log( 2076): 
,I/jxcore-log( 2076): Size 1080 1776
I/jxcore-log( 2076): 
,I/jxcore-log( 2076): Screen Brightness 82
I/jxcore-log( 2076): 
,E/jxcore-log( 2076): Dummy Error Log.
E/jxcore-log( 2076): 
,I/jxcore-log( 2076): getBuffer is called!!!!
I/jxcore-log( 2076): 
,I/ActivityManager(  775): Killing 1589:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
,I/ActivityManager(  775): Killing 1217:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,I/ActivityManager(  775): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2182 uid=10001 gids={50001, 3003, 1028, 1015}
,I/jxcore-log( 2076): ****TEST TOOK:  5028  ms ****
I/jxcore-log( 2076): 
,I/jxcore-log( 2076): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2076): 
,I/ActivityManager(  775): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  775): Killing 2076:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  775): Force removing ActivityRecord{42f81520 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  775): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  775): Resuming delayed broadcast
I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  775): Resuming delayed broadcast
,I/ActivityManager(  775): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver,


```




###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DC14BF44-BDD8-4C67-AB8E-015BD303FB81/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DC14BF44-BDD8-4C67-AB8E-015BD303FB81/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A9F190FB-96F4-43EE-858C-C63692C9B7AA/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64610"
,(lldb)     command script import "/tmp/DC14BF44-BDD8-4C67-AB8E-015BD303FB81/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 15:38:19.656 HelloWorld[1616:1736180] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/620AD34B-4167-4352-8294-3A1EF49392DE/Library/Cookies/Cookies.binarycookies
,2015-11-06 15:38:20.041 HelloWorld[1616:1736180] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 15:38:20.042 HelloWorld[1616:1736180] Multi-tasking -> Device: YES, App: YES
,2015-11-06 15:38:20.045 HelloWorld[1616:1736180] Unlimited access to network resources
,2015-11-06 15:38:20.050 HelloWorld[1616:1736180] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 15:38:23.895 HelloWorld[1616:1736180] Resetting plugins due to page load.
,2015-11-06 15:38:24.269 HelloWorld[1616:1736180] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/A9F190FB-96F4-43EE-858C-C63692C9B7AA/HelloWorld.app/www/index.html
,2015-11-06 15:38:24.333 HelloWorld[1616:1736180] JXcore Cordova plugin initializing
2015-11-06 15:38:24.334 HelloWorld[1616:1736304] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 130969600
execPath /private/var/mobile/Containers/Bundle/Application/A9F190FB-96F4-43EE-858C-C63692C9B7AA/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/A9,F190FB-96F4-43EE-858C-C63692C9B7AA/HelloWorld.app/www/jxcore/
userPath []
2015-11-06 15:38:24.559 HelloWorld[1616:1736304] Native method ScreenInfo not found.
2015-11-06 15:38:24.559 HelloWorld[1616:1736304] Native method ScreenBrightness not found.
Du,mmy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5111  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4FB77FB0-63D1-41A9-977B-825B432FB894/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4FB77FB0-63D1-41A9-977B-825B432FB894/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/B7DA805F-7443-4CA8-BE91-0E2C23A6D83E/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64613"
,(lldb)     command script import "/tmp/4FB77FB0-63D1-41A9-977B-825B432FB894/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 15:39:06.857 HelloWorld[1315:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-06 15:39:06.862 HelloWorld[1315:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-06 15:39:06.867 HelloWorld[1315:60b] Unlimited access to network resources
,2015-11-06 15:39:06.877 HelloWorld[1315:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 15:39:17.716 HelloWorld[1315:60b] Resetting plugins due to page load.
,2015-11-06 15:39:18.554 HelloWorld[1315:60b] Finished load of: file:///var/mobile/Applications/B7DA805F-7443-4CA8-BE91-0E2C23A6D83E/HelloWorld.app/www/index.html
,2015-11-06 15:39:18.623 HelloWorld[1315:60b] JXcore Cordova plugin initializing
,2015-11-06 15:39:18.628 HelloWorld[1315:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 496181248
execPath /private/var/mobile/Applications/B7DA805F-7443-4CA8-BE91-0E2C23A6D83E/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/B7DA805F-7443-4CA8-BE91-0E2C23A6D83E/HelloWorld.app/www/jxcore/
userPath []
,2015-11-06 15:39:19.103 HelloWorld[1315:6707] Native method ScreenInfo not found.
,2015-11-06 15:39:19.105 HelloWorld[1315:6707] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5249  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5762C7D9-E3E6-4F09-964A-F33B8F2A6EE0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5762C7D9-E3E6-4F09-964A-F33B8F2A6EE0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D2AE8B92-C2FC-49CB-B39F-27166A0CA6E8/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64625"
,(lldb)     command script import "/tmp/5762C7D9-E3E6-4F09-964A-F33B8F2A6EE0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 15:38:21.623 HelloWorld[2612:2799963] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/136B0B00-42B5-429D-BA90-9B15A9F6C95C/Library/Cookies/Cookies.binarycookies
,2015-11-06 15:38:22.028 HelloWorld[2612:2799963] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 15:38:22.029 HelloWorld[2612:2799963] Multi-tasking -> Device: YES, App: YES
,2015-11-06 15:38:22.032 HelloWorld[2612:2799963] Unlimited access to network resources
,2015-11-06 15:38:22.038 HelloWorld[2612:2799963] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 15:38:25.456 HelloWorld[2612:2799963] Resetting plugins due to page load.
,2015-11-06 15:38:25.807 HelloWorld[2612:2799963] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/D2AE8B92-C2FC-49CB-B39F-27166A0CA6E8/HelloWorld.app/www/index.html
,2015-11-06 15:38:25.889 HelloWorld[2612:2799963] JXcore Cordova plugin initializing
,2015-11-06 15:38:25.890 HelloWorld[2612:2800098] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 98729984
execPath /private/var/mobile/Containers/Bundle/Application/D2AE8B92-C2FC-49CB-B39F-27166A0CA6E8/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/D2AE,8B92-C2FC-49CB-B39F-27166A0CA6E8/HelloWorld.app/www/jxcore/
userPath []
2015-11-06 15:38:26.140 HelloWorld[2612:2800098] Native method ScreenInfo not found.
2015-11-06 15:38:26.141 HelloWorld[2612:2800098] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5105  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5864215B-2EDC-4859-BBB5-B40BBC7E0A9C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5864215B-2EDC-4859-BBB5-B40BBC7E0A9C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A118283B-F954-4074-BD86-93BF7572129C/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64609"
,(lldb)     command script import "/tmp/5864215B-2EDC-4859-BBB5-B40BBC7E0A9C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 15:38:24.123 HelloWorld[1740:3646953] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6343ACA9-CAEB-4699-9D59-49F5353EEFE2/Library/Cookies/Cookies.binarycookies
,2015-11-06 15:38:24.523 HelloWorld[1740:3646953] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 15:38:24.524 HelloWorld[1740:3646953] Multi-tasking -> Device: YES, App: YES
,2015-11-06 15:38:24.528 HelloWorld[1740:3646953] Unlimited access to network resources
,2015-11-06 15:38:24.535 HelloWorld[1740:3646953] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 15:38:34.081 HelloWorld[1740:3646953] Resetting plugins due to page load.
,2015-11-06 15:38:37.388 HelloWorld[1740:3646953] Finished load of: file:///var/mobile/Containers/Bundle/Application/A118283B-F954-4074-BD86-93BF7572129C/HelloWorld.app/www/index.html
,2015-11-06 15:38:37.464 HelloWorld[1740:3646953] JXcore Cordova plugin initializing
,2015-11-06 15:38:37.465 HelloWorld[1740:3647209] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 337297408
,execPath /private/var/mobile/Containers/Bundle/Application/A118283B-F954-4074-BD86-93BF7572129C/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/A118283B-F954-4074-BD86-93BF7572129C/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-06 15:38:37.658 HelloWorld[1740:3647209] Native method ScreenInfo not found.
2015-11-06 15:38:37.658 HelloWorld[1740:3647209] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5120  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_476722347fc8662/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":22,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 22, cancel: 1 } }


```

