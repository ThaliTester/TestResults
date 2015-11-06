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
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on 30049d9501da2100 
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Android task is completed 
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
I/ActivityManager( 1197): Killing 2730:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2771:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2694:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 1626:com.android.printspooler/u0a118 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2912:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2928:com.samsung.android.app.memo/u0a130 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2943:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3021:com.sec.phone/u0a127 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3105:com.sec.android.widgetapp.samsungapps/u0a120 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3079:com.google.android.configupdater/u0a2 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3156:com.sec.dsm.system/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3188:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3211:com.sec.factory/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3226:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3258:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 1499:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3275:com.android.onetimeinitializer/u0a21 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3290:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3318:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3334:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
W/ActivityManager( 1197): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1197): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1197): Killing 3348:com.osp.app.signin/u0a30 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42adb390 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42a22280 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42c2a868 u0 com.samsung.android.providers.context/.ContextService}
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42bbf628 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{428e2068 u0 com.sec.esdk.elm/.service.ElmAgentService}
I/ActivityManager( 1197): Killing 2956:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2586:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 1644:com.android.settings/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3385:com.wssyncmldm/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 2573:com.google.android.partnersetup/u0a11 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3408:com.google.android.googlequicksearchbox:search/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3446:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3432:com.samsung.android.intelligenceservice/u0a52 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3460:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3474:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3488:com.wssnps/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Process com.samsung.android.MtpApplication (pid 4165) (adj 0) has died.
I/ActivityManager( 1197): Killing 3501:com.samsung.android.app.accesscontrol/u0a57 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3518:com.sec.android.app.FileShareServer/u0a62 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3533:com.sec.android.nearby.mediaserver/u0a63 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3546:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3560:com.sec.android.app.bluetoothtest/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3573:com.blurb.checkout/u0a67 (adj 15): bgCount ##33
W/ActivityManager( 1197): mDVFSHelper.acquire()
W/ActivityManager( 1197): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
I/ActivityManager( 1197): Killing 3586:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3599:com.dropbox.android/u0a78 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3638:com.sec.factory.camera/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3652:com.samsung.android.app.watchmanagerstub/u0a86 (adj 15): bgCount ##33
W/ActivityManager( 1197): mDVFSHelper.release()
I/ActivityManager( 1197): Killing 3731:com.samsung.scrc.idi.server/u0a91 (adj 15): bgCount ##33
I/ActivityManager( 1197): Process com.sec.factory (pid 4151) (adj 0) has died.
I/ActivityManager( 1197): Process com.sec.android.app.sysscope (pid 3953) (adj 0) has died.
I/ActivityManager( 1197): Killing 3745:com.samsung.helphub/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3758:com.LocalFota/u0a92 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3774:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3802:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3828:com.sec.android.app.camera/u0a121 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 1777:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42b3e358 u0 com.rxnetworks.rxnservicesxybrid/com.rxnetworks.rxnserviceslib.RXNetworksService}
I/ActivityManager( 1197): Killing 3919:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1197): Waited long enough for: ServiceRecord{42bbb758 u0 com.samsung.android.MtpApplication/.MtpService}
I/ActivityManager( 1197): Killing 3885:com.android.exchange/u0a126 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3841:com.android.email/u0a125 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3938:com.sec.android.app.worldclock/u0a135 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3967:com.sec.android.app.controlpanel/u0a141 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3980:com.samsung.android.service.travel/u0a143 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3993:com.google.android.youtube/u0a146 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4057:com.gameloft.android.gdc:remote/u0a152 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4270:com.sec.spp.push:RemoteDlcProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4288:com.sec.spp.push:RemoteNotiProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4329:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 3696:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4457:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
I/ActivityManager( 1197): Killing 4508:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
,--------- beginning of /dev/log/main
W/ActivityManager( 1197): mDVFSHelper.acquire()
,W/ActivityManager( 1197): mDVFSHelper.release()
W/jxcore-log( 4892): Initializing JXcore engine
W/jxcore-log( 4892): JXcore engine is ready
W/jxcore-log( 4892): Starting JXcore engine
W/jxcore-log( 4892): Platform android
W/jxcore-log( 4892): 
W/jxcore-log( 4892): Process ARCH arm
W/jxcore-log( 4892): 
I/jxcore-log( 4892): JXcore Cordova bridge is ready!
I/jxcore-log( 4892): 
W/jxcore-log( 4892): JXcore engine is started
E/jxcore-log( 4892): >> samsung-SM-T232
E/jxcore-log( 4892): 
I/jxcore-log( 4892): Total memory 1352024064
I/jxcore-log( 4892): 
I/jxcore-log( 4892): Free memory 210137088
I/jxcore-log( 4892): 
I/jxcore-log( 4892): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4892): 
I/jxcore-log( 4892): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4892): 
I/jxcore-log( 4892): userPath [ 'www' ]
I/jxcore-log( 4892): 
I/jxcore-log( 4892): Size 800 1280
I/jxcore-log( 4892): 
I/jxcore-log( 4892): Screen Brightness 143
I/jxcore-log( 4892): 
E/jxcore-log( 4892): Dummy Error Log.
E/jxcore-log( 4892): 
I/jxcore-log( 4892): getBuffer is called!!!!
I/jxcore-log( 4892): 
,I/jxcore-log( 4892): ****TEST TOOK:  5401  ms ****
I/jxcore-log( 4892): 
,I/jxcore-log( 4892): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4892): 
,I/ActivityManager( 1197): Killing 4892:com.example.hello/u0a357 (adj 0): stop com.example.hello


samsung-SM-G920F: 
--------- beginning of system
W/ActivityManager( 3463): mDVFSHelper.release()
--------- beginning of main
,I/ActivityManager( 3463): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3463): mDVFSHelper.acquire()
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3463): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9679 uid=10425 gids={50425, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 3463): Activity pause timeout for ActivityRecord{cf83535 u0 com.example.hello/.MainActivity t44}
,D/ActivityManager( 3463): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/ActivityManager( 3463): Displayed Component not be shown by security: +737ms
,W/ActivityManager( 3463): mDVFSHelper.release()
,W/jxcore-log( 9679): Initializing JXcore engine
W/jxcore-log( 9679): JXcore engine is ready
,W/jxcore-log( 9679): Starting JXcore engine
,W/jxcore-log( 9679): Platform android
W/jxcore-log( 9679): 
W/jxcore-log( 9679): Process ARCH arm
W/jxcore-log( 9679): 
,I/jxcore-log( 9679): JXcore Cordova bridge is ready!
I/jxcore-log( 9679): 
W/jxcore-log( 9679): JXcore engine is started
,E/jxcore-log( 9679): >> samsung-SM-G920F
E/jxcore-log( 9679): 
,I/jxcore-log( 9679): Total memory 2829074432
I/jxcore-log( 9679): 
I/jxcore-log( 9679): Free memory 49643520
I/jxcore-log( 9679): 
I/jxcore-log( 9679): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9679): 
I/jxcore-log( 9679): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9679): 
,I/jxcore-log( 9679): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9679): 
,I/jxcore-log( 9679): Size 1440 2560
I/jxcore-log( 9679): 
,I/jxcore-log( 9679): Screen Brightness 134
I/jxcore-log( 9679): 
E/jxcore-log( 9679): Dummy Error Log.
E/jxcore-log( 9679): 
,I/jxcore-log( 9679): getBuffer is called!!!!
I/jxcore-log( 9679): 
,I/jxcore-log( 9679): ****TEST TOOK:  5076  ms ****
I/jxcore-log( 9679): 
,I/jxcore-log( 9679): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9679): 
,I/ActivityManager( 3463): Force stopping com.example.hello appid=10425 user=-1: uninstall pkg
,I/ActivityManager( 3463): Killing 9679:com.example.hello/u0a425 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3463):   Force finishing activity ActivityRecord{cf83535 u0 com.example.hello/.MainActivity t44}
,I/ActivityManager( 3463): Force stopping com.example.hello appid=10425 user=0: pkg removed
,W/ActivityManager( 3463): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9788 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 3463): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5237, uid=10127 that is not exported from uid 10125
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,I/ActivityManager( 3463): Killing 9205:com.sec.pcw.device/1000 (adj 15): empty #25
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9808 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=9823 uid=10054 gids={50054, 9997, 3003, 3002} abi=arm64-v8a
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=9838 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9856 uid=10102 gids={50102, 9997, 1028, 3003, 1015} abi=arm64-v8a
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
,W/ActivityManager( 3463): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=9872 uid=10001 gids={50001, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=arm64-v8a
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9888 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,I/ActivityManager( 3463): Killing 8750:com.samsung.android.app.galaxyfinder/u0a27 (adj 15): empty #25
,D/ActivityManager( 3463): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
,W/ActivityManager( 3463): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/ActivityManager( 3463): Killing 9235:com.policydm/1000 (adj 15): empty #25
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.sec.android.app.vepreload for broadcast com.sec.android.app.vepreload/.VEExtensionPackUpdateReceiver: pid=9905 uid=10170 gids={50170, 9997, 1028, 1015, 1003, 3003} abi=arm64-v8a
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3463): Killing 8765:com.google.android.apps.plus/u0a136 (adj 15): empty #25
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3463): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3463): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9921 uid=10027 gids={50027, 9997, 1028, 1015, 3003, 3002} abi=arm64-v8a
I/ActivityManager( 3463): Killing 9274:com.sec.spp.push/u0a33 (adj 15): empty #25
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3463): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.vodafone.smhs, destAppInfo.processName = com.vodafone.smhs
,I/ActivityManager( 3463): Killing 8729:com.sec.android.app.shealth/u0a28 (adj 15): empty #25
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.SnippetsWidgetService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.DashboardsWidgetService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3463): Killing 9314:com.sec.spp.push:RemoteNotiProcess/u0a33 (adj 15): empty #25
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3463): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3463): userId = 0, bbcId = -10000
W/ActivityManager( 3463): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3463): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3463): do not start freezing screen for locked container getKeyguardshowstate = false


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1309): Start proc 8936:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver
I/ActivityManager( 1309): Killing 8473:com.lge.ia.task.smartsetting/u0a21 (adj 15): empty #22
I/ActivityManager( 1309): Start proc 8960:com.google.android.talk/u0a121 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1309): Start proc 9000:com.google.android.partnersetup/u0a5 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager( 1309): Start proc 9039:com.lge.appbox.client/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper
I/ActivityManager( 1309): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1309): setTaskToReturnTo : TaskRecord{2fd349e4 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1309): setTaskToReturnTo : TaskRecord{2fd349e4 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1309): Killing 8311:com.lge.wifisettings/1000 (adj 15): empty #22
I/ActivityManager( 1309): Start proc 9064:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1309): Start proc 9088:com.android.contacts/u0a18 for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver
I/ActivityManager( 1309): Start proc 9126:com.lge.exchange/u0a22 for broadcast com.lge.exchange/.receiver.PackageChangeReceiver
I/ActivityManager( 1309): Killing 8429:com.lge.NfcSettings/1000 (adj 15): empty #22
I/ActivityManager( 1309): Start proc 9155:com.lge.email/u0a56 for content provider com.lge.email/.providers.EmailProvider
I/ActivityManager( 1309): Killing 8289:com.android.settings/1000 (adj 15): empty #22
I/ActivityManager( 1309): Displayed com.example.hello/.MainActivity: +761ms (total +30s771ms)
W/ActivityManager( 1309): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1309): Start proc 9188:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.PackageIntentReceiver
W/ActivityManager( 1309): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1309): Killing 8661:com.lge.eodengine/1000 (adj 15): empty #22
W/jxcore-log( 9064): Initializing JXcore engine
W/jxcore-log( 9064): JXcore engine is ready
W/jxcore-log( 9064): Starting JXcore engine
I/ActivityManager( 1309): Start proc 9212:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver
I/ActivityManager( 1309): Killing 8069:com.uei.lg.quicksetsdk.irblaster/1000 (adj 15): empty #22
W/jxcore-log( 9064): Platform android
W/jxcore-log( 9064): 
W/jxcore-log( 9064): Process ARCH arm
W/jxcore-log( 9064): 
W/ActivityManager( 1309): Scheduling restart of crashed service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service in 1000ms
I/ActivityManager( 1309): Killing 8640:com.lge.sync/1000 (adj 15): empty #22
I/jxcore-log( 9064): JXcore Cordova bridge is ready!
I/jxcore-log( 9064): 
W/jxcore-log( 9064): JXcore engine is started
E/jxcore-log( 9064): >> LGE-LG-H815
E/jxcore-log( 9064): 
I/jxcore-log( 9064): Total memory 2968948736
I/jxcore-log( 9064): 
I/jxcore-log( 9064): Free memory 77828096
I/jxcore-log( 9064): 
I/jxcore-log( 9064): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9064): 
I/jxcore-log( 9064): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9064): 
I/jxcore-log( 9064): userPath [ 'www' ]
I/jxcore-log( 9064): 
I/jxcore-log( 9064): Size 1440 2392
I/jxcore-log( 9064): 
I/jxcore-log( 9064): Screen Brightness 255
I/jxcore-log( 9064): 
E/jxcore-log( 9064): Dummy Error Log.
E/jxcore-log( 9064): 
I/ActivityManager( 1309): Start proc 9233:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
I/ActivityManager( 1309): Killing 8049:com.lge.qremote/u0a138 (adj 15): empty #22
,I/ActivityManager( 1309): Start proc 9253:com.android.vending/u0a62 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
I/ActivityManager( 1309): Killing 8734:com.lge.cic.eden.service/u0a7 (adj 15): empty #22
I/jxcore-log( 9064): getBuffer is called!!!!
I/jxcore-log( 9064): 
I/ActivityManager( 1309): Start proc 9296:com.google.android.apps.docs/u0a118 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager( 1309): Killing 8757:com.lge.clock/u0a16 (adj 15): empty #22
W/ActivityManager( 1309): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1309): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1309): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1309): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1309): Start proc 9332:com.google.android.apps.plus/u0a122 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager( 1309): Killing 8705:com.google.android.music:main/u0a123 (adj 15): empty #22
,W/ActivityManager( 1309): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
,I/ActivityManager( 1309): Start proc 9365:com.google.android.googlequicksearchbox:search/u0a63 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,I/ActivityManager( 1309): Killing 8521:com.lge.task/u0a20 (adj 15): empty #22
,I/ActivityManager( 1309): Killing 8832:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #22
,I/ActivityManager( 1309): Start proc 9402:com.lge.lifetracker/u0a137 for broadcast com.lge.lifetracker/.widgets.HealthWidgetProvider
,I/ActivityManager( 1309): Start proc 9425:com.lge.lgaccount/u0a107 for content provider com.lge.lgaccount/.provider.LGAccountProvider
,I/ActivityManager( 1309): Start proc 9447:com.lge.bioitplatform.sdservice.service/u0a4 for content provider com.lge.bioitplatform.sdservice.service/com.lge.bioitplatform.sdservice.provider.BioDataProvider
,I/ActivityManager( 1309): Killing 8854:com.lge.myplace/u0a30 (adj 15): empty #22
,I/ActivityManager( 1309): Killing 8216:com.android.defcontainer/u0a3 (adj 15): empty #22
,I/ActivityManager( 1309): Start proc 9486:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
,I/ActivityManager( 1309): Start proc 9506:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
,I/ActivityManager( 1309): Killing 8882:com.google.android.gm/u0a113 (adj 15): empty #22
,I/ActivityManager( 1309): Start proc 9529:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,W/ActivityManager( 1309): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1309): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1309): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1309): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1309): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1309): Start proc 9570:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/ActivityManager( 1309): Killing 8936:com.google.android.setupwizard/u0a54 (adj 15): empty #22
,I/ActivityManager( 1309): Killing 8809:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1309): Killing 9000:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,W/ActivityManager( 1309): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1309): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9064): ****TEST TOOK:  5074  ms ****
I/jxcore-log( 9064): 
,I/jxcore-log( 9064): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9064): 
,I/ActivityManager( 1309): Killing 8685:com.lge.bnr/1000 (adj 15): empty #22
,I/ActivityManager( 1309): Force stopping com.example.hello appid=10360 user=0: pkg removed
I/ActivityManager( 1309): Killing 9064:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1309): Force removing ActivityRecord{7d21e4d u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1309): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
,W/ActivityManager( 1309): Spurious death for ProcessRecord{1d948877 9064:com.example.hello/u0a360}, curProc for 9064: null
,I/ActivityManager( 1309): Start proc 9647:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1309): Start proc 9667:com.lge.bnr/1000 for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver
,I/ActivityManager( 1309): Displayed com.lge.launcher2/.Launcher: +227ms (total +36s321ms)
,I/ActivityManager( 1309): Start proc 9691:com.android.settings/1000 for broadcast com.android.settings/.hotkey.PackageIntentReceiver
,I/ActivityManager( 1309): Killing 9155:com.lge.email/u0a56 (adj 15): empty #22
,I/ActivityManager( 1309): Start proc 9713:com.google.android.gms:car/u0a6 for service com.google.android.gms/.car.CarService


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2994): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2994): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2994): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
I/ActivityManager( 2994): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2994): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager( 2994): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2994): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2994): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/ActivityManager( 2994): filter receiver for action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager( 2994): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/ActivityManager( 2994): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2994): Displayed com.example.hello/.MainActivity: +1s407ms
,W/jxcore-log( 6328): Initializing JXcore engine
W/jxcore-log( 6328): JXcore engine is ready
,W/jxcore-log( 6328): Starting JXcore engine
,W/jxcore-log( 6328): Platform android
W/jxcore-log( 6328): 
W/jxcore-log( 6328): Process ARCH arm
W/jxcore-log( 6328): 
,I/jxcore-log( 6328): JXcore Cordova bridge is ready!
I/jxcore-log( 6328): 
W/jxcore-log( 6328): JXcore engine is started
,E/jxcore-log( 6328): >> HUAWEI-ALE-L21
E/jxcore-log( 6328): 
,I/jxcore-log( 6328): Total memory 1949741056
I/jxcore-log( 6328): 
,I/jxcore-log( 6328): Free memory 18059264
I/jxcore-log( 6328): 
,I/jxcore-log( 6328): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6328): 
I/jxcore-log( 6328): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6328): 
,I/jxcore-log( 6328): userPath [ 'www' ]
I/jxcore-log( 6328): 
,I/jxcore-log( 6328): Size 720 1184
I/jxcore-log( 6328): 
,I/jxcore-log( 6328): Screen Brightness 242
I/jxcore-log( 6328): 
,E/jxcore-log( 6328): Dummy Error Log.
E/jxcore-log( 6328): 
,I/ActivityManager( 2994): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2994): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/jxcore-log( 6328): getBuffer is called!!!!
I/jxcore-log( 6328): 
,I/ActivityManager( 2994): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
,I/jxcore-log( 6328): ****TEST TOOK:  5095  ms ****
I/jxcore-log( 6328): 
,I/jxcore-log( 6328): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6328): 
,I/ActivityManager( 2994): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2994): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/ActivityManager( 2994): filter receiver for action = android.intent.action.PACKAGE_CHANGED


```

####Node name: thali02
Console output:
```
STOP log received from  FA533YJ03104 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on FA533YJ03104 
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed 
```

Logcat output:
```
LGE-LG-D722: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  849): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{10a84753 #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{10a84753 #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  849): Killing 4914:com.google.android.talk/u0a61 (adj 15): empty #11
I/ActivityManager(  849): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5180 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  849): Displayed com.example.hello/.MainActivity: +1s160ms
,W/jxcore-log( 5180): Initializing JXcore engine
W/jxcore-log( 5180): JXcore engine is ready
,W/jxcore-log( 5180): Starting JXcore engine
,W/jxcore-log( 5180): Platform android
W/jxcore-log( 5180): 
,W/jxcore-log( 5180): Process ARCH arm
W/jxcore-log( 5180): 
I/jxcore-log( 5180): JXcore Cordova bridge is ready!
I/jxcore-log( 5180): 
W/jxcore-log( 5180): JXcore engine is started
,E/jxcore-log( 5180): >> LGE-LG-D722
E/jxcore-log( 5180): 
,I/jxcore-log( 5180): Total memory 906309632
I/jxcore-log( 5180): 
I/jxcore-log( 5180): Free memory 31338496
I/jxcore-log( 5180): 
I/jxcore-log( 5180): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5180): 
I/jxcore-log( 5180): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5180): 
I/jxcore-log( 5180): userPath [ 'www' ]
I/jxcore-log( 5180): 
I/jxcore-log( 5180): Size 720 1196
I/jxcore-log( 5180): 
,I/jxcore-log( 5180): Screen Brightness 255
I/jxcore-log( 5180): 
E/jxcore-log( 5180): Dummy Error Log.
E/jxcore-log( 5180): 
I/ActivityManager(  849): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5280 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 3530:com.android.calendar/u0a13 (adj 15): empty #11
I/jxcore-log( 5180): getBuffer is called!!!!
I/jxcore-log( 5180): 
,I/ActivityManager(  849): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5302 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 4996:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/jxcore-log( 5180): ****TEST TOOK:  5077  ms ****
I/jxcore-log( 5180): 
I/jxcore-log( 5180): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5180): 
,I/ActivityManager(  849): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
,I/ActivityManager(  849): Killing 5180:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  849): Force removing ActivityRecord{1a93d890 u0 com.example.hello/.MainActivity t217}: app died, no saved state
,W/ActivityManager(  849): Spurious death for ProcessRecord{1abb277 5180:com.example.hello/u0a30}, curProc for 5180: null
,I/ActivityManager(  849): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  849): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5394 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 5021:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5429 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 5040:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=5455 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 5080:com.google.android.apps.plus/u0a86 (adj 15): empty #11


LGE-Nexus 5: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager(  754): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  754): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2862 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,V/ActivityManager(  754): Display changed displayId=0
,I/ActivityManager(  754): Displayed com.example.hello/.MainActivity: +615ms (total +39s239ms)
,W/jxcore-log( 2862): Initializing JXcore engine
W/jxcore-log( 2862): JXcore engine is ready
,W/jxcore-log( 2862): Starting JXcore engine
,I/ActivityManager(  754): Killing 2209:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/jxcore-log( 2862): Platform android
W/jxcore-log( 2862): 
,W/jxcore-log( 2862): Process ARCH arm
W/jxcore-log( 2862): 
,I/jxcore-log( 2862): JXcore Cordova bridge is ready!
I/jxcore-log( 2862): 
,W/jxcore-log( 2862): JXcore engine is started
,E/jxcore-log( 2862): >> LGE-Nexus 5
E/jxcore-log( 2862): 
I/jxcore-log( 2862): Total memory 1946181632
I/jxcore-log( 2862): 
I/jxcore-log( 2862): Free memory 323444736
I/jxcore-log( 2862): 
I/jxcore-log( 2862): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2862): 
I/jxcore-log( 2862): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2862): 
,I/jxcore-log( 2862): userPath [ 'www' ]
I/jxcore-log( 2862): 
,I/jxcore-log( 2862): Size 1080 1776
I/jxcore-log( 2862): 
,I/jxcore-log( 2862): Screen Brightness 82
I/jxcore-log( 2862): 
E/jxcore-log( 2862): Dummy Error Log.
E/jxcore-log( 2862): 
,I/jxcore-log( 2862): getBuffer is called!!!!
I/jxcore-log( 2862): 
,I/ActivityManager(  754): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=2949 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  754): Killing 2296:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/jxcore-log( 2862): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 2862): 
I/jxcore-log( 2862): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2862): 
,I/ActivityManager(  754): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  754): Killing 2862:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/ActivityManager(  754):   Force finishing activity ActivityRecord{37efbfa2 u0 com.example.hello/.MainActivity t214}
,V/ActivityManager(  754): Display changed displayId=0
,I/ActivityManager(  754): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/ActivityManager(  754):   Force finishing activity ActivityRecord{37efbfa2 u0 com.example.hello/.MainActivity t214 f}
W/ActivityManager(  754): Duplicate finish request for ActivityRecord{37efbfa2 u0 com.example.hello/.MainActivity t214 f}
,W/ActivityManager(  754): Spurious death for ProcessRecord{32ff3b58 2862:com.example.hello/u0a277}, curProc for 2862: null
,I/ActivityManager(  754): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3057 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  754): Killing 2354:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/ActivityManager(  754): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3096 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,--------- beginning of crash
,I/ActivityManager(  754): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3126 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  754): Killing 1828:com.google.android.apps.fitness/u0a45 (adj 15): empty #17


HTC-HTC One M9: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1059): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4583 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager( 1059): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4624 uid=10139 gids={50139, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager( 1059): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4653 uid=10061 gids={50061, 9997} abi=arm64-v8a
I/ActivityManager( 1059): Killing 3969:com.google.android.configupdater/u0a87 (adj 15): empty #17
I/ActivityManager( 1059): Recipient 3969
,I/ActivityManager( 1059): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4677 uid=10003 gids={50003, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
I/ActivityManager( 1059): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4723 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
I/ActivityManager( 1059): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4674 on display 0
I/ActivityManager( 1059): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4745 uid=10193 gids={50193, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1059): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4768 uid=10036 gids={50036, 9997, 3003, 1028, 3002, 3001} abi=arm64-v8a
I/ActivityManager( 1059): Killing 4006:com.google.android.gm/u0a95 (adj 15): empty #17
I/ActivityManager( 1059): Recipient 4006
,I/ActivityManager( 1059): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4790 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
,I/ActivityManager( 1059): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4818 uid=10024 gids={50024, 9997, 1028, 1015, 3003, 1023, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1059): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4869 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 1059): Killing 4055:com.htc.backup/u0a98 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4055
,I/ActivityManager( 1059): Displayed com.example.hello/.MainActivity: +699ms
,W/jxcore-log( 4745): Initializing JXcore engine
W/jxcore-log( 4745): JXcore engine is ready
,W/jxcore-log( 4745): Starting JXcore engine
,I/ActivityManager( 1059): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4907 uid=10012 gids={50012, 9997, 3003, 1028, 1015, 1023} abi=arm64-v8a
,I/ActivityManager( 1059): Killing 3377:com.htc.cs.dm/u0a88 (adj 15): empty #17
,W/jxcore-log( 4745): Platform android
W/jxcore-log( 4745): 
W/jxcore-log( 4745): Process ARCH arm
W/jxcore-log( 4745): 
,I/jxcore-log( 4745): JXcore Cordova bridge is ready!,
I/jxcore-log( 4745): 
W/jxcore-log( 4745): JXcore engine is started
,I/ActivityManager( 1059): Recipient 3377
,E/jxcore-log( 4745): >> HTC-HTC One M9,
E/jxcore-log( 4745): 
,I/jxcore-log( 4745): Total memory 2860257280,
I/jxcore-log( 4745): ,
,I/jxcore-log( 4745): Free memory 196489216
I/jxcore-log( 4745): ,
I/jxcore-log( 4745): execPath /data/data/com.example.hello/files/www/jxcore
,I/jxcore-log( 4745): 
I/jxcore-log( 4745): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4745): 
I/ActivityManager( 1059): Killing 3801:com.htc.sense.mms/u0a54 (adj 15): empty #17
I/jxcore-log( 4745): userPath [ 'www' ]
I/jxcore-log( 4745): 
,I/jxcore-log( 4745): Size 1080 1776
I/jxcore-log( 4745): 
,I/jxcore-log( 4745): Screen Brightness 142,
I/jxcore-log( 4745): 
E/jxcore-log( 4745): Dummy Error Log.
E/jxcore-log( 4745): 
,I/ActivityManager( 1059): Recipient 3801,
,I/ActivityManager( 1059): Start proc com.htc.music:musicenhancer for broadcast com.htc.music/com.htc.musicenhancer.provider.MScannerReceiver: pid=4931 uid=10025 gids={50025, 9997, 1028, 1015, 3003, 3002, 1023} abi=armeabi-v7a,
,I/ActivityManager( 1059): Killing 4085:com.google.android.talk/u0a102 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4085
,I/ActivityManager( 1059): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4955 uid=10064 gids={50064, 9997, 5001, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 1059): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4983 uid=10068 gids={50068, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
I/ActivityManager( 1059): Killing 4160:com.htc.cs.pns:boot_complete/u0a119 (adj 15): empty #17
I/jxcore-log( 4745): getBuffer is called!!!!
I/jxcore-log( 4745): 
I/ActivityManager( 1059): Recipient 4160
I/ActivityManager( 1059): Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5007 uid=10008 gids={50008, 9997, 1028, 1015, 5001, 5011, 3003} abi=arm64-v8a
I/ActivityManager( 1059): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/ActivityManager( 1059): Resuming delayed broadcast
I/ActivityManager( 1059): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5033 uid=10095 gids={50095, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/ActivityManager( 1059): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1059): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager( 1059): Killing 4185:com.htc.cs.pns/u0a119 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4185
,W/ActivityManager( 1059): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1059): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1059): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1059): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1059): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/ActivityManager( 1059): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Start proc com.htc.autobot for broadcast com.htc.autobot/.AlarmReceiver: pid=5082 uid=10027 gids={50027, 9997, 3003, 3002, 3001, 1024, 5003} abi=arm64-v8a
,I/ActivityManager( 1059): Killing 4198:tv.peel.app/u0a123 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 4198
,I/ActivityManager( 1059): Delay finish: com.htc.autobot/.AlarmReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.google.android.gm/.GmailReceiver
I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Delay finish: com.google.android.gm/.GmailReceiver,
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver,
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5130 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager( 1059): Killing 4330:com.android.smith/1000 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 4330,
,I/ActivityManager( 1059): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5160 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/ActivityManager( 1059): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Killing 4351:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4351
,I/ActivityManager( 1059): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver,
,I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1059): Resuming delayed broadcast,
,I/ActivityManager( 1059): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver,
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5196 uid=10023 gids={50023, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager( 1059): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver,
I/ActivityManager( 1059): Resuming delayed broadcast
I/ActivityManager( 1059): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
I/ActivityManager( 1059): Resuming delayed broadcast
I/ActivityManager( 1059): Killing 4378:com.htc.usage/1000 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 4378,
,I/ActivityManager( 1059): Killing 4400:com.htc.WifiRouter/u0a134 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 4400
,I/ActivityManager( 1059): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver,
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher,
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5225 uid=10088 gids={50088, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager( 1059): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5247 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1059): Killing 4457:com.htc.themepicker/u0a59 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4457
,I/ActivityManager( 1059): Killing 4583:com.android.vending/u0a57 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 4583
,I/ActivityManager( 1059): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=5302 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 1059): Killing 4653:com.htc.mms.backupagent/u0a61 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4653
,I/ActivityManager( 1059): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5331 uid=10126 gids={50126, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/jxcore-log( 4745): ****TEST TOOK:  5043  ms ****,
I/jxcore-log( 4745): 
I/jxcore-log( 4745): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4745): 
,I/ActivityManager( 1059): Killing 4284:com.android.settings/1000 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 4284
,I/ActivityManager( 1059): Killing 4723:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4723,
,I/ActivityManager( 1059): Force stopping com.example.hello appid=10193 user=-1: uninstall pkg
I/ActivityManager( 1059): Killing 4745:com.example.hello/u0a193 (adj 0): stop com.example.hello
,I/ActivityManager( 1059): Recipient 4745,
,W/ActivityManager( 1059): Force removing ActivityRecord{379d3e1a u0 com.example.hello/.MainActivity t67}: app died, no saved state,
,I/ActivityManager( 1059): Force stopping com.example.hello appid=10193 user=0: pkg removed
,W/ActivityManager( 1059): Spurious death for ProcessRecord{227c0459 4745:com.example.hello/u0a193}, curProc for 4745: null
,I/ActivityManager( 1059): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver,
,I/ActivityManager( 1059): Resuming delayed broadcast
,I/ActivityManager( 1059): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5398 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager( 1059): Killing 4768:com.htc.widget.hmsproc2/u0a36 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4768,
,I/ActivityManager( 1059): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5452 uid=10039 gids={50039, 9997, 3003, 1028} abi=arm64-v8a
,I/ActivityManager( 1059): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5474 uid=10062 gids={50062, 9997, 3003} abi=arm64-v8a
,I/ActivityManager( 1059): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5499 uid=10039 gids={50039, 9997, 3003, 1028} abi=arm64-v8a,
,I/ActivityManager( 1059): Killing 4790:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 4790
,I/ActivityManager( 1059): Waited long enough for: ServiceRecord{143a7f0b u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,E/ActivityManager( 1059): App crashed! Process: com.google.process.gapps
,I/ActivityManager( 1059): Killing 4983:com.htc.updater/u0a68 (adj 15): empty #17
,I/ActivityManager( 1059): Recipient 4983
,I/ActivityManager( 1059): Killing 5007:com.htc.bgp/u0a8 (adj 15): empty #17,
,I/ActivityManager( 1059): Recipient 5007


```

####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/system,
--------- beginning of /dev/log/main
W/ActivityManager( 2421): mDVFSHelper.acquire()
,W/ActivityManager( 2421): mDVFSHelper.release()
,W/jxcore-log( 6625): Initializing JXcore engine
W/jxcore-log( 6625): JXcore engine is ready
W/jxcore-log( 6625): Starting JXcore engine
W/jxcore-log( 6625): Platform android
W/jxcore-log( 6625): 
W/jxcore-log( 6625): Process ARCH arm
W/jxcore-log( 6625): 
I/jxcore-log( 6625): JXcore Cordova bridge is ready!
I/jxcore-log( 6625): 
W/jxcore-log( 6625): JXcore engine is started
,E/jxcore-log( 6625): >> samsung-SM-G800F
E/jxcore-log( 6625): 
,I/jxcore-log( 6625): Total memory 1319530496
I/jxcore-log( 6625): 
I/jxcore-log( 6625): Free memory 37072896
I/jxcore-log( 6625): 
I/jxcore-log( 6625): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6625): 
,I/jxcore-log( 6625): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6625): 
,I/jxcore-log( 6625): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6625): 
,I/jxcore-log( 6625): Size 720 1280
I/jxcore-log( 6625): 
,I/jxcore-log( 6625): Screen Brightness 134
I/jxcore-log( 6625): 
,E/jxcore-log( 6625): Dummy Error Log.
E/jxcore-log( 6625): 
,I/jxcore-log( 6625): getBuffer is called!!!!
I/jxcore-log( 6625): 
,I/jxcore-log( 6625): ****TEST TOOK:  5097  ms ****,
I/jxcore-log( 6625): 
,I/jxcore-log( 6625): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6625): 
,I/ActivityManager( 2421): Killing 6625:com.example.hello/u0a388 (adj 0): stop com.example.hello
,I/ActivityManager( 2421): Killing 5704:com.sec.phone/1001 (adj 15): empty #43
,I/ActivityManager( 2421): Killing 5574:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/ActivityManager( 2421): Process android.process.acore (pid 2955) (adj -12) has died.
,I/ActivityManager( 2421): Process com.google.android.googlequicksearchbox:search (pid 5905) (adj 5) has died.
,I/ActivityManager( 2421): Process com.samsung.android.magazine.service (pid 6297) (adj 5) has died.
,W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/ActivityManager( 2421): Process android.process.acore (pid 6760) (adj -12) has died.
,F/ActivityManager( 2421): Service ServiceRecord{42fe45e8 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{42ffe538 6760:android.process.acore/u0a20} not same as in map: null
,I/ActivityManager( 2421): Process com.android.keychain (pid 6777) (adj 5) has died.
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 2851) (adj 1) has died.
,I/ActivityManager( 2421): Process com.google.android.gms (pid 3564) (adj 0) has died.
,W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/ActivityManager( 2421): Process android.process.acore (pid 6794) (adj -12) has died.
,I/ActivityManager( 2421): Killing 5287:com.google.android.talk/u0a109 (adj 15): empty #43,
,I/ActivityManager( 2421): Process com.android.documentsui (pid 6823) (adj 9) has died.,
,W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!,
,I/ActivityManager( 2421): Process android.process.acore (pid 6839) (adj -12) has died.
,W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/ActivityManager( 2421): Process android.process.acore (pid 6896) (adj -12) has died.
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 6912) (adj 0) has died.
,W/ActivityManager( 2421): Service crashed 2 times, stopping: ServiceRecord{42fc6888 u0 com.google.android.gms/.gcm.GcmService}
,W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
,I/ActivityManager( 2421): Killing 6949:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
,W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/ActivityManager( 2421): Process android.process.acore (pid 6935) (adj -12) has died.
,I/ActivityManager( 2421): Process com.google.process.gapps (pid 6969) (adj 0) has died.
,W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/ActivityManager( 2421): Process android.process.acore (pid 6975) (adj -12) has died.
,W/ActivityManager( 2421): Process com.google.process.gapps has crashed too many times: killing!
,I/ActivityManager( 2421): Killing 6999:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2421): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,W/ActivityManager( 2421): Process android.process.acore has crashed too many times: killing!
,I/ActivityManager( 2421): Process android.process.acore (pid 7015) (adj -12) has died.


motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3407
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3423 uid=10319 gids={50319, 3003, 3001, 3002}
,I/ActivityManager( 1018): Displayed com.example.hello/.MainActivity: +354ms (total +382ms)
,W/jxcore-log( 3423): Initializing JXcore engine
,W/jxcore-log( 3423): JXcore engine is ready
,W/jxcore-log( 3423): Starting JXcore engine
,W/jxcore-log( 3423): Platform android
W/jxcore-log( 3423): 
,W/jxcore-log( 3423): Process ARCH arm
W/jxcore-log( 3423): 
,I/jxcore-log( 3423): JXcore Cordova bridge is ready!
I/jxcore-log( 3423): 
,W/jxcore-log( 3423): JXcore engine is started
,E/jxcore-log( 3423): >> motorola-XT1039
E/jxcore-log( 3423): 
,I/jxcore-log( 3423): Total memory 893136896
I/jxcore-log( 3423): 
,I/jxcore-log( 3423): Free memory 38436864
I/jxcore-log( 3423): 
I/jxcore-log( 3423): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3423): 
,I/jxcore-log( 3423): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3423): 
,I/jxcore-log( 3423): userPath [ 'www' ]
I/jxcore-log( 3423): 
,I/jxcore-log( 3423): Size 720 1184
I/jxcore-log( 3423): 
,I/jxcore-log( 3423): Screen Brightness 10
I/jxcore-log( 3423): 
,E/jxcore-log( 3423): Dummy Error Log.
E/jxcore-log( 3423): 
,I/jxcore-log( 3423): getBuffer is called!!!!
I/jxcore-log( 3423): 
,I/jxcore-log( 3423): ****TEST TOOK:  5063  ms ****
I/jxcore-log( 3423): 
I/jxcore-log( 3423): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3423): 
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 3423:com.example.hello/u0a319 (adj 0): stop com.example.hello
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{432515e8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10319 user=0: pkg removed
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{432515e8 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{432515e8 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3505 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1018): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3523 uid=10058 gids={50058}
,I/ActivityManager( 1018): Killing 3258:com.android.calendar/u0a7 (adj 15): empty #9
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3543 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1018): Killing 3301:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1018): Killing 3241:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1018): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3561 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 3017:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager( 1027): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1027): setTaskToReturnTo : TaskRecord{2e2e9008 #8 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1027): setTaskToReturnTo : TaskRecord{2e2e9008 #8 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1027): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5940 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1027): Display changed displayId=0
,I/ActivityManager( 1027): Displayed com.example.hello/.MainActivity: +602ms (total +674ms)
,W/jxcore-log( 5940): Initializing JXcore engine
W/jxcore-log( 5940): JXcore engine is ready
,W/jxcore-log( 5940): Starting JXcore engine
,W/jxcore-log( 5940): Platform android
W/jxcore-log( 5940): 
,W/jxcore-log( 5940): Process ARCH arm
W/jxcore-log( 5940): 
,I/jxcore-log( 5940): JXcore Cordova bridge is ready!
I/jxcore-log( 5940): 
,W/jxcore-log( 5940): JXcore engine is started
,E/jxcore-log( 5940): >> LGE-LG-D855
E/jxcore-log( 5940): 
,I/jxcore-log( 5940): Total memory 2995761152
I/jxcore-log( 5940): 
I/jxcore-log( 5940): Free memory 599281664
I/jxcore-log( 5940): 
I/jxcore-log( 5940): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5940): 
I/jxcore-log( 5940): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5940): 
I/jxcore-log( 5940): userPath [ 'www' ]
I/jxcore-log( 5940): 
I/jxcore-log( 5940): Size 1440 2392
I/jxcore-log( 5940): 
I/jxcore-log( 5940): Screen Brightness 50
I/jxcore-log( 5940): 
E/jxcore-log( 5940): Dummy Error Log.
E/jxcore-log( 5940): 
I/jxcore-log( 5940): getBuffer is called!!!!
I/jxcore-log( 5940): 
,I/jxcore-log( 5940): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 5940): 
I/jxcore-log( 5940): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5940): 
,I/ActivityManager( 1027): Killing 4835:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1027): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1027): Killing 5940:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1027):   Force finishing activity ActivityRecord{7e5f3a1 u0 com.example.hello/.MainActivity t8}
,W/ActivityManager( 1027): Spurious death for ProcessRecord{3bb5a05f 5940:com.example.hello/u0a318}, curProc for 5940: null
I/ActivityManager( 1027): Force stopping com.example.hello appid=10318 user=0: pkg removed
,I/ActivityManager( 1027):   Force finishing activity ActivityRecord{7e5f3a1 u0 com.example.hello/.MainActivity t8 f}
W/ActivityManager( 1027): Duplicate finish request for ActivityRecord{7e5f3a1 u0 com.example.hello/.MainActivity t8 f}
,I/ActivityManager( 1027): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6057 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1027): Killing 5625:com.google.android.gms:car/u0a5 (adj 15): empty #17
,I/ActivityManager( 1027): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6085 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1027): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6104 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1027): Killing 5522:com.google.android.apps.plus/u0a97 (adj 15): empty #17


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
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of main
--------- beginning of system
D/ActivityManager(  751): handle home activity for 0
D/ActivityManager(  751): post active user change for 0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  751): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6166 uid=10109 gids={50109, 9997} abi=armeabi-v7a
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6183 uid=10115 gids={50115, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  751): Killing 5196:com.sec.spp.push:RemoteNotiProcess/u0a43 (adj 15): bgCount ##41
I/ActivityManager(  751): Killing 5219:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
I/ActivityManager(  751): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager(  751): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  751): mDVFSHelper.acquire()
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  751): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6221 uid=10408 gids={50408, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager(  751): Display changed displayId=0
D/ActivityManager(  751): post active user change for 0
I/ActivityManager(  751): Displayed com.example.hello/.MainActivity: +551ms
W/jxcore-log( 6221): Initializing JXcore engine
W/jxcore-log( 6221): JXcore engine is ready
W/jxcore-log( 6221): Starting JXcore engine
W/ActivityManager(  751): mDVFSHelper.release()
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  751): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6279 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 6221): Platform android
W/jxcore-log( 6221): 
W/jxcore-log( 6221): Process ARCH arm
W/jxcore-log( 6221): 
I/jxcore-log( 6221): JXcore Cordova bridge is ready!
I/jxcore-log( 6221): 
W/jxcore-log( 6221): JXcore engine is started
I/ActivityManager(  751): Killing 5255:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
E/jxcore-log( 6221): >> samsung-SM-N9005
E/jxcore-log( 6221): 
I/jxcore-log( 6221): Total memory 2971471872
I/jxcore-log( 6221): 
I/jxcore-log( 6221): Free memory 413872128
I/jxcore-log( 6221): 
I/jxcore-log( 6221): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6221): 
I/jxcore-log( 6221): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6221): 
I/jxcore-log( 6221): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6221): 
I/jxcore-log( 6221): Size 1080 1920
I/jxcore-log( 6221): 
I/jxcore-log( 6221): Screen Brightness 162
I/jxcore-log( 6221): 
E/jxcore-log( 6221): Dummy Error Log.
E/jxcore-log( 6221): 
,I/jxcore-log( 6221): getBuffer is called!!!!
I/jxcore-log( 6221): 
,I/jxcore-log( 6221): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 6221): 
,I/jxcore-log( 6221): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6221): 
,I/ActivityManager(  751): Force stopping com.example.hello appid=10408 user=-1: uninstall pkg
,I/ActivityManager(  751): Killing 6221:com.example.hello/u0a408 (adj 0): stop com.example.hello
,W/ActivityManager(  751): Force removing ActivityRecord{3f22e10c u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  751): mDVFSHelper.acquire()
,W/ActivityManager(  751): Spurious death for ProcessRecord{394d5622 6221:com.example.hello/u0a408}, curProc for 6221: null
,I/ActivityManager(  751): Force stopping com.example.hello appid=10408 user=0: pkg removed
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6347 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager(  751): handle home activity for 0
,D/ActivityManager(  751): post active user change for 0
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6374 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 4371:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,W/ActivityManager(  751): mDVFSHelper.release()
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6392 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 5101:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6408 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 5359:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,I/ActivityManager(  751): Killing 5381:com.sec.knox.bridge/1000 (adj 13): bgCount ##41
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6432 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6466 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  751): Process com.google.android.googlequicksearchbox:search (pid 1598)(adj 1) has died(497,1356)
,W/ActivityManager(  751): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
W/ActivityManager(  751): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
W/ActivityManager(  751): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms
,I/ActivityManager(  751): Killing 5439:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0


HTC-HTC One_M8: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  950): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  950): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5616 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  950): Displayed com.example.hello/.MainActivity: +447ms
,W/jxcore-log( 5616): Initializing JXcore engine
W/jxcore-log( 5616): JXcore engine is ready
,W/jxcore-log( 5616): Starting JXcore engine
,W/jxcore-log( 5616): Platform android
W/jxcore-log( 5616): 
W/jxcore-log( 5616): Process ARCH arm
W/jxcore-log( 5616): 
,I/jxcore-log( 5616): JXcore Cordova bridge is ready!
I/jxcore-log( 5616): 
,W/jxcore-log( 5616): JXcore engine is started
,E/jxcore-log( 5616): >> HTC-HTC One_M8
E/jxcore-log( 5616): 
,I/jxcore-log( 5616): Total memory 1912020992
I/jxcore-log( 5616): 
,I/jxcore-log( 5616): Free memory 141295616
I/jxcore-log( 5616): 
I/jxcore-log( 5616): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5616): 
I/jxcore-log( 5616): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5616): 
,I/jxcore-log( 5616): userPath [ 'www' ]
I/jxcore-log( 5616): 
,I/jxcore-log( 5616): Size 1080 1776
I/jxcore-log( 5616): 
,I/jxcore-log( 5616): Screen Brightness 142
I/jxcore-log( 5616): 
,E/jxcore-log( 5616): Dummy Error Log.
E/jxcore-log( 5616): 
,I/jxcore-log( 5616): getBuffer is called!!!!
I/jxcore-log( 5616): 
,I/ActivityManager(  950): Killing 5112:com.htc.cs.dm/u0a105 (adj 15): empty #17,
,I/ActivityManager(  950): Recipient 5112,
,I/ActivityManager(  950): Killing 5297:com.google.android.apps.docs/u0a107 (adj 15): empty #17,
,I/ActivityManager(  950): Recipient 5297
,I/ActivityManager(  950): Waited long enough for: ServiceRecord{3f6632d0 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  950): Killing 5372:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
,I/ActivityManager(  950): Recipient 5372,
,I/ActivityManager(  950): Waited long enough for: ServiceRecord{2322e851 u0 com.htc.musicenhancer/.EnhancerService},
,I/jxcore-log( 5616): ****TEST TOOK:  5086  ms ****,
I/jxcore-log( 5616): ,
I/jxcore-log( 5616): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5616): 
,I/ActivityManager(  950): Killing 5390:com.htc.sdm/u0a82 (adj 15): empty #17
,I/ActivityManager(  950): Recipient 5390
,I/ActivityManager(  950): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
I/ActivityManager(  950): Killing 5616:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  950): Recipient 5616
,W/ActivityManager(  950): Force removing ActivityRecord{16e663ce u0 com.example.hello/.MainActivity t27}: app died, no saved state
,W/ActivityManager(  950): Spurious death for ProcessRecord{f98a8db 5616:com.example.hello/u0a380}, curProc for 5616: null
,I/ActivityManager(  950): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  950): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5736 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  950): Killing 5452:com.htc.task/u0a72 (adj 15): empty #17,
,I/ActivityManager(  950): Recipient 5452
,I/ActivityManager(  950): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5763 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/ActivityManager(  950): App crashed! Process: com.google.android.gms,
,I/ActivityManager(  950): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5810 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  950): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
E/ActivityManager(  950): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4300, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
,W/ActivityManager(  950): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  950): android.os.TransactionTooLargeException
W/ActivityManager(  950): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  950): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  950): ,	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  950): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  950): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  950): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2009)
W/ActivityManager(  950): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1547)
W/ActivityManager(  950): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
W/ActivityManager(  950): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1060)
W/ActivityManager(  950): 	,at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:958)
W/ActivityManager(  950): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6859)
W/ActivityManager(  950): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
W/ActivityManager(  950): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/ActivityManager(  950): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  950): Recipient 5763
,I/ActivityManager(  950): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=5827 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/ActivityManager(  950): Spurious death for ProcessRecord{1cd5e659 5827:com.google.android.apps.docs/u0a107}, curProc for 5763: null
,I/ActivityManager(  950): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5847 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  950): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5866 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a,
,E/ActivityManager(  950): App crashed! Process: com.android.documentsui,
,I/ActivityManager(  950): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5883 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager(  950): Killing 5054:com.google.android.talk/u0a120 (adj 15): empty #17
,I/ActivityManager(  950): Recipient 5054
,W/ActivityManager(  950): Can't addPackageDependency on system process
,I/ActivityManager(  950): Killing 5233:com.google.android.gms:car/u0a25 (adj 15): empty #17,
,I/ActivityManager(  950): Recipient 5233
,I/ActivityManager(  950): Killing 4759:com.google.android.music:main/u0a167 (adj 15): empty #17
,I/ActivityManager(  950): Recipient 4759,
,I/ActivityManager(  950): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0,
,I/ActivityManager(  950): Recipient 5827
,I/ActivityManager(  950): Process com.google.android.apps.docs (pid 5827) has died
,W/ActivityManager(  950): Force removing ActivityRecord{22a36af7 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t28}: app died, no saved state
,I/ActivityManager(  950): Killing 5015:com.google.android.gm/u0a115 (adj 15): empty #17,
,I/ActivityManager(  950): Recipient 5015


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
W/ActivityManager(  818): Can't addPackageDependency on system process
F/ActivityManager(  818): Activity Manager Crash
F/ActivityManager(  818): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean com.android.server.pm.UserManagerService.hasUserRestriction(java.lang.String, int)' on a null object reference
F/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.handleIncomingUser(ActivityManagerService.java:14850)
F/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.startActivityAsUser(ActivityManagerService.java:3553)
F/ActivityManager(  818): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:164)
F/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2407)
F/ActivityManager(  818): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager(  818): Config changes=1df8 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h731dp 560dpi nrml long port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
,I/ActivityManager(  818): Config changes=508 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h658dp 560dpi nrml port ?uimode ?night finger -keyb/v/h -nav/h s.3}
,I/ActivityManager(  818): Config changes=200 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h658dp 560dpi nrml port finger -keyb/v/h -nav/h s.4}
,I/ActivityManager(  818): System now ready
,I/ActivityManager(  818): Start proc WebViewLoader-armeabi-v7a [android.webkit.WebViewFactory$RelroFileCreator] for : pid=1085 uid=1037 gids={} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.systemui for service com.android.systemui/.SystemUIService: pid=1102 uid=10024 gids={50024, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc android.process.media for broadcast com.android.providers.media/.MtpReceiver: pid=1124 uid=10008 gids={50008, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 1024} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.googlequicksearchbox:interactor for service com.google.android.googlequicksearchbox/com.google.android.voiceinteraction.GsaVoiceInteractionService: pid=1228 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.inputmethod.latin for service com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME: pid=1250 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.phone for service com.android.mms.service/.MmsService: pid=1277 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.server.telecom for added application com.android.server.telecom: pid=1289 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.nfc for added application com.android.nfc: pid=1311 uid=1027 gids={41027, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.phone for added application com.android.phone: pid=1332 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  818): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,I/ActivityManager(  818): Start proc com.google.android.googlequicksearchbox for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: pid=1352 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,V/ActivityManager(  818): Display changed displayId=0
,W/ActivityManager(  818): No pending application record for pid 1277 (IApplicationThread android.app.ApplicationThreadProxy@9a3eed4); dropping process
,V/ActivityManager(  818): Display changed displayId=0
,I/ActivityManager(  818): Start proc com.android.printspooler for service com.android.printspooler/.model.PrintSpoolerService: pid=1381 uid=10081 gids={50081, 9997} abi=armeabi-v7a
,V/ActivityManager(  818): Display changed displayId=0
,V/ActivityManager(  818): Display changed displayId=0
,I/ActivityManager(  818): Start proc android.process.acore for content provider com.android.providers.contacts/.CallLogProvider: pid=1414 uid=10005 gids={50005, 9997} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.gms.persistent for broadcast com.google.android.gms/com.google.android.location.internal.NlpNetworkProviderSettingsUpdateReceiver: pid=1442 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.process.gapps for service com.google.android.gms/.config.ConfigService: pid=1526 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/ActivityManager(  818): Display changed displayId=0
,I/ActivityManager(  818): Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService: pid=1551 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=1634 uid=10016 gids={50016, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  818): Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +1s662ms
,I/ActivityManager(  818): Start proc com.google.android.gms for service com.google.android.gms/.usagereporting.service.UsageReportingService: pid=1742 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=1785 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.audio.MediaButtonIntentReceiver: pid=1841 uid=10067 gids={50067, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider: pid=1957 uid=10051 gids={50051, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=1975 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=1999 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.dialer for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver: pid=2038 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2049 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.motorola.motocit for broadcast com.motorola.motocit/.CQATestBootReceiver: pid=2094 uid=10002 gids={50002, 9997, 3002, 3001, 1028, 1015, 1023, 3003} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=2118 uid=10003 gids={50003, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2139 uid=10015 gids={50015, 9997} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2164 uid=10017 gids={50017, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2185 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc org.simalliance.openmobileapi.service:remote for service org.simalliance.openmobileapi.service/.SmartcardService: pid=2202 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=2219 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2246 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2324 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2427 uid=10044 gids={50044, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 1841:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  818): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2450 uid=10019 gids={50019, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  818): Killing 1381:com.android.printspooler/u0a81 (adj 15): empty #17
,I/ActivityManager(  818): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=2486 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2506 uid=10078 gids={50078, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  818): Killing 2049:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  818): Killing 2038:com.google.android.dialer/u0a13 (adj 15): empty #17
,I/ActivityManager(  818): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2540 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  818): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/ActivityManager(  818): Start proc com.google.android.apps.messaging for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver: pid=2571 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 2094:com.motorola.motocit/u0a2 (adj 15): empty #17
,I/ActivityManager(  818): Killing 1785:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  818): Start proc com.android.sdm.plugins.sprintdm for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver: pid=2609 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2627 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 2139:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
,I/ActivityManager(  818): Killing 2164:com.android.managedprovisioning/u0a17 (adj 15): empty #17
,I/ActivityManager(  818): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2649 uid=10066 gids={50066, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 2185:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/ActivityManager(  818): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=2694 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  818): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
I/ActivityManager(  818): Resuming delayed broadcast
,I/ActivityManager(  818): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  818): Resuming delayed broadcast
,I/ActivityManager(  818): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2748 uid=10074 gids={50074, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 2246:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/ActivityManager(  818): Killing 1975:com.google.android.keep/u0a79 (adj 15): empty #17,
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{d016d0e u0 org.simalliance.openmobileapi.service/.SmartcardService},
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{35d4479 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService},
,I/ActivityManager(  818): Killing 2324:com.google.android.youtube/u0a86 (adj 15): empty #17,
,I/ActivityManager(  818): Killing 2427:com.google.android.deskclock/u0a44 (adj 15): empty #17
,V/ActivityManager(  818): Display changed displayId=0
,I/ActivityManager(  818): Killing 2486:com.google.android.gms:car/u0a11 (adj 15): empty #17
,TIME-OUT KILL (timeout was 150000ms),I/ActivityManager(  818): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  818): Force stopping com.example.hello appid=10272 user=0: pkg removed
I/ActivityManager(  818): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2841 uid=10018 gids={50018, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  818): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2863 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  818): Killing 2540:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/ActivityManager(  818): Killing 1957:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/ActivityManager(  818): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2897 uid=10046 gids={50046, 9997, 1028, 3003, 1015} abi=armeabi-v7a


```

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on 022678fb504e29b0 
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
--------- beginning of system
W/ActivityManager( 1019): mDVFSHelper.acquire()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5354 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1019): Display changed displayId=0
W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{265c32c6 u0 com.example.hello/.MainActivity t19}
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/ActivityManager( 1019): Displayed Component not be shown by security: +607ms (total +687ms)
W/ActivityManager( 1019): mDVFSHelper.release()
,W/jxcore-log( 5354): Initializing JXcore engine
W/jxcore-log( 5354): JXcore engine is ready
W/jxcore-log( 5354): Starting JXcore engine
W/jxcore-log( 5354): Platform android
W/jxcore-log( 5354): 
W/jxcore-log( 5354): Process ARCH arm
W/jxcore-log( 5354): 
I/jxcore-log( 5354): JXcore Cordova bridge is ready!
I/jxcore-log( 5354): 
W/jxcore-log( 5354): JXcore engine is started
E/jxcore-log( 5354): >> samsung-SM-A300FU
E/jxcore-log( 5354): 
I/jxcore-log( 5354): Total memory 1451114496
I/jxcore-log( 5354): 
I/jxcore-log( 5354): Free memory 22364160
I/jxcore-log( 5354): 
I/jxcore-log( 5354): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5354): 
I/jxcore-log( 5354): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5354): 
I/jxcore-log( 5354): userPath [ 'www' ]
I/jxcore-log( 5354): 
I/jxcore-log( 5354): Size 540 960
I/jxcore-log( 5354): 
I/jxcore-log( 5354): Screen Brightness 160
I/jxcore-log( 5354): 
E/jxcore-log( 5354): Dummy Error Log.
E/jxcore-log( 5354): 
I/jxcore-log( 5354): getBuffer is called!!!!
I/jxcore-log( 5354): 
,I/jxcore-log( 5354): ****TEST TOOK:  5049  ms ****
I/jxcore-log( 5354): 
,I/jxcore-log( 5354): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5354): 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5354:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{265c32c6 u0 com.example.hello/.MainActivity t19}
,W/ActivityManager( 1019): Spurious death for ProcessRecord{3cda71b9 5354:com.example.hello/u0a345}, curProc for 5354: null
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5418 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/ActivityManager( 1019): Killing 4863:com.wssyncmldm/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5439 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4884:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5474 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5486 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,


HTC-HTC One M8s: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  925): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4985 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  925): Killing 4443:com.google.android.youtube/u0a176 (adj 15): empty #17
I/ActivityManager(  925): Recipient 4443
I/ActivityManager(  925): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5019 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  925): Killing 3793:com.android.defcontainer/u0a15 (adj 15): empty #17
I/ActivityManager(  925): Recipient 3793
I/ActivityManager(  925): Killing 4525:com.google.android.gm/u0a106 (adj 15): empty #17
I/ActivityManager(  925): Recipient 4525
,I/ActivityManager(  925): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5059 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  925): Killing 4598:com.google.android.partnersetup/u0a27 (adj 15): empty #17
I/ActivityManager(  925): Recipient 4598
I/ActivityManager(  925): Killing 4566:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
I/ActivityManager(  925): Recipient 4566
I/ActivityManager(  925): Killing 4684:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
I/ActivityManager(  925): Recipient 4684
I/ActivityManager(  925): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5056 on display 0
I/ActivityManager(  925): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5105 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  925): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5134 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  925): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5162 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  925): Killing 4710:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
I/ActivityManager(  925): Recipient 4710
I/ActivityManager(  925): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5198 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  925): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5238 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  925): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
I/ActivityManager(  925): Resuming delayed broadcast
I/ActivityManager(  925): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5263 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  925): Killing 4758:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
I/ActivityManager(  925): Recipient 4758
I/ActivityManager(  925): Displayed com.example.hello/.MainActivity: +1s184ms
,I/ActivityManager(  925): Killing 4802:com.htc.mobiledata/u0a46 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 4802
,I/ActivityManager(  925): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5296 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,W/jxcore-log( 5105): Initializing JXcore engine
,W/jxcore-log( 5105): JXcore engine is ready
,W/jxcore-log( 5105): Starting JXcore engine
,I/ActivityManager(  925): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5319 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  925): Killing 4410:com.google.android.talk/u0a112 (adj 15): empty #17
,W/jxcore-log( 5105): Platform android,
W/jxcore-log( 5105): 
W/jxcore-log( 5105): Process ARCH arm
W/jxcore-log( 5105): 
,I/ActivityManager(  925): Recipient 4410
,I/jxcore-log( 5105): JXcore Cordova bridge is ready!
I/jxcore-log( 5105): 
,W/jxcore-log( 5105): JXcore engine is started
,E/jxcore-log( 5105): >> HTC-HTC One M8s,
E/jxcore-log( 5105): 
,I/jxcore-log( 5105): Total memory 1931808768,
I/jxcore-log( 5105): 
I/jxcore-log( 5105): Free memory 86994944
I/jxcore-log( 5105): 
I/jxcore-log( 5105): execPath /data/data/com.example.hello/files/www/jxcore,
I/jxcore-log( 5105): 
I/jxcore-log( 5105): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5105): 
,I/jxcore-log( 5105): userPath [ 'www' ],
I/jxcore-log( 5105): 
,I/jxcore-log( 5105): Size 1080 1776
I/jxcore-log( 5105): 
,I/jxcore-log( 5105): Screen Brightness 142
I/jxcore-log( 5105): 
E/jxcore-log( 5105): Dummy Error Log.
E/jxcore-log( 5105): 
,I/ActivityManager(  925): Cannot resolve ContentProvider=com.htc.vowifi
,I/ActivityManager(  925): Cannot resolve ContentProvider=com.htc.vowifi,
,I/ActivityManager(  925): Killing 4831:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
,I/ActivityManager(  925): Recipient 4831
,I/ActivityManager(  925): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5361 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager(  925): Killing 4861:com.htc.backupreset/1000 (adj 15): empty #17,
,I/ActivityManager(  925): Recipient 4861
,I/jxcore-log( 5105): getBuffer is called!!!!
I/jxcore-log( 5105): 
,I/ActivityManager(  925): Killing 4911:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 4911
,I/ActivityManager(  925): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5400 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/ActivityManager(  925): Killing 4937:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 4937,
,I/ActivityManager(  925): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5451 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager(  925): Killing 4780:com.htc.task/u0a69 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 4780
,I/ActivityManager(  925): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5480 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/ActivityManager(  925): Killing 4985:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 4985
,I/ActivityManager(  925): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5503 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
,I/ActivityManager(  925): Killing 5059:com.htc.task.gtask/u0a66 (adj 15): empty #17,
,I/ActivityManager(  925): Recipient 5059,
,I/ActivityManager(  925): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  925): Resuming delayed broadcast,
,I/ActivityManager(  925): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  925): Resuming delayed broadcast
,I/ActivityManager(  925): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5555 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  925): Killing 3706:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 3706
,I/ActivityManager(  925): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5581 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  925): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5610 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  925): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5636 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  925): Killing 4883:com.htc.bgp/u0a11 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 4883,
,W/ActivityManager(  925): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/jxcore-log( 5105): ****TEST TOOK:  5128  ms ****,
I/jxcore-log( 5105): 
I/jxcore-log( 5105): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5105): 
,W/ActivityManager(  925): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  925): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  925): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  925): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5714 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  925): Killing 4731:com.htc.sense.news/u0a74 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 4731
,I/ActivityManager(  925): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg,
,I/ActivityManager(  925): Killing 5105:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  925): Recipient 5105
,W/ActivityManager(  925): Force removing ActivityRecord{3283058a u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  925): Force stopping com.example.hello appid=10373 user=0: pkg removed
,W/ActivityManager(  925): Spurious death for ProcessRecord{19a503c5 5105:com.example.hello/u0a373}, curProc for 5105: null,
,I/ActivityManager(  925): Killing 5238:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,I/ActivityManager(  925): Recipient 5238
,I/ActivityManager(  925): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=5741 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/ActivityManager(  925): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5763 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  925): Killing 5263:com.htc.cs.dm/u0a99 (adj 15): empty #17,
,I/ActivityManager(  925): Recipient 5263,
,I/ActivityManager(  925): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  925): Resuming delayed broadcast
,I/ActivityManager(  925): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  925): Resuming delayed broadcast
,I/ActivityManager(  925): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  925): Resuming delayed broadcast
,E/ActivityManager(  925): App crashed! Process: com.google.android.music:main
,I/ActivityManager(  925): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  925): Resuming delayed broadcast
,I/ActivityManager(  925): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5837 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/ActivityManager(  925): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5852 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,E/ActivityManager(  925): App crashed! Process: com.google.android.googlequicksearchbox:search
,E/ActivityManager(  925): App crashed! Process: com.nero.android.htc.sync,
,W/ActivityManager(  925): Can't addPackageDependency on system process,
,I/ActivityManager(  925): Killing 5296:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  960): Killing 3344:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327cbc8 stackId=1, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3977
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327cbc8 stackId=1, 2 tasks}
V/ActivityManager(  960): Moving to PAUSING: ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  960): resumeTopActivityLocked: Pausing null
V/ActivityManager(  960): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  960): setFocusedStack: mFocusedStack=ActivityStack{4327cbc8 stackId=1, 2 tasks}
D/ActivityManager(  960): allPausedActivitiesComplete: r=ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  960): startService SlideAside
V/ActivityManager(  960): Moving to PAUSED: ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327cbc8 stackId=1, 2 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Restarting ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  960): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3993 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3} (starting new instance)
,I/ActivityManager(  960): Displayed com.example.hello/.MainActivity: +375ms
,I/ActivityManager( 3993): Timeline: Activity_idle id: android.os.BinderProxy@4289ad00 time:47303
,W/jxcore-log( 3993): Initializing JXcore engine
,W/jxcore-log( 3993): JXcore engine is ready
,W/jxcore-log( 3993): Starting JXcore engine
,I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3} time:47686
D/ActivityManager(  960): no-history finish of ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  960): Finishing activity token=Token{430dbaf0 ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  960): Moving to FINISHING: ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2 f}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  960): Moving to STOPPING: ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  960): Moving to STOPPED: ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,W/jxcore-log( 3993): Platform android
W/jxcore-log( 3993): 
,W/jxcore-log( 3993): Process ARCH arm
W/jxcore-log( 3993): 
,I/jxcore-log( 3993): JXcore Cordova bridge is ready!
I/jxcore-log( 3993): 
,W/jxcore-log( 3993): JXcore engine is started
,E/jxcore-log( 3993): >> LGE-LG-D802
E/jxcore-log( 3993): 
,I/jxcore-log( 3993): Total memory 1943035904
I/jxcore-log( 3993): 
I/jxcore-log( 3993): Free memory 473899008
I/jxcore-log( 3993): 
I/jxcore-log( 3993): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3993): 
,I/jxcore-log( 3993): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3993): 
,I/jxcore-log( 3993): userPath [ 'www' ]
I/jxcore-log( 3993): 
,I/jxcore-log( 3993): Size 1080 1776
I/jxcore-log( 3993): 
,I/jxcore-log( 3993): Screen Brightness 255
I/jxcore-log( 3993): 
,E/jxcore-log( 3993): Dummy Error Log.
E/jxcore-log( 3993): 
,I/jxcore-log( 3993): getBuffer is called!!!!
I/jxcore-log( 3993): 
,I/ActivityManager(  960): Killing 3406:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327cbc8 stackId=1, 2 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3993): ****TEST TOOK:  5042  ms ****
I/jxcore-log( 3993): 
I/jxcore-log( 3993): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3993): 
,I/ActivityManager(  960): Waited long enough for: ServiceRecord{431fda40 u0 com.android.mms/.transaction.SmsReceiverService}
,I/ActivityManager(  960): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  960): Killing 3993:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  960): Force removing ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{43110fd8 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327cbc8 stackId=1, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  960): moveHomeStack:
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
,V/ActivityManager(  960): Moving to RESUMED: ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  960): resumeTopActivityLocked: Resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  960): Moving to DESTROYING: ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  960): Moving to DESTROYED: ActivityRecord{431fc860 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4080 uid=10090 gids={50090}
,I/ActivityManager(  960): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4104 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  960): Killing 3294:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  960): Service ServiceRecord{4331be30 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432a1e40 3294:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  960): Service ServiceRecord{43224378 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432a1e40 3294:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  960): Killing 2089:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4133 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  960): Delaying start of: ServiceRecord{43183b80 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  960): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4151 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  960): Killing 3808:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
I/ActivityManager(  960): Killing 3862:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
,D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): Timeline: Activity_windows_visible id: ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1} time:54321
,I/ActivityManager(  960): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4165 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  960): Killing 3214:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  960): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c25fe0 stackId=0, 1 tasks}
D/ActivityManager(  960): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ba5778 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  960): Delaying start of: ServiceRecord{42a05da0 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager( 1486): Timeline: Activity_idle id: android.os.BinderProxy@4289ffb0 time:54377


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device c5afcdcb app:com.example.hello code:0 
child process exited with code 0 on device c5afcdcb 
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of system
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
--------- beginning of main
I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4900 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4295:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/ActivityManager( 1019): Waited long enough for: ServiceRecord{1b150c51 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4926 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4201:com.google.android.music:main/u0a111 (adj 15): empty #31
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 4395:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=4972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=4984 uid=10150 gids={50150, 9997} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/ActivityManager( 1019): Killing 4311:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
I/ActivityManager( 1019): Killing 4440:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1019): mDVFSHelper.acquire()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5016 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5031 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5049 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/ActivityManager( 1019): Process ACMS.Process (pid 4688)(adj 0) has died(35,1064)
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/ActivityManager( 1019): Waited long enough for: ServiceRecord{25484a05 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1019): Displayed Component not be shown by security: +906ms
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5115 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5126 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=5144 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5162 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4230:com.android.mms/u0a46 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 4428:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1019): Killing 4459:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
W/jxcore-log( 5031): Initializing JXcore engine
W/jxcore-log( 5031): JXcore engine is ready
,W/jxcore-log( 5031): Starting JXcore engine
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4476:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 5031): Platform android
W/jxcore-log( 5031): 
W/jxcore-log( 5031): Process ARCH arm
W/jxcore-log( 5031): 
,I/ActivityManager( 1019): Killing 4493:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5031): JXcore Cordova bridge is ready!
I/jxcore-log( 5031): 
,W/jxcore-log( 5031): JXcore engine is started
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/jxcore-log( 5031): >> samsung-SM-A500FU
E/jxcore-log( 5031): 
,I/jxcore-log( 5031): Total memory 1983787008
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): Free memory 46247936
I/jxcore-log( 5031): 
I/jxcore-log( 5031): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5031): 
I/jxcore-log( 5031): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): Size 720 1280
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): Screen Brightness 255
I/jxcore-log( 5031): 
,E/jxcore-log( 5031): Dummy Error Log.
E/jxcore-log( 5031): 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1019): Killing 4508:com.sec.pcw.device/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5225 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{f118656 u0 com.sec.bcservice/.BroadcastService}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=5243 uid=10040 gids={50040, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,I/ActivityManager( 1019): Killing 3951:com.policydm/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5265 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Process com.samsung.indexservice (pid 5225)(adj 11) has died(42,1035)
,I/jxcore-log( 5031): getBuffer is called!!!!
I/jxcore-log( 5031): 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1019): Killing 4569:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.async.BackgroundTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1019): Killing 4589:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5287 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/ActivityManager( 1019): Display changed displayId=0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4604:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{2d8c57d4 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/ActivityManager( 1019): Killing 4028:com.osp.app.signin/u0a41 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/jxcore-log( 5031): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5031): 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 5031:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{1e7f36f9 u0 com.example.hello/.MainActivity t11}
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10174 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5354 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5369 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=5382 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5400 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5418 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5432 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4737:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 4753:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5451 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=5467 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4803:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 3991:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 4844:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
W/ActivityManager(  859): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4380 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  859): Killing 3521:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4402 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  859): Killing 3554:com.sec.android.automotive.drivelinkremote/u0a100 (adj 15): bgCount ##41
I/ActivityManager(  859): Killing 3581:com.dropbox.android/u0a101 (adj 15): bgCount ##41
I/ActivityManager(  859): Waited long enough for: ServiceRecord{266fae2c u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4427 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  859): Killing 3370:tv.peel.smartremote/u0a171 (adj 15): bgCount ##41
I/ActivityManager(  859): Process com.sec.factory (pid 3090)(adj 0) has died(50,701)
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4458 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.LocalFota for broadcast com.LocalFota/.XLFBroadcastReceiver: pid=4473 uid=10120 gids={50120, 9997, 3003, 2001} abi=armeabi-v7a
I/ActivityManager(  859): Killing 3598:org.simalliance.openmobileapi.service/1101 (adj 15): bgCount ##41
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.walkingmate.receiver.WalkingMateReceiver: pid=4486 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  859): Killing 2357:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
I/ActivityManager(  859): Killing 3636:com.samsung.android.scloud.backup/u0a65 (adj 15): bgCount ##41
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4514 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3674:com.fmm.dm/1000 (adj 15): bgCount ##41
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4545 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  859): Killing 3692:com.sec.android.app.taskmanager/u0a176 (adj 15): bgCount ##41
I/ActivityManager(  859): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  859): mDVFSHelper.acquire()
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4581 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  859): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=4595 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4613 uid=10143 gids={50143, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3726:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
,I/ActivityManager(  859): Killing 3760:com.samsung.android.service.travel/u0a178 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4688 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 2058:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,D/ActivityManager(  859): post active user change for 0
,I/ActivityManager(  859): Displayed com.example.hello/.MainActivity: +1s108ms
,W/ActivityManager(  859): mDVFSHelper.release()
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4751 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3775:com.sec.usbsettings/1000 (adj 15): bgCount ##41
,I/ActivityManager(  859): Killing 3620:com.sec.android.fotaclient/u0a11 (adj 15): bgCount ##42
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4839 uid=10154 gids={50154, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,W/jxcore-log( 4581): Initializing JXcore engine
W/jxcore-log( 4581): JXcore engine is ready
,W/jxcore-log( 4581): Starting JXcore engine
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4855 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 4581): Platform android
W/jxcore-log( 4581): 
W/jxcore-log( 4581): Process ARCH arm
W/jxcore-log( 4581): 
,I/jxcore-log( 4581): JXcore Cordova bridge is ready!
I/jxcore-log( 4581): 
,W/jxcore-log( 4581): JXcore engine is started
,E/jxcore-log( 4581): >> samsung-SM-G900F
E/jxcore-log( 4581): 
,I/jxcore-log( 4581): Total memory 1787449344
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): Free memory 49557504
I/jxcore-log( 4581): 
I/jxcore-log( 4581): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4581): 
I/jxcore-log( 4581): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): Size 1080 1920
I/jxcore-log( 4581): 
,I/jxcore-log( 4581): Screen Brightness 134
I/jxcore-log( 4581): 
,E/jxcore-log( 4581): Dummy Error Log.
E/jxcore-log( 4581): 
,I/ActivityManager(  859): Killing 3710:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4886 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  859): Process com.sec.android.app.sns3 (pid 4751)(adj 0) has died(47,622)
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4913 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 4581): getBuffer is called!!!!
I/jxcore-log( 4581): 
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4940 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  859): Killing 3805:com.sec.factory.camera/1000 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4946 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4977 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3824:com.google.android.onetimeinitializer/u0a14 (adj 15): bgCount ##41
,I/ActivityManager(  859): Killing 3793:com.wssnps/1000 (adj 15): bgCount ##42
,W/ActivityManager(  859): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager(  859): getTasks: caller 10163 does not hold GET_TASKS; limiting output
,I/ActivityManager(  859): Killing 3839:com.samsung.android.app.accesscontrol/1000 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4999 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3164:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,I/ActivityManager(  859): Process com.android.email (pid 4886)(adj 11) has died(67,617)
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=5011 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5021 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3855:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/ActivityManager(  859): Killing 3913:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=5052 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3919:com.samsung.android.provider.filterprovider/u0a109 (adj 15): bgCount ##41
,W/ActivityManager(  859): getTasks: caller 10164 does not hold GET_TASKS; limiting output
,I/ActivityManager(  859): Process com.android.exchange (pid 4977)(adj 11) has died(77,623)
,I/ActivityManager(  859): Killing 3939:com.samsung.android.app.airwakeupview/u0a72 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5083 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/ActivityManager(  859): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5102 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3966:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5141 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3984:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5157 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=5173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  859): Killing 3997:com.samsung.klmsagent/u0a19 (adj 15): bgCount ##41
,I/ActivityManager(  859): Killing 3876:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  859): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  859): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5190 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a


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
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5026 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1018): Display changed displayId=0
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{fc380b1 u0 com.example.hello/.MainActivity t10}
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/ActivityManager( 1018): Displayed Component not be shown by security: +635ms (total +709ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
,W/jxcore-log( 5026): Initializing JXcore engine
W/jxcore-log( 5026): JXcore engine is ready
,W/jxcore-log( 5026): Starting JXcore engine
,W/jxcore-log( 5026): Platform android
W/jxcore-log( 5026): 
W/jxcore-log( 5026): Process ARCH arm
W/jxcore-log( 5026): 
,I/jxcore-log( 5026): JXcore Cordova bridge is ready!
I/jxcore-log( 5026): 
,W/jxcore-log( 5026): JXcore engine is started
,E/jxcore-log( 5026): >> samsung-SM-A300FU
E/jxcore-log( 5026): 
,I/jxcore-log( 5026): Total memory 1451114496
I/jxcore-log( 5026): 
,I/jxcore-log( 5026): Free memory 23367680
I/jxcore-log( 5026): 
I/jxcore-log( 5026): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5026): 
,I/jxcore-log( 5026): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5026): 
,I/jxcore-log( 5026): userPath [ 'www' ]
I/jxcore-log( 5026): 
,I/jxcore-log( 5026): Size 540 960
I/jxcore-log( 5026): 
,I/jxcore-log( 5026): Screen Brightness 255
I/jxcore-log( 5026): 
E/jxcore-log( 5026): Dummy Error Log.
E/jxcore-log( 5026): 
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{31e61413 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5026): getBuffer is called!!!!
I/jxcore-log( 5026): 
,I/jxcore-log( 5026): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 5026): 
,I/jxcore-log( 5026): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5026): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5026:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{fc380b1 u0 com.example.hello/.MainActivity t10}
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5094 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5105 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5126 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5164 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5177 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 4432:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5197 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4171:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 4119:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2198
I/ActivityManager(  904): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2209 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/ActivityManager(  904): Waited long enough for: ServiceRecord{42ed76d0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2239 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  904): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2258 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Killing 1809:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
I/ActivityManager(  904): Recipient 1809
I/ActivityManager(  904): Killing 1825:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/ActivityManager(  904): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2279 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  904): Recipient 1825
I/ActivityManager(  904): Displayed com.example.hello/.MainActivity: +421ms
I/ActivityManager(  904): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2291 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
I/ActivityManager(  904): Killing 1909:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  904): Recipient 1909
I/ActivityManager(  904): Delay finish: com.android.providers.calendar/.CalendarReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2307 uid=10016 gids={50016, 3003, 5012, 2001}
I/ActivityManager(  904): Killing 1261:com.android.printspooler/u0a161 (adj 15): empty #17
I/ActivityManager(  904): Recipient 1261
I/ActivityManager(  904): Killing 1979:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2342 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Recipient 1979
I/ActivityManager(  904): Delay finish: com.android.providers.downloads/.DownloadReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2359 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Killing 1969:com.htc.showme/u0a82 (adj 15): empty #17
I/ActivityManager(  904): Recipient 1969
I/ActivityManager(  904): Killing 1868:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
I/ActivityManager(  904): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
I/ActivityManager(  904): Recipient 1868
I/ActivityManager(  904): Resuming delayed broadcast
W/jxcore-log( 2209): Initializing JXcore engine
W/jxcore-log( 2209): JXcore engine is ready
W/jxcore-log( 2209): Starting JXcore engine
I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
W/ActivityManager(  904): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,W/jxcore-log( 2209): Platform android
W/jxcore-log( 2209): 
,W/jxcore-log( 2209): Process ARCH arm
W/jxcore-log( 2209): 
,I/jxcore-log( 2209): JXcore Cordova bridge is ready!
I/jxcore-log( 2209): 
,W/jxcore-log( 2209): JXcore engine is started
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2395 uid=10030 gids={50030}
,E/jxcore-log( 2209): >> HTC-HTC Desire 820
E/jxcore-log( 2209): 
,I/jxcore-log( 2209): Total memory 1964650496
I/jxcore-log( 2209): 
I/jxcore-log( 2209): Free memory 831897600
I/jxcore-log( 2209): 
,I/jxcore-log( 2209): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2209): 
,I/jxcore-log( 2209): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2209): 
,I/jxcore-log( 2209): userPath [ 'www' ]
I/jxcore-log( 2209): 
,I/jxcore-log( 2209): Size 720 1184
I/jxcore-log( 2209): 
,I/jxcore-log( 2209): Screen Brightness 10
I/jxcore-log( 2209): 
,E/jxcore-log( 2209): Dummy Error Log.
E/jxcore-log( 2209): 
,I/ActivityManager(  904): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2409 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  904): Killing 1847:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/ActivityManager(  904): Recipient 1847
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Killing 2045:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2045
,I/ActivityManager(  904): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2437 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  904): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2449 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  904): Killing 1928:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 1928
,I/jxcore-log( 2209): getBuffer is called!!!!
I/jxcore-log( 2209): 
,I/ActivityManager(  904): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2461 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  904): Killing 2061:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2061
,I/ActivityManager(  904): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2478 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  904): Killing 2079:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2079
,I/ActivityManager(  904): Killing 2102:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  904): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2490 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  904): Recipient 2102
,I/ActivityManager(  904): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2504 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  904): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2520 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/ActivityManager(  904): Killing 1655:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,I/ActivityManager(  904): Killing 1945:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 1945
,I/ActivityManager(  904): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2535 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  904): Killing 2239:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2239
,I/ActivityManager(  904): Recipient 1655
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2548 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  904): Killing 2258:com.qualcomm.privinit/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2258
,I/ActivityManager(  904): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Killing 2279:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  904): Recipient 2279
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42e4d180 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2573 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,I/ActivityManager(  904): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2585 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  904): Killing 2307:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2307
,I/ActivityManager(  904): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2600 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,I/ActivityManager(  904): Killing 2342:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2342
,I/ActivityManager(  904): Delay finish: com.htc.lmw/.StorageBroadcastReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2617 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  904): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2641 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
I/ActivityManager(  904): Killing 2359:com.htc.fm/u0a24 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2359
,I/ActivityManager(  904): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{4300c3d0 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2663 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2695 uid=10077 gids={50077}
,I/ActivityManager(  904): Killing 2395:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2395
,I/ActivityManager(  904): Killing 2409:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2409
,I/ActivityManager(  904): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2710 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,I/ActivityManager(  904): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2726 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  904): Killing 2437:com.htc.csrecommend/u0a33 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2437
,I/ActivityManager(  904): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2740 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
,I/ActivityManager(  904): Killing 2449:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2449
,I/ActivityManager(  904): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=2755 uid=10031 gids={50031, 3003, 5012}
,I/jxcore-log( 2209): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 2209): 
,I/jxcore-log( 2209): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2209): 
,I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
,I/ActivityManager(  904): Killing 2461:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2461
,I/ActivityManager(  904): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  904): Killing 2209:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  904): Force removing ActivityRecord{4311a928 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  904): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 2478:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2478
,I/ActivityManager(  904): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=2821 uid=10090 gids={50090, 3003, 5012, 1028}
,I/ActivityManager(  904): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=2842 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  904): Killing 2490:com.htc.aurora/u0a47 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2490
,I/ActivityManager(  904): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2854 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  904): Killing 2504:com.htc.aurora:remote/u0a47 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2504
,I/ActivityManager(  904): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=2869 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  904): Killing 2520:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2520
,I/ActivityManager(  904): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  908): Killing 2558:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  908): Killing 2572:com.htc.updater/u0a85 (adj 15): empty #17
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Recipient 2572
I/ActivityManager(  908): Killing 2604:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2558
I/ActivityManager(  908): Recipient 2604
I/ActivityManager(  908): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2870 uid=9987 gids={49987}
I/ActivityManager(  908): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2886 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
,I/ActivityManager(  908): Killing 2630:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2630
I/ActivityManager(  908): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2898 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 2650:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2650
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2906
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2947 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  908): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +260ms
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,W/jxcore-log( 2947): Initializing JXcore engine
,W/jxcore-log( 2947): JXcore engine is ready
,W/jxcore-log( 2947): Starting JXcore engine
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,W/jxcore-log( 2947): Platform android
W/jxcore-log( 2947): 
,W/jxcore-log( 2947): Process ARCH arm
W/jxcore-log( 2947): 
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3044 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/jxcore-log( 2947): JXcore Cordova bridge is ready!
I/jxcore-log( 2947): 
,W/jxcore-log( 2947): JXcore engine is started
,E/jxcore-log( 2947): >> HTC-HTC Desire 820
E/jxcore-log( 2947): 
,I/jxcore-log( 2947): Total memory 1964650496
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Free memory 696143872
I/jxcore-log( 2947): 
I/jxcore-log( 2947): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): userPath [ 'www' ]
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Size 720 1184
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Screen Brightness 142
I/jxcore-log( 2947): 
,E/jxcore-log( 2947): Dummy Error Log.
E/jxcore-log( 2947): 
,I/ActivityManager(  908): Killing 2662:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2662
,I/ActivityManager(  908): Delay finish: com.android.settings/.NSReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3085 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,I/jxcore-log( 2947): getBuffer is called!!!!
I/jxcore-log( 2947): 
,I/ActivityManager(  908): Killing 2457:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3124 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  908): Recipient 2457
,I/ActivityManager(  908): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3136 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 2691:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  908): Killing 2734:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2691
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3153 uid=10041 gids={50041}
,I/ActivityManager(  908): Recipient 2734
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3168 uid=10078 gids={50078}
,I/ActivityManager(  908): Killing 2677:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Killing 2755:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3181 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Recipient 2677
,I/ActivityManager(  908): Recipient 2755
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3197 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  908): Killing 2782:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2782
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3212 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3226 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 2799:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2799
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3241 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  908): Killing 2814:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2814
I/ActivityManager(  908): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3253 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3265 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  908): Killing 2870:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  908): Killing 2841:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
I/ActivityManager(  908): Recipient 2841
I/ActivityManager(  908): Recipient 2870
I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2886:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3281 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  908): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/ActivityManager(  908): Recipient 2886
I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3295 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2898:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  908): Killing 3044:com.android.vending/u0a74 (adj 15): empty #17
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  908): Recipient 3044
I/ActivityManager(  908): Recipient 2898
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2853:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Recipient 2853
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3320 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3340 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 3085:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3085
,I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3357 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Killing 3124:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3124
,I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3377 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3396 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Killing 3136:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3136
,I/ActivityManager(  908): Killing 3181:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3181
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3418 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/jxcore-log( 2947): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 2947): 
I/jxcore-log( 2947): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2947): 
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,I/ActivityManager(  908): Killing 2947:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  908): Force removing ActivityRecord{4304e740 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  908): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3450 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  908): Killing 2828:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2828
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver


LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  773): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2169 uid=10001 gids={50001, 3003, 1028, 1015}
I/ActivityManager(  773): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2143
I/ActivityManager(  773): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2184 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  773): Killing 1229:com.google.android.partnersetup/u0a11 (adj 15): empty #17
I/ActivityManager(  773): Killing 1578:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #18
,I/ActivityManager(  773): Displayed com.example.hello/.MainActivity: +289ms
,W/jxcore-log( 2184): Initializing JXcore engine
,W/jxcore-log( 2184): JXcore engine is ready
,W/jxcore-log( 2184): Starting JXcore engine
,W/jxcore-log( 2184): Platform android
W/jxcore-log( 2184): 
,W/jxcore-log( 2184): Process ARCH arm
W/jxcore-log( 2184): 
,I/jxcore-log( 2184): JXcore Cordova bridge is ready!
I/jxcore-log( 2184): 
,W/jxcore-log( 2184): JXcore engine is started
,E/jxcore-log( 2184): >> LGE-Nexus 5
E/jxcore-log( 2184): 
,I/jxcore-log( 2184): Total memory 1945137152
I/jxcore-log( 2184): 
I/jxcore-log( 2184): Free memory 933343232
I/jxcore-log( 2184): 
I/jxcore-log( 2184): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2184): 
,I/jxcore-log( 2184): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2184): 
,I/jxcore-log( 2184): userPath [ 'www' ]
I/jxcore-log( 2184): 
,I/jxcore-log( 2184): Size 1080 1776
I/jxcore-log( 2184): 
,I/jxcore-log( 2184): Screen Brightness 82
I/jxcore-log( 2184): 
,E/jxcore-log( 2184): Dummy Error Log.
E/jxcore-log( 2184): 
,I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Killing 1606:com.android.vending/u0a14 (adj 15): empty #17
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/jxcore-log( 2184): getBuffer is called!!!!
I/jxcore-log( 2184): 
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
I/ActivityManager(  773): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2293 uid=10011 gids={50011, 3003}
,I/ActivityManager(  773): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2308 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  773): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2322 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  773): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,I/ActivityManager(  773): Killing 1679:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  773): Delaying start of: ServiceRecord{42c9ce58 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  773): Killing 1707:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  773): Waited long enough for: ServiceRecord{42d0b738 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2366 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,I/ActivityManager(  773): Killing 1083:com.android.printspooler/u0a64 (adj 15): empty #17
,I/ActivityManager(  773): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2417 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  773): Waited long enough for: ServiceRecord{42b70e48 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  773): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2433 uid=10035 gids={50035, 1028, 3003, 1015}
W/ActivityManager(  773): No permission grants found for com.quickoffice.android
I/ActivityManager(  773): Killing 1756:com.google.android.keep/u0a52 (adj 15): empty #17
,I/ActivityManager(  773): Killing 1793:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  773): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  773): Resuming delayed broadcast
,I/jxcore-log( 2184): ****TEST TOOK:  5021  ms ****
I/jxcore-log( 2184): 
,I/jxcore-log( 2184): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2184): 
,I/ActivityManager(  773): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  773): Killing 2184:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  773): Force removing ActivityRecord{42f52f30 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  773): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  773): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2536 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/ActivityManager(  773): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  773): Resuming delayed broadcast
,I/ActivityManager(  773): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2571 uid=10034 gids={50034}
,I/ActivityManager(  773): Killing 1820:com.google.android.youtube/u0a71 (adj 15): empty #17
,I/ActivityManager(  773): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2593 uid=10006 gids={50006, 1028, 1015, 1023}
,F/ActivityManager(  773): Service ServiceRecord{42de46a8 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42d36ca0 1820:com.google.android.youtube/u0a71} not same as in map: null
,I/ActivityManager(  773): Killing 1940:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/ActivityManager(  773): Killing 1692:com.google.android.deskclock/u0a33 (adj 15): empty #17


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
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/80F96111-6E75-49A2-A187-0DA1B76FFA5F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/80F96111-6E75-49A2-A187-0DA1B76FFA5F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/770B190A-1630-402F-AFD5-54E80077A7B7/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64780"
,(lldb)     command script import "/tmp/80F96111-6E75-49A2-A187-0DA1B76FFA5F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 16:12:00.547 HelloWorld[1624:1739477] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/888294BD-4883-449C-89C9-F427A5C27D69/Library/Cookies/Cookies.binarycookies
,2015-11-06 16:12:00.920 HelloWorld[1624:1739477] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 16:12:00.921 HelloWorld[1624:1739477] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:12:00.925 HelloWorld[1624:1739477] Unlimited access to network resources
,2015-11-06 16:12:00.932 HelloWorld[1624:1739477] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:12:04.848 HelloWorld[1624:1739477] Resetting plugins due to page load.
,2015-11-06 16:12:05.237 HelloWorld[1624:1739477] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/770B190A-1630-402F-AFD5-54E80077A7B7/HelloWorld.app/www/index.html
,2015-11-06 16:12:05.352 HelloWorld[1624:1739477] JXcore Cordova plugin initializing
,2015-11-06 16:12:05.354 HelloWorld[1624:1739595] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 130207744
execPath /private/var/mobile/Containers/Bundle/Application/770B190A-1630-402F-AFD5-54E80077A7B7/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/77,0B190A-1630-402F-AFD5-54E80077A7B7/HelloWorld.app/www/jxcore/
userPath []
2015-11-06 16:12:05.620 HelloWorld[1624:1739595] Native method ScreenInfo not found.
2015-11-06 16:12:05.621 HelloWorld[1624:1739595] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5118  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F6ADCA25-6A2C-41E6-B6A2-CEE13E362B9F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F6ADCA25-6A2C-41E6-B6A2-CEE13E362B9F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/B69CB553-62F4-4CC9-9FF0-A38EB6DB093C/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64783"
,(lldb)     command script import "/tmp/F6ADCA25-6A2C-41E6-B6A2-CEE13E362B9F/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 16:12:46.293 HelloWorld[1322:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-06 16:12:46.296 HelloWorld[1322:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:12:46.302 HelloWorld[1322:60b] Unlimited access to network resources
,2015-11-06 16:12:46.309 HelloWorld[1322:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:12:56.703 HelloWorld[1322:60b] Resetting plugins due to page load.
,2015-11-06 16:12:57.495 HelloWorld[1322:60b] Finished load of: file:///var/mobile/Applications/B69CB553-62F4-4CC9-9FF0-A38EB6DB093C/HelloWorld.app/www/index.html
,2015-11-06 16:12:57.562 HelloWorld[1322:60b] JXcore Cordova plugin initializing
,2015-11-06 16:12:57.566 HelloWorld[1322:6607] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 494374912
execPath /private/var/mobile/Applications/B69CB553-62F4-4CC9-9FF0-A38EB6DB093C/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/B69CB553-62F4-4CC9-9FF0-A38EB6DB093C/HelloWorld.app/www/jxcore/
userPath []
,2015-11-06 16:12:58.016 HelloWorld[1322:6607] Native method ScreenInfo not found.
,2015-11-06 16:12:58.018 HelloWorld[1322:6607] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5230  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/829684BA-7C03-4C64-9658-6C3BFCDFF26E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/829684BA-7C03-4C64-9658-6C3BFCDFF26E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0FD7C7D2-FA69-4259-9DC4-77BC291745BA/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64778"
,(lldb)     command script import "/tmp/829684BA-7C03-4C64-9658-6C3BFCDFF26E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 16:12:00.388 HelloWorld[2621:2803498] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0822EB3C-D8FE-4D37-99B7-DF65DE58C93B/Library/Cookies/Cookies.binarycookies
,2015-11-06 16:12:00.800 HelloWorld[2621:2803498] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 16:12:00.801 HelloWorld[2621:2803498] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:12:00.806 HelloWorld[2621:2803498] Unlimited access to network resources
,2015-11-06 16:12:00.814 HelloWorld[2621:2803498] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:12:04.510 HelloWorld[2621:2803498] Resetting plugins due to page load.
,2015-11-06 16:12:04.742 HelloWorld[2621:2803498] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/0FD7C7D2-FA69-4259-9DC4-77BC291745BA/HelloWorld.app/www/index.html
,2015-11-06 16:12:04.816 HelloWorld[2621:2803498] JXcore Cordova plugin initializing
2015-11-06 16:12:04.818 HelloWorld[2621:2803622] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 98709504
execPath /private/var/mobile/Containers/Bundle/Application/0FD7C7D2-FA69-4259-9DC4-77BC291745BA/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/0FD7,C7D2-FA69-4259-9DC4-77BC291745BA/HelloWorld.app/www/jxcore/
userPath []
2015-11-06 16:12:05.056 HelloWorld[2621:2803622] Native method ScreenInfo not found.
2015-11-06 16:12:05.057 HelloWorld[2621:2803622] Native method ScreenBrightness not found.
Dumm,y Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5115  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3B6F33F7-808C-48B2-A41C-B25EFD2A64F0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3B6F33F7-808C-48B2-A41C-B25EFD2A64F0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/476722347fc8662/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E1AD2AAA-F888-4A64-B147-6CCBCF54F487/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64777"
,(lldb)     command script import "/tmp/3B6F33F7-808C-48B2-A41C-B25EFD2A64F0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 16:12:04.329 HelloWorld[1750:3651078] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41BD7B61-023E-4A9D-8D13-6299D52D738E/Library/Cookies/Cookies.binarycookies
,2015-11-06 16:12:04.748 HelloWorld[1750:3651078] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 16:12:04.750 HelloWorld[1750:3651078] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:12:04.754 HelloWorld[1750:3651078] Unlimited access to network resources
,2015-11-06 16:12:04.764 HelloWorld[1750:3651078] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:12:14.194 HelloWorld[1750:3651078] Resetting plugins due to page load.
,2015-11-06 16:12:17.803 HelloWorld[1750:3651078] Finished load of: file:///var/mobile/Containers/Bundle/Application/E1AD2AAA-F888-4A64-B147-6CCBCF54F487/HelloWorld.app/www/index.html
,2015-11-06 16:12:17.873 HelloWorld[1750:3651078] JXcore Cordova plugin initializing
,2015-11-06 16:12:17.874 HelloWorld[1750:3651281] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 321994752
,execPath /private/var/mobile/Containers/Bundle/Application/E1AD2AAA-F888-4A64-B147-6CCBCF54F487/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/E1AD2AAA-F888-4A64-B147-6CCBCF54F487/HelloWorld.app/www/jxcore/
userPath []
2015-11-06 16:12:18.061 HelloWorld[1750:3651281] Native method ScreenInfo not found.
2015-11-06 16:12:18.061 HelloWorld[1750:3651281] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5111  ms ****
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

