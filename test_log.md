#### Test 50242285b143d21 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50242285b143d21/serverApp/index.js',
  '{"devices":{"ios":4,"android":20,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 20, cancel: 1 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  03157df360a1882a Test has  SUCCEEDED
STOP log received from  30049d9501da2100 Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on 30049d9501da2100 
Device test finished on LGH8153b36be34 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Device test finished on 03157df360a1882a 
Android task is completed 
```

Logcat output:
```
samsung-SM-T232: 
--------- beginning of /dev/log/system
I/ActivityManager( 1194): rtcc_minfree = 82449,70671,58892,47114,35335
I/ActivityManager( 1194): Config changes=1df8 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h961dp 213dpi lrg port ?uimode ?night -touch -keyb/v/h -nav/h s.2}
I/ActivityManager( 1194): Config changes=408 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port ?uimode ?night finger -keyb/v/h -nav/h s.3}
I/ActivityManager( 1194): System now ready
I/ActivityManager( 1194): Config changes=200 {0 1.0 ?mcc?mnc en_US ldltr sw600dp w600dp h936dp 213dpi lrg port finger -keyb/v/h -nav/h s.4}
I/ActivityManager( 1194): !@ mBooting is set true!
I/ActivityManager( 1194): RTCC_TRIGGER_MSG, ASYNC.
W/ActivityManager( 1194): mDVFSHelper.release()
E/ActivityThread( 1578): Failed to find provider info for com.samsung.helphub.provider
W/ActivityManager( 1194): Unable to start service Intent { cmp=com.samsung.android.app.gestureservice/.GestureService } U=0: not found
W/ActivityManager( 1194): !@call fb1: post finishBooting() with 1000msec delay
I/ActivityManager( 1194): !@Boot: bootcomplete
W/ActivityThread( 3175): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityThread( 3199): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1194): Killing 2740:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2772:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 1591:com.android.printspooler/u0a118 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2725:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2901:com.sec.android.widgetapp.activeapplicationwidget/u0a123 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2918:com.samsung.android.app.memo/u0a130 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2931:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3009:com.sec.phone/u0a127 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3091:com.sec.android.widgetapp.samsungapps/u0a120 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3071:com.google.android.configupdater/u0a2 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3144:com.sec.dsm.system/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3175:com.sec.android.app.factorykeystring/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3199:com.sec.factory/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3214:com.sec.android.fotaclient/u0a8 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3246:com.samsung.klmsagent/u0a15 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 1496:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3263:com.android.onetimeinitializer/u0a21 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3278:com.sec.pcw.device/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3306:com.vlingo.midas/u0a26 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3322:com.sec.spp.push/u0a28 (adj 15): bgCount ##33
W/ActivityManager( 1194): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1194): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1194): Killing 3336:com.osp.app.signin/u0a30 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2945:com.android.providers.calendar/u0a31 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2598:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 1620:com.android.settings/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3371:com.wssyncmldm/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 2560:com.google.android.partnersetup/u0a11 (adj 15): bgCount ##33
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{4272c8b0 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1194): Killing 3396:com.google.android.googlequicksearchbox:search/u0a44 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3435:com.sec.providers.settingsearch/u0a136 (adj 15): bgCount ##33
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{427e02e8 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/ActivityManager( 1194): Killing 3418:com.samsung.android.intelligenceservice/u0a52 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3459:com.samsung.android.scloud.backup/u0a53 (adj 15): bgCount ##33
I/ActivityManager( 1194): Process com.samsung.android.MtpApplication (pid 4145) (adj 0) has died.
I/ActivityManager( 1194): Killing 3473:com.samsung.android.scloud.sync/u0a55 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3487:com.wssnps/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3500:com.samsung.android.app.accesscontrol/u0a57 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3517:com.sec.android.app.FileShareServer/u0a62 (adj 15): bgCount ##33
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{429d2830 u0 com.samsung.android.providers.context/.ContextService}
I/ActivityManager( 1194): Killing 3532:com.sec.android.nearby.mediaserver/u0a63 (adj 15): bgCount ##33
W/ActivityThread( 4132): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1194): Killing 3545:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##33
W/ActivityManager( 1194): Unable to start service Intent { act=com.sec.knox.containeragent.service.containerinstallermanager.ContainerInstallerManagerService } U=0: not found
I/ActivityManager( 1194): Killing 3558:com.sec.android.app.bluetoothtest/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3571:com.blurb.checkout/u0a67 (adj 15): bgCount ##33
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{42919e08 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{41d519b8 u0 com.sec.esdk.elm/.service.ElmAgentService}
I/ActivityManager( 1194): Process com.sec.android.app.sysscope (pid 3926) (adj 0) has died.
I/ActivityManager( 1194): Process com.sec.factory (pid 4132) (adj 0) has died.
I/ActivityManager( 1194): Killing 3584:com.samsung.android.app.colorblind/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3597:com.dropbox.android/u0a78 (adj 15): bgCount ##33
W/ActivityThread( 4502): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1194): Killing 3636:com.sec.factory.camera/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3650:com.samsung.android.app.watchmanagerstub/u0a86 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3727:com.samsung.scrc.idi.server/u0a91 (adj 15): bgCount ##33
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{424cad88 u0 com.android.exchange/.ExchangeService}
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{42703dc0 u0 com.android.exchange/.service.ExchangeBroadcastProcessorService}
I/ActivityManager( 1194): Killing 3741:com.samsung.helphub/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3754:com.LocalFota/u0a92 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3771:com.sec.android.app.mt/1000 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3798:com.sec.android.app.sbrowser/u0a114 (adj 15): bgCount ##33
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{428c6a28 u0 com.rxnetworks.rxnservicesxybrid/com.rxnetworks.rxnserviceslib.RXNetworksService}
I/ActivityManager( 1194): Killing 3822:com.sec.android.app.camera/u0a121 (adj 15): bgCount ##33
W/ActivityManager( 1194): mDVFSHelper.acquire()
I/ActivityManager( 1194): Waited long enough for: ServiceRecord{427ee7a0 u0 com.samsung.android.MtpApplication/.MtpService}
W/ActivityManager( 1194): mDVFSHelper.release()
E/ActivityThread( 3116): Activity com.gameloft.android.gdc.StartActivity has leaked IntentReceiver hj@41d69ff0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3116): android.app.IntentReceiverLeaked: Activity com.gameloft.android.gdc.StartActivity has leaked IntentReceiver hj@41d69ff0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3116): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:809)
E/ActivityThread( 3116): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:610)
E/ActivityThread( 3116): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1816)
E/ActivityThread( 3116): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1796)
E/ActivityThread( 3116): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1790)
E/ActivityThread( 3116): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:479)
E/ActivityThread( 3116): 	at hj.b(Unknown Source)
E/ActivityThread( 3116): 	at hj.a(Unknown Source)
E/ActivityThread( 3116): 	at hm.a(Unknown Source)
E/ActivityThread( 3116): 	at hi.run(Unknown Source)
E/ActivityThread( 3116): 	at java.lang.Thread.run(Thread.java:841)
I/ActivityManager( 1194): Killing 1725:com.sec.android.provider.badge/u0a65 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3898:com.sec.android.app.clockpackage/u0a133 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3911:com.sec.android.app.worldclock/u0a135 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3940:com.sec.android.app.controlpanel/u0a141 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3953:com.samsung.android.service.travel/u0a143 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3968:com.google.android.youtube/u0a146 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 4035:com.gameloft.android.gdc:remote/u0a152 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 4251:com.sec.spp.push:RemoteDlcProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 4267:com.sec.spp.push:RemoteNotiProcess/u0a28 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 4309:com.android.mms/u0a36 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 3694:com.google.android.talk/u0a90 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 4183:com.sec.android.widgetapp.SPlannerAppWidget/u0a34 (adj 15): bgCount ##33
I/ActivityManager( 1194): Killing 4210:com.android.calendar/u0a117 (adj 15): bgCount ##33
W/ActivityManager( 1194): mDVFSHelper.acquire()
W/ActivityManager( 1194): mDVFSHelper.release()
,--------- beginning of /dev/log/main
W/ActivityManager( 1194): mDVFSHelper.acquire()
W/ActivityManager( 1194): mDVFSHelper.release()
,W/jxcore-log( 4909): Initializing JXcore engine
W/jxcore-log( 4909): JXcore engine is ready
W/jxcore-log( 4909): Starting JXcore engine
W/jxcore-log( 4909): Platform android
W/jxcore-log( 4909): 
W/jxcore-log( 4909): Process ARCH arm
W/jxcore-log( 4909): 
I/jxcore-log( 4909): JXcore Cordova bridge is ready!
I/jxcore-log( 4909): 
W/jxcore-log( 4909): JXcore engine is started
E/jxcore-log( 4909): >> samsung-SM-T232
E/jxcore-log( 4909): 
I/jxcore-log( 4909): Total memory 1352024064
I/jxcore-log( 4909): 
I/jxcore-log( 4909): Free memory 221356032
I/jxcore-log( 4909): 
I/jxcore-log( 4909): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4909): 
I/jxcore-log( 4909): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4909): 
I/jxcore-log( 4909): userPath [ 'www' ]
I/jxcore-log( 4909): 
I/jxcore-log( 4909): Size 800 1280
I/jxcore-log( 4909): 
I/jxcore-log( 4909): Screen Brightness 143
I/jxcore-log( 4909): 
E/jxcore-log( 4909): Dummy Error Log.
E/jxcore-log( 4909): 
I/jxcore-log( 4909): getBuffer is called!!!!
I/jxcore-log( 4909): 
,I/jxcore-log( 4909): ****TEST TOOK:  5122  ms ****
I/jxcore-log( 4909): 
,I/jxcore-log( 4909): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4909): 
,I/ActivityManager( 1194): Killing 4909:com.example.hello/u0a357 (adj 0): stop com.example.hello


samsung-SM-G920F: 
--------- beginning of main
I/ActivityManager( 3487): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
--------- beginning of system
W/ActivityManager( 3487): mDVFSHelper.acquire()
V/ActivityManager( 3487): Display changed displayId=0
E/ActivityManager( 3487): Invalid thumbnail dimensions: 768x768
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.samsung.android.email.widget
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.samsung.android.email.widget for broadcast com.samsung.android.email.widget/.WidgetProvider: pid=9785 uid=10044 gids={50044, 9997} abi=arm64-v8a
D/ActivityManager( 3487): handle home activity for 0
D/ActivityManager( 3487): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/ActivityThread( 9785): Added TimaKeyStore provider
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
I/ActivityManager( 3487): Killing 9297:com.policydm/1000 (adj 15): empty #25
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=9801 uid=10100 gids={50100, 9997} abi=arm64-v8a
D/ActivityThread( 9801): Added TimaKeyStore provider
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=9816 uid=10103 gids={50103, 9997, 3003} abi=arm64-v8a
I/ActivityManager( 3487): Killing 9319:com.osp.app.signin/u0a37 (adj 15): empty #25
D/ActivityThread( 9816): Added TimaKeyStore provider
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=9832 uid=10152 gids={50152, 9997, 1028, 1015, 3003, 1023} abi=arm64-v8a
I/ActivityManager( 3487): Killing 7591:com.samsung.android.SettingsReceiver/1000 (adj 15): empty #25
D/ActivityThread( 9832): Added TimaKeyStore provider
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
I/ActivityManager( 3487): Killing 8359:com.samsung.android.sm/1000 (adj 15): empty #25
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 3487): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 3487): mDVFSHelper.acquire()
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=9858 uid=10434 gids={50434, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 4256): updateVisibility : ActivityRecord{2b310189 token=android.os.BinderProxy@3c7df2ad {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : true
D/ActivityThread( 9858): Added TimaKeyStore provider
V/ActivityThread( 4256): updateVisibility : ActivityRecord{2b310189 token=android.os.BinderProxy@3c7df2ad {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
,D/ActivityManager( 3487): post active user change for 0 fullscreen true record.isFloatingActivity() false
I/ActivityManager( 3487): Displayed Component not be shown by security: +496ms
W/ActivityManager( 3487): mDVFSHelper.release()
W/jxcore-log( 9858): Initializing JXcore engine
W/jxcore-log( 9858): JXcore engine is ready
W/jxcore-log( 9858): Starting JXcore engine
W/jxcore-log( 9858): Platform android
W/jxcore-log( 9858): 
W/jxcore-log( 9858): Process ARCH arm
W/jxcore-log( 9858): 
I/jxcore-log( 9858): JXcore Cordova bridge is ready!
I/jxcore-log( 9858): 
W/jxcore-log( 9858): JXcore engine is started
E/jxcore-log( 9858): >> samsung-SM-G920F
E/jxcore-log( 9858): 
I/jxcore-log( 9858): Total memory 2829074432
I/jxcore-log( 9858): 
I/jxcore-log( 9858): Free memory 48443392
I/jxcore-log( 9858): 
I/jxcore-log( 9858): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9858): 
I/jxcore-log( 9858): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9858): 
I/jxcore-log( 9858): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 9858): 
I/jxcore-log( 9858): Size 1440 2560
I/jxcore-log( 9858): 
I/jxcore-log( 9858): Screen Brightness 134
I/jxcore-log( 9858): 
E/jxcore-log( 9858): Dummy Error Log.
E/jxcore-log( 9858): 
I/jxcore-log( 9858): getBuffer is called!!!!
I/jxcore-log( 9858): 
V/ActivityThread( 9858): updateVisibility : ActivityRecord{26e297cd token=android.os.BinderProxy@6ff5cf6 {com.example.hello/com.example.hello.MainActivity}} show : true
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.samsung.android.SettingsReceiver for broadcast com.samsung.android.SettingsReceiver/.AccessibilityReceiver: pid=9924 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
D/ActivityThread( 9924): Added TimaKeyStore provider
I/ActivityManager( 3487): Killing 9338:com.sec.android.app.soundalive/u0a54 (adj 15): empty #25
D/ActivityManager( 3487): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ActivityManager( 3487): Display changed displayId=0
,I/jxcore-log( 9858): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 9858): 
,I/jxcore-log( 9858): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9858): 
,I/ActivityManager( 3487): Force stopping com.example.hello appid=10434 user=-1: uninstall pkg
I/ActivityManager( 3487): Killing 9858:com.example.hello/u0a434 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 3487):   Force finishing activity ActivityRecord{80c3d14 u0 com.example.hello/.MainActivity t44}
,I/ActivityManager( 3487): Force stopping com.example.hello appid=10434 user=0: pkg removed
,W/ActivityManager( 3487): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9989 uid=10059 gids={50059, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.sec.android.app.launcher/com.sec.android.app.launcher.services.LauncherService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
,W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.launcher
,D/ActivityThread( 9989): Added TimaKeyStore provider
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5345, uid=10127 that is not exported from uid 10125
W/ActivityManager( 3487): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.microsoft.skydrive, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.vodafone.vodafone360updates/com.vodafone.vodafone360updates.agent.Agent; callingUser = 0; userId(target) = 0
W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.vodafone.vodafone360updates, destAppInfo.processName = com.vodafone.vodafone360updates
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.samsung.android.coreapps for content provider com.samsung.android.coreapps/.easysignup.db.EasySignUpProviderPublic: pid=10007 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager( 3487): Killing 9420:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #25
,D/ActivityThread(10007): Added TimaKeyStore provider
,I/ActivityManager( 3487): Killing 9443:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #25
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3487): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10023 uid=10104 gids={50104, 9997, 3003} abi=arm64-v8a
,D/ActivityThread(10023): Added TimaKeyStore provider
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 3487): userId = 0, bbcId = -10000
W/ActivityManager( 3487): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 3487): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3487): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3487): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=arm64-v8a
,I/ActivityManager( 3487): Killing 9458:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #25
,D/ActivityThread(10055): Added TimaKeyStore provider
,D/ActivityManager( 3487): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService; callingUser = 0; userId(target) = 0


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
I/ActivityManager( 1281): Killing 8602:com.lge.bnr/1000 (adj 15): empty #22
W/ActivityManager( 1281): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
I/ActivityManager( 1281): Start proc 9160:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
I/ActivityManager( 1281): Killing 8677:com.lge.clock/u0a16 (adj 15): empty #22
I/ActivityManager( 1281): Start proc 9191:com.lge.bnr/1000 for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver
I/ActivityManager( 1281): Start proc 9212:com.google.android.gms:car/u0a6 for service com.google.android.gms/.car.CarService
W/ActivityManager( 1281): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1281): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1281): Start proc 9238:com.lge.exchange/u0a22 for broadcast com.lge.exchange/.receiver.PackageChangeReceiver
W/ActivityManager( 1281): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1281): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1281): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1281): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1281): Start proc 9263:com.lge.email/u0a56 for content provider com.lge.email/.providers.EmailProvider
I/ActivityManager( 1281): Killing 8622:com.google.android.music:main/u0a123 (adj 15): empty #22
I/ActivityManager( 1281): Killing 8734:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #22
I/ActivityManager( 1281): Killing 8755:com.lge.myplace/u0a30 (adj 15): empty #22
,I/ActivityManager( 1281): Start proc 9293:com.lge.NfcSettings/1000 for broadcast com.lge.NfcSettings/.search.NfcSearchingDBUpdateReceiver
I/ActivityManager( 1281): Start proc 9317:com.lge.eula/u0a105 for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver
I/ActivityManager( 1281): Killing 8777:com.google.android.gm/u0a113 (adj 15): empty #22
I/ActivityManager( 1281): Start proc 9354:com.google.android.apps.docs/u0a118 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager( 1281): Killing 8833:com.google.android.setupwizard/u0a54 (adj 15): empty #22
I/ActivityManager( 1281): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1281): setTaskToReturnTo : TaskRecord{1a75e57e #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1281): setTaskToReturnTo : TaskRecord{1a75e57e #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1281): Start proc 9378:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
W/ActivityThread( 4220): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 4220): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 4220): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3450)
W/ActivityThread( 4220): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3539)
W/ActivityThread( 4220): 	at android.app.ActivityThread.access$1100(ActivityThread.java:162)
W/ActivityThread( 4220): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1378)
W/ActivityThread( 4220): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 4220): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 4220): 	at android.app.ActivityThread.main(ActivityThread.java:5430)
W/ActivityThread( 4220): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 4220): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 4220): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
W/ActivityThread( 4220): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
I/ActivityManager( 1281): Activity reported stop, but no longer stopping: ActivityRecord{5595c69 u0 com.lge.launcher2/.Launcher t45}
W/ActivityManager( 1281): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1281): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1281): Killing 8910:com.lge.lgaccount/u0a107 (adj 15): empty #22
I/ActivityManager( 1281): Killing 8579:com.lge.sizechangable.weather/u0a136 (adj 15): empty #23
I/ActivityManager( 1281): Displayed com.example.hello/.MainActivity: +697ms (total +35s774ms)
W/ActivityManager( 1281): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
W/jxcore-log( 9378): Initializing JXcore engine
W/jxcore-log( 9378): JXcore engine is ready
W/jxcore-log( 9378): Starting JXcore engine
W/ActivityManager( 1281): getRunningAppProcesses: caller 10118 does not hold REAL_GET_TASKS; limiting output
W/jxcore-log( 9378): Platform android
W/jxcore-log( 9378): 
W/jxcore-log( 9378): Process ARCH arm
W/jxcore-log( 9378): 
I/jxcore-log( 9378): JXcore Cordova bridge is ready!
I/jxcore-log( 9378): 
W/jxcore-log( 9378): JXcore engine is started
E/jxcore-log( 9378): >> LGE-LG-H815
E/jxcore-log( 9378): 
I/jxcore-log( 9378): Total memory 2968948736
I/jxcore-log( 9378): 
I/jxcore-log( 9378): Free memory 71688192
I/jxcore-log( 9378): 
I/jxcore-log( 9378): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9378): 
I/jxcore-log( 9378): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9378): 
I/jxcore-log( 9378): userPath [ 'www' ]
I/jxcore-log( 9378): 
I/jxcore-log( 9378): Size 1440 2392
I/jxcore-log( 9378): 
I/jxcore-log( 9378): Screen Brightness 255
I/jxcore-log( 9378): 
E/jxcore-log( 9378): Dummy Error Log.
E/jxcore-log( 9378): 
I/ActivityManager( 1281): Killing 8890:com.lge.lifetracker/u0a137 (adj 15): empty #22
I/jxcore-log( 9378): getBuffer is called!!!!
I/jxcore-log( 9378): 
I/ActivityManager( 1281): Start proc 9461:com.google.android.gm/u0a113 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
D/ActivityThread( 9461): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 1281): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1281): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1281): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1281): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1281): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1281): Start proc 9503:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ActivityManager( 1281): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1281): Killing 8932:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
,W/ActivityManager( 1281): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9378): ****TEST TOOK:  5041  ms ****
I/jxcore-log( 9378): 
,I/jxcore-log( 9378): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9378): 
,I/ActivityManager( 1281): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
I/ActivityManager( 1281): Killing 9378:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1281): Force removing ActivityRecord{2d934adf u0 com.example.hello/.MainActivity t47}: app died, no saved state,
,I/ActivityManager( 1281): Force stopping com.example.hello appid=10360 user=0: pkg removed
,W/ActivityManager( 1281): Spurious death for ProcessRecord{17268a6e 9378:com.example.hello/u0a360}, curProc for 9378: null
,I/ActivityManager( 1281): Start proc 9592:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1281): Displayed com.lge.launcher2/.Launcher: +175ms
,I/ActivityManager( 1281): Start proc 9613:com.android.settings/1000 for broadcast com.android.settings/.hotkey.PackageIntentReceiver
,I/ActivityManager( 1281): Killing 8414:com.android.defcontainer/u0a3 (adj 15): empty #22
,I/ActivityManager( 1281): Killing 8988:com.google.android.partnersetup/u0a5 (adj 15): empty #22


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2936): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
I/ActivityManager( 2936): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/ActivityManager( 2936): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/ActivityManager( 2936): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/ActivityManager( 2936): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2936): Displayed com.example.hello/.MainActivity: +1s717ms
,W/jxcore-log( 6215): Initializing JXcore engine
W/jxcore-log( 6215): JXcore engine is ready
,W/jxcore-log( 6215): Starting JXcore engine
,W/jxcore-log( 6215): Platform android
W/jxcore-log( 6215): 
W/jxcore-log( 6215): Process ARCH arm
W/jxcore-log( 6215): 
,I/jxcore-log( 6215): JXcore Cordova bridge is ready!
I/jxcore-log( 6215): 
,W/jxcore-log( 6215): JXcore engine is started
,E/jxcore-log( 6215): >> HUAWEI-ALE-L21
E/jxcore-log( 6215): 
,I/jxcore-log( 6215): Total memory 1949741056
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): Free memory 19128320
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6215): 
I/jxcore-log( 6215): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): userPath [ 'www' ]
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): Size 720 1184
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): Screen Brightness 242
I/jxcore-log( 6215): 
,E/jxcore-log( 6215): Dummy Error Log.
E/jxcore-log( 6215): 
,I/jxcore-log( 6215): getBuffer is called!!!!
I/jxcore-log( 6215): 
,I/ActivityManager( 2936): filter receiver for action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager( 2936): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2936): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
,I/jxcore-log( 6215): ****TEST TOOK:  5106  ms ****
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6215): 
,I/ActivityManager( 2936): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2936): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED


```

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager(  759): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2819 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2865 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  759): Displayed com.example.hello/.MainActivity: +379ms (total +32s793ms)
W/jxcore-log( 2865): Initializing JXcore engine
W/jxcore-log( 2865): JXcore engine is ready
W/jxcore-log( 2865): Starting JXcore engine
W/jxcore-log( 2865): Platform android
W/jxcore-log( 2865): 
W/jxcore-log( 2865): Process ARCH arm
W/jxcore-log( 2865): 
I/jxcore-log( 2865): JXcore Cordova bridge is ready!
I/jxcore-log( 2865): 
W/jxcore-log( 2865): JXcore engine is started
E/jxcore-log( 2865): >> LGE-Nexus 5
E/jxcore-log( 2865): 
I/jxcore-log( 2865): Total memory 1946181632
I/jxcore-log( 2865): 
I/jxcore-log( 2865): Free memory 331468800
I/jxcore-log( 2865): 
I/jxcore-log( 2865): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2865): 
I/jxcore-log( 2865): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2865): 
I/jxcore-log( 2865): userPath [ 'www' ]
I/jxcore-log( 2865): 
I/jxcore-log( 2865): Size 1080 1776
I/jxcore-log( 2865): 
I/jxcore-log( 2865): Screen Brightness 82
I/jxcore-log( 2865): 
E/jxcore-log( 2865): Dummy Error Log.
E/jxcore-log( 2865): 
,I/jxcore-log( 2865): getBuffer is called!!!!
I/jxcore-log( 2865): 
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{b9a1219 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{3aaf54b7 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  759): Killing 2316:com.google.android.configupdater/u0a36 (adj 15): empty #17
,I/jxcore-log( 2865): ****TEST TOOK:  5036  ms ****
I/jxcore-log( 2865): 
I/jxcore-log( 2865): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2865): 
,I/ActivityManager(  759): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 2865:com.example.hello/u0a277 (adj 0): stop com.example.hello
,W/ActivityManager(  759): Force removing ActivityRecord{3a4ffa74 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  759): Spurious death for ProcessRecord{3ba6cf58 2865:com.example.hello/u0a277}, curProc for 2865: null
,I/ActivityManager(  759): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2950 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2991 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2350:com.google.android.keep/u0a71 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3013 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2376:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17


LGE-LG-D722: 
--------- beginning of system
--------- beginning of main
I/ActivityManager(  849): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3112 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 3002} abi=armeabi-v7a
I/ActivityManager(  849): Killing 1895:com.android.printspooler/u0a87 (adj 15): empty #11
,E/ActivityThread( 3112): Failed to find provider info for com.lge.ims.rcs
E/ActivityThread( 3112): Failed to find provider info for com.lge.ims.rcs
I/ActivityManager(  849): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{14a51053 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{14a51053 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  849): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3148 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityManager(  849): enqueue in BackgroundQueue #52 Intent=Intent { act=com.lge.qremote.action.wait_loading flg=0x14 cmp=com.lge.qremote/.appwidget.RemoteAppWidgetProvider (has extras) }
,E/ActivityThread( 3112): Failed to find provider info for com.lge.ims.provider.uc
,I/ActivityManager(  849): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=3200 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Displayed com.example.hello/.MainActivity: +1s98ms
,I/ActivityManager(  849): Killing 2808:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.android.contacts for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver: pid=3246 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 2546:com.lge.qremote/u0a106 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.wcdma_only.log_service.FactorySIMReceiver: pid=3271 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/jxcore-log( 3148): Initializing JXcore engine
W/jxcore-log( 3148): JXcore engine is ready
,W/jxcore-log( 3148): Starting JXcore engine
I/ActivityManager(  849): Killing 2839:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/ActivityManager(  849): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
,I/ActivityManager(  849): Start proc com.android.providers.partnerbookmarks for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver: pid=3289 uid=10071 gids={50071, 9997} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 2971:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
W/jxcore-log( 3148): Platform android
W/jxcore-log( 3148): 
,W/jxcore-log( 3148): Process ARCH arm
W/jxcore-log( 3148): 
,I/jxcore-log( 3148): JXcore Cordova bridge is ready!
I/jxcore-log( 3148): 
W/jxcore-log( 3148): JXcore engine is started
,E/jxcore-log( 3148): >> LGE-LG-D722
E/jxcore-log( 3148): 
I/jxcore-log( 3148): Total memory 906309632
I/jxcore-log( 3148): 
I/jxcore-log( 3148): Free memory 25600000
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3148): 
I/jxcore-log( 3148): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3148): 
I/jxcore-log( 3148): userPath [ 'www' ]
I/jxcore-log( 3148): 
I/jxcore-log( 3148): Size 720 1196
I/jxcore-log( 3148): 
I/jxcore-log( 3148): Screen Brightness 255
I/jxcore-log( 3148): 
E/jxcore-log( 3148): Dummy Error Log.
E/jxcore-log( 3148): 
,I/ActivityManager(  849): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3307 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  849): Killing 2992:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  849): Killing 2179:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/jxcore-log( 3148): getBuffer is called!!!!
I/jxcore-log( 3148): 
,I/ActivityManager(  849): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3353 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityManager(  849): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,I/ActivityManager(  849): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3378 uid=10008 gids={50008, 9997} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3018:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3398 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3037:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.email for broadcast com.lge.email/.ui.widget.EmailWidgetProvider: pid=3423 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3054:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=3444 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3079:com.android.browser/u0a12 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3461 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  849): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3488 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3200:com.android.settings/1000 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3522 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3542 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3289:com.android.providers.partnerbookmarks/u0a71 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3570 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3307:com.lge.eula/1000 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3587 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 2214:com.android.defcontainer/u0a4 (adj 15): empty #11
,I/ActivityManager(  849): Killing 3246:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  849): Killing 3353:com.android.keychain/1000 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3612 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3637 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3271:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3669 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3378:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3695 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3398:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3723 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  849): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3743 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3423:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  849): Waited long enough for: ServiceRecord{3bee7c35 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,I/ActivityManager(  849): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3763 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 3461:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/jxcore-log( 3148): ****TEST TOOK:  5158  ms ****
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3148): 
,I/ActivityManager(  849): Killing 3488:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3787 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3522:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3809 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3542:com.lge.clock/u0a10 (adj 15): empty #11
,I/ActivityManager(  849): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3844 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3570:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  849): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  849): Killing 3148:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  849): Force removing ActivityRecord{8736d90 u0 com.example.hello/.MainActivity t219}: app died, no saved state
,I/ActivityManager(  849): Force stopping com.example.hello appid=10030 user=0: pkg removed
,W/ActivityManager(  849): Spurious death for ProcessRecord{3bd3a5eb 3148:com.example.hello/u0a30}, curProc for 3148: null
,I/ActivityManager(  849): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=3865 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3886 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3587:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  849): Killing 3637:com.android.settings/1000 (adj 15): empty #11
,I/ActivityManager(  849): Waited long enough for: ServiceRecord{2f624fc4 u0 com.lge.sizechangable.weather/.service.WeatherService}
,W/ActivityManager(  849): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  849): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3912 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  849): Killing 3669:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,I/ActivityManager(  849): Process com.lge.defaultaccount (pid 3809) has died
,I/ActivityManager(  849): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3930 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3949 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a


```

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on LGD8553bed2d08 
Device test finished on 320414cd475f91e3 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
,W/ActivityManager( 2409): mDVFSHelper.acquire()
D/ActivityThread( 6633): Added TimaKesytore provider
,W/ActivityManager( 2409): mDVFSHelper.release()
,W/jxcore-log( 6633): Initializing JXcore engine
,W/jxcore-log( 6633): JXcore engine is ready
,W/jxcore-log( 6633): Starting JXcore engine
,W/jxcore-log( 6633): Platform android
W/jxcore-log( 6633): 
,W/jxcore-log( 6633): Process ARCH arm
W/jxcore-log( 6633): 
,I/jxcore-log( 6633): JXcore Cordova bridge is ready!
I/jxcore-log( 6633): 
,W/jxcore-log( 6633): JXcore engine is started
,E/jxcore-log( 6633): >> samsung-SM-G800F
E/jxcore-log( 6633): 
,I/jxcore-log( 6633): Total memory 1319530496
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): Free memory 35295232
I/jxcore-log( 6633): 
I/jxcore-log( 6633): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): Size 720 1280
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): Screen Brightness 134
I/jxcore-log( 6633): 
,E/jxcore-log( 6633): Dummy Error Log.
E/jxcore-log( 6633): 
,I/jxcore-log( 6633): getBuffer is called!!!!
I/jxcore-log( 6633): 
,I/ActivityManager( 2409): Killing 5687:com.sec.phone/1001 (adj 15): empty #43
,I/jxcore-log( 6633): ****TEST TOOK:  5093  ms ****,
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 6633): 
,I/ActivityManager( 2409): Killing 6633:com.example.hello/u0a397 (adj 0): stop com.example.hello,
,W/ActivityManager( 2409): Force removing ActivityRecord{42421c80 u0 com.example.hello/.MainActivity t4}: app died, no saved state,
,W/ActivityManager( 2409): mDVFSHelper.acquire()
,D/ActivityThread( 6701): Added TimaKesytore provider
,W/ActivityManager( 2409): mDVFSHelper.release(),
,I/ActivityManager( 2409): Killing 5558:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/ActivityThread( 6715): Added TimaKesytore provider
,I/ActivityManager( 2409): Killing 5696:com.android.calendar/u0a144 (adj 15): empty #43,
,D/ActivityThread( 6736): Added TimaKesytore provider
,D/ActivityThread( 6752): Added TimaKesytore provider
,D/ActivityThread( 6784): Added TimaKesytore provider
,I/ActivityManager( 2409): Killing 5760:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/ActivityThread( 6799): Added TimaKesytore provider
,I/ActivityManager( 2409): Killing 5756:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/ActivityThread( 6813): Added TimaKesytore provider
,D/ActivityThread( 6826): Added TimaKesytore provider,
,I/ActivityManager( 2409): Killing 5274:com.google.android.talk/u0a109 (adj 15): empty #43
,I/ActivityManager( 2409): Killing 5927:com.sec.android.diagmonagent/1000 (adj 15): empty #43,
,I/ActivityManager( 2409): Process com.google.android.apps.docs (pid 6826) (adj 0) has died.


motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3476
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3492 uid=10328 gids={50328, 3003, 3001, 3002}
I/ActivityManager( 1018): Displayed com.example.hello/.MainActivity: +335ms (total +362ms)
W/jxcore-log( 3492): Initializing JXcore engine
W/jxcore-log( 3492): JXcore engine is ready
W/jxcore-log( 3492): Starting JXcore engine
W/jxcore-log( 3492): Platform android
W/jxcore-log( 3492): 
W/jxcore-log( 3492): Process ARCH arm
W/jxcore-log( 3492): 
I/jxcore-log( 3492): JXcore Cordova bridge is ready!
I/jxcore-log( 3492): 
W/jxcore-log( 3492): JXcore engine is started
E/jxcore-log( 3492): >> motorola-XT1039
E/jxcore-log( 3492): 
I/jxcore-log( 3492): Total memory 893136896
I/jxcore-log( 3492): 
I/jxcore-log( 3492): Free memory 34189312
I/jxcore-log( 3492): 
I/jxcore-log( 3492): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3492): 
I/jxcore-log( 3492): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3492): 
I/jxcore-log( 3492): userPath [ 'www' ]
I/jxcore-log( 3492): 
I/jxcore-log( 3492): Size 720 1184
I/jxcore-log( 3492): 
I/jxcore-log( 3492): Screen Brightness 10
I/jxcore-log( 3492): 
E/jxcore-log( 3492): Dummy Error Log.
E/jxcore-log( 3492): 
,I/jxcore-log( 3492): getBuffer is called!!!!
I/jxcore-log( 3492): 
,I/jxcore-log( 3492): ****TEST TOOK:  5049  ms ****
I/jxcore-log( 3492): 
I/jxcore-log( 3492): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3492): 
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10328 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 3492:com.example.hello/u0a328 (adj 0): stop com.example.hello
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{42ba1f20 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10328 user=0: pkg removed
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{42ba1f20 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{42ba1f20 u0 com.example.hello/.MainActivity t3 f}
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3578 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1018): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3597 uid=10058 gids={50058}
,I/ActivityManager( 1018): Killing 3230:com.android.providers.calendar/u0a8 (adj 15): empty #9
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3616 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1018): Killing 3358:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1018): Killing 3334:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1018): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3632 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 3107:android.process.acore/u0a10 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{cc9b9db #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{cc9b9db #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1029): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5990 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1029): Display changed displayId=0
I/ActivityManager( 1029): Killing 5652:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager( 1029): Displayed com.example.hello/.MainActivity: +612ms (total +726ms)
W/jxcore-log( 5990): Initializing JXcore engine
W/jxcore-log( 5990): JXcore engine is ready
W/jxcore-log( 5990): Starting JXcore engine
W/jxcore-log( 5990): Platform android
W/jxcore-log( 5990): 
W/jxcore-log( 5990): Process ARCH arm
W/jxcore-log( 5990): 
I/jxcore-log( 5990): JXcore Cordova bridge is ready!
I/jxcore-log( 5990): 
W/jxcore-log( 5990): JXcore engine is started
E/jxcore-log( 5990): >> LGE-LG-D855
E/jxcore-log( 5990): 
I/jxcore-log( 5990): Total memory 2995761152
I/jxcore-log( 5990): 
I/jxcore-log( 5990): Free memory 658001920
I/jxcore-log( 5990): 
I/jxcore-log( 5990): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5990): 
I/jxcore-log( 5990): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5990): 
I/jxcore-log( 5990): userPath [ 'www' ]
I/jxcore-log( 5990): 
I/jxcore-log( 5990): Size 1440 2392
I/jxcore-log( 5990): 
I/jxcore-log( 5990): Screen Brightness 50
I/jxcore-log( 5990): 
E/jxcore-log( 5990): Dummy Error Log.
E/jxcore-log( 5990): 
I/jxcore-log( 5990): getBuffer is called!!!!
I/jxcore-log( 5990): 
,I/jxcore-log( 5990): ****TEST TOOK:  5067  ms ****
I/jxcore-log( 5990): 
I/jxcore-log( 5990): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5990): 
,I/ActivityManager( 1029): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1029): Killing 5990:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1029):   Force finishing activity ActivityRecord{2e70c78 u0 com.example.hello/.MainActivity t2}
,W/ActivityManager( 1029): Spurious death for ProcessRecord{d2226d8 5990:com.example.hello/u0a318}, curProc for 5990: null
I/ActivityManager( 1029): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{2e70c78 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1029): Duplicate finish request for ActivityRecord{2e70c78 u0 com.example.hello/.MainActivity t2 f}
,I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6104 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 4846:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6131 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 6131): Failed to find provider info for com.lge.lgaccount.provider
,I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6152 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 5788:com.google.android.talk/u0a72 (adj 15): empty #17
,--------- beginning of crash


```

####Node name: thali05
Console output:
```
STOP log received from  1d6a772d Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on SH47FWM00508 
Android task is completed 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of main
,I/ActivityManager(  910): do not start freezing screen for locked container getKeyguardshowstate = false
--------- beginning of system
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  910): mDVFSHelper.acquire()
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  910): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6010 uid=10215 gids={50215, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6010): Added TimaKeyStore provider
V/ActivityManager(  910): Display changed displayId=0
V/ActivityThread( 1445): updateVisibility : ActivityRecord{2bc063fc token=android.os.BinderProxy@36a1ec9a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{1dc0b2a3 u0 com.example.hello/.MainActivity t2}
D/ActivityManager(  910): post active user change for 0
V/ActivityThread( 6010): updateVisibility : ActivityRecord{1406c003 token=android.os.BinderProxy@8f01abd {com.example.hello/com.example.hello.MainActivity}} show : true
W/ActivityManager(  910): mDVFSHelper.release()
,W/jxcore-log( 6010): Initializing JXcore engine
W/jxcore-log( 6010): JXcore engine is ready
,W/jxcore-log( 6010): Starting JXcore engine
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  910): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6088 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 6010): Platform android
W/jxcore-log( 6010): 
W/jxcore-log( 6010): Process ARCH arm
W/jxcore-log( 6010): 
,D/ActivityThread( 6088): Added TimaKeyStore provider
,I/jxcore-log( 6010): JXcore Cordova bridge is ready!
I/jxcore-log( 6010): 
,W/jxcore-log( 6010): JXcore engine is started
,I/ActivityManager(  910): Killing 5218:com.sec.spp.push:RemoteNotiProcess/u0a43 (adj 15): bgCount ##41
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{1ed6abd u0 com.samsung.android.MtpApplication/.MtpService}
,E/jxcore-log( 6010): >> samsung-SM-N9005
E/jxcore-log( 6010): 
,I/jxcore-log( 6010): Total memory 2971471872
I/jxcore-log( 6010): 
,I/jxcore-log( 6010): Free memory 435855360
I/jxcore-log( 6010): 
I/jxcore-log( 6010): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6010): 
I/jxcore-log( 6010): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6010): 
,I/jxcore-log( 6010): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6010): 
,I/jxcore-log( 6010): Size 1080 1920
I/jxcore-log( 6010): 
,I/jxcore-log( 6010): Screen Brightness 162
I/jxcore-log( 6010): 
,E/jxcore-log( 6010): Dummy Error Log.
E/jxcore-log( 6010): 
,I/jxcore-log( 6010): getBuffer is called!!!!
I/jxcore-log( 6010): 
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{354bc33f u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{27f07587 u0 com.google.android.music/.wear.WearMetadataSyncService}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{126552d3 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,I/jxcore-log( 6010): ****TEST TOOK:  5087  ms ****
I/jxcore-log( 6010): 
,I/jxcore-log( 6010): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6010): 
,I/ActivityManager(  910): Force stopping com.example.hello appid=10215 user=-1: uninstall pkg
,I/ActivityManager(  910): Killing 6010:com.example.hello/u0a215 (adj 0): stop com.example.hello
,I/ActivityManager(  910):   Force finishing activity ActivityRecord{1dc0b2a3 u0 com.example.hello/.MainActivity t2}
,I/ActivityManager(  910): Force stopping com.example.hello appid=10215 user=0: pkg removed
,W/ActivityManager(  910): Spurious death for ProcessRecord{a843e83 6010:com.example.hello/u0a215}, curProc for 6010: null
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  910): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6151 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6151): Added TimaKeyStore provider
,V/ActivityThread( 1445): updateVisibility : ActivityRecord{2bc063fc token=android.os.BinderProxy@36a1ec9a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  910): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6172 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  910): Killing 5263:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,D/ActivityThread( 6172): Added TimaKeyStore provider
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  910): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6190 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/ActivityManager(  910): Killing 4714:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/ActivityThread( 6190): Added TimaKeyStore provider
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  910): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6210 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6210): Added TimaKeyStore provider
,I/ActivityManager(  910): Process com.sec.android.app.shealth (pid 4055)(adj 5) has died(501,1369)
,W/ActivityManager(  910): Scheduling restart of crashed service com.sec.android.app.shealth/.service.HandleAppDataService in 1000ms
,I/ActivityManager(  910): Killing 5375:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  910): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6234 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 6234): Added TimaKeyStore provider
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  910): checkUser: useridlist=null, currentuser=0
,E/ActivityThread( 6234): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6250 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a


HTC-HTC One_M8: 
--------- beginning of system
I/ActivityManager(  891): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3223 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
--------- beginning of main
I/ActivityManager(  891): Killing 2915:com.htc.showme/u0a85 (adj 15): empty #17
I/ActivityManager(  891): Recipient 2915
I/ActivityManager(  891): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3247 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 2607:com.htc.sense.browser/u0a9 (adj 15): empty #17
I/ActivityManager(  891): Recipient 2607
I/ActivityManager(  891): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3267 uid=10020 gids={50020, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 2651:com.google.android.partnersetup/u0a28 (adj 15): empty #17
I/ActivityManager(  891): Recipient 2651
I/ActivityManager(  891): Start proc com.fitbit.FitbitMobile for broadcast com.fitbit.FitbitMobile/com.fitbit.galileo.service.BootCompletedReceiver: pid=3286 uid=10023 gids={50023, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 2691:com.htc.sense.mms/u0a67 (adj 15): empty #17
I/ActivityManager(  891): Recipient 2691
,I/ActivityManager(  891): Killing 1960:com.htc.dotmatrix/u0a43 (adj 15): empty #17
I/ActivityManager(  891): Recipient 1960
I/ActivityManager(  891): Killing 2946:com.android.settings/1000 (adj 15): empty #17
I/ActivityManager(  891): Recipient 2946
I/ActivityManager(  891): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3313 uid=10027 gids={50027, 9997} abi=armeabi-v7a
I/ActivityManager(  891): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3342 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  891): Killing 2978:com.htc.widget.hmsproc1/u0a37 (adj 15): empty #17
I/ActivityManager(  891): Recipient 2978
I/ActivityManager(  891): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3366 uid=10030 gids={50030, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=armeabi-v7a
I/ActivityManager(  891): Killing 2997:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
I/ActivityManager(  891): Recipient 2997
I/ActivityManager(  891): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3388 uid=10032 gids={50032, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  891): Killing 3014:com.htc.backup/u0a118 (adj 15): empty #17
I/ActivityManager(  891): Recipient 3014
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  891): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3405 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  891): Killing 3061:com.futuredial/u0a86 (adj 15): empty #17
I/ActivityManager(  891): Recipient 3061
E/ActivityThread( 1491): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1491): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1491): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1491): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1491): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1491): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1491): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/ActivityThread( 1491): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1491): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/ActivityThread( 1491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
I/ActivityManager(  891): Activity reported stop, but no longer stopping: ActivityRecord{13fcdff3 u0 com.htc.launcher/.Launcher t26}
I/ActivityManager(  891): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3425 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  891): Killing 3083:com.android.keychain/1000 (adj 15): empty #17
I/ActivityManager(  891): Recipient 3083
,I/ActivityManager(  891): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3448 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  891): Killing 3109:android.process.media/u0a17 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3109,
,I/ActivityManager(  891): Killing 3127:com.htc.lucy/u0a64 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3127,
,I/ActivityManager(  891): Killing 3155:com.htc.wifidisplay/u0a166 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3155
,I/ActivityManager(  891): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3479 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3498 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 3037:com.htc.cs.dm/u0a105 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3037
,I/ActivityManager(  891): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3523 uid=10051 gids={50051, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/ActivityManager(  891): Killing 3200:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3200,
,I/ActivityManager(  891): Displayed com.example.hello/.MainActivity: +712ms,
,I/ActivityManager(  891): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3544 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  891): Killing 3223:com.htc.calendar/u0a10 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3223,
,I/ActivityManager(  891): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3574 uid=10057 gids={50057, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
,I/ActivityManager(  891): Killing 3247:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3247
,W/jxcore-log( 3405): Initializing JXcore engine
W/jxcore-log( 3405): JXcore engine is ready
,W/jxcore-log( 3405): Starting JXcore engine
,I/ActivityManager(  891): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3591 uid=10057 gids={50057, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
,I/ActivityManager(  891): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3607 uid=10061 gids={50061, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/ActivityManager(  891): Killing 3267:com.htc.fm/u0a20 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3267,
,W/jxcore-log( 3405): Platform android,
W/jxcore-log( 3405): 
W/jxcore-log( 3405): Process ARCH arm
W/jxcore-log( 3405): 
,I/jxcore-log( 3405): JXcore Cordova bridge is ready!,
I/jxcore-log( 3405): 
W/jxcore-log( 3405): JXcore engine is started
,E/jxcore-log( 3405): >> HTC-HTC One_M8
E/jxcore-log( 3405): 
,I/jxcore-log( 3405): Total memory 1912020992
I/jxcore-log( 3405): 
I/jxcore-log( 3405): Free memory 187838464
I/jxcore-log( 3405): 
I/jxcore-log( 3405): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3405): 
I/jxcore-log( 3405): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3405): 
,I/jxcore-log( 3405): userPath [ 'www' ]
I/jxcore-log( 3405): 
,I/jxcore-log( 3405): Size 1080 1776
I/jxcore-log( 3405): 
,I/jxcore-log( 3405): Screen Brightness 142,
I/jxcore-log( 3405): 
E/jxcore-log( 3405): Dummy Error Log.
E/jxcore-log( 3405): 
,I/ActivityManager(  891): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3635 uid=10066 gids={50066, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 3286:com.fitbit.FitbitMobile/u0a23 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3286,
,I/ActivityManager(  891): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=3679 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 1024} abi=armeabi-v7a,
I/ActivityManager(  891): Killing 1892:com.htc.bgp/u0a11 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 1892,
,I/ActivityManager(  891): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3731 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/jxcore-log( 3405): getBuffer is called!!!!
I/jxcore-log( 3405): 
,I/ActivityManager(  891): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3760 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3796 uid=10079 gids={50079, 9997} abi=armeabi-v7a,
,I/ActivityManager(  891): Killing 3313:com.google.android.onetimeinitializer/u0a27 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3313
,I/ActivityManager(  891): Killing 3366:com.htc.video/u0a30 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3366
,I/ActivityManager(  891): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3820 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  891): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3839 uid=10087 gids={50087, 9997, 1007, 3003, 1028} abi=armeabi-v7a,
I/ActivityManager(  891): Killing 2056:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 2056
,I/ActivityManager(  891): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3857 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a,
,I/ActivityManager(  891): Killing 3388:com.htc.csrecommend/u0a32 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3388
,I/ActivityManager(  891): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/.BootReceiver: pid=3891 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager(  891): Killing 3342:com.google.android.partnersetup/u0a28 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3342
,I/ActivityManager(  891): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3912 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.htc.tiber2 for service com.htc.videohub.ui/com.htc.htcircontrol.HtcIrService: pid=3930 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
,I/ActivityManager(  891): Resuming delayed broadcast
,I/ActivityManager(  891): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3960 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  891): Killing 3425:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3425
,I/ActivityManager(  891): Killing 2668:com.htc.contacts/u0a40 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 2668
,I/ActivityManager(  891): Killing 3448:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3448
,I/ActivityManager(  891): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4016 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 3479:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3479,
,I/ActivityManager(  891): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4039 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 3498:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3498,
,I/ActivityManager(  891): Killing 3523:com.htc.musicenhancer/u0a51 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3523,
I/ActivityManager(  891): Killing 3544:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  891): Recipient 3544
,I/ActivityManager(  891): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  891): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4098 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a,
I/ActivityManager(  891): Killing 3574:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3574
,I/ActivityManager(  891): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4118 uid=10163 gids={50163, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 4098): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider,
,I/ActivityManager(  891): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  891): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4170 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 3607:com.htc.lmw/u0a61 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3607
,I/ActivityManager(  891): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4205 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 3635:com.android.managedprovisioning/u0a66 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3635
,I/ActivityManager(  891): Killing 1997:com.google.android.gms/u0a25 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 1997
,I/ActivityManager(  891): Killing 3760:com.htc.cs.pns/u0a74 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3760
,I/ActivityManager(  891): Killing 3796:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3796
,I/ActivityManager(  891): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 3820:com.htc.showme/u0a85 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3820
,I/jxcore-log( 3405): ****TEST TOOK:  5091  ms ****,
I/jxcore-log( 3405): 
I/jxcore-log( 3405): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,I/jxcore-log( 3405): 
,I/ActivityManager(  891): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4253 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  891): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg,
I/ActivityManager(  891): Killing 3405:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  891): Recipient 3405,
,W/ActivityManager(  891): Force removing ActivityRecord{1c1e49fd u0 com.example.hello/.MainActivity t27}: app died, no saved state
,W/ActivityManager(  891): Spurious death for ProcessRecord{1386f4bb 3405:com.example.hello/u0a380}, curProc for 3405: null
,I/ActivityManager(  891): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  891): Killing 3839:com.htc.feedback/u0a87 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3839,
,I/ActivityManager(  891): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4318 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4339 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
I/ActivityManager(  891): Killing 3857:com.htc.updater/u0a88 (adj 15): empty #17
,I/ActivityManager(  891): Recipient 3857,
,W/ActivityThread( 4318): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  891): Killing 3912:com.htc.android.worldclock/u0a96 (adj 15): empty #17,
,W/ActivityThread( 4339): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  891): Recipient 3912
,I/ActivityManager(  891): Killing 3891:com.htc.videocenter/u0a91 (adj 15): empty #17,
,I/ActivityManager(  891): Recipient 3891
,E/ActivityManager(  891): App crashed! Process: com.google.android.gms


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
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1019): mDVFSHelper.acquire()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5418 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5418): Added TimaKeyStore provider
V/ActivityManager( 1019): Display changed displayId=0
V/ActivityThread( 1482): updateVisibility : ActivityRecord{1f465ee9 token=android.os.BinderProxy@960b86f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false,
,V/ActivityThread( 5418): updateVisibility : ActivityRecord{15274f40 token=android.os.BinderProxy@aa40672 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1019): Displayed Component not be shown by security: +586ms (total +665ms),
W/ActivityManager( 1019): mDVFSHelper.release(),
,W/jxcore-log( 5418): Initializing JXcore engine
W/jxcore-log( 5418): JXcore engine is ready
,W/jxcore-log( 5418): Starting JXcore engine
,W/jxcore-log( 5418): Platform android
W/jxcore-log( 5418): 
,W/jxcore-log( 5418): Process ARCH arm
W/jxcore-log( 5418): 
,I/jxcore-log( 5418): JXcore Cordova bridge is ready!
I/jxcore-log( 5418): 
,W/jxcore-log( 5418): JXcore engine is started
,E/jxcore-log( 5418): >> samsung-SM-A300FU
E/jxcore-log( 5418): 
,I/jxcore-log( 5418): Total memory 1451114496
I/jxcore-log( 5418): 
I/jxcore-log( 5418): Free memory 25513984
I/jxcore-log( 5418): 
I/jxcore-log( 5418): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5418): 
I/jxcore-log( 5418): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): userPath [ 'www' ]
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): Size 540 960
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): Screen Brightness 160
I/jxcore-log( 5418): 
E/jxcore-log( 5418): Dummy Error Log.
E/jxcore-log( 5418): 
,I/jxcore-log( 5418): getBuffer is called!!!!
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 5418): 
,I/jxcore-log( 5418): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5418): 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 5418:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{2907236f u0 com.example.hello/.MainActivity t19}
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=0: pkg removed,
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5484 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 5484): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/ActivityManager( 1019): Killing 4925:com.wssyncmldm/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5504 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,D/ActivityThread( 5504): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5521 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4946:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/ActivityThread( 5521): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5537 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5537): Added TimaKeyStore provider
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,D/ActivityThread( 5553): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain


HTC-HTC One M8s: 
--------- beginning of system
I/ActivityManager(  943): Recipient 4421
--------- beginning of main
,I/ActivityManager(  943): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5012 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  943): Killing 4500:com.google.android.gm/u0a106 (adj 15): empty #17
I/ActivityManager(  943): Recipient 4500
I/ActivityManager(  943): Killing 3736:com.android.defcontainer/u0a15 (adj 15): empty #17
I/ActivityManager(  943): Recipient 3736
I/ActivityManager(  943): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5069 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  943): Killing 4577:com.google.android.partnersetup/u0a27 (adj 15): empty #17
I/ActivityManager(  943): Recipient 4577
I/ActivityManager(  943): Killing 4546:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
I/ActivityManager(  943): Recipient 4546
I/ActivityManager(  943): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 5037 on display 0
I/ActivityManager(  943): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5101 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  943): Killing 4679:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
W/ActivityThread( 5012): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  943): Recipient 4679
I/ActivityManager(  943): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5129 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  943): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5160 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  943): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5196 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  943): Killing 4707:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
I/ActivityManager(  943): Recipient 4707
I/ActivityManager(  943): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5241 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  943): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5268 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  943): Killing 4756:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
I/ActivityManager(  943): Recipient 4756
I/ActivityManager(  943): Displayed com.example.hello/.MainActivity: +1s372ms
I/ActivityManager(  943): Killing 4800:com.htc.mobiledata/u0a46 (adj 15): empty #17
I/ActivityManager(  943): Recipient 4800
I/ActivityManager(  943): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5299 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/ActivityManager(  943): Killing 4387:com.google.android.talk/u0a112 (adj 15): empty #17
I/ActivityManager(  943): Recipient 4387
W/jxcore-log( 5101): Initializing JXcore engine
W/jxcore-log( 5101): JXcore engine is ready
W/jxcore-log( 5101): Starting JXcore engine
I/ActivityManager(  943): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5324 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  943): Killing 4829:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  943): Recipient 4829,
,I/ActivityManager(  943): Killing 4859:com.htc.backupreset/1000 (adj 15): empty #17
W/jxcore-log( 5101): Platform android
W/jxcore-log( 5101): 
W/jxcore-log( 5101): Process ARCH arm
W/jxcore-log( 5101): 
,I/jxcore-log( 5101): JXcore Cordova bridge is ready!
I/jxcore-log( 5101): 
,W/jxcore-log( 5101): JXcore engine is started
,I/ActivityManager(  943): Recipient 4859,
E/jxcore-log( 5101): >> HTC-HTC One M8s
E/jxcore-log( 5101): 
,I/jxcore-log( 5101): Total memory 1931808768,
I/jxcore-log( 5101): 
I/jxcore-log( 5101): Free memory 84992000
I/jxcore-log( 5101): 
I/jxcore-log( 5101): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5101): 
I/jxcore-log( 5101): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5101): 
,I/jxcore-log( 5101): userPath [ 'www' ],
I/jxcore-log( 5101): 
,I/jxcore-log( 5101): Size 1080 1776
I/jxcore-log( 5101): 
I/jxcore-log( 5101): Screen Brightness 142
I/jxcore-log( 5101): 
E/jxcore-log( 5101): Dummy Error Log.
E/jxcore-log( 5101): 
,I/ActivityManager(  943): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4111): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  943): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4111): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  943): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5365 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager(  943): Killing 4907:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/jxcore-log( 5101): getBuffer is called!!!!,
I/jxcore-log( 5101): 
,I/ActivityManager(  943): Recipient 4907
,W/ActivityThread( 5365): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  943): Killing 4932:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17,
,I/ActivityManager(  943): Recipient 4932
,I/ActivityManager(  943): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5405 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/ActivityManager(  943): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5451 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  943): Killing 4778:com.htc.task/u0a69 (adj 15): empty #17,
,I/ActivityManager(  943): Recipient 4778,
,I/ActivityManager(  943): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5484 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/ActivityManager(  943): Killing 4978:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
,I/ActivityManager(  943): Recipient 4978
,I/ActivityManager(  943): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5506 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,I/ActivityManager(  943): Killing 5069:com.htc.task.gtask/u0a66 (adj 15): empty #17,
,I/ActivityManager(  943): Recipient 5069,
,I/ActivityManager(  943): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  943): Resuming delayed broadcast
,I/ActivityManager(  943): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  943): Resuming delayed broadcast,
,I/ActivityManager(  943): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5560 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,I/ActivityManager(  943): Killing 3698:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  943): Recipient 3698
,I/ActivityManager(  943): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5586 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager(  943): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5616 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/ActivityManager(  943): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5642 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/ActivityManager(  943): Killing 4882:com.htc.bgp/u0a11 (adj 15): empty #17,
,I/ActivityManager(  943): Recipient 4882,
,W/ActivityManager(  943): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  943): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found,
,W/ActivityManager(  943): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  943): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  943): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5692 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  943): Killing 4729:com.htc.sense.news/u0a74 (adj 15): empty #17
,I/jxcore-log( 5101): ****TEST TOOK:  5112  ms ****,
I/jxcore-log( 5101): 
I/jxcore-log( 5101): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5101): 
,I/ActivityManager(  943): Recipient 4729
,I/ActivityManager(  943): Killing 5241:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
,I/ActivityManager(  943): Recipient 5241,
,I/ActivityManager(  943): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=5728 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/ActivityManager(  943): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5745 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  943): Killing 5268:com.htc.cs.dm/u0a99 (adj 15): empty #17
,I/ActivityManager(  943): Recipient 5268
,I/ActivityManager(  943): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  943): Resuming delayed broadcast
,I/ActivityManager(  943): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  943): Resuming delayed broadcast
I/ActivityManager(  943): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
I/ActivityManager(  943): Killing 5101:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  943): Recipient 5101,
,W/ActivityManager(  943): Force removing ActivityRecord{3c51dc4 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,W/ActivityManager(  943): Spurious death for ProcessRecord{26c1c9b3 5101:com.example.hello/u0a373}, curProc for 5101: null
,I/ActivityManager(  943): Force stopping com.example.hello appid=10373 user=0: pkg removed
,I/ActivityManager(  943): Delay finish: com.google.android.gms/.fitness.service.FitnessInitReceiver
,I/ActivityManager(  943): Resuming delayed broadcast,
,I/ActivityManager(  943): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=5829 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  943): Killing 5299:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
,I/ActivityManager(  943): Recipient 5299,
,I/ActivityManager(  943): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5870 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,I/ActivityManager(  943): Killing 5405:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,I/ActivityManager(  943): Recipient 5405
,E/ActivityManager(  943): App crashed! Process: com.nero.android.htc.sync
,W/ActivityManager(  943): Can't addPackageDependency on system process,


LGE-LG-D802: 
--------- beginning of /dev/log/system
--------- beginning of /dev/log/main
I/ActivityManager(  965): Killing 3380:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4390e5d0 stackId=1, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3935
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4390e5d0 stackId=1, 2 tasks}
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  965): startService SlideAside
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{4390e5d0 stackId=1, 2 tasks}
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4390e5d0 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  965): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3957 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/ActivityManager(  965): Displayed com.example.hello/.MainActivity: +434ms
I/ActivityManager( 3957): Timeline: Activity_idle id: android.os.BinderProxy@42f7c460 time:46954
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3} time:47267
D/ActivityManager(  965): no-history finish of ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{439ecea8 ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
W/jxcore-log( 3957): Initializing JXcore engine
W/jxcore-log( 3957): JXcore engine is ready
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 3957): Starting JXcore engine
,W/jxcore-log( 3957): Platform android
W/jxcore-log( 3957): 
,W/jxcore-log( 3957): Process ARCH arm
W/jxcore-log( 3957): 
,I/jxcore-log( 3957): JXcore Cordova bridge is ready!
I/jxcore-log( 3957): 
,W/jxcore-log( 3957): JXcore engine is started
,E/jxcore-log( 3957): >> LGE-LG-D802
E/jxcore-log( 3957): 
,I/jxcore-log( 3957): Total memory 1943035904
I/jxcore-log( 3957): 
I/jxcore-log( 3957): Free memory 467435520
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): userPath [ 'www' ]
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): Size 1080 1776
I/jxcore-log( 3957): 
,I/jxcore-log( 3957): Screen Brightness 255
I/jxcore-log( 3957): 
,E/jxcore-log( 3957): Dummy Error Log.
E/jxcore-log( 3957): 
,I/jxcore-log( 3957): getBuffer is called!!!!
I/jxcore-log( 3957): 
,I/ActivityManager(  965): Killing 3444:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4390e5d0 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3957): ****TEST TOOK:  5074  ms ****
I/jxcore-log( 3957): 
I/jxcore-log( 3957): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3957): 
,I/ActivityManager(  965): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,I/ActivityManager(  965): Killing 3957:com.example.hello/u0a311 (adj 0): stop com.example.hello
,W/ActivityManager(  965): Force removing ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{4348ad38 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4390e5d0 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  965): moveHomeStack:
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  965): resumeTopActivityLocked: Resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/ActivityManager(  965): Force stopping com.example.hello appid=10311 user=0: pkg removed
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4055 uid=10090 gids={50090}
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{43397fd0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4077 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  965): Killing 3331:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  965): Service ServiceRecord{4390d268 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43999960 3331:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  965): Service ServiceRecord{43901288 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43999960 3331:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Killing 3007:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4104 uid=10065 gids={50065, 1028, 4002}
,I/ActivityManager(  965): Delaying start of: ServiceRecord{43bec200 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/ActivityManager(  965): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4124 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  965): Killing 3771:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  965): Killing 3241:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4139 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1} time:54267
,I/ActivityManager(  965): Killing 3826:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Delaying start of: ServiceRecord{43acbf00 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager(  965): Process android.process.media (pid 4139) has died.
,I/ActivityManager(  965): Start proc android.process.media for restart android.process.media: pid=4155 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42f76138 time:54348
,I/ActivityManager(  965): Process android.process.media (pid 4155) has died.
,I/ActivityManager(  965): Start proc android.process.media for restart android.process.media: pid=4168 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Process com.google.android.gms (pid 1943) has died.
W/ActivityManager(  965): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  965): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  965): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
W/ActivityManager(  965): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
W/ActivityManager(  965): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  965): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20998ms
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Process android.process.media (pid 4168) has died.
,W/ActivityManager(  965): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 20982ms
,I/ActivityManager(  965): Start proc android.process.media for restart android.process.media: pid=4186 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Process android.process.media (pid 4186) has died.
,W/ActivityManager(  965): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 83928ms
I/ActivityManager(  965): Start proc android.process.media for restart android.process.media: pid=4201 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): Process android.process.media (pid 4201) has died.
,W/ActivityManager(  965): Canceling start item Intent { cmp=com.android.providers.downloads/.DownloadService } in service ComponentInfo{com.android.providers.downloads/com.android.providers.downloads.DownloadService}
W/ActivityManager(  965): Canceling start item Intent { cmp=com.android.providers.downloads/.DownloadService } in service ComponentInfo{com.android.providers.downloads/com.android.providers.downloads.DownloadService}
W/ActivityManager(  965): Canceling start item Intent { cmp=com.android.providers.downloads/.DownloadService } in service ComponentInfo{com.android.providers.downloads/com.android.providers.downloads.DownloadService}
,W/ActivityManager(  965): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 335712ms
I/ActivityManager(  965): Start proc android.process.media for restart android.process.media: pid=4217 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{432f5688 stackId=0, 1 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{4330e360 u0 com.lge.launcher2/.Launcher t1}


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
--------- beginning of system
I/ActivityManager( 1017): Waited long enough for: ServiceRecord{2e050eb4 u0 com.sec.bcservice/.BroadcastService}
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5372 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
V/ActivityThread( 1480): updateVisibility : ActivityRecord{27135eee token=android.os.BinderProxy@2e01faed {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 5372): Added TimaKeyStore provider
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 4623:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.async.BackgroundTaskService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 4704:com.policydm/1000 (adj 15): empty #31
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ActivityManager( 1017): Display changed displayId=0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1017): mDVFSHelper.acquire()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5411 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5411): Added TimaKeyStore provider
V/ActivityManager( 1017): Display changed displayId=0
V/ActivityThread( 1480): updateVisibility : ActivityRecord{27135eee token=android.os.BinderProxy@2e01faed {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{351910b3 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,V/ActivityThread( 5411): updateVisibility : ActivityRecord{92ccc73 token=android.os.BinderProxy@3aadd5ad {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager( 1017): Displayed Component not be shown by security: +531ms (total +602ms)
,W/ActivityManager( 1017): mDVFSHelper.release()
,W/jxcore-log( 5411): Initializing JXcore engine
,W/jxcore-log( 5411): JXcore engine is ready
,W/jxcore-log( 5411): Starting JXcore engine
,W/jxcore-log( 5411): Platform android
W/jxcore-log( 5411): 
W/jxcore-log( 5411): Process ARCH arm
W/jxcore-log( 5411): 
,I/jxcore-log( 5411): JXcore Cordova bridge is ready!
I/jxcore-log( 5411): 
,W/jxcore-log( 5411): JXcore engine is started
,E/jxcore-log( 5411): >> samsung-SM-A500FU
E/jxcore-log( 5411): 
,I/jxcore-log( 5411): Total memory 1983787008
I/jxcore-log( 5411): 
,I/jxcore-log( 5411): Free memory 42860544
I/jxcore-log( 5411): 
,I/jxcore-log( 5411): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5411): 
,I/jxcore-log( 5411): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5411): 
,I/jxcore-log( 5411): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5411): 
,I/jxcore-log( 5411): Size 720 1280
I/jxcore-log( 5411): 
,I/jxcore-log( 5411): Screen Brightness 255
I/jxcore-log( 5411): 
,E/jxcore-log( 5411): Dummy Error Log.
E/jxcore-log( 5411): 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5411): getBuffer is called!!!!
I/jxcore-log( 5411): 
,I/ActivityManager( 1017): Killing 4689:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 5411): ****TEST TOOK:  5042  ms ****
I/jxcore-log( 5411): 
,I/jxcore-log( 5411): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5411): 
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 5411:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{306a6605 u0 com.example.hello/.MainActivity t11}
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5492 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5507 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 5492): Added TimaKeyStore provider
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=5516 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/ActivityThread( 5507): Added TimaKeyStore provider
,D/ActivityThread( 5516): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5538 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityThread( 5538): Added TimaKeyStore provider
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{898d917 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5556 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,I/ActivityManager( 1017): Killing 4759:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,D/ActivityThread( 5556): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5572 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityThread( 5572): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4796:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 4821:com.osp.app.signin/u0a41 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5587 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityThread( 5587): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityThread( 5572): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=5606 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5615 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/ActivityThread( 5606): Added TimaKeyStore provider
,D/ActivityThread( 5615): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4960:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5637 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5007:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,D/ActivityThread( 5637): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5654 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 4406:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/ActivityThread( 5654): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5106:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5129:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5150:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5688 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5704 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a,
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityThread( 5688): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
W/ActivityManager(  873): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager(  873): Killing 3861:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
W/ActivityManager(  873): getTasks: caller 10163 does not hold GET_TASKS; limiting output
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  873): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4897 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  873): Process com.android.email (pid 4752)(adj 9) has died(71,655)
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4897): Added TimaKeyStore provider
I/ActivityManager(  873): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4913 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/ActivityThread( 4913): Added TimaKeyStore provider
I/ActivityManager(  873): Killing 3876:com.google.android.onetimeinitializer/u0a14 (adj 15): bgCount ##41
I/ActivityManager(  873): Killing 3896:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
I/ActivityManager(  873): Process com.sec.android.app.sns3 (pid 4774)(adj 0) has died(72,657)
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  873): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4931 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  873): Killing 2081:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##41
D/ActivityThread( 4931): Added TimaKeyStore provider
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  873): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  873): Killing 3913:com.sec.usbsettings/1000 (adj 15): bgCount ##41
D/ActivityThread( 4951): Added TimaKeyStore provider
W/ActivityManager(  873): getTasks: caller 10164 does not hold GET_TASKS; limiting output
I/ActivityManager(  873): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  873): mDVFSHelper.acquire()
I/ActivityManager(  873): Process com.android.exchange (pid 4866)(adj 11) has died(69,661)
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  873): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4983 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 4983): Added TimaKeyStore provider
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  873): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4999 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 4999): Added TimaKeyStore provider
W/ActivityManager(  873): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  873): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=5029 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  873): Killing 3932:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
D/ActivityThread( 5029): Added TimaKeyStore provider
D/ActivityManager(  873): post active user change for 0
I/ActivityManager(  873): Killing 3940:com.samsung.android.provider.filterprovider/u0a109 (adj 15): bgCount ##41
I/ActivityManager(  873): Displayed com.example.hello/.MainActivity: +746ms
W/ActivityManager(  873): mDVFSHelper.release()
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  873): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5077 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/ActivityThread( 5077): Added TimaKeyStore provider
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  873): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5097 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,W/ActivityThread( 5077): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 5097): Added TimaKeyStore provider
,W/jxcore-log( 4983): Initializing JXcore engine
W/jxcore-log( 4983): JXcore engine is ready
,W/jxcore-log( 4983): Starting JXcore engine
,W/jxcore-log( 4983): Platform android
W/jxcore-log( 4983): 
W/jxcore-log( 4983): Process ARCH arm
W/jxcore-log( 4983): 
,I/jxcore-log( 4983): JXcore Cordova bridge is ready!
I/jxcore-log( 4983): 
W/jxcore-log( 4983): JXcore engine is started
,I/ActivityManager(  873): Killing 3964:com.samsung.android.nearby.mediaserver/u0a76 (adj 15): bgCount ##41
,E/jxcore-log( 4983): >> samsung-SM-G900F
E/jxcore-log( 4983): 
,I/jxcore-log( 4983): Total memory 1787449344
I/jxcore-log( 4983): 
I/jxcore-log( 4983): Free memory 47611904
I/jxcore-log( 4983): 
I/jxcore-log( 4983): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4983): 
I/jxcore-log( 4983): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4983): 
,I/jxcore-log( 4983): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4983): 
,I/jxcore-log( 4983): Size 1080 1920
I/jxcore-log( 4983): 
I/jxcore-log( 4983): Screen Brightness 134
I/jxcore-log( 4983): 
E/jxcore-log( 4983): Dummy Error Log.
E/jxcore-log( 4983): 
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  873): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 5132): Added TimaKeyStore provider
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  873): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5150 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 5150): Added TimaKeyStore provider
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  873): Start proc com.sec.factory for broadcast com.sec.factory/.entry.ProtectedFactoryTestBroadcastReceiver: pid=5166 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  873): Killing 3984:com.samsung.klmsagent/u0a19 (adj 15): bgCount ##41
,D/ActivityThread( 5166): Added TimaKeyStore provider
,I/jxcore-log( 4983): getBuffer is called!!!!
I/jxcore-log( 4983): 
,I/ActivityManager(  873): Killing 4000:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  873): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5181 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  873): Killing 3187:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,D/ActivityThread( 5181): Added TimaKeyStore provider


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
--------- beginning of system,
--------- beginning of main
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1013): mDVFSHelper.acquire()
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1013): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5076 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 5076): Added TimaKeyStore provider
V/ActivityManager( 1013): Display changed displayId=0
V/ActivityThread( 1472): updateVisibility : ActivityRecord{2a63a6cc token=android.os.BinderProxy@b3a897c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/ActivityManager( 1013): Activity pause timeout for ActivityRecord{b08b7c5 u0 com.example.hello/.MainActivity t10}
D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
V/ActivityThread( 5076): updateVisibility : ActivityRecord{391369d4 token=android.os.BinderProxy@faeb1e6 {com.example.hello/com.example.hello.MainActivity}} show : true
I/ActivityManager( 1013): Displayed Component not be shown by security: +615ms (total +698ms)
W/ActivityManager( 1013): mDVFSHelper.release()
W/jxcore-log( 5076): Initializing JXcore engine
W/jxcore-log( 5076): JXcore engine is ready
W/jxcore-log( 5076): Starting JXcore engine
,W/jxcore-log( 5076): Platform android
W/jxcore-log( 5076): 
W/jxcore-log( 5076): Process ARCH arm
W/jxcore-log( 5076): 
,I/jxcore-log( 5076): JXcore Cordova bridge is ready!
I/jxcore-log( 5076): 
,W/jxcore-log( 5076): JXcore engine is started
,E/jxcore-log( 5076): >> samsung-SM-A300FU
E/jxcore-log( 5076): 
,I/jxcore-log( 5076): Total memory 1451114496
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): Free memory 26083328
I/jxcore-log( 5076): 
I/jxcore-log( 5076): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5076): 
I/jxcore-log( 5076): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): userPath [ 'www' ]
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): Size 540 960
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): Screen Brightness 255
I/jxcore-log( 5076): 
,E/jxcore-log( 5076): Dummy Error Log.
E/jxcore-log( 5076): 
,I/jxcore-log( 5076): getBuffer is called!!!!
I/jxcore-log( 5076): 
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{1aed61dc u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 5076): ****TEST TOOK:  5059  ms ****
I/jxcore-log( 5076): 
,I/jxcore-log( 5076): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5076): 
,I/ActivityManager( 1013): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,I/ActivityManager( 1013): Killing 5076:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1013):   Force finishing activity ActivityRecord{b08b7c5 u0 com.example.hello/.MainActivity t10}
,I/ActivityManager( 1013): Force stopping com.example.hello appid=10333 user=0: pkg removed
,W/ActivityManager( 1013): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5144 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5159 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 5144): Added TimaKeyStore provider
,D/ActivityThread( 5159): Added TimaKeyStore provider
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5176 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5189 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 5176): Added TimaKeyStore provider
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityThread( 5189): Added TimaKeyStore provider
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5212 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 5212): Added TimaKeyStore provider
,I/ActivityManager( 1013): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5226 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1013): Killing 4476:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityThread( 5226): Added TimaKeyStore provider
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5244 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 4218:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5244): Added TimaKeyStore provider
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5226): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5270 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 5270): Added TimaKeyStore provider
,I/ActivityManager( 1013): Killing 4165:com.google.android.music:main/u0a108 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 3556:com.google.android.talk/u0a102 (adj 15): empty #31
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/ActivityManager( 1013): Killing 4567:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 4584:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1013): Killing 4691:com.google.android.gms:car/u0a11 (adj 15): empty #31


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager(  903): Waited long enough for: ServiceRecord{4248a928 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=2198 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.qualcomm.privinit for broadcast com.qualcomm.privinit/.BootReciever: pid=2218 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Killing 1801:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
I/ActivityManager(  903): Recipient 1801
I/ActivityManager(  903): Killing 1820:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=2232 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  903): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=2244 uid=10021 gids={50021, 1028, 1015, 1023, 1024, 5001, 2001, 3003, 5012, 3007}
I/ActivityManager(  903): Killing 1263:com.android.printspooler/u0a161 (adj 15): empty #17
I/ActivityManager(  903): Recipient 1820
I/ActivityManager(  903): Delay finish: com.android.providers.calendar/.CalendarReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2265 uid=10016 gids={50016, 3003, 5012, 2001}
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2194
I/ActivityManager(  903): Recipient 1263
I/ActivityManager(  903): Killing 1909:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  903): Recipient 1909
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2283 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/ActivityManager(  903): Killing 1961:com.htc.zero:re_proc/u0a34 (adj 15): empty #17
I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=2306 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Recipient 1961
I/ActivityManager(  903): Delay finish: com.android.providers.downloads/.DownloadReceiver
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=2336 uid=10024 gids={50024, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 1974:com.htc.showme/u0a82 (adj 15): empty #17
I/ActivityManager(  903): Recipient 1974
I/ActivityManager(  903): Killing 1866:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
,I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +268ms
,I/ActivityManager(  903): Recipient 1866
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/ActivityManager(  903): Unable to start service Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.fitness.service.BrokeredFitnessService (has extras) } U=0: not found
,W/jxcore-log( 2283): Initializing JXcore engine
,W/jxcore-log( 2283): JXcore engine is ready
,W/jxcore-log( 2283): Starting JXcore engine
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2391 uid=10030 gids={50030}
,I/ActivityManager(  903): Delay finish: com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=2405 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  903): Killing 1845:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.GooglePartnerSetup
,W/jxcore-log( 2283): Platform android
W/jxcore-log( 2283): 
,W/jxcore-log( 2283): Process ARCH arm
W/jxcore-log( 2283): 
,I/ActivityManager(  903): Recipient 1845
,I/jxcore-log( 2283): JXcore Cordova bridge is ready!
I/jxcore-log( 2283): 
,W/jxcore-log( 2283): JXcore engine is started
,E/jxcore-log( 2283): >> HTC-HTC Desire 820
E/jxcore-log( 2283): 
,I/jxcore-log( 2283): Total memory 1964650496
I/jxcore-log( 2283): 
I/jxcore-log( 2283): Free memory 836411392
I/jxcore-log( 2283): 
I/jxcore-log( 2283): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2283): 
,I/jxcore-log( 2283): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2283): 
,I/jxcore-log( 2283): userPath [ 'www' ]
I/jxcore-log( 2283): 
,I/jxcore-log( 2283): Size 720 1184
I/jxcore-log( 2283): 
,I/jxcore-log( 2283): Screen Brightness 10
I/jxcore-log( 2283): 
,E/jxcore-log( 2283): Dummy Error Log.
E/jxcore-log( 2283): 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 2042:com.futuredial/u0a83 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2042
,I/ActivityManager(  903): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=2430 uid=10033 gids={50033, 3003, 5012}
,I/ActivityManager(  903): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=2442 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  903): Killing 1927:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 1927
,I/ActivityManager(  903): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=2456 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  903): Killing 2057:com.htc.lucy/u0a62 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2057
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=2473 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  903): Killing 2076:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2076
,I/ActivityManager(  903): Killing 2096:com.htc.wifidisplay/u0a153 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2096
I/ActivityManager(  903): Start proc com.htc.aurora for broadcast com.htc.aurora/.receiver.BootCompletedReceiver: pid=2485 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/jxcore-log( 2283): getBuffer is called!!!!
I/jxcore-log( 2283): 
,I/ActivityManager(  903): Start proc com.htc.aurora:remote for service com.htc.aurora/.download.DownloadService: pid=2499 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,I/ActivityManager(  903): Delay finish: com.htc.aurora/.receiver.BootCompletedReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2515 uid=10050 gids={50050, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
,I/ActivityManager(  903): Killing 1628:com.google.android.gms.wearable/u0a28 (adj 15): empty #17
,I/ActivityManager(  903): Killing 1948:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 1948
,I/ActivityManager(  903): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2530 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  903): Killing 2198:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 1628
,I/ActivityManager(  903): Killing 2218:com.qualcomm.privinit/1000 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2218
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2543 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 2232:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  903): Recipient 2232
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.upservice.HtcUPServiceReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=2569 uid=10055 gids={50055, 1028, 1015, 3003, 5012, 3001, 3002}
,I/ActivityManager(  903): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2581 uid=10056 gids={50056, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  903): Killing 2265:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2265
,I/ActivityManager(  903): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2596 uid=10059 gids={50059, 1028, 1015, 3003, 5012, 1023}
,I/ActivityManager(  903): Killing 2306:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  903): Delay finish: com.htc.lmw/.StorageBroadcastReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.android.providers.media/.MediaScannerReceiver
,I/ActivityManager(  903): Recipient 2306
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{4256b718 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2613 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  903): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2636 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/ActivityManager(  903): Killing 2336:com.htc.fm/u0a24 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2336
,I/ActivityManager(  903): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{425c35a0 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2657 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2689 uid=10077 gids={50077}
,I/ActivityManager(  903): Killing 2391:com.google.android.onetimeinitializer/u0a30 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2391
,I/ActivityManager(  903): Killing 2405:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2405
,I/ActivityManager(  903): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2705 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,I/ActivityManager(  903): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2720 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
I/ActivityManager(  903): Killing 2430:com.htc.csrecommend/u0a33 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2430
,I/ActivityManager(  903): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2734 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
,I/ActivityManager(  903): Killing 2442:com.htc.home.personalize/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2442
,I/ActivityManager(  903): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=2749 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
,I/ActivityManager(  903): Killing 2456:com.htc.contacts/u0a41 (adj 15): empty #17
,I/jxcore-log( 2283): ****TEST TOOK:  5048  ms ****
I/jxcore-log( 2283): 
I/jxcore-log( 2283): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2283): 
,I/ActivityManager(  903): Recipient 2456
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,I/ActivityManager(  903): Killing 2283:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  903): Force removing ActivityRecord{4257c578 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  903): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 2473:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2473
,I/ActivityManager(  903): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=2824 uid=10090 gids={50090, 3003, 5012, 1028}
,I/ActivityManager(  903): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=2845 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  903): Killing 2485:com.htc.aurora/u0a47 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2485
,I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2858 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  903): Killing 2499:com.htc.aurora:remote/u0a47 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2499
,I/ActivityManager(  903): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=2873 uid=10098 gids={50098, 3003, 5012}
,I/ActivityManager(  903): Killing 2515:com.htc.music:mediaplaybackservice/u0a50 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2515
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
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2997 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2982
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3041 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  906): Killing 2660:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2660
I/ActivityManager(  906): Delay finish: com.android.settings/.NSReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3071 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +290ms
I/ActivityManager(  906): Killing 2453:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2453
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3131 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3143 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2689:com.google.android.gm/u0a107 (adj 15): empty #17
W/jxcore-log( 3041): Initializing JXcore engine
W/jxcore-log( 3041): JXcore engine is ready
I/ActivityManager(  906): Killing 2674:com.htc.cs.dm/u0a98 (adj 15): empty #17
W/jxcore-log( 3041): Starting JXcore engine
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3158 uid=10041 gids={50041}
I/ActivityManager(  906): Recipient 2689
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3174 uid=10078 gids={50078}
I/ActivityManager(  906): Killing 2758:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2758
I/ActivityManager(  906): Recipient 2674
I/ActivityManager(  906): Killing 2735:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3186 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
W/jxcore-log( 3041): Platform android
W/jxcore-log( 3041): 
W/jxcore-log( 3041): Process ARCH arm
W/jxcore-log( 3041): 
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3202 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  906): Recipient 2735
I/ActivityManager(  906): Killing 2786:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2786
I/jxcore-log( 3041): JXcore Cordova bridge is ready!
I/jxcore-log( 3041): 
W/jxcore-log( 3041): JXcore engine is started
I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3217 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
E/jxcore-log( 3041): >> HTC-HTC Desire 820
E/jxcore-log( 3041): 
I/jxcore-log( 3041): Total memory 1964650496
I/jxcore-log( 3041): 
I/jxcore-log( 3041): Free memory 704155648
I/jxcore-log( 3041): 
I/jxcore-log( 3041): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3041): 
I/jxcore-log( 3041): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3041): 
I/jxcore-log( 3041): userPath [ 'www' ]
I/jxcore-log( 3041): 
I/jxcore-log( 3041): Size 720 1184
I/jxcore-log( 3041): 
I/jxcore-log( 3041): Screen Brightness 142
I/jxcore-log( 3041): 
E/jxcore-log( 3041): Dummy Error Log.
E/jxcore-log( 3041): 
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3231 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 2803:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2803
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3246 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  906): Killing 2818:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2818
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3258 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3270 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  906): Killing 2872:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  906): Killing 2844:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  906): Recipient 2872
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2887:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2887
,I/ActivityManager(  906): Recipient 2844
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3287 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3301 uid=10091 gids={50091, 3003, 5012}
,I/jxcore-log( 3041): getBuffer is called!!!!
I/jxcore-log( 3041): 
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 2899:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  906): Killing 2997:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  906): Recipient 2899
I/ActivityManager(  906): Recipient 2997
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3326 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3071:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3347 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Recipient 3071
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3131:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3364 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  906): Recipient 3131
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3382 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3143:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3143
,I/ActivityManager(  906): Killing 3186:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3186
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3404 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3423 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  906): Killing 2832:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2832
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/jxcore-log( 3041): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 3041): 
,I/jxcore-log( 3041): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3041): 
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3246:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  906): Recipient 3246
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  906): Killing 3041:com.example.hello/u0a396 (adj 0): stop com.example.hello
,W/ActivityManager(  906): Force removing ActivityRecord{425c68f0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3462 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3494 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  906): Killing 3258:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3258
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{427f39a8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/ActivityManager(  906): App crashed! Process: com.google.android.music:main


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  759): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2107 uid=10001 gids={50001, 3003, 1028, 1015}
I/ActivityManager(  759): Killing 1562:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
I/ActivityManager(  759): Delaying start of: ServiceRecord{42f1c160 u0 com.android.providers.calendar/.EmptyService}
,I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2134
I/ActivityManager(  759): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2150 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  759): Killing 1193:com.google.android.partnersetup/u0a11 (adj 15): empty #17
I/ActivityManager(  759): Resuming delayed broadcast
I/ActivityManager(  759): Killing 1593:com.android.vending/u0a14 (adj 15): empty #17
I/ActivityManager(  759): Delay finish: com.google.android.gm/.GmailReceiver
I/ActivityManager(  759): Resuming delayed broadcast
I/ActivityManager(  759): Delay finish: com.google.android.gm/.GmailReceiver
I/ActivityManager(  759): Resuming delayed broadcast
I/ActivityManager(  759): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  759): Displayed com.example.hello/.MainActivity: +294ms
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
I/ActivityManager(  759): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2247 uid=10011 gids={50011, 3003}
,I/ActivityManager(  759): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2262 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  759): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  759): Resuming delayed broadcast
,W/jxcore-log( 2150): Initializing JXcore engine
W/jxcore-log( 2150): JXcore engine is ready
I/ActivityManager(  759): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2278 uid=10014 gids={50014, 3003, 1028, 1015}
,W/jxcore-log( 2150): Starting JXcore engine
,I/ActivityManager(  759): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  759): Delaying start of: ServiceRecord{4279b628 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,W/jxcore-log( 2150): Platform android
W/jxcore-log( 2150): 
,W/jxcore-log( 2150): Process ARCH arm
W/jxcore-log( 2150): 
,I/jxcore-log( 2150): JXcore Cordova bridge is ready!
I/jxcore-log( 2150): 
,W/jxcore-log( 2150): JXcore engine is started
,E/jxcore-log( 2150): >> LGE-Nexus 5
E/jxcore-log( 2150): 
,I/jxcore-log( 2150): Total memory 1945137152
I/jxcore-log( 2150): 
I/jxcore-log( 2150): Free memory 914681856
I/jxcore-log( 2150): 
I/jxcore-log( 2150): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2150): 
,I/jxcore-log( 2150): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2150): 
,I/jxcore-log( 2150): userPath [ 'www' ]
I/jxcore-log( 2150): 
,I/jxcore-log( 2150): Size 1080 1776
I/jxcore-log( 2150): 
,I/jxcore-log( 2150): Screen Brightness 82
I/jxcore-log( 2150): 
,E/jxcore-log( 2150): Dummy Error Log.
E/jxcore-log( 2150): 
,I/ActivityManager(  759): Killing 1666:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/jxcore-log( 2150): getBuffer is called!!!!
I/jxcore-log( 2150): 
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2331 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,I/ActivityManager(  759): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2363 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  759): Killing 1699:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2379 uid=10035 gids={50035, 1028, 3003, 1015}
,I/ActivityManager(  759): Killing 1751:com.google.android.keep/u0a52 (adj 15): empty #17
,W/ActivityManager(  759): No permission grants found for com.quickoffice.android
,I/ActivityManager(  759): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.music/.wear.WearBroadcastReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
I/ActivityManager(  759): Killing 1771:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{42baa1b0 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  759): Resuming delayed broadcast
I/ActivityManager(  759): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{42bc1f30 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  759): Killing 1825:com.google.android.exchange/u0a37 (adj 15): empty #17
,I/ActivityManager(  759): Killing 1071:com.android.printspooler/u0a64 (adj 15): empty #17
,I/jxcore-log( 2150): ****TEST TOOK:  5025  ms ****
I/jxcore-log( 2150): 
,I/jxcore-log( 2150): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2150): 
,I/ActivityManager(  759): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  759): Killing 2150:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  759): Force removing ActivityRecord{42f27da0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  759): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  759): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2501 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/ActivityManager(  759): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  759): Resuming delayed broadcast
,I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2528 uid=10034 gids={50034}
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2547 uid=10006 gids={50006, 1028, 1015, 1023}
,I/ActivityManager(  759): Killing 1913:com.google.android.youtube/u0a71 (adj 15): empty #17
,F/ActivityManager(  759): Service ServiceRecord{42b9e3f8 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42df5a50 1913:com.google.android.youtube/u0a71} not same as in map: null
,I/ActivityManager(  759): Killing 1683:com.google.android.deskclock/u0a33 (adj 15): empty #17


```




###iOS Logs

```
Iphone5s-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B0B696EC-0947-43D4-8F4F-A2B9BC562F31/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B0B696EC-0947-43D4-8F4F-A2B9BC562F31/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1B68171A-4BEC-41BE-86B8-3527FB534667/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53778"
,(lldb)     command script import "/tmp/B0B696EC-0947-43D4-8F4F-A2B9BC562F31/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 20:48:37.298 HelloWorld[1937:2220455] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8EE23C30-237E-47FB-B3CE-23624CF4853C/Library/Cookies/Cookies.binarycookies
,2015-11-10 20:48:37.623 HelloWorld[1937:2220455] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-10 20:48:37.624 HelloWorld[1937:2220455] Multi-tasking -> Device: YES, App: YES
,2015-11-10 20:48:37.627 HelloWorld[1937:2220455] Unlimited access to network resources
,2015-11-10 20:48:37.633 HelloWorld[1937:2220455] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 20:48:41.951 HelloWorld[1937:2220455] Resetting plugins due to page load.
,2015-11-10 20:48:42.315 HelloWorld[1937:2220455] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/1B68171A-4BEC-41BE-86B8-3527FB534667/HelloWorld.app/www/index.html
,2015-11-10 20:48:42.368 HelloWorld[1937:2220455] JXcore Cordova plugin initializing
2015-11-10 20:48:42.369 HelloWorld[1937:2220583] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5s-1
Total memory 1047695360
Free memory 125394944
execPath /private/var/mobile/Containers/Bundle/Application/1B68171A-4BEC-41BE-86B8-3527FB534667/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/1B,68171A-4BEC-41BE-86B8-3527FB534667/HelloWorld.app/www/jxcore/
userPath []
2015-11-10 20:48:42.595 HelloWorld[1937:2220583] Native method ScreenInfo not found.
2015-11-10 20:48:42.595 HelloWorld[1937:2220583] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5114  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone5-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C89A7122-2AA3-4D04-9F1E-D01823CDBCF7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C89A7122-2AA3-4D04-9F1E-D01823CDBCF7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/9472B42F-54DE-4228-A5F3-B93238C951BE/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53765"
,(lldb)     command script import "/tmp/C89A7122-2AA3-4D04-9F1E-D01823CDBCF7/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 20:48:52.184 HelloWorld[1576:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-10 20:48:52.191 HelloWorld[1576:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-10 20:48:52.195 HelloWorld[1576:60b] Unlimited access to network resources
,2015-11-10 20:48:52.202 HelloWorld[1576:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 20:48:58.305 HelloWorld[1576:60b] Resetting plugins due to page load.
,2015-11-10 20:48:58.827 HelloWorld[1576:60b] Finished load of: file:///var/mobile/Applications/9472B42F-54DE-4228-A5F3-B93238C951BE/HelloWorld.app/www/index.html
,2015-11-10 20:48:58.895 HelloWorld[1576:60b] JXcore Cordova plugin initializing
,2015-11-10 20:48:58.898 HelloWorld[1576:6807] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone5-1
Total memory 1065000960
Free memory 481501184
execPath /private/var/mobile/Applications/9472B42F-54DE-4228-A5F3-B93238C951BE/HelloWorld.app/HelloWorld
process.cwd /var/mobile/Applications/9472B42F-54DE-4228-A5F3-B93238C951BE/HelloWorld.app/www/jxcore/
userPath []
,2015-11-10 20:48:59.266 HelloWorld[1576:6807] Native method ScreenInfo not found.
,2015-11-10 20:48:59.270 HelloWorld[1576:6807] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5173  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



Iphone6-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A528EC42-D55F-43F5-83D5-87B259A801B7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A528EC42-D55F-43F5-83D5-87B259A801B7/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B1628A6D-DCA1-4979-A991-32476F83C917/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53763"
,(lldb)     command script import "/tmp/A528EC42-D55F-43F5-83D5-87B259A801B7/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 20:48:28.412 HelloWorld[3013:3322227] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/583869D4-6743-4330-A8DE-0E497616B4EE/Library/Cookies/Cookies.binarycookies
,2015-11-10 20:48:28.696 HelloWorld[3013:3322227] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-10 20:48:28.697 HelloWorld[3013:3322227] Multi-tasking -> Device: YES, App: YES
,2015-11-10 20:48:28.699 HelloWorld[3013:3322227] Unlimited access to network resources
,2015-11-10 20:48:28.703 HelloWorld[3013:3322227] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 20:48:30.886 HelloWorld[3013:3322227] Resetting plugins due to page load.
,2015-11-10 20:48:31.056 HelloWorld[3013:3322227] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/B1628A6D-DCA1-4979-A991-32476F83C917/HelloWorld.app/www/index.html
,2015-11-10 20:48:31.096 HelloWorld[3013:3322227] JXcore Cordova plugin initializing
2015-11-10 20:48:31.097 HelloWorld[3013:3322307] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-Iphone6-1
Total memory 1035988992
Free memory 81367040
execPath /private/var/mobile/Containers/Bundle/Application/B1628A6D-DCA1-4979-A991-32476F83C917/HelloWorld.app/HelloWorld
process.cwd /private/var/mobile/Containers/Bundle/Application/B162,8A6D-DCA1-4979-A991-32476F83C917/HelloWorld.app/www/jxcore/
userPath []
2015-11-10 20:48:31.280 HelloWorld[3013:3322307] Native method ScreenInfo not found.
2015-11-10 20:48:31.280 HelloWorld[3013:3322307] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
****TEST TOOK:  5087  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



IpadAir2-1: 
[100%] Installed package /Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7DAFB438-4A1C-4CA9-8D7B-56588ABA5644/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7DAFB438-4A1C-4CA9-8D7B-56588ABA5644/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50242285b143d21/build_ios/platforms/ios/build/device/HelloWorld.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D0E57689-FD84-4117-A6AB-B98635C3BEBE/HelloWorld.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53762"
,(lldb)     command script import "/tmp/7DAFB438-4A1C-4CA9-8D7B-56588ABA5644/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-10 20:48:32.251 HelloWorld[1998:4348081] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DBA619C3-132B-4233-9B83-75C55E9C146D/Library/Cookies/Cookies.binarycookies
,2015-11-10 20:48:32.517 HelloWorld[1998:4348081] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-10 20:48:32.518 HelloWorld[1998:4348081] Multi-tasking -> Device: YES, App: YES
,2015-11-10 20:48:32.519 HelloWorld[1998:4348081] Unlimited access to network resources
,2015-11-10 20:48:32.524 HelloWorld[1998:4348081] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-10 20:48:36.835 HelloWorld[1998:4348081] Resetting plugins due to page load.
,2015-11-10 20:48:38.273 HelloWorld[1998:4348081] Finished load of: file:///var/mobile/Containers/Bundle/Application/D0E57689-FD84-4117-A6AB-B98635C3BEBE/HelloWorld.app/www/index.html
,2015-11-10 20:48:38.320 HelloWorld[1998:4348081] JXcore Cordova plugin initializing
,2015-11-10 20:48:38.321 HelloWorld[1998:4348266] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,>> Apple-IpadAir2-1
,Total memory 2084569088
Free memory 383631360
,execPath /private/var/mobile/Containers/Bundle/Application/D0E57689-FD84-4117-A6AB-B98635C3BEBE/HelloWorld.app/HelloWorld
,process.cwd /var/mobile/Containers/Bundle/Application/D0E57689-FD84-4117-A6AB-B98635C3BEBE/HelloWorld.app/www/jxcore/
,userPath []
,2015-11-10 20:48:38.501 HelloWorld[1998:4348266] Native method ScreenInfo not found.
2015-11-10 20:48:38.502 HelloWorld[1998:4348266] Native method ScreenBrightness not found.
Dummy Error Log.
,getBuffer is called!!!!
,Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,****TEST TOOK:  5108  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****



```

#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":20,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_50242285b143d21/serverApp/index.js',
  '{"devices":{"ios":4,"android":20,"cancel":1}}' ]

JSON { devices: { ios: 4, android: 20, cancel: 1 } }


```

