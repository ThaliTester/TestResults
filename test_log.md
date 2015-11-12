#### Test 49526184b4f3aa9 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184b4f3aa9/Sub/serverApp/index.js',
  '{"devices":{"android":18,"cancel":1}}' ]

JSON { devices: { android: 18, cancel: 1 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
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
E/ActivityThread( 1575): Failed to find provider info for com.samsung.helphub.provider
W/ActivityManager( 1195): Unable to start service Intent { cmp=com.samsung.android.app.gestureservice/.GestureService } U=0: not found
W/ActivityManager( 1195): !@call fb1: post finishBooting() with 1000msec delay
I/ActivityManager( 1195): !@Boot: bootcomplete
W/ActivityThread( 3222): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityThread( 3250): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityManager( 1195): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
I/ActivityManager( 1195): Killing 2739:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2768:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 1597:com.android.printspooler/u0a118 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2721:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2899:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2914:com.samsung.android.app.memo/u0a130 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2929:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3015:com.sec.phone/u0a127 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3094:com.google.android.configupdater/u0a2 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3119:com.sec.android.widgetapp.samsungapps/u0a120 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3189:com.sec.dsm.system/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3222:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3250:com.sec.factory/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3281:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3311:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 1491:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3332:com.android.onetimeinitializer/u0a21 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3347:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3387:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3434:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3448:com.osp.app.signin/u0a30 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2942:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
W/ActivityManager( 1195): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1195): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1195): Killing 3478:com.android.chrome/u0a73 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{42759410 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{4271d310 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
W/ActivityThread( 1195): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{41e883f8 u0 com.samsung.android.providers.context/.ContextService}
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{42814440 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{428c6d00 u0 com.sec.esdk.elm/.service.ElmAgentService}
I/ActivityManager( 1195): Killing 2599:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 1641:com.android.settings/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3525:com.wssyncmldm/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3462:com.sec.android.gallery3d/u0a33 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 2561:com.google.android.partnersetup/u0a11 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3562:com.google.android.googlequicksearchbox:search/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3599:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3585:com.samsung.android.intelligenceservice/u0a52 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3613:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3627:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3641:com.wssnps/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Process com.samsung.android.MtpApplication (pid 4329) (adj 0) has died.
I/ActivityManager( 1195): Killing 3654:com.samsung.android.app.accesscontrol/u0a57 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3689:com.sec.android.nearby.mediaserver/u0a63 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3702:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3715:com.sec.android.app.bluetoothtest/1000 (adj 15): bgCount ##33
W/ActivityManager( 1195): mDVFSHelper.acquire()
I/ActivityManager( 1195): Killing 3728:com.blurb.checkout/u0a67 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3741:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3754:com.dropbox.android/u0a78 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3795:com.sec.factory.camera/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3809:com.samsung.android.app.watchmanagerstub/u0a86 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3824:com.google.android.gm/u0a87 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3854:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3889:com.samsung.scrc.idi.server/u0a91 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3903:com.samsung.helphub/1000 (adj 15): bgCount ##33
W/ActivityManager( 1195): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
I/ActivityManager( 1195): Killing 3916:com.LocalFota/u0a92 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3932:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3947:com.sec.android.app.music:service/u0a105 (adj 15): bgCount ##33
W/ActivityManager( 1195): mDVFSHelper.release()
I/ActivityManager( 1195): Killing 3961:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3985:com.sec.android.app.camera/u0a121 (adj 15): bgCount ##33
W/ActivityThread( 4316): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityManager( 1195): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
I/ActivityManager( 1195): Killing 1773:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4042:com.android.exchange/u0a126 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4216:com.gameloft.android.gdc:remote/u0a152 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4267:com.android.vending/u0a24 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 3674:com.sec.android.app.FileShareServer/u0a62 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4435:com.samsung.shareshot/u0a137 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4499:com.sec.spp.push:RemoteNotiProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4482:com.sec.spp.push:RemoteDlcProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4513:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4532:com.sec.android.cloudagent/u0a1 (adj 15): bgCount ##33
I/ActivityManager( 1195): Process com.sec.android.app.sysscope (pid 4112) (adj 0) has died.
I/ActivityManager( 1195): Killing 4449:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4468:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4603:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4617:com.google.android.apps.magazines/u0a93 (adj 15): bgCount ##33
I/ActivityManager( 1195): Process com.sec.factory (pid 4316) (adj 0) has died.
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{4286fa68 u0 com.rxnetworks.rxnservicesxybrid/com.rxnetworks.rxnserviceslib.RXNetworksService}
I/ActivityManager( 1195): Killing 3999:com.android.email/u0a125 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4139:com.samsung.android.service.travel/u0a143 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4152:com.google.android.youtube/u0a146 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4550:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4563:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4715:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4079:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4097:com.sec.android.app.worldclock/u0a135 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4125:com.sec.android.app.controlpanel/u0a141 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4754:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4902:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4920:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1195): Waited long enough for: ServiceRecord{42ddcc20 u0 com.samsung.android.MtpApplication/.MtpService}
I/ActivityManager( 1195): Killing 4956:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
,--------- beginning of /dev/log/main
W/ActivityManager( 1195): mDVFSHelper.acquire()
W/ActivityManager( 1195): mDVFSHelper.release()
W/jxcore-log( 5387): Initializing JXcore engine
W/jxcore-log( 5387): JXcore engine is ready
W/jxcore-log( 5387): Starting JXcore engine
W/jxcore-log( 5387): Platform android
W/jxcore-log( 5387): 
W/jxcore-log( 5387): Process ARCH arm
W/jxcore-log( 5387): 
I/jxcore-log( 5387): JXcore Cordova bridge is ready!
I/jxcore-log( 5387): 
W/jxcore-log( 5387): JXcore engine is started
,E/jxcore-log( 5387): >> samsung-SM-T232
E/jxcore-log( 5387): 
I/jxcore-log( 5387): Total memory 1352024064
I/jxcore-log( 5387): 
I/jxcore-log( 5387): Free memory 136867840
I/jxcore-log( 5387): 
I/jxcore-log( 5387): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5387): 
I/jxcore-log( 5387): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5387): 
I/jxcore-log( 5387): userPath [ 'www' ]
I/jxcore-log( 5387): 
I/jxcore-log( 5387): Size 800 1280
I/jxcore-log( 5387): 
I/jxcore-log( 5387): Screen Brightness 143
I/jxcore-log( 5387): 
E/jxcore-log( 5387): Dummy Error Log.
E/jxcore-log( 5387): 
I/jxcore-log( 5387): getBuffer is called!!!!
I/jxcore-log( 5387): 
,I/jxcore-log( 5387): Bluetooth turned on
I/jxcore-log( 5387): 
,I/jxcore-log( 5387): WiFi turned off
I/jxcore-log( 5387): 
,W/ActivityManager( 1195): Permission Denial: getCurrentUser() from pid=5387, uid=10357 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 5387): WiFi turned on
I/jxcore-log( 5387): 
,I/ActivityManager( 1195): Killing 4993:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
,I/ActivityManager( 1195): Killing 4369:com.sec.android.widgetapp.SPlannerAppWidget/u0a34 (adj 15): bgCount ##33
,I/ActivityManager( 1195): Killing 4385:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
,I/ActivityManager( 1195): Killing 4398:com.android.calendar/u0a117 (adj 15): bgCount ##33
,I/jxcore-log( 5387): No internet connection
I/jxcore-log( 5387): 
,I/ActivityManager( 1195): Killing 4970:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
,I/ActivityManager( 1195): Killing 4864:com.sec.phone/u0a127 (adj 15): bgCount ##33
,I/ActivityManager( 1195): Killing 4887:com.google.android.gm/u0a87 (adj 15): bgCount ##33
,I/jxcore-log( 5387): No internet connection
I/jxcore-log( 5387): 
,W/ActivityManager( 1195): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 1195): Killing 4845:com.sec.android.app.music:service/u0a105 (adj 15): bgCount ##33
I/ActivityManager( 1195): Killing 4826:com.sec.android.app.myfiles/u0a37 (adj 15): bgCount ##33
,I/ActivityManager( 1195): Killing 5143:com.wssyncmldm/1000 (adj 15): bgCount ##33
,I/jxcore-log( 5387): No internet connection
I/jxcore-log( 5387): 
,I/ActivityManager( 1195): Killing 4732:com.google.android.music:main/u0a103 (adj 15): bgCount ##33
,I/jxcore-log( 5387): No internet connection
I/jxcore-log( 5387): 
,I/jxcore-log( 5387): No internet connection
I/jxcore-log( 5387): 
,I/jxcore-log( 5387): WiFi
I/jxcore-log( 5387): 
,I/jxcore-log( 5387): Response status code was: 200
I/jxcore-log( 5387): 
I/jxcore-log( 5387): ****TEST TOOK:  11419  ms ****
I/jxcore-log( 5387): 
,I/jxcore-log( 5387): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5387): 
,I/ActivityManager( 1195): Killing 5387:com.example.hello/u0a357 (adj 0): stop com.example.hello


samsung-SM-G920F: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager( 3486): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3486): mDVFSHelper.acquire()
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3486): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10571 uid=10445 gids={50445, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 4256): updateVisibility : ActivityRecord{3b814473 token=android.os.BinderProxy@3f82f634 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
D/ActivityThread(10571): Added TimaKeyStore provider
V/ActivityManager( 3486): Display changed displayId=0
V/ActivityThread( 4256): updateVisibility : ActivityRecord{3b814473 token=android.os.BinderProxy@3f82f634 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
D/ActivityManager( 3486): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/ActivityManager( 3486): Displayed Component not be shown by security: +546ms
W/ActivityManager( 3486): mDVFSHelper.release()
W/jxcore-log(10571): Initializing JXcore engine
W/jxcore-log(10571): JXcore engine is ready
W/jxcore-log(10571): Starting JXcore engine
,W/jxcore-log(10571): Platform android
W/jxcore-log(10571): 
W/jxcore-log(10571): Process ARCH arm
W/jxcore-log(10571): 
I/jxcore-log(10571): JXcore Cordova bridge is ready!
I/jxcore-log(10571): 
W/jxcore-log(10571): JXcore engine is started
E/jxcore-log(10571): >> samsung-SM-G920F
E/jxcore-log(10571): 
I/jxcore-log(10571): Total memory 2829074432
I/jxcore-log(10571): 
I/jxcore-log(10571): Free memory 49467392
I/jxcore-log(10571): 
I/jxcore-log(10571): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10571): 
I/jxcore-log(10571): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10571): 
I/jxcore-log(10571): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10571): 
I/jxcore-log(10571): Size 1440 2560
I/jxcore-log(10571): 
I/jxcore-log(10571): Screen Brightness 134
I/jxcore-log(10571): 
E/jxcore-log(10571): Dummy Error Log.
E/jxcore-log(10571): 
I/jxcore-log(10571): getBuffer is called!!!!
I/jxcore-log(10571): 
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.cache.CacheBootstrapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/ActivityManager( 3486): do not start freezing screen for locked container getKeyguardshowstate = false
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 3486): mDVFSHelper.acquire()
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/ActivityThread(10571): updateVisibility : ActivityRecord{22dec527 token=android.os.BinderProxy@160ebc41 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
,W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/ActivityThread(10571): updateVisibility : ActivityRecord{22dec527 token=android.os.BinderProxy@160ebc41 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/ActivityManager( 3486): Display changed displayId=0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log(10571): Bluetooth turned on
I/jxcore-log(10571): 
,I/jxcore-log(10571): WiFi turned off
I/jxcore-log(10571): 
,W/ActivityManager( 3486): Permission Denial: getCurrentUser() from pid=10571, uid=10445 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log(10571): WiFi turned on
I/jxcore-log(10571): 
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.android.settings for broadcast com.android.settings/.wifi.connectionhandler.WifiIntentReciever: pid=10661 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityThread(10661): Added TimaKeyStore provider
,I/ActivityManager( 3486): Killing 10121:com.sec.pcw.device/1000 (adj 15): empty #25
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3486): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=10695 uid=10078 gids={50078, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityThread(10695): Added TimaKeyStore provider
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10710 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3486): Killing 9621:com.samsung.android.app.galaxyfinder/u0a27 (adj 15): empty #25
,D/ActivityThread(10710): Added TimaKeyStore provider
,I/ActivityManager( 3486): Killing 10137:com.osp.app.signin/u0a37 (adj 15): empty #25
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.vodafone.smhs, destAppInfo.processName = com.vodafone.smhs
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.SnippetsWidgetService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.vodafone.smhs/com.vodafone.smhs.appwidget.DashboardsWidgetService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=10725 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityThread(10725): Added TimaKeyStore provider
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=10741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityThread(10741): Added TimaKeyStore provider
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 3486): Killing 9902:com.android.mms/u0a48 (adj 15): empty #25
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10757 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityThread(10757): Added TimaKeyStore provider
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=10774 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 10048:com.samsung.android.sm/1000 (adj 15): empty #25
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(10774): Added TimaKeyStore provider
,I/ActivityManager( 3486): Start proc com.samsung.android.coreapps for broadcast com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener: pid=10789 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(10789): Added TimaKeyStore provider
,I/ActivityManager( 3486): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=10805 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityThread(10805): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.AutoUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.ManualUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.ModalUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.AsyncMoveService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
,I/ActivityManager( 3486): Killing 10158:com.sec.android.app.soundalive/u0a54 (adj 15): empty #25
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.themestore for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver: pid=10857 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,W/ActivityThread(10774): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/ActivityThread(10857): Added TimaKeyStore provider
,I/ActivityManager( 3486): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=10872 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 10240:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #25
,D/ActivityThread(10872): Added TimaKeyStore provider
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=10895 uid=10114 gids={50114, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 3486): Killing 10263:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #25
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityThread(10895): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.PushClientService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.weather.widget.easywidget.EasyWeatherAppWidget: pid=10912 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 10278:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #25
,D/ActivityThread(10912): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=10932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.samsung.android.themecenter/com.samsung.android.thememanager.ThemeManagerService; callingUser = 0; userId(target) = 0
,D/ActivityThread(10932): Added TimaKeyStore provider
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.samsung.android.themecenter
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/jxcore-log(10571): No internet connection
I/jxcore-log(10571): 
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3486): Killing 10295:com.sec.android.widgetapp.samsungapps/u0a110 (adj 15): empty #25
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.drivelink.stub for broadcast com.samsung.android.drivelink.stub/.receiver.WifiStateReceiver: pid=10956 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 10311:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): empty #25
D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityThread(10956): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3486): Killing 10343:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #25
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=10975 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(10975): Added TimaKeyStore provider
,I/ActivityManager( 3486): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=10987 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 10359:com.sec.android.app.vepreload/u0a170 (adj 15): empty #25
,D/ActivityThread(10987): Added TimaKeyStore provider
,I/ActivityManager( 3486): Killing 10391:com.sec.spp.push:RemoteNotiProcess/u0a33 (adj 15): empty #25
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11013 uid=10032 gids={50032, 9997, 3003} abi=arm64-v8a
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityThread(11013): Added TimaKeyStore provider
,I/ActivityManager( 3486): Killing 10410:com.google.android.apps.docs/u0a102 (adj 15): empty #25
,I/ActivityManager( 3486): Killing 10472:com.sec.android.app.shealth/u0a28 (adj 15): empty #25
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 3486): mDVFSHelper.release()
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=11076 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 9951:com.android.defcontainer/u0a3 (adj 15): empty #25
,D/ActivityThread(11076): Added TimaKeyStore provider
,I/ActivityManager( 3486): Killing 10495:com.android.vending/u0a23 (adj 15): empty #25
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.SmartManagerReceiver: pid=11093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityThread(11093): Added TimaKeyStore provider
,I/ActivityManager( 3486): Killing 10695:com.samsung.android.app.FileShareClient/u0a78 (adj 15): empty #25
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.vodafone.smhs, destAppInfo.processName = com.vodafone.smhs
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.vodafone.smhs, destAppInfo.processName = com.vodafone.smhs
,I/jxcore-log(10571): No internet connection
I/jxcore-log(10571): 
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.vodafone.smhs, destAppInfo.processName = com.vodafone.smhs
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=11115 uid=10078 gids={50078, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityThread(11115): Added TimaKeyStore provider
,I/ActivityManager( 3486): Killing 10757:com.sec.pcw.device/1000 (adj 15): empty #25
,I/jxcore-log(10571): No internet connection
I/jxcore-log(10571): 
,I/jxcore-log(10571): No internet connection
I/jxcore-log(10571): 
,I/jxcore-log(10571): No internet connection
I/jxcore-log(10571): 
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11234 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,D/ActivityThread(11234): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMAliveService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/jxcore-log(10571): WiFi
I/jxcore-log(10571): 
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
,W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log(10571): Response status code was: 200
I/jxcore-log(10571): 
,I/jxcore-log(10571): ****TEST TOOK:  11234  ms ****
I/jxcore-log(10571): 
I/jxcore-log(10571): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10571): 
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.samsung.android.themestore/com.samsung.android.themestore.manager.autoSelfUpgradeService.AutoSelfUpgradeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.samsung.android.themestore, destAppInfo.processName = com.samsung.android.themestore
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.AutoUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.ManualUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
,W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.ModalUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.microsoft.skydrive/com.microsoft.skydrive.upload.AsyncMoveService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.microsoft.skydrive
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3486): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3486): Force stopping com.example.hello appid=10445 user=-1: uninstall pkg
,I/ActivityManager( 3486): Killing 10571:com.example.hello/u0a445 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3486):   Force finishing activity ActivityRecord{ce4e031 u0 com.example.hello/.MainActivity t43}
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 3486): Force stopping com.example.hello appid=10445 user=0: pkg removed
,I/ActivityManager( 3486):   Force finishing activity ActivityRecord{ce4e031 u0 com.example.hello/.MainActivity t43 f}
,W/ActivityManager( 3486): Duplicate finish request for ActivityRecord{ce4e031 u0 com.example.hello/.MainActivity t43 f}
,W/ActivityManager( 3486): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5372, uid=10127 that is not exported from uid 10125
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=11304 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
,W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
,W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityThread(11304): Added TimaKeyStore provider
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3486): Killing 11115:com.samsung.android.app.FileShareClient/u0a78 (adj 15): empty #25
,I/ActivityManager( 3486): Killing 10710:com.samsung.android.app.FileShareServer/u0a79 (adj 15): empty #25
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11323 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,D/ActivityThread(11323): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=11340 uid=10027 gids={50027, 9997, 1028, 1015, 3003, 3002} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 10661:com.android.settings/1000 (adj 15): empty #25
,D/ActivityThread(11340): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 3486): Killing 8945:com.samsung.android.SettingsReceiver/1000 (adj 15): empty #25
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
,W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=11362 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 1023, 1003} abi=arm64-v8a
,D/ActivityThread(11362): Added TimaKeyStore provider
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3486): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3486): Start proc com.samsung.android.SettingsReceiver for broadcast com.samsung.android.SettingsReceiver/.SettingsIntentReceiver: pid=11388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,I/ActivityManager( 3486): Killing 10932:com.sec.android.diagmonagent/1000 (adj 15): empty #25
,I/ActivityManager( 3486): Killing 10725:com.samsung.android.keyguardwallpaperupdator/u0a118 (adj 15): empty #25
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3486): userId = 0, bbcId = -10000
W/ActivityManager( 3486): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 3486): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 3486): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1278): Start proc 9318:com.google.android.apps.magazines/u0a115 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1278): Killing 8856:com.lge.ia.task.smartsetting/u0a21 (adj 15): empty #22
W/ActivityManager( 1278): getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
E/ActivityThread( 5104): Failed to find provider info for com.google.android.wearable.settings
W/ActivityManager( 1278): getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
D/ActivityManager( 1278): enqueue in BackgroundQueue #60 Intent=Intent { act=android.content.syncmanager.SYNC_ALARM flg=0x14 (has extras) }
I/ActivityManager( 1278): Start proc 9368:com.google.android.gms.unstable/u0a6 for service com.google.android.gms/.droidguard.DroidGuardService
W/ActivityManager( 1278): getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1278): Start proc 9401:com.android.chrome/u0a101 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager( 1278): Killing 8954:com.lge.bnr/1000 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 9428:com.google.android.apps.plus/u0a122 for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver
I/ActivityManager( 1278): Killing 9018:com.lge.lifetracker/u0a137 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 9472:com.google.android.talk/u0a121 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,I/ActivityManager( 1278): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{34318794 #50 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1278): setTaskToReturnTo : TaskRecord{34318794 #50 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1278): Start proc 9536:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
I/ActivityManager( 1278): Start proc 9565:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
I/ActivityManager( 1278): Killing 9052:com.lge.lgaccount/u0a107 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 8810:com.lge.NfcSettings/1000 (adj 15): empty #22
I/ActivityManager( 1278): Killing 8997:com.lge.task/u0a20 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 9596:com.lge.sync/1000 for broadcast com.lge.sync/.StartReceiver
I/ActivityManager( 1278): Killing 8723:com.lge.wifisettings/1000 (adj 15): empty #22
I/ActivityManager( 1278): Start proc 9636:com.android.settings/1000 for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver
I/ActivityManager( 1278): Displayed com.example.hello/.MainActivity: +728ms (total +31s902ms)
I/ActivityManager( 1278): Killing 8921:com.uei.lg.quicksetsdk.irblaster/1000 (adj 15): empty #22
E/ActivityThread( 5104): Failed to find provider info for com.google.android.wearable.settings
W/ActivityManager( 1278): Scheduling restart of crashed service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service in 1000ms
I/ActivityManager( 1278): Start proc 9667:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
W/jxcore-log( 9536): Initializing JXcore engine
W/jxcore-log( 9536): JXcore engine is ready
W/jxcore-log( 9536): Starting JXcore engine
I/ActivityManager( 1278): Start proc 9690:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
W/jxcore-log( 9536): Platform android
W/jxcore-log( 9536): 
W/jxcore-log( 9536): Process ARCH arm
W/jxcore-log( 9536): 
I/jxcore-log( 9536): JXcore Cordova bridge is ready!
I/jxcore-log( 9536): 
W/jxcore-log( 9536): JXcore engine is started
I/ActivityManager( 1278): Start proc 9713:com.lge.sizechangable.weather/u0a136 for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget
E/jxcore-log( 9536): >> LGE-LG-H815
E/jxcore-log( 9536): 
I/jxcore-log( 9536): Total memory 2968948736
I/jxcore-log( 9536): 
I/jxcore-log( 9536): Free memory 86487040
I/jxcore-log( 9536): 
I/jxcore-log( 9536): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9536): 
I/jxcore-log( 9536): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9536): 
I/jxcore-log( 9536): userPath [ 'www' ]
I/jxcore-log( 9536): 
I/jxcore-log( 9536): Size 1440 2392
I/jxcore-log( 9536): 
I/jxcore-log( 9536): Screen Brightness 255
I/jxcore-log( 9536): 
E/jxcore-log( 9536): Dummy Error Log.
E/jxcore-log( 9536): 
I/ActivityManager( 1278): Killing 8879:com.lge.lockscreensettings/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 9740:com.lge.bnr/1000 for broadcast com.lge.bnr/.receiver.DamagedFileRemover
,I/ActivityManager( 1278): Killing 9089:com.google.android.music:main/u0a123 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 9764:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager( 1278): Killing 9120:com.lge.appbox.client/u0a9 (adj 15): empty #22
,I/jxcore-log( 9536): getBuffer is called!!!!
I/jxcore-log( 9536): 
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 9795:com.lge.cic.eden.service/u0a7 for broadcast com.lge.cic.eden.service/com.lge.cic.eden.receiver.EdenBroadcastReceiver
,I/ActivityManager( 1278): Killing 9144:com.lge.lgdmsclient/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 8830:com.lge.formmanager/u0a49 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 9820:com.lge.clock/u0a16 for broadcast com.lge.clock/.alarmclock.ToneMappingReceiver
,W/ActivityManager( 1278): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
,I/ActivityManager( 1278): Killing 9199:com.lge.myplace/u0a30 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 9842:com.android.gallery3d/u0a55 for broadcast com.android.gallery3d/com.lge.gallery.app.GalleryGlobalReceiver
,I/ActivityManager( 1278): Killing 9221:com.lge.exchange/u0a22 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 9170:com.lge.email/u0a56 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 9871:com.lge.myplace/u0a30 for broadcast com.lge.myplace/.Receiver
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 9894:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,I/ActivityManager( 1278): Killing 9245:com.google.android.setupwizard/u0a54 (adj 15): empty #22
,D/ActivityThread( 9894): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1278): Killing 8572:com.android.defcontainer/u0a3 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 9943:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver
,I/ActivityManager( 1278): Killing 9267:com.lge.drmservice/u0a68 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 9969:com.lge.appbox.client/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper
,I/ActivityManager( 1278): Killing 9318:com.google.android.apps.magazines/u0a115 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 9989:com.google.android.partnersetup/u0a5 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager( 1278): Killing 9401:com.android.chrome/u0a101 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10012:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
,I/ActivityManager( 1278): Killing 9428:com.google.android.apps.plus/u0a122 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10037:com.android.contacts/u0a18 for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver
,I/ActivityManager( 1278): Killing 9565:com.lge.eodengine/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10059:com.lge.exchange/u0a22 for broadcast com.lge.exchange/.receiver.PackageChangeReceiver
,I/ActivityManager( 1278): Killing 9636:com.android.settings/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10080:com.lge.email/u0a56 for content provider com.lge.email/.providers.EmailProvider
,I/ActivityManager( 1278): Killing 9596:com.lge.sync/1000 (adj 15): empty #22
,I/jxcore-log( 9536): Bluetooth turned on
I/jxcore-log( 9536): 
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 10104:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.PackageIntentReceiver
,I/ActivityManager( 1278): Killing 8899:com.lge.qremote/u0a138 (adj 15): empty #22
,I/jxcore-log( 9536): WiFi turned off
I/jxcore-log( 9536): 
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9536): WiFi turned on
I/jxcore-log( 9536): 
,I/ActivityManager( 1278): Start proc 10137:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
,I/ActivityManager( 1278): Killing 9667:com.uei.lg.quicksetsdk.irblaster/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10158:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver
,I/ActivityManager( 1278): Killing 9795:com.lge.cic.eden.service/u0a7 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10178:com.android.vending/u0a62 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,I/ActivityManager( 1278): Killing 9820:com.lge.clock/u0a16 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9536): No internet connection
I/jxcore-log( 9536): 
,I/ActivityManager( 1278): Start proc 10222:com.google.android.googlequicksearchbox:search/u0a63 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,I/ActivityManager( 1278): Start proc 10244:com.google.android.apps.plus/u0a122 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor,
,I/ActivityManager( 1278): Start proc 10271:com.google.android.gms:car/u0a6 for service com.google.android.gms/.car.CarService
,I/ActivityManager( 1278): Killing 9764:com.google.android.music:main/u0a123 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 9690:com.lge.task/u0a20 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9536): No internet connection
I/jxcore-log( 9536): 
,I/ActivityManager( 1278): Start proc 10347:com.google.android.apps.docs/u0a118 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Killing 9291:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Killing 9871:com.lge.myplace/u0a30 (adj 15): empty #23
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9536): No internet connection
I/jxcore-log( 9536): 
W/ActivityManager( 1278): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Killing 9894:com.google.android.gm/u0a113 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10405:com.lge.lifetracker/u0a137 for broadcast com.lge.lifetracker/.widgets.HealthWidgetProvider
,I/ActivityManager( 1278): Start proc 10425:com.lge.lgaccount/u0a107 for content provider com.lge.lgaccount/.provider.LGAccountProvider
,I/ActivityManager( 1278): Start proc 10447:com.lge.bioitplatform.sdservice.service/u0a4 for content provider com.lge.bioitplatform.sdservice.service/com.lge.bioitplatform.sdservice.provider.BioDataProvider
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9536): No internet connection
I/jxcore-log( 9536): 
,I/ActivityManager( 1278): Killing 9943:com.google.android.setupwizard/u0a54 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 9713:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 9368:com.google.android.gms.unstable/u0a6 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10471:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
,I/ActivityManager( 1278): Start proc 10498:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9536): No internet connection
I/jxcore-log( 9536): 
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1278): Start proc 10533:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
,I/ActivityManager( 1278): Start proc 10560:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver
,I/ActivityManager( 1278): Killing 9989:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
I/jxcore-log( 9536): No internet connection
I/jxcore-log( 9536): 
,I/ActivityManager( 1278): Killing 9740:com.lge.bnr/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10593:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,D/ActivityThread(10593): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1278): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1278): Killing 10012:com.lge.formmanager/u0a49 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10660:com.lge.wifisettings/1000 for broadcast com.lge.wifisettings/.wifioffload.WiFiOffLoadBroadcast
,I/ActivityManager( 1278): Start proc 10681:com.lge.qremote/u0a138 for broadcast com.lge.qremote/.settings.WiFiStateReceiver
,I/ActivityManager( 1278): Killing 10059:com.lge.exchange/u0a22 (adj 15): empty #22
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1278): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9536): WiFi
I/jxcore-log( 9536): 
,I/ActivityManager( 1278): Start proc 10712:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
,I/ActivityManager( 1278): Killing 10080:com.lge.email/u0a56 (adj 15): empty #22
,I/jxcore-log( 9536): Response status code was: 200
I/jxcore-log( 9536): 
I/jxcore-log( 9536): ****TEST TOOK:  13192  ms ****
I/jxcore-log( 9536): 
I/jxcore-log( 9536): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9536): 
,I/ActivityManager( 1278): Start proc 10756:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
,I/ActivityManager( 1278): Start proc 10795:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
,I/ActivityManager( 1278): Start proc 10832:com.lge.lgdmsclient/1000 for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver
,I/ActivityManager( 1278): Killing 10137:com.lge.NfcSettings/1000 (adj 15): empty #22
,I/ActivityManager( 1278): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
I/ActivityManager( 1278): Killing 9536:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1278): Force removing ActivityRecord{de023d u0 com.example.hello/.MainActivity t50}: app died, no saved state
,I/ActivityManager( 1278): Force stopping com.example.hello appid=10360 user=0: pkg removed
,W/ActivityManager( 1278): Spurious death for ProcessRecord{3de0876f 9536:com.example.hello/u0a360}, curProc for 9536: null
,I/ActivityManager( 1278): Killing 10158:com.lge.eula/u0a105 (adj 15): empty #22
,I/ActivityManager( 1278): Killing 10347:com.google.android.apps.docs/u0a118 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10864:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1278): Killing 10037:com.android.contacts/u0a18 (adj 15): empty #22
,I/ActivityManager( 1278): Start proc 10885:com.lge.email/u0a56 for broadcast com.lge.email/.adapter.event.receiver.EmailEngineReceiver


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.INITIALIZE
I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2934): filter receiver for action = com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION
,I/ActivityManager( 2934): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/ActivityManager( 2934): filter receiver for action = com.google.android.gm.intent.ACTION_PROVIDER_CREATED
,I/ActivityManager( 2934): Displayed com.example.hello/.MainActivity: +1s221ms
,W/jxcore-log( 6121): Initializing JXcore engine
W/jxcore-log( 6121): JXcore engine is ready
,W/jxcore-log( 6121): Starting JXcore engine
,I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,W/jxcore-log( 6121): Platform android
W/jxcore-log( 6121): 
W/jxcore-log( 6121): Process ARCH arm
W/jxcore-log( 6121): 
,I/jxcore-log( 6121): JXcore Cordova bridge is ready!
I/jxcore-log( 6121): 
W/jxcore-log( 6121): JXcore engine is started
,E/jxcore-log( 6121): >> HUAWEI-ALE-L21
E/jxcore-log( 6121): 
,I/jxcore-log( 6121): Total memory 1949741056
I/jxcore-log( 6121): 
I/jxcore-log( 6121): Free memory 17960960
I/jxcore-log( 6121): 
I/jxcore-log( 6121): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6121): 
I/jxcore-log( 6121): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): userPath [ 'www' ]
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): Size 720 1184
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): Screen Brightness 242
I/jxcore-log( 6121): 
,E/jxcore-log( 6121): Dummy Error Log.
E/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
,I/ActivityManager( 2934): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/jxcore-log( 6121): getBuffer is called!!!!
I/jxcore-log( 6121): 
I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2934): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2934): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/ActivityManager( 2934): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2934): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/jxcore-log( 6121): Bluetooth turned on
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): WiFi turned off
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/jxcore-log( 6121): WiFi turned on
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager( 2934): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/jxcore-log( 6121): No internet connection
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/jxcore-log( 6121): No internet connection
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.p2p.THIS_DEVICE_CHANGED
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.SCAN_RESULTS
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 6121): No internet connection
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/jxcore-log( 6121): No internet connection
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = android.intent.action.PACKAGE_CHANGED
,I/jxcore-log( 6121): No internet connection
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2934): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/jxcore-log( 6121): No internet connection
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): WiFi
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): Response status code was: 200
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): ****TEST TOOK:  12479  ms ****
I/jxcore-log( 6121): 
I/jxcore-log( 6121): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6121): 
,I/ActivityManager( 2934): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2934): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED


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
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3056 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +715ms (total +35s11ms)
,W/jxcore-log( 3056): Initializing JXcore engine
,W/jxcore-log( 3056): JXcore engine is ready
,W/jxcore-log( 3056): Starting JXcore engine
,W/jxcore-log( 3056): Platform android
W/jxcore-log( 3056): 
,W/jxcore-log( 3056): Process ARCH arm
W/jxcore-log( 3056): 
,I/jxcore-log( 3056): JXcore Cordova bridge is ready!
I/jxcore-log( 3056): 
W/jxcore-log( 3056): JXcore engine is started
,E/jxcore-log( 3056): >> LGE-Nexus 5
E/jxcore-log( 3056): 
,I/jxcore-log( 3056): Total memory 1946181632
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): Free memory 289001472
I/jxcore-log( 3056): 
I/jxcore-log( 3056): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3056): 
I/jxcore-log( 3056): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): userPath [ 'www' ]
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): Size 1080 1776
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): Screen Brightness 82
I/jxcore-log( 3056): 
,E/jxcore-log( 3056): Dummy Error Log.
E/jxcore-log( 3056): 
,I/jxcore-log( 3056): getBuffer is called!!!!
I/jxcore-log( 3056): 
,V/ActivityManager(  760): Display changed displayId=0
,I/jxcore-log( 3056): Bluetooth turned on
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): WiFi turned off
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): WiFi turned on
I/jxcore-log( 3056): 
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3212 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2513:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/jxcore-log( 3056): No internet connection
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): No internet connection
I/jxcore-log( 3056): 
,I/ActivityManager(  760): Killing 2719:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/ActivityManager(  760): Killing 2599:com.google.android.youtube/u0a80 (adj 15): empty #18
,I/jxcore-log( 3056): No internet connection
I/jxcore-log( 3056): 
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3286 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2701:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/jxcore-log( 3056): No internet connection
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): WiFi
I/jxcore-log( 3056): 
,I/jxcore-log( 3056): Response status code was: 200
I/jxcore-log( 3056): 
I/jxcore-log( 3056): ****TEST TOOK:  10493  ms ****
I/jxcore-log( 3056): 
I/jxcore-log( 3056): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3056): 
,I/ActivityManager(  760): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3444 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3056:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{218aecce u0 com.example.hello/.MainActivity t214}
,V/ActivityManager(  760): Display changed displayId=0
,I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=0: pkg removed
I/ActivityManager(  760):   Force finishing activity ActivityRecord{218aecce u0 com.example.hello/.MainActivity t214 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{218aecce u0 com.example.hello/.MainActivity t214 f}
,W/ActivityManager(  760): Spurious death for ProcessRecord{333a59b0 3056:com.example.hello/u0a277}, curProc for 3056: null
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3470 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,W/ActivityThread( 3444): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3504 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3530 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,--------- beginning of crash


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  853): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3192 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 3002} abi=armeabi-v7a
I/ActivityManager(  853): Killing 1911:com.android.printspooler/u0a87 (adj 15): empty #11
,E/ActivityThread( 3192): Failed to find provider info for com.lge.ims.rcs
E/ActivityThread( 3192): Failed to find provider info for com.lge.ims.rcs
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2e59c11f #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{2e59c11f #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  853): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3232 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3259 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
W/ActivityManager(  853): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
I/ActivityManager(  853): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=3303 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 3192): Failed to find provider info for com.lge.ims.provider.uc
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=3338 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2527:com.lge.qremote/u0a106 (adj 15): empty #11
,I/ActivityManager(  853): Killing 2814:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/ActivityManager(  853): Displayed com.example.hello/.MainActivity: +1s424ms
,I/ActivityManager(  853): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3370 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  853): Killing 2944:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3003:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3070:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver: pid=3401 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/jxcore-log( 3232): Initializing JXcore engine
W/jxcore-log( 3232): JXcore engine is ready
,W/jxcore-log( 3232): Starting JXcore engine
,W/jxcore-log( 3232): Platform android
W/jxcore-log( 3232): 
W/jxcore-log( 3232): Process ARCH arm
W/jxcore-log( 3232): 
,I/ActivityManager(  853): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.wcdma_only.log_service.FactorySIMReceiver: pid=3436 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3091:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/jxcore-log( 3232): JXcore Cordova bridge is ready!
I/jxcore-log( 3232): 
W/jxcore-log( 3232): JXcore engine is started
,W/ActivityManager(  853): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
,E/jxcore-log( 3232): >> LGE-LG-D722
E/jxcore-log( 3232): 
,I/jxcore-log( 3232): Total memory 906309632
I/jxcore-log( 3232): 
I/jxcore-log( 3232): Free memory 25006080
I/jxcore-log( 3232): 
I/jxcore-log( 3232): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3232): 
I/jxcore-log( 3232): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3232): 
I/jxcore-log( 3232): userPath [ 'www' ]
I/jxcore-log( 3232): 
I/jxcore-log( 3232): Size 720 1196
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Screen Brightness 255
I/jxcore-log( 3232): 
E/jxcore-log( 3232): Dummy Error Log.
E/jxcore-log( 3232): 
,I/ActivityManager(  853): Start proc com.android.providers.partnerbookmarks for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver: pid=3461 uid=10071 gids={50071, 9997} abi=armeabi-v7a
I/ActivityManager(  853): Killing 3124:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3480 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3144:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3163:com.android.browser/u0a12 (adj 15): empty #11
I/jxcore-log( 3232): getBuffer is called!!!!
I/jxcore-log( 3232): 
,I/ActivityManager(  853): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3519 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=3541 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3578 uid=10008 gids={50008, 9997} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3022:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3259:com.lge.clock/u0a10 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3606 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3303:com.android.calendar/u0a13 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=3633 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.ui.widget.EmailWidgetProvider: pid=3653 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3370:com.qualcomm.timeservice/1000 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3461:com.android.providers.partnerbookmarks/u0a71 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=3690 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3480:com.lge.eula/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3723 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3401:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3757 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3519:com.android.keychain/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3783 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Waited long enough for: ServiceRecord{27ee847 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3805 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2421:com.android.defcontainer/u0a4 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3830 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3436:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3847 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3541:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3578:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3869 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3606:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3895 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3653:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3921 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 2265:com.google.android.gms/u0a6 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3947 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/jxcore-log( 3232): Bluetooth turned on
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): WiFi turned off
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): WiFi turned on
I/jxcore-log( 3232): 
,I/ActivityManager(  853): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3973 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3633:com.lge.settings.easy/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3992 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 3723:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3757:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4010 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3783:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4032 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4050 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3805:com.lge.clock/u0a10 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4068 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/jxcore-log( 3232): No internet connection
I/jxcore-log( 3232): 
,I/ActivityManager(  853): Killing 3830:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3847:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4087 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  853): Process com.lge.defaultaccount (pid 4032) has died
,I/ActivityManager(  853): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4106 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4123 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4140 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  853): Killing 3338:com.android.settings/1000 (adj 15): empty #11
,I/jxcore-log( 3232): No internet connection
I/jxcore-log( 3232): 
,I/ActivityManager(  853): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4172 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 3895:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,I/ActivityManager(  853): Killing 3921:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,I/ActivityManager(  853): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=4192 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  853): Waited long enough for: ServiceRecord{5ef1e92 u0 com.google.android.gms/.gcm.GcmService}
,W/ActivityThread( 4192): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 3232): WiFi
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Response status code was: 200
I/jxcore-log( 3232): 
I/jxcore-log( 3232): ****TEST TOOK:  8276  ms ****
I/jxcore-log( 3232): 
I/jxcore-log( 3232): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3232): 
,I/ActivityManager(  853): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  853): Killing 3232:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  853): Force removing ActivityRecord{1208dc6c u0 com.example.hello/.MainActivity t217}: app died, no saved state
,I/ActivityManager(  853): Force stopping com.example.hello appid=10030 user=0: pkg removed
,W/ActivityManager(  853): Spurious death for ProcessRecord{3b563757 3232:com.example.hello/u0a30}, curProc for 3232: null
,I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4331 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,--------- beginning of crash


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
W/ActivityManager( 2419): mDVFSHelper.acquire()
D/ActivityThread( 6869): Added TimaKesytore provider
,W/ActivityManager( 2419): mDVFSHelper.release()
,W/jxcore-log( 6869): Initializing JXcore engine
,W/jxcore-log( 6869): JXcore engine is ready
,W/jxcore-log( 6869): Starting JXcore engine
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
I/jxcore-log( 6869): Free memory 31633408
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
,I/jxcore-log( 6869): Bluetooth turned on,
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): WiFi turned off,
I/jxcore-log( 6869): 
,W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=6869, uid=10408 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 6869): WiFi turned on,
I/jxcore-log( 6869): 
,D/ActivityThread( 6969): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6370:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/jxcore-log( 6869): No internet connection
I/jxcore-log( 6869): 
,D/ActivityThread( 7003): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6273:com.sec.phone/1001 (adj 15): empty #43
,D/ActivityThread( 7015): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6438:com.google.android.partnersetup/u0a14 (adj 15): empty #43
I/jxcore-log( 6869): No internet connection
I/jxcore-log( 6869): 
D/ActivityThread( 7027): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 6464:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/ActivityThread( 7042): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 6477:com.android.musicfx/u0a24 (adj 15): empty #43
,D/ActivityThread( 7059): Added TimaKesytore provider
,I/jxcore-log( 6869): No internet connection
I/jxcore-log( 6869): 
,I/ActivityManager( 2419): Killing 6505:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/ActivityThread( 7099): Added TimaKesytore provider
,I/jxcore-log( 6869): No internet connection
I/jxcore-log( 6869): 
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2419): Killing 6069:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/ActivityThread( 7123): Added TimaKesytore provider,
,I/ActivityManager( 2419): Killing 5958:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/ActivityThread( 7136): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6541:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,I/ActivityManager( 2419): Killing 6342:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/jxcore-log( 6869): No internet connection
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): WiFi
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): Response status code was: 200
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): ****TEST TOOK:  11499  ms ****
I/jxcore-log( 6869): 
,I/jxcore-log( 6869): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6869): 
,D/ActivityThread( 7230): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6869:com.example.hello/u0a408 (adj 0): stop com.example.hello
,D/ActivityThread( 7256): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6568:com.sec.android.service.cm/u0a82 (adj 15): empty #43
,D/ActivityThread( 7273): Added TimaKesytore provider
,I/ActivityManager( 2419): Process com.google.process.gapps (pid 2850) (adj 0) has died.
,I/ActivityManager( 2419): Killing 6582:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/ActivityThread( 7292): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6594:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
,I/ActivityManager( 2419): Process com.sec.android.app.mss (pid 7292) (adj 9) has died.
,D/ActivityThread( 7306): Added TimaKesytore provider
,D/ActivityThread( 7321): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6607:com.samsung.helphub/1000 (adj 15): empty #43
,I/ActivityManager( 2419): Killing 6621:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,D/ActivityThread( 7335): Added TimaKesytore provider
,D/ActivityThread( 7339): Added TimaKesytore provider
,I/ActivityManager( 2419): Process com.google.process.gapps (pid 7335) (adj 0) has died.
W/ActivityManager( 2419): Service crashed 2 times, stopping: ServiceRecord{4306f260 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
,W/ActivityManager( 2419): Service crashed 2 times, stopping: ServiceRecord{4305cde8 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,W/ActivityManager( 2419): Service crashed 2 times, stopping: ServiceRecord{43041fc8 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager( 2419): Process com.sec.android.app.shealth (pid 7339) (adj 0) has died.
,D/ActivityThread( 7371): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6634:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,I/ActivityManager( 2419): Process com.samsung.android.sdk.samsunglink (pid 7371) (adj 9) has died.
,I/ActivityManager( 2419): Process com.google.android.googlequicksearchbox:search (pid 6406) (adj 5) has died.
,D/ActivityThread( 7388): Added TimaKesytore provider
,D/ActivityThread( 7401): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6647:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,D/ActivityThread( 7414): Added TimaKesytore provider
,D/ActivityThread( 7427): Added TimaKesytore provider
,D/ActivityThread( 7433): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6662:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,I/ActivityManager( 2419): Process com.google.process.gapps (pid 7427) (adj 0) has died.
,W/ActivityManager( 2419): Service crashed 2 times, stopping: ServiceRecord{4306a138 u0 com.google.android.gms/.auth.GetToken}
,D/ActivityThread( 7455): Added TimaKesytore provider
,I/ActivityManager( 2419): Process com.samsung.android.magazine.service (pid 7455) (adj 5) has died.
,D/ActivityThread( 7471): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6387:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43,


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager( 1028): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1028): setTaskToReturnTo : TaskRecord{1d56642e #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1028): setTaskToReturnTo : TaskRecord{1d56642e #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1028): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6760 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1028): Display changed displayId=0
,W/ActivityManager( 1028): Activity pause timeout for ActivityRecord{39e2dbcf u0 com.example.hello/.MainActivity t4}
,I/ActivityManager( 1028): Displayed com.example.hello/.MainActivity: +621ms (total +707ms)
,W/jxcore-log( 6760): Initializing JXcore engine
W/jxcore-log( 6760): JXcore engine is ready
,W/jxcore-log( 6760): Starting JXcore engine
,W/jxcore-log( 6760): Platform android
W/jxcore-log( 6760): 
,W/jxcore-log( 6760): Process ARCH arm
W/jxcore-log( 6760): 
,I/jxcore-log( 6760): JXcore Cordova bridge is ready!
I/jxcore-log( 6760): 
,W/jxcore-log( 6760): JXcore engine is started
,E/jxcore-log( 6760): >> LGE-LG-D855
E/jxcore-log( 6760): 
,I/jxcore-log( 6760): Total memory 2995761152
I/jxcore-log( 6760): 
I/jxcore-log( 6760): Free memory 545050624
I/jxcore-log( 6760): 
I/jxcore-log( 6760): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6760): 
I/jxcore-log( 6760): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6760): 
I/jxcore-log( 6760): userPath [ 'www' ]
I/jxcore-log( 6760): 
I/jxcore-log( 6760): Size 1440 2392
I/jxcore-log( 6760): 
I/jxcore-log( 6760): Screen Brightness 50
I/jxcore-log( 6760): 
E/jxcore-log( 6760): Dummy Error Log.
E/jxcore-log( 6760): 
I/jxcore-log( 6760): getBuffer is called!!!!
I/jxcore-log( 6760): 
,I/jxcore-log( 6760): Bluetooth turned on
I/jxcore-log( 6760): 
,I/jxcore-log( 6760): WiFi turned off
I/jxcore-log( 6760): 
,I/jxcore-log( 6760): WiFi turned on
I/jxcore-log( 6760): 
,I/ActivityManager( 1028): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6893 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1028): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6916 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1028): Killing 6178:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/ActivityManager( 1028): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6942 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1028): Killing 6382:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/ActivityManager( 1028): Killing 6206:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/jxcore-log( 6760): No internet connection
I/jxcore-log( 6760): 
,I/jxcore-log( 6760): No internet connection
I/jxcore-log( 6760): 
,I/jxcore-log( 6760): WiFi
I/jxcore-log( 6760): 
,I/ActivityManager( 1028): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7087 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/jxcore-log( 6760): Response status code was: 200
I/jxcore-log( 6760): 
,I/jxcore-log( 6760): ****TEST TOOK:  8527  ms ****
I/jxcore-log( 6760): 
I/jxcore-log( 6760): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6760): 
,I/ActivityManager( 1028): Killing 6445:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager( 1028): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7121 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1028): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1028): Killing 6760:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1028):   Force finishing activity ActivityRecord{39e2dbcf u0 com.example.hello/.MainActivity t4}
,W/ActivityManager( 1028): Spurious death for ProcessRecord{1944e713 6760:com.example.hello/u0a318}, curProc for 6760: null
I/ActivityManager( 1028): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1028):   Force finishing activity ActivityRecord{39e2dbcf u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1028): Duplicate finish request for ActivityRecord{39e2dbcf u0 com.example.hello/.MainActivity t4 f}
,I/ActivityManager( 1028): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7182 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1028): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,I/ActivityManager( 1028): Killing 6291:com.google.android.gms:car/u0a5 (adj 15): empty #17
,I/ActivityManager( 1028): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7212 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1028): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7230 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1028): Killing 5879:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager( 1028): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7248 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1028): Killing 5999:com.google.android.gms.wearable/u0a5 (adj 15): empty #17


motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3799
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3815 uid=10339 gids={50339, 3003, 3001, 3002}
,I/ActivityManager( 1020): Displayed com.example.hello/.MainActivity: +289ms (total +313ms)
,W/jxcore-log( 3815): Initializing JXcore engine
,W/jxcore-log( 3815): JXcore engine is ready
,W/jxcore-log( 3815): Starting JXcore engine
,W/jxcore-log( 3815): Platform android
W/jxcore-log( 3815): 
,W/jxcore-log( 3815): Process ARCH arm
W/jxcore-log( 3815): 
,I/jxcore-log( 3815): JXcore Cordova bridge is ready!
I/jxcore-log( 3815): 
,W/jxcore-log( 3815): JXcore engine is started
,E/jxcore-log( 3815): >> motorola-XT1039
E/jxcore-log( 3815): 
,I/jxcore-log( 3815): Total memory 893136896
I/jxcore-log( 3815): 
I/jxcore-log( 3815): Free memory 56565760
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): userPath [ 'www' ]
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): Size 720 1184
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): Screen Brightness 10
I/jxcore-log( 3815): 
,E/jxcore-log( 3815): Dummy Error Log.
E/jxcore-log( 3815): 
,I/jxcore-log( 3815): getBuffer is called!!!!
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): Bluetooth turned on
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): WiFi turned off
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): WiFi turned on
I/jxcore-log( 3815): 
,I/ActivityManager( 1020): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3888 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1020): Killing 3640:com.android.calendar/u0a7 (adj 15): empty #9
,I/jxcore-log( 3815): No internet connection
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): No internet connection
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): No internet connection
I/jxcore-log( 3815): 
,I/ActivityManager( 1020): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3944 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,E/ActivityThread( 1564): Failed to find provider info for com.motorola.blur.setupprovider
,E/ActivityThread( 1564): Failed to find provider info for com.motorola.blur.setupprovider
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3970 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3417:android.process.acore/u0a10 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3991 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 3672:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4004 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3437:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4017 uid=10076 gids={50076, 3003, 1028, 1015}
I/ActivityManager( 1020): Killing 3694:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,I/ActivityManager( 1020): Killing 3575:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/jxcore-log( 3815): No internet connection
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): No internet connection
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): No internet connection
I/jxcore-log( 3815): 
,E/ActivityThread( 1423): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4150 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/jxcore-log( 3815): WiFi
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): Response status code was: 200
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): ****TEST TOOK:  12343  ms ****
I/jxcore-log( 3815): 
,I/jxcore-log( 3815): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3815): 
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10339 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 3815:com.example.hello/u0a339 (adj 0): stop com.example.hello
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{431986d8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10339 user=0: pkg removed
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{431986d8 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1020): Duplicate finish request for ActivityRecord{431986d8 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4209 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4236 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3472:com.android.vending/u0a38 (adj 15): empty #9
,I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4251 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3888:com.android.settings/1000 (adj 15): empty #9
,I/ActivityManager( 1020): Process android.process.acore (pid 4209) has died.


```

####Node name: thali05
Console output:
```
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Device test finished on 1d6a772d 
Android task is completed 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of system
--------- beginning of main
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6520 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 6520): Added TimaKeyStore provider
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  920): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6543 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  920): Killing 5752:com.wsomacp/u0a29 (adj 15): bgCount ##41
D/ActivityThread( 6543): Added TimaKeyStore provider
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  920): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6561 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  920): Killing 5691:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
D/ActivityThread( 6561): Added TimaKeyStore provider
I/ActivityManager(  920): Killing 5776:com.sec.smartcard.manager/u0a196 (adj 15): bgCount ##41
I/ActivityManager(  920): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager(  920): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  920): mDVFSHelper.acquire()
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  920): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6587 uid=10216 gids={50216, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6587): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  920): Start proc flipboard.app for broadcast flipboard.app/flipboard.sstream.SstreamBroadcastReceiver: pid=6612 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 6612): Added TimaKeyStore provider
D/ActivityManager(  920): post active user change for 0
I/ActivityManager(  920): Displayed com.example.hello/.MainActivity: +753ms
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  920): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=6696 uid=10009 gids={50009, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  920): mDVFSHelper.release()
I/ActivityManager(  920): Killing 5901:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
D/ActivityThread( 6696): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=6715 uid=10049 gids={50049, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,D/ActivityThread( 6715): Added TimaKeyStore provider
,W/jxcore-log( 6587): Initializing JXcore engine
W/jxcore-log( 6587): JXcore engine is ready
,W/jxcore-log( 6587): Starting JXcore engine
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6734 uid=10056 gids={50056, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,D/ActivityThread( 6734): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 5949:com.sec.android.app.sns3/u0a41 (adj 15): bgCount ##41
,I/ActivityManager(  920): Killing 5978:com.sec.spp.push:RemoteDlcProcess/u0a43 (adj 15): bgCount ##41
,W/jxcore-log( 6587): Platform android
W/jxcore-log( 6587): 
W/jxcore-log( 6587): Process ARCH arm
W/jxcore-log( 6587): 
,I/jxcore-log( 6587): JXcore Cordova bridge is ready!
I/jxcore-log( 6587): 
,W/jxcore-log( 6587): JXcore engine is started
,I/ActivityManager(  920): Process com.samsung.indexservice (pid 6696)(adj 9) has died(313,1430)
,E/jxcore-log( 6587): >> samsung-SM-N9005
E/jxcore-log( 6587): 
,I/jxcore-log( 6587): Total memory 2971471872
I/jxcore-log( 6587): 
,I/jxcore-log( 6587): Free memory 327901184
I/jxcore-log( 6587): 
I/jxcore-log( 6587): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6587): 
I/jxcore-log( 6587): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6587): 
,I/jxcore-log( 6587): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6587): 
,I/jxcore-log( 6587): Size 1080 1920
I/jxcore-log( 6587): 
,I/jxcore-log( 6587): Screen Brightness 162
I/jxcore-log( 6587): 
,E/jxcore-log( 6587): Dummy Error Log.
E/jxcore-log( 6587): 
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6755): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 5997:com.sec.spp.push:RemoteNotiProcess/u0a43 (adj 15): bgCount ##41
,I/jxcore-log( 6587): getBuffer is called!!!!
I/jxcore-log( 6587): 
,I/ActivityManager(  920): Killing 6014:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/jxcore-log( 6587): Bluetooth turned on
I/jxcore-log( 6587): 
,I/jxcore-log( 6587): WiFi turned off
I/jxcore-log( 6587): 
,W/ActivityManager(  920): Permission Denial: getCurrentUser() from pid=6587, uid=10216 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 6587): WiFi turned on
I/jxcore-log( 6587): 
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6810 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/ActivityThread( 6810): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6029:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6852 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6852): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6059:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6882 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6587): No internet connection
I/jxcore-log( 6587): 
,D/ActivityThread( 6882): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6078:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6900 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6900): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6919 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6919): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 5404:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6934 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6934): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6951 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6181:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6965 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityThread( 6951): Added TimaKeyStore provider
,D/ActivityThread( 6965): Added TimaKeyStore provider
,I/jxcore-log( 6587): No internet connection
I/jxcore-log( 6587): 
,I/ActivityManager(  920): Killing 5076:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6987 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6987): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7003 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6209:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,W/ActivityThread( 6965): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 7003): Added TimaKeyStore provider
,I/ActivityManager(  920): Waited long enough for: ServiceRecord{185957ea u0 com.google.android.music/.wear.WearMetadataSyncService}
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7034 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6245:com.osp.app.signin/u0a50 (adj 15): bgCount ##41
,D/ActivityThread( 7034): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7052 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 5708:com.android.mms/u0a55 (adj 15): bgCount ##41
,D/ActivityThread( 7052): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6266:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7073 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 7073): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 5852:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7092 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6308:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,I/jxcore-log( 6587): No internet connection
I/jxcore-log( 6587): 
,D/ActivityThread( 7092): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6331:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7109 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6351:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,I/ActivityManager(  920): Waited long enough for: ServiceRecord{44f9089 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,D/ActivityThread( 7109): Added TimaKeyStore provider
,I/ActivityManager(  920): Waited long enough for: ServiceRecord{344ef4bc u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/ActivityManager(  920): Killing 6366:com.samsung.helphub/1000 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7178 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 7178): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7194 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 6419:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,D/ActivityThread( 7194): Added TimaKeyStore provider
,I/jxcore-log( 6587): No internet connection
I/jxcore-log( 6587): 
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7216 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,D/ActivityThread( 7216): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 5433:com.sec.android.app.samsungapps/u0a45 (adj 15): bgCount ##41
,I/ActivityManager(  920): Killing 6094:sstream.app/u0a25 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7237 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7237): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6162:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7260 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityManager(  920): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityThread( 7260): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6381:com.sec.android.app.controlpanel/u0a134 (adj 13): bgCount ##41
,I/jxcore-log( 6587): No internet connection
I/jxcore-log( 6587): 
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6587): WiFi
I/jxcore-log( 6587): 
,I/ActivityManager(  920): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7362 uid=10112 gids={50112, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7362): Added TimaKeyStore provider
,I/jxcore-log( 6587): Response status code was: 200
I/jxcore-log( 6587): 
,I/jxcore-log( 6587): ****TEST TOOK:  11276  ms ****
I/jxcore-log( 6587): 
I/jxcore-log( 6587): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6587): 
,W/ActivityManager(  920): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/ActivityManager(  920): Force stopping com.example.hello appid=10216 user=-1: uninstall pkg
I/ActivityManager(  920): Killing 6587:com.example.hello/u0a216 (adj 0): stop com.example.hello
,W/ActivityManager(  920): Force removing ActivityRecord{2507b93f u0 com.example.hello/.MainActivity t3}: app died, no saved state
,W/ActivityManager(  920): mDVFSHelper.acquire()
,I/ActivityManager(  920): Force stopping com.example.hello appid=10216 user=0: pkg removed
,W/ActivityManager(  920): Spurious death for ProcessRecord{7f19e55 6587:com.example.hello/u0a216}, curProc for 6587: null
,D/ActivityManager(  920): handle home activity for 0
D/ActivityManager(  920): post active user change for 0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7409 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 7409): Added TimaKeyStore provider
,W/ActivityManager(  920): mDVFSHelper.release()
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7434 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,D/ActivityThread( 7434): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 6561:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##41
,I/ActivityManager(  920): Waited long enough for: ServiceRecord{1819e8f1 u0 com.samsung.android.MtpApplication/.MtpService}
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7450 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 5832:com.sec.providers.settingsearch/u0a191 (adj 13): bgCount ##41
,D/ActivityThread( 7450): Added TimaKeyStore provider
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7498 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  920): Killing 4665:com.sec.android.app.shealth/u0a40 (adj 13): bgCount ##41
,D/ActivityThread( 7498): Added TimaKeyStore provider
,E/ActivityThread( 7498): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7516 uid=10040 gids={50040, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  920): Killing 5476:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 13): bgCount ##41
,D/ActivityThread( 7516): Added TimaKeyStore provider
,I/ActivityManager(  920): Killing 4733:com.android.calendar/u0a172 (adj 13): bgCount ##41
,E/ActivityThread( 7516): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  920): Process com.sec.android.app.shealth (pid 7516)(adj 0) has died(391,1399)
,E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  920): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  920): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7539 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a


HTC-HTC One_M8: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  896): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3308 uid=10030 gids={50030, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=armeabi-v7a
I/ActivityManager(  896): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3331 uid=10032 gids={50032, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 2987:com.htc.showme/u0a85 (adj 15): empty #17
I/ActivityManager(  896): Recipient 2987
I/ActivityManager(  896): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3348 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  896): Killing 3004:com.htc.widget.hmsproc1/u0a37 (adj 15): empty #17
I/ActivityManager(  896): Recipient 3004
I/ActivityManager(  896): Killing 3022:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
I/ActivityManager(  896): Recipient 3022
,I/ActivityManager(  896): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3367 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 3061:com.futuredial/u0a86 (adj 15): empty #17
I/ActivityManager(  896): Recipient 3061
I/ActivityManager(  896): Killing 3044:com.android.keychain/1000 (adj 15): empty #17
I/ActivityManager(  896): Recipient 3044
I/ActivityManager(  896): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3394 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 3082:com.htc.lucy/u0a64 (adj 15): empty #17
I/ActivityManager(  896): Recipient 3082
I/ActivityManager(  896): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3416 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a
I/ActivityManager(  896): Killing 3099:android.process.media/u0a17 (adj 15): empty #17
I/ActivityManager(  896): Recipient 3099
I/ActivityManager(  896): Killing 3124:com.htc.wifidisplay/u0a166 (adj 15): empty #17
I/ActivityManager(  896): Recipient 3124
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  896): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3435 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/ActivityThread( 1500): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1500): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1500): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1500): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1500): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1500): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1500): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1500): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/ActivityThread( 1500): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1500): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1500): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/ActivityThread( 1500): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
I/ActivityManager(  896): Activity reported stop, but no longer stopping: ActivityRecord{2185bbef u0 com.htc.launcher/.Launcher t26}
I/ActivityManager(  896): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3452 uid=10051 gids={50051, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 2891:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  896): Recipient 2891
,I/ActivityManager(  896): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3472 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3164:com.htc.calendar/u0a10 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3164,
,I/ActivityManager(  896): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3517 uid=10057 gids={50057, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3190:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3190,
,I/ActivityManager(  896): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3540 uid=10057 gids={50057, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3557 uid=10061 gids={50061, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
I/ActivityManager(  896): Killing 3214:com.htc.fm/u0a20 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3214
,I/ActivityManager(  896): Displayed com.example.hello/.MainActivity: +819ms
I/ActivityManager(  896): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3587 uid=10066 gids={50066, 9997, 1028, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 3233:com.fitbit.FitbitMobile/u0a23 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3233
,I/ActivityManager(  896): Start proc android.process.media for broadcast com.android.providers.media/.MediaScannerReceiver: pid=3631 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 1024} abi=armeabi-v7a,
I/ActivityManager(  896): Killing 1866:com.htc.bgp/u0a11 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 1866
,W/jxcore-log( 3435): Initializing JXcore engine,
W/jxcore-log( 3435): JXcore engine is ready
W/jxcore-log( 3435): Starting JXcore engine
,I/ActivityManager(  896): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3685 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/jxcore-log( 3435): Platform android,
W/jxcore-log( 3435): 
W/jxcore-log( 3435): Process ARCH arm,
W/jxcore-log( 3435): 
,I/jxcore-log( 3435): JXcore Cordova bridge is ready!
I/jxcore-log( 3435): 
W/jxcore-log( 3435): JXcore engine is started
,E/jxcore-log( 3435): >> HTC-HTC One_M8,
E/jxcore-log( 3435): 
,I/jxcore-log( 3435): Total memory 1912020992
I/jxcore-log( 3435): 
I/jxcore-log( 3435): Free memory 170418176
I/jxcore-log( 3435): 
I/jxcore-log( 3435): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3435): 
I/jxcore-log( 3435): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3435): 
I/jxcore-log( 3435): userPath [ 'www' ]
I/jxcore-log( 3435): 
I/jxcore-log( 3435): Size 1080 1776
I/jxcore-log( 3435): 
I/jxcore-log( 3435): Screen Brightness 142
I/jxcore-log( 3435): 
E/jxcore-log( 3435): Dummy Error Log.
E/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3720 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/jxcore-log( 3435): getBuffer is called!!!!,
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3750 uid=10079 gids={50079, 9997} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3261:com.google.android.onetimeinitializer/u0a27 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3261
,I/ActivityManager(  896): Killing 3308:com.htc.video/u0a30 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3308
,I/ActivityManager(  896): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3768 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3787 uid=10087 gids={50087, 9997, 1007, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3280:com.google.android.partnersetup/u0a28 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3280
,I/ActivityManager(  896): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3810 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a,
,I/ActivityManager(  896): Killing 3331:com.htc.csrecommend/u0a32 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3331,
,I/ActivityManager(  896): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/.BootReceiver: pid=3837 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3348:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3348,
,I/ActivityManager(  896): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3857 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.tiber2 for service com.htc.videohub.ui/com.htc.htcircontrol.HtcIrService: pid=3876 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  896): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver,
,I/ActivityManager(  896): Resuming delayed broadcast
,I/ActivityManager(  896): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3902 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  896): Killing 2698:com.htc.contacts/u0a40 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 2698,
,I/ActivityManager(  896): Killing 3367:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3367,
,I/ActivityManager(  896): Killing 2037:com.google.android.gms.wearable/u0a25 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 2037
,I/ActivityManager(  896): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3961 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a,
I/ActivityManager(  896): Killing 3394:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3394
,I/ActivityManager(  896): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3982 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  896): Killing 3416:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3416,
,I/ActivityManager(  896): Killing 3452:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3452
,I/ActivityManager(  896): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4014 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  896): Killing 3472:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3472,
,I/ActivityManager(  896): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4032 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3517:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3517,
,I/ActivityManager(  896): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4052 uid=10163 gids={50163, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 4032): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider,
,I/ActivityManager(  896): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4103 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3557:com.htc.lmw/u0a61 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3557
,I/ActivityManager(  896): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4141 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3587:com.android.managedprovisioning/u0a66 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3587,
,I/ActivityManager(  896): Killing 1950:com.google.android.gms/u0a25 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 1950,
,I/ActivityManager(  896): Killing 3720:com.htc.cs.pns/u0a74 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3720,
,I/ActivityManager(  896): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  896): Killing 3750:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3750,
,I/ActivityManager(  896): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4186 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  896): Waited long enough for: ServiceRecord{3c03e8cf u0 com.google.android.gms/.gcm.GcmService},
,I/ActivityManager(  896): Killing 3768:com.htc.showme/u0a85 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3768,
,I/jxcore-log( 3435): Bluetooth turned on
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4227 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,I/jxcore-log( 3435): WiFi turned off,
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4244 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 3435): WiFi turned on
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4283 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  896): Killing 3787:com.htc.feedback/u0a87 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3787
,W/ActivityThread( 4227): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  896): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4317 uid=10036 gids={50036, 9997, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3810:com.htc.updater/u0a88 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3810,
,I/ActivityManager(  896): Killing 3857:com.htc.android.worldclock/u0a96 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3857
,I/ActivityManager(  896): Killing 3876:com.htc.tiber2/u0a91 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3876
,W/ActivityThread( 4283): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  896): Killing 3685:com.htc.sense.mms/u0a67 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3685,
,I/jxcore-log( 3435): No internet connection,
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,I/ActivityManager(  896): Resuming delayed broadcast
,I/ActivityManager(  896): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4450 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=4491 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4515 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/jxcore-log( 3435): No internet connection
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Killing 3902:com.google.android.configupdater/u0a104 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3902
,I/ActivityManager(  896): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4544 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager(  896): Killing 3982:com.htc.backup/u0a118 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3982
,I/jxcore-log( 3435): No internet connection
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4664 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 3961:com.htc.cs.dm/u0a105 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 3961,
,I/ActivityManager(  896): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4704 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  896): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4741 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 4014:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4014
,I/ActivityManager(  896): Killing 4032:com.htc.htccupd/u0a13 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 4032
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  896): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=4780 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
W/ActivityManager(  896): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,E/ActivityThread( 4741): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@21f450da that was originally bound here,
E/ActivityThread( 4741): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@21f450da that was originally bound here
E/ActivityThread( 4741): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4741): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4741): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4741): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4741): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4741): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4741): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4741): 	at com.android.email.service.n.c(SourceFile:177)
,E/ActivityThread( 4741): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4741): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4741): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4741): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4741): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4741): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4741): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4741): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  896): Unbind failed: could not find connection for android.os.BinderProxy@fc78a64,
,I/ActivityManager(  896): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=4810 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a,
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/jxcore-log( 3435): WiFi
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4841 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/jxcore-log( 3435): Response status code was: 200
I/jxcore-log( 3435): 
I/jxcore-log( 3435): ****TEST TOOK:  9295  ms ****
I/jxcore-log( 3435): 
I/jxcore-log( 3435): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3435): 
,I/ActivityManager(  896): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4869 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
,W/ActivityThread( 4841): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  896): Killing 4103:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4103
,I/ActivityManager(  896): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4916 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 4083:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4083
,I/ActivityManager(  896): Killing 4141:com.htc.bgp/u0a11 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4141
,I/ActivityManager(  896): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4953 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  896): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4972 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  896): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
,I/ActivityManager(  896): Killing 3435:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  896): Recipient 3435,
,W/ActivityManager(  896): Force removing ActivityRecord{117c91d6 u0 com.example.hello/.MainActivity t27}: app died, no saved state,
,W/ActivityManager(  896): Spurious death for ProcessRecord{3301299f 3435:com.example.hello/u0a380}, curProc for 3435: null,
,I/ActivityManager(  896): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  896): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4997 uid=10037 gids={50037, 9997} abi=armeabi-v7a,
,I/ActivityManager(  896): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5022 uid=10079 gids={50079, 9997} abi=armeabi-v7a
I/ActivityManager(  896): Killing 4165:com.android.smith/1000 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4165,
,I/ActivityManager(  896): Killing 2944:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 2944
,I/ActivityManager(  896): Killing 4227:com.google.android.gms:car/u0a25 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 4227
,I/ActivityManager(  896): Killing 4186:com.android.vending/u0a75 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4186
,W/ActivityManager(  896): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,I/ActivityManager(  896): Killing 4317:com.htc.widget.hmsproc3/u0a36 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4317
,I/ActivityManager(  896): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5044 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a,
,I/ActivityManager(  896): Killing 3837:com.htc.videocenter/u0a91 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 3837
,I/ActivityManager(  896): Waited long enough for: ServiceRecord{294a656e u0 com.htc.autobot/.htcmodeclient.HtcModeService},
,I/ActivityManager(  896): Killing 4491:com.htc.android.mail:sync/u0a65 (adj 15): empty #17,
,I/ActivityManager(  896): Recipient 4491
,E/ActivityManager(  896): App crashed! Process: com.google.process.gapps,
I/ActivityManager(  896): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5084 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5106 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 4544:com.google.android.youtube/u0a186 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4544,
,I/ActivityManager(  896): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=5136 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,E/ActivityManager(  896): App crashed! Process: com.google.android.gms
,I/ActivityManager(  896): Cannot resolve ContentProvider=com.htc.vowifi,
E/ActivityThread( 4124): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  896): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4124): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  896): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5168 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a,
I/ActivityManager(  896): Killing 4664:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4664
,I/ActivityManager(  896): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5199 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/ActivityManager(  896): App crashed! Process: com.android.vending
,I/ActivityManager(  896): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5227 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  896): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/.TimeChangedReceiver: pid=5252 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,W/ActivityThread( 5199): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  896): Killing 4741:com.google.android.gm/u0a115 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4741
,I/ActivityManager(  896): Killing 4869:com.htc.sense.news/u0a77 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4869,
,I/ActivityManager(  896): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=5276 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 4916:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4916
,I/ActivityManager(  896): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=5294 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,E/ActivityManager(  896): App crashed! Process: com.htc.launcher
,I/ActivityManager(  896): Killing 4515:com.htc.sense.mms/u0a67 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4515
,W/ActivityManager(  896):   Force finishing activity com.htc.launcher/.Launcher,
,W/ActivityManager(  896): Can't addPackageDependency on system process
,I/ActivityManager(  896): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5318 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  896): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,E/ActivityManager(  896): App crashed! Process: com.android.settings:remote
,I/ActivityManager(  896): Killing 4972:com.htc.mobiledata/u0a48 (adj 15): empty #17
,I/ActivityManager(  896): Recipient 4972


```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of system
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
--------- beginning of main
I/ActivityManager( 1018): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5886 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 5886): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 5088:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1018): mDVFSHelper.acquire()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5927 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5927): Added TimaKeyStore provider
V/ActivityManager( 1018): Display changed displayId=0
V/ActivityThread( 1482): updateVisibility : ActivityRecord{30e05515 token=android.os.BinderProxy@19ea21ac {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{742ad8a u0 com.example.hello/.MainActivity t22}
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 5927): updateVisibility : ActivityRecord{231282b3 token=android.os.BinderProxy@47891ed {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1018): Displayed Component not be shown by security: +691ms (total +768ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
,W/jxcore-log( 5927): Initializing JXcore engine
,W/jxcore-log( 5927): JXcore engine is ready
,W/jxcore-log( 5927): Starting JXcore engine
,W/jxcore-log( 5927): Platform android
W/jxcore-log( 5927): 
W/jxcore-log( 5927): Process ARCH arm
W/jxcore-log( 5927): 
,I/jxcore-log( 5927): JXcore Cordova bridge is ready!
I/jxcore-log( 5927): 
,W/jxcore-log( 5927): JXcore engine is started
,E/jxcore-log( 5927): >> samsung-SM-A300FU
E/jxcore-log( 5927): 
,I/jxcore-log( 5927): Total memory 1451114496
I/jxcore-log( 5927): 
,I/jxcore-log( 5927): Free memory 25763840
I/jxcore-log( 5927): 
I/jxcore-log( 5927): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5927): 
I/jxcore-log( 5927): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5927): 
,I/jxcore-log( 5927): userPath [ 'www' ]
I/jxcore-log( 5927): 
,I/jxcore-log( 5927): Size 540 960
I/jxcore-log( 5927): 
,I/jxcore-log( 5927): Screen Brightness 160
I/jxcore-log( 5927): 
,E/jxcore-log( 5927): Dummy Error Log.
E/jxcore-log( 5927): 
,I/jxcore-log( 5927): getBuffer is called!!!!
I/jxcore-log( 5927): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5927): Bluetooth turned on
I/jxcore-log( 5927): 
,I/jxcore-log( 5927): WiFi turned off
I/jxcore-log( 5927): 
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5927, uid=10345 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 5927): WiFi turned on,
I/jxcore-log( 5927): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5987 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 5987): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6016 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4950:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,D/ActivityThread( 6016): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6033 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
I/ActivityManager( 1018): Killing 4468:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/ActivityThread( 6033): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/jxcore-log( 5927): No internet connection
I/jxcore-log( 5927): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6058 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 6058): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1018): Killing 5180:com.google.android.gm/u0a99 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 4178:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
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
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
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
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6078 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6078): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityThread( 6078): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6105 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 6105): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1018): Killing 5162:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/jxcore-log( 5927): No internet connection
I/jxcore-log( 5927): 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 5586:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityThread( 6124): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6140 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4729:com.android.mms/u0a41 (adj 15): empty #31,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 6140): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5601:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6157 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6157): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5257:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6174 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 6174): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6189 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5618:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,D/ActivityThread( 6189): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6218 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,D/ActivityThread( 6218): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5267:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31,
,I/ActivityManager( 1018): Killing 5685:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 5927): No internet connection
I/jxcore-log( 5927): 
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6240 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
,D/ActivityThread( 6240): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6257 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5737:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityThread( 6257): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6316 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5705:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31,
,D/ActivityThread( 6316): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5073:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/jxcore-log( 5927): No internet connection
I/jxcore-log( 5927): 
,I/jxcore-log( 5927): No internet connection
I/jxcore-log( 5927): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/jxcore-log( 5927): WiFi
I/jxcore-log( 5927): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/jxcore-log( 5927): Response status code was: 200
I/jxcore-log( 5927): 
I/jxcore-log( 5927): ****TEST TOOK:  11282  ms ****
I/jxcore-log( 5927): 
I/jxcore-log( 5927): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5927): 
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5927:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{742ad8a u0 com.example.hello/.MainActivity t22}
,W/ActivityManager( 1018): Spurious death for ProcessRecord{2636ed2a 5927:com.example.hello/u0a345}, curProc for 5927: null
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0


HTC-HTC One M8s: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  992): Killing 3782:com.android.defcontainer/u0a15 (adj 15): empty #17
I/ActivityManager(  992): Recipient 3782
I/ActivityManager(  992): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5112 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
I/ActivityManager(  992): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5146 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  992): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5110 on display 0
I/ActivityManager(  992): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5181 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,W/ActivityThread( 5146): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  992): Killing 4640:com.google.android.youtube/u0a176 (adj 15): empty #17
I/ActivityManager(  992): Recipient 4640
I/ActivityManager(  992): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5243 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  992): Killing 4722:com.google.android.gm/u0a106 (adj 15): empty #17
I/ActivityManager(  992): Recipient 4722
I/ActivityManager(  992): Killing 4803:com.google.android.partnersetup/u0a27 (adj 15): empty #17
I/ActivityManager(  992): Recipient 4803
I/ActivityManager(  992): Displayed com.example.hello/.MainActivity: +1s268ms
W/jxcore-log( 5181): Initializing JXcore engine
W/jxcore-log( 5181): JXcore engine is ready
W/jxcore-log( 5181): Starting JXcore engine
I/ActivityManager(  992): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5287 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  992): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4504): Failed to find provider info for com.google.android.wearable.settings
W/jxcore-log( 5181): Platform android
W/jxcore-log( 5181): 
W/jxcore-log( 5181): Process ARCH arm
W/jxcore-log( 5181): 
I/jxcore-log( 5181): JXcore Cordova bridge is ready!
I/jxcore-log( 5181): 
W/jxcore-log( 5181): JXcore engine is started
I/ActivityManager(  992): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5316 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
E/jxcore-log( 5181): >> HTC-HTC One M8s
E/jxcore-log( 5181): 
I/jxcore-log( 5181): Total memory 1931808768
I/jxcore-log( 5181): 
I/jxcore-log( 5181): Free memory 83550208
I/jxcore-log( 5181): 
I/jxcore-log( 5181): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5181): 
I/jxcore-log( 5181): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5181): 
I/jxcore-log( 5181): userPath [ 'www' ]
I/jxcore-log( 5181): 
I/jxcore-log( 5181): Size 1080 1776
I/jxcore-log( 5181): 
I/jxcore-log( 5181): Screen Brightness 142
I/jxcore-log( 5181): 
E/jxcore-log( 5181): Dummy Error Log.
E/jxcore-log( 5181): 
W/ActivityThread( 5316): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  992): Killing 4772:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/jxcore-log( 5181): getBuffer is called!!!!
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Recipient 4772
,I/ActivityManager(  992): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5384 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  992): Killing 4839:com.htc.club/u0a181 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 4839,
,I/ActivityManager(  992): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5416 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  992): Killing 4893:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 4893,
,I/ActivityManager(  992): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4504): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  992): Killing 4918:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 4918,
,I/ActivityManager(  992): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5447 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5475 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5502 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager(  992): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5523 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  992): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5554 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  992): Killing 4969:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 4969
,I/ActivityManager(  992): Killing 5014:com.htc.mobiledata/u0a46 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5014
,I/ActivityManager(  992): Killing 5044:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 5044
,I/ActivityManager(  992): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5587 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  992): Killing 4330:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 4330
,I/ActivityManager(  992): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5612 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5635 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  992): Killing 5081:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5081
,I/ActivityManager(  992): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5669 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5694 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
I/ActivityManager(  992): Killing 4940:com.htc.sense.news/u0a74 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 4940,
,I/ActivityManager(  992): Killing 5243:com.google.android.setupwizard/u0a77 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 5243,
,I/ActivityManager(  992): Killing 4605:com.google.android.talk/u0a112 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 4605
,I/jxcore-log( 5181): Bluetooth turned on
I/jxcore-log( 5181): 
I/ActivityManager(  992): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5717 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/jxcore-log( 5181): WiFi turned off
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5740 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
I/ActivityManager(  992): Killing 5287:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
,I/jxcore-log( 5181): WiFi turned on
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Recipient 5287
,I/ActivityManager(  992): Waited long enough for: ServiceRecord{34bf4b1e u0 com.google.android.gms/.config.ConfigFetchService},
,I/ActivityManager(  992): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5766 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5790 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5813 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  992): Killing 4867:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 4867
,I/ActivityManager(  992): Killing 5384:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5384,
,I/ActivityManager(  992): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5740): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  992): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5740): Failed to find provider info for com.htc.vowifi
,I/jxcore-log( 5181): No internet connection,
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5861 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager(  992): Killing 5416:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5416
,I/ActivityManager(  992): Killing 5447:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5447
,I/ActivityManager(  992): Killing 5475:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5475
,I/ActivityManager(  992): Killing 4992:com.htc.task/u0a69 (adj 15): empty #17,
,W/ActivityThread( 5861): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  992): Recipient 4992
,I/ActivityManager(  992): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5893 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/jxcore-log( 5181): No internet connection
I/jxcore-log( 5181): 
,W/ActivityThread( 5893): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  992): Killing 5112:com.htc.bgp/u0a11 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 5112
,I/ActivityManager(  992): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5925 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/jxcore-log( 5181): No internet connection,
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Killing 3941:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 3941
,I/ActivityManager(  992): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5971 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  992): Killing 5554:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5554
,I/ActivityManager(  992): Killing 5523:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5523,
,I/ActivityManager(  992): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6013 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,I/ActivityManager(  992): Killing 5612:com.htc.task.gtask/u0a66 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5612
,I/jxcore-log( 5181): No internet connection
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=6035 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=6059 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  992): Killing 5635:com.htc.sdm/u0a79 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5635,
,I/ActivityManager(  992): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=6093 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,I/jxcore-log( 5181): No internet connection
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6143 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6169 uid=10035 gids={50035, 9997} abi=arm64-v8a
,I/ActivityManager(  992): Killing 5669:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 5669
,I/ActivityManager(  992): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6199 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager(  992): Killing 5694:com.htc.cs.dm/u0a99 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 5694
,I/jxcore-log( 5181): No internet connection
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6254 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  992): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6280 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  992): Killing 5717:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 5717,
,W/ActivityManager(  992): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  992): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/jxcore-log( 5181): WiFi,
I/jxcore-log( 5181): 
,W/ActivityManager(  992): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,W/ActivityManager(  992): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/jxcore-log( 5181): Response status code was: 200
I/jxcore-log( 5181): 
I/jxcore-log( 5181): ****TEST TOOK:  12335  ms ****
I/jxcore-log( 5181): 
I/jxcore-log( 5181): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5181): 
,I/ActivityManager(  992): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6335 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  992): Killing 5316:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5316
,I/ActivityManager(  992): Killing 5861:com.google.android.gms:car/u0a24 (adj 15): empty #17,
,I/ActivityManager(  992): Recipient 5861,
,I/ActivityManager(  992): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=6382 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,I/ActivityManager(  992): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  992): Killing 5181:com.example.hello/u0a373 (adj 0): stop com.example.hello,
,W/ActivityManager(  992): Force removing ActivityRecord{1616aef7 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  992): Force stopping com.example.hello appid=10373 user=0: pkg removed
,I/ActivityManager(  992): Killing 5790:com.android.vending/u0a72 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5790,
,I/ActivityManager(  992): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6454 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  992): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6504 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,E/ActivityManager(  992): App crashed! Process: com.android.vending
,W/ActivityThread( 6504): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  992): Killing 5925:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 5925
,I/ActivityManager(  992): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6549 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,E/ActivityManager(  992): App crashed! Process: com.google.android.googlequicksearchbox:search
,I/ActivityManager(  992): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=6578 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  992): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=6609 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/ActivityManager(  992): Killing 6035:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  992): Recipient 6035


LGE-LG-D802: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
I/ActivityManager(  963): Delaying start of: ServiceRecord{432f7068 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ActivityManager(  963): Killing 4010:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  963): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 4551
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
V/ActivityManager(  963): Moving to PAUSING: ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  963): resumeTopActivityLocked: Pausing null
V/ActivityManager(  963): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  963): startService SlideAside
D/ActivityManager(  963): setFocusedStack: mFocusedStack=ActivityStack{4323d0b8 stackId=1, 2 tasks}
D/ActivityManager(  963): allPausedActivitiesComplete: r=ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  963): Moving to PAUSED: ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Restarting ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  963): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4569 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/ActivityManager( 4569): Timeline: Activity_idle id: android.os.BinderProxy@4282c1d8 time:47635
I/ActivityManager(  963): Displayed com.example.hello/.MainActivity: +491ms
I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3} time:47905
D/ActivityManager(  963): no-history finish of ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  963): Finishing activity token=Token{4313bb00 ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  963): Moving to FINISHING: ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  963): Moving to STOPPING: ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  963): Moving to STOPPED: ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 4569): Initializing JXcore engine
W/jxcore-log( 4569): JXcore engine is ready
W/jxcore-log( 4569): Starting JXcore engine
W/jxcore-log( 4569): Platform android
W/jxcore-log( 4569): 
W/jxcore-log( 4569): Process ARCH arm
W/jxcore-log( 4569): 
,I/jxcore-log( 4569): JXcore Cordova bridge is ready!
I/jxcore-log( 4569): 
,W/jxcore-log( 4569): JXcore engine is started
,E/jxcore-log( 4569): >> LGE-LG-D802
E/jxcore-log( 4569): 
,I/jxcore-log( 4569): Total memory 1943035904
I/jxcore-log( 4569): 
I/jxcore-log( 4569): Free memory 412110848
I/jxcore-log( 4569): 
I/jxcore-log( 4569): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): userPath [ 'www' ]
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): Size 1080 1776
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): Screen Brightness 255
I/jxcore-log( 4569): 
,E/jxcore-log( 4569): Dummy Error Log.
E/jxcore-log( 4569): 
,I/jxcore-log( 4569): getBuffer is called!!!!
I/jxcore-log( 4569): 
,I/ActivityManager(  963): Killing 3495:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Killing 4113:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Waited long enough for: ServiceRecord{432cdf68 u0 com.android.mms/.transaction.SmsReceiverService}
,I/jxcore-log( 4569): Bluetooth turned on
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): WiFi turned off
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): WiFi turned on
I/jxcore-log( 4569): 
,I/ActivityManager(  963): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4641 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  963): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4672 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  963): Killing 2091:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4697 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  963): Killing 3855:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Killing 4345:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4718 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Killing 4426:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 4569): No internet connection
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): No internet connection
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): No internet connection
I/jxcore-log( 4569): 
,I/ActivityManager(  963): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4777 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  963): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4796 uid=10052 gids={50052, 3003}
,I/ActivityManager(  963): Killing 4160:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4822 uid=10063 gids={50063, 3003, 1028, 1015}
,I/ActivityManager(  963): Killing 4176:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4838 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  963): Killing 4485:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Killing 3840:com.google.android.apps.plus/u0a112 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4853 uid=10104 gids={50104, 3003, 1028, 1015}
,I/ActivityManager(  963): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4887 uid=10112 gids={50112, 3003, 3002, 1028, 1015}
,I/ActivityManager(  963): Killing 4196:com.android.vending/u0a50 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  963): Killing 1751:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 2 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 4569): No internet connection
I/jxcore-log( 4569): 
,E/ActivityThread(  963): Failed to find provider info for com.lge.ims.provisioning
,I/jxcore-log( 4569): WiFi
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): Response status code was: 200
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): ****TEST TOOK:  10314  ms ****
I/jxcore-log( 4569): 
,I/jxcore-log( 4569): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4569): 
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  963): Killing 4569:com.example.hello/u0a311 (adj 0): stop com.example.hello
W/ActivityManager(  963): Force removing ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3 f} (removed from history)
V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{4319f7c8 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{4323d0b8 stackId=1, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  963): moveHomeStack:
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb8d30 stackId=0, 1 tasks}
,V/ActivityManager(  963): Moving to RESUMED: ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  963): resumeTopActivityLocked: Resumed ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  963): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42bb8d30 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb8d30 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  963): Moving to DESTROYING: ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,I/ActivityManager(  963): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5020 uid=10090 gids={50090}
,I/ActivityManager(  963): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5034 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,V/ActivityManager(  963): Moving to DESTROYED: ActivityRecord{4325cf38 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb8d30 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Killing 4408:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5061 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb8d30 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Killing 4796:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb8d30 stackId=0, 1 tasks}
D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Killing 4822:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  963): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5083 uid=10073 gids={50073, 3003, 1028, 1015}
,I/ActivityManager(  963): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bb8d30 stackId=0, 1 tasks}
,D/ActivityManager(  963): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  963): Timeline: Activity_windows_visible id: ActivityRecord{42c1c460 u0 com.lge.launcher2/.Launcher t1} time:59967
,I/ActivityManager( 1491): Timeline: Activity_idle id: android.os.BinderProxy@4282eff0 time:59972
,I/ActivityManager(  963): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5104 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}


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
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.app.popupuireceiver
--------- beginning of system
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=4836 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
I/ActivityManager( 1015): Killing 4093:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4836): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.samsung.android.app.powersharing
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=4855 uid=10122 gids={50122, 9997} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4207:com.wsomacp/u0a25 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4855): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.FingerprintScannerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=4880 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/ActivityThread( 4880): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 4233:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 4300:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
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
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Waited long enough for: ServiceRecord{3e264c59 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=4928 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/ActivityThread( 4928): Added TimaKeyStore provider
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4944 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 1491): updateVisibility : ActivityRecord{413ca5e token=android.os.BinderProxy@3dd8989a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 4944): Added TimaKeyStore provider
V/ActivityThread( 1491): updateVisibility : ActivityRecord{413ca5e token=android.os.BinderProxy@3dd8989a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=4966 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4251:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityThread( 4966): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
I/ActivityManager( 1015): Killing 4369:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4985 uid=10134 gids={50134, 9997} abi=armeabi-v7a
D/ActivityThread( 4985): Added TimaKeyStore provider
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5012 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4386:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/ActivityThread( 5012): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 4316:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/ActivityManager( 1015): Displayed Component not be shown by security: +930ms
,W/ActivityManager( 1015): mDVFSHelper.release()
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityThread( 5055): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5075 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ActivityThread( 3647): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 5075): Added TimaKeyStore provider
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{25b8fcb7 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,W/jxcore-log( 4944): Initializing JXcore engine
W/jxcore-log( 4944): JXcore engine is ready
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/jxcore-log( 4944): Starting JXcore engine
I/ActivityManager( 1015): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=5103 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/ActivityThread( 5103): Added TimaKeyStore provider
,D/ActivityThread( 5116): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1015): Killing 4434:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,W/jxcore-log( 4944): Platform android
W/jxcore-log( 4944): 
,W/jxcore-log( 4944): Process ARCH arm
W/jxcore-log( 4944): 
,I/jxcore-log( 4944): JXcore Cordova bridge is ready!
I/jxcore-log( 4944): 
,W/jxcore-log( 4944): JXcore engine is started
,I/ActivityManager( 1015): Killing 4164:com.android.mms/u0a46 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5139 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5139): Added TimaKeyStore provider
,E/jxcore-log( 4944): >> samsung-SM-A500FU
E/jxcore-log( 4944): 
,I/jxcore-log( 4944): Total memory 1983787008
I/jxcore-log( 4944): 
,I/jxcore-log( 4944): Free memory 42098688
I/jxcore-log( 4944): 
I/jxcore-log( 4944): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4944): 
I/jxcore-log( 4944): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4944): 
,I/jxcore-log( 4944): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4944): 
,I/jxcore-log( 4944): Size 720 1280
I/jxcore-log( 4944): 
,I/jxcore-log( 4944): Screen Brightness 255
I/jxcore-log( 4944): 
,E/jxcore-log( 4944): Dummy Error Log.
E/jxcore-log( 4944): 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5163 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5163): Added TimaKeyStore provider
,I/jxcore-log( 4944): getBuffer is called!!!!
I/jxcore-log( 4944): 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityThread( 5163): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5194 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5194): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4419:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5214 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5214): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=5230 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5230): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5247 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4447:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 5247): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1015): Killing 4467:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31,
,E/ActivityThread( 5163): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@375a58cc that was originally bound here
E/ActivityThread( 5163): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@375a58cc that was originally bound here
E/ActivityThread( 5163): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5163): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5163): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5163): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5163): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5163): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 5163): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5163): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5163): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 5163): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 5163): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 5163): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 5163): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 5163): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 5163): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 5163): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5163): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5163): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5163): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5163): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5163): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5163): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5163): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5163): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5163): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 1015): Killing 4481:com.sec.pcw.device/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 4495:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{282481ad u0 com.sec.bcservice/.BroadcastService}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1015): Killing 3898:com.policydm/1000 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5274 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 5274): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=5292 uid=10040 gids={50040, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,D/ActivityThread( 5292): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,I/ActivityManager( 1015): Killing 4579:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/ActivityManager( 1015): Process com.samsung.indexservice (pid 5274)(adj 13) has died(41,1007)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.async.BackgroundTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1015): Killing 4641:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/ActivityThread( 4944): updateVisibility : ActivityRecord{d1fc97f token=android.os.BinderProxy@2a691368 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,V/ActivityManager( 1015): Display changed displayId=0
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{2a65b1f2 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/ActivityManager( 1015): Killing 4594:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=4944, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 4944): Bluetooth turned on
I/jxcore-log( 4944): 
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5332 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 4944): WiFi turned off
I/jxcore-log( 4944): 
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=4944, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 4944): WiFi turned on
I/jxcore-log( 4944): 
,D/ActivityThread( 5332): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5367 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityThread( 5367): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4014:com.osp.app.signin/u0a41 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5400 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityThread( 5400): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4544:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5430 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5430): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5440 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4684:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/ActivityThread( 5440): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 4944): No internet connection
I/jxcore-log( 4944): 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 4704:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5503 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5503): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4836:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,I/jxcore-log( 4944): No internet connection
I/jxcore-log( 4944): 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/jxcore-log( 4944): No internet connection
I/jxcore-log( 4944): 
,I/jxcore-log( 4944): No internet connection
I/jxcore-log( 4944): 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{10be255c u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 4944): No internet connection
I/jxcore-log( 4944): 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/jxcore-log( 4944): No internet connection
I/jxcore-log( 4944): 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5573 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityThread( 5573): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=5594 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5594): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5610 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5610): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5630 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4855:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityThread( 5630): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5651 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 4944): WiFi
I/jxcore-log( 4944): 
,D/ActivityThread( 5651): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=5673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/jxcore-log( 4944): Response status code was: 200
I/jxcore-log( 4944): 
I/jxcore-log( 4944): ****TEST TOOK:  15711  ms ****
I/jxcore-log( 4944): 
I/jxcore-log( 4944): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4944): 
,D/ActivityThread( 5673): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4880:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=5717 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmReceiverService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 5717): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4928:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5769 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 4944:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,D/ActivityThread( 5769): Added TimaKeyStore provider
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{1700112f u0 com.example.hello/.MainActivity t11}
,W/ActivityManager( 1015): Spurious death for ProcessRecord{127461fc 4944:com.example.hello/u0a174}, curProc for 4944: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10174 user=0: pkg removed
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{1700112f u0 com.example.hello/.MainActivity t11 f}
W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{1700112f u0 com.example.hello/.MainActivity t11 f}
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityThread( 5673): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1015): Killing 4966:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 3499:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5075:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5830 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5103:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.fotaclient/com.sec.android.fotaclient.FotaUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.fotaclient, destAppInfo.processName = com.sec.android.fotaclient
,I/ActivityManager( 1015): Killing 5139:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ActivityThread( 5830): Added TimaKeyStore provider
,E/ActivityThread( 1830): Failed to find provider info for com.google.android.wearable.settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=5851 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5194:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/ActivityThread( 5851): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.cron.AuthCronService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=5871 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3647:com.google.android.talk/u0a104 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 5871): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=5886 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 5886): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5904 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 5904): Added TimaKeyStore provider
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{1d2b4fdd u0 com.samsung.android.MtpApplication/.MtpService}


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
W/ActivityManager(  854): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4298 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3486:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
D/ActivityThread( 4298): Added TimaKeyStore provider
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3397:com.google.android.configupdater/u0a92 (adj 15): bgCount ##41
D/ActivityThread( 4332): Added TimaKeyStore provider
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.zalando.samsung.provider for broadcast com.zalando.samsung.provider/.PreInstallReceiver: pid=4353 uid=10192 gids={50192, 9997} abi=armeabi-v7a
I/ActivityManager(  854): Process com.sec.factory (pid 3090)(adj 0) has died(24,729)
D/ActivityThread( 4353): Added TimaKeyStore provider
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3521:com.sec.android.automotive.drivelinkremote/u0a100 (adj 15): bgCount ##41
I/ActivityManager(  854): Killing 3535:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4381 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3561:com.dropbox.android/u0a101 (adj 15): bgCount ##41
D/ActivityThread( 4370): Added TimaKeyStore provider
D/ActivityThread( 4381): Added TimaKeyStore provider
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4400 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3362:tv.peel.smartremote/u0a171 (adj 15): bgCount ##41
D/ActivityThread( 4400): Added TimaKeyStore provider
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.LocalFota for broadcast com.LocalFota/.XLFBroadcastReceiver: pid=4420 uid=10120 gids={50120, 9997, 3003, 2001} abi=armeabi-v7a
I/ActivityManager(  854): Killing 2144:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
D/ActivityThread( 4420): Added TimaKeyStore provider
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3585:org.simalliance.openmobileapi.service/1101 (adj 15): bgCount ##41
D/ActivityThread( 4442): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4461 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3604:com.samsung.android.scloud.backup/u0a65 (adj 15): bgCount ##41
D/ActivityThread( 4461): Added TimaKeyStore provider
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.walkingmate.receiver.WalkingMateReceiver: pid=4485 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3645:com.sec.android.app.taskmanager/u0a176 (adj 15): bgCount ##41
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4485): Added TimaKeyStore provider
I/ActivityManager(  854): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4502 uid=10143 gids={50143, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3681:com.sec.esdk.elm/u0a104 (adj 15): bgCount ##41
D/ActivityThread( 4502): Added TimaKeyStore provider
I/ActivityManager(  854): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  854): mDVFSHelper.acquire()
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  854): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4536 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 4536): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4559 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=4570 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/ActivityThread( 4559): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4600 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 3696:com.samsung.android.service.travel/u0a178 (adj 15): bgCount ##41
,D/ActivityThread( 4570): Added TimaKeyStore provider
,D/ActivityThread( 4600): Added TimaKeyStore provider
,I/ActivityManager(  854): Killing 3714:com.samsung.android.scloud.sync/u0a67 (adj 15): bgCount ##41
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4645 uid=10154 gids={50154, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4645): Added TimaKeyStore provider
,I/ActivityManager(  854): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4667 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 4667): Added TimaKeyStore provider
,W/ActivityThread( 4559): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityManager(  854): post active user change for 0
,I/ActivityManager(  854): Killing 3731:com.fmm.dm/1000 (adj 15): bgCount ##41
,I/ActivityManager(  854): Displayed com.example.hello/.MainActivity: +1s100ms
,W/ActivityManager(  854): mDVFSHelper.release()
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4716 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityThread( 4716): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4753 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 3761:com.sec.usbsettings/1000 (adj 15): bgCount ##41
,I/ActivityManager(  854): Killing 3746:com.sec.factory.camera/1000 (adj 15): bgCount ##42
,D/ActivityThread( 4753): Added TimaKeyStore provider
,W/jxcore-log( 4536): Initializing JXcore engine
W/jxcore-log( 4536): JXcore engine is ready
,W/jxcore-log( 4536): Starting JXcore engine
,W/jxcore-log( 4536): Platform android
W/jxcore-log( 4536): 
W/jxcore-log( 4536): Process ARCH arm
W/jxcore-log( 4536): 
,I/jxcore-log( 4536): JXcore Cordova bridge is ready!
I/jxcore-log( 4536): 
,W/jxcore-log( 4536): JXcore engine is started
,E/jxcore-log( 4536): >> samsung-SM-G900F
E/jxcore-log( 4536): 
,I/jxcore-log( 4536): Total memory 1787449344
I/jxcore-log( 4536): 
I/jxcore-log( 4536): Free memory 42692608
I/jxcore-log( 4536): 
,I/jxcore-log( 4536): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4536): 
I/jxcore-log( 4536): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4536): 
,I/jxcore-log( 4536): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4536): 
,I/jxcore-log( 4536): Size 1080 1920
I/jxcore-log( 4536): 
,I/jxcore-log( 4536): Screen Brightness 134
I/jxcore-log( 4536): 
,E/jxcore-log( 4536): Dummy Error Log.
E/jxcore-log( 4536): 
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4846 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,D/ActivityThread( 4846): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4874 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 2127:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
,I/ActivityManager(  854): Killing 3777:com.wssnps/1000 (adj 15): bgCount ##41
,I/ActivityManager(  854): Killing 3825:com.samsung.android.app.accesscontrol/1000 (adj 15): bgCount ##41
,D/ActivityThread( 4874): Added TimaKeyStore provider
,I/jxcore-log( 4536): getBuffer is called!!!!
I/jxcore-log( 4536): 
,W/ActivityManager(  854): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4913 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 3793:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,W/ActivityManager(  854): getTasks: caller 10163 does not hold GET_TASKS; limiting output
,I/ActivityManager(  854): Killing 3844:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/ActivityThread( 4913): Added TimaKeyStore provider
,I/ActivityManager(  854): Process com.android.email (pid 4716)(adj 9) has died(58,615)
,I/ActivityManager(  854): Killing 4874:com.android.exchange/u0a164 (adj 9): depends on provider com.android.email/.provider.EmailProvider in dying proc com.android.email
,I/ActivityManager(  854): Process com.sec.android.app.sns3 (pid 4753)(adj 0) has died(65,619)
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4956 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 4956): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  854): Killing 3850:com.samsung.android.provider.filterprovider/u0a109 (adj 15): bgCount ##41
,D/ActivityThread( 4982): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5006 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 3856:com.samsung.android.app.airwakeupview/u0a72 (adj 15): bgCount ##41
,D/ActivityThread( 5006): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=5022 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 3890:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,D/ActivityThread( 5022): Added TimaKeyStore provider
,I/ActivityManager(  854): Killing 3654:com.sec.android.fotaclient/u0a11 (adj 15): bgCount ##41
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5046 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,D/ActivityThread( 5046): Added TimaKeyStore provider
,I/ActivityManager(  854): Killing 3159:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5065 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityThread( 5065): Added TimaKeyStore provider
,W/ActivityThread( 5065): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5097 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 5097): Added TimaKeyStore provider
,I/ActivityManager(  854): Killing 3927:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5113 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5113): Added TimaKeyStore provider
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=5129 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 3945:com.google.android.onetimeinitializer/u0a14 (adj 15): bgCount ##41
,D/ActivityThread( 5129): Added TimaKeyStore provider
,I/ActivityManager(  854): Killing 3965:com.samsung.android.nearby.mediaserver/u0a76 (adj 15): bgCount ##41


```

####Node name: thali08
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184b4f3aa9/build_android/android_0_49526184b4f3aa9.apk) to device 4325e43f error: protocol fault (no status)
- waiting for device -
rm: /data/local/tmp/android_0_49526184b4f3aa9.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```
####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3235 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 2915:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2915
I/ActivityManager(  906): Delay finish: com.android.settings/.NSReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2948:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3282 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Recipient 2948
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3232
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3302 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
,I/ActivityManager(  906): Killing 2982:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2982
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +269ms
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3363 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3375 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2930:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  906): Killing 3004:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3390 uid=10041 gids={50041}
I/ActivityManager(  906): Recipient 2930
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3407 uid=10078 gids={50078}
I/ActivityManager(  906): Killing 2724:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2724
I/ActivityManager(  906): Killing 3031:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3031
I/ActivityManager(  906): Recipient 3004
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3421 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 3048:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3048
W/jxcore-log( 3302): Initializing JXcore engine
W/jxcore-log( 3302): JXcore engine is ready
W/jxcore-log( 3302): Starting JXcore engine
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3443 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3458 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3472 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
W/jxcore-log( 3302): Platform android
W/jxcore-log( 3302): 
W/jxcore-log( 3302): Process ARCH arm
W/jxcore-log( 3302): 
I/jxcore-log( 3302): JXcore Cordova bridge is ready!
I/jxcore-log( 3302): 
W/jxcore-log( 3302): JXcore engine is started
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3487 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  906): Killing 3063:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3063
E/jxcore-log( 3302): >> HTC-HTC Desire 820
E/jxcore-log( 3302): 
I/jxcore-log( 3302): Total memory 1964650496
I/jxcore-log( 3302): 
I/jxcore-log( 3302): Free memory 666705920
I/jxcore-log( 3302): 
I/jxcore-log( 3302): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3302): 
I/jxcore-log( 3302): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3302): 
I/jxcore-log( 3302): userPath [ 'www' ]
I/jxcore-log( 3302): 
I/jxcore-log( 3302): Size 720 1184
I/jxcore-log( 3302): 
I/jxcore-log( 3302): Screen Brightness 142
I/jxcore-log( 3302): 
E/jxcore-log( 3302): Dummy Error Log.
E/jxcore-log( 3302): 
I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3499 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3511 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3117:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  906): Killing 3090:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
I/ActivityManager(  906): Recipient 3090
I/ActivityManager(  906): Recipient 3117
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3532 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Killing 3131:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3131
,I/jxcore-log( 3302): getBuffer is called!!!!
I/jxcore-log( 3302): 
,I/ActivityManager(  906): Killing 3143:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3143
,I/ActivityManager(  906): Killing 3235:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3553 uid=10079 gids={50079, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3565 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3579 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Recipient 3235
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3593 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3102:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  906): Killing 3282:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3102
I/ActivityManager(  906): Killing 3363:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3363
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3610 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3375:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3282
,I/ActivityManager(  906): Recipient 3375
,I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3644 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3664 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  906): Killing 3390:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3390
,I/ActivityManager(  906): Killing 3407:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3407
,I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3706 uid=10090 gids={50090, 3003, 5012, 1028}
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3721 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 3458:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3458
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3737 uid=10041 gids={50041}
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3750 uid=10078 gids={50078}
,I/ActivityManager(  906): Killing 2738:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3762 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  906): Killing 3487:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3487
,I/ActivityManager(  906): Recipient 2738
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=3777 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 3499:com.htc.stock:remote/u0a82 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3499
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3511:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/ActivityManager(  906): Recipient 3511
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3806 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  906): Killing 3532:com.facebook.katana/u0a27 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3532
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3831 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 3553:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3553
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3855 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/jxcore-log( 3302): Bluetooth turned on
I/jxcore-log( 3302): 
,I/jxcore-log( 3302): WiFi turned off
I/jxcore-log( 3302): 
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3579:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/jxcore-log( 3302): WiFi turned on
I/jxcore-log( 3302): 
I/ActivityManager(  906): Recipient 3579
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3875 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Delaying start of: ServiceRecord{42f76948 u0 com.htc.sense.mms/.transaction.TransactionService}
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42f01a50 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3924 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3593:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3593
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3943 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/jxcore-log( 3302): No internet connection
I/jxcore-log( 3302): 
,I/ActivityManager(  906): Killing 3610:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3960 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Killing 3421:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3421
,I/ActivityManager(  906): Recipient 3610
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3976 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3706:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3706
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3999 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3077:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  906): Recipient 3077
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4035 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/jxcore-log( 3302): No internet connection
I/jxcore-log( 3302): 
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3721:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3721
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4060 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3565:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Recipient 3565
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4090 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4103 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3737:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3737
,I/jxcore-log( 3302): No internet connection
I/jxcore-log( 3302): 
,I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4121 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 3750:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3750
,I/ActivityManager(  906): Delay finish: com.htc.backup/.task.restore.PackageInstallReceiver
,I/ActivityManager(  906): Delaying start of: ServiceRecord{42f1dbf0 u0 com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4150 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  906): Killing 3664:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/jxcore-log( 3302): No internet connection
I/jxcore-log( 3302): 
,I/ActivityManager(  906): Killing 3806:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3806
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4162 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackageAddedReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3855:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Recipient 3855
,I/ActivityManager(  906): Killing 3443:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,I/ActivityManager(  906): Recipient 3443
,I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3831): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3831): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4233 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/jxcore-log( 3302): WiFi
I/jxcore-log( 3302): 
,I/jxcore-log( 3302): Response status code was: 200
I/jxcore-log( 3302): 
I/jxcore-log( 3302): ****TEST TOOK:  10291  ms ****
I/jxcore-log( 3302): 
,I/jxcore-log( 3302): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3302): 
,I/ActivityManager(  906): Killing 3762:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4271 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,I/ActivityManager(  906): Killing 3472:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3472
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  906): Recipient 3762
,I/ActivityManager(  906): Delaying start of: ServiceRecord{430c2320 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4305 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  906): Killing 3302:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  906): Force removing ActivityRecord{42ee8dc8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  906): Killing 3999:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3999
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4345 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/ActivityManager(  906): Killing 4035:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4035
,E/ActivityManager(  906): App crashed! Process: com.google.android.talk
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,E/ActivityManager(  906): App crashed! Process: com.google.process.gapps


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,I/ActivityManager(  771): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2296
I/ActivityManager(  771): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2325 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  771): Killing 1654:com.android.vending/u0a14 (adj 15): empty #17
,I/ActivityManager(  771): Displayed com.example.hello/.MainActivity: +285ms
,W/jxcore-log( 2325): Initializing JXcore engine
,W/jxcore-log( 2325): JXcore engine is ready
,W/jxcore-log( 2325): Starting JXcore engine
,W/jxcore-log( 2325): Platform android
W/jxcore-log( 2325): 
,W/jxcore-log( 2325): Process ARCH arm
W/jxcore-log( 2325): 
,I/jxcore-log( 2325): JXcore Cordova bridge is ready!
I/jxcore-log( 2325): 
,W/jxcore-log( 2325): JXcore engine is started
,E/jxcore-log( 2325): >> LGE-Nexus 5
E/jxcore-log( 2325): 
,I/jxcore-log( 2325): Total memory 1945137152
I/jxcore-log( 2325): 
I/jxcore-log( 2325): Free memory 881311744
I/jxcore-log( 2325): 
I/jxcore-log( 2325): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): userPath [ 'www' ]
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): Size 1080 1776
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): Screen Brightness 82
I/jxcore-log( 2325): 
,E/jxcore-log( 2325): Dummy Error Log.
E/jxcore-log( 2325): 
,I/jxcore-log( 2325): getBuffer is called!!!!
I/jxcore-log( 2325): 
,I/ActivityManager(  771): Killing 1746:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  771): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2402 uid=10001 gids={50001, 3003, 1028, 1015}
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Killing 1777:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  771): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=2448 uid=10031 gids={50031, 3003, 1028, 1015}
,I/ActivityManager(  771): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2475 uid=10068 gids={50068}
,I/ActivityManager(  771): Killing 1095:com.android.printspooler/u0a64 (adj 15): empty #17
,I/ActivityManager(  771): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
I/ActivityManager(  771): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,W/ActivityThread(  771): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  771): Resuming delayed broadcast
I/ActivityManager(  771): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2516 uid=10011 gids={50011, 3003}
,I/ActivityManager(  771): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2532 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  771): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2548 uid=10014 gids={50014, 3003, 1028, 1015}
,I/ActivityManager(  771): Killing 1842:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  771): Delaying start of: ServiceRecord{42e16410 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
I/ActivityManager(  771): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  771): Killing 1916:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/jxcore-log( 2325): Bluetooth turned on
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): WiFi turned off
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): WiFi turned on
I/jxcore-log( 2325): 
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  771): Resuming delayed broadcast
,I/jxcore-log( 2325): No internet connection
I/jxcore-log( 2325): 
I/ActivityManager(  771): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  771): Waited long enough for: ServiceRecord{42c22648 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,I/ActivityManager(  771): Waited long enough for: ServiceRecord{42d1e160 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2627 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  771): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2643 uid=10035 gids={50035, 1028, 3003, 1015}
,I/ActivityManager(  771): Killing 2057:com.google.android.youtube/u0a71 (adj 15): empty #17
,W/ActivityManager(  771): No permission grants found for com.quickoffice.android
,F/ActivityManager(  771): Service ServiceRecord{42f07fd8 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42e2e0b0 2057:com.google.android.youtube/u0a71} not same as in map: null
,I/jxcore-log( 2325): No internet connection
I/jxcore-log( 2325): 
,I/ActivityManager(  771): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  771): Killing 2180:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Killing 1794:com.google.android.gm/u0a41 (adj 15): empty #17
,I/jxcore-log( 2325): No internet connection
I/jxcore-log( 2325): 
,I/ActivityManager(  771): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2728 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/ActivityManager(  771): Killing 1886:com.google.android.email/u0a36 (adj 15): empty #17
,I/jxcore-log( 2325): WiFi
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): Response status code was: 200
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): ****TEST TOOK:  9204  ms ****
I/jxcore-log( 2325): 
,I/jxcore-log( 2325): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2325): 
,I/ActivityManager(  771): Killing 2475:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,I/ActivityManager(  771): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  771): Killing 2325:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  771): Force removing ActivityRecord{42d58410 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  771): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  771): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2826 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/ActivityManager(  771): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2857 uid=10034 gids={50034}
,I/ActivityManager(  771): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2879 uid=10006 gids={50006, 1028, 1015, 1023}


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184b4f3aa9/Sub/serverApp/index.js',
  '{"devices":{"android":18,"cancel":1}}' ]

JSON { devices: { android: 18, cancel: 1 } }


```

