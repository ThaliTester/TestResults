#### Test 47672234907c1b8 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_47672234907c1b8/Sub/serverApp/index.js',
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
I/ActivityManager( 1210): rtcc_minfree = 82449,70671,58892,47114,35335
I/ActivityManager( 1210): Config changes=1df8 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h961dp 213dpi lrg port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
I/ActivityManager( 1210): Config changes=408 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port ?uimode ?night finger -keyb/v/h -nav/h s.3}
I/ActivityManager( 1210): System now ready
I/ActivityManager( 1210): Config changes=200 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port finger -keyb/v/h -nav/h s.4}
I/ActivityManager( 1210): !@ mBooting is set true!
I/ActivityManager( 1210): RTCC_TRIGGER_MSG, ASYNC.
W/ActivityManager( 1210): mDVFSHelper.release()
W/ActivityManager( 1210): Unable to start service Intent { cmp=com.samsung.android.app.gestureservice/.GestureService } U=0: not found
W/ActivityManager( 1210): !@call fb1: post finishBooting() with 1000msec delay
I/ActivityManager( 1210): !@Boot: bootcomplete
I/ActivityManager( 1210): Killing 2711:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 2764:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 1623:com.android.printspooler/u0a118 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 2666:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 2914:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 2931:com.samsung.android.app.memo/u0a130 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 2944:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3020:com.sec.phone/u0a127 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3079:com.google.android.configupdater/u0a2 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3102:com.sec.android.widgetapp.samsungapps/u0a120 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3155:com.sec.dsm.system/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3187:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3210:com.sec.factory/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3225:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3257:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 1496:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3274:com.android.onetimeinitializer/u0a21 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3289:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3317:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3333:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
W/ActivityManager( 1210): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1210): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1210): Killing 3347:com.osp.app.signin/u0a30 (adj 15): bgCount ##33
I/ActivityManager( 1210): Waited long enough for: ServiceRecord{4271bb38 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1210): Waited long enough for: ServiceRecord{427b16e0 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/ActivityManager( 1210): Waited long enough for: ServiceRecord{429183a0 u0 com.samsung.android.providers.context/.ContextService}
I/ActivityManager( 1210): Waited long enough for: ServiceRecord{428ebba8 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 1210): Waited long enough for: ServiceRecord{426ce8c8 u0 com.sec.esdk.elm/.service.ElmAgentService}
I/ActivityManager( 1210): Killing 2957:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 2588:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 1640:com.android.settings/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3382:com.wssyncmldm/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 2575:com.google.android.partnersetup/u0a11 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3409:com.google.android.googlequicksearchbox:search/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3443:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3430:com.samsung.android.intelligenceservice/u0a52 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3457:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3471:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3485:com.wssnps/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Process com.samsung.android.MtpApplication (pid 4159) (adj 0) has died.
I/ActivityManager( 1210): Killing 3498:com.samsung.android.app.accesscontrol/u0a57 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3515:com.sec.android.app.FileShareServer/u0a62 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3530:com.sec.android.nearby.mediaserver/u0a63 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3544:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3557:com.sec.android.app.bluetoothtest/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3570:com.blurb.checkout/u0a67 (adj 15): bgCount ##33
W/ActivityManager( 1210): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
W/ActivityManager( 1210): mDVFSHelper.acquire()
I/ActivityManager( 1210): Killing 3583:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3596:com.dropbox.android/u0a78 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3635:com.sec.factory.camera/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3649:com.samsung.android.app.watchmanagerstub/u0a86 (adj 15): bgCount ##33
W/ActivityManager( 1210): mDVFSHelper.release()
I/ActivityManager( 1210): Killing 3726:com.samsung.scrc.idi.server/u0a91 (adj 15): bgCount ##33
I/ActivityManager( 1210): Process com.sec.factory (pid 4146) (adj 0) has died.
I/ActivityManager( 1210): Process com.sec.android.app.sysscope (pid 3947) (adj 0) has died.
I/ActivityManager( 1210): Killing 3741:com.samsung.helphub/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3755:com.LocalFota/u0a92 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3771:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3798:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3823:com.sec.android.app.camera/u0a121 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 1756:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3885:com.android.exchange/u0a126 (adj 15): bgCount ##33
I/ActivityManager( 1210): Waited long enough for: ServiceRecord{428cee08 u0 com.rxnetworks.rxnservicesxybrid/com.rxnetworks.rxnserviceslib.RXNetworksService}
I/ActivityManager( 1210): Waited long enough for: ServiceRecord{427b42c8 u0 com.samsung.android.MtpApplication/.MtpService}
I/ActivityManager( 1210): Killing 3836:com.android.email/u0a125 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3912:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3932:com.sec.android.app.worldclock/u0a135 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3960:com.sec.android.app.controlpanel/u0a141 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3974:com.samsung.android.service.travel/u0a143 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3987:com.google.android.youtube/u0a146 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 4051:com.gameloft.android.gdc:remote/u0a152 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 4264:com.sec.spp.push:RemoteDlcProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 4280:com.sec.spp.push:RemoteNotiProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 4320:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 3694:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 4457:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
I/ActivityManager( 1210): Killing 4506:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
,--------- beginning of /dev/log/main
W/ActivityManager( 1210): mDVFSHelper.acquire()
W/ActivityManager( 1210): mDVFSHelper.release()
W/jxcore-log( 4885): Initializing JXcore engine
W/jxcore-log( 4885): JXcore engine is ready
,W/jxcore-log( 4885): Starting JXcore engine
W/jxcore-log( 4885): Platform android
W/jxcore-log( 4885): 
W/jxcore-log( 4885): Process ARCH arm
W/jxcore-log( 4885): 
I/jxcore-log( 4885): JXcore Cordova bridge is ready!
I/jxcore-log( 4885): 
W/jxcore-log( 4885): JXcore engine is started
E/jxcore-log( 4885): >> samsung-SM-T232
E/jxcore-log( 4885): 
I/jxcore-log( 4885): Total memory 1352024064
I/jxcore-log( 4885): 
I/jxcore-log( 4885): Free memory 207749120
I/jxcore-log( 4885): 
I/jxcore-log( 4885): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4885): 
I/jxcore-log( 4885): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4885): 
I/jxcore-log( 4885): userPath [ 'www' ]
I/jxcore-log( 4885): 
I/jxcore-log( 4885): Size 800 1280
I/jxcore-log( 4885): 
I/jxcore-log( 4885): Screen Brightness 143
I/jxcore-log( 4885): 
E/jxcore-log( 4885): Dummy Error Log.
E/jxcore-log( 4885): 
I/jxcore-log( 4885): getBuffer is called!!!!
I/jxcore-log( 4885): 
,I/jxcore-log( 4885): ****TEST TOOK:  5115  ms ****
I/jxcore-log( 4885): 
,I/jxcore-log( 4885): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4885): 
,I/ActivityManager( 1210): Killing 4885:com.example.hello/u0a357 (adj 0): stop com.example.hello


samsung-SM-G920F: 
--------- beginning of system
W/ActivityManager( 3489): mDVFSHelper.release()
,--------- beginning of main
I/ActivityManager( 3489): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3489): mDVFSHelper.acquire()
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3489): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9570 uid=10427 gids={50427, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 3489): Activity pause timeout for ActivityRecord{86a3292 u0 com.example.hello/.MainActivity t44}
,D/ActivityManager( 3489): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/ActivityManager( 3489): Displayed Component not be shown by security: +864ms
,W/ActivityManager( 3489): mDVFSHelper.release()
,W/jxcore-log( 9570): Initializing JXcore engine
W/jxcore-log( 9570): JXcore engine is ready
,W/jxcore-log( 9570): Starting JXcore engine
,W/jxcore-log( 9570): Platform android
W/jxcore-log( 9570): 
W/jxcore-log( 9570): Process ARCH arm
W/jxcore-log( 9570): 
,I/jxcore-log( 9570): JXcore Cordova bridge is ready!
I/jxcore-log( 9570): 
W/jxcore-log( 9570): JXcore engine is started
,E/jxcore-log( 9570): >> samsung-SM-G920F
E/jxcore-log( 9570): 
,I/jxcore-log( 9570): Total memory 2829074432
I/jxcore-log( 9570): 
I/jxcore-log( 9570): Free memory 64331776
I/jxcore-log( 9570): 
I/jxcore-log( 9570): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9570): 
I/jxcore-log( 9570): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9570): 
,I/jxcore-log( 9570): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9570): 
,I/jxcore-log( 9570): Size 1440 2560
I/jxcore-log( 9570): 
,I/jxcore-log( 9570): Screen Brightness 134
I/jxcore-log( 9570): 
E/jxcore-log( 9570): Dummy Error Log.
E/jxcore-log( 9570): 
,I/jxcore-log( 9570): getBuffer is called!!!!
I/jxcore-log( 9570): 
,I/jxcore-log( 9570): ****TEST TOOK:  5071  ms ****
I/jxcore-log( 9570): 
,I/jxcore-log( 9570): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9570): 
,I/ActivityManager( 3489): Force stopping com.example.hello appid=10427 user=-1: uninstall pkg
,I/ActivityManager( 3489): Killing 9570:com.example.hello/u0a427 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3489):   Force finishing activity ActivityRecord{86a3292 u0 com.example.hello/.MainActivity t44}
,I/ActivityManager( 3489): Force stopping com.example.hello appid=10427 user=0: pkg removed
,W/ActivityManager( 3489): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9686 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
,W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 3489): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5276, uid=10127 that is not exported from uid 10125
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
,W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,I/ActivityManager( 3489): Killing 9097:com.sec.pcw.device/1000 (adj 15): empty #25
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
,W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=9705 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=9720 uid=10054 gids={50054, 9997, 3003, 3002} abi=arm64-v8a
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=9729 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
,W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9753 uid=10102 gids={50102, 9997, 1028, 3003, 1015} abi=arm64-v8a
D/ActivityManager( 3489): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=9785 uid=10001 gids={50001, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=arm64-v8a
,D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3489): Killing 8584:com.samsung.android.app.galaxyfinder/u0a27 (adj 15): empty #25
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3489): Killing 9126:com.sec.spp.push/u0a33 (adj 15): empty #25
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.android.app.vepreload for broadcast com.sec.android.app.vepreload/.VEExtensionPackUpdateReceiver: pid=9802 uid=10170 gids={50170, 9997, 1028, 1015, 1003, 3003} abi=arm64-v8a
,D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9818 uid=10027 gids={50027, 9997, 1028, 1015, 3003, 3002} abi=arm64-v8a
,I/ActivityManager( 3489): Killing 9163:com.policydm/1000 (adj 15): empty #25
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
,W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.vodafone.smhs, destAppInfo.processName = com.vodafone.smhs
,I/ActivityManager( 3489): Killing 9181:com.sec.spp.push:RemoteNotiProcess/u0a33 (adj 15): empty #25
,I/ActivityManager( 3489): Killing 8600:com.google.android.apps.plus/u0a136 (adj 15): empty #25
,I/ActivityManager( 3489): Killing 8549:com.sec.android.app.shealth/u0a28 (adj 15): empty #25
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.SnippetsWidgetService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.DashboardsWidgetService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10993ms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9863 uid=10136 gids={50136, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3489): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3489): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=9869 uid=10033 gids={50033, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 3489): Process com.google.android.gms (pid 4559)(adj 0) has died(208,1003)
,W/ActivityManager( 3489): Exception when unbinding service com.google.android.gms/.icing.service.LightweightIndexService
W/ActivityManager( 3489): android.os.TransactionTooLargeException
W/ActivityManager( 3489): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3489): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3489): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 3489): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1904)
W/ActivityManager( 3489): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2288)
W/ActivityManager( 3489): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18330)
W/ActivityManager( 3489): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6504)
W/ActivityManager( 3489): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6710)
W/ActivityManager( 3489): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1596)
W/ActivityManager( 3489): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20917ms
W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30917ms
W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 40917ms
W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 40917ms
,W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 40917ms
W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 50917ms
,W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.cast.media.CastMediaRouteProviderService in 50916ms
W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 60916ms
,D/ActivityManager( 3489): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3489): userId = 0, bbcId = -10000
W/ActivityManager( 3489): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3489): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/ActivityManager( 3489): Process com.google.process.gapps (pid 4309)(adj 1) has died(208,1003)
,W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 60897ms
W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 70897ms
W/ActivityManager( 3489): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService$LightweightWorkerService in 80897ms


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1277): Start proc 8983:com.google.android.googlequicksearchbox:search/u0a63 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
I/ActivityManager( 1277): Start proc 9011:com.google.android.partnersetup/u0a5 for content provider com.google.android.partnersetup/.RlzAppProvider
I/ActivityManager( 1277): Start proc 9033:com.lge.appbox.client/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper
I/ActivityManager( 1277): Killing 8233:com.android.settings/1000 (adj 15): empty #22
I/ActivityManager( 1277): Killing 8582:com.lge.eodengine/1000 (adj 15): empty #22
I/ActivityManager( 1277): Start proc 9059:com.android.contacts/u0a18 for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver
I/ActivityManager( 1277): Start proc 9082:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.PackageIntentReceiver
I/ActivityManager( 1277): Killing 8448:com.uei.lg.quicksetsdk.irblaster/1000 (adj 15): empty #22
,W/ActivityManager( 1277): Scheduling restart of crashed service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service in 1000ms
I/ActivityManager( 1277): Killing 8561:com.lge.sync/1000 (adj 15): empty #22
I/ActivityManager( 1277): Start proc 9107:com.android.vending/u0a62 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
I/ActivityManager( 1277): Killing 8424:com.lge.qremote/u0a138 (adj 15): empty #22
I/ActivityManager( 1277): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1277): setTaskToReturnTo : TaskRecord{26a0fc43 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1277): setTaskToReturnTo : TaskRecord{26a0fc43 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1277): Start proc 9160:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1277): Start proc 9202:com.google.android.apps.plus/u0a122 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager( 1277): Killing 8681:com.lge.cic.eden.service/u0a7 (adj 15): empty #22
,I/ActivityManager( 1277): Displayed com.example.hello/.MainActivity: +491ms (total +32s184ms)
I/ActivityManager( 1277): Killing 8701:com.lge.clock/u0a16 (adj 15): empty #22
W/jxcore-log( 9160): Initializing JXcore engine
W/jxcore-log( 9160): JXcore engine is ready
W/jxcore-log( 9160): Starting JXcore engine
I/ActivityManager( 1277): Start proc 9257:com.lge.exchange/u0a22 for broadcast com.lge.exchange/.receiver.PackageChangeReceiver
I/ActivityManager( 1277): Killing 8627:com.google.android.music:main/u0a123 (adj 15): empty #22
W/jxcore-log( 9160): Platform android
W/jxcore-log( 9160): 
W/jxcore-log( 9160): Process ARCH arm
W/jxcore-log( 9160): 
I/jxcore-log( 9160): JXcore Cordova bridge is ready!
I/jxcore-log( 9160): 
W/jxcore-log( 9160): JXcore engine is started
E/jxcore-log( 9160): >> LGE-LG-H815
E/jxcore-log( 9160): 
I/jxcore-log( 9160): Total memory 2968948736
I/jxcore-log( 9160): 
I/jxcore-log( 9160): Free memory 64462848
I/jxcore-log( 9160): 
I/jxcore-log( 9160): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9160): 
I/jxcore-log( 9160): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9160): 
I/jxcore-log( 9160): userPath [ 'www' ]
I/jxcore-log( 9160): 
I/jxcore-log( 9160): Size 1440 2392
I/jxcore-log( 9160): 
I/jxcore-log( 9160): Screen Brightness 255
I/jxcore-log( 9160): 
E/jxcore-log( 9160): Dummy Error Log.
E/jxcore-log( 9160): 
W/ActivityManager( 1277): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
I/ActivityManager( 1277): Start proc 9278:com.lge.email/u0a56 for content provider com.lge.email/.providers.EmailProvider
I/ActivityManager( 1277): Killing 8774:com.lge.myplace/u0a30 (adj 15): empty #22
I/ActivityManager( 1277): Killing 8753:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #23
I/jxcore-log( 9160): getBuffer is called!!!!
I/jxcore-log( 9160): 
,I/ActivityManager( 1277): Start proc 9303:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
W/ActivityManager( 1277): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1277): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1277): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1277): Start proc 9331:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
W/ActivityManager( 1277): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1277): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1277): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1277): Killing 8808:com.google.android.setupwizard/u0a54 (adj 15): empty #22
I/ActivityManager( 1277): Start proc 9351:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver
I/ActivityManager( 1277): Killing 8864:com.google.android.gm/u0a113 (adj 15): empty #22
I/ActivityManager( 1277): Start proc 9380:com.google.android.apps.docs/u0a118 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,W/ActivityManager( 1277): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1277): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1277): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1277): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1277): Start proc 9422:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
,I/ActivityManager( 1277): Killing 8658:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1277): Killing 8934:com.lge.lgaccount/u0a107 (adj 15): empty #22
,I/ActivityManager( 1277): Start proc 9446:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,W/ActivityManager( 1277): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1277): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1277): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1277): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1277): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1277): Start proc 9485:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/ActivityManager( 1277): Killing 8913:com.lge.lifetracker/u0a137 (adj 15): empty #22
,I/ActivityManager( 1277): Killing 8294:com.android.defcontainer/u0a3 (adj 15): empty #22
,W/ActivityManager( 1277): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1277): Killing 8957:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
,W/ActivityManager( 1277): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9160): ****TEST TOOK:  5035  ms ****
I/jxcore-log( 9160): 
,I/jxcore-log( 9160): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9160): 
,I/ActivityManager( 1277): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
I/ActivityManager( 1277): Killing 9160:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1277): Force removing ActivityRecord{1e3a02c0 u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1277): Force stopping com.example.hello appid=10360 user=0: pkg removed
,W/ActivityManager( 1277): Spurious death for ProcessRecord{10b3fdc4 9160:com.example.hello/u0a360}, curProc for 9160: null
,I/ActivityManager( 1277): Start proc 9557:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1277): Start proc 9582:com.android.settings/1000 for broadcast com.android.settings/.hotkey.PackageIntentReceiver
,I/ActivityManager( 1277): Displayed com.lge.launcher2/.Launcher: +338ms (total +37s926ms)
,I/ActivityManager( 1277): Killing 9011:com.google.android.partnersetup/u0a5 (adj 15): empty #22


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2933): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2933): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/ActivityManager( 2933): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2933): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/ActivityManager( 2933): Displayed com.example.hello/.MainActivity: +2s269ms
,W/jxcore-log( 6329): Initializing JXcore engine
W/jxcore-log( 6329): JXcore engine is ready
,W/jxcore-log( 6329): Starting JXcore engine
,W/jxcore-log( 6329): Platform android
W/jxcore-log( 6329): 
,W/jxcore-log( 6329): Process ARCH arm
W/jxcore-log( 6329): 
,I/jxcore-log( 6329): JXcore Cordova bridge is ready!
I/jxcore-log( 6329): 
,W/jxcore-log( 6329): JXcore engine is started
,E/jxcore-log( 6329): >> HUAWEI-ALE-L21
E/jxcore-log( 6329): 
,I/jxcore-log( 6329): Total memory 1949741056
I/jxcore-log( 6329): 
,I/jxcore-log( 6329): Free memory 18751488
I/jxcore-log( 6329): 
I/jxcore-log( 6329): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6329): 
I/jxcore-log( 6329): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6329): 
,I/jxcore-log( 6329): userPath [ 'www' ]
I/jxcore-log( 6329): 
I/jxcore-log( 6329): Size 720 1184
I/jxcore-log( 6329): 
I/jxcore-log( 6329): Screen Brightness 242
I/jxcore-log( 6329): 
E/jxcore-log( 6329): Dummy Error Log.
E/jxcore-log( 6329): 
,I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/jxcore-log( 6329): getBuffer is called!!!!
I/jxcore-log( 6329): 
,I/ActivityManager( 2933): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2933): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
,I/jxcore-log( 6329): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 6329): 
,I/jxcore-log( 6329): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6329): 
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PACKAGE_CHANGED


```

####Node name: thali02
Console output:
```
STOP log received from  FA533YJ03104 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Device test finished on FA533YJ03104 
Android task is completed 
```

Logcat output:
```
LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  863): Killing 5004:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/ActivityManager(  863): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  863): setTaskToReturnTo : TaskRecord{12556fcc #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  863): setTaskToReturnTo : TaskRecord{12556fcc #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  863): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5236 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  863): Displayed com.example.hello/.MainActivity: +1s111ms
,I/ActivityManager(  863): Killing 5049:com.google.android.talk/u0a61 (adj 15): empty #11
,W/jxcore-log( 5236): Initializing JXcore engine
W/jxcore-log( 5236): JXcore engine is ready
W/jxcore-log( 5236): Starting JXcore engine
W/jxcore-log( 5236): Platform android
W/jxcore-log( 5236): 
W/jxcore-log( 5236): Process ARCH arm
W/jxcore-log( 5236): 
I/jxcore-log( 5236): JXcore Cordova bridge is ready!
I/jxcore-log( 5236): 
W/jxcore-log( 5236): JXcore engine is started
,E/jxcore-log( 5236): >> LGE-LG-D722
E/jxcore-log( 5236): 
,I/jxcore-log( 5236): Total memory 906309632
I/jxcore-log( 5236): 
I/jxcore-log( 5236): Free memory 21299200
I/jxcore-log( 5236): 
I/jxcore-log( 5236): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5236): 
I/jxcore-log( 5236): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5236): 
I/jxcore-log( 5236): userPath [ 'www' ]
I/jxcore-log( 5236): 
I/jxcore-log( 5236): Size 720 1196
I/jxcore-log( 5236): 
I/jxcore-log( 5236): Screen Brightness 255
I/jxcore-log( 5236): 
,E/jxcore-log( 5236): Dummy Error Log.
E/jxcore-log( 5236): 
,I/ActivityManager(  863): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5350 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 5236): getBuffer is called!!!!
I/jxcore-log( 5236): 
,I/ActivityManager(  863): Killing 3554:com.android.calendar/u0a13 (adj 15): empty #11
,I/ActivityManager(  863): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5394 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 5087:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/jxcore-log( 5236): ****TEST TOOK:  5077  ms ****
I/jxcore-log( 5236): 
I/jxcore-log( 5236): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5236): 
,I/ActivityManager(  863): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  863): Killing 5236:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  863): Force removing ActivityRecord{1a38f215 u0 com.example.hello/.MainActivity t217}: app died, no saved state
,W/ActivityManager(  863): Spurious death for ProcessRecord{9a08092 5236:com.example.hello/u0a30}, curProc for 5236: null
,I/ActivityManager(  863): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  863): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5476 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5511 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 5108:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/ActivityManager(  863): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=5531 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a


LGE-Nexus 5: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2803 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,V/ActivityManager(  761): Display changed displayId=0
,I/ActivityManager(  761): Displayed com.example.hello/.MainActivity: +564ms (total +38s931ms)
,W/jxcore-log( 2803): Initializing JXcore engine
W/jxcore-log( 2803): JXcore engine is ready
,W/jxcore-log( 2803): Starting JXcore engine
,W/jxcore-log( 2803): Platform android
W/jxcore-log( 2803): 
W/jxcore-log( 2803): Process ARCH arm
W/jxcore-log( 2803): 
,I/jxcore-log( 2803): JXcore Cordova bridge is ready!
I/jxcore-log( 2803): 
,W/jxcore-log( 2803): JXcore engine is started
,E/jxcore-log( 2803): >> LGE-Nexus 5
E/jxcore-log( 2803): 
I/jxcore-log( 2803): Total memory 1946181632
I/jxcore-log( 2803): 
I/jxcore-log( 2803): Free memory 331268096
I/jxcore-log( 2803): 
I/jxcore-log( 2803): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2803): 
I/jxcore-log( 2803): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2803): 
,I/jxcore-log( 2803): userPath [ 'www' ]
I/jxcore-log( 2803): 
,I/jxcore-log( 2803): Size 1080 1776
I/jxcore-log( 2803): 
,I/jxcore-log( 2803): Screen Brightness 82
I/jxcore-log( 2803): 
,E/jxcore-log( 2803): Dummy Error Log.
E/jxcore-log( 2803): 
,I/ActivityManager(  761): Killing 2101:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/jxcore-log( 2803): getBuffer is called!!!!
I/jxcore-log( 2803): 
,I/ActivityManager(  761): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=2891 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2137:com.google.android.youtube/u0a80 (adj 15): empty #17
,I/jxcore-log( 2803): ****TEST TOOK:  5026  ms ****
I/jxcore-log( 2803): 
I/jxcore-log( 2803): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2803): 
,I/ActivityManager(  761): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 2803:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{329c156a u0 com.example.hello/.MainActivity t214}
,V/ActivityManager(  761): Display changed displayId=0
,W/ActivityManager(  761): Spurious death for ProcessRecord{d614fc7 2803:com.example.hello/u0a277}, curProc for 2803: null
I/ActivityManager(  761): Force stopping com.example.hello appid=10277 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{329c156a u0 com.example.hello/.MainActivity t214 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{329c156a u0 com.example.hello/.MainActivity t214 f}
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2994 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2233:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3026 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3054 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 1768:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/ActivityManager(  761): Killing 2429:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17


HTC-HTC One M9: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1070): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4530 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager( 1070): Killing 3873:com.htc.android.worldclock/u0a75 (adj 15): empty #17
I/ActivityManager( 1070): Recipient 3873
I/ActivityManager( 1070): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4573 uid=10139 gids={50139, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager( 1070): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4602 uid=10061 gids={50061, 9997} abi=arm64-v8a
I/ActivityManager( 1070): Killing 3895:com.google.android.configupdater/u0a87 (adj 15): empty #17
I/ActivityManager( 1070): Recipient 3895
,I/ActivityManager( 1070): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4624 uid=10003 gids={50003, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
I/ActivityManager( 1070): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4671 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
I/ActivityManager( 1070): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4646 on display 0
I/ActivityManager( 1070): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4694 uid=10193 gids={50193, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1070): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4717 uid=10036 gids={50036, 9997, 3003, 1028, 3002, 3001} abi=arm64-v8a
I/ActivityManager( 1070): Killing 3957:com.google.android.gm/u0a95 (adj 15): empty #17
I/ActivityManager( 1070): Recipient 3957
I/ActivityManager( 1070): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4741 uid=1000 gids={41000, 9997, 1028, 3003, 3002, 3001, 1015, 5001, 5011, 3006, 1007, 1023} abi=arm64-v8a
,I/ActivityManager( 1070): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4764 uid=10024 gids={50024, 9997, 1028, 1015, 3003, 1023, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1070): Killing 3726:com.htc.sense.mms/u0a54 (adj 15): empty #17,
,I/ActivityManager( 1070): Recipient 3726
,I/ActivityManager( 1070): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4810 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager( 1070): Displayed com.example.hello/.MainActivity: +855ms
,W/jxcore-log( 4694): Initializing JXcore engine
W/jxcore-log( 4694): JXcore engine is ready
W/jxcore-log( 4694): Starting JXcore engine
I/ActivityManager( 1070): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4853 uid=10012 gids={50012, 9997, 3003, 1028, 1015, 1023} abi=arm64-v8a
I/ActivityManager( 1070): Killing 4063:com.google.android.talk/u0a102 (adj 15): empty #17
W/jxcore-log( 4694): Platform android
W/jxcore-log( 4694): 
W/jxcore-log( 4694): Process ARCH arm
W/jxcore-log( 4694): 
I/jxcore-log( 4694): JXcore Cordova bridge is ready!
I/jxcore-log( 4694): 
W/jxcore-log( 4694): JXcore engine is started
I/ActivityManager( 1070): Recipient 4063
E/jxcore-log( 4694): >> HTC-HTC One M9
E/jxcore-log( 4694): 
I/jxcore-log( 4694): Total memory 2860257280
I/jxcore-log( 4694): 
I/jxcore-log( 4694): Free memory 181559296
I/jxcore-log( 4694): 
I/jxcore-log( 4694): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4694): 
I/jxcore-log( 4694): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4694): 
I/jxcore-log( 4694): userPath [ 'www' ]
I/jxcore-log( 4694): 
I/jxcore-log( 4694): Size 1080 1776
I/jxcore-log( 4694): 
I/jxcore-log( 4694): Screen Brightness 142
I/jxcore-log( 4694): 
E/jxcore-log( 4694): Dummy Error Log.
E/jxcore-log( 4694): 
I/ActivityManager( 1070): Killing 4109:com.htc.cs.pns:boot_complete/u0a119 (adj 15): empty #17
I/ActivityManager( 1070): Recipient 4109
I/ActivityManager( 1070): Start proc com.htc.music:musicenhancer for broadcast com.htc.music/com.htc.musicenhancer.provider.MScannerReceiver: pid=4878 uid=10025 gids={50025, 9997, 1028, 1015, 3003, 3002, 1023} abi=armeabi-v7a
I/ActivityManager( 1070): Killing 4136:com.htc.cs.pns/u0a119 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4136
,I/jxcore-log( 4694): getBuffer is called!!!!
I/jxcore-log( 4694): 
,I/ActivityManager( 1070): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4903 uid=10064 gids={50064, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager( 1070): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4929 uid=10068 gids={50068, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/ActivityManager( 1070): Killing 3934:com.htc.cs.dm/u0a88 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 3934,
,I/ActivityManager( 1070): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast,
,I/ActivityManager( 1070): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4962 uid=10095 gids={50095, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 1070): Killing 4157:tv.peel.app/u0a123 (adj 15): empty #17,
,I/ActivityManager( 1070): Recipient 4157,
,W/ActivityManager( 1070): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
W/ActivityManager( 1070): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1070): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1070): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1070): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1070): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager( 1070): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/ActivityManager( 1070): Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5007 uid=10008 gids={50008, 9997, 1028, 1015, 5001, 5011, 3003} abi=arm64-v8a
,I/ActivityManager( 1070): Killing 4282:com.android.smith/1000 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4282,
,I/ActivityManager( 1070): Start proc com.htc.autobot for broadcast com.htc.autobot/.AlarmReceiver: pid=5038 uid=10027 gids={50027, 9997, 3003, 3002, 3001, 1024, 5003} abi=arm64-v8a,
,I/ActivityManager( 1070): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast,
,I/ActivityManager( 1070): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5070 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1070): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5101 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,I/ActivityManager( 1070): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager( 1070): Killing 4302:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4302
,I/ActivityManager( 1070): Resuming delayed broadcast,
,I/ActivityManager( 1070): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Killing 4327:com.htc.usage/1000 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4327
,I/ActivityManager( 1070): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver,
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast,
,I/ActivityManager( 1070): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver,
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5140 uid=10023 gids={50023, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager( 1070): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
I/ActivityManager( 1070): Killing 4351:com.htc.WifiRouter/u0a134 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4351,
,I/ActivityManager( 1070): Delay finish: com.htc.launcher/.receiver.PackageStateReceiver,
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Killing 4413:com.htc.themepicker/u0a59 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4413,
,I/ActivityManager( 1070): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5167 uid=10088 gids={50088, 9997, 3003} abi=arm64-v8a
,I/ActivityManager( 1070): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
,I/ActivityManager( 1070): Killing 4530:com.android.vending/u0a57 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4530
,I/ActivityManager( 1070): Resuming delayed broadcast,
,I/ActivityManager( 1070): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5191 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1070): Killing 4033:com.htc.backup/u0a98 (adj 15): empty #17,
,I/ActivityManager( 1070): Recipient 4033
,I/ActivityManager( 1070): Killing 4602:com.htc.mms.backupagent/u0a61 (adj 15): empty #17
,I/jxcore-log( 4694): ****TEST TOOK:  5041  ms ****
I/jxcore-log( 4694): 
I/jxcore-log( 4694): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4694): 
,I/ActivityManager( 1070): Recipient 4602
,I/ActivityManager( 1070): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=5253 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 1070): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5278 uid=10126 gids={50126, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1070): Killing 4236:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4236,
,I/ActivityManager( 1070): Killing 4671:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4671
,I/ActivityManager( 1070): Force stopping com.example.hello appid=10193 user=-1: uninstall pkg
I/ActivityManager( 1070): Killing 4694:com.example.hello/u0a193 (adj 0): stop com.example.hello
,I/ActivityManager( 1070): Recipient 4694
,W/ActivityManager( 1070): Force removing ActivityRecord{5693a63 u0 com.example.hello/.MainActivity t67}: app died, no saved state,
,W/ActivityManager( 1070): Spurious death for ProcessRecord{29135e66 4694:com.example.hello/u0a193}, curProc for 4694: null
,I/ActivityManager( 1070): Force stopping com.example.hello appid=10193 user=0: pkg removed
,I/ActivityManager( 1070): Waited long enough for: ServiceRecord{2915e6c6 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager( 1070): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,I/ActivityManager( 1070): Resuming delayed broadcast
,I/ActivityManager( 1070): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5341 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/ActivityManager( 1070): App crashed! Process: com.android.vending
,I/ActivityManager( 1070): Killing 4717:com.htc.widget.hmsproc2/u0a36 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4717
,I/ActivityManager( 1070): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5400 uid=10062 gids={50062, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager( 1070): Killing 4741:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager( 1070): Recipient 4741,
,E/ActivityManager( 1070): App crashed! Process: com.google.process.gapps,
,I/ActivityManager( 1070): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5427 uid=10039 gids={50039, 9997, 3003, 1028} abi=arm64-v8a,


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
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
W/ActivityManager( 2420): mDVFSHelper.acquire()
,W/ActivityManager( 2420): mDVFSHelper.release()
,W/jxcore-log( 6700): Initializing JXcore engine
,W/jxcore-log( 6700): JXcore engine is ready
,W/jxcore-log( 6700): Starting JXcore engine
,W/jxcore-log( 6700): Platform android
W/jxcore-log( 6700): 
,W/jxcore-log( 6700): Process ARCH arm
W/jxcore-log( 6700): 
,I/jxcore-log( 6700): JXcore Cordova bridge is ready!
I/jxcore-log( 6700): 
,W/jxcore-log( 6700): JXcore engine is started
,E/jxcore-log( 6700): >> samsung-SM-G800F
E/jxcore-log( 6700): 
,I/jxcore-log( 6700): Total memory 1319530496
I/jxcore-log( 6700): 
I/jxcore-log( 6700): Free memory 35368960
I/jxcore-log( 6700): 
I/jxcore-log( 6700): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6700): 
,I/jxcore-log( 6700): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6700): 
,I/jxcore-log( 6700): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6700): 
,I/jxcore-log( 6700): Size 720 1280
I/jxcore-log( 6700): 
,I/jxcore-log( 6700): Screen Brightness 134
I/jxcore-log( 6700): 
,E/jxcore-log( 6700): Dummy Error Log.
E/jxcore-log( 6700): 
,I/jxcore-log( 6700): getBuffer is called!!!!
I/jxcore-log( 6700): 
,I/jxcore-log( 6700): ****TEST TOOK:  5102  ms ****,
I/jxcore-log( 6700): 
,I/jxcore-log( 6700): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 6700): 
,I/ActivityManager( 2420): Killing 6700:com.example.hello/u0a390 (adj 0): stop com.example.hello
,I/ActivityManager( 2420): Killing 5596:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/ActivityManager( 2420): Killing 5308:com.google.android.talk/u0a109 (adj 15): empty #43
,I/ActivityManager( 2420): Process com.google.android.googlequicksearchbox:search (pid 5907) (adj 5) has died.
,I/ActivityManager( 2420): Process com.samsung.android.magazine.service (pid 6314) (adj 5) has died.
,I/ActivityManager( 2420): Process com.android.keychain (pid 6837) (adj 5) has died.
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 2855) (adj 1) has died.
,I/ActivityManager( 2420): Process com.google.android.gms (pid 3144) (adj 0) has died.
,I/ActivityManager( 2420): Killing 5748:com.android.calendar/u0a144 (adj 15): empty #43
,I/ActivityManager( 2420): Process com.android.documentsui (pid 6861) (adj 9) has died.
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 6918) (adj 0) has died.
,W/ActivityManager( 2420): Service crashed 2 times, stopping: ServiceRecord{434a6838 u0 com.google.android.gms/.gcm.GcmService}
,W/ActivityManager( 2420): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2420): Killing 6940:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 6956) (adj 0) has died.
,W/ActivityManager( 2420): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2420): Killing 6971:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 6986) (adj 0) has died.
,W/ActivityManager( 2420): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2420): Killing 7001:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2420): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,I/ActivityManager( 2420): Killing 5793:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/ActivityManager( 2420): Process com.google.process.gapps (pid 7025) (adj 0) has died.


motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager( 1023): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3425
I/ActivityManager( 1023): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3441 uid=10321 gids={50321, 3003, 3001, 3002}
,I/ActivityManager( 1023): Displayed com.example.hello/.MainActivity: +324ms (total +349ms)
,W/jxcore-log( 3441): Initializing JXcore engine
,W/jxcore-log( 3441): JXcore engine is ready
,W/jxcore-log( 3441): Starting JXcore engine
,W/jxcore-log( 3441): Platform android
W/jxcore-log( 3441): 
,W/jxcore-log( 3441): Process ARCH arm
W/jxcore-log( 3441): 
,I/jxcore-log( 3441): JXcore Cordova bridge is ready!
I/jxcore-log( 3441): 
,W/jxcore-log( 3441): JXcore engine is started
,E/jxcore-log( 3441): >> motorola-XT1039
E/jxcore-log( 3441): 
,I/jxcore-log( 3441): Total memory 893136896
I/jxcore-log( 3441): 
I/jxcore-log( 3441): Free memory 33021952
I/jxcore-log( 3441): 
,I/jxcore-log( 3441): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3441): 
,I/jxcore-log( 3441): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3441): 
,I/jxcore-log( 3441): userPath [ 'www' ]
I/jxcore-log( 3441): 
,I/jxcore-log( 3441): Size 720 1184
I/jxcore-log( 3441): 
,I/jxcore-log( 3441): Screen Brightness 10
I/jxcore-log( 3441): 
,E/jxcore-log( 3441): Dummy Error Log.
E/jxcore-log( 3441): 
,I/jxcore-log( 3441): getBuffer is called!!!!
I/jxcore-log( 3441): 
,I/jxcore-log( 3441): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 3441): 
I/jxcore-log( 3441): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3441): 
,I/ActivityManager( 1023): Force stopping com.example.hello appid=10321 user=-1: uninstall pkg
,I/ActivityManager( 1023): Killing 3441:com.example.hello/u0a321 (adj 0): stop com.example.hello
,I/ActivityManager( 1023):   Force finishing activity ActivityRecord{42176160 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1023): Force stopping com.example.hello appid=10321 user=0: pkg removed
I/ActivityManager( 1023):   Force finishing activity ActivityRecord{42176160 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1023): Duplicate finish request for ActivityRecord{42176160 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1023): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3545 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1023): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3563 uid=10058 gids={50058}
,I/ActivityManager( 1023): Killing 3211:com.android.providers.calendar/u0a8 (adj 15): empty #9
,I/ActivityManager( 1023): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3585 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1023): Killing 3327:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1023): Killing 3297:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1023): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3601 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1023): Killing 3100:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{3ef156d7 #8 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{3ef156d7 #8 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1029): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6024 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1029): Display changed displayId=0
,I/ActivityManager( 1029): Killing 4889:com.lge.bnr/1000 (adj 15): empty #17
,W/ActivityManager( 1029): Activity pause timeout for ActivityRecord{1681abc4 u0 com.example.hello/.MainActivity t8}
,I/ActivityManager( 1029): Displayed com.example.hello/.MainActivity: +629ms (total +736ms)
,W/jxcore-log( 6024): Initializing JXcore engine
,W/jxcore-log( 6024): JXcore engine is ready
,W/jxcore-log( 6024): Starting JXcore engine
,W/jxcore-log( 6024): Platform android
W/jxcore-log( 6024): 
,W/jxcore-log( 6024): Process ARCH arm
W/jxcore-log( 6024): 
,I/jxcore-log( 6024): JXcore Cordova bridge is ready!
I/jxcore-log( 6024): 
W/jxcore-log( 6024): JXcore engine is started
,E/jxcore-log( 6024): >> LGE-LG-D855
E/jxcore-log( 6024): 
,I/jxcore-log( 6024): Total memory 2995761152
I/jxcore-log( 6024): 
I/jxcore-log( 6024): Free memory 634949632
I/jxcore-log( 6024): 
I/jxcore-log( 6024): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6024): 
I/jxcore-log( 6024): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6024): 
I/jxcore-log( 6024): userPath [ 'www' ]
I/jxcore-log( 6024): 
,I/jxcore-log( 6024): Size 1440 2392
I/jxcore-log( 6024): 
I/jxcore-log( 6024): Screen Brightness 50
I/jxcore-log( 6024): 
E/jxcore-log( 6024): Dummy Error Log.
E/jxcore-log( 6024): 
,I/jxcore-log( 6024): getBuffer is called!!!!
I/jxcore-log( 6024): 
,I/jxcore-log( 6024): ****TEST TOOK:  5072  ms ****
I/jxcore-log( 6024): 
I/jxcore-log( 6024): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6024): 
,I/ActivityManager( 1029): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1029): Killing 6024:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1029):   Force finishing activity ActivityRecord{1681abc4 u0 com.example.hello/.MainActivity t8}
,W/ActivityManager( 1029): Spurious death for ProcessRecord{26265c24 6024:com.example.hello/u0a318}, curProc for 6024: null
I/ActivityManager( 1029): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{1681abc4 u0 com.example.hello/.MainActivity t8 f}
W/ActivityManager( 1029): Duplicate finish request for ActivityRecord{1681abc4 u0 com.example.hello/.MainActivity t8 f}
,I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6130 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 5696:com.google.android.gms:car/u0a5 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6157 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6181 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 5590:com.google.android.apps.plus/u0a97 (adj 15): empty #17


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
,V/ActivityManager(  757): Display changed displayId=0
V/ActivityManager(  757): Display changed displayId=0
D/ActivityManager(  757): handle home activity for 0
D/ActivityManager(  757): post active user change for 0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  757): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6111 uid=10109 gids={50109, 9997} abi=armeabi-v7a
I/ActivityManager(  757): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  757): mDVFSHelper.acquire()
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  757): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6130 uid=10409 gids={50409, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager(  757): Display changed displayId=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  757): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6147 uid=10115 gids={50115, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  757): Activity reported stop, but no longer stopping: ActivityRecord{4ecfe5f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1}
I/ActivityManager(  757): Killing 5215:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
D/ActivityManager(  757): post active user change for 0
I/ActivityManager(  757): Displayed com.example.hello/.MainActivity: +631ms
W/ActivityManager(  757): mDVFSHelper.release()
W/jxcore-log( 6130): Initializing JXcore engine
W/jxcore-log( 6130): JXcore engine is ready
W/jxcore-log( 6130): Starting JXcore engine
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  757): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6205 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 6130): Platform android
W/jxcore-log( 6130): 
W/jxcore-log( 6130): Process ARCH arm
W/jxcore-log( 6130): 
I/jxcore-log( 6130): JXcore Cordova bridge is ready!
I/jxcore-log( 6130): 
W/jxcore-log( 6130): JXcore engine is started
I/ActivityManager(  757): Killing 5022:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
E/jxcore-log( 6130): >> samsung-SM-N9005
E/jxcore-log( 6130): 
I/jxcore-log( 6130): Total memory 2971471872
I/jxcore-log( 6130): 
I/jxcore-log( 6130): Free memory 435068928
I/jxcore-log( 6130): 
I/jxcore-log( 6130): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6130): 
I/jxcore-log( 6130): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6130): 
I/jxcore-log( 6130): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6130): 
I/jxcore-log( 6130): Size 1080 1920
I/jxcore-log( 6130): 
I/jxcore-log( 6130): Screen Brightness 162
I/jxcore-log( 6130): 
E/jxcore-log( 6130): Dummy Error Log.
E/jxcore-log( 6130): 
,I/jxcore-log( 6130): getBuffer is called!!!!
I/jxcore-log( 6130): 
,I/ActivityManager(  757): Killing 4323:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/jxcore-log( 6130): ****TEST TOOK:  5069  ms ****
I/jxcore-log( 6130): 
,I/jxcore-log( 6130): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6130): 
,I/ActivityManager(  757): Force stopping com.example.hello appid=10409 user=-1: uninstall pkg
,I/ActivityManager(  757): Killing 6130:com.example.hello/u0a409 (adj 0): stop com.example.hello
,W/ActivityManager(  757): Force removing ActivityRecord{27798412 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  757): mDVFSHelper.acquire()
,W/ActivityManager(  757): Spurious death for ProcessRecord{3c0f9504 6130:com.example.hello/u0a409}, curProc for 6130: null
I/ActivityManager(  757): Force stopping com.example.hello appid=10409 user=0: pkg removed
,D/ActivityManager(  757): handle home activity for 0
D/ActivityManager(  757): post active user change for 0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  757): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6271 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  757): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6293 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 5059:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,W/ActivityManager(  757): mDVFSHelper.release()
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  757): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6309 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 5312:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  757): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6327 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 5338:com.sec.knox.bridge/1000 (adj 13): bgCount ##41
,I/ActivityManager(  757): Killing 5391:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##41
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  757): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6350 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6367 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  757): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  757): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6373 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  757): Process com.google.android.googlequicksearchbox:search (pid 1586)(adj 1) has died(519,1359)
,W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms


HTC-HTC One_M8: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  978): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  978): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5584 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  978): Displayed com.example.hello/.MainActivity: +569ms
,W/jxcore-log( 5584): Initializing JXcore engine
W/jxcore-log( 5584): JXcore engine is ready
,W/jxcore-log( 5584): Starting JXcore engine
,W/jxcore-log( 5584): Platform android
W/jxcore-log( 5584): 
,W/jxcore-log( 5584): Process ARCH arm
W/jxcore-log( 5584): 
,I/jxcore-log( 5584): JXcore Cordova bridge is ready!
I/jxcore-log( 5584): 
,W/jxcore-log( 5584): JXcore engine is started
,E/jxcore-log( 5584): >> HTC-HTC One_M8
E/jxcore-log( 5584): 
,I/jxcore-log( 5584): Total memory 1912020992
I/jxcore-log( 5584): 
I/jxcore-log( 5584): Free memory 138031104
I/jxcore-log( 5584): 
,I/jxcore-log( 5584): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5584): 
I/jxcore-log( 5584): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5584): 
,I/jxcore-log( 5584): userPath [ 'www' ]
I/jxcore-log( 5584): 
,I/jxcore-log( 5584): Size 1080 1776
I/jxcore-log( 5584): 
,I/jxcore-log( 5584): Screen Brightness 142
I/jxcore-log( 5584): 
E/jxcore-log( 5584): Dummy Error Log.
E/jxcore-log( 5584): 
,I/jxcore-log( 5584): getBuffer is called!!!!,
I/jxcore-log( 5584): 
,I/ActivityManager(  978): Killing 5093:com.htc.cs.dm/u0a105 (adj 15): empty #17
,I/ActivityManager(  978): Recipient 5093
,I/ActivityManager(  978): Killing 5277:com.google.android.apps.docs/u0a107 (adj 15): empty #17
,I/ActivityManager(  978): Recipient 5277
,I/ActivityManager(  978): Waited long enough for: ServiceRecord{1095a6b u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,I/ActivityManager(  978): Killing 4747:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
,I/ActivityManager(  978): Recipient 4747,
,I/ActivityManager(  978): Waited long enough for: ServiceRecord{369fbbb u0 com.htc.musicenhancer/.EnhancerService},
,I/jxcore-log( 5584): ****TEST TOOK:  5131  ms ****,
I/jxcore-log( 5584): 
I/jxcore-log( 5584): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5584): 
,I/ActivityManager(  978): Killing 4807:com.htc.sdm/u0a82 (adj 15): empty #17,
,I/ActivityManager(  978): Recipient 4807,
,I/ActivityManager(  978): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg,
I/ActivityManager(  978): Killing 5584:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  978): Recipient 5584,
,W/ActivityManager(  978): Force removing ActivityRecord{3ac8db45 u0 com.example.hello/.MainActivity t27}: app died, no saved state,
,W/ActivityManager(  978): Spurious death for ProcessRecord{14bbf913 5584:com.example.hello/u0a380}, curProc for 5584: null,
I/ActivityManager(  978): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  978): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5687 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  978): Killing 5414:com.htc.task/u0a72 (adj 15): empty #17
,I/ActivityManager(  978): Recipient 5414,
,I/ActivityManager(  978): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5718 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a,
,I/ActivityManager(  978): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5777 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  978): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,E/ActivityManager(  978): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4300, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
,W/ActivityManager(  978): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  978): android.os.TransactionTooLargeException
W/ActivityManager(  978): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  978): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  978): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  978): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  978): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  978): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2009)
W/ActivityManager(  978): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1547)
W/ActivityManager(  978): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
W/ActivityManager(  978): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1060)
W/ActivityManager(  978): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:958)
W/ActivityManager(  978): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6859)
W/ActivityManager(  978): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
W/ActivityManager(  978): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/ActivityManager(  978): ,	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  978): Recipient 5718
,I/ActivityManager(  978): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=5794 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a,
,W/ActivityManager(  978): Spurious death for ProcessRecord{3846a41d 5794:com.google.android.apps.docs/u0a107}, curProc for 5718: null
,I/ActivityManager(  978): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5813 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  978): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5833 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
,E/ActivityManager(  978): App crashed! Process: com.android.documentsui
I/ActivityManager(  978): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5850 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  978): Killing 5029:com.google.android.talk/u0a120 (adj 15): empty #17
,I/ActivityManager(  978): Recipient 5029
,W/ActivityManager(  978): Can't addPackageDependency on system process
,I/ActivityManager(  978): Killing 5213:com.google.android.gms:car/u0a25 (adj 15): empty #17,
,I/ActivityManager(  978): Recipient 5213
,I/ActivityManager(  978): Killing 4713:com.google.android.music:main/u0a167 (adj 15): empty #17
,I/ActivityManager(  978): Recipient 4713
,I/ActivityManager(  978): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,I/ActivityManager(  978): Recipient 5794,
,I/ActivityManager(  978): Process com.google.android.apps.docs (pid 5794) has died,
W/ActivityManager(  978): Force removing ActivityRecord{3516f0db u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t28}: app died, no saved state
,I/ActivityManager(  978): Killing 5508:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
,I/ActivityManager(  978): Recipient 5508
,E/ActivityManager(  978): App crashed! Process: com.htc.launcher
,W/ActivityManager(  978):   Force finishing activity com.htc.launcher/.Launcher
,I/ActivityManager(  978): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,I/ActivityManager(  978): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=5891 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a,


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
F/ActivityManager(  825): Activity Manager Crash
F/ActivityManager(  825): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean com.android.server.pm.UserManagerService.hasUserRestriction(java.lang.String, int)' on a null object reference
F/ActivityManager(  825): 	at com.android.server.am.ActivityManagerService.handleIncomingUser(ActivityManagerService.java:14850)
F/ActivityManager(  825): 	at com.android.server.am.ActivityManagerService.startActivityAsUser(ActivityManagerService.java:3553)
F/ActivityManager(  825): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:164)
F/ActivityManager(  825): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2407)
F/ActivityManager(  825): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  825): Can't addPackageDependency on system process
,I/ActivityManager(  825): Config changes=1df8 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h731dp 560dpi nrml long port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
,I/ActivityManager(  825): Config changes=508 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h658dp 560dpi nrml port ?uimode ?night finger -keyb/v/h -nav/h s.3}
,I/ActivityManager(  825): Config changes=200 {1.0 ?mcc?mnc en_US ldltr sw411dp w411dp h658dp 560dpi nrml port finger -keyb/v/h -nav/h s.4}
,I/ActivityManager(  825): System now ready
,I/ActivityManager(  825): Start proc WebViewLoader-armeabi-v7a [android.webkit.WebViewFactory$RelroFileCreator] for : pid=1082 uid=1037 gids={} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.systemui for service com.android.systemui/.SystemUIService: pid=1099 uid=10024 gids={50024, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc android.process.media for broadcast com.android.providers.media/.MtpReceiver: pid=1117 uid=10008 gids={50008, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 1024} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.googlequicksearchbox:interactor for service com.google.android.googlequicksearchbox/com.google.android.voiceinteraction.GsaVoiceInteractionService: pid=1231 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.inputmethod.latin for service com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME: pid=1251 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.phone for service com.android.mms.service/.MmsService: pid=1276 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.server.telecom for added application com.android.server.telecom: pid=1287 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.nfc for added application com.android.nfc: pid=1312 uid=1027 gids={41027, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.phone for added application com.android.phone: pid=1329 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  825): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,I/ActivityManager(  825): Start proc com.google.android.googlequicksearchbox for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: pid=1353 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.printspooler for service com.android.printspooler/.model.PrintSpoolerService: pid=1386 uid=10081 gids={50081, 9997} abi=armeabi-v7a
,W/ActivityManager(  825): No pending application record for pid 1276 (IApplicationThread android.app.ApplicationThreadProxy@18c4cd2f); dropping process
,V/ActivityManager(  825): Display changed displayId=0
,V/ActivityManager(  825): Display changed displayId=0
,V/ActivityManager(  825): Display changed displayId=0
,I/ActivityManager(  825): Start proc com.google.android.gms.persistent for broadcast com.google.android.gms/com.google.android.location.internal.NlpNetworkProviderSettingsUpdateReceiver: pid=1428 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc android.process.acore for content provider com.android.providers.contacts/.CallLogProvider: pid=1478 uid=10005 gids={50005, 9997} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService: pid=1523 uid=10028 gids={50028, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.process.gapps for service com.google.android.gms/.config.ConfigService: pid=1551 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=1635 uid=10016 gids={50016, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  825): Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +1s797ms
,I/ActivityManager(  825): Start proc com.google.android.gms for service com.google.android.gms/.usagereporting.service.UsageReportingService: pid=1744 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=1788 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.audio.MediaButtonIntentReceiver: pid=1840 uid=10067 gids={50067, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider: pid=1959 uid=10051 gids={50051, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=1977 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=2002 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/ActivityManager(  825): Display changed displayId=0
,I/ActivityManager(  825): Start proc com.google.android.dialer for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver: pid=2041 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2059 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.motorola.motocit for broadcast com.motorola.motocit/.CQATestBootReceiver: pid=2097 uid=10002 gids={50002, 9997, 3002, 3001, 1028, 1015, 1023, 3003} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=2120 uid=10003 gids={50003, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2142 uid=10015 gids={50015, 9997} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2168 uid=10017 gids={50017, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2189 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc org.simalliance.openmobileapi.service:remote for service org.simalliance.openmobileapi.service/.SmartcardService: pid=2206 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=2223 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2250 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2325 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2435 uid=10044 gids={50044, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  825): Killing 1840:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  825): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2457 uid=10019 gids={50019, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Killing 1386:com.android.printspooler/u0a81 (adj 15): empty #17
,I/ActivityManager(  825): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=2493 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2513 uid=10078 gids={50078, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Killing 2059:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  825): Killing 2041:com.google.android.dialer/u0a13 (adj 15): empty #17
,I/ActivityManager(  825): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2548 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.apps.messaging for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver: pid=2577 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  825): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/ActivityManager(  825): Killing 2097:com.motorola.motocit/u0a2 (adj 15): empty #17
,I/ActivityManager(  825): Killing 1788:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  825): Start proc com.android.sdm.plugins.sprintdm for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver: pid=2617 uid=1001 gids={41001, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2635 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/ActivityManager(  825): Killing 2142:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
,I/ActivityManager(  825): Killing 2168:com.android.managedprovisioning/u0a17 (adj 15): empty #17
,I/ActivityManager(  825): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2656 uid=10066 gids={50066, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Killing 2189:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/ActivityManager(  825): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=2702 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  825): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2757 uid=10074 gids={50074, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  825): Killing 2250:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/ActivityManager(  825): Killing 1977:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  825): Waited long enough for: ServiceRecord{dd794f8 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/ActivityManager(  825): Waited long enough for: ServiceRecord{1667ca4b u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  825): Killing 2325:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/ActivityManager(  825): Killing 2435:com.google.android.deskclock/u0a44 (adj 15): empty #17
,V/ActivityManager(  825): Display changed displayId=0
,I/ActivityManager(  825): Killing 2493:com.google.android.gms:car/u0a11 (adj 15): empty #17
,TIME-OUT KILL (timeout was 150000ms),I/ActivityManager(  825): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  825): Force stopping com.example.hello appid=10272 user=0: pkg removed
I/ActivityManager(  825): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2851 uid=10018 gids={50018, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  825): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2871 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  825): Killing 2548:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/ActivityManager(  825): Killing 1959:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/ActivityManager(  825): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2904 uid=10046 gids={50046, 9997, 1028, 3003, 1015} abi=armeabi-v7a


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
--------- beginning of system
--------- beginning of main
,I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1020): mDVFSHelper.acquire()
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5281 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1020): Display changed displayId=0
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/ActivityManager( 1020): Displayed Component not be shown by security: +602ms (total +681ms)
W/ActivityManager( 1020): mDVFSHelper.release()
,W/jxcore-log( 5281): Initializing JXcore engine
W/jxcore-log( 5281): JXcore engine is ready
W/jxcore-log( 5281): Starting JXcore engine
W/jxcore-log( 5281): Platform android
W/jxcore-log( 5281): 
W/jxcore-log( 5281): Process ARCH arm
W/jxcore-log( 5281): 
I/jxcore-log( 5281): JXcore Cordova bridge is ready!
I/jxcore-log( 5281): 
W/jxcore-log( 5281): JXcore engine is started
E/jxcore-log( 5281): >> samsung-SM-A300FU
E/jxcore-log( 5281): 
I/jxcore-log( 5281): Total memory 1451114496
I/jxcore-log( 5281): 
I/jxcore-log( 5281): Free memory 27095040
I/jxcore-log( 5281): 
I/jxcore-log( 5281): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5281): 
I/jxcore-log( 5281): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5281): 
I/jxcore-log( 5281): userPath [ 'www' ]
I/jxcore-log( 5281): 
I/jxcore-log( 5281): Size 540 960
I/jxcore-log( 5281): 
I/jxcore-log( 5281): Screen Brightness 160
I/jxcore-log( 5281): 
E/jxcore-log( 5281): Dummy Error Log.
E/jxcore-log( 5281): 
I/jxcore-log( 5281): getBuffer is called!!!!
I/jxcore-log( 5281): 
,I/jxcore-log( 5281): ****TEST TOOK:  5053  ms ****
I/jxcore-log( 5281): 
,I/jxcore-log( 5281): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5281): 
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 5281:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{34bc82ef u0 com.example.hello/.MainActivity t19}
,W/ActivityManager( 1020): Spurious death for ProcessRecord{13263806 5281:com.example.hello/u0a345}, curProc for 5281: null
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=0: pkg removed,
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{34bc82ef u0 com.example.hello/.MainActivity t19 f}
W/ActivityManager( 1020): Duplicate finish request for ActivityRecord{34bc82ef u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5347 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/ActivityManager( 1020): Killing 4262:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5368 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder


HTC-HTC One M8s: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  947): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4661 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/ActivityManager(  947): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=4686 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/ActivityManager(  947): Start proc com.htc.showme for broadcast com.htc.showme/.update.MobileNetworkTurnOnReceiver: pid=4714 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  947): Killing 4054:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4054
I/ActivityManager(  947): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=4736 uid=10009 gids={50009, 9997, 5001, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 4081:com.htc.htccupd/u0a13 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4081
I/ActivityManager(  947): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=4787 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/ActivityManager(  947): Killing 4151:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4151
I/ActivityManager(  947): Killing 4175:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4175
I/ActivityManager(  947): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4830 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
I/ActivityManager(  947): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4777 on display 0
I/ActivityManager(  947): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4849 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  947): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=4872 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  947): Waited long enough for: ServiceRecord{17074472 u0 com.htc.HTCSpeaker/.NGFService}
,I/ActivityManager(  947): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4901 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  947): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4922 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/ActivityManager(  947): Killing 4199:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4199
I/ActivityManager(  947): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4963 uid=10076 gids={50076, 9997} abi=arm64-v8a
I/ActivityManager(  947): Killing 4222:com.android.smith/1000 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4222
I/ActivityManager(  947): Killing 4129:com.android.settings/1000 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4129
I/ActivityManager(  947): Killing 4280:com.google.android.gms:car/u0a24 (adj 15): empty #17
I/ActivityManager(  947): Recipient 4280
I/ActivityManager(  947): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4995 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  947): Killing 3341:com.android.defcontainer/u0a15 (adj 15): empty #17
I/ActivityManager(  947): Recipient 3341
,I/ActivityManager(  947): Killing 4243:com.android.vending/u0a72 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 4243
,I/ActivityManager(  947): Displayed com.example.hello/.MainActivity: +1s344ms
,I/ActivityManager(  947): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5026 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
,W/jxcore-log( 4849): Initializing JXcore engine
,W/jxcore-log( 4849): JXcore engine is ready
,W/jxcore-log( 4849): Starting JXcore engine
,I/ActivityManager(  947): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  947): Killing 4439:com.google.android.youtube/u0a176 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 4439
,W/jxcore-log( 4849): Platform android
W/jxcore-log( 4849): 
W/jxcore-log( 4849): Process ARCH arm
W/jxcore-log( 4849): 
,I/jxcore-log( 4849): JXcore Cordova bridge is ready!
I/jxcore-log( 4849): 
,W/jxcore-log( 4849): JXcore engine is started
,E/jxcore-log( 4849): >> HTC-HTC One M8s
E/jxcore-log( 4849): 
,I/jxcore-log( 4849): Total memory 1931808768
I/jxcore-log( 4849): 
,I/jxcore-log( 4849): Free memory 86900736
I/jxcore-log( 4849): 
I/jxcore-log( 4849): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4849): 
,I/jxcore-log( 4849): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4849): 
,I/jxcore-log( 4849): userPath [ 'www' ],
I/jxcore-log( 4849): 
,I/jxcore-log( 4849): Size 1080 1776
I/jxcore-log( 4849): 
,I/jxcore-log( 4849): Screen Brightness 142
I/jxcore-log( 4849): 
,E/jxcore-log( 4849): Dummy Error Log.
E/jxcore-log( 4849): 
,I/ActivityManager(  947): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  947): Killing 4518:com.google.android.gm/u0a106 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 4518,
,I/ActivityManager(  947): Killing 4562:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 4562
,I/jxcore-log( 4849): getBuffer is called!!!!,
I/jxcore-log( 4849): 
,I/ActivityManager(  947): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5117 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  947): Killing 4714:com.htc.showme/u0a81 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 4714
,I/ActivityManager(  947): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5140 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/ActivityManager(  947): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5163 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  947): Killing 4736:com.htc.sense.browser/u0a9 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 4736,
,I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi,
,I/ActivityManager(  947): Cannot resolve ContentProvider=com.htc.vowifi
,I/ActivityManager(  947): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5204 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/ActivityManager(  947): Killing 4787:com.htc.contacts/u0a38 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 4787
,I/ActivityManager(  947): Killing 4901:com.htc.mobiledata/u0a46 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 4901
,I/ActivityManager(  947): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5241 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/ActivityManager(  947): Killing 4922:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 4922
,I/ActivityManager(  947): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5294 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  947): Killing 4963:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 4963,
,I/ActivityManager(  947): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5325 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/ActivityManager(  947): Killing 4872:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 4872
,I/ActivityManager(  947): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5347 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/ActivityManager(  947): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5375 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/ActivityManager(  947): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5403 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager(  947): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5425 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 3801:com.htc.sense.mms/u0a64 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 3801
,I/jxcore-log( 4849): ****TEST TOOK:  5161  ms ****,
I/jxcore-log( 4849): 
I/jxcore-log( 4849): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4849): 
,I/ActivityManager(  947): Killing 4407:com.google.android.talk/u0a112 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 4407
,I/ActivityManager(  947): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5454 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  947): Killing 5026:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 5026
,I/ActivityManager(  947): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5510 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  947): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  947): Killing 4849:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  947): Recipient 4849
,W/ActivityManager(  947): Force removing ActivityRecord{1c84c3aa u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  947): Killing 4830:com.htc.sense.news/u0a74 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 4830,
,I/ActivityManager(  947): Force stopping com.example.hello appid=10373 user=0: pkg removed,
,W/ActivityManager(  947): Spurious death for ProcessRecord{3b9f8b6e 4849:com.example.hello/u0a373}, curProc for 4849: null,
,I/ActivityManager(  947): Killing 5084:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 5084,
,I/ActivityManager(  947): Killing 4597:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 4597
,I/ActivityManager(  947): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5555 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  947): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5569 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  947): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5602 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  947): Killing 5117:com.htc.cs.dm/u0a99 (adj 15): empty #17,
,I/ActivityManager(  947): Recipient 5117
,I/ActivityManager(  947): Killing 5140:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  947): Recipient 5140
,I/ActivityManager(  947): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5625 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,E/ActivityManager(  947): App crashed! Process: com.google.android.music:main,
,I/ActivityManager(  947): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5658 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  968): Killing 3375:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431a3660 stackId=1, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3957
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431a3660 stackId=1, 2 tasks}
V/ActivityManager(  968): Moving to PAUSING: ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  968): resumeTopActivityLocked: Pausing null
V/ActivityManager(  968): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  968): startService SlideAside
D/ActivityManager(  968): setFocusedStack: mFocusedStack=ActivityStack{431a3660 stackId=1, 2 tasks}
D/ActivityManager(  968): allPausedActivitiesComplete: r=ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  968): Moving to PAUSED: ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431a3660 stackId=1, 2 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Restarting ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  968): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3974 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3} (starting new instance)
,I/ActivityManager(  968): Displayed com.example.hello/.MainActivity: +373ms
,I/ActivityManager( 3974): Timeline: Activity_idle id: android.os.BinderProxy@427df510 time:46823
,W/jxcore-log( 3974): Initializing JXcore engine
,W/jxcore-log( 3974): JXcore engine is ready
,W/jxcore-log( 3974): Starting JXcore engine
,I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3} time:47184
,D/ActivityManager(  968): no-history finish of ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  968): Finishing activity token=Token{43226090 ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  968): Moving to FINISHING: ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  968): Moving to STOPPING: ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  968): Moving to STOPPED: ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,W/jxcore-log( 3974): Platform android
W/jxcore-log( 3974): 
,W/jxcore-log( 3974): Process ARCH arm
W/jxcore-log( 3974): 
,I/jxcore-log( 3974): JXcore Cordova bridge is ready!
I/jxcore-log( 3974): 
,W/jxcore-log( 3974): JXcore engine is started
,E/jxcore-log( 3974): >> LGE-LG-D802
E/jxcore-log( 3974): 
,I/jxcore-log( 3974): Total memory 1943035904
I/jxcore-log( 3974): 
I/jxcore-log( 3974): Free memory 476504064
I/jxcore-log( 3974): 
I/jxcore-log( 3974): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3974): 
,I/jxcore-log( 3974): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3974): 
,I/jxcore-log( 3974): userPath [ 'www' ]
I/jxcore-log( 3974): 
,I/jxcore-log( 3974): Size 1080 1776
I/jxcore-log( 3974): 
,I/jxcore-log( 3974): Screen Brightness 255
I/jxcore-log( 3974): 
,E/jxcore-log( 3974): Dummy Error Log.
E/jxcore-log( 3974): 
,I/jxcore-log( 3974): getBuffer is called!!!!
I/jxcore-log( 3974): 
,I/ActivityManager(  968): Killing 3442:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431a3660 stackId=1, 2 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3974): ****TEST TOOK:  5042  ms ****
I/jxcore-log( 3974): 
I/jxcore-log( 3974): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3974): 
,I/ActivityManager(  968): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  968): Killing 3974:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  968): Force removing ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3 f} (removed from history)
V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{43035b50 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{431a3660 stackId=1, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  968): moveHomeStack:
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,V/ActivityManager(  968): Moving to RESUMED: ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  968): resumeTopActivityLocked: Resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  968): Moving to DESTROYING: ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  968): Moving to DESTROYED: ActivityRecord{43230ae0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4060 uid=10090 gids={50090}
,I/ActivityManager(  968): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4074 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  968): Killing 3325:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  968): Service ServiceRecord{43279ba0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43228660 3325:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  968): Service ServiceRecord{4324df48 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43228660 3325:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4103 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  968): Killing 2092:android.process.media/u0a23 (adj 15): empty #17
I/ActivityManager(  968): Delaying start of: ServiceRecord{431b00d0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4119 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  968): Timeline: Activity_windows_visible id: ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1} time:53889
I/ActivityManager(  968): Waited long enough for: ServiceRecord{431db920 u0 com.android.mms/.transaction.SmsReceiverService}
,I/ActivityManager(  968): Killing 3253:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  968): Killing 3812:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4136 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@427e22f8 time:53978
,I/ActivityManager(  968): Killing 3853:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Delaying start of: ServiceRecord{43012e08 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager(  968): Process android.process.media (pid 4136) has died.
,I/ActivityManager(  968): Start proc android.process.media for restart android.process.media: pid=4150 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1},
,I/ActivityManager(  968): Process android.process.media (pid 4150) has died.
,I/ActivityManager(  968): Start proc android.process.media for restart android.process.media: pid=4165 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Process android.process.media (pid 4165) has died.
,I/ActivityManager(  968): Start proc android.process.media for restart android.process.media: pid=4179 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Process android.process.media (pid 4179) has died.
,I/ActivityManager(  968): Start proc android.process.media for restart android.process.media: pid=4195 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Process android.process.media (pid 4195) has died.
,I/ActivityManager(  968): Start proc android.process.media for restart android.process.media: pid=4208 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  968): Process android.process.media (pid 4208) has died.
,W/ActivityManager(  968): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 1000ms
,I/ActivityManager(  968): Start proc android.process.media for restart android.process.media: pid=4222 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  968): resumeTopActivitiesLocked(): target Stack:ActivityStack{42b31108 stackId=0, 1 tasks}
,D/ActivityManager(  968): resumeTopActivityLocked: Top activity resumed ActivityRecord{42b18e38 u0 com.lge.launcher2/.Launcher t1}


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
--------- beginning of main
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
--------- beginning of system
W/ActivityManager( 1016): ProcessRecord{1994490 4391:com.sec.providers.settingsearch/u0a150} is already killed
I/ActivityManager( 1016): Existing provider com.sec.providers.settingsearch/.SettingSearchProvider is crashing; detaching ProcessRecord{38864189 1303:com.android.settings/1000}
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/ActivityManager( 1016): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5056 uid=10150 gids={50150, 9997} abi=armeabi-v7a
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1016): Killing 4309:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
I/ActivityManager( 1016): Waited long enough for: ServiceRecord{300a1642 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
I/ActivityManager( 1016): Killing 4475:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5096 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5116 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1016): mDVFSHelper.acquire()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5146 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5178 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5200 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=5215 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5232 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Killing 4492:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/ActivityManager( 1016): Killing 4155:com.android.mms/u0a46 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/ActivityManager( 1016): Process ACMS.Process (pid 4776)(adj 0) has died(42,1045)
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/ActivityManager( 1016): Killing 4458:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/ActivityManager( 1016): Killing 4519:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/ActivityManager( 1016): Displayed Component not be shown by security: +928ms
,W/ActivityManager( 1016): mDVFSHelper.release()
,I/ActivityManager( 1016): Killing 4511:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/jxcore-log( 5146): Initializing JXcore engine
W/jxcore-log( 5146): JXcore engine is ready
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/jxcore-log( 5146): Starting JXcore engine
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{29af0d15 u0 com.sec.bcservice/.BroadcastService}
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/ActivityManager( 1016): Killing 4540:com.sec.pcw.device/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5317 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 5146): Platform android,
W/jxcore-log( 5146): 
W/jxcore-log( 5146): Process ARCH arm
W/jxcore-log( 5146): 
,I/ActivityManager( 1016): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=5334 uid=10040 gids={50040, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/jxcore-log( 5146): JXcore Cordova bridge is ready!
I/jxcore-log( 5146): 
,W/jxcore-log( 5146): JXcore engine is started
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,I/ActivityManager( 1016): Killing 4605:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,E/jxcore-log( 5146): >> samsung-SM-A500FU
E/jxcore-log( 5146): 
,I/jxcore-log( 5146): Total memory 1983787008
I/jxcore-log( 5146): 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/jxcore-log( 5146): Free memory 33705984
I/jxcore-log( 5146): 
I/jxcore-log( 5146): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5146): 
I/jxcore-log( 5146): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5146): 
,I/jxcore-log( 5146): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5146): 
,I/jxcore-log( 5146): Size 720 1280
I/jxcore-log( 5146): 
,I/jxcore-log( 5146): Screen Brightness 255
I/jxcore-log( 5146): 
,E/jxcore-log( 5146): Dummy Error Log.
E/jxcore-log( 5146): 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5355 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Process com.samsung.indexservice (pid 5317)(adj 11) has died(42,1031)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 4624:com.policydm/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.async.BackgroundTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1016): Killing 4640:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5146): getBuffer is called!!!!
I/jxcore-log( 5146): 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5379 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,V/ActivityManager( 1016): Display changed displayId=0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 4681:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{1b89feb9 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/ActivityManager( 1016): Killing 4717:com.osp.app.signin/u0a41 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/jxcore-log( 5146): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 5146): 
,I/jxcore-log( 5146): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5146): 
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 5146:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{3ed169ec u0 com.example.hello/.MainActivity t11}
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10174 user=0: pkg removed
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5449 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5464 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=5479 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5495 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/ActivityManager( 1016): Killing 4825:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5512 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,I/ActivityManager( 1016): Killing 4843:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5528 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 4859:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=5544 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4662:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5561 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5597 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4919:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5613 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4942:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.LocalFota for broadcast com.LocalFota/.XLFBroadcastReceiver: pid=4453 uid=10120 gids={50120, 9997, 3003, 2001} abi=armeabi-v7a
I/ActivityManager(  895): Killing 3375:tv.peel.smartremote/u0a171 (adj 15): bgCount ##41
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4459 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/ActivityManager(  895): Killing 3604:com.samsung.android.scloud.backup/u0a65 (adj 15): bgCount ##41
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.walkingmate.receiver.WalkingMateReceiver: pid=4494 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4512 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  895): Killing 3637:org.simalliance.openmobileapi.service/1101 (adj 15): bgCount ##41
I/ActivityManager(  895): Killing 3668:com.fmm.dm/1000 (adj 15): bgCount ##41
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4537 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  895): Killing 3685:com.sec.android.app.taskmanager/u0a176 (adj 15): bgCount ##41
I/ActivityManager(  895): Killing 3702:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4561 uid=10143 gids={50143, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  895): Killing 3717:com.samsung.android.service.travel/u0a178 (adj 15): bgCount ##41
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=4581 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4600 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager(  895): Killing 3763:com.sec.usbsettings/1000 (adj 15): bgCount ##41
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4630 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4638 uid=10154 gids={50154, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/ActivityManager(  895): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  895): mDVFSHelper.acquire()
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  895): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4678 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  895): Activity reported stop, but no longer stopping: ActivityRecord{1612819e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9}
,I/ActivityManager(  895): Killing 2341:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,D/ActivityManager(  895): post active user change for 0
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4767 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  895): Displayed com.example.hello/.MainActivity: +1s214ms
,W/ActivityManager(  895): mDVFSHelper.release()
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4844 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  895): Killing 3621:com.sec.android.fotaclient/u0a11 (adj 15): bgCount ##41
,I/ActivityManager(  895): Killing 3750:com.wssnps/1000 (adj 15): bgCount ##41
,W/jxcore-log( 4678): Initializing JXcore engine
W/jxcore-log( 4678): JXcore engine is ready
,W/jxcore-log( 4678): Starting JXcore engine
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4891 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,W/jxcore-log( 4678): Platform android
W/jxcore-log( 4678): 
W/jxcore-log( 4678): Process ARCH arm
W/jxcore-log( 4678): 
,I/jxcore-log( 4678): JXcore Cordova bridge is ready!
I/jxcore-log( 4678): 
,W/jxcore-log( 4678): JXcore engine is started
,I/ActivityManager(  895): Killing 3786:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,E/jxcore-log( 4678): >> samsung-SM-G900F
E/jxcore-log( 4678): 
,I/jxcore-log( 4678): Total memory 1787449344
I/jxcore-log( 4678): 
I/jxcore-log( 4678): Free memory 52391936
I/jxcore-log( 4678): 
,I/jxcore-log( 4678): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4678): 
I/jxcore-log( 4678): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4678): 
,I/ActivityManager(  895): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4923 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/jxcore-log( 4678): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4678): 
,I/ActivityManager(  895): Killing 3823:com.google.android.onetimeinitializer/u0a14 (adj 15): bgCount ##41
,I/ActivityManager(  895): Killing 3802:com.samsung.android.app.accesscontrol/1000 (adj 15): bgCount ##42
,I/jxcore-log( 4678): Size 1080 1920
I/jxcore-log( 4678): 
,I/jxcore-log( 4678): Screen Brightness 134
I/jxcore-log( 4678): 
,E/jxcore-log( 4678): Dummy Error Log.
E/jxcore-log( 4678): 
,W/ActivityManager(  895): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager(  895): getTasks: caller 10163 does not hold GET_TASKS; limiting output
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  895): Process com.android.email (pid 4767)(adj 0) has died(57,632)
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4961 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 3843:com.sec.factory.camera/1000 (adj 15): bgCount ##41
,I/ActivityManager(  895): Killing 3849:com.samsung.android.app.airwakeupview/u0a72 (adj 15): bgCount ##41
,I/ActivityManager(  895): Process com.sec.android.app.sns3 (pid 4844)(adj 0) has died(64,633)
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4984 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 3922:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,I/jxcore-log( 4678): getBuffer is called!!!!
I/jxcore-log( 4678): 
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=5004 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 3164:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,W/ActivityManager(  895): getTasks: caller 10164 does not hold GET_TASKS; limiting output
,I/ActivityManager(  895): Process com.android.exchange (pid 4923)(adj 11) has died(77,634)
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5027 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  895): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=5044 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 3906:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/ActivityManager(  895): Killing 3961:com.samsung.android.provider.filterprovider/u0a109 (adj 15): bgCount ##41
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5076 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5101 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 3954:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 3986:com.samsung.klmsagent/u0a19 (adj 15): bgCount ##41
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5149 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 4004:com.samsung.android.nearby.mediaserver/u0a76 (adj 15): bgCount ##41
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=5165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 3890:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/ActivityManager(  895): Killing 4020:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  895): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  895): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5180 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a


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
--------- beginning of system
,--------- beginning of main
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1019): mDVFSHelper.acquire()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5007 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1019): Display changed displayId=0
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{28dbf1af u0 com.example.hello/.MainActivity t10}
I/ActivityManager( 1019): Displayed Component not be shown by security: +675ms (total +755ms)
W/ActivityManager( 1019): mDVFSHelper.release()
,W/jxcore-log( 5007): Initializing JXcore engine
W/jxcore-log( 5007): JXcore engine is ready
,W/jxcore-log( 5007): Starting JXcore engine
,W/jxcore-log( 5007): Platform android,
W/jxcore-log( 5007): 
W/jxcore-log( 5007): Process ARCH arm
W/jxcore-log( 5007): 
,I/jxcore-log( 5007): JXcore Cordova bridge is ready!,
I/jxcore-log( 5007): 
W/jxcore-log( 5007): JXcore engine is started,
,E/jxcore-log( 5007): >> samsung-SM-A300FU
E/jxcore-log( 5007): 
,I/jxcore-log( 5007): Total memory 1451114496
I/jxcore-log( 5007): 
,I/jxcore-log( 5007): Free memory 23502848
I/jxcore-log( 5007): 
I/jxcore-log( 5007): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5007): 
,I/jxcore-log( 5007): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5007): 
,I/jxcore-log( 5007): userPath [ 'www' ]
I/jxcore-log( 5007): 
,I/jxcore-log( 5007): Size 540 960
I/jxcore-log( 5007): 
,I/jxcore-log( 5007): Screen Brightness 255
I/jxcore-log( 5007): 
,E/jxcore-log( 5007): Dummy Error Log.
E/jxcore-log( 5007): 
,I/jxcore-log( 5007): getBuffer is called!!!!
I/jxcore-log( 5007): 
,I/ActivityManager( 1019): Killing 4424:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{2bfe7021 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5007): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 5007): 
,I/jxcore-log( 5007): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5007): 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5007:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{28dbf1af u0 com.example.hello/.MainActivity t10}
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5075 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5090 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5107 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5123 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5158 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,I/ActivityManager( 1019): Killing 4158:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5179 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5195 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4107:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/ActivityManager( 1019): Killing 3626:com.google.android.talk/u0a102 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 4508:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2196
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2210 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
,I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +253ms
,W/jxcore-log( 2210): Initializing JXcore engine
,W/jxcore-log( 2210): JXcore engine is ready
,W/jxcore-log( 2210): Starting JXcore engine
,W/jxcore-log( 2210): Platform android
W/jxcore-log( 2210): 
,W/jxcore-log( 2210): Process ARCH arm
W/jxcore-log( 2210): 
,I/jxcore-log( 2210): JXcore Cordova bridge is ready!
I/jxcore-log( 2210): 
,W/jxcore-log( 2210): JXcore engine is started
,E/jxcore-log( 2210): >> HTC-HTC Desire 820
E/jxcore-log( 2210): 
,I/jxcore-log( 2210): Total memory 1964650496
I/jxcore-log( 2210): 
I/jxcore-log( 2210): Free memory 837890048
I/jxcore-log( 2210): 
I/jxcore-log( 2210): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2210): 
,I/jxcore-log( 2210): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2210): 
,I/jxcore-log( 2210): userPath [ 'www' ]
I/jxcore-log( 2210): 
,I/jxcore-log( 2210): Size 720 1184
I/jxcore-log( 2210): 
,I/jxcore-log( 2210): Screen Brightness 10
I/jxcore-log( 2210): 
,E/jxcore-log( 2210): Dummy Error Log.
E/jxcore-log( 2210): 
,I/jxcore-log( 2210): getBuffer is called!!!!
I/jxcore-log( 2210): 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4257aa48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2255 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2268 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 1811:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 1811
,I/ActivityManager(  906): Killing 1827:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 1827
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2282 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2294 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,I/ActivityManager(  906): Killing 1914:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2313 uid=10016 gids={50016, 3003, 5012, 2001}
,I/ActivityManager(  906): Recipient 1914
,I/ActivityManager(  906): Killing 1260:com.android.printspooler/u0a161 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 1260
,I/ActivityManager(  906): Killing 1973:com.htc.showme/u0a82 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 1973
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2343 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.android.providers.downloads/.DownloadReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2360 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 1987:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
,I/ActivityManager(  906): Killing 1851:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 1987
,I/ActivityManager(  906): Recipient 1851
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/ActivityManager(  906): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2396 uid=10030 gids={50030}
,I/ActivityManager(  906): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver,
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2410 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  906): Killing 1878:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,I/ActivityManager(  906): Recipient 1878
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 2048:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2048
,I/ActivityManager(  906): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2436 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2448 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 1931:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 1931
,I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2460 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2062:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2062
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2477 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  906): Killing 2081:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2081
,I/ActivityManager(  906): Killing 2102:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2102
,I/ActivityManager(  906): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2489 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  906): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2503 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  906): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2519 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/ActivityManager(  906): Killing 1660:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,I/ActivityManager(  906): Killing 1950:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 1950
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2534 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Killing 2255:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2255
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2547 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 2268:com.qualcomm.privinit/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 1660
,I/ActivityManager(  906): Recipient 2268
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 2282:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Recipient 2282
,I/ActivityManager(  906): Killing 2313:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2313
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4252ba20 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2572 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,I/ActivityManager(  906): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2584 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Killing 2343:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2343
,I/jxcore-log( 2210): ****TEST TOOK:  5042  ms ****
I/jxcore-log( 2210): 
I/jxcore-log( 2210): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2210): 
,I/ActivityManager(  906): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2601 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,I/ActivityManager(  906): Killing 2294:android.process.media/u0a21 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2294
,I/ActivityManager(  906): Start proc android.process.media for broadcast com.android.providers.media/.MediaScannerReceiver: pid=2617 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
,I/ActivityManager(  906): Killing 2360:com.htc.fm/u0a24 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2360
,I/ActivityManager(  906): Delay finish: com.android.providers.media/.MediaScannerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2637 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2668 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/ActivityManager(  906): Killing 1199:com.google.android.gms/u0a28 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
,I/ActivityManager(  906): Recipient 1199
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  906): Killing 2210:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  906): Force removing ActivityRecord{4260fd40 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4263d8c0 u0 com.htc.autobot/.htcmodeclient.HtcModeService}


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
,--------- beginning of /dev/log/system
I/ActivityManager(  909): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2916
I/ActivityManager(  909): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2963 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,I/ActivityManager(  909): Displayed com.example.hello/.MainActivity: +274ms
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,W/jxcore-log( 2963): Initializing JXcore engine
,W/jxcore-log( 2963): JXcore engine is ready
,W/jxcore-log( 2963): Starting JXcore engine
,I/ActivityManager(  909): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3039 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,W/jxcore-log( 2963): Platform android
W/jxcore-log( 2963): 
,W/jxcore-log( 2963): Process ARCH arm
W/jxcore-log( 2963): 
,I/jxcore-log( 2963): JXcore Cordova bridge is ready!
I/jxcore-log( 2963): 
,W/jxcore-log( 2963): JXcore engine is started
,I/ActivityManager(  909): Killing 2661:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2661
,E/jxcore-log( 2963): >> HTC-HTC Desire 820
E/jxcore-log( 2963): 
,I/jxcore-log( 2963): Total memory 1964650496
I/jxcore-log( 2963): 
I/jxcore-log( 2963): Free memory 698089472
I/jxcore-log( 2963): 
I/jxcore-log( 2963): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2963): 
,I/jxcore-log( 2963): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2963): 
,I/jxcore-log( 2963): userPath [ 'www' ]
I/jxcore-log( 2963): 
,I/jxcore-log( 2963): Size 720 1184
I/jxcore-log( 2963): 
,I/jxcore-log( 2963): Screen Brightness 142
I/jxcore-log( 2963): 
,E/jxcore-log( 2963): Dummy Error Log.
E/jxcore-log( 2963): 
,I/ActivityManager(  909): Killing 2460:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2460
,I/ActivityManager(  909): Delay finish: com.android.settings/.NSReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3077 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  909): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3119 uid=10032 gids={50032, 3003, 5012}
,I/jxcore-log( 2963): getBuffer is called!!!!
I/jxcore-log( 2963): 
,I/ActivityManager(  909): Killing 2693:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2693
,I/ActivityManager(  909): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3132 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  909): Killing 2728:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2728
,I/ActivityManager(  909): Killing 2676:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3147 uid=10041 gids={50041}
,I/ActivityManager(  909): Recipient 2676
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3162 uid=10078 gids={50078}
I/ActivityManager(  909): Killing 2754:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  909): Killing 2781:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2781
I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3175 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  909): Recipient 2754
I/ActivityManager(  909): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3191 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  909): Killing 2798:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2798
I/ActivityManager(  909): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3206 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3220 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Killing 2814:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2814
I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3235 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  909): Killing 2841:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2841
I/ActivityManager(  909): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3247 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  909): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3259 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  909): Killing 2882:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  909): Killing 2868:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
I/ActivityManager(  909): Recipient 2882
I/ActivityManager(  909): Recipient 2868
,I/ActivityManager(  909): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 2895:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3275 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  909): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  909): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3289 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  909): Recipient 2895
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3039:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  909): Killing 2853:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 2853
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  909): Recipient 3039
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3314 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  909): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3334 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  909): Killing 3077:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3077
,I/ActivityManager(  909): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3351 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  909): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Killing 3119:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3368 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002},
,I/ActivityManager(  909): Recipient 3119
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3387 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  909): Killing 3132:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3132
,I/ActivityManager(  909): Killing 3175:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3175
,I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3409 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  909): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/jxcore-log( 2963): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 2963): 
,I/jxcore-log( 2963): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2963): 
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3438 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  909): Killing 2828:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  909): Recipient 2828
,I/ActivityManager(  909): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,I/ActivityManager(  909): Killing 2963:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  909): Force removing ActivityRecord{41d9fe60 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{426202a0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  909): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3463 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/ActivityManager(  909): App crashed! Process: com.google.android.music:main
,I/ActivityManager(  909): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3498 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  909): Killing 3235:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3235
,I/ActivityManager(  909): Killing 3247:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3247


LGE-Nexus 5: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2122
I/ActivityManager(  756): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2141 uid=10001 gids={50001, 3003, 1028, 1015}
I/ActivityManager(  756): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2153 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  756): Killing 1229:com.google.android.partnersetup/u0a11 (adj 15): empty #17
I/ActivityManager(  756): Killing 1553:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #18
,I/ActivityManager(  756): Displayed com.example.hello/.MainActivity: +294ms
,W/jxcore-log( 2153): Initializing JXcore engine
,W/jxcore-log( 2153): JXcore engine is ready
W/jxcore-log( 2153): Starting JXcore engine
,W/jxcore-log( 2153): Platform android
W/jxcore-log( 2153): 
,W/jxcore-log( 2153): Process ARCH arm
W/jxcore-log( 2153): 
,I/jxcore-log( 2153): JXcore Cordova bridge is ready!
I/jxcore-log( 2153): 
,W/jxcore-log( 2153): JXcore engine is started
,E/jxcore-log( 2153): >> LGE-Nexus 5
E/jxcore-log( 2153): 
,I/jxcore-log( 2153): Total memory 1945137152
I/jxcore-log( 2153): 
I/jxcore-log( 2153): Free memory 912338944
I/jxcore-log( 2153): 
I/jxcore-log( 2153): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2153): 
,I/jxcore-log( 2153): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2153): 
,I/jxcore-log( 2153): userPath [ 'www' ]
I/jxcore-log( 2153): 
,I/jxcore-log( 2153): Size 1080 1776
I/jxcore-log( 2153): 
,I/jxcore-log( 2153): Screen Brightness 82
I/jxcore-log( 2153): 
,E/jxcore-log( 2153): Dummy Error Log.
E/jxcore-log( 2153): 
,I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Killing 1587:com.android.vending/u0a14 (adj 15): empty #17
,I/ActivityManager(  756): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.gm/.GmailReceiver
,I/jxcore-log( 2153): getBuffer is called!!!!
I/jxcore-log( 2153): 
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2292 uid=10011 gids={50011, 3003}
,I/ActivityManager(  756): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2312 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  756): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2327 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  756): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  756): Delaying start of: ServiceRecord{42d66840 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2371 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
I/ActivityManager(  756): Killing 1649:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Killing 1678:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  756): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2398 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  756): Killing 1730:com.google.android.keep/u0a52 (adj 15): empty #17
,I/ActivityManager(  756): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2421 uid=10035 gids={50035, 1028, 3003, 1015}
I/ActivityManager(  756): Killing 1765:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ActivityManager(  756): No permission grants found for com.quickoffice.android
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{42bda0d8 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  756): Killing 1082:com.android.printspooler/u0a64 (adj 15): empty #17
,I/ActivityManager(  756): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  756): Waited long enough for: ServiceRecord{42cb4338 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
I/ActivityManager(  756): Resuming delayed broadcast
,I/jxcore-log( 2153): ****TEST TOOK:  5029  ms ****
I/jxcore-log( 2153): 
I/jxcore-log( 2153): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2153): 
,I/ActivityManager(  756): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  756): Killing 2153:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  756): Force removing ActivityRecord{42b192d8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  756): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  756): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2538 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  756): Resuming delayed broadcast
I/ActivityManager(  756): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  756): Resuming delayed broadcast
,I/ActivityManager(  756): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2560 uid=10034 gids={50034}
,I/ActivityManager(  756): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2579 uid=10006 gids={50006, 1028, 1015, 1023}
,I/ActivityManager(  756): Killing 1793:com.google.android.youtube/u0a71 (adj 15): empty #17
,I/ActivityManager(  756): Killing 1918:com.google.android.exchange/u0a37 (adj 15): empty #17
,F/ActivityManager(  756): Service ServiceRecord{42c9bb98 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42abea48 1793:com.google.android.youtube/u0a71} not same as in map: null
,I/ActivityManager(  756): Killing 1663:com.google.android.deskclock/u0a33 (adj 15): empty #17


```




###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0FDD3E61-2429-4352-AD6E-57F32B71A348/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0FDD3E61-2429-4352-AD6E-57F32B71A348/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E7899691-DD99-4E8F-A41F-7C241FCAD0E1/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65067"
,(lldb)     command script import "/tmp/0FDD3E61-2429-4352-AD6E-57F32B71A348/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 16:34:04.279 HelloWorld[1639:1742464] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FFADBC30-B4F6-4EEF-83EB-3FAA3D0A32FD/Library/Cookies/Cookies.binarycookies
,2015-11-06 16:34:04.633 HelloWorld[1639:1742464] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 16:34:04.634 HelloWorld[1639:1742464] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:34:04.638 HelloWorld[1639:1742464] Unlimited access to network resources
,2015-11-06 16:34:04.643 HelloWorld[1639:1742464] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:34:08.641 HelloWorld[1639:1742464] Resetting plugins due to page load.
,2015-11-06 16:34:09.095 HelloWorld[1639:1742464] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/E7899691-DD99-4E8F-A41F-7C241FCAD0E1/HelloWorld.app/www/index.html
,2015-11-06 16:34:09.187 HelloWorld[1639:1742464] JXcore Cordova plugin initializing
,2015-11-06 16:34:09.190 HelloWorld[1639:1742580] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 128753664
execPath /private/var/mobile/Containers/Bundle/Application/E7899691-DD99-4E8F-A41F-7C241FCAD0E1/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/E7899691-DD99-4E8F-A41F-7C241FCAD0E1/HelloWorld.app/www/jxcore/
,userPath []
2015-11-06 16:34:09.456 HelloWorld[1639:1742580] Native method ScreenInfo not found.
2015-11-06 16:34:09.456 HelloWorld[1639:1742580] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5108  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9249CBAB-650A-40EC-B194-F34401BE8BDC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9249CBAB-650A-40EC-B194-F34401BE8BDC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/A6E3AACF-359E-4B5A-84CF-177321ABBF87/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65070"
,(lldb)     command script import "/tmp/9249CBAB-650A-40EC-B194-F34401BE8BDC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 16:34:51.545 HelloWorld[1336:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-06 16:34:51.549 HelloWorld[1336:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:34:51.555 HelloWorld[1336:60b] Unlimited access to network resources
,2015-11-06 16:34:51.563 HelloWorld[1336:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:35:02.454 HelloWorld[1336:60b] Resetting plugins due to page load.
,2015-11-06 16:35:03.237 HelloWorld[1336:60b] Finished load of: file:///var/mobile/Applications/A6E3AACF-359E-4B5A-84CF-177321ABBF87/HelloWorld.app/www/index.html
,2015-11-06 16:35:03.299 HelloWorld[1336:60b] JXcore Cordova plugin initializing
,2015-11-06 16:35:03.301 HelloWorld[1336:6607] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 494243840
execPath /private/var/mobile/Applications/A6E3AACF-359E-4B5A-84CF-177321ABBF87/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/A6E3AACF-359E-4B5A-84CF-177321ABBF87/HelloWorld.app/www/jxcore/
userPath []
,2015-11-06 16:35:03.773 HelloWorld[1336:6607] Native method ScreenInfo not found.
,2015-11-06 16:35:03.775 HelloWorld[1336:6607] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5254  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E7767FE7-7CEA-443E-9E7B-1B1086AE813B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E7767FE7-7CEA-443E-9E7B-1B1086AE813B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/40D60F3D-1409-4CB7-8762-696C53306394/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65065"
,(lldb)     command script import "/tmp/E7767FE7-7CEA-443E-9E7B-1B1086AE813B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-11-06 16:34:03.817 HelloWorld[2637:2806707] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/13AEA27F-DB9B-472A-BB55-8BB469ECE8EE/Library/Cookies/Cookies.binarycookies
,2015-11-06 16:34:04.206 HelloWorld[2637:2806707] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 16:34:04.207 HelloWorld[2637:2806707] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:34:04.210 HelloWorld[2637:2806707] Unlimited access to network resources
,2015-11-06 16:34:04.215 HelloWorld[2637:2806707] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:34:07.870 HelloWorld[2637:2806707] Resetting plugins due to page load.
,2015-11-06 16:34:08.108 HelloWorld[2637:2806707] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/40D60F3D-1409-4CB7-8762-696C53306394/HelloWorld.app/www/index.html
,2015-11-06 16:34:08.162 HelloWorld[2637:2806707] JXcore Cordova plugin initializing
2015-11-06 16:34:08.163 HelloWorld[2637:2806828] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 97472512
execPath /private/var/mobile/Containers/Bundle/Application/40D60F3D-1409-4CB7-8762-696C53306394/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/40D6,0F3D-1409-4CB7-8762-696C53306394/HelloWorld.app/www/jxcore/
,userPath []
2015-11-06 16:34:08.392 HelloWorld[2637:2806828] Native method ScreenInfo not found.
2015-11-06 16:34:08.393 HelloWorld[2637:2806828] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5106  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D1D73D95-ACF8-4D6B-A64B-FC956D4ABC8E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D1D73D95-ACF8-4D6B-A64B-FC956D4ABC8E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/47672234907c1b8/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0FE6D079-8ED0-468A-800C-565A7D7E87C1/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65064"
,(lldb)     command script import "/tmp/D1D73D95-ACF8-4D6B-A64B-FC956D4ABC8E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-06 16:34:08.118 HelloWorld[1766:3656127] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A4FD1146-BE9F-412A-A849-75EB1DF2806A/Library/Cookies/Cookies.binarycookies
,2015-11-06 16:34:08.551 HelloWorld[1766:3656127] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-06 16:34:08.553 HelloWorld[1766:3656127] Multi-tasking -> Device: YES, App: YES
,2015-11-06 16:34:08.557 HelloWorld[1766:3656127] Unlimited access to network resources
,2015-11-06 16:34:08.566 HelloWorld[1766:3656127] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-06 16:34:18.606 HelloWorld[1766:3656127] Resetting plugins due to page load.
,2015-11-06 16:34:22.269 HelloWorld[1766:3656127] Finished load of: file:///var/mobile/Containers/Bundle/Application/0FE6D079-8ED0-468A-800C-565A7D7E87C1/HelloWorld.app/www/index.html
,2015-11-06 16:34:22.336 HelloWorld[1766:3656127] JXcore Cordova plugin initializing
,2015-11-06 16:34:22.337 HelloWorld[1766:3656329] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
,Free memory 302465024
,execPath /private/var/mobile/Containers/Bundle/Application/0FE6D079-8ED0-468A-800C-565A7D7E87C1/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Containers/Bundle/Application/0FE6D079-8ED0-468A-800C-565A7D7E87C1/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-06 16:34:22.530 HelloWorld[1766:3656329] Native method ScreenInfo not found.
2015-11-06 16:34:22.530 HelloWorld[1766:3656329] Native method ScreenBrightness not found.
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
  '/home/pi/Test/server_47672234907c1b8/Sub/serverApp/index.js',
  '{"devices":{"ios":4,"android":22,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 22, cancel: 1 } }


```

